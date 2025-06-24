### Demostración Paralela: Contención vs Igualdad

#### **Caso (a):** $f(f^{-1}(B)) \subseteq B$ (siempre cierto)
| Paso | Demostración                                  | Razón Lógica                                                          |
| ---- | --------------------------------------------- | --------------------------------------------------------------------- |
| 1    | Sea $y \in f(f^{-1}(B))$                      | Supuesto inicial                                                      |
| 2    | $\exists x \in f^{-1}(B)$ tal que $f(x) = y$  | **Por definición de imagen**<br>$y \in f(A) \implies \exists x \in A$ |
| 3    | Como $x \in f^{-1}(B)$, entonces $f(x) \in B$ | **Definición de preimagen**<br>$x \in f^{-1}(B) \iff f(x) \in B$      |
| 4    | Pero $f(x) = y$, luego $y \in B$              | Sustitución directa                                                   |
| 5    | $\therefore f(f^{-1}(B)) \subseteq B$         | Conclusión final                                                      |

**No requiere sobreyectividad:** La existencia de $x$ en el paso 2 está garantizada por la definición de imagen, sin depender de propiedades de $f$.

---

#### **Caso (b):** $B \subseteq f(f^{-1}(B))$ (requiere sobreyectividad)
| Paso | Demostración                                                       | Razón Lógica                                                                 |
| ---- | ------------------------------------------------------------------ | ---------------------------------------------------------------------------- |
| 1    | Sea $y \in B$                                                      | Supuesto inicial                                                             |
| 2    | $\exists x \in X$ tal que $f(x) = y$                               | **Por sobreyectividad de $f$**<br>$\forall y \in Y, \exists x \in X: f(x)=y$ |
| 3    | Como $y \in B$ y $f(x) = y$, entonces $f(x) \in B$                 | Sustitución directa                                                          |
| 4    | Como $f(x) \in B$, entonces $x \in f^{-1}(B)$                      | **Definición de preimagen**<br>$x \in f^{-1}(B) \iff f(x) \in B$             |
| 5    | Como $x \in f^{-1}(B)$ y $f(x) = y$, entonces $y \in f(f^{-1}(B))$ | **Definición de imagen**<br>$y \in f(A) \iff \exists x \in A: f(x)=y$        |
| 6    | $\therefore B \subseteq f(f^{-1}(B))$                              | Conclusión final                                                             |

**Requiere sobreyectividad:** El paso 2 depende críticamente de que $f$ sea sobreyectiva. Sin esto, no podemos garantizar la existencia de $x$ para todo $y \in B$.

---

### Diferencia Clave: Paso 2 Comparado
$$ \begin{array}{c|c} \text{Caso (a)} & \text{Caso (b)} \\ \hline \begin{aligned} y \in f(f^{-1}(B)) \implies \\ \exists x \in \color{red}{f^{-1}(B)} \end{aligned} & \begin{aligned} y \in B \implies \\ \exists x \in \color{blue}{X} \end{aligned} \\ \text{Garantizado por definición} & \text{Solo con sobreyectividad} \\ \end{array} $$

### ¿Por qué la sobreyectividad es crucial?
- **En (a):**  
  $x$ está en $f^{-1}(B)$ por construcción:  
  $$y \in f(A) \implies x \in A \text{ con } f(x)=y \quad (A = f^{-1}(B))$$
  
- **En (b):**  
  Necesitamos "fabricar" un $x$ para cualquier $y \in B$:  
  $$y \in B \xrightarrow{\text{sobreyectividad}} \exists x \in X: f(x)=y$$
  Sin sobreyectividad, podría haber $y \in B$ sin preimagen, rompiendo la cadena.

---

### Diagrama de Flujo Lógico
```mermaid
graph TD
    subgraph Caso a[Contención Directa]
    A[y ∈ f(f⁻¹B)] --> B[∃ x ∈ f⁻¹B]
    B --> C[f(x) ∈ B]
    C --> D[y ∈ B]
    end

    subgraph Caso b[Contención Inversa]
    E[y ∈ B] --> F{¿f sobreyectiva?}
    F -->|Sí| G[∃ x ∈ X]
    F -->|No| H[Fallo]
    G --> I[x ∈ f⁻¹B]
    I --> J[y ∈ f(f⁻¹B)]
    end
```

### Conclusión Final
1. **$f(f^{-1}(B)) \subseteq B$ siempre es cierto:**  
   Porque los elementos de $f(f^{-1}(B))$ son **por construcción** imágenes de puntos que mapean a $B$:  
   $$x \in f^{-1}(B) \implies f(x) \in B \implies \text{contención}$$

2. **$B \subseteq f(f^{-1}(B))$ requiere sobreyectividad:**  
   Porque necesitamos garantizar que **todo elemento de $B$ tiene origen** en $X$:  
   $$\text{Sobreyectividad} \iff \forall y \in B, \exists x \in X: f(x)=y$$  
   Solo así podemos asegurar que $y$ proviene de algún $x \in f^{-1}(B)$.