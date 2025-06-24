Aquí tienes una demostración paralela en formato de tabla, explicando por qué en un caso no se requiere sobreyectividad y en el otro sí:

### Demostración Paralela: Contención vs Igualdad

| Paso | **Caso (a):** $f(f^{-1}(B)) \subseteq B$<br>(siempre cierto) | **Caso (b):** $B \subseteq f(f^{-1}(B))$<br>(requiere sobreyectividad) |
|------|---------------------------------------------------------------|-----------------------------------------------------------------------|
| 1.   | Sea $y \in f(f^{-1}(B))$ | Sea $y \in B$ |
| 2.   | $\exists x \in f^{-1}(B)$ tal que $f(x) = y$<br>*(Por definición de imagen)* | $\exists x \in X$ tal que $f(x) = y$<br>***(Requiere $f$ sobreyectiva)*** |
| 3.   | Como $x \in f^{-1}(B)$, entonces $f(x) \in B$<br>*(Def. preimagen)* | Como $y \in B$ y $f(x) = y$, entonces $f(x) \in B$ |
| 4.   | Pero $f(x) = y$, luego $y \in B$ | Como $f(x) \in B$, entonces $x \in f^{-1}(B)$<br>*(Def. preimagen)* |
| 5.   | ∴ $y \in B$ | Como $x \in f^{-1}(B)$ y $f(x) = y$, entonces $y \in f(f^{-1}(B))$<br>*(Def. imagen)* |
| Conclusión | $f(f^{-1}(B)) \subseteq B$ | $B \subseteq f(f^{-1}(B))$ |

### Análisis de la Diferencia Clave

**Paso 2 - Existencia de $x$:**
```math
\begin{array}{c|c}
\text{Caso (a)} & \text{Caso (b)} \\
\hline
\begin{array}{l}
y \in f(f^{-1}(B)) \implies \\ 
\exists x \in \color{red}{f^{-1}(B)} \text{ con } f(x)=y \\
\text{(Esto viene de la definición} \\
\text{de imagen de un conjunto)}
\end{array} &
\begin{array}{l}
y \in B \implies \\
\exists x \in \color{blue}{X} \text{ con } f(x)=y \\
\text{(Esto SOLO se garantiza si} \\
\text{$f$ es sobreyectiva)}
\end{array}
\end{array}
```

**Por qué la sobreyectividad es crucial en (b):**
- En (a) la existencia de $x$ está **garantizada por construcción**:  
  $y \in f(A)$ siempre implica $\exists x \in A$ con $f(x)=y$ (donde $A = f^{-1}(B)$)
  
- En (b) necesitamos conectar $y \in B$ con algún $x \in X$:  
  $$y \in B \xrightarrow{\text{¿?}} \exists x \in X: f(x)=y$$
  Esto solo es cierto para todo $y \in B$ si $f$ es sobreyectiva.

### Diagrama de Dependencias
```mermaid
graph LR
    subgraph Caso a
    A[y ∈ f(f⁻¹B)] --> B[∃ x ∈ f⁻¹B]
    B --> C[f(x)∈B]
    C --> D[y∈B]
    end
    
    subgraph Caso b
    E[y∈B] --> F[∃ x∈X?]
    F -->|Sobreyectiva| G[f(x)=y]
    G --> H[x∈f⁻¹B]
    H --> I[y∈f(f⁻¹B)]
    end
```

### Conclusión
1. **En (a):**  
   La relación $x \in f^{-1}(B) \implies f(x) \in B$ es **directa por definición de preimagen**, por eso no requiere condiciones adicionales.

2. **En (b):**  
   La relación $y \in B \implies \exists x \in X: f(x)=y$ es **justo la definición de sobreyectividad** cuando $B \subseteq Y$. Sin esta propiedad, podrían existir elementos en $B$ que no son imagen de ningún $x$, rompiendo la cadena lógica.

**En esencia:**  
La sobreyectividad es la condición que permite "invertir" la contención al garantizar que todo elemento de $B$ proviene de algún elemento en el dominio.