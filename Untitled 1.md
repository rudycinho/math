### Problema 1

#### (i) $f(x) = x^3 - x^2 - 8x + 1$ en $[-2, 2]$
- Derivada: $f'(x) = 3x^2 - 2x - 8$
- Puntos críticos: $3x^2 - 2x - 8 = 0$ → $x = 2$, $x = -\frac{4}{3}$
- Valores:
  - $f(-2) = (-2)^3 - (-2)^2 - 8(-2) + 1 = -8 - 4 + 16 + 1 = 5$
  - $f(2) = 2^3 - 2^2 - 8 \cdot 2 + 1 = 8 - 4 - 16 + 1 = -11$
  - $f\left(-\frac{4}{3}\right) = \left(-\frac{4}{3}\right)^3 - \left(-\frac{4}{3}\right)^2 - 8\left(-\frac{4}{3}\right) + 1 = -\frac{64}{27} - \frac{16}{9} + \frac{32}{3} + 1 = \frac{203}{27} \approx 7.518$
- Comparación: $f\left(-\frac{4}{3}\right) \approx 7.518$, $f(-2) = 5$, $f(2) = -11$
- **Máximo:** $\frac{203}{27}$ en $x = -\frac{4}{3}$
- **Mínimo:** $-11$ en $x = 2$

#### (ii) $f(x) = x^4 + x + 1$ en $[-1, 1]$
- Derivada: $f'(x) = 4x^3 + 1$
- Puntos críticos: $4x^3 + 1 = 0$ → $x = -\sqrt[3]{\frac{1}{4}} = -4^{-1/3} \approx -0.63$
- Valores:
  - $f(-1) = (-1)^4 + (-1) + 1 = 1 - 1 + 1 = 1$
  - $f(1) = 1^4 + 1 + 1 = 3$
  - $f\left(-4^{-1/3}\right) = \frac{3}{4} \cdot \left(-4^{-1/3}\right) + 1 = 1 - \frac{3}{4^{4/3}} \approx 0.5275$
- Comparación: $f(1) = 3$, $f(-1) = 1$, $f\left(-4^{-1/3}\right) \approx 0.5275$
- **Máximo:** $3$ en $x = 1$
- **Mínimo:** $1 - \frac{3}{4^{4/3}}$ en $x = -4^{-1/3}$

#### (iii) $f(x) = 3x^4 - 8x^2 + 6x^2 = 3x^4 - 2x^2$ en $\left[-\frac{1}{2}, \frac{1}{2}\right]$ (simplificado)
- Derivada: $f'(x) = 12x^3 - 4x = 4x(3x^2 - 1)$
- Puntos críticos: $4x(3x^2 - 1) = 0$ → $x = 0$, $x = \pm \frac{1}{\sqrt{3}} \approx \pm 0.577$ (solo $x = 0$ en intervalo)
- Valores:
  - $f\left(-\frac{1}{2}\right) = 3\left(\frac{1}{16}\right) - 2\left(\frac{1}{4}\right) = \frac{3}{16} - \frac{8}{16} = -\frac{5}{16} = -0.3125$
  - $f\left(\frac{1}{2}\right) = 3\left(\frac{1}{16}\right) - 2\left(\frac{1}{4}\right) = -\frac{5}{16} = -0.3125$
  - $f(0) = 0$
- Comparación: $f(0) = 0$, $f\left(\pm \frac{1}{2}\right) = -0.3125$
- **Máximo:** $0$ en $x = 0$
- **Mínimo:** $-\frac{5}{16}$ en $x = \pm \frac{1}{2}$

#### (iv) $f(x) = \frac{1}{x^2 + x + 1}$ en $\left[-\frac{1}{2}, 1\right]$
- Derivada: $f'(x) = -\frac{2x + 1}{(x^2 + x + 1)^2}$
- Puntos críticos: $2x + 1 = 0$ → $x = -\frac{1}{2}$ (extremo)
- Valores:
  - $f\left(-\frac{1}{2}\right) = \frac{1}{\left(-\frac{1}{2}\right)^2 + \left(-\frac{1}{2}\right) + 1} = \frac{1}{\frac{1}{4} - \frac{1}{2} + 1} = \frac{1}{\frac{3}{4}} = \frac{4}{3} \approx 1.333$
  - $f(1) = \frac{1}{1^2 + 1 + 1} = \frac{1}{3} \approx 0.333$
