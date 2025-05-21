# Principio de Induccion
Para utilizar este principio, procedemos de la siguiente manera:
**Base de Induccion.** 
$\boxed{n=1}$ para $\boxed{p(n)}$ ( formula o enunciado $n \in \mathbb N$ ) 

**Hipotesis de Induccion.** 
$\boxed{n=k}$ para $\boxed{p(k)}$ (verdadero) 

**Base de Induccion.** 
$\boxed{n=k+1}$ para $\boxed{p(k+1)}$ (Por demostrar) 


Ejemplo. Sea $t_n =$ el n-esimo numero triangular.


$$
	\begin{aligned}
	t_1 &= 1 \\
	t_2 &= 3 \\
	t_3 &= 6 \\
	t_4 &= 10
	\end{aligned}
$$

![[Pasted image 20250218181323.png]]



$$
	\begin{aligned}
		t_1 &= 1\\
		t_2 &= 1+2 = 3\\
		t_3 &= 1+2+3 = 6\\
		t_4 &= 1+2+3+4= 10\\
		\vdots\\
		t_n &= 1+2+3+\dots+n= \frac{n\cdot(n+1)}{2}
	\end{aligned}
	$$

Problema. Probar que la siguiente igualdad $$\boxed{1+2+3+4+\dots+n= \frac{n\cdot(n+1)}{2}}$$se cumple para todo entero positivo "n".

Demostracion. Sea $p(n)$ : $1+2+3+\dots+n= \frac{n\cdot(n)+1}{2}$
1. Base : $\boxed{n=1}$ , $p(1)$ verdadero

$$
	\begin{aligned}
		1 &= \frac{1\cdot(1+1)}{2}\\	
		1 &= 1	
	\end{aligned}
$$

1. Hipotesis de Induccion: $\boxed{n=k}$
	$$p(k) : 1+2+3+\dots+k= \frac{k\cdot(k+1)}{2} \qquad\text{(verdadero)}$$  
	Tesis de Induccion: $\boxed{n=k+1}$
	$$p(k+1) : 1+2+3+\dots+k+(k+1) \stackrel{?}{=} \frac{(k+1)\cdot(k+2)}{2}$$
	Prueba:
$$
\begin{aligned}
    1+2+3+\dots+k+(k+1) &= \frac{k\cdot(k+1)}{2} + k + 1  && \text{Hipótesis de inducción} \\
    &= \frac{k^2+k+2k+2}{2}  && \text{Propiedades de Reales} \\
    &= \frac{k^2+3k+2}{2}  && \text{Clausura en } \mathbb{R} \\
    &= \frac{(k+1)\cdot(k+2)}{2}  && \text{Propiedad Distributiva}
\end{aligned}
$$
Por tanto, $p(n)$ se cumple $\forall n \in \mathbb N$
Problema: 
Probar la siguiente igualdad $$1+2+2^2+2^3+\dots+2^{n-1}+2^n = 2^{n-1} - 1$$se cumple para todo entero positivo "n".

Demostracion.
Sea $$p(x) : 2^0+2^1+2^2+\dots+2^n=2^{n+1}-1$$
1. Base:
	$\boxed{n=0} \;,\; p(0) :$
	$$
	\begin{aligned}
		2^0 &= 2^{0+1}-1\\
		1&=1
	\end{aligned}
	$$
	$\boxed{n=1} \;,\; p(1) :$
	$$
	\begin{aligned}
		2^0+2^1 &= 2^{1+1}-1\\
		3&=4-1\\
		3&=3
	\end{aligned}
	$$
2. H.I. $\boxed{n=k}$
					$$1+2+2^2+\dots+2^k=2^{k+1}-1 \qquad\text(verdadero)$$ 
	T.I. $\boxed{n=k+1}$
	$$1+2+2^2+\dots+2^k+2^{k+1} \stackrel{?}{=} 2^{k+2}-1 $$ 
	Prueba:
	$$
	\begin{aligned}
		1+2+2^2+\dots+2^k+2^{k+1} &= 2^{k+1}-1+2^{k+1}\\
		&= 2^1\cdot2^{k+1}-1\\
		&= 2^{k+2}-1
	\end{aligned}
	$$

	Por tanto , $p(n)$ se cumple para todo entero positivo incluido el cero ("$n$") $\blacksquare$

	$$
	\begin{aligned}
		-1-2-2^2-\dots-2^{n-1}-2^n &= -x\\
		2+2^2+2^3+\dots+2^n+2^{n+1} &= 2x\\
		\hline
		2^{n+1}-1 &= x  
	\end{aligned}
	$$

Problema 3.
Demostrar que la suma de los angulos interiores de cualquier poligono **convexo** de n-lados es $\boxed{180^\circ \cdot (n-2)}$para todo entero positivo $n\geq3$.
Demostracion


