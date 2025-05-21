
# Funciones y gráficas

## Definicion (Intuitiva) 
Una funcion es una regla de correspondencia (relacion) que asigna a **cada elemento** de un cierto conjunto de múmeros (llamado el dominio de la función) en otro número (único).

Ejemplos

1. La regla de correspondencia que asigna a cada número $x \neq 10$ un número y tal que $x \cdot y = 1$   $(y = x^{- 1})$.

2. La regla de correspondencia que asigna a cada número $x \geq 0$ un número $y \geq 0$ tal que $y^2=x$   $(y = \sqrt x)$

## Notación

Si llamamos $f$ a la funcion y $A \in \mathbb R$ es su dominio. La notación habitual es 
$$
\underbrace{f}_{\text{nombre de la funcion}}  \overbrace{\mathbb A }^{\text{dominio de } f} \rightarrow \underbrace{\mathbb R }_{\text{codominio de } f}
$$

Si $x \in \mathbb A$ , el valor $y$ que le corresponde por $f$ se denota como

$$
\underbrace{y}_{\text{imagen de x por f}}  =  \underbrace{f(x)}_{\text{se lee "f de x" o "f aplicado a x"}}  
$$
$$\boxed{\mathbb A \xrightarrow{f} \mathbb R}$$
 $$\boxed{f: \mathbb A \longmapsto \mathbb R \qquad x \longmapsto y = f(x)}$$
$$
\boxed{
	\begin{aligned}
	f: \mathbb A &\rightarrow \mathbb R \\ 
	x &\longmapsto f(x)
	\end{aligned}
}
$$

Mas ejemplos
$$
	\begin{aligned}
		&f: \mathbb R \rightarrow \mathbb R \qquad \text{def. como}\\
		&f(x) = x^2 - 2x + 3
	\end{aligned}
$$

