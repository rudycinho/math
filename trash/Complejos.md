**IV. Números complejos**

Los números reales tienen una deficiencia algebraica: no todas las ecuaciones cuadráticas tienen solución en ellos. Por ejemplo, $x^2 + 1 = 0$.

¿Qué hacemos? ¡Simple! Nos inventamos otros números. Tomemos los números reales:  
$$
-1, \quad 2, \quad \mathbb{R}
$$  
Creamos otros números:  
$$
-14, \quad 2, \quad -2, \quad -1
$$  
Con la condición de que:  
$$
(1^*)^2 = -1, \quad (2^*)^2 = -4, \quad (-1^*)^2 = -1, \quad (-2^*)^2 = -4,
$$  
es decir, $1^*$ y $-1^*$ son las soluciones de $x^2 + 1 = 0$.

Sumarlos es fácil: $a^* + b^* = (a + b)^*$. La multiplicación ya no es tan fácil: $a^* = a \cdot 1^*$; así:  
$$
(a^*) \cdot (b^*) = (a \cdot 1^*) \cdot (b \cdot 1^*) = a \cdot b \cdot (1^*)^2 = a \cdot b \cdot (-1) = -ab.
$$

Euler, que propuso estos números, les llamó **números imaginarios**.  
**FALTA** [*Nota: El texto original indica "FALTA", posiblemente por omisión en el escaneo*].

Es muy fácil verificar las siguientes propiedades:  
$$
(a,b) + (c,d) = (c,d) + (a,b);
$$  
$$
(a,b) + \left[(c,d) + (e,f)\right] = \left[(a,b) + (c,d)\right] + (e,f);
$$  
$$
(a,b) + (x,y) = (a,b) \quad \text{[Existencia del neutro aditivo]}.
$$

Antes, recordemos:  
$$
(a,b) = (c,d) \iff a = c \quad \text{y} \quad b = d.
$$

Hallemos el neutro aditivo:  
$$
(x,y) + (a,b) = (a,b)
$$  
$$
(x + a, y + b) = (a,b)
$$  
$$
\iff x + a = a \quad \land \quad y + b = b
$$  
$$
\iff x = 0 \quad \land \quad y = 0;
$$  
por tanto, $(x,y) = (0,0)$. Ahora hallemos el inverso aditivo de $(a,b)$:  
$$
(a,b) + (x,y) = (0,0)
$$  
$$
\iff (a + x, b + y) = (0,0)
$$  
$$
\iff a + x = 0 \quad \land \quad b + y = 0
$$  
$$
\iff x = -a \quad \land \quad y = -b,
$$  
por tanto $(x,y) = (-a,-b)$.

¿Cómo multiplicamos dos pares? La multiplicación está dada por:  
$$
(a,b) \cdot (c,d) = (ac - bd, \, ad + bc).
$$  
Aunque parezca complicada, esta definición es la única que nos da las propiedades que queremos.

Antes, dos definiciones: Dado el par $z = (a,b)$, la **parte real** es la primera componente $\operatorname{Re} z = a$, y la **parte imaginaria** es la segunda componente $\operatorname{Im} z = b$.

De aquí, un par de la forma $(a,0)$ "es" esencialmente un número real. Y los pares de la forma $(0,b)$ son los **números imaginarios puros**.

La multiplicación, como la hemos definido, satisface:  
- Conmutatividad: $(a,b) \cdot (c,d) = (c,d) \cdot (a,b)$  
- Asociatividad: $(a,b) \cdot \left[(c,d) \cdot (e,f)\right] = \left[(a,b) \cdot (c,d)\right] \cdot (e,f)$  
- Existencia del neutro multiplicativo: $\exists \, (x,y)$ tal que $(a,b) \cdot (x,y) = (a,b)$  
- Existencia del inverso multiplicativo para $(a,b) \neq (0,0)$: $\exists \, (x,y)$ tal que $(a,b) \cdot (x,y) = (1,0)$.

Hallemos el neutro multiplicativo:  
$$
(x,y) \cdot (a,b) = (a,b)
$$  
$$
(xa - yb, \, xb + ya) = (a,b)
$$  
$$
\iff 
\begin{cases} 
xa - yb = a \\ 
xb + ya = b 
\end{cases}
$$  
Si $(a,b) = (0,0)$, $(x,y)$ puede ser cualquier par. Entonces, asumamos $(a,b) \neq (0,0)$. Resolvamos el sistema:  
$$
\text{Multiplicando la primera ecuación por } a \text{ y la segunda por } b:
$$  
$$
a(xa - yb) = a^2 \implies a^2 x - aby = a^2
$$  
$$
b(xb + ya) = b^2 \implies b^2 x + aby = b^2
$$  
Sumando ambas:  
$$
(a^2 x - aby) + (b^2 x + aby) = a^2 + b^2
$$  
$$
(a^2 + b^2)x = a^2 + b^2
$$  
$$
\implies x = 1 \quad (pues \, a^2 + b^2 \neq 0)
$$  
Reemplazando en la primera ecuación: $1 \cdot a - yb = a \implies yb = 0 \implies y = 0$.  
Por tanto, $(x,y) = (1,0)$.

