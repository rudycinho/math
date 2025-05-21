Problema
Victor y Maria empiezan a trabajar el mismo dia. Victor trabaja tres días segundos y luego tiene un dia libre. Maria trabaja siete días seguidos y descansa tres. Cuantos días de descanso tuvieron los dos juntos durante los 1000 días?
Solución
![[Pasted image 20250219212730.png]]
Por lo tanto, Victor y Maria cada 20 días, descansan dos veces. Por los 1000 días, descansaran 100 días.

Problema
La siguiente figura muestra castillos de naipes 1,2 y 3 plantas. Para construir estos castillos se utilizaron 2,7 y 15 cartas respectivamente. Cuantas cartas se necesitaran para construir un castillo de 10 pisos?
![[Pasted image 20250219214122.png]]
Solución. 
Sea $a_n$ el numero de cartas para la n-esima planta
$$
\begin{aligned}
	\boxed{n=1} &\quad a_1=2\\
	\boxed{n=2} &\quad a_2=2+5=7\\
	\boxed{n=3} &\quad a_3=7+8=15\\
	\boxed{n=4} &\quad a_4=15+11=26\\[3pt]
	&\quad a_5 = 26+14=40\\[3pt]
	&\quad a_6 = 40+17=57\\[3pt]
	&\quad a_7 = 57+20=77\\[3pt]
	&\quad a_8 = 77+23=100\\[3pt]
	&\quad a_9 = 100+26=126\\[3pt]
	&\quad a_{10} = 126+29=155
\end{aligned}
$$

Sumamos:
$$
	\begin{aligned}
		a_1 &= 2\\
		a_2 &= a_1 + 3\cdot1 + 2\\
		a_3 &= a_2 + 3\cdot2 + 2\\
		a_4 &= a_3 + 3\cdot3 + 2\\
		\vdots \\
		a_n &= a_{n-1} + 3\cdot(n-1) + 2\\
		\hline
		a_1+a_2+a_3+\dots+a_n &= 2+a_1+a_2+a_3+\dots+a_{n-1}+3\cdot1+3\cdot2+3\cdot3+\dots+3\cdot(n-1)+\overbrace{2+2+2+\dots+2}^{n-1}\\
		a_n &= 3\cdot(1+2+3+\dots+(n-1)) + 2\cdot n\\
		a_n &= 3\cdot \frac{(n-1)\cdot n}{2} + 2\cdot n\\		
		a_n &= n \cdot \left( \frac{3\cdot(n-1)}{2}+2\right)\\		
		a_n &= n \cdot \left( \frac{3\cdot n-3+4)}{2}\right)\\
		\text{luego, } a_n &= \frac{n}{2} \cdot (3\cdot n +1)	
	\end{aligned}
$$

Para $a_{10}$

$$
	\begin{aligned}
		a_{10} &= \frac{10}{2} \cdot (3 \cdot 10 + 1)\\
		a_{10} &= 5 \cdot (31)\\
		a_{10} &= 155
	\end{aligned}
$$



Problema
Para construir el siguiente arrego que tiene 2008 lineas (filas), se sigue la siguiente regla.

![[Pasted image 20250219232522.png]]

a. Cuantas veces aparece la palabra MAT completa en la columna mas grande de este arreglo?
b. Cuantas veces aparece la letra M en el arreglo?

Solucion 
a. La columna mas grande es de 2008 letras, pues tenemos 2008 filas (dato). Como sabemos que la palabra MAT tiene 3 letras, dividimos las 2008 letras entre 3 letras, el cual se obtiene 669 palabras MAT.

Es decir:

![[Pasted image 20250219233031.png]]

$$2008 = 3\cdot669 + 1$$

Solucion 
b. Para contar el total de letras M, procedemos de la siguiente manera:
![[Pasted image 20250219233646.png]]

