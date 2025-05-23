# Límites en Análisis Real: Explicación Detallada y Práctica

---

## 1. **Concepto Intuitivo de Límite**
El límite de una función $f(x)$ cuando $x$ tiende a $a$ es el valor $L$ al que se aproxima $f(x)$ a medida que $x$ se acerca a $a$, sin importar el valor de $f(a)$.

**Ejemplo intuitivo**:
- Para $f(x) = 3x$, cuando $x \to 5$, $f(x) \to 15$.  
- Gráficamente, la función se "acerca" a 15 incluso si $x$ no es exactamente 5.

---

## 2. **Definición Formal (ε-δ)**
$$
\lim_{x \to a} f(x) = L \iff \forall \varepsilon > 0, \exists \delta > 0 \text{ tal que } 0 < |x - a| < \delta \implies |f(x) - L| < \varepsilon.
$$

**Desglose**:
- **ε (épsilon)**: Controla qué tan cerca queremos que $f(x)$ esté de $L$.
- **δ (delta)**: Determina qué tan cerca debe estar $x$ de $a$ para cumplir lo anterior.
- **Relación**: Primero elegimos ε, luego hallamos δ en función de ε.

---

## 3. **Cómo Aplicar la Definición ε-δ: Paso a Paso**

### **Ejemplo 1: Función Lineal**  
Demostrar que $\lim_{x \to 5} 3x = 15$.

1. **Planteamiento**:
   $$
   |3x - 15| < \varepsilon \implies 3|x - 5| < \varepsilon \implies |x - 5| < \frac{\varepsilon}{3}.
   $$
2. **Solución**:
   - Dado cualquier $\varepsilon > 0$, elegimos $\delta = \frac{\varepsilon}{3}$.
   - Si $0 < |x - 5| < \delta$, entonces $|3x - 15| < 3 \cdot \frac{\varepsilon}{3} = \varepsilon$.

---

### **Ejemplo 2: Función Cuadrática**  
Demostrar que $\lim_{x \to 3} x^2 = 9$.

1. **Factorización**:
   $$
   |x^2 - 9| = |x - 3||x + 3|.
   $$
2. **Acotar $|x + 3|$**:
   - Si $|x - 3| < 1$, entonces $2 < x < 4$, luego $|x + 3| < 7$.
3. **Elección de δ**:
   - $\delta = \min\left(1, \frac{\varepsilon}{7}\right)$.
   - Si $|x - 3| < \delta$, entonces $|x^2 - 9| < 7 \cdot \frac{\varepsilon}{7} = \varepsilon$.

---

## 4. **Teoremas Clave**

### **Teorema 1: Unicidad del Límite**
Si $\lim_{x \to a} f(x) = L$ y $\lim_{x \to a} f(x) = M$, entonces $L = M$.

**Demostración**:
1. Supongamos $L \neq M$.
2. Sea $\varepsilon = \frac{|L - M|}{2}$.
3. Existirán $\delta_1$ y $\delta_2$ tales que:
   - $|f(x) - L| < \varepsilon$ si $0 < |x - a| < \delta_1$.
   - $|f(x) - M| < \varepsilon$ si $0 < |x - a| < \delta_2$.
4. Para $\delta = \min(\delta_1, \delta_2)$, llegamos a una contradicción:
   $$
   |L - M| \leq |f(x) - L| + |f(x) - M| < \varepsilon + \varepsilon = |L - M|.
   $$

---

### **Teorema 2: Álgebra de Límites**
Si $\lim_{x \to a} f(x) = L$ y $\lim_{x \to a} g(x) = M$, entonces:
1. $\lim_{x \to a} [f(x) + g(x)] = L + M$.
2. $\lim_{x \to a} [f(x) \cdot g(x)] = L \cdot M$.
3. Si $M \neq 0$, $\lim_{x \to a} \frac{1}{g(x)} = \frac{1}{M}$.

**Ejemplo de aplicación**:
$$
\lim_{x \to 2} \frac{x^3 - 8}{x - 2} = \lim_{x \to 2} (x^2 + 2x + 4) = 12.
$$
- **Paso 1**: Factorizar $x^3 - 8 = (x - 2)(x^2 + 2x + 4)$.
- **Paso 2**: Simplificar y aplicar el límite.

