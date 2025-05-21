# Principio de Contradiccion 
_Método por Contradicción_

$$p \rightarrow q$$
![[Pasted image 20250215211722.png]]

![[Pasted image 20250215221741.png]]


Un poco de lógica.

| p | $\rightarrow$ | q | $\equiv$ | $\neg$ | p | $\vee$ | q | 
| --- | --- | --- | --- | --- | --- | --- |  --- |  
| V | V | V | V | F | V | V | V |
| V | F | F | V | F | V | F | F |
| F | V | V | V | V | F | V | V |
| F | V | F | V | V | F | V | F |


$$p \rightarrow q$$

| Si | hoy es miercoles | entonces | manana es jueves |
| --- | --- | --- | --- |
| | p | $\rightarrow$ | q |

$$\neg \, ( \, p \rightarrow q \, ) \equiv p \wedge \neg q$$

1. $p$ Hipótesis
2. $\neg q$ Hipótesis adicional
3. $r \wedge \neg r$ $( \Rightarrow \Leftarrow )$ Contradicción
4. $\neg (\neg(p \rightarrow q)) \equiv p \rightarrow q \; \blacksquare$


$$\neg \, ( \; \forall x \, ,\, p(x)  \; ) 
= 
\exists x \, , \, \neg p(x) $$

$$\neg \, ( \; \exists x \, ,\, p(x)  \; ) 
= 
\forall x \, , \, \neg p(x) $$