- Comparación: $f\left(-\frac{1}{2}\right) = \frac{4}{3}$, $f(1) = \frac{1}{3}$
- **Máximo:** $\frac{4}{3}$ en $x = -\frac{1}{2}$
- **Mínimo:** $\frac{1}{3}$ en $x = 1$

#### (v) $f(x) = \frac{x + 1}{x^2 + 1}$ en $\left[-1, \frac{1}{2}\right]$
- Derivada: $f'(x) = \frac{-(x^2 + 2x - 1)}{(x^2 + 1)^2}$
- Puntos críticos: $x^2 + 2x - 1 = 0$ → $x = -1 \pm \sqrt{2}$ (solo $x = -1 + \sqrt{2} \approx 0.414$ en intervalo)
- Valores:
  - $f(-1) = \frac{-1 + 1}{(-1)^2 + 1} = \frac{0}{2} = 0$
  - $f\left(\frac{1}{2}\right) = \frac{\frac{1}{2} + 1}{\left(\frac{1}{2}\right)^2 + 1} = \frac{1.5}{1.25} = \frac{6}{5} = 1.2$
  - $f\left(-1 + \sqrt{2}\right) = \frac{\sqrt{2} + 1}{2} \approx 1.207$
- Comparación: $f\left(-1 + \sqrt{2}\right) \approx 1.207$, $f\left(\frac{1}{2}\right) = 1.2$, $f(-1) = 0$
- **Máximo:** $\frac{\sqrt{2} + 1}{2}$ en $x = -1 + \sqrt{2}$
- **Mínimo:** $0$ en $x = -1$

#### (vi) $f(x) = \frac{x}{x^2 - 1}$ en $[0, 5]$
- Derivada: $f'(x) = \frac{-(x^2 + 1)}{(x^2 - 1)^2} < 0$ (siempre negativa donde definida)
- Discontinuidad en $x = 1$
- Comportamiento:
  - En $[0, 1)$: $f$ decrece de $f(0) = 0$ a $-\infty$ (cuando $x \to 1^-$)
  - En $(1, 5]$: $f$ decrece de $+\infty$ (cuando $x \to 1^+$) a $f(5) = \frac{5}{24} \approx 0.2083$
- **No hay máximo ni mínimo absolutos** (la función no es acotada ni continua en $[0, 5]$)

---

### Problema 2: Gráficas y puntos extremos locales

#### (i) $f(x) = x^3 - x^2 - 8x + 1$
- Gráfica: Cúbica con puntos críticos en $x = 2$ (mínimo local) y $x = -\frac{4}{3}$ (máximo local).
- **Máximo local:** $\left(-\frac{4}{3}, \frac{203}{27}\right)$
- **Mínimo local:** $(2, -11)$

#### (ii) $f(x) = x^4 + x + 1$
- Gráfica: Parábola cuártica convexa. Punto crítico en $x = -4^{-1/3}$ (mínimo local).
- **Mínimo local:** $\left(-4^{-1/3}, 1 - \frac{3}{4^{4/3}}\right)$

#### (iii) $f(x) = 3x^4 - 2x^2$
- Gráfica: Parábola cuártica simétrica. Puntos críticos:
  - $x = 0$: máximo local ($f(0) = 0$)
  - $x = \pm \frac{1}{\sqrt{3}}$ (fuera de intervalo, pero globalmente mínimos locales).
- En $\left[-\frac{1}{2}, \frac{1}{2}\right]$:
  - **Máximo local:** $(0, 0)$
  - **Mínimos locales:** $\left(\pm \frac{1}{2}, -\frac{5}{16}\right)$

#### (iv) $f(x) = \frac{1}{x^2 + x + 1}$
- Gráfica: Campana decreciente en $\left[-\frac{1}{2}, 1\right]$. Punto crítico en $x = -\frac{1}{2}$ (máximo local).
- **Máximo local:** $\left(-\frac{1}{2}, \frac{4}{3}\right)$

#### (v) $f(x) = \frac{x + 1}{x^2 + 1}$
- Gráfica: Decrece luego crece. Punto crítico en $x = -1 + \sqrt{2}$ (máximo local).
- **Máximo local:** $\left(-1 + \sqrt{2}, \frac{\sqrt{2} + 1}{2}\right)$

#### (vi) $f(x) = \frac{x}{x^2 - 1}$
- Gráfica: Asíntota vertical en $x = 1$. Decreciente en $(0, 1)$ y $(1, 5]$. 
- **Sin extremos locales** (derivada no se anula).

---

### Problema 3: Gráficas

