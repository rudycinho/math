### Demostración Paralela

| **Paso** | **Caso (a):** $f(f^{-1}(B)) \subseteq B$ (siempre) | **Caso (b):** $B \subseteq f(f^{-1}(B))$ (solo con sobreyectividad) |
|----------|----------------------------------------------------|--------------------------------------------------------------------|
| **1**    | Sea $y \in f(f^{-1}(B))$                          | Sea $y \in B$                                                     |
| **2**    | $\exists x \in f^{-1}(B)$ tal que $f(x) = y$      | $\exists x \in X$ tal que $f(x) = y$                              |
| **3**    | Como $x \in f^{-1}(B)$, entonces $f(x) \in B$     | Como $y \in B$ y $f(x) = y$, entonces $f(x) \in B$               |
| **4**    | Pero $f(x) = y$, luego $y \in B$                  | Entonces $x \in f^{-1}(B)$                                        |
| **5**    | $\therefore$ Conclusión: $y \in B$                | Como $x \in f^{-1}(B)$ y $f(x)=y$, entonces $y \in f(f^{-1}(B))$ |
| **Final**| $f(f^{-1}(B)) \subseteq B$                        | $B \subseteq f(f^{-1}(B))$                                       |

---

### Diferencia Fundamental
La diferencia crítica está en el **paso 2**:
- **En (a):**  
  La existencia de $x \in f^{-1}(B)$ está garantizada por la **definición de imagen** ($y \in f(A) \implies \exists x \in A$).  
  *No requiere ninguna propiedad de $f$.*

- **En (b):**  
  La existencia de $x \in X$ requiere **sobreyectividad** ($\forall y \in Y, \exists x \in X: f(x)=y$).  
  Sin ella, podría haber $y \in B$ sin preimagen, rompiendo la cadena lógica.

> **Esencia:**  
> - (a) Es un resultado directo de las definiciones (imagen → preimagen → pertenencia).  
> - (b) Necesita sobreyectividad para "retroceder" de $B$ al dominio ($B \to X \to f^{-1}(B)$).