---

## 5. **Casos Especiales**

### **Límites Laterales**
- **Límite por la derecha**:
  $$
  \lim_{x \to a^+} f(x) = L \iff \forall \varepsilon > 0, \exists \delta > 0 \text{ tal que } 0 < x - a < \delta \implies |f(x) - L| < \varepsilon.
  $$
- **Límite por la izquierda**:
  $$
  \lim_{x \to a^-} f(x) = L \iff \forall \varepsilon > 0, \exists \delta > 0 \text{ tal que } 0 < a - x < \delta \implies |f(x) - L| < \varepsilon.
  $$

**Ejemplo**:
Para $f(x) = \begin{cases} -1, & x < 0 \\ 1, & x > 0 \end{cases}$:
- $\lim_{x \to 0^-} f(x) = -1$.
- $\lim_{x \to 0^+} f(x) = 1$.
- $\lim_{x \to 0} f(x)$ no existe.

---

### **Límites en el Infinito**
$$
\lim_{x \to \infty} f(x) = L \iff \forall \varepsilon > 0, \exists N > 0 \text{ tal que } x > N \implies |f(x) - L| < \varepsilon.
$$

**Ejemplo**:
$$
\lim_{x \to \infty} \frac{1}{x} = 0.
$$
- Para $\varepsilon > 0$, elegir $N = \frac{1}{\varepsilon}$.
- Si $x > N$, entonces $\left|\frac{1}{x} - 0\right| < \varepsilon$.

---

## 6. **Estrategias para Calcular Límites**

### **Método 1: Sustitución Directa**
- Si $f(x)$ es continua en $a$, entonces $\lim_{x \to a} f(x) = f(a)$.
- **Ejemplo**: $\lim_{x \to 2} (3x + 1) = 7$.

### **Método 2: Factorización**
- Útil para formas indeterminadas $\frac{0}{0}$.
- **Ejemplo**:
  $$
  \lim_{x \to 1} \frac{x^2 - 1}{x - 1} = \lim_{x \to 1} (x + 1) = 2.
  $$

### **Método 3: Racionalización**
- Para límites con raíces.
- **Ejemplo**:
  $$
  \lim_{x \to 0} \frac{\sqrt{a + x} - \sqrt{a}}{x} = \lim_{x \to 0} \frac{1}{\sqrt{a + x} + \sqrt{a}} = \frac{1}{2\sqrt{a}}.
  $$

---

## 7. **Problemas Resueltos**

### **Problema 1**:
Calcular $\lim_{x \to 0} \frac{\sqrt{1 - x^2} - 1}{x^2}$.

**Solución**:
1. Racionalizar:
   $$
   \frac{\sqrt{1 - x^2} - 1}{x^2} \cdot \frac{\sqrt{1 - x^2} + 1}{\sqrt{1 - x^2} + 1} = \frac{-x^2}{x^2(\sqrt{1 - x^2} + 1)}.
   $$
2. Simplificar:
   $$
   \lim_{x \to 0} \frac{-1}{\sqrt{1 - x^2} + 1} = -\frac{1}{2}.
   $$

---

## 8. **Visualización Gráfica**
- **Gráfica de $f(x) = x \sin(1/x)$**:
  - Oscila entre $-x$ y $x$, pero $\lim_{x \to 0} x \sin(1/x) = 0$.
  - La función está acotada por $y = |x|$, que tiende a 0.

---

## 9. **Errores Comunes y Consejos**
- **Error**: Ignorar la restricción $0 < |x - a| < \delta$.  
  **Solución**: No confundir el valor en $a$ con el límite.
- **Consejo**: Siempre verificar si la función es continua o requiere manipulación algebraica.

---

## 10. **Referencias Cruzadas**
- **Continuidad**: $f$ es continua en $a$ si $\lim_{x \to a} f(x) = f(a)$.
- **Derivadas**: Se definen usando límites: $f'(a) = \lim_{h \to 0} \frac{f(a + h) - f(a)}{h}$.

---
