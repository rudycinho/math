### Respuestas detalladas a los problemas

#### **1. (a) Demostración de que la relación es de equivalencia y descripción de la clase de equivalencia**  
**Definiciones:**  
- $X$ e $Y$ conjuntos no vacíos.  
- $f: X \to Y$ una función.  
- Relación $\sim$ en $X$ definida como:  
  $$x \sim y \iff f(x) = f(y)$$  

**Demostración:**  
1. **Reflexividad:**  
   - Para todo $x \in X$, $f(x) = f(x)$.  
   - Sustituyendo en la definición: $x \sim x$.  

2. **Simetría:**  
   - Si $x \sim y$, entonces $f(x) = f(y)$.  
   - Por igualdad: $f(y) = f(x)$.  
   - Sustituyendo en la definición: $y \sim x$.  

3. **Transitividad:**  
   - Si $x \sim y$ e $y \sim z$, entonces $f(x) = f(y)$ y $f(y) = f(z)$.  
   - Por transitividad de la igualdad: $f(x) = f(z)$.  
   - Sustituyendo en la definición: $x \sim z$.  

**Clase de equivalencia de $z \in X$:**  
- Definición: $[z] = \{x \in X \mid x \sim z\}$.  
- Sustituyendo $\sim$: $[z] = \{x \in X \mid f(x) = f(z)\}$.  
- **Conclusión:** $[z] = f^{-1}(\{f(z)\})$ (preimagen de $f(z)$ bajo $f$).  

---

#### **1. (b) Inyectividad de $\tilde{f}$**  
**Definiciones:**  
- $\tilde{f}: X / \sim \to Y$ definida como $\tilde{f}([x]) = f(x)$.  

**Demostración de que $\tilde{f}$ es inyectiva:**  
1. **Bien definida:**  
   - Si $[x] = [y]$, entonces $x \sim y$.  
   - Por definición de $\sim$: $f(x) = f(y)$.  
   - Sustituyendo en $\tilde{f}$: $\tilde{f}([x]) = f(x) = f(y) = \tilde{f}([y])$.  

2. **Inyectividad:**  
   - Supongamos $\tilde{f}([x]) = \tilde{f}([y])$.  
   - Por definición de $\tilde{f}$: $f(x) = f(y)$.  
   - Por definición de $\sim$: $x \sim y$.  
   - Por definición de clase: $[x] = [y]$.  
**Conclusión:** $\tilde{f}$ es inyectiva.  

---

#### **2. Demostración de que la relación es de orden**  
**Definiciones:**  
- $R \subseteq A \times A$ y $S \subseteq B \times B$ relaciones de orden.  
- Relación $\leq$ en $A \times B$ definida como:  
  $$(a_1, b_1) \leq (a_2, b_2) \iff a_1 \mathbin{R} a_2 \quad \text{y} \quad b_1 \mathbin{S} b_2$$  

**Demostración:**  
1. **Reflexividad:**  
   - Para todo $(a,b) \in A \times B$: $a \mathbin{R} a$ (por reflexividad de $R$) y $b \mathbin{S} b$ (por reflexividad de $S$).  
   - Sustituyendo en $\leq$: $(a,b) \leq (a,b)$.  

2. **Antisimetría:**  
   - Supongamos $(a_1,b_1) \leq (a_2,b_2)$ y $(a_2,b_2) \leq (a_1,b_1)$.  
   - Por definición de $\leq$:  
     - $a_1 \mathbin{R} a_2$ y $a_2 \mathbin{R} a_1$ $\implies a_1 = a_2$ (antisimetría de $R$).  
     - $b_1 \mathbin{S} b_2$ y $b_2 \mathbin{S} b_1$ $\implies b_1 = b_2$ (antisimetría de $S$).  
   - Conclusión: $(a_1,b_1) = (a_2,b_2)$.  

3. **Transitividad:**  
   - Supongamos $(a_1,b_1) \leq (a_2,b_2)$ y $(a_2,b_2) \leq (a_3,b_3)$.  
   - Por definición de $\leq$:  
     - $a_1 \mathbin{R} a_2$ y $a_2 \mathbin{R} a_3$ $\implies a_1 \mathbin{R} a_3$ (transitividad de $R$).  
     - $b_1 \mathbin{S} b_2$ y $b_2 \mathbin{S} b_3$ $\implies b_1 \mathbin{S} b_3$ (transitividad de $S$).  
   - Conclusión: $(a_1,b_1) \leq (a_3,b_3)$.  
**Conclusión:** $\leq$ es relación de orden.  

---

#### **3. Existencia de $g$ tal que $g \circ f = \text{id}_A$**  
**Hipótesis:**  
- $f: A \to B$ inyectiva.  

**Demostración:**  
1. **Construcción de $g$:**  
   - Como $f$ es inyectiva, $f: A \to f(A)$ es biyectiva.  
   - Sea $f^{-1}: f(A) \to A$ su inversa.  
   - Si $A \neq \emptyset$, fijamos $a_0 \in A$.  
   - Definimos $g: B \to A$ como:  
     $$
     g(b) = 
     \begin{cases} 
     f^{-1}(b) & \text{si } b \in f(A) \\
     a_0 & \text{si } b \notin f(A)
     \end{cases}
     $$  

2. **Verificación de $g \circ f = \text{id}_A$:**  
   - Para todo $a \in A$:  
     - $f(a) \in f(A)$.  
     - $(g \circ f)(a) = g(f(a)) = f^{-1}(f(a)) = a$.  
   - Conclusión: $g \circ f(a) = a$ para todo $a \in A$.  
**Conclusión:** Existe $g$ tal que $g \circ f = \text{id}_A$.  

---

#### **4. Demostración de igualdad de conjuntos**  
**Definiciones:**  
- $g: X \to Y$ función.  
- $B \subseteq Y$.  
- Preimagen de $C \subseteq Y$: $g^{-1}(C) = \{x \in X \mid g(x) \in C\}$.  

**Demostración de $g^{-1}(Y \setminus B) = X \setminus g^{-1}(B)$:**  
1. **Doble contención:**  
   - Sea $x \in g^{-1}(Y \setminus B)$.  
     - Por definición: $g(x) \in Y \setminus B$.  
     - Equivalentemente: $g(x) \notin B$.  
     - Por definición de preimagen: $x \notin g^{-1}(B)$.  
     - Conclusión: $x \in X \setminus g^{-1}(B)$.  
     - Así: $g^{-1}(Y \setminus B) \subseteq X \setminus g^{-1}(B)$.  

   - Sea $x \in X \setminus g^{-1}(B)$.  
     - Por definición: $x \notin g^{-1}(B)$.  
     - Equivalentemente: $g(x) \notin B$.  
     - Como $g(x) \in Y$: $g(x) \in Y \setminus B$.  
     - Por definición: $x \in g^{-1}(Y \setminus B)$.  
     - Así: $X \setminus g^{-1}(B) \subseteq g^{-1}(Y \setminus B)$.  

2. **Igualdad:**  
   - Ambas contenciones prueban que:  
     $$g^{-1}(Y \setminus B) = X \setminus g^{-1}(B).$$