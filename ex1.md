### Examen de Álgebra (Matemáticas Puras) 
---
#### **Lógica**  
1. **Simbolice y demuestre:**  
   "Si $x \neq 0$ y $y = 1$, entonces $z = 2$. Si $z = 2$ implica $w = 3$, entonces $x = 0$. Por tanto, $w \neq 3$."  

2. **Determine el valor de verdad (sin tabla):**  
   Se sabe que $(p \to q)$ es falsa, $(r \land s)$ es verdadera, $(\neg r \lor t)$ es falsa, y $(u \to \neg s)$ es verdadera. Calcule el valor de:  
   $$
   [(r \to t) \land (s \lor \neg u)] \leftrightarrow (\neg p \to u).
   $$  

3. **Negación de una definición:**  
   La continuidad de $f$ en $a$ se define como:  
   $$
   (\forall \varepsilon > 0)(\exists \delta > 0)(\forall x)(|x - a| < \delta \implies |f(x) - f(a)| < \varepsilon).  
   $$  
   Escriba su negación.  

---

#### **Teoría de Conjuntos**  
1. **Demuestre:**  
   $$
   (A \times B) \setminus (C \times D) = [(A \setminus C) \times B] \cup [A \times (B \setminus D)] \cup [(A \cap C) \times (B \setminus D)].
   $$  

2. **Calcule:**  
   Considere $Z_j = (-\infty, j] \cap [j, \infty)$ para $j \in \mathbb{N}$. Determine $\bigcup_{j \in \mathbb{N}} Z_j$ y $\left( \bigcap_{j \in \mathbb{N}} Z_j \right)^c$.  

3. **Simplifique:**  
   $$
   \left[ (A \triangle B) \cap (A \cup C)^c \right] \cup \left[ (B \setminus C) \triangle (A \cap B) \right],
   $$  
   donde $A \triangle B = (A \setminus B) \cup (B \setminus A)$.  

---

#### **Funciones**  
1. **Sea $f: X \to Y$:**  
   - Demuestre que si $A \subseteq X$, entonces $f^{-1}[f(A)] \supseteq A$.  
   - Si $f$ es inyectiva, pruebe que $f^{-1}[f(A)] = A$ para todo $A \subseteq X$.  

2. **Relación de equivalencia:**  
   Dada $f: X \to Y$, defina la relación $x \sim y \iff f(x) = f(y)$.  
   - Demuestre que $\sim$ es de equivalencia.  
   - Construya $\bar{f}: X/{\sim} \to \text{Im}(f)$ con $\bar{f}([x]) = f(x)$. ¿Es $\bar{f}$ biyectiva? Justifique.  

3. **Inyectividad y función inversa:**  
   Sea $f: A \to B$ inyectiva. Demuestre que existe $g: B \to A$ tal que $g \circ f = \text{id}_A$.  

---

#### **Relaciones de Equivalencia**  
1. **En $\mathbb{Z} \times \mathbb{Z}$** definimos $(a,b) \sim (c,d) \iff a - b = c - d$.  
   - Demuestre que $\sim$ es relación de equivalencia.  
   - Describa $[(3,1)]$, $[(0,0)]$, y $[(4,6)]$.  
   - Defina $[(a,b)] + [(c,d)] = [(a+c, b+d)]$. Calcule $[(3,1)] + [(1,2)]$ y analice la estructura algebraica.  

---

#### **Órdenes Parciales**  
1. **Diagrama de Hasse:**  
   Sea $X = \{1,2,3\}$ y $\mathcal{P}(X)$ el conjunto potencia. Ordenado por inclusión:  
   - Dibuje el diagrama de Hasse.  
   - Para $Z = \{ \{1,2\}, \{2,3\} \}$, encuentre $\sup Z$ e $\inf Z$ si existen.  

2. **Orden lexicográfico:**  
   Sean $(A, \leq_A)$ y $(B, \leq_B)$ órdenes parciales. En $A \times B$ definimos:  
   $$
   (a_1, b_1) \preceq (a_2, b_2) \iff (a_1 <_A a_2) \lor (a_1 = a_2 \land b_1 \leq_B b_2).
   $$  
   Demuestre que $\preceq$ es un orden parcial.  

---

#### **Números Complejos**  
1. **Descripción geométrica:**  
   Grafique el conjunto $\{ z \in \mathbb{C} : |z - 1| + |z + 1| = 4 \}$. Identifique la figura.  

2. **Forma binómica:**  
   Calcule:  
   - $\log(1 + i)$ (valor principal).  
   - $(1 + i)^{i}$.  

3. **Demuestre:**  
   $$
   \left| \frac{z - a}{1 - \bar{a}z} \right| = 1 \quad \text{si} \quad |z| = 1 \quad \text{y} \quad |a| < 1.
   $$  

---

#### **Inducción Matemática**  
1. **Demuestre para $n \geq 1$:**  
   $$
   \sum_{k=1}^{n} k \cdot k! = (n+1)! - 1.
   $$  

2. **Desigualdad:**  
   Demuestre que para $n \geq 2$:  
   $$
   \left(1 + \frac{1}{n}\right)^n < 4.
   $$  

---

#### **Combinatoria**  
1. **Calcule:**  
   $$
   \sum_{k=0}^{n} 3^k \binom{n}{k}.
   $$  

---

#### **Teoría de Números**  
1. **Demuestre:**  
   Si $d = \gcd(a,b)$ y $d \mid c$, entonces $\gcd(a, b, c) = \gcd(d, c)$.  

2. **Axiomas de Peano:**  
   Demuestre la asociatividad de la multiplicación:  
   $$
   \forall m,n,p \in \mathbb{N}, \quad (m \cdot n) \cdot p = m \cdot (n \cdot p).
   $$  

---