#### (i) $f(x) = x + \frac{1}{x}$
- Dominio: $\mathbb{R} \setminus \{0\}$
- Asíntotas: Vertical en $x = 0$, oblicua $y = x$.
- Puntos críticos:
  - $x = 1$: mínimo local ($f(1) = 2$)
  - $x = -1$: máximo local ($f(-1) = -2$)
- Comportamiento: 
  - $x \to 0^+$: $f \to +\infty$
  - $x \to 0^-$: $f \to -\infty$
  - $x \to \pm\infty$: $f \sim x$

#### (ii) $f(x) = x + \frac{3}{x^2}$
- Dominio: $\mathbb{R} \setminus \{0\}$
- Asíntotas: Vertical en $x = 0$, oblicua $y = x$.
- Puntos críticos: $x = \sqrt[3]{6}$ (mínimo local, $f(\sqrt[3]{6}) = \sqrt[3]{6} + \frac{3}{(\sqrt[3]{6})^2}$)
- Comportamiento:
  - $x \to 0^{\pm}$: $f \to +\infty$
  - $x \to \pm\infty$: $f \sim x$

#### (iii) $f(x) = \frac{x^2}{x^2 - 1}$
- Dominio: $\mathbb{R} \setminus \{\pm 1\}$
- Asíntotas: Verticales en $x = \pm 1$, horizontal $y = 1$.
- Puntos críticos: $x = 0$ (máximo local, $f(0) = 0$)
- Comportamiento:
  - $x \to 1^{\pm}$: $f \to \pm\infty$
  - $x \to -1^{\pm}$: $f \to \mp\infty$
  - $x \to \pm\infty$: $f \to 1$

#### (iv) $f(x) = \frac{1}{1 + x^2}$
- Dominio: $\mathbb{R}$
- Asíntotas: Horizontal $y = 0$.
- Puntos críticos: $x = 0$ (máximo local, $f(0) = 1$)
- Comportamiento: Par, simétrica respecto al eje $y$. 
  - $x \to \pm\infty$: $f \to 0$

---

### Problema 4

#### (a) $f(x) = \sum_{i=1}^n (x - a_i)^2$
- Derivada: $f'(x) = 2 \sum_{i=1}^n (x - a_i) = 2(nx - \sum a_i)$
- Punto crítico: $f'(x) = 0$ → $x = \frac{1}{n} \sum a_i = \bar{a}$ (media aritmética)
- $f''(x) = 2n > 0$ → mínimo.
- **Valor mínimo:** $f(\bar{a}) = \sum (\bar{a} - a_i)^2$

#### (b) $f(x) = \sum_{i=1}^n |x - a_i|$
- Función lineal por tramos, no diferenciable en $x = a_i$.
- Pendiente en intervalo $(a_j, a_{j+1})$: $f'(x) = 2k - n$, donde $k = |\{i: a_i < x\}|$.
- $f$ es decreciente para $x < \text{mediana}$, creciente para $x > \text{mediana}$.
- **Valor mínimo:**
  - Si $n$ impar: en $x = a_{(n+1)/2}$ (mediana).
  - Si $n$ par: en cualquier $x \in [a_{n/2}, a_{n/2 + 1}]$.

#### (c) $f(x) = \frac{1}{1 + |x|} + \frac{1}{1 + |x - a|}$ ($a > 0$)
- Intervalos: $(-\infty, 0)$, $(0, a)$, $(a, \infty)$.
- Análisis:
  - $(-\infty, 0)$: $f'(x) > 0$ → creciente.
  - $(a, \infty)$: $f'(x) < 0$ → decreciente.
  - $(0, a)$: $f'(x) = 0$ en $x = \frac{a}{2}$ (mínimo local).
- Valores:
  - $f(0) = f(a) = \frac{2 + a}{1 + a}$
  - $f\left(\frac{a}{2}\right) = \frac{4}{2 + a}$
- Comparación: $\frac{2 + a}{1 + a} > \frac{4}{2 + a}$ para $a > 0$.
- **Valor máximo:** $\frac{2 + a}{1 + a}$ en $x = 0$ y $x = a$.

### Respuesta al Problema 5

#### (i) $f(x) = \begin{cases} 
x, & x \neq 3, 5, 7, 9 \\ 
5, & x = 3 \\ 
-3, & x = 5 \\ 
7, & x = 7 \\ 
7, & x = 9 
\end{cases}$

