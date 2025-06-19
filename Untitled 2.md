A continuación, se enumeran los principales teoremas y definiciones sobre integrales en el libro *Cálculo* de Spivak, utilizando notación matemática en formato LaTeX con `$` para ecuaciones en línea y `$$` para ecuaciones centradas, según lo solicitado.

---

### **Definiciones clave:**
1. **Partición de un intervalo:**  
   Una partición de $[a, b]$ es un conjunto finito $P = \{t_0, t_1, \dots, t_n\}$ tal que:  
   $$a = t_0 < t_1 < \dots < t_n = b.$$

2. **Suma inferior y suma superior:**  
   Para $f$ acotada en $[a, b]$ y una partición $P$:  
   - **Suma inferior:** $L(f, P) = \sum_{i=1}^n m_i (t_i - t_{i-1})$, donde $m_i = \inf\{f(x) : t_{i-1} \leq x \leq t_i\}$.  
   - **Suma superior:** $U(f, P) = \sum_{i=1}^n M_i (t_i - t_{i-1})$, donde $M_i = \sup\{f(x) : t_{i-1} \leq x \leq t_i\}$.

3. **Integral inferior e integral superior:**  
   - **Integral inferior:** $\underline{\int_a^b} f = \sup\{L(f, P) : P \text{ es partición de } [a, b]\}$.  
   - **Integral superior:** $\overline{\int_a^b} f = \inf\{U(f, P) : P \text{ es partición de } [a, b]\}$.

4. **Función integrable:**  
   $f$ es integrable en $[a, b]$ si $\underline{\int_a^b} f = \overline{\int_a^b} f$. En tal caso, la integral se define como:  
   $$\int_a^b f = \underline{\int_a^b} f = \overline{\int_a^b} f.$$

---

### **Teoremas principales:**
1. **Criterio de integrabilidad:**  
   $f$ acotada en $[a, b]$ es integrable si y solo si para todo $\epsilon > 0$ existe una partición $P$ tal que:  
   $$U(f, P) - L(f, P) < \epsilon.$$

2. **Funciones continuas son integrables:**  
   Si $f$ es continua en $[a, b]$, entonces $f$ es integrable en $[a, b]$.

3. **Propiedades de la integral:**  
   Si $f$ y $g$ son integrables en $[a, b]$ y $c$ es constante:  
   - *Linealidad:* $\int_a^b (f + g) = \int_a^b f + \int_a^b g$ y $\int_a^b c \cdot f = c \cdot \int_a^b f$.  
   - *Monotonía:* Si $f(x) \leq g(x)$ para todo $x \in [a, b]$, entonces $\int_a^b f \leq \int_a^b g$.  
   - *Aditividad:* Si $a < c < b$, entonces $\int_a^b f = \int_a^c f + \int_c^b f$.

4. **Teorema Fundamental del Cálculo (Parte 1):**  
   Sea $f$ integrable en $[a, b]$ y continua en $c \in [a, b]$. Si $F(x) = \int_a^x f$, entonces:  
   $$F'(c) = f(c).$$

5. **Teorema Fundamental del Cálculo (Parte 2):**  
   Si $f$ es integrable en $[a, b]$ y $f = g'$ para alguna función $g$, entonces:  
   $$\int_a^b f = g(b) - g(a).$$

6. **Regla de sustitución:**  
   Sea $u = g(x)$ con $g'$ continua en $[c, d]$, y $f$ continua en $g([c, d])$. Entonces:  
   $$\int_{g(c)}^{g(d)} f(u)  du = \int_c^d f(g(x)) g'(x)  dx.$$

7. **Integración por partes:**  
   Si $f', g'$ son continuas en $[a, b]$, entonces:  
   $$\int_a^b f g' = f(b)g(b) - f(a)g(a) - \int_a^b f' g.$$

8. **Integrabilidad de funciones monótonas:**  
   Si $f$ es monótona en $[a, b]$, entonces $f$ es integrable en $[a, b]$.

---

### **Otros resultados relevantes:**
- **Lema para sumas superiores e inferiores:**  
  Para dos particiones $P_1$ y $P_2$ de $[a, b]$:  
  $$L(f, P_1) \leq U(f, P_2).$$

- **Teorema del valor medio para integrales:**  
  Si $f$ es continua en $[a, b]$, existe $c \in [a, b]$ tal que:  
  $$\int_a^b f = f(c) (b - a).$$

---

Estos conceptos forman la base del análisis de integrales en el texto de Spivak, destacando rigurosidad en definiciones y demostraciones.