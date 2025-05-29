
# Análisis de $f(x) = \lfloor 1/x \rfloor$  
**Objetivo**: Determinar para qué valores de $a$ existe $\lim_{x \to a} \lfloor 1/x \rfloor$.  

---

## 1. Comportamiento general de la función  
La función $\lfloor 1/x \rfloor$ toma el **mayor entero menor o igual a $1/x$**.  
**Ejemplos**:  
- Si $x = 0.5 \implies 1/x = 2 \implies \lfloor 1/x \rfloor = 2$.  
- Si $x = 0.3 \implies 1/x \approx 3.333 \implies \lfloor 1/x \rfloor = 3$.  
- Si $x = -0.5 \implies 1/x = -2 \implies \lfloor 1/x \rfloor = -2$.  

---

## 2. Puntos críticos (donde el límite falla)  

### **Caso 1: $a = 0$**  
- **Límite por la derecha** ($x \to 0^+$):  
  $$ 1/x \to +\infty \implies \lfloor 1/x \rfloor \to +\infty. $$  
  *Ejemplo*: $x = 0.001 \implies \lfloor 1000 \rfloor = 1000$.  

- **Límite por la izquierda** ($x \to 0^-$):  
  $$ 1/x \to -\infty \implies \lfloor 1/x \rfloor \to -\infty. $$  
  *Ejemplo*: $x = -0.001 \implies \lfloor -1000 \rfloor = -1000$.  

**Conclusión**:  
El límite **no existe** en $a = 0$ porque:  
$$ \lim_{x \to 0^+} \lfloor 1/x \rfloor \neq \lim_{x \to 0^-} \lfloor 1/x \rfloor. $$

---

### **Caso 2: $a = \frac{1}{n}$ ($n \in \mathbb{Z}$, $n \neq 0$)**  
**Ejemplo con $a = \frac{1}{2}$ ($n = 2$)**:  
- **Límite por la izquierda** ($x \to \frac{1}{2}^-$):  
  $$ 1/x \to 2^+ \implies \lfloor 1/x \rfloor = 2. $$  
  *Ejemplo*: $x = 0.499 \implies \lfloor 2.004 \rfloor = 2$.  

- **Límite por la derecha** ($x \to \frac{1}{2}^+$):  
  $$ 1/x \to 2^- \implies \lfloor 1/x \rfloor = 1. $$  
  *Ejemplo*: $x = 0.501 \implies \lfloor 1.996 \rfloor = 1$.  

**Conclusión**:  
El límite **no existe** porque:  
$$ \lim_{x \to \frac{1}{2}^-} \lfloor 1/x \rfloor = 2 \quad \text{y} \quad \lim_{x \to \frac{1}{2}^+} \lfloor 1/x \rfloor = 1. $$

---

### **Caso 3: $a \neq 0$ y $a \neq \frac{1}{n}$**  
**Ejemplo con $a = 0.3$**:  
- $1/a \approx 3.333$ (no es entero).  
- **Cerca de $x = 0.3$**:  
  $$ x = 0.29 \implies \lfloor 3.448 \rfloor = 3, $$  
  $$ x = 0.31 \implies \lfloor 3.225 \rfloor = 3. $$  

**Conclusión**:  
El límite **existe** y es:  
$$ \lim_{x \to 0.3} \lfloor 1/x \rfloor = \lfloor 1/0.3 \rfloor = 3. $$  

---

## 3. Resumen de casos  
| **Tipo de $a$**               | **¿Existe $\lim_{x \to a} \lfloor 1/x \rfloor$?** | **Razón**                                                                 |
|-------------------------------|--------------------------------------------------|---------------------------------------------------------------------------|
| $a = 0$                       | ❌ No                                            | Límites laterales son $+\infty$ y $-\infty$.                              |
| $a = \frac{1}{n}$ ($n \neq 0$) | ❌ No                                            | Límites laterales son $n$ (izq.) y $n-1$ (der.). Ejemplo: $a = \frac{1}{2}$. |
| $a \neq 0$ y $a \neq \frac{1}{n}$ | ✅ Sí                                     | $\lfloor 1/x \rfloor$ es constante cerca de $a$. Ejemplo: $a = 0.3$.      |

---

## 4. Ejemplos clave  

### **Ejemplo 1: $a = \frac{1}{3}$**  
- **Límite por izquierda**: $\lfloor 1/(0.333^-) \rfloor = 3$.  
- **Límite por derecha**: $\lfloor 1/(0.333^+) \rfloor = 2$.  
- **Conclusión**: No existe el límite.  

### **Ejemplo 2: $a = 0.4$**  
- $\lfloor 1/0.4 \rfloor = \lfloor 2.5 \rfloor = 2$.  
- **Conclusión**: El límite existe y es $2$.  

---

**Conclusión final**:  
El límite $\lim_{x \to a} \lfloor 1/x \rfloor$ **existe** si y solo si $a \neq 0$ y $a \neq \frac{1}{n}$ para cualquier $n \in \mathbb{Z} \setminus \{0\}$. 