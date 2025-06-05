### Enunciado del Problema

---

### Solución
Para determinar la capacidad de asientos que maximiza la ganancia diaria bruta, se define $x$ como el número de lugares, donde $x > 80$ (dado que para $x \leq 80$ la ganancia es menor, como se verifica más adelante). La ganancia diaria bruta total $G(x)$ depende de $x$ de la siguiente manera:

- **Ganancia por lugar cuando $x > 80$**:  
  La ganancia por lugar disminuye en $0.04 por cada lugar excedente sobre 80. El número de lugares excedentes es $x - 80$, por lo que la ganancia por lugar es:  
  $$
  8 - 0.04(x - 80)
  $$

- **Ganancia total $G(x)$**:  
  $$
  G(x) = x \left[ 8 - 0.04(x - 80) \right]
  $$
  Simplificando la expresión:  
  $$
  G(x) = x \left[ 8 - 0.04x + 3.2 \right] = x(11.2 - 0.04x) = 11.2x - 0.04x^2
  $$
  Así,  
  $$
  G(x) = -0.04x^2 + 11.2x
  $$

Esta función cuadrática tiene la forma $ax^2 + bx + c$ con $a = -0.04$, $b = 11.2$, y $c = 0$. Como $a < 0$, la parábola abre hacia abajo, lo que indica que tiene un máximo en su vértice. La coordenada $x$ del vértice se calcula como:  
$$
x = -\frac{b}{2a} = -\frac{11.2}{2 \times (-0.04)} = \frac{11.2}{0.08} = 140
$$

Por lo tanto, la capacidad óptima es **140 lugares**.

---

### Verificación
- **Ganancia en $x = 140$**:  
  Ganancia por lugar: $8 - 0.04(140 - 80) = 8 - 0.04 \times 60 = 8 - 2.4 = 5.6$ dólares.  
  Ganancia total: $140 \times 5.6 = 784$ dólares.

- **Comparación con otros puntos**:  
  - En $x = 80$ (límite superior del primer rango):  
    Ganancia total: $80 \times 8 = 640$ dólares (menor que 784).  
  - En $x = 100$ (dentro del rango $x > 80$):  
    Ganancia por lugar: $8 - 0.04(100 - 80) = 8 - 0.8 = 7.2$ dólares.  
    Ganancia total: $100 \times 7.2 = 720$ dólares (menor que 784).  
  - En $x = 150$:  
    Ganancia total: $-0.04(150)^2 + 11.2(150) = -900 + 1680 = 780$ dólares (menor que 784).

Además, para $x \leq 80$, la función lineal $G(x) = 8x$ es creciente, por lo que el máximo en ese rango es $x = 80$ con 640 dólares, que es inferior a los 784 dólares obtenidos en $x = 140$.

---

### Conclusión
La capacidad de asientos que maximiza la ganancia diaria bruta es **140 lugares**, con una ganancia total de **784 dólares**.