11.1 INTRODUCCION

Presentamos en esta unidad la teoría y la ejercitación básicas relativas al estudio de los números complejos. La generación del conjunto C y de las operaciones en él es la habitual: una relación de equivalencia en R que presenta la ventaja de caracterizar clases unitarias y la consiguiente identificación con C. Se definen las operaciones de adición y de multiplicación, se destaca el isomorfismo de una parte de Cen R, y además de la forma binómica se introducen las formas trigonométrica y exponencial. Queda resuelto el problema de la radicación y de la logaritmación, no siempre posibles en R. Se introduce, además, el concepto de raices primitivas de la unidad.

11.2. EL NUMERO COMPLEJO

11.2.1. Ecuaciones sin soluciones en R

El ejemplo más conspicuo de una ecuación sin raíces reales es x+1=0 ya que, cualquiera que sea x & R. se verifica. 0, y en consecuencia x²+1>0 De un modo más general, la ecuación ax2 + bx +c=0 con coeficientes reales no tiene soluciones en R si el discriminante b²-4 ac es negativo.

Se hace necesaria la ampliación de Ra un conjunto en el cual puedan resolverse situaciones del tipo anterior, de manera que R sea isomorfo a una parte de él. Tal conjunto es el de los números complejos.

342

EL CUERPO DE LOS NUMEROS COMPLEJOS

11.2.2. Relación de equivalencia en R³ y números complejos

En el conjunto R2, de todos los pares ordenados de números reales, definimos la relación mediante (a,b)(c,d)a=cbd

Esta relación es la identidad. y obviamente es de equivalencia; se traduce en el siguiente enunciado: "dos pares ordenados de números reales son equivalentes si y sólo si son idénticos".

Cada clase de equivalencia es unitaria, y se la identifica con el par ordenado Correspondiente, es decir K(0.5) = (a,b) La identificación que proponemos. en virtud del unitarismo de las clases nos permite escribir


K(a,b) = (a,b)
Definición

Parte real de un número complejo es su primera componente. Parte imaginaria. su segunda componente.

Conviene advertir que las partes real e imaginaria de un complejo son números reales. Las notaciones son

Re(z) = a ^ I * m(z) = b

Introduciendo un sistema cartesiano, los números complejos se corresponden con los puntos del plano. La abscisa de cada punto es la parte real, y la ordenada es la parte imaginaria. Por otro lado, a cada complejo le está asociado un vector con origen en el origen del sistema, y cuyo extremo es el punto determinado por el par ordenado correspondiente.

Equihua

COMPLE/OS REALES I IMAGINARIOS

343

R

z = (a, b)

R

Los complejos de parte imaginaria nula. decir los parcs ordenados del tipo (a, 0), son puntos del eje de abscisas. Los complejos de parte real nula caracterizan el eje de ordenadas.

Definición

Un complejo es teal si y sólo si su parte imaginaria es cero.

Un complejo es imaginario si y sólo si su parte real es cero.

Ejemplo 11-1.

Determinamos analítica y gráficamente los complejos z = (x, y) que verifican

i) Re (z) = 2

Resultan todos los pares ordenados para los cuales x = 2 es decir, z = (2, v) La ecuación x = 2 corresponde a la recta paralela al eje de ordenadas que el punto de abscisa 2.

ii) Im (z) <= 3

La condición anterior se traduce en y <= 3 y corresponde al semiplano que contiene

al origen, cuyo borde es la recta de ecuación y = 3
iii) Re(z) + Im(z) = 1

Equihua

3-14

EL CUERPO DE LOS NUMEROS COMPLEJOS

Se trata de los complejos z = (x, y) tales que x + y = 1 Queda definida así la recta del plano que pasa por los (1, 0) * y(0, 1)

y

(0,1)

x + y = i

(1.0)

11.2.3. Operaciones en C

En C = R ^ 1 se definen la adición y multiplicación mediante

1 (a,b)+(c.d)= (a + c, b + d)

2. (a.b). (c, d) = (ac - bd, ad + bc)

Estas leyes de composición interna en C verifican las siguientes propiedades:

I) ( C ,+) es un grupo abeliano. La justificación está dada en los ejemplos 5-2 y 5-5.

nulo es el par (0, 0), y el inverso aditivo de todo complejo z = (a, b) es

- = (- a, - b) II ( C - \{0\} ) es un grupo abeliano. El símbolo 0 denota el complejo nulo (0.0). axiomas

G_{1} El producto es ley de composición interna en C, por la definición 2.

z in C^ z^ * epsilon C Rightarrow z.z^ * epsilon*C

G_{2} Asociatividad.