- **Máximo local**: En $x = 3$ ($f(3) = 5$), ya que para $x$ cercanos (distintos de 3, 5, 7, 9), $f(x) = x < 5$.
- **Mínimo local**: En $x = 5$ ($f(5) = -3$), ya que para $x$ cercanos, $f(x) = x > -3$.
- **Mínimo local**: En $x = 9$ ($f(9) = 7$), ya que para $x$ cercanos, $f(x) = x > 7$.
- No hay extremos locales en $x = 7$ (los valores cercanos son menores y mayores).

---

#### (ii) $f(x) = \begin{cases} 
0, & x \text{ irracional} \\ 
1/q, & x = p/q \text{ fracción irreducible} 
\end{cases}$

- **Máximo local**: En todo $x$ racional, ya que en un entorno suficientemente pequeño, $f(y) \leq f(x)$ (porque no hay racionales con denominador menor en el entorno).
- **Mínimo local**: En todo $x$ irracional, ya que $f(x) = 0$ y $f(y) \geq 0$ para todo $y$.

---

#### (iii) $f(x) = \begin{cases} 
x, & x \text{ racional} \\ 
0, & x \text{ irracional} 
\end{cases}$

- **Máximo local**: En todo $x$ irracional negativo ($x < 0$), ya que $f(x) = 0$ y en un entorno pequeño (con $\delta < |x|$), $f(y) \leq 0$.
- **Mínimo local**: En todo $x$ irracional positivo ($x > 0$), ya que $f(x) = 0$ y $f(y) \geq 0$ para todo $y$.
- En $x = 0$ (irracional) y en todo $x$ racional, no hay extremos locales (los valores cercanos son mayores y menores).

---

#### (iv) $f(x) = \begin{cases} 
1, & x = 1/n \text{ para algún } n \in \mathbb{N} \\ 
0, & \text{en los demás casos} 
\end{cases}$

- **Máximo local**: En todo $x = 1/n$ ($n \in \mathbb{N}$), ya que en un entorno pequeño (sin otros $1/m$), $f(y) \leq 1$ y $f(x) = 1$.
- **Mínimo local**: En todo $x \neq 1/n$ (para todo $n \in \mathbb{N}$), ya que $f(x) = 0$ y $f(y) \geq 0$ para todo $y$.

---

#### (v) $f(x) = \begin{cases} 
1, & \text{si el desarrollo decimal de } x \text{ contiene un } 5 \\ 
0, & \text{en los demás casos} 
\end{cases}$

- **Máximo local**: En todo $x$ cuyo desarrollo decimal contiene un 5, ya que $f(x) = 1$ y $f(y) \leq 1$ para todo $y$.
- **Mínimo local**: En todo $x$ cuyo desarrollo decimal no contiene un 5, ya que $f(x) = 0$ y $f(y) \geq 0$ para todo $y$.

---

### Respuesta al Problema 6

**Demostración:**  
Supongamos $f$ creciente en $(a, b)$ y continua en $[a, b]$. Sean $x, y \in [a, b]$ con $x < y$.  
- Si $a < x < y < b$, entonces $f(x) \leq f(y)$ por ser creciente en $(a, b)$.  
- Si $x = a$, $y \in (a, b)$: Sea $\{x_n\} \subset (a, b)$ con $x_n \to a^+$. Como $f$ es creciente, $f(x_n) \leq f(y)$ para $x_n < y$. Por continuidad en $a$, $f(a) = \lim f(x_n) \leq f(y)$.  
- Si $y = b$, $x \in (a, b)$: Sea $\{y_n\} \subset (a, b)$ con $y_n \to b^-$. Como $f$ es creciente, $f(x) \leq f(y_n)$ para $x < y_n$. Por continuidad en $b$, $f(x) \leq \lim f(y_n) = f(b)$.  
- Si $x = a$, $y = b$: Tomando $c \in (a, b)$, se tiene $f(a) \leq f(c) \leq f(b)$.  
Por tanto, $f$ es creciente en $[a, b]$.  

**Caso particular:** Si $f$ continua en $[a, b]$ y $f' > 0$ en $(a, b)$, entonces $f$ es estrictamente creciente en $(a, b)$ (por teorema del valor medio). Por el resultado anterior, $f$ es creciente en $[a, b]$.

---

### Respuesta al Problema 7

