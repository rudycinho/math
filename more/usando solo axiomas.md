**Solución utilizando axiomas de cuerpo ordenado:**

Queremos demostrar que para todo número real $x$, la desigualdad $x^2 - 2x + 2 > 0$ es verdadera. Usaremos únicamente propiedades de los cuerpos ordenados.

---

### **Paso 1: Completar el cuadrado**
Reescribimos la expresión $x^2 - 2x + 2$:
$$
x^2 - 2x + 2 = (x^2 - 2x + 1) + 1 = (x - 1)^2 + 1.
$$

**Justificación:**
- **Axioma de la suma y multiplicación:** La manipulación algebraica es válida en cualquier cuerpo.
- **Axioma del elemento neutro aditivo ($0$) y multiplicativo ($1$)**: Se usan para completar el cuadrado.

---

### **Paso 2: Analizar $(x - 1)^2 \geq 0$**
En un cuerpo ordenado, el cuadrado de cualquier elemento es no negativo:
$$
(x - 1)^2 \geq 0 \quad \text{para todo } x.
$$
**Justificación:**
- **Axioma de orden:** Si $a \neq 0$, entonces $a^2 > 0$. Si $a = 0$, $a^2 = 0$.

---

### **Paso 3: Sumar 1 a ambos lados**
Sumamos 1 a la desigualdad anterior:
$$
(x - 1)^2 + 1 \geq 1.
$$
**Justificación:**
- **Axioma de la suma en desigualdades:** Si $a \geq b$, entonces $a + c \geq b + c$.

---

### **Paso 4: Comparar con 0**
Sabemos que $1 > 0$ en cualquier cuerpo ordenado. Por lo tanto:
$$
(x - 1)^2 + 1 \geq 1 > 0 \implies (x - 1)^2 + 1 > 0.
$$
**Justificación:**
- **Propiedad transitiva del orden:** Si $a \geq b$ y $b > c$, entonces $a > c$.

---

### **Conclusión**
La expresión $x^2 - 2x + 2 = (x - 1)^2 + 1$ es siempre mayor que 0 para cualquier $x$. Por lo tanto, la desigualdad $x^2 - 2x + 2 > 0$ **se cumple para todos los números reales**.

**Respuesta final:**  
$$
\boxed{\mathbb{R}} \quad \text{(todos los números reales)}
$$