1) z^ prime prime =[ (a, b) .(a^ - ,b^ - i].(a^ prime prime ,b^ prime prime )=(aa^ prime -b dot 0 ^ prime prime )=(aa^ prime -b dot 0 ^ prime prime . un bata", ( 23 ^ 1 * a ^ 12 ...55a^ prime prime -a5^ prime prime -6a5^ 11 .22h^ prime prime -bb^ prime h^ prime prime +aba^ prime prime +5a^ prime a^ prime prime ) b^ prime prime 1 =

.(z^ prime ,z^ prime prime )=(a,b)[ (a', b') .(a^ prime prime ,b^ prime prime )]=(a,b)(a^ prime a^ prime prime -b^ prime b^ prime prime ,ab^ prime prime +b^ prime a^ prime prime )= = ia * a' a^ prime prime -ab^ prime b^ prime prime -ba^ prime b^ prime prime -bb^ prime a^ prime prime , a^ prime b^ prime prime +ab^ prime a^ prime prime +ba^ prime a^ prime prime - b * b' b^ prime prime )

(2)

De(1) * y(2) resulta

(z * z') z^ prime prime =z(z^ prime z^ prime prime )

G_{3} : Elemento neutro es el complejo (1,0). En efecto, si z = (x, y) es neutro para el producto, debe satisfacer

(a,b).(x,y)=(x,y). (a, b) = (a, b)

forall (a, b) \in C

Por definición de multiplicación

(ax - by, ay + bx) = (a, b)

Por igualdad de complejos ax - by = a; bx + ay = b

Resolviendo el sistema triangle= matrix | matrix a&-b\\ vdots&b matrix |= a ^ 2 + b ^ 2 = triangle x abub

si (a, b) ne(0,0) entonces. kappa = (Delta*pi)/Delta =1^ y ne Delta y Delta =0

Resulta (x, v) = (1, 0) que satisface G_{1} para todo (a, b) e C. pues en el caso (a, b) = (0, 0) se tiene (0.0).( 0)= (0.1 + 0 * 0 * 0 + 0.1) = (0)

G4: Todo complejo no nulo admite inverso multiplicativo. Seaz(a, b) (0.0). Si existe z ^ - 1 = (x, y) debe satisfacer z.z^ -1 =z^ -1 . z = (1, 0) (a.b). (x, y) =(x,y).(a.b)=(1.0) Es decir

Efectuando el producto (ax - by, ay + bx) = (1, 0)

Por igualdad de números complejos resulta el sistema ar - b_{i} = 1 b_{X} + omega_{Y} = 0 Delta = det [[a, - b], [b, a]] =a^ 2 +b^ 2 ne0 Delta' * x = det [[1, - b], [0, a]] = a Delta*nu = det [[a, 1], [b, 0]] = - b Resolviendo el sistema

Equihua

316

EL CUERPO DE LOS NUMEROS COMPLEJON

Luego x = - (Delta*x)/Delta = a/(a ^ 2 + b ^ 2) G_{5} Conmutatividad. y = (Delta*y)/Delta = (- b)/(a ^ 2 + b ^ 2) z ^ - 1 = (a/(a ^ 2 + b ^ 2), - b/(a ^ 2 + b ^ 2)) O sea

z.z^ * =(a.b).(a^ * ,b^ * )=(aa^ * - b b^ * .ab^ * +ba^ * )= = (a' * a - b' * b, b' * a + a' * b) = (a', b')(a, b) = zz

b_{X} + omega_{Y} = 0

Resolviendo el sistema

Delta = det [[a, - b], [b, a]] =a^ 2 +b^ 2 ne0

Delta*x =| matrix 1&-b\\ 0&*&a matrix |=a

Delta*y = det [[a, 1], [b, 0]] = - b

Equihua

346

EL CUERPO DE LOS NUMEROS COMPLEJOS

Luego

x=- triangle x triangle = a/(a ^ 2 + b ^ 2) y = (Delta*y)/Delta = (- b)/(a ^ 2 + b ^ 2)

z ^ - 1 = (a/(a ^ 2 + b ^ 2), - b/(a ^ 2 + b ^ 2))

G: Conmutatividad.

;z^ * = (a, b) .(a^ * ,b^ * )=(aa^ * -bb^ * ,ab^ * +ba^ * )= = (a' * a - b' * b, b' * a + a' * b) = (a', b')(a, b) = z' * z

de acuerdo con la definición de multiplicación en C y la conmutatividad del producto en R.

III) El producto es distributivo respecto de la suma. En efecto

(z + z') :" = [(a, b) (a, b)] (a", b")=(a+a', b+b²) (a", b")=

=(aa^ prime prime +a^ prime prime - b b^ prime prime -b^ prime prime ,ab^ prime prime +a^ prime prime +ba^ prime prime +b^ prime prime b^ prime prime )=

=(aa^ prime prime - b b^ prime prime ,ab^ prime prime +ba^ prime prime )+(a dot a ^ prime prime -b dot prime ^ prime prime ab"+bb")=

=(a,b).(a^ prime prime ,b^ prime prime )+ (a', b') (a^ prime prime ,b^ prime prime )=zz^ prime prime +zz^ prime prime

Por adición en C, nultiplicación en C y conmutatividad de la suma en R.

En consecuencia, la terna (C) es un cuerpo. La diferencia esencial que presenta con relación al cuerpo de los números reales consiste en que es no ordenado.

En efecto, si fuera ordenado, como i ≠ 0, caben dos posibilidades:

i>0 i < 0

En el primer caso, por la compatibilidad de la relación respecto del producto, se nene i ^ 2 > 0 es decir, 10, lo que es absurdo.

En el segundo caso es 0 < i y en consecuencia, - i < 0 por la compatibilidad con el producto resulta - f ^ 2 < 0 o sea, 1 < 0 lo que también es absurdo.

Ejemplo 11-2.

z_{1} = (- 2, 3) , z_{2} = (1, 2) y z_{3} = (- 3, - 1) Efectuar (z_{1} - z_{2}) (z_{1} - z_{2}) * z_{3} = [(- 2, 3) - (1, 2)](- 3, - 1) =

= (- 3, 1)(- 3, - 1) = (9 + 1, 3 - 3) = (10, 0)

O sea

11.3. ISOMORFISMO DE LOS COMPLEJOS REALES EN LOS REALES

Sea C_{R} = \{(a, b) * epsilon*C / b = 0\} el conjunto de los complejos de parte imaginaria nula. La f / C_{\mathbb{R}} -> \mathbb{R} por f(a, 0) = a asigna a cada complejo real su primera componente.

C

C_{R}

R

(2.0)

( a ^ * ,0)]

La aplicación es obviamente biyectiva. y además un morfismo de C_{R} R respecto de la adición y multiplicación. En efecto, sean(2.0) y z = (a 0); entonces

f(z+z^ * )=f[ (a, 0) +(a^ * ,0)]=f(a+a^ * 0)= =a+a^ prime =f(a,0)+f(a^ * ,0)= f' * (z) + f(z')

Por otra parte f(z z^ * )=f[ (a, 0) (a^ * ,0)]=f^ prime (aa^ * ,0)=aa^ * = = f(a, 0) * f(a', 0) = f(z) * f(z')

En consecuencia. fes un isomorfismo de C_{R} en R respecto de la adición y multiplicación; o sea, \mathfrak{a}_{R} y R son conjuntos indistinguibles desde el punto de vista algebraico.

El isomorfismo permite identificar cada complejo real con el real correspondiente, es decir. (a, 0) = a

