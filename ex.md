### Nuevo Examen de Álgebra

#### Lógica
1. Simbolice la siguiente inferencia y demuéstrela:  
   "Si $p$ o $q$, entonces $r$. Si $r$, entonces $s$. $p$ o $q$. Por consiguiente, $s$."

2. Se sabe que $(a \to b)$ es verdadera, $(c \land d)$ es falsa, $(a \lor c)$ es verdadera, y $(b \lor d)$ es falsa. Determine (sin tabla de verdad) el valor de verdad de:  
   $[(a \land c) \to (d \lor b)] \leftrightarrow (\neg a \land d)$.

#### Teoría de Conjuntos
1. Demuestre que $(A \setminus B) \times C = (A \times C) \setminus (B \times C)$.

2. Considere la familia de conjuntos $\{E_n\}_{n \in \mathbb{N}^+}$ donde $E_n = \left[-\frac{1}{n}, \frac{1}{n}\right]$. Calcule $\left(\bigcap_{n \in \mathbb{N}^+} E_n\right)^c$.

3. Simplifique:  
   $\left[(A \cup B) \cap (C \cup B)\right] \setminus (A \cap C)$.

#### Funciones
1. Sea $f: X \to Y$ una función. Demuestre:  
   - $f(A \cap B) \subseteq f(A) \cap f(B)$ para todo $A, B \subseteq X$.  
   - Si $f$ es inyectiva, entonces $f(A \cap B) = f(A) \cap f(B)$.

2. Sean $f: A \to B$ y $g: B \to C$ funciones. Demuestre:  
   - Si $g \circ f$ es inyectiva, entonces $f$ es inyectiva.  
   - Si $g \circ f$ es sobreyectiva, entonces $g$ es sobreyectiva.

3. Sea $f: A \to B$ sobreyectiva. Demuestre que existe $g: B \to A$ tal que $f \circ g = \operatorname{id}_B$.

#### Relaciones de Equivalencia
1. En $\mathbb{N}^+ \times \mathbb{N}^+$ definimos $(a, b) \sim (c, d) \Leftrightarrow ad = bc$.  
   - Demuestre que $\sim$ es relación de equivalencia.  
   - Calcule $[(1,2)]$ y $[(3,6)]$. ¿Son iguales?  
   - Defina $[(a,b)] \cdot [(c,d)] = [(ac, bd)]$. Calcule $[(2,3)] \cdot [(3,2)]$ y $[(1,2)] \cdot [(2,1)]$.

#### Órdenes Parciales
1. Sea $P = \{1,2,3,4,6,12\}$ con orden $a \preceq b \Leftrightarrow a \mid b$ ($a$ divide a $b$).  
   - Dibuje el diagrama de Hasse.  
   - Identifique elementos minimales, maximales, mínimo y máximo (si existen).

2. Sean $R \subset A^2$ y $S \subset B^2$ relaciones de orden. En $A \times B$ definimos $(a_1, b_1) \ll (a_2, b_2) \Leftrightarrow a_1 R a_2 \land b_1 S b_2$. Demuestre que $\ll$ es relación de orden.

3. Sea $X = \{a,b\}$, $\mathcal{W} = 2^X \setminus \{X\} = \{\emptyset, \{a\}, \{b\}\}$ con orden $A \preceq B \Leftrightarrow A \supseteq B$.  
   - Dibuje el diagrama de Hasse.  
   - Identifique elementos minimales y maximales.

#### Números Complejos
1. Describa geométricamente $\{z \in \mathbb{C} : \operatorname{Im}(z^2) = 1\}$ y bosqueje su gráfica en $\mathbb{R}^2$.

2. Exprese en forma $x + iy$:  
   - $\log(1 - i\sqrt{3})$ (valor principal).  
   - $i^{\log i}$ (valor principal).

#### Inducción Matemática
1. Demuestre por inducción: Para todo entero $n \geq 4$, $n! > 2^n$.

2. Demuestre por inducción:  
   $\sum_{k=1}^n k^2 = \frac{n(n+1)(2n+1)}{6}$ para todo $n \in \mathbb{N}$.

#### Combinatoria
1. Calcule $\sum_{k=0}^n \binom{n}{k} 3^k$.

#### Teoría de Números
1. Demuestre: Si $\gcd(a,b) = 1$ y $\gcd(a,c) = 1$, entonces $\gcd(a, bc) = 1$.

2. En axiomas de Peano, demuestre: Para todo $m, n, p \in \mathbb{N}$,  
   $m + (n + p) = (m + n) + p$ (asociatividad de la suma).

---

### Notas:
- Todas las preguntas tienen dificultad similar al examen anterior.
- Incluye demostraciones, simplificaciones, cálculos y aplicaciones teóricas.
- Las soluciones requieren precisión y rigor matemático.