$$
	\begin{aligned}
		&g: \mathbb R \rightarrow \mathbb R \qquad \text{def. como}\\
		&g(x) = \left\{
		\begin{array}
			\\-7      &, \text{si } x \geq 1\\
			\sin(x) &, \text{si } x < 1
		\end{array}
		\right.\\
	\end{aligned}
$$
$$
	\begin{aligned}
		&h: \mathbb R \rightarrow \mathbb R \qquad \text{def. como}\\
		&h(x) = \left\{
		\begin{array}
			\\1 ,& \text{si } x \in \mathbb Q\\
			0 ,& \text{si } x \in \mathbb Q^c
		\end{array}
		\right.\\
	\end{aligned}
$$


$$
	\begin{aligned}
		&f_n = \left\{
		\begin{array}
			\\1      &, n=1\\
			1      &, n=2\\
			f_{n-1} + f_{n-2} &, n\geq 3
		\end{array}
		\right.\\\\
	&1 \qquad 1 \qquad 2 \qquad 3 \qquad 5 \qquad 8 \qquad 13 \qquad 
	\end{aligned}
$$

Secuencias
Son funciones $a : \mathbb N \rightarrow \mathbb R$
$$
\begin{align}
a(n) &= a_n   \\
a_n &= (-1)^n \\\\
a_1&=-1 \\ a_2&=1 \\ a_3&=-1 \\ a_4&=1 \\ a_5&=-1
\end{align}
$$

$$
\begin{align}
b_n &= \frac{1}{n} \\\\
&1 \quad \frac{1}{2} \quad \frac{1}{3} \quad \frac{1}{4} \quad \frac{1}{5}  
\end{align}
$$

$$
\begin{align}
	c_n &= 10^{-n} \rightarrow 
	c_n = 
	\left\{
		\begin{matrix}
			\frac{1}{10} , n=1\\
			\frac{1}{10} \cdot c_{n-1}, n \geq 2
		\end{matrix}
	\right.\\
	&0.1 \quad 0.01 \quad 0.001 \quad 0.0001 \\  
	&\frac{1}{10} \quad \frac{1}{100} \quad \frac{1}{1000} \quad \frac{1}{10000}  
\end{align}
$$

$$
\begin{align}
	d_n = 
	\left\{
		\begin{matrix}
			2^n ,& n \text{ par}\\
			(-1)^n \cdot \frac{1}{n} ,& n \text{ impar}
		\end{matrix}
	\right.\\\\
	-1 \quad 4 \quad -\frac{1}{3} \quad 16 \quad -\frac{1}{5}  \quad 64  
\end{align}
$$

$$
\begin{align}
	y(x) = 
	\left\{
		\begin{matrix}
			n ,& \text{ si aparecen exactamente n 7's en el desarrollo decimales de x}\\
			n ,& \text{ si apaarecen infinitos 7's en el desarrollo decimales de x}\\
			3
		\end{matrix}
	\right.\\
	\\\\
	y(0.173) = 1\\	
	y(\frac{1}{3}) = 0\\	
	y(\pi) = ?\\	
	y(\sqrt 2) = ?\\	
\end{align}
$$




## Definicion(Igualdad)

Sean $f \; \mathbb A \rightarrow \mathbb{R}$ y $g  \; \mathbb{B}  \rightarrow \mathbb{R}$ funciones, diremos que $f$ es igual a $g$ $(f \equiv g)$, si $\mathbb A = \mathbb B$ y $f(x)=g(x)$, para $x \in \mathbb A = \mathbb B$.

$$
\begin{aligned}
f \; \mathbb R \rightarrow \mathbb R &:\quad  x \mapsto f(x) = x ^ 2 - 2x + 1 \\ 
g \; [-5,5] \mapsto \mathbb R &: \quad x \mapsto g(x) = (x - 1) ^ 2 = x ^ 2 - 2x + 1\\\\
f(2)=1 & \qquad f(6)=25\\
f(2)=1 & \qquad g(6)=\text{ no existe}
\end{aligned}
$$

![[Pasted image 20250225151358.png]]

Cuando no se especifica el dominio de una función, asumimos que el dominio es el mayor conjunto donde la función puede ser evaluada

$$
	\begin{aligned}	
		&f(x) = \frac{x^2 - 3x + 1}{x^2 - 3}, \; x \neq \sqrt 3, -\sqrt 3\\
		&f : \; \mathbb R \, \setminus \{\sqrt{3},-\sqrt{3},\} \rightarrow \mathbb R
	\end{aligned}	
$$


$$f(x) = \sqrt{\sin(x)}$$
$$0 < x < \pi$$
$$
\sin x \geq 0
$$

![[Pasted image 20250225004334.png]]
$$
\begin{align}
	-2\pi \leq &x \leq - \pi \\
	0 \leq &x \leq \pi \\
	2\pi \leq &x \leq 3 \pi\\
	4\pi \leq &x \leq 5 \pi\\
\end{align}
$$$$A=\{x \in \mathbb R / 2 k \pi \leq x \leq (2k+1) \pi, k \in \mathbb Z\}$$ 

$g(x) = \ln(\sin(x))$
$h(x) = \sin(\ln(x))$





## Operaciones con funciones

### Suma de funciones

Sean $f \; \mathbb A \rightarrow \mathbb R$ y $f \; \mathbb B \rightarrow \mathbb R$, la suma de $f$ y $g$ es la funcion
$$f + g \quad \mathbb A \cap \mathbb B \rightarrow \mathbb R$$
definida como

$$(f + g)(x) = f(x) + g(x)$$

### Producto de funciones 
Sean $f \; \mathbb A \rightarrow \mathbb R$ y $f \; \mathbb B \rightarrow \mathbb R$, el producto de $f$ y $g$ es la función

$f \cdot g \quad \mathbb A \cap \mathbb B \rightarrow \mathbb R$

definida como

$(f \cdot g)(x) = f(x) \cdot g(x)$

### Cociente de funciones 
Sean $f \; \mathbb A \rightarrow \mathbb R$ y $g \; \mathbb B \rightarrow \mathbb R$, el producto de $f$ y $g$ es la funcion 

$\frac{f}{g} \quad \mathbb A \cap \{x \in \mathbb B \quad g(x) \neq 0\} \rightarrow \mathbb R$

definida como

$\frac{f}{g}(x) = \frac{f(x)}{g(x)}$

---

$f(x) = \sqrt{\sin x} + \ln(\cos x)$

$\sin x \geq 0$
![[Pasted image 20250225175001.png]]
$$
\begin{align}
	-\frac{\pi}{2} < &x < \frac{\pi}{2}\\
	\frac{3\pi}{2} < &x < \frac{5\pi}{2}\\
	\frac{7\pi}{2} < &x < \frac{9\pi}{2}
\end{align}
$$



$2k\pi - \frac{\pi}{2} \leq x \leq (2k+1) \pi - \frac{\pi}{2}$ 
$(4k-1) \frac{\pi}{2} < x < (4k+1) \frac{\pi}{2}$


$(2k + 1) \frac{\pi}{2} < x < (2k + 3) \frac{\pi}{2}$

$A=\{ x \in \mathbb R /\;2k \pi \leq x \leq (2k+1) \pi, k \in\mathbb Z\}$
$B=\{ x \in \mathbb R /\; (4k-1) \frac{\pi}{2} < x < (4k+1) \frac{\pi}{2}, k \in\mathbb Z\}$