11.4. FORMA BINOMICA DE UN COMPLEJO

11.4.1. Unidad imaginaria

El número complejo imaginario de segunda componente igual a 1, se llama unidad imaginaria y se denota por i = (0, 1)

La multiplcación de un complejo real por la unidad imaginaria permuta las componentes de aquél, es decir, lo trasforma en un complejo imaginario. En efecto (b,0).i=(b,0). (0, 1) = (b, 0 - 0.1, b, 1 + 0) = (0, b) y por el isomorfismo de los complejos reales con los reales, se tiene bi = (0, b) Las potencias sucesivas de la unidad imaginaria son l ^ a = 1 i ^ 1 = i i^ 2 =(0.1). (0.1) = (- 1) = - 1 i ^ 3 = i ^ 2 i = (- 1) .i-i

Análogamente i ^ 4 = 1 i ^ 5 = i i ^ 6 = - 1 i ^ 7 = - i

Si el exporente es de la forma 4 k con ke Z, se tiene i ^ (4k) = (i ^ 4) ^ k = 1 ^ k = 1 En general, si el exponente de i es a e N, al efectuar se tiene a = 4q + r donde 0 <= r < 4 En consecuencia l ^ a = i ^ (4q + r) = i ^ (4q) i ^ r = 1 y este cálculo se reduce a uno de los cuatro considerados en primer término.

11.4.2. Forma binómica de los complejos

Seaz (a, b) un número complejo. Por definición de suma 10.01-10.6) Por el isomorfismo de los complejos reales con tos reales y por 11.4.1, resulta la forma binómica z=a+bi La converiencia de la forma binómica se pone de manifiesto al efectuar operaciones con números complejos, evitando el cálculo con pares ordenados, que es más laborioso.

Ejemplo 11-3.

Sean z_{1} = (- 2, 3) z_{2} = (1, 2) y z_{3} = (- 3, 1) Calcular (22) 2 Con tiene

(z 1 *** z 2 )z 3 ^ 2 =[(-2+3i)^ -** (1+2 i)] (- 3 + i) ^ 2 = = (- 3 + i)(9 + i ^ 2 - 6i) = (- 3 + i)(9 - 1 - 6i) = = (- 3 + i)(8 - 6i) = - 24 + 18i + 8i - 6i ^ 2 = = - 24 + 26i + 6 = - 18 + 26i

11.5. LA CONJUGACION EN C

11.5.1. Complejos conjugados

Sea=a+bi.

Definición

Conjugado de za + bi es el número complejo abi. El símbolo z se lee "conjugado de z" o "z conjugado". Si-1+3i, entonces overline z = - 1 - 3i

El conjugado de z = (3/2, - 1) overline z = (3/2, 1) .

Dadoa+bi se tiene abi ya+biz, es decir, que el conjugado del conjugado de un número complejo es igual a éste. Los complejos z y se llaman conjugados.

Definición

Dos complejos son conjugados si y sólo si tienen la misma parte real, y sus partes imaginarias son números opuestos.

Dos complejos conjugados caracterizan puntos simétricos respecto del eje real.

Im (z)

z=a+bi

Rel

za-bi

11.5.2. Propiedad. La suma de dos complejos conjugados es igual al duplo de la parte real. El producto de dos complejos conjugados es un número real no negativo. En efecto, sea za+bi. Entonces.

z+ overline z = (a + bi) + (a - bi) = 2a = 2Re(z)

FL CUERPO DE LOS NUMEROS COMPLEJOS

Por otra parte 2.2 (a+bi) (abi) = a²(bi)² = a² + b² Como a y b son números reales, resulta z.ZER A 2.20

11.5.3. Propiedad. Un número complejo es real si y sólo si es igual a su conjugado.

ZER=7

FR=0+0====

1)abia hibibi2bi00

Entonces a, o lo que es lo mismo, eR

11.5.4. Aatomorfismo en C

La función: CC definida por (2) es un automorfismo en C. En efecto

i) fes inyectiva. Sean zyz'en C, tales que f() = (') y por igualdad de complejos resulta aabb. osea

11) fes sobreyectiva. Para todo wa+bie C, existe za bi, tal que

(2)=f(abi) = a+biw

ni) / es un morfismo respecto de la adición, pues =(a+bi)+(a+bi) = (a+a)+(b+b') = =(a+a)-(b+b²)i(abi)+(abi) = =+=f(z)+f(z')

Por definición dely suma en C.

iv) fes un morfismo respecto de la multiplicación, ya que f'(zz')==(a+bi) (a+bi) = (ua-bb')+(ab+ba') i = (aa'bb')(ab+ba') i = =(abi) (abi) = 22'=f(z)f(z')

Las propiedades iii) y iv) se traducen en el siguiente enunciado: "el conjugado de la suma es igual a la suma de los conjugados, y el conjugado del producto es igual al producto de los conjugados".

+=+
.
Ejemplo 11-4.

Determinar los complejos z = x + yi que satisfacen

1) z =- overline z

En la forma binómica se tiene x+yi=- (x - yi) Rightarrow x+yi=-x+yi Rightarrow x=-x Rightarrow x=0

Los complejos que verifican la condición dada son de la forma z = yi es decir, imaginarios puros, y corresponden al eje de ordenadas.

ii) z = 1

Esta condición se traduce en

(x+yi). (x - yi) = 1

Luego. x ^ 2 + y ^ 2 = 1 y corresponde a la circunferencia de radio 1 con centro en el ori-gen.

11.6. MODULO DE UN COMPLEJO

11.6.1. Sea=a+bi.

Definición

Módulo de un complejo es la raíz cuadrada no negativa de la suma de los cuadrados de real e imaginaria

La notación es z|= sqrt(a ^ 2 + b ^ 2)

El módulo de un complejo es la distancia del punto correspondiente, al crigen.

z = a + bi

←

Siz = - 3 + 4i entonces |z| = sqrt((- 3) ^ 2 + 4 ^ 2) = sqrt(25) = 5

11.6.2. Propiedades del módulo

I) El módulo de todo complejo es mayor o igual que su parte real z = a + bi Entonces