**Demostración:**  
Sea $(x, 0)$ el punto en el eje horizontal. La longitud total es:  
$$ L(x) = \sqrt{x^2 + a^2} + \sqrt{(x - 1)^2 + b^2} $$  
La derivada es:  
$$ L'(x) = \frac{x}{\sqrt{x^2 + a^2}} + \frac{x - 1}{\sqrt{(x - 1)^2 + b^2}} $$  
Igualando a cero:  
$$ \frac{x}{\sqrt{x^2 + a^2}} = -\frac{x - 1}{\sqrt{(x - 1)^2 + b^2}} $$  
Sean $\alpha$ y $\beta$ los ángulos con la vertical de los segmentos $(0,a)$ a $(x,0)$ y $(x,0)$ a $(1,b)$, respectivamente. Entonces:  
$$ \frac{x}{\sqrt{x^2 + a^2}} = \sin \alpha, \quad \frac{x - 1}{\sqrt{(x - 1)^2 + b^2}} = -\sin \beta $$  
La ecuación es $\sin \alpha = \sin \beta$. Como $\alpha, \beta \in [0, \pi/2)$ (asumiendo $a, b > 0$), se tiene $\alpha = \beta$.  

**Mínimo:**  
La segunda derivada es:  
$$ L''(x) = \frac{a^2}{(x^2 + a^2)^{3/2}} + \frac{b^2}{((x - 1)^2 + b^2)^{3/2}} > 0 $$  
Como $L''(x) > 0$, $L$ es convexa, y el punto crítico ($\alpha = \beta$) es un mínimo.  

**Demostración geométrica alternativa:**  
Reflejar el punto $(1, b)$ sobre el eje horizontal a $(1, -b)$. La recta de $(0, a)$ a $(1, -b)$ corta el eje horizontal en $(x, 0)$. Por reflexión, $\alpha = \beta$, y la longitud es mínima por ser una línea recta.

### Respuestas

#### **8. Distancia mínima de un punto a una recta**
**(a)** Minimizar la distancia de $(x_0, y_0)$ a $L: y = mx + b$.  
- Función distancia al cuadrado: $s(x) = (x - x_0)^2 + (mx + b - y_0)^2$.  
- Derivada: $s'(x) = 2(x - x_0) + 2m(mx + b - y_0)$.  
- Punto crítico: $s'(x) = 0 \implies x = \frac{x_0 + m(y_0 - b)}{1 + m^2}$.  
- $\boxed{\overline{x} = \dfrac{x_0 + m(y_0 - b)}{1 + m^2}}$.

**(b)** Recta perpendicular a $L$ por $(x_0, y_0)$.  
- Pendiente de $L$: $m$.  
- Pendiente perpendicular: $-\frac{1}{m}$.  
- Ecuación: $\frac{y - y_0}{x - x_0} = -\frac{1}{m}$.  
- Intersección con $L$: misma solución $\boxed{\overline{x} = \dfrac{x_0 + m(y_0 - b)}{1 + m^2}}$.

