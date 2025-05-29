La noción de límite en cálculo surge de la necesidad de formalizar la idea intuitiva de **aproximación**. Comencemos con ejemplos concretos y progresemos hacia la definición general.

---

### **1. Intuición inicial**
Imagina una función $f(x)$ y un punto $a$. Decir que el límite de $f(x)$ cuando $x$ tiende a $a$ es $L$ significa que, a medida que $x$ se acerca arbitrariamente a $a$, los valores de $f(x)$ se acercan cada vez más a $L$. Por ejemplo:

- Para $f(x) = x^2$, cuando $x \to 2$, los valores de $f(x)$ se aproximan a $4$.
- Incluso si $f(a)$ no está definido o es diferente de $L$, el límite depende solo del comportamiento de $f(x)$ *cerca de $a$*, no en $a$.

---

### **2. Necesidad de rigor**
La intuición falla en casos complejos. Por ejemplo, para $f(x) = \frac{\sin(x)}{x}$ cuando $x \to 0$, aunque $f(0)$ no está definido, el límite existe y es $1$. ¿Cómo garantizar esto sin ambigüedad?

---

### **3. Formalización: La definición $\epsilon$-$\delta$**
La definición precisa, introducida por Cauchy y Weierstrass, utiliza dos parámetros:
- $\epsilon$: Controla qué tan cerca debe estar $f(x)$ de $L$.
- $\delta$: Controla qué tan cerca debe estar $x$ de $a$.

**Definición:**  
Decimos que $\lim_{x \to a} f(x) = L$ si, para todo $\epsilon > 0$, existe un $\delta > 0$ tal que:  
$$ 0 < |x - a| < \delta \implies |f(x) - L| < \epsilon. $$

---

### **4. Desglose de la definición**
1. **"Para todo $\epsilon > 0$":**  
   Queremos que $f(x)$ esté tan cerca de $L$ como se desee (sin importar cuán pequeño sea $\epsilon$).

2. **"Existe un $\delta > 0$":**  
   La elección de $\delta$ depende de $\epsilon$ y garantiza que $x$ esté suficientemente cerca de $a$.

3. **"$0 < |x - a| < \delta$":**  
   Excluye el punto $a$ mismo (el límite no depende de $f(a)$).

4. **"$\implies |f(x) - L| < \epsilon$":**  
   La consecuencia lógica: si $x$ está en el entorno reducido $(a - \delta, a + \delta)$, entonces $f(x)$ está en $(L - \epsilon, L + \epsilon)$.

---

### **5. Ejemplo ilustrativo**
Sea $f(x) = 3x + 1$. Probemos que $\lim_{x \to 2} f(x) = 7$:

1. Dado $\epsilon > 0$, buscamos $\delta$ tal que:  
   $$ |x - 2| < \delta \implies |3x + 1 - 7| < \epsilon. $$
2. Simplificamos:  
   $$ |3x - 6| = 3|x - 2| < \epsilon \implies |x - 2| < \frac{\epsilon}{3}. $$
3. Elegimos $\delta = \frac{\epsilon}{3}$. Así, si $|x - 2| < \delta$, entonces:  
   $$ 3|x - 2| < 3 \cdot \frac{\epsilon}{3} = \epsilon. $$

---

### **6. Casos no lineales**
Para funciones no lineales, como $f(x) = x^2$, el $\delta$ depende de $\epsilon$ y de acotar $x$ cerca de $a$:

1. Demostrar $\lim_{x \to 3} x^2 = 9$:  
   $$ |x^2 - 9| = |x - 3||x + 3|. $$
2. Si restringimos $|x - 3| < 1$ (para acotar $|x + 3| < 7$), entonces:  
   $$ |x - 3||x + 3| < 7|x - 3|. $$
3. Para que $7|x - 3| < \epsilon$, elegimos $\delta = \min\left(1, \frac{\epsilon}{7}\right)$.

---

### **7. Importancia de la definición**
- **Rigor matemático:** Resuelve paradojas y comportamientos oscilantes (e.g., $f(x) = \sin(1/x)$ cerca de $0$ no tiene límite).
- **Fundamento del cálculo:**  
  - **Continuidad:** $f$ es continua en $a$ si $\lim_{x \to a} f(x) = f(a)$.  
  - **Derivadas:** $\frac{d}{dx}f(a) = \lim_{h \to 0} \frac{f(a+h) - f(a)}{h}$.  
  - **Integrales:** Límites de sumas de Riemann.

---

### **8. Conclusión**
El límite generaliza la intuición de aproximación mediante un marco lógico:  
- $\epsilon$ representa la precisión deseada en el codominio.  
- $\delta$ garantiza la proximidad necesaria en el dominio.  
Esta dualidad asegura que, sin importar la complejidad de $f(x)$, el comportamiento cerca de $a$ está completamente controlado.