|a|^ 2 =a^ 2 Rightarrow|a|^ 2 a^ 2 +b^ 2 Rightarrow|a|^ 2 |z|^ 2 Rightarrow |a| << |z|

Como a eRa lal, de esta relación y de lall resulta Izla, es decir, Re (2) Izl. Análogamente Im (2)</

II) El producto de cualquier complejo por su conjugado es igual al cuadrado del módulo. Tesis) z. overline z = |z| ^ 2 Demostración)

Efectuando el producto y aplicando la definición de módulo, resulta 2. Xi=(a+bi). (a - bi) = a ^ 2 - (bi) ^ 2 = a ^ 2 + b ^ 2 = |z| ^ 2

III) El móculo del producto de dos complejos es igual al producto de los módulos Tesis)z!

Demostración)

A partir del cuadrado del primer miembro aplicamos II, conjugado del producto. conmutatividad y asociatividad del producto en C y la propiedad 11 Resulta |z * z'| ^ 2 = (|z||z'|) ^ 2 Y como las bases son no negativas, se tiene

2222

(V) El módulo de la suma de dos complejos es menor o igual que la suma de los módulos. Tesis) |z + 2'| < |z| + |z'| Demostración

Por cuadrado del módulo, conjugado de la suma. distributividad del producto respecto de la suma en C y por la propiedad II se tiene |z + z'| ^ 2 = (z + z')(z + z') =(z+z^ prime )( overline z + overline z )= +++:+2=1+++

Como los términos centrales son complejos conjugados, su suma es el duplo de la parte real, es decir zzzz2 Re (zz') Sustituyenco en la igualdad inicial tenemos |z + z'| ^ 2 =|z|^ 2 +2 Re(z overline z )+|z^ prime |^ 7 (1)
.

.Ahora bien, teniendo en cuenta que la parte real es menor o igual que el módulo 2 Re (zz) <2zz For módulo del producto

2 Re (zz')2z2 2 Re (22)222 y como 12'12'], es (2)

Sumando (1) * y(2) |z + z'| ^ 2 +2Rc(zz^ prime prime )<|z|^ 2 +2Rc(zz^ prime prime )+|z^ prime prime |^ 2 +2|z||z^ prime | Después de cancelar y factorear el segundo miembro |z + z'| ^ 2 <= (|z| + |z'|) ^ 2 y como las bases son no negativas, resulta 12+212 +2

V) El módulo de una potencia de exponente natural es igual a la potencia del módulo

Ejemplo 11-5.

Al dividir dos complejos, siendo el segundo distinto de cero, puede evitarse la determinación del inverso multiplicativo del divisor multiplicando por el conjugado de este, y se obtiene zw wi

En particular (- 1 + 2i)/(2 + 3i) plus/minus ((- 1 + 2i)(2 - 3i))/((2 + 3i)(2 - 3i)) = (- 2 + 3i + 4i - 6i ^ 2)/(2 ^ 2 + 3 ^ 2) =- 2+ 13 * (7i + 6)/13 = (4 + 7i)/13 = 4/13 + 7/13

Ejemplo 11-6.

Determinar los complejos z que satisfacen

i) iz = 1 + i z = (1 + i)/i = ((1 + i)(- i))/(i(- i)) = (- i - i ^ 2)/1 = = - i + 1 = 1 - i

ii)z-12-2 Sizx + yi entonces

|x + yi - 1 + 2i| =2 Rightarrow |(x - 1) + (y + 2) * i| = 2 = sqrt((x - 1) ^ 2 + (y + 2) ^ 2) =2 Rightarrow Rightarrow (x - 1) ^ 2 + (y + 2) ^ 2 = 4

Es la ecuación de la circunferencia de radio 2, con centro (1, 2).

[z-Re(z) 1 = [Im(z)] ^ 2 2=x+yix+yi-xy² ||yi|=y^ 2 Rightarrow (sqrt(y ^ 2)) ^ 2 = y ^ 2 = ni|y|=y^ 2 Rightarrow y ^ 2 = ycony 0 Rightarrow y-y=0y (y-1)=0 Rightarrow v = 0 y=1z=x V z=x+i

Se obtienen los complejos correspondientes a los puntos de las rectas de ecuaciones y = 0 y = 1

iv) z=- overline z + 2 z=x+:+5=2 2x=2x=1z=1

Es la recta de ecuación x = 1 v (a + bi) * z = (a ^ 2 + b ^ 2) * i con (a,b)≠(0.0) Se tiene z = ((a ^ 2 + b ^ 2) * i)/(a + bi) = ((a ^ 2 + b ^ 2) * i(a - bi))/((a + bi)(a - bi)) = = ((a ^ 2 + b ^ 2) * i(a - bi))/(a ^ 2 + b ^ 2) = i(a - bi) = ai - b * i ^ 2 = = b + ai

11.7. RAIZ CUADRADA EN C

Sea z = a + bi. Por definición, la raíz cuadrada de z es un complejo x + yi que satisface

(x + yi) ^ 2 = a + bi

(1)

Aplicando módulos

|(x + yi) ^ 2| = ia + bi

Por 11.6.2. v) y por definición de módulo

|x + yi| ^ 2 = sqrt(a ^ 2 + b ^ 2)

Por cuadrado del módulo x ^ 2 + y ^ 2 = sqrt a^ 2 + overline b^ 2

Es decir x ^ 2 + y ^ 2 = |z| (2)

Desarrollando (1) x²y²+2xyi = a + bi

Por igualdad de complejos x ^ 2 - y ^ 2 = a 2 Xy = b (3) (4)

Sumando y restando (2) y (3) \ [[x ^ 2 + y ^ 1 = |z|], [x ^ 2 - y ^ 2 = a]] 2x ^ 2 =|z|+a| 2y ^ 2 =|z|-a| x = plus/minus sqrt((|x| + a)/2) y = plus/minus sqrt((|z| - a)/2) Resulta

Ambos radicandos son no negativos, pues za, y se obtienen cuatro parts de valores reales, de los cuales se seleccionan dos de acuerdo con la condición (4): b > 0 entonces x e y se eligen con el mismo signo, y si b < 0 se eligen con distinto signo.

