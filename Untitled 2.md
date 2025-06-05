**Solución mejorada:**

El objetivo es determinar la capacidad de asientos $x$ que maximiza la ganancia diaria bruta $g(x)$, considerando las condiciones dadas.

### Definición de la función de ganancia $g(x)$:
1. **Para $40 \leq x \leq 80$**:  
   La ganancia por lugar es constante: $\$8$.  
   $$
   g(x) = 8x
   $$

2. **Para $x > 80$**:  
   - El excedente de lugares es $x - 80$.  
   - La ganancia por lugar se reduce en $\$0.04$ por cada lugar excedente:  
     $$
     \text{Ganancia por lugar} = 8 - 0.04(x - 80)
     $$  
   - La ganancia total es:  
     $$
     g(x) = x \left[8 - 0.04(x - 80)\right]
     $$  
     Simaplificando la expresión:  
     $$
     g(x) = x \left[8 - 0.04x + 3.2\right] = x(11.2 - 0.04x) = 11.2x - 0.04x^2
     $$

### Análisis de la función:
- **En $[40, 80]$**: $g(x) = 8x$ es una **función lineal creciente** (derivada $g'(x) = 8 > 0$).  
- **En $(80, \infty)$**: $g(x) = 11.2x - 0.04x^2$ es una **parábola cóncava hacia abajo** (coeficiente de $x^2$ es negativo).

### Búsqueda del máximo global:
- **Paso 1: Máximo en $x > 80$**.  
  La derivada de $g(x)$ para $x > 80$ es:  
  $$
  g'(x) = 11.2 - 0.08x
  $$  
  Igualamos a cero para encontrar puntos críticos:  
  $$
  11.2 - 0.08x = 0 \implies 0.08x = 11.2 \implies x = \frac{11.2}{0.08} = 140
  $$  
  Este es un máximo local por la concavidad.

- **Paso 2: Evaluar puntos clave**.  
  - En $x = 80$ (límite del primer segmento):  
    $$
    g(80) = 8 \times 80 = 640
    $$  
  - En $x = 140$ (punto crítico):  
    $$
    g(140) = 11.2 \times 140 - 0.04 \times (140)^2 = 1568 - 0.04 \times 19600 = 1568 - 784 = 784
    $$  
  - Comparamos con valores cercanos a $140$:  
    $$
    \begin{align*}
    g(130) &= 11.2 \times 130 - 0.04 \times 130^2 = 1456 - 676 = 780, \\
    g(131) &= 11.2 \times 131 - 0.04 \times 131^2 = 1467.2 - 686.44 = 780.76, \\
    g(141) &= 11.2 \times 141 - 0.04 \times 141^2 = 1579.2 - 795.24 = 783.96, \\
    g(150) &= 11.2 \times 150 - 0.04 \times 150^2 = 1680 - 900 = 780.
    \end{align*}
    $$  
    **Conclusión**: $g(140) = 784$ es mayor que los valores adyacentes.

- **Paso 3: Máximo global**.  
  Como $g(x)$ es creciente en $[40, 80]$ y $g(140) = 784 > g(80) = 640$, el máximo global está en $x = 140$.

### Respuesta final:
La capacidad de asientos que maximiza la ganancia diaria bruta es **140 lugares**, con una ganancia de **\$784**.