Ahora, hallemos el inverso de $(a,b) \neq (0,0)$: Buscamos $(x,y)$ tal que  
$$
(a,b) \cdot (x,y) = (1,0)
$$  
$$
(ax - by, \, ay + bx) = (1,0)
$$  
$$
\iff 
\begin{cases} 
ax - by = 1 \\ 
bx + ay = 0 
\end{cases}
$$  
Multiplicando la primera por $a$ y la segunda por $b$:  
$$
a(ax - by) = a \implies a^2 x - aby = a \quad \text{(1)}
$$  
$$
b(bx + ay) = 0 \implies b^2 x + aby = 0 \quad \text{(2)}
$$  
Sumando (1) y (2):  
$$
(a^2 x - aby) + (b^2 x + aby) = a + 0
$$  
$$
(a^2 + b^2)x = a \implies x = \frac{a}{a^2 + b^2}
$$  
De la segunda ecuación original: $bx + ay = 0$  
$$
\implies y = -\frac{b}{a} x = -\frac{b}{a} \cdot \frac{a}{a^2 + b^2} = -\frac{b}{a^2 + b^2} \quad (si \, a \neq 0)
$$  
Si $a = 0$, entonces $b \neq 0$, y resolviendo: $y = -\frac{1}{b}$ (coherente con la fórmula).  
Por tanto, el inverso es $(x,y) = \left( \frac{a}{a^2 + b^2}, \, -\frac{b}{a^2 + b^2} \right)$.

Es fácil verificar la distributividad:  
$$
(a,b) \cdot \left[ (c,d) + (e,f) \right] = (a,b) \cdot (c,d) + (a,b) \cdot (e,f).
$$  
Por tanto, el conjunto $\mathbb{R}^2$ con estas operaciones forma el **cuerpo de los números complejos** ($\mathbb{C}$). Un par ordenado $(a,b)$ es un **número complejo**. Los números complejos de la forma $(a,0)$ satisfacen:  
$$
(a,0) + (b,0) = (a+b, 0), \quad (a,0) \cdot (b,0) = (a \cdot b, 0).
$$  
Esto quiere decir que el subconjunto de $\mathbb{C}$:  
$$
\mathbb{R}' = \{ (a, 0) \mid a \in \mathbb{R} \}
$$  
es una copia isomorfa de $\mathbb{R}$. Y esto significa que podemos hacer la identificación:  
$$
a \equiv (a, 0).
$$  
En el plano $\mathbb{R}^2 = \mathbb{C}$, el par $(1,0)$ es el elemento neutro multiplicativo.

¿Qué rol juega el par $(0,1)$? Para empezar:  
$$
(0,1) \cdot (0,1) = (0 \cdot 0 - 1 \cdot 1, \, 0 \cdot 1 + 1 \cdot 0) = (-1, 0) \equiv -1.
$$  
Además:  
$$
(0,b) \cdot (0,1) = (0 \cdot 0 - b \cdot 1, \, 0 \cdot 1 + b \cdot 0) = (-b, 0) \equiv -b,
$$  
$$
(b,0) \cdot (0,1) = (b \cdot 0 - 0 \cdot 1, \, b \cdot 1 + 0 \cdot 0) = (0,b).
$$  
Por tanto, para cualquier $z = (a,b)$:  
$$
z = (a,b) = (a,0) + (0,b) = a \cdot (1,0) + b \cdot (0,1) \equiv a + b \cdot (0,1).
$$  
El número complejo $(0,1)$ recibe el nombre de **unidad imaginaria** y se denota:  
$$
i = (0,1).
$$  
Así,  
$$
z = (a,b) = a + b i,
$$  
y esta se llama la **forma binómica** del complejo $z$.