Ejemplo 11-7.

Calcular las raíces cuadradas de los siguientes complejos

i) z = - 4 - 3i

4,6-3,25 a = - 4

x= pm sqrt 5-4 2 = pm - 1/(sqrt(2)) = plus/minus (sqrt(2))/2 y= pm sqrt 5+4 2 = pm - 3/(sqrt(2)) = plus/minus (3sqrt(2))/2

Como b <0, x e y se eligen con signos distintos, y las soluciones son

Es decir ((sqrt(2))/2, (- 3sqrt(2))/2)(- (sqrt(2))/2, (3sqrt(2))/2)

sqrt(- 4 - 3i) = plus/minus ((sqrt(2))/2 - (3sqrt(2))/2 * i)

i) z = - 2i x=0.b= - 2' .|z|=? x = t * sqrt((2 + 0)/2) = plus/minus i = y

Comob-20, las soluciones son

(1,-1) y (-1,1)

Luego

sqrt(- 2i) = plus/minus (1 - i)

iii) z = - 9 9, b = 0, |z| = 9 a = - 9 x = plus/minus sqrt((9 - 9)/2) = 0 y = plus/minus sqrt((9 + 9)/2) = plus/minus 3

En este case, los cuatro pares de valores se reducen a dos

(0.3) у (0,-3)

y se tiene

sqrt(- 9) = sqrt(- 9 + 0i) = plus/minus (0 + 3i) = plus/minus 3 * i

Analogamente

Eguthua

sqrt - 1 4 = plus/minus 1/2 - 1 sqrt(- 3) = plus/minus sqrt(3) * i

11.8. FORMA POLAR O TRIGONOMETRICA

z = a + bi un complejo no nulo. Las coordenadas polares del punto de coordenadas cartesianas a y b son: el radio vector py el argumento, o cualquiera de los congruentesa y, módulo 2 π.
.
Las fórmulas de pasaje de las coordenadas polares a cartesianas son

a = rho * cos varphi

b = rho * sin varphi

rho / z|z|

6

donde rho = sqrt(a ^ 2 + b ^ 2) = z! y varphi = argz Se tiene z = a + bi = rho * cos varphi + rho*i * sin varphi

es decir

z = rho(cos varphi + i * sin varphi)

Esta es la llamada forma polar o trigonométrica del complejo z.

Es claro que py definen univocamente a z. Pero z caracteriza unívocamente a p.

у по a arg

Definición

Argumento principal del complejo no nulo z es el número real que satisface

i) a = |z| * cos varphi ^ b = |z| * sin varphi

ii) 0 <= varphi < 2pi

Para denotar el argumento principal escribiremos varphi = Arg =

Dados dos complejos en forma polar picas p/sen = rho^ * (cos varphi, i * sin varphi') diremos que son iguales si y sólo si tienen el mismo módulo y sus congruentes módulo 2 π. En símbolos

z=z^ prime Leftrightarrow rho = rho' +2k con k \in Z

Ejemplo 11-8.

Determinar la forma polar de los siguientes complejos

i) z = - 2 + 2i

rho = sqrt((- 2) ^ 2 + 2 ^ 2) = sqrt(8) = 2sqrt(2)

ara el argumento principal consideramos cos varphi = - a/rho = - 2/(2sqrt(2)) = - (sqrt(2))/2 sin varphi = b/rho = 2/(2sqrt(2)) = (sqrt(2))/2

Resulta del segundo cuadrante e igual a 135 deg Luego z = 2sqrt(2) * (cos 135 deg + f * sin 135 deg)

ii) z = - 3i rho = sqrt(0 ^ 2 + (- 3) ^ 2) = 3 varphi = tau

Luego z = 3(cos pi + i * sin pi)

z = - 3i

11.9 OPERACIONES EN FORMA POLAR

11.9.1. Multiplicación

El producto de dos complejos en forma polar tiene por módulo el producto de los módulos, y por argumento la suma de los argumentos.

anz = rho(cos varphi + i * sin varphi) * y * z' = rho' * (cos varphi + i * sin varphi)..

Entonces

zz' = pp (cos + i sen ) (cos + i sen ) = = pp [(cos cossensen) + i (sen cos + cos sen)] = pp [cos (+) + i sen (+)

11.9.2. Cociente

El cociente de dos complejos en forma polar, siendo el segundo distinto de cero, tiene por módulo el cociente de los módulos, y por argumento la diferencia de los argumentos.

ww p(cos + i sen ) = p (cos + i sen ) R (cos + i sen $) -p(cos + i sen) = Rp [cos (+) + i sen (+)]

Por igualdad de complejos. Rp=p Luego +=+2 km R==- si k=0 [cos(-) + i sen ( - )

11.9.3. Potenciación de exponente natural

La potencia -sima de un complejo en forma polar tiene por módulo la potencia. n-sima de su módulo, y por argumento el producto de su argumento por n.

z=p(cos + i sen) z = p (cos no + i sen n )

Lo demostramos por inducción completa

1°) 12 = z = p (cos + i sen ) = mh M = p (cos 1.0+ i sen 1.6)

zh+1 ph+1 [cos (+1) +i sen (h+1) 2°) z = p (cos h + i sen ho) zh*1 HIPOTESIS En efecto, por definición de potencia, hipótesis inductiva y 11.9.1., se tiene

zh+1=zhz = p (cosh + i sen hy) p (cos + i sen ) = =p+1 [cos (+1) + i sen (h+1)]

La fórmula z p" (cos + i sen n) se llama de De Moivre.

11.9.4. Determinación geométrica del producto y del cociente

nz = rho(cos varphi + i * sin varphi) * y * z' = rho' * (cos varphi' + i * sin varphi')

i) Producto. En un sistema cartesiano consideramos U(1, 0) : los puntos A y B representantes de los complejos zyz, es decir, de coordenadas polares (varphi, rho) * y(varphi', rho') respectivamente.

