
# Examen 1

**Nombre completo:** \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_
**C.I.:** \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_


1. Sean m y n son enteros positivos tales que $n + n^3 + n^5 = m + m^2$. Probar que $n$ es par.

	Por contradicion decimos que n es impar.
	
	Primero demostracion las potencias:

	sea x in Z
	x = 2k+1
	x2 = x\*x =(2k+1)(2k+1) = 4k2 + 4k + 1 = 2(2k2+2k)+1 = 2l + 1, l in math bb Z  por tanto x2 es impar
	x3 = x2\*x =(2l+1)(2k+1) = 4kl + 2k + 2l + 1 = 2(2kl + k + l)+1 = 2s + 1, s in math bb Z  por tanto x3 es impar
	x5 = x3\*x2 = (2s + 1)(2l + 1) = 4sl + 2s + 2l + 1 = 2(2sl + s + l)+1 = 2t + 1, t in math bb Z  por tanto x5 es impar

	sea y in Z
	y = 2k
	y2 = y\*y = (2k)(2k) = 4k2 = 2(2k2) , por tanto y2 es par

		
	lado izquierdo
	
	n + n3 + n5 = impar + impar  + impar = impar
	lado derecho.
	caso 1. m es par.
		dado que m es par entonces tenemos que:
		n + n2 = par + par = par
		por lo que no puede ser.
	caso 2. m es impar
		dado que m es impar entonces tenemos que 
		n + n2 = impar + impar = par
		por lo que no puede ser
	igualando los lados notamos
	impar = par
	esto es imposible, por lo tanto n es par.
	
2. Probar que todo entero positivo $n$ se puede expresar como la suma de una o más potencias de 2, distintas entre sí.

decimos que el numero n se encuentra acotado entre dos potenciss de base 2.
2^x <= n < 2^(x+1) , donde x in Z

Caso base:
	n = 1 -> 2^0 <= 1 < 2^1 -> 1 <= 1 < 2 -> x=0    
	n = 2 -> 2^1 <= 2 < 2^2 -> 2 <= 2 < 4 -> x=1    
	n = 3 -> 2^1 <= 3 < 2^2 -> 2 <= 3 < 4 -> x=1 , 3 se puede expresar como como la suma de 2 y 1, ambos demostrados
Hipotesis de induccion:
	k < n
	2^x <= k < 2^(x+1)
Tesis de inducuin:
	2^x <= n < 2^(x+1)
	Tomamos la parte:
	n < 2^(x+1)
	n < 2^x+ 2^1 
	n < 2^x \* 2^1 
	n < 2\*2^x 
	n < 2^x+2^x 
	n -2^x < 2^x 
	esta expresion es la suma de potencias de base 2, menores que 2^x.
	notamos que 2^x <= n, se puede expresar como:
	n = 2^x + (n -2^x), donde (n -2^x) ya esta demostrado
	por tanto todo n puede ser represrntaod

**Demostración por inducción fuerte:**

- **Base:**
    
    - n=1=20n=1=20.
        
    - n=2=21n=2=21.
        
    - n=3=21+20n=3=21+20.  
        Se cumple.
        
- **Hipótesis inductiva:** Supongamos que todo entero kk con 1≤k<n1≤k<n puede expresarse como suma de potencias de 2 distintas.
    
- **Paso inductivo:**  
    Sea xx el mayor entero tal que 2x≤n2x≤n. Entonces:
    
    2x≤n<2x+1.2x≤n<2x+1.
    - Si n=2xn=2x, entonces nn es una potencia de 2.
        
    - Si n>2xn>2x, sea r=n−2xr=n−2x. Como r<2xr<2x (porque n<2x+1=2⋅2xn<2x+1=2⋅2x), y r≥1r≥1, entonces r<nr<n. Por hipótesis inductiva, rr es suma de potencias de 2 distintas, todas menores que 2x2x (ya que r<2xr<2x).
        
    - Por tanto, n=2x+rn=2x+r es suma de potencias de 2 distintas.
        

**Ejemplo:** n=10n=10.

- 23=8≤10<1623=8≤10<16, r=10−8=2=21r=10−8=2=21.
    
- 10=8+2=23+2110=8+2=23+21.