La unidad imaginaria satisface:  
$$
i^2 = -1, \quad i^3 = i^2 \cdot i = -i, \quad i^4 = i^2 \cdot i^2 = (-1) \cdot (-1) = 1.
$$  
**Ejemplos de operaciones:**  
$$
(2 + 3i) - (1 - 4i) = 1 + 7i,
$$  
$$
(2 + 3i)(1 - 4i) = 2 \cdot 1 + 2 \cdot (-4i) + 3i \cdot 1 + 3i \cdot (-4i) = 2 - 8i + 3i - 12i^2 = 2 - 5i + 12 = 14 - 5i \quad (\text{pues } i^2 = -1).
$$  
**Módulo de un complejo:** Sea $z = a + bi$, su módulo es $|z| = \sqrt{a^2 + b^2}$. Propiedades:  
$$
|z \cdot w| = |z| \cdot |w|, \quad |z^n| = |z|^n \quad (n \in \mathbb{N}), \quad |z + w| \leq |z| + |w|.
$$  
*Demostración de $|z \cdot w| = |z| \cdot |w|$:*  
$$
|z \cdot w|^2 = (z \cdot w) \cdot (\overline{z \cdot w}) = (z \cdot w) \cdot (\overline{z} \cdot \overline{w}) = (z \cdot \overline{z}) \cdot (w \cdot \overline{w}) = |z|^2 \cdot |w|^2.
$$  
Por tanto, $|z \cdot w| = |z| \cdot |w|$.

**Raíz cuadrada de un complejo:** Sea $z = a + bi$. Una raíz cuadrada de $z$ es un $w = x + yi$ tal que $w^2 = z$. Entonces:  
$$
w^2 = z \implies (x + yi)^2 = a + bi \implies (x^2 - y^2) + 2xy i = a + bi.
$$  
Igualando partes real e imaginaria:  
$$
x^2 - y^2 = a, \quad 2xy = b.
$$  
Además, por el módulo:  
$$
|w^2| = |z| \implies |w|^2 = |z| \implies x^2 + y^2 = \sqrt{a^2 + b^2}.
$$  
Resolvamos el sistema:  
1. Sumando las ecuaciones $x^2 - y^2 = a$ y $x^2 + y^2 = \sqrt{a^2 + b^2}$:  
$$
2x^2 = a + \sqrt{a^2 + b^2} \implies x^2 = \frac{a + \sqrt{a^2 + b^2}}{2}, \quad x = \pm \sqrt{ \frac{a + \sqrt{a^2 + b^2}}{2} }
$$  
2. Restándolas:  
$$
2y^2 = \sqrt{a^2 + b^2} - a \implies y^2 = \frac{ \sqrt{a^2 + b^2} - a }{2}, \quad y = \pm \sqrt{ \frac{ \sqrt{a^2 + b^2} - a }{2} }
$$  
La ecuación $2xy = b$ determina los signos: si $b > 0$, $x$ e $y$ mismo signo; si $b < 0$, signos opuestos. Así:  
$$
w = \pm \left( \sqrt{ \frac{a + \sqrt{a^2 + b^2}}{2} } + i \cdot \operatorname{sgn}(b) \sqrt{ \frac{ \sqrt{a^2 + b^2} - a }{2} } \right) \quad \text{[*Nota: $\operatorname{sgn}(b)$ ajusta el signo según $b$*]}.
$$  
**Ejemplo 1:** Raíces cuadradas de $z = -4$.  
$$
|z| = \sqrt{(-4)^2 + 0^2} = 4,
$$  
$$
x^2 = \frac{-4 + 4}{2} = 0 \implies x = 0,
$$  
$$
y^2 = \frac{4 - (-4)}{2} = 4 \implies y = \pm 2.
$$  
Como $b = 0$, no hay restricción de signos. Soluciones: $w = \pm 2i$ (pues $(2i)^2 = -4$).

**Ejemplo 2:** Raíces cuadradas de $z = -4 - 3i$.  
$$
|z| = \sqrt{(-4)^2 + (-3)^2} = 5,
$$  
$$
x^2 = \frac{-4 + 5}{2} = \frac{1}{2} \implies x = \pm \frac{\sqrt{2}}{2},
$$  
$$
y^2 = \frac{5 - (-4)}{2} = \frac{9}{2} \implies y = \pm \frac{3\sqrt{2}}{2}.
$$  
Como $b = -3 < 0$, los signos de $x$ e $y$ son opuestos:  
- Si $x = \frac{\sqrt{2}}{2}$, entonces $y = -\frac{3\sqrt{2}}{2}$  
- Si $x = -\frac{\sqrt{2}}{2}$, entonces $y = \frac{3\sqrt{2}}{2}$.  
Soluciones: $w = \frac{\sqrt{2}}{2} - i \frac{3\sqrt{2}}{2}$ y $w = -\frac{\sqrt{2}}{2} + i \frac{3\sqrt{2}}{2}$.

Lastimosamente, este método no se puede extender fácilmente a raíces superiores.