( varphi+ varphi^ prime . rho * rho' )

B(varphi', rho')

A(varphi, rho)

U

Considerando a OB como homólogo de OU, construimos O B ^ hat BC sim O hat U A . Resulta C de coordenadas polares (varphi + varphi', R) y por la proporcionalidad de lados homólogos (d(0, C))/(d(0, A)) = (d(0, B))/(d(0, U))

es decir

Omega/rho = dot mu ^ prime 1 Rightarrow R= rho rho^ *

En consecuencia, el vector vec oc representa el producto de los complejos zyz

ii) Cociente. Razonando sobre la misma figura, suponemos dados los puntos C y B asociados al dividendo y divisor respectivamente. Construimos sobre OU, como homólogo de OB, el triángulo OÛA semejante a OBC, y obtenemos el vector vec OA , es decir, el cociente.

OPERACIONES EN FORMA POLAR

361

Ejemplo 11-9.

Siendo z=-1+i sqrt 3 y z^ * = 3/2 + (3sqrt(3))/2 ; siguientes operaciones realizar en forma polar las

z * z' * z/(z') Expresamoszy z'en forma polar p= sqrt (- 1) ^ 2 +( sqrt 3)^ 2 - sqrt 4 -?

varphi - b/rho = sqrt 3 2 Rightarrow varphi=120 p cuadrante Luego z = 2(cos 120 deg + j * sin 120 deg) caracteriza un punto del segundo

Por otra parte p' + sqrt((3/2) ^ 2 + ((3sqrt(3))/2) ^ 2) = sqrt(9/4 + 27/4) = sqrt(36/4) = 3

sen varphi' = b/k = sqrt 3 2 Rightarrow varphi=60^ . cuadrante. ya que z ^ * corresponde a un punto del primer

Entonces

z = 3(eos * 60 deg + i * sin b * 0 deg)

Aplicando las fórmulas deducidas tenemos

i) z * z deg = 6(cos 180 deg + i * sin 180 deg) = 6(- 1 + 0i) = - 6

z/(z') = 2/3 * (cos 60 deg + i * sin 60 deg) = = 3/3 * i * 1/2 + ((sqrt(3))/2) = 1/3 + (sqrt(3))/3 * i

=2^ tan 05 120^ + i * sin 6.12 deg * t = 2 deg * t * cos 720 deg + art * 720 deg )= = 2 deg * c * cos 0 deg + i * sin 0 deg )=2^ (1+0.1)=2^ =64

Ejemplo 11-10.

Mediante la fórmula de De Moivre, obtener sen 2 y cos 2. Sea z un complejo de módulo 1 y argumento, es decir z = cos varphi + i * sin varphi

Elevamos al cuadrado de dos maneras: por cuadrado de un binomio

z ^ 2 = (cos varphi + iscn*varphi) ^ 2 =cos^ 2 varphi-sen^ 2 varphi+2 dot t sen (1)

y por la fórmula de De Moivre

z ^ 2 = (cos varphi + iscn*varphi) ^ 2 = cos 2varphi + iscn * 2varphi (2)

De(1) * y(2) resulta cos 2varphi = cos^2 varphi - sin^2 varphi n supseteq varphi = 2sin varphi * cos varphi

11.10. RADICACION EN C

Por derin.ción, el complejo w es raiz-sima de sí y sólo si " = w. Teorema. Todo complejo no nulo admiten raices n-simas distintas dadas por w=Vpl cos +2k+isen +2kㅠ) +2κπ p=121 y = arg donde k = 0, 1, 2 ,....,n-1 Demostración)

Sean=p(cos + i seny w R (cos + i sen ) Por definición de raíz, debe ser WAZ Es decir R" (cos n + i sen n ) = p (cos + i sen 4) Por igualdad de complejos Luego R" =р у n*Phi = varphi + 2k*pi RVPy Phi = (varphi + 2k*pi)/n

Se obtiene la fórmula root(rho(cos varphi + i * sin varphi), n) = root(rho, n) * (cos((varphi + 2kappa*pi)/n) + i * sin((varphi + 2kappa*pi)/n)) Todas las raíces de tienen el mismo módulo, y difieren en el argumento que es +2 con kez

De los infinitos valores enteros de k es suficiente considerar 0, 1, 2,...,-1 para obtener las raíces distintas.

RAICES

ARGUMENTOS

binomial(varphi,n)

varphi/n + (2pi)/n

varphi n +2. (2pi)/n

varphi/n + 3 * (2pi)/n

w n - 1

varphi/n + (n - 1) * (2pi)/n

w_{1}

w_{2}

kappa = n entonces la correspondiente raiz w_{n} tiene argumento

varphi/pi + n * (2pi)/n = varphi/n + 2pi

Que es congruente a varphi/n * y se vuelve a obtener wo

En general w j + n =w j y sólo existen n raices distintas. Nota

Las raíces n-simas, distintas de un complejo no nulo, se identifican con los vértices de un poligono regular den lados inscripto en la circunferencia de radio R= sqrt[n] rho.

w_{2}

w_{1}

W3

2

2万

(2pi)/n

w_{0}

varphi/n

(2pi)/n

\mathbb{R} = root(rho, n)

w n - 1

w n - 2

Ejemplo 11-11.

Calcular y representar

root(- 4 + 41sqrt(3), 4) z = - 4 + 4i * sqrt(3) = rho = sqrt((- 4) ^ 2 + (4sqrt(3)) ^ 2) = sqrt c4=8 cos rho = a/rho = - 4/8 = -1 2 Rightarrow varphi=120^ = 2 pi 3

pues: corresponde a un punto del segundo cuadrante. El argumeno de w_{k} es

Phi_{k} = ((2pi)/3 + 2k*pi)/4 = pi/6 + (k*pi)/2

y se tienen los cuatro argumentos

Phi_{0} = pi/6 = 30 deg Phi_{1} = pi/6 + pi/2 = 30 deg + 90 deg = 120 deg

Phi 2 =* pi/6 + pi = 30 deg + 180 deg = 210 deg

Phi_{3} = pi/6 + 3 * pi/2 = 30 deg + 270 deg = 300 deg

Las cuatro raíces son

w_{5} = root(8, 4) * (cos 30 deg + i * sin 30 deg) = sqrt[3] 8 ( sqrt 3 2 + i 2 ,1

w_{i} = root(8, 4) * (cos 120 ^ 0 + i * sin 120 deg) = = root(8, 4) * (- cos 60 deg + i * sin 60 deg) = root(8, 4) * (- 1/2 + i * (sqrt(3))/2)

omega_{2} = root(8, 4) * (cos 210 deg + i * sin 210 deg) = = root(8, 4) * (- cos 30 deg - i * sin 30 deg) = root(8, 4) * i - (sqrt(3))/2 - 1/5 * i )

w 3 = sqrt[4] 8 (cos 300^ + overline i * sin 300 deg )=

= root(8, 4) * (cos 60 deg - i * sin 60 deg) = root(8, 4) * (1/2 - i * (sqrt(3))/2)

ⅱ) root(t, 3)

