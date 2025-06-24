Aquí tienes la explicación con fórmulas en LaTeX (usando `$` y `$$`) y el resto en Markdown:

### Conceptos preliminares  
Sea $f: X \to Y$ una función entre conjuntos, y $B \subseteq Y$ un subconjunto del codominio.  

1. **Preimagen de $B$**:  
$$f^{-1}(B) = \{ x \in X \mid f(x) \in B \}$$  

2. **Imagen de un conjunto $A \subseteq X$**:  
$$f(A) = \{ f(x) \mid x \in A \}$$  

---

### **a) $f(f^{-1}(B)) \subseteq B$ (siempre cierto)**  
**Demostración:**  
$$
\begin{align*}
\text{Sea } & y \in f(f^{-1}(B)) \\
\text{Entonces } & \exists x \in f^{-1}(B) \text{ tal que } f(x) = y \\
\text{Como } & x \in f^{-1}(B) \implies f(x) \in B \\
\text{Por tanto } & y = f(x) \in B \\
\end{align*}
$$  
Conclusión: $y \in f(f^{-1}(B)) \implies y \in B$, luego $f(f^{-1}(B)) \subseteq B$.  

**¿Por qué es subconjunto?**  
- Los elementos de $f(f^{-1}(B))$ son imágenes de puntos $x$ que **por definición** cumplen $f(x) \in B$  
- Esto garantiza que toda la imagen está contenida en $B$  
- La igualdad **no siempre** se cumple  

**Ejemplo no sobreyectivo:**  
- $X = \{1,2\},\ Y = \{a,b,c\}$  
- $f(1) = a,\ f(2) = b$  
- $B = \{a,b,c\}$  
- $f^{-1}(B) = \{1,2\}$  
- $f(f^{-1}(B)) = \{a,b\} \subsetneq \{a,b,c\} = B$  

---

### **b) Si $f$ es sobreyectiva, entonces $f(f^{-1}(B)) = B$**  
**Demostración:**  
$$
\begin{align*}
&(1)\ \text{Por (a): } f(f^{-1}(B)) \subseteq B \\
&(2)\ \text{Probemos } B \subseteq f(f^{-1}(B)): \\
&\quad \text{Sea } y \in B \\
&\quad \text{Como } f \text{ es sobreyectiva, } \exists x \in X \text{ tal que } f(x) = y \\
&\quad \text{Como } y \in B, \text{ entonces } f(x) \in B \implies x \in f^{-1}(B) \\
&\quad \text{Luego } y = f(x) \in f(f^{-1}(B)) \\
&\quad \therefore B \subseteq f(f^{-1}(B)) \\
&(3)\ \text{De (1) y (2): } f(f^{-1}(B)) = B
\end{align*}
$$  

**¿Por qué ahora es igualdad?**  
La sobreyectividad ($\forall y \in Y, \exists x \in X: f(x) = y$) garantiza que:  
- Todo elemento de $B$ tiene preimagen en $X$  
- Esa preimagen **está necesariamente en $f^{-1}(B)$**  
- Así $B$ está **completamente cubierto** por la imagen  

**Ejemplo sobreyectivo:**  
- $X = \{1,2,3\},\ Y = \{a,b\}$  
- $f(1) = a,\ f(2) = b,\ f(3) = b$  
- $B = \{a,b\}$  
- $f^{-1}(B) = \{1,2,3\}$  
- $f(f^{-1}(B)) = \{a,b\} = B$  

---

### Visualización de relaciones  
```
X: dominio           Y: codominio
● x₁                 ● y₁
● x₂ ───f───→        ● y₂
● x₃                 ● y₃

f⁻¹(B): puntos que mapean a B
f(f⁻¹(B)): imágenes de esos puntos
```
- **Sin sobreyectividad**:  
$f(f^{-1}(B))$ puede ser subconjunto propio de $B$ (ej: si $y_3$ no es imagen de ningún $x$)  

- **Con sobreyectividad**:  
Todo elemento en $B$ es imagen de algún $x \in f^{-1}(B)$ $\implies$ igualdad  

### Conclusión clave  
La relación $f(f^{-1}(B)) \subseteq B$ siempre es cierta porque:  
$$x \in f^{-1}(B) \implies f(x) \in B \implies f(x) \in B$$  
La igualdad $f(f^{-1}(B)) = B$ requiere sobreyectividad para garantizar:  
$$y \in B \implies y \in f(f^{-1}(B))$$