3. Consideremos los números enteros del 1 al 2025.
   ¿Cuántos de estos números tienen una suma de dígitos que es múltiplo de 5?

en el rango de 1 al 9 :
	tenemos solo el numero 5
en el rango de 10 al 99 tenemos:
	en un rango de 10 numeros tenemos 2 numeros:
		10 -> no,
		11 -> no,
		12 -> no,
		13 -> no,
		14 -> si, 1+4 mod 5 = 0
		15 -> no,
		16 -> no,
		17 -> no,
		18 -> no,
		19 -> si, 1+9 mod 5 = 0
	entonces:
		99-10+1= 90.
		tememos por regla de 3: 
			10 ---- 2
			90 ---- x
		10 x = 90 \* 2 => x = 18
 en 	el rango de 100 al 999
		999-100+1= 900.
		tememos por regla de 3: 
			10  ---- 2
			900 ---- x
		10 x = 900 \* 2 => x = 180
 en 	el rango de 1000 al 1999
		1999-1000+1= 1000.
		tememos por regla de 3: 
			10  ---- 2
			1000 ---- x
		10 x = 1000 \* 2 => x = 200
 en el rango de 2000 al 2019
		2019-2000+1 = 20.
		tememos por regla de 3: 
			10  ---- 2
			20 ---- x
		10 x = 20 \* 2 => x = 4
 en el rango de 2020 al 2025
 2020 = 2 + 0 + 2 + 0 = 4 => no
 2021 = 2 + 0 + 2 + 1 = 5 => si
 2022 = 2 + 0 + 2 + 2 = 4 => no
 2023 = 2 + 0 + 2 + 2 = 4 => no
 2024 = 2 + 0 + 2 + 2 = 4 => no
 2025 = 2 + 0 + 2 + 2 = 4 => no

por tanto tenemos:
1 + 18 + 180 + 200 + 4 + 1 = 
		 
	
5. ¿Cómo se puede cortar un rectángulo de dimensiones $13\times7$ en 13 rectángulos de áreas y dimensiones diferentes?

basta con dibular un rectangulo 13x7
en la filas colocamos:
13 cuadrados
1 cuadrado , 12 cuadrados
2 cuadrads , 11 cuadrados
3 cuadrads , 10 cuadrados
4 cuadrads , 9 cuadrados
5 cuadrads , 8 cuadrados
6 cuadrads , 7 cuadrados

5. ¿Existe una solución entera para la ecuación $a \cdot b \cdot (a - b) = 45045\;$?

lado derecho
45045 es impar

lado izquierdo:

a es par y b es par
tenemos a\*b\*(a-b) = P\*P\*(P-P) = P 
a es par y b es impar
tenemos a\*b\*(a-b) = P\*I\*(P-I) = P 
a es impar y b es par
tenemos a\*b\*(a-b) = I\*P\*(I-P) = P 
a es impar y b es impar
tenemos a\*b\*(a-b) = I\*I\*(I-I) = I\*I\*P = P 

en tondos los caso es par

tenemos:
par = impar, por lo que no existen enters que satisfagan la ecuacion


# Examen 2

**Nombre completo:** \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_
**C.I.:** \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_

1. ¿Para qué valores naturales $n$ es posible cubrir completamente un rectángulo de tamaño $3\times n$ con las piezas mostradas en la siguiente figura, sin superposiciones ni dejar espacios vacíos?
\begin{tikzpicture}
  % Cuadro base
  \foreach \x/\y in {0/0, 1/0, 0/1} {
    \draw[thick] (\x,\y) rectangle ++(1,1);
    \fill[blue!30] (\x,\y) rectangle ++(1,1);
  }
\end{tikzpicture}
\begin{tikzpicture}
  % Cuadro base
  \foreach \x/\y in {0/1, 1/1, 1/0, 2/0} {
    \draw[thick] (\x,\y) rectangle ++(1,1);
    \fill[red!30] (\x,\y) rectangle ++(1,1);
  }
\end{tikzpicture}

caso 1. 
el area 3n es divisible por 3. para evitar los huevos n de ser par y mayor que 2.

caso 2.
no es posible, debido a que nunca llenara los huecos