z=1+0 i Rightarrow rho = i varphi = 0 Rightarrow root(1(cos 0 + i * sin 0), 3) = root(1, 3) * (cos((0 + 2k*pi)/3) + i * sin((0 + 2k*pi)/3)) = = cos((2k*pi)/3) + i * sin((2k*pi)/3)

Entonces

0050+ser: 01 w_{1} = cos((2pi)/3) + i * sin((2pi)/3) = ios * 120 ^ o + i * sin 120 ^ o = = - cos 60 deg + i * sin 60 deg = - 1/2 + i * (sqrt(3))/2 = - cos 60 deg - i * sin 60 deg = - 1/2 - i * (sqrt(3))/2

w_{2} = cos((4pi)/3) + i * sin((4pi)/3) = cos 240 deg + i * sin 240 deg =

11.11. FORMA EXPONENCIAL EN C

11.11.1. Exponencial compleja

En los cursos de Análisis se demuestra que la exponencial real e admite el desarrollo en serie e^ x = 1 + x + (x ^ 2)/(2!) + (x ^ 3)/(3!) +...= sum k=0 ^ infty x^ k k!

y satisface las propiedades básicas e ^ 0 = 1 لامعلم A fin de preservar estas propiedades definimos la exponencial compleja mediante

excosx + i sen x

Se verifica

(cosx + i sen x) (cos y + i sen y) = =(cosx cos y sen x sen y) + i (sen x cos y + cos x sen y) = = cos(x + y) + i * sin(x + y) = e ^ (l(x + y))

Sea z = p (cos + i sen). Entonces z = pel es la forma exponencial del complejo z.

Equihua

FORMA EXPONENCIAL

367

11.11.2. Operaciones en forma exponencial

La traducción de las fórmulas relativas al producto, cociente y potenciación,

obtenidas en la forma polar son las siguientes

i) z.zpele p'elp" = pp' el(p+p')

ii) Pele م 음 ρ

iii) z" (pel)" = p" elne

Ejemplo 11-12.

Demostrar

1)=e

En efecto

cos +1 sen =√cos²+sen = 1

ii) e^ z =1 Rightarrow z = 2n*pi*i con neZ Sea = x + y Entonces = قم = الامم = الاقم )COS v + i sen v( = = e ^ x * cos y + e ^ x * i * sin y = 1 + 0i

Por igualdad de complejos es e ^ x * cos y = 1 ^ (e ^ x) * sin y = 0 Como 0 resulta sen 0 y en consecuenciak con ke Z Ahora bien Luego y=k pi Rightarrow cos y = cosk*pi = (- 1) ^ k e ^ x * (- 1) ^ k = 1 = (- 1) ^ (2k) Es decir, ex(1) y como e>0, se tiene k = 2n Asi.e1=x=0 Resulta

z = x + yi = 0 + 2n*pi*i = 2n*pi*i

11.12. LOGARITMACION EN C

Sea0. Por definición In z = w y sólo si ez

Equihua

368

EL CUERPO DE LOS NUMEROS COMPLEJOS

Para determinar los complejos w que satisfacen w = ln(z) proponemos la ferma exponencial para el complejo z y la forma binómica para w, es decir

z = rho * e ^ (j*varphi) w = u + iy

Hay que determinary v tales que e ^ (mu + iv) = rho * e ^ (i*varphi) e ^ mu * e ^ (iv) = rho * e ^ (i*varphi) e^ omega = rho cap r = varphi + plus/minus k * pi u = ln(rho ^ v) = varphi + 2k*pi

Resulta

nz = ln(varphi) + i(varphi + 2k*pi) con k \in Z

fórmula que permite obtener los infinitos logaritmos de un complejo no nulo.

Como la parte real del n = cs independiente de k, todos los logaritmos corresponden a puntos de la paralela al eje de ordenadas que pasa por (In p. 0)

Valor principal de In z es el que se obtiene k = 0 o sea

V.p. z = ln(rho) + i*varphi

Ejemplo 11-13.

Hallar In z en los siguientes casos

1) z = - 2

z=-2+0 i Rightarrow rho = 2 ^ varphi = pi

