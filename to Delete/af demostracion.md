
**Problema**: Sean $a, b, c, d, e, f$ números reales con las siguientes propiedades:  
1. $f(a - b + c - d + e) < 0$  
2. $a(b - c + d - e + f) < 0$ 
Demostrar que $af < 0$, usando **reducción al absurdo**.

---

**Demostración**:  
Supongamos lo contrario, es decir, que $af \geq 0$. Esto implica dos casos posibles:  
- **Caso 1**: $a > 0$ y $f > 0$ (ambos positivos).  
- **Caso 2**: $a < 0$ y $f < 0$ (ambos negativos).  

Analicemos ambos casos:

---

**Caso 1: $a > 0$ y $f > 0$**  
1. De la primera desigualdad $f(a - b + c - d + e) < 0$:  
   Como $f > 0$, el término entre paréntesis debe ser negativo:  
   $$
   a - b + c - d + e < 0 \quad \text{(Llamemos a esto \(X < 0\))}.
   $$

2. De la segunda desigualdad $a(b - c + d - e + f) < 0$:  
   Como $a > 0$, el término entre paréntesis debe ser negativo:  
   $$
   b - c + d - e + f < 0 \quad \text{(Llamemos a esto \(Y < 0\))}.
   $$

3. Sumando \(X + Y\):  
   $$
   (a - b + c - d + e) + (b - c + d - e + f) = a + f.
   $$ 
   Según nuestras hipótesis, $X < 0$ y $Y < 0$, por lo que su suma debería ser negativa. Sin embargo:  
   $$
   X + Y = a + f > 0 \quad (\text{ya que \(a > 0\) y \(f > 0\)}).
   $$ 
   Esto es una **contradicción**, porque la suma de dos números negativos no puede ser positiva.

---

**Caso 2: $a < 0$ y $f < 0$**  
1. De la primera desigualdad $f(a - b + c - d + e) < 0$:  
   Como $f < 0$, el término entre paréntesis debe ser positivo:  
   $$
   a - b + c - d + e > 0 \quad \text{(Llamemos a esto \(X > 0\))}.
   $$

2. De la segunda desigualdad $a(b - c + d - e + f) < 0$:  
   Como $a < 0$, el término entre paréntesis debe ser positivo:  
   $$
   b - c + d - e + f > 0 \quad \text{(Llamemos a esto \(Y > 0\))}.
   $$

3. Sumando $X + Y$:  
   $$
   (a - b + c - d + e) + (b - c + d - e + f) = a + f.
   $$
   Según nuestras hipótesis, \(X > 0\) y \(Y > 0\), por lo que su suma debería ser positiva. Sin embargo:  
   $$
   X + Y = a + f < 0 \quad (\text{ya que \(a < 0\) y \(f < 0\)}).
   $$
   Esto es otra **contradicción**, porque la suma de dos números positivos no puede ser negativa.

---

**Conclusión**: Ambos casos llevan a contradicciones. Por lo tanto, nuestra suposición inicial (\(af \geq 0\)) es falsa.  
$$
\boxed{af < 0}
$$