![[Pasted image 20250218203708.png]]![[Pasted image 20250218203753.png]]

Para la demostracion utilizamos el principio de induccion sobre el numero de lados "$n$".

1. Caso Base $\boxed{n=3}$
	La suma de los angulos interiores de un poligono de $n=3$ lados es : $180^\circ \cdot (3-2)=180^\circ$.
2. Hipotesis de Induccion $\boxed{n=k}$
	La suma de los angulos interiores de un poligono de $n=k$ lados es $180^\circ \cdot (k-2)$.
	Tesis de Induccion $\boxed{n=k+1}$
	Para Demostrar:
	La suma de los angulos interiores de un poligono de $n=k+1$ lados es: 
	$$180^\circ(k-1)$$
	Prueba. Consideramos un poligono de $(k+1)$ lados donde $P_1,P_2,P_3,\dots,P_k,P_{k+1}$ son los vertices de dicho poligono.
	Por hipotesis de induccion sabemos que la suma de los angulos interiores de un poligono de $k$ lados es $\boxed{180^\circ \cdot (k-2)}$ .
	Luego de acuerdo a la figura tenemos un triangulo $\triangle\;P_1\;P_k\;P_{k+1}$ , la suma de los angulos internos de este triangulo  mas la suma de los angulos internos del poligono de $k$ lados.
	
![[Pasted image 20250218210929.png]]
	Tenemos:
	$$180^\circ + 180^\circ \cdot (k-2) = 180^\circ \cdot (k-1)  $$
	$$\therefore 180^\circ \cdot (k-2) \quad \forall n \in \mathbb N, n\geq3 \qquad \blacksquare$$
	
Problema 4
Probar que $(11^{n+1}+12^{2n-1})$ es multiplo de 133, para cualquier entero positivo "$n$".
Demostracion
Para la prueba vamos a utilizar el principio de induccion sobre $\text{``}n\text{''} \in \mathbb{N}$.

1. Caso Base: 
	$\boxed{n=1}$ 
	$11^{1+1}+12^{2\cdot1-1} = 11^2+12^1 = 121 + 12 = 133$
	$\boxed{n=2}$ 
	$11^{2+1}+12^{2\cdot2-1} = 11^3+12^3 = 3059 = 23\cdot133$
2. Hipotesis de Induccion
	$\boxed{n=k}$
	$11^{k+1} + 12^{2\cdot k-1}$ es multiplo de 113.
	
	Tesis de Induccion
	$\boxed{n=k+1}$
	$11^{k+1} + 12^{2\cdot k+1}$ es multiplo de 113. (P.D.)
	
	![[Pasted image 20250218224506.png]]

	$$
	\begin{align}
		17 &= 5\cdot3 + 2 \\
		17 &= 2 + 5\cdot3 \\
		17 - 2 &= 5\cdot3 \\
		5 \; &| \; (17-2) \\
		17 &\underbrace{\equiv}_{\text{congruencia}} 2 \pmod {5} 
	\end{align}
	$$
	
	$$
	\begin{align}
		5 &\equiv 1 \pmod{2} \\
		2  &| (5-1)
	\end{align}
	$$

	Prueba: 
	$$
	\begin{align}
		11^{k+1} + 12^{2\cdot k-1} &\equiv 0 \pmod{133} & \text{Hipotesis Induccion}\\
		144\cdot(11^{k+1} + 12^{2\cdot k-1}) &\equiv 144\cdot0 \pmod{133} & \text{Multiplicando 144}\\
		12^2\cdot11^{k+1} + 12^2\cdot12^{2\cdot k-1} &\equiv 0 \pmod{133} & \text{Propiedad Distributiva}\\
			
	\end{align}
	$$
	Por otro lado, tenemos:
	$$
		\begin{align}
			133 \qquad &| \qquad(11x - 12^2 x)\\ 
			11\cdot11^{k+1} &\equiv 12^2\cdot11^{k+1} \pmod{133} \\
			11\cdot11^{k+1} + 12^2\cdot12^{2\cdot k-1}  &\equiv 12^2\cdot11^{k+1} + 12^2\cdot12^{2\cdot k-1} \pmod{133} & \text{Sumando a ambos miembros}\\
			11\cdot11^{k+1} + 12^2\cdot12^{2\cdot k-1}  &\equiv 0 \pmod{133} & \text{Por la transitividad de la congruencia}\\
		\end{align}
	$$
	$$\therefore 11^{k+2}+11^{2\cdot k+1} \text{ es multiplo de } 133 \;\blacksquare$$
	
	$$133 | (11-12^2) \Leftrightarrow 133 | (-133)$$
	![[Pasted image 20250218234455.png]]