Luego rz = ln(1) - 21 =ln 2+i( pi+2k pi i= = ln(2) + (1 + 2k) * pi ;

z = - e/(sqrt(2)) - e/(sqrt(2)) * i rho = sqrt((e ^ 2)/2) + (e ^ 2)/2 =e A varphi = 225 deg = 5 * pi/4

Entonces

ln z=ln e+i( int 5 pi/4 + 2k*pi )= = 1 + i(5 * pi/4 + 2kappa*pi)

Los valores principales son, respectivamente, In 2 + i*pi y 1 + 5 * pi/4 * 1

11.13. ΕΧΡΟNENCIAL COMPLEJA GENERAL

z_{1}*y*z_{2} tales que z_{1} ne0. Estamos interesados en la determinación de la exponencial compleja

w = z_{1} ^ x_{2}

Aplicando logaritmos en hase natural

w=z z ln(z) z |

Por definición de logaritmo w=e^ x 2 ln(x) 1

Ejemplo 11-14.

Hallar el valor principal de la exponencial

z = ((1 - i)/(1 + i)) ^ i

11.13. EXPONENCIAL COMPLEJA GENERAL

Sean z_{1}*y*z_{2} tales que z_{1} ne0 Estamos interesados en la determinación de la exponencial compleja

w = z_{1} ^ z_{2}

Aplicando logaritmos en base natural

In w=z 2 ln(z) 1 |

w=e^ x z ln(z) 3

Por definición de logaritmo

Ejemplo 11-14.

Hallar el valor principal de la exponencial z = ((1 - i)/(1 + i)) ^ i

Equihua

370

EL CUERPO DE LOS NUMEROS COMPLEJOS

Calculamos (1 - i)/(1 + i) = ((1 - i) ^ 2)/((1 + i)(1 - i)) = (1 - 2i - 1)/2 = - i

Entonces z=(-i)^ i Rightarrow ln(z) = i * ln(- i) (1)

A complejoi - i le corresponden

rho= sqrt 0 ^ 2 +(***1)^ 2 =1 varphi = 3 * pi/2

Entonces ln(- i) = ln(1) + i(3 * pi/2 + 2kr) = = 1(3 * pi/2 + 2k*pi)

Sustituyendo en (1) tenemos

ln z= - 3 * pi/2 -...>= k pi

Por definición de logaritmo resulta z = e

Siendo el valor principal V, p, z = e ^ (-3 * u/2)

11.14. RAICES PRIMITIVAS DE LA UNIDAD

11.14.1 Concepto

En el ejemplo 11-11-ii) hemos determinado las raíces de orden 3 de la unidad, es decir, las tres raíces cúbicas de 1. Tales raíces son w_{0} = 1 w_{1} = - 1/2 + i * (sqrt(3))/2 w_{2} = - 1/2 - i - (sqrt(3))/2

Las dos últimas no son raíces de la unidad de un orden menor que 3, pero la primera sí lo es, puesto que root(1, 1) = 1 y root(1, 2) = plus/minus 1

Por este motivo se dice que w₁ y w₁ son raices primitivas de orden 3 de la unidad: en cambio, w_{0} = 1 no es raiz primitiva de orden 3 ni de orden 2, sino de orden 1.

Equihua

RAICES PRIMITIN AS

371

Sea G, el conjunto de las raíces n-simas de la unidad. Un elemento genérico de Ges w_{h} = cos((2k*pi)/n) + i * sin((2k*pi)/n) = e ^ (i * (2k*pi)/n)

donde k = 0, 1, 2 ,...,n-1 Por definición de raíz -sima, los complejos w satisfacen w 1, y son tales que (G,..) es un grupo multiplicativo abeliano. Esta situación ha sido tratada en el ejemplo 8-12, en el caso particular en que 123.

Definición

El elemento we en es una raiz primitiva de orden de ia umdad sa у овом по es raíz de 1 de un orden menor que

El conjunto de las raíces cuartas de la unidad es G. con la definición y con el conocimiento de G G G 1.1.-1 De acuerda podemos decir que y som raices primitivas de orden 4 de la unidad. Los resultados 1.1.1 yi se obtienen de la fórmula general al tomar k los valores 0. 1. 2 y 3, respectivamente. Observamos aquíque si k es coprimo con n. entonces la raiz wa es primitiva. Tal es el caso de y Wa para 4. La demostración de esta propiedad es el objeto de lo que sigue.

11.14.2. Propiedad. El complejo wa e G, es raizm-sıma de la unidad si y sólo s n km.

Demostración Sea w_{k} = cos((2k*pi)/n) + i * sin((2k*pi)/n) =e^ i 2 R- R in G n Entonces n k = sqrt[m] 1 Leftrightarrow w k ^ prime prime =1 Leftrightarrow cos - (2km*pi)/n + i * sin - (2km*pi)/n =! infty cos((2km*pi)/n) = 1sin((2km*pi)/n) = 0 * ∞ (2km*pi)/n = 2pi * q ^ q in Z Rightarrow. nikm

11.14.3. Propiedad. Sea 0 <= k < n Entonces wh e G, es una raiz primitiva de orden de la unidad si y sólo sin y k son coprimos.

1) ny k son coprimos we es raíz n-sima primitiva de 1.

Sea wa una raíz m-sima de la unidad. Entonces, por 11.14.2.. se tiene que ni kin y como n y k son coprimos, resulta nm. de acuerdo con lo demostrado en el ejemplo 9-8-ji). Ahora bien, siendo nym números naturales y nm, es nm, y en consecuencia wa no es raíz de la unidad de un orden menor que n, o lo que es lo mismo, we es raíz primitiva de orden n de 1.

11) es raiz -sima primitiva de 1 Rightarrow m.c.d. (n, k) = 1 w_{k} Supongamos que [[y, k]] no son coprimosm.c.d. positivo. Por definición de m.c.d. se tiene

dinadikndu'kdk donde m.c.d. ( n' ,k^ prime prime )=1

Sustituyendo estos valores en la expresión de W_{k} resulta

w n =cos- 2 d k^ prime pi dot d n^ prime + i * sin((2 * d * k' * pi)/(d * n')) = こん sen

Como n' * y * k' son coprimos se deduce que es raiz de la unidad de orden n ^ * <n. w_{k} lo que contradice la hipótesis. Luego debe ser ( (n, k) = 1

Ejemplo 11-15.

Determinar las raíces primitivas de orden & de la unidad. Las seis raíces sextas de 1 están dadas por omega_{k} = omega*os * (2k*pi)/6 + i * sin((2k*pi)/n)

con k = 0.1 ,.....5 De acuerdo con 11.14.3. 1) elegimos k de modo que m.c.d. ( n .6)=1 y se obtiene k = 1 5. Las raíces primitivas pedidas son, entonces

= cos((2pi)/6) + i * sin((2pi)/6) = = cos(pi/3) + i * sin(pi/3) = cos 60 deg + i * sin 60 deg = = 1/2 + i * (sqrt(3))/2 10 sen 107 = cos((3pi)/3) + t * sin((5pi)/3) = cos 300 ^ alpha + i * sin 300 deg = cos 50 deg - i * sin 60 deg = 1/2 - i * (sqrt(3))/2