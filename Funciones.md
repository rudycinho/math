# Funciones en Análisis Real

## Conceptos Fundamentales  
- **Función**: Asociación entre elementos de dos conjuntos que asigna a cada elemento del dominio *exactamente un elemento* en el codominio.  
- **Dominio**: Conjunto de números reales para los cuales la función está definida.  
- **Regla de asignación**: Método (algebraico, lógico o descriptivo) para determinar la correspondencia entre elementos.  
- **Notación funcional**: Uso de $f(x)$ para denotar el valor asignado a $x$ por la función $f$.  

---

## Definiciones  
### **Definición 1 (Provisional)**  
Una función es una regla que asigna a cada elemento de un conjunto de números reales otro número real.  

> **Explicación**: Esta definición intuitiva enfatiza la idea de correspondencia, pero carece de rigor al no especificar qué es una "regla".  

---

### **Definición 2 (Formal)**  
Una función es una colección de pares ordenados $(a, b)$ con la propiedad:  
**Si $(a, b)$ y $(a, c)$ están en la colección, entonces $b = c$**.  

> **Implicaciones**:  
> - Cada elemento del dominio tiene una *única* imagen.  
> - El dominio es el conjunto de todos los primeros elementos de los pares.  
> - $f(a) = b$ si $(a, b)$ pertenece a la función.  

---

## Tipos de Funciones y Ejemplos  
### **Funciones Polinómicas**  
**Estructura**: $f(x) = a_n x^n + \dots + a_1 x + a_0$.  
- **Ejemplo 1**: $f(x) = x^2$ (definida para todo $x$).  

### **Funciones Racionales**  
**Estructura**: Cociente de polinomios $\frac{p(x)}{q(x)}$, con $q(x) \neq 0$.  
- **Ejemplo 2**: $g(y) = \frac{y^3 + 3y + 5}{y^2 + 1}$.  

### **Funciones Definidas por Partes**  
- **Ejemplo 5**:  
  $$
  s(x) = \begin{cases} 
  0, & x \text{ irracional} \\
  1, & x \text{ racional}.
  \end{cases}
  $$  

### **Funciones con Dominio Restringido**  
- **Ejemplo 4**: $r(x) = x^2$, definida solo para $-17 \leq x \leq \frac{\pi}{3}$.  

---

## Operaciones con Funciones  
### **Suma y Producto**  
Dadas $f$ y $g$:  
1. **Suma**: $(f + g)(x) = f(x) + g(x)$.  
2. **Producto**: $(f \cdot g)(x) = f(x) \cdot g(x)$.  
   - *Dominio*: Intersección de los dominios de $f$ y $g$.  

### **Composición**  
Dadas $f$ y $g$:  
$$ (f \circ g)(x) = f(g(x)) $$  
- *Dominio*: $\{ x \in \text{dominio}(g) \mid g(x) \in \text{dominio}(f) \}$.  

### **Propiedades Algebraicas**  
- **Asociatividad**:  
  $$ (f + g) + h = f + (g + h), \quad (f \cdot g) \cdot h = f \cdot (g \cdot h). $$  
- **Conmutatividad**:  
  $$ f + g = g + f, \quad f \cdot g = g \cdot f. $$  

---

## Construcción de Funciones Complejas  
### **Métodos de Combinación**  
1. **Uso de funciones elementales**: $I(x) = x$, $\text{sen}(x)$.  
2. **Composición iterada**:  
   - **Ejemplo 11**: $\text{sen}(\text{sen}(x^2)) = \text{sen} \circ \text{sen} \circ (I \cdot I)$.  

### **Notación Alternativa**  
- $x \to \text{sen}(x^2)$: Representa la función que mapea $x$ a $\text{sen}(x^2)$.  

---

## Ambiguidades y Precauciones  
1. **Notación ambigua**:  
   - "La función $x + t^3$" puede interpretarse como $x \to x + t^3$ o $t \to x + t^3$.  
2. **Dominio implícito**:  
   - $k(x) = \frac{1}{x} + \frac{1}{x-1}$ asume $x \neq 0, 1$.  

---

## Visualizaciones Clave  
### **Tabla de Pares Ordenados**  
$$
\begin{array}{c|c}
x & f(x) \\
\hline
1 & 1 \\
-1 & 1 \\
\pi & \pi^2 \\
\end{array}
$$  
> Ilustra la definición formal: cada $x$ tiene un único $f(x)$.  

---

## Conexiones y Aplicaciones  
1. **Cálculo de funciones compuestas**:  
   - Ejemplo: $f(r(s(\theta(\alpha_3(y(\frac{1}{3}))))) = 1$.  
2. **Relación con polinomios y funciones racionales**:  
   - Toda función polinómica es una combinación de $I$ y constantes mediante sumas y productos.  

---

