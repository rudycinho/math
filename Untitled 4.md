**Demostraciones rigurosas con notación matemática adecuada:**

**a) $A \subseteq f^{-1}(f(A))$**  
1. Sea $x \in A$ arbitrario.  
2. Por definición de imagen: $f(x) \in f(A)$.  
3. Por definición de preimagen: $f^{-1}(f(A)) = \{ z \in X \mid f(z) \in f(A) \}$.  
4. Como $f(x) \in f(A)$, entonces $x \in f^{-1}(f(A))$.  
5. ∴ $A \subseteq f^{-1}(f(A))$.  

**b) $f[f^{-1}(B)] \subseteq B$**  
1. Sea $b \in f[f^{-1}(B)]$ arbitrario.  
2. ∃ $x \in f^{-1}(B)$ tal que $f(x) = b$.  
3. Como $x \in f^{-1}(B)$, entonces $f(x) \in B$.  
4. Luego $b = f(x) \in B$.  
5. ∴ $f[f^{-1}(B)] \subseteq B$.  

**c) $f(X)-f(A) \subseteq f(X-A)$**  
1. Sea $c \in f(X)-f(A)$ arbitrario.  
2. Entonces $c \in f(X)$ y $c \notin f(A)$.  
3. ∃ $x \in X$ tal que $f(x) = c$ (por $c \in f(X)$).  
4. Si $x \in A$, entonces $c = f(x) \in f(A)$ (contradice $c \notin f(A)$).  
5. Luego $x \notin A$ ⇒ $x \in X-A$.  
6. Como $f(x) = c$ y $x \in X-A$, entonces $c \in f(X-A)$.  
7. ∴ $f(X)-f(A) \subseteq f(X-A)$.  

**d) $f^{-1}(Y - B) = X - f^{-1}(B)$**  
*(Demostramos igualdad por doble contención)*  
- **$\subseteq$):**  
  1. Sea $x \in f^{-1}(Y - B)$.  
  2. $f(x) \in Y - B$ ⇒ $f(x) \notin B$.  
  3. $x \notin f^{-1}(B)$ ⇒ $x \in X - f^{-1}(B)$.  
- **$\supseteq$):**  
  1. Sea $x \in X - f^{-1}(B)$.  
  2. $x \notin f^{-1}(B)$ ⇒ $f(x) \notin B$.  
  3. Como $f(x) \in Y$, entonces $f(x) \in Y - B$.  
  4. Luego $x \in f^{-1}(Y - B)$.  
∴ $f^{-1}(Y - B) = X - f^{-1}(B)$.  

**e) $f(A \cap f^{-1}(B)) = f(A) \cap B$**  
*(Demostramos igualdad por doble contención)*  
- **$\subseteq$):**  
  1. Sea $d \in f(A \cap f^{-1}(B))$.  
  2. ∃ $x \in A \cap f^{-1}(B)$ con $f(x) = d$.  
  3. Como $x \in A$, entonces $d \in f(A)$.  
  4. Como $x \in f^{-1}(B)$, entonces $d \in B$.  
  5. Luego $d \in f(A) \cap B$.  
- **$\supseteq$):**  
  1. Sea $d \in f(A) \cap B$.  
  2. $d \in f(A)$ ⇒ ∃ $a \in A$ con $f(a) = d$.  
  3. $d \in B$ ⇒ $a \in f^{-1}(B)$.  
  4. Como $a \in A$ y $a \in f^{-1}(B)$, entonces $a \in A \cap f^{-1}(B)$.  
  5. Luego $d = f(a) \in f(A \cap f^{-1}(B))$.  
∴ $f(A \cap f^{-1}(B)) = f(A) \cap B$.  

---

**Observaciones sobre igualdades estrictas:**  
- **a)** La igualdad $A = f^{-1}(f(A))$ requiere $f$ inyectiva.  
- **b)** La igualdad $f[f^{-1}(B)] = B$ requiere $f$ sobreyectiva en $B$.  
- **c)** La igualdad $f(X)-f(A) = f(X-A)$ requiere $f$ inyectiva.  
- **d)** y **e)** Siempre son igualdades (no requieren condiciones adicionales).