$$
	\begin{aligned}
		2008 + 2005 + 2002 + 1999 + \dots + 4 + 1 &= \\ 
		\boxed{3\cdot669+1} + \boxed{3\cdot668+1} + \boxed{3\cdot667+1} + \boxed{3\cdot666+1} + \dots + \boxed{3\cdot1+1} \cdot \boxed{3\cdot0+1} &= 3\cdot(669+668+667+666+\dots+1+0) + \overbrace{(1+1+1+1+\dots+1+1)}^{\text{670-veces}}\\
		&= 3\cdot\left(\frac{669\cdot670}{2}\right)+670\cdot1\\
		&= 670\cdot\left(\frac{3\cdot669}{2}+1\right)\\
		&= 670\cdot\left(\frac{2009}{2}\right)\\
		&= 335\cdot2009\\
		&= 673015 \qquad \blacksquare \\
	\end{aligned}
$$


Problema.
En una cuadricula numerada siguiendo un camino poligonal, tal como la gráfica, Cuales son los números de los puntos justo/debajo y a la izquierda del punto 2001? 

![[Pasted image 20250221140203.png]]

Solución.
Notemos:
1. Los cuadrados perfectos pares se encuentran en el eje vertical.
2. Los cuadrados perfectos impares se encuentran en el eje horizontal.
3. Ademas el 2001, esta entre los cuadrados perfectos $44^2$ y $45^2$ 
$$
	\begin{aligned}
		\text{i.e.} &\qquad 44^2 < 2001 < 45^2 \\
		&\qquad 1936 < 2001 < 2025
	\end{aligned}
$$

$$2025-2001=24$$
$$43^2=1849+1 = 1850$$
$$1850+24=1874$$

De acuerdo a lo explicado, el numero que se encuentra debajo de 2001 es 2002. Y a la izquierda se encuentra 1874.

Problema.
En una mesa 2010 fósforos se apilan en forma de escalera.
![[Pasted image 20250221144328.png]]

a. Cual es la escalera del ultimo fósforo?
b. En que nivel esta la cabeza del ultimo fósforo?

Solución
Sea $a_n$ la cantidad de fósforo de la n-esima escalera
$$
	\begin{align}
		a_1 &= 5\\
		a_2 &= a_1 + 4\\
		a_3 &= a_2 + 4\\
		\vdots \\
		a_n &= a_{n+1} + 4\\
		\hline
		a_1+a_2+a_3+\dots+a_{n-1}+a_n &= 5+a_1+a_2+a_3+\dots+a_{n-1}+4(n-1)\\
		a_n &= 5 + 4 \cdot (n-1)\\
		a_n &= 4 \cdot n-1
	\end{align}
$$

La suma

$$
	\begin{align}
	 S_n &= a_1+a_2+a_3+\dots+a_n\\
	 &= (4\cdot1+1)+(4\cdot1+1)+(4\cdot1+1)+\dots+(4\cdot1+1)\\
	 &= 4\cdot(1+2+3+\dots+n)+n\\
	 &= 4\cdot \frac{n\cdot(n+1)}{2}+n\\
	 &= n\cdot ( 2\cdot(n+1)+1)\\
	 &= n\cdot ( 2\cdot n+3)\\
	 &= n^2 + 3\cdot n\\
	 S_n &= n^2 	 
	\end{align}
$$

La suma de las primeras n-esimas escaleras

$$
	(S_1=5, S_2=14, S_3=27)
$$

Notemos que la suma de los n-esimas escaleras se aproxima a $2 n^2$
$$
\begin{align}
S_n &\approx 2 \cdot n^2 \\
2010 &\approx 2 \cdot n^2 \\
\sqrt{\frac{2010}{2}} &\approx n\\
\sqrt{1005} &\approx n\\
31.70 &\approx n\\
\end{align}
$$

$$
\text{Si } n=31 , \qquad S_{31} = 31\cdot(2\cdot 31 + 3) = 31 \cdot 65 = 2015
$$

![[Pasted image 20250221161117.png]]