**(c)** Distancia mínima.  
- Con $b = 0$: distancia = $\frac{|y_0 - m x_0|}{\sqrt{1 + m^2}}$.  
- Caso general: $\boxed{d = \dfrac{| -m x_0 + y_0 - b |}{\sqrt{1 + m^2}} = \dfrac{|m x_0 - y_0 + b|}{\sqrt{1 + m^2}}$.

**(d)** Recta $Ax + By + C = 0$.  
- Distancia: $\boxed{d = \dfrac{|A x_0 + B y_0 + C|}{\sqrt{A^2 + B^2}}}$.

---

#### **9. Relación entre puntos críticos de $f$ y $f^2$**  
- $g(x) = [f(x)]^2$, $g'(x) = 2f(x)f'(x)$.  
- Puntos críticos de $g$:  
  - $f'(x) = 0$ (puntos críticos de $f$).  
  - $f(x) = 0$ (ceros de $f$).  
- Todo punto crítico de $f$ es punto crítico de $g$, pero no viceversa.  
- $\boxed{\text{Puntos críticos de } g \text{ son ceros de } f \text{ y puntos críticos de } f}$.

---

#### **10. Rectángulo de perímetro fijo y área máxima**  
- Perímetro $P = 2a + 2b$ fijo $\implies b = \frac{P}{2} - a$.  
- Área: $A(a) = a \left( \frac{P}{2} - a \right) = \frac{P}{2}a - a^2$.  
- Derivada: $A'(a) = \frac{P}{2} - 2a = 0 \implies a = \frac{P}{4}$.  
- $b = \frac{P}{4}$ (cuadrado).  
- $\boxed{\text{El cuadrado maximiza el área}}$.

---

#### **11. Cilindro de volumen fijo $V$ y mínima superficie**  
- Volumen: $V = \pi r^2 h \implies h = \frac{V}{\pi r^2}$.  
- Superficie: $S(r) = 2\pi r^2 + \frac{2V}{r}$.  
- Derivada: $S'(r) = 4\pi r - \frac{2V}{r^2} = 0 \implies r^3 = \frac{V}{2\pi}$.  
- $r = \sqrt[3]{\frac{V}{2\pi}}$, $h = \frac{V}{\pi r^2} = 2 \sqrt[3]{\frac{V}{2\pi}} = 2r$.  
- $\boxed{r = \sqrt[3]{\dfrac{V}{2\pi}}, \quad h = 2r}$.

---

#### **12. Cono de volumen máximo generado por triángulo rectángulo**  
- Hipotenusa $a$ fija. Catetos $b$, $c$: $b^2 + c^2 = a^2$.  
- Girar alrededor de un cateto (ej. $b$): radio $c$, altura $b$.  
- Volumen: $V(b) = \frac{1}{3} \pi c^2 b = \frac{1}{3} \pi (a^2 - b^2)b$.  
- Derivada: $V'(b) = \frac{1}{3} \pi (a^2 - 3b^2) = 0 \implies b = \frac{a}{\sqrt{3}}$.  
- $c = \sqrt{a^2 - b^2} = a \sqrt{\frac{2}{3}}$.  
- $V_{\text{max}} = \frac{1}{3} \pi \left( a \sqrt{\frac{2}{3}} \right)^2 \left( \frac{a}{\sqrt{3}} \right) = \frac{2\pi a^3}{9\sqrt{3}}$.  
- $\boxed{V_{\text{max}} = \dfrac{2\pi a^3}{9\sqrt{3}}}$.

---

#### **13. Suma de un número positivo y su recíproco**  
- Sea $x > 0$, $f(x) = x + \frac{1}{x}$.  
- Derivada: $f'(x) = 1 - \frac{1}{x^2} = 0 \implies x = 1$.  
- $f''(x) = \frac{2}{x^3}$, $f''(1) > 0$ (mínimo).  
- $f(1) = 2$.  
- $\boxed{x + \dfrac{1}{x} \geq 2}$ para todo $x > 0$.

---

#### **14. Trapecio de área máxima inscrito en semicírculo**  
- Radio $a$, base mayor $2a$ (diámetro).  
- Base menor $2b$, altura $h = \sqrt{a^2 - b^2}$.  
- Área: $A(b) = (a + b) \sqrt{a^2 - b^2}$.  
- Derivada: optimizar $A^2(b) = (a + b)^2 (a^2 - b^2)$.  
- $A^2(b) = (a + b)^3 (a - b)$.  
- Derivada: $\frac{d}{db}[A^2] = (a + b)^2 (2a - 4b) = 0 \implies b = \frac{a}{2}$.  
- $h = \sqrt{a^2 - \left( \frac{a}{2} \right)^2} = \frac{a\sqrt{3}}{2}$.  
- Área máxima: $\boxed{A = \dfrac{3\sqrt{3}}{4} a^2}$.

---

#### **15. Longitud máxima de escalera en pasillos en ángulo recto**  
- Anchuras $a$, $b$. Ángulo $\theta$ con la pared.  
- Longitud: $L(\theta) = \frac{a}{\sin \theta} + \frac{b}{\cos \theta}$.  
- Derivada: $L'(\theta) = -a \csc \theta \cot \theta + b \sec \theta \tan \theta = 0$.  
- $\tan^3 \theta = \frac{a}{b} \implies \theta = \arctan \left( \sqrt[3]{\frac{a}{b}} \right)$.  
- Longitud: $\boxed{L = \left( a^{2/3} + b^{2/3} \right)^{3/2}}$.

---

#### **16. Sector circular de área fija $A$ y perímetro mínimo**  
- Área: $A = \frac{1}{2} R^2 \theta \implies \theta = \frac{2A}{R^2}$.  
- Perímetro: $P(R) = 2R + R\theta = 2R + \frac{2A}{R}$.  
- Derivada: $P'(R) = 2 - \frac{2A}{R^2} = 0 \implies R = \sqrt{A}$.  
- $\theta = \frac{2A}{(\sqrt{A})^2} = 2$ radianes.  
- $\boxed{R = \sqrt{A}, \quad \theta = 2 \text{ radianes}}$.