| Proposicion                     | Negacion                              |
| ------------------------------- | ------------------------------------- |
| 1. Hoy comi pollo               | 1. Hoy no comi pollo                  |
| 2. "x" es mayor o igual que 100 | 2. "x" es menor que 100               |
| $$x \ge 100 $$                    | $$\neg (x \ge 100) = x < 100$$            |
| 3. Todas las vacas son blancas  | 3. Existe una blanca que no es blanca |
| $$\forall x \, ( \, p(x) \rightarrow q(x) \, ) $$ | $$\neg \, ( \; (\forall x \, ( \, p(x) \rightarrow q(x) \, ) \; ) = \exists x \, ( \, p(x) \wedge \neg q(x) \,)$$ |
| donde:                          |                                       |
| $p(x)$ : "x es una vaca"           | $q(x)$ : "x es blanca"                 |


Problemas Deterministicos
Problemas Demostrativos

Para resolver los problemas se utilizaran tres razonamientos.
5. Razonamiento Analogico
6. Razonamiento Inductivo
7. Razonamiento Deductivo

Ejemplo 2. La suma de las inversas de cuatro enteros positivos es 1, probar que alguno de ellos es par.
Solucion
Simbolos 
$$\forall x \;[ \; p(x) 
\rightarrow 
q(x) \;]$$

$$\neg \, (\, \overbrace{\forall \, x_1,\,x_2,\,x_3,\,x_4\, \in \mathbb Z^+}^{\forall x} \, , \overbrace{\left( \sum_{i=1}^4 \frac{1}{x_i} = 1 \right)}^{p(x)} \rightarrow \overbrace{\left( \exists \, i \in \{ 1,2,3,4\}\,,\, x_i \;\text{es par} \right)}^{q(x)}\;) \equiv$$
Negacion
$$\exists \, x_1,\,x_2,\,x_3,\,x_4\, \in \mathbb Z^+ \, , \left( \sum_{i=1}^4 \frac{1}{x_i} = 1 \right) \wedge \, \left( \forall \, i \in \{ 1,2,3,4\}\,,\, x_i \;\text{es impar} \right) $$

Como $x_1\,x_2\,x_3\,x_4$ son numeros positivos impares, entonces:
$$\frac{1}{x_1} + \frac{1}{x_2} + \frac{1}{x_3} + \frac{1}{x_4} = 1 $$
$$\frac{x_2 x_3 x_4 + x_1 x_3 x_4 + x_1 x_2 x_4 + x_1 x_2 x_3}{x_1 x_2 x_3 x_4} = 1$$
$$x_2 x_3 x_4 + x_1 x_3 x_4 + x_1 x_2 x_4 + x_1 x_2 x_3 = x_1 x_2 x_3 x_4$$
$$\text{PAR} = \text{IMPAR}$$
$$( \Rightarrow \Leftarrow )  \qquad \blacksquare$$
*En el primer miembro hay cuatro impares, por lo que su suma sera par, en cambio en el segundo miembro la multiplicacion de impares siempre sera impar*
Sea un x impar, tenemos : $x=(2k-1)$
$$x_1 x_2 \Rightarrow (2k-1)(2k-1) \Rightarrow 4k^2-4k+1 ,\; \text{tenemos} \; l=k^2-k \Rightarrow 4l+1 \Rightarrow x_1x_2 \;\text{es impar}$$

Problema 3. El producto de 34 número enteros es 1. Demostrar que la suma de estos no puede ser cero
Solución

$$\neg \, ( \, \underbrace{\forall x_1,x_2,x_3, \dots ,x_{34} \in \mathbb Z \; ,}_{\forall x \; ,} \quad  \underbrace{x_1\cdot x_2\cdot x_3 \dots x_{34} = 1 }_{p(x)} \rightarrow \underbrace{x_1 + x_2 + \dots + x_{34} \neq 0}_{q(x)} \,) \equiv$$
$$\underbrace{\exists \, x_1,x_2,x_3, \dots ,x_{34} \in \mathbb Z \; , \;  x_1\cdot x_2\cdot x_3 \dots x_{34} = 1}_{\text{Hipotesis}} \wedge \underbrace{x_1 + x_2 + \dots + x_{34} = 0}_{\text{Hipotesis Adicional}}$$

Paso 1 : Sabemos que $x_1\cdot x_2\cdot x_3\cdot ... \cdot x_{34} = 1$ entonces eso significa que:
$$\forall i \in \{ 1,2,...,34 \}\; , \; x_i = 1 \; \vee \; x_i = -1$$
Caso 1: (Todos los enteros son $1$)
$$\underbrace{1+1+1+\dots+1}_{\text{34 veces}} =34 \neq 0 \qquad ( \Rightarrow \Leftarrow )$$
Caso 2: (Todos los enteros son $-1$)
$$\underbrace{(-1)+(-1)+(-1)+\dots+(-1)}_{\text{34 veces}} = -34 \neq 0 \qquad ( \Rightarrow \Leftarrow )$$
Caso 3: 
Sea "a" la cantidad de 1's.
Sea "b" la cantidad de -1's.
$$a\cdot 1 + b \cdot (-1) = 0 \Rightarrow a=b$$
$$a + b = 34 \Rightarrow a = b = 17$$
$$ \underbrace{x_1 \cdot x_2 \cdot x_3 \dots x_{17}}_{a-veces} \cdot \underbrace{x_{18} \dots x_{34}}_{b-veces} = 1^a \cdot (-1)^b = 1 \cdot (-1)= -1 \qquad ( \Rightarrow \Leftarrow ) \qquad \blacksquare$$


Ejercicio : Probar que la cantidad de números primos es infinito.

Problema : Alrededor de una circunferencia están escritos 10 números enteros cuya suma es 67.
Demostrar que podemos encontrar tres números **consecutivos** cuya suma es mayor o igual que 21.

Entender el problema:
$$x_1 + x_2 + x_3 + \dots + x_{10} = 67 $$
$$ \sum_{i=1}^{10} \; x_i = 67$$

![[Pasted image 20250218015114.png]]

$$x_1 + x_2 + x_3 \geq 21$$
$$x_7 + x_8 + x_9 \geq 21$$

Simbolizar:
$$
\neg \left( 
    \forall x_1, x_2, x_3, \dots, x_{10} \in \mathbb{Z}, 
    \left( \sum_{i=1}^{10} x_i = 67 \right) 
    \rightarrow 
    \left( \exists i \in \{ 1,2,\dots,10\}, x_i + x_{i+1} + x_{i+2} \geq 21 \right) 
\right)
$$

$$
\neg \left(
\forall x\; (\;p(x) \rightarrow q(x)\;) \;
\right)
\equiv
\exists x\; (\;p(x) \wedge \neg \; q(x)\;)
$$

$$
\exists \;x_1, x_2,\dots , x_{10} \; \in \mathbb Z \;,\;
\sum_{i=1}^{10} \, x_i = 67 \;
\wedge
\forall i \in \{1,2,\dots,10\}, x_i + x_{i+1} + x_{i+2} \leq 20  
$$ 
[^1]

$$
\begin{array}{c@{\quad}c}
    & x_1 + x_2 + x_3 \leq 20\\
    & x_2 + x_3 + x_4 \leq 20\\
    & x_3 + x_4 + x_5 \leq 20\\
    & x_4 + x_5 + x_6 \leq 20\\
  + & x_5 + x_6 + x_7 \leq 20\\
    & x_6 + x_7 + x_8 \leq 20\\
    & x_7 + x_8 + x_9 \leq 20\\
    & x_8 + x_9 + x_{10} \leq 20\\
    & x_9 + x_{10} + x_1 \leq 20\\
    & x_{10} + x_1 + x_2 \leq 20\\
    \hline
    & 3 \cdot (x_1 + x_2 + x_3 + \dots + x_{10}) \leq 10 \cdot 20
\end{array}
$$



$$3 \cdot 67 \leq 200 $$
$$201 \leq 200$$
$$( \Rightarrow \Leftarrow)$$


Por lo tanto, existe tres enteros consecutivos cuya suma es mayor o igual que 21. $\blacksquare$

Problema 
Demostrar que la cantidad de números primos es infinita.
Demostración. Para la prueba utilizaremos el método de contradicción.
- Supongamos que la cantidad de números primos es finito, digamos:
$$
	p_1,p_2,p_3,\dots,p_k,\dots,p_n
$$
son todos los números primos
- Consideramos $N=p_1\cdot p_2\cdot p_3\dots p_k \dots p_{n+1}$ un numero cualquiera. Notemos que $N \geq 2$, entonces por el teorema fundamental de la aritmetica N tiene al menos un factor primo ($N = p_k \, l  \quad , \quad l \in \mathbb Z^+$)
- Tambien $N-1 = p_1\cdot p_2\cdot p_3\dots p_k \dots p_{n+1}$


[^1]: Tenemos $x_i + x_{i+1} + x_{i+2} < 21$ pero lo cambiamos a $x_i + x_{i+1} + x_{i+2} \leq 20$.


aprendizaje heuristico