2. En cada casilla de un tablero de $8\times 8$ se escribe un número entero. Se sabe que, para cada casilla, la suma de los números en sus casillas vecinas es igual a 1. Determina la suma de todos los números del tablero.
    
    > **Nota.** Se considera que dos casillas son vecinas si comparten un lado.
    
    \begin{center}
\begin{tikzpicture}[scale=1]
\def\rows{8}
\def\cols{8}
\draw[line width=1.5pt, black, step=1cm]
(0,0) grid (\cols,\rows);
\fill[yellow] (1,0) rectangle (2,1);
\fill[yellow] (2,0) rectangle (3,1);
\fill[yellow] (5,0) rectangle (6,1);
\fill[yellow] (6,0) rectangle (7,1);
\fill[yellow] (0,2) rectangle (1,3);

\fill[yellow] (3,2) rectangle (4,3);

\fill[yellow] (4,2) rectangle (5,3);

\fill[yellow] (7,2) rectangle (8,3);

\fill[yellow] (0,3) rectangle (1,4);

\fill[yellow] (7,3) rectangle (8,4);

\fill[yellow] (2,4) rectangle (3,5);

\fill[yellow] (5,4) rectangle (6,5);

\fill[yellow] (2,5) rectangle (3,6);

\fill[yellow] (5,5) rectangle (6,6);

\fill[yellow] (0,6) rectangle (1,7);

\fill[yellow] (7,6) rectangle (8,7);

\fill[yellow] (0,7) rectangle (1,8);

\fill[yellow] (7,7) rectangle (8,8);

\fill[yellow] (3,7) rectangle (4,8);

\fill[yellow] (4,7) rectangle (5,8);

\end{tikzpicture}

\end{center}
    
3. Sean $a,b,c,d,e,f$ números reales con la siguiente propiedad:
$$
  \begin{align}
    f\bigl(a - b + c - d + e\bigr) &< 0, \\
    a\bigl(b - c + d - e + f\bigr) &< 0.
  \end{align}
$$

  Demostrar que $af < 0$.

por contradiccion demostramos que af>=0

dividimos en af>0 y af=0
para af > 0 tanto a como f deben tener el mismo signo
para af = 0 , a o f deben ser cero
a. a>0 y f>0
	como a>0 entonces (b-c+d-e+f)<0
	como f>0 entonces (a-b+c-d+e)<0
	sumando ambos tenemos a+f<0.
	como a>0 y f>0 entonces a+f<0 es imposible

b. a<0 y f<0
	como a<0 entonces (b-c+d-e+f)>0
	como f<0 entonces (a-b+c-d+e)>0
	sumando ambos tenemos a+f>0.
	como a<0 y f<0 entonces a+f>0 es imposible

c. a=0 y f \neq 0
	como a=0 entonces a(b-c+d-e+f)= 0(b-c+d-e+f) = 0 > 0, lo cual es imporsible

d. a \neq 0 y f=0
	como f=0 entonces f(a-b+c-d+e)= 0(a-b+c-d+e) = 0 > 0, lo cual es imporsible
	
4. En una bolsa hay 32 bolillos numerados del 1 al 32. ¿Cuál es el mínimo número de bolillos que hay que extraer de la bolsa, para tener la certeza de haber obtenido dos bolillos cuya suma es mayor o igual que 20 y menor o igual que 45?
resuelve por palomar

tenemos el conjunto de numeros S={1,2,...32}
eviatamos los pares que cuya suma se encuentre entre 20 y 45.
tenmos los subconjundos 
S1={1,2,...,10}, la suma mayor de estos numeros es 9+10=19<20
S2={23,24,...,32}, la suma menor de estos numeros es 23+24=47>45
tanto s1 cmo s2, tienen tamanio 10.
concluimos con 10 estracciones se puede evitar un par que sume 20 a 45, pero no con 11, por tanto siempre existira el par con 11 extracciones
    
5. Un grafo simple tiene 8 vértices de grados $3,3,3,3,3,3,3,x$. Hallar todos los posibles valores de $x$.


sumando los grados tenemos
21+x= par, por tanto x debe ser impar, por teor
ademas 0<=x <= 7 debido a que el grafo tieene 8 vericies y no es simple
en el rango [0,7] , tenemos los imprares 

