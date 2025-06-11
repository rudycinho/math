
En el proyecto de una cafetería se calcula que si hay lugares para 40 a 80 personas, la ganancia diaria bruta será de \$8 por lugar. Sin embargo, si la capacidad de asientos sobrepasa los 80 lugares, la ganancia diaria bruta en cada lugar disminuirá en 4 centavos (\$0.04) por el número de lugares excedentes. ¿Cuál deberá ser la capacidad de asientos para obtener la mayor ganancia diaria bruta?

---

## Comprender el problema:
- **Variables:**
  - $x$: Número de lugares (capacidad de asientos).
  - $g(x)$: Ganancia diaria bruta total.
---
- **Condiciones:**
  - Si $40 \leq x \leq 80$:  
    Ganancia por lugar = $8$ $\Rightarrow$ $g(x) = 8x$.
  - Si $x > 80$:  
    Excedente = $x - 80$.  
    Ganancia por lugar = $8 - 0.04(x - 80)$.  
    Ganancia total:  
    $$
	\begin{align}
    g(x) &= x \left[ 8 - 0.04(x - 80) \right] \\ &= x \left( 8 - 0.04x + 3.2 \right) \\ &= x(11.2 - 0.04x) \\ &= 11.2x - 0.04x^2.
	\end{align}
    $$
---
- **Función por partes:**
  $$
  g(x) = 
  \begin{cases} 
  8x & \text{si } 40 \leq x \leq 80, \\
  11.2x - 0.04x^2 & \text{si } x > 80.
  \end{cases}
  $$
---

## Concebir un plan:
- **Tramo $[40, 80]$:**  
  $g(x) = 8x$ es lineal y creciente $\Rightarrow$ Máximo en $x = 80$:  
  $g(80) = 8 \times 80 = 640$.
- **Tramo $x > 80$:**  
  $g(x) = 11.2x - 0.04x^2$ es una parábola cóncava hacia abajo (coeficiente de $x^2$ es negativo, $-0.04$).  
  Tiene un máximo en su vértice.  

---

![[Figure_1.png]]
  **Método:** Derivar e igualar a cero para encontrar 
  el punto crítico.

---

## Ejecutar el plan:
- **Derivada de $g(x)$ para $x > 80$:**  
  $$
 \begin{align}
  g'(x) &= \frac{d}{dx}(11.2x - 0.04x^2) \\ &= 11.2 - 0.08x.
 \end{align} 
  $$
- **Igualar a cero:**  
  $$
 \begin{align}
  11.2 - 0.08x = 0 &\implies 0.08x = 11.2 \\ &\implies x = \frac{11.2}{0.08} = 140.
 \end{align}
  $$
---
- **Evaluar $g(140)$:**  
  $$
 \begin{align}
  g(140) &= 11.2(140) - 0.04(140)^2 \\ &= 1568 - 0.04 \times 19600 \\ &= 1568 - 784 \\ &= 784.
 \end{align}
  $$
- **Comparar con el máximo tramo anterior:**  
  $g(80) = 640 < 784 = g(140)$ $\Rightarrow$ El máximo no está en $x = 80$.

---

## Verificación:

| $x$   | $g(x)$ (para $x > 80$)                                  | Resultado |
| ----- | ------------------------------------------------------- | --------- |
| $130$ | $11.2 \times 130 - 0.04 \times 130^2 = 1456 - 676$      | $780$     |
| $131$ | $11.2 \times 131 - 0.04 \times 131^2 = 1467.2 - 686.44$ | $780.76$  |
| $140$ | $11.2 \times 140 - 0.04 \times 140^2 = 1568 - 784$      | $784$     |
| $141$ | $11.2 \times 141 - 0.04 \times 141^2 = 1579.2 - 795.24$ | $783.96$  |
| $150$ | $11.2 \times 150 - 0.04 \times 150^2 = 1680 - 900$      | $780$     |

- **Conclusión:** La ganancia máxima es **\$784** en $x = 140$, y valores cercanos son menores.
