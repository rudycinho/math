
# Examen 1

**Nombre completo:** \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_
**C.I.:** \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_


1. Sean m y n son enteros positivos tales que $n + n^3 + n^5 = m + m^2$. Probar que $n$ es par.

	Por contradicion decimos que n es impar.
	primero demostracion las potencias:

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

3. Consideremos los números enteros del 1 al 2025.
   ¿Cuántos de estos números tienen una suma de dígitos que es múltiplo de 5?

4. ¿Cómo se puede cortar un rectángulo de dimensiones $13\times7$ en 13 rectángulos de áreas y dimensiones diferentes?

basta con dibular un rectangulo 13x7
en la filas colocamos:
1 cuadrado , 2

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
    
2. En cada casilla de un tablero de $8\times 8$ se escribe un número entero. Se sabe que, para cada casilla, la suma de los números en sus casillas vecinas es igual a 1. Determina la suma de todos los números del tablero.
    
    > **Nota.** Se considera que dos casillas son vecinas si comparten un lado.
    
3. Sean $a,b,c,d,e,f$ números reales con la siguiente propiedad:
$$
  \begin{align}
    f\bigl(a - b + c - d + e\bigr) &< 0, \\
    a\bigl(b - c + d - e + f\bigr) &< 0.
  \end{align}
$$

  Demostrar que $af < 0$.
  
    
4. En una bolsa hay 32 bolillos numerados del 1 al 32. ¿Cuál es el mínimo número de bolillos que hay que extraer de la bolsa, para tener la certeza de haber obtenido dos bolillos cuya suma es mayor o igual que 20 y menor o igual que 45?
    
5. Un grafo simple tiene 8 vértices de grados $3,3,3,3,3,3,3,x$. Hallar todos los posibles valores de $x$.