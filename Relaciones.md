# Relaciones y funciones 

En este capítulo estudiamos dos tipos especiales de conjuntos: las relaciones y las funciones.  

## A. Relaciones
Sean $A$, $B$ dos conjuntos no vacíos, una **relación $R$ de $A$ en $B$** es un subconjunto $R \subseteq A \times B$.  
$R$ es una relación si $R \subseteq A \times B$. 

Ejemplo. $\emptyset \subseteq A \times B$ es una relación. $\blacksquare$
Ejemplo. Sean $A = \{a, b, c\}$ y $B = \{3, 5, 7\}$.  
  $R_1 = \{(a, 3)\}$,  
  $R_2 = \{(a, 3), (a, 5), (a, 7)\}$,  
  $R_3 = \{(b, 3), (a, 3), (c, 3)\}$.  
  Son relaciones de $A$ en $B$. 
  Como $|A \times B| = 9$, hay $2^9 = 512$ posibles relaciones de $A$ en $B$.  

Ejemplo. Sean $A = B = \mathbb{Z}$ y definamos $$R = \{(x, x^2) : x \in \mathbb{Z}\}$$.  
Así, por ejemplo, $$(1, 1), (2, 4), (-2, 4) \in R$$,  
pero $(2, 3) \notin R$ pues $3 \neq 2^2$.  
pero $(\sqrt{2}, 2) \notin R$ pues $\sqrt{2} \notin \mathbb{Z}$.  
Nota: $(x, y) \in R$ cuando $y = x^2$.  $\blacksquare$


Toda relación $R \subseteq A \times B$ tiene asociados dos conjuntos:  
- El **dominio** de $R$: $$D_R = \{a \in A : (\exists b \in B) \text{ tal que } ((a, b) \in R)\}$$.  
- La **imagen** de $R$: $$I_R = \{b \in B : (\exists a \in A) \text{ tal que } ((a, b) \in R)\}$$.  

**Ejemplo:**  De los ejemplos anteriores:
$$
\begin{align}
D_{R_1} = \{a\} && I_{R_1} = \{3\}\\
D_{R_2} = \{a\} && I_{R_2} = \{3,5,7\}\\
D_{R_3} = \{b,a,c\} = A && I_{R_3} = \{3\}\\
D_R = \mathbb{Z} && I_{R} = \{x^2 : x \in \mathbb{Z}\}\\
\end{align}
$$

**Ejemplo:** Sea $A=\{1,2,3\}$ y $B=\{1,3,5,7\}$
Pongamos
$$S = \{(x,2x):x \in A\}$$
Entonces 

$$
\begin{align}
D_5 = \emptyset && I_5 = \emptyset,\\
\text{i.e. } ,\\
S = \emptyset && \blacksquare
\end{align}
$$
**Ejemplo:** Sea $A=B=\mathbb{Z}$ y pongamos:
$$R=\{(x,x^2): x\in \mathbb{Z}\}$$
Asi, por ejemplo,
$(1,1),(2,4),(-2,4) \in R$

Pero
$(2,3) \notin R$ , pues $3 \neq 2^2$
$(\sqrt{2},2) \notin R$ , pues $\sqrt{2} \notin \mathbb{Z}$ $\blacksquare$

**Ejemplo:** En $R$ definimos
$$
x \sim y \Longleftrightarrow x^2 = y^2
$$

Es $\sim$ una relacion de equivalencia?

**Demostrar:**

En $\mathbb{R}$ definimos $$x \sim y \Leftrightarrow x^2 = y^2$$. ¿Es $\sim$ una relación de equivalencia?  
- **(i) Reflexividad**: $(\forall x \in \mathbb{R}) (x \sim x)$. 
	Para todo $x \in \mathbb{R}$, es obvio que $x = x$ ; de aqui se sigue que $x^2 = x^2$; i.e., $x \sim x$.  
- **(ii) Simetría**: $(\forall x, y \in \mathbb{R}) (x \sim y \Rightarrow y \sim x)$. 
	Sean $x,y \in \mathbb{R}$ tal que $x \sim y$, i.e., $x^2 = y^2$. 
	Por simetría de la igualdad, se sigue que $y^2 = x^2$. Esto quiere decir que $y \sim x$.    
- **(iii) Transitividad**: $(\forall x, y, z \in \mathbb{R}) (x \sim y \land y \sim z \Rightarrow x \sim z)$. 
	Sean $x, y, z \in \mathbb{R}$ y supongamos que $x \sim y$ e $y \sim z$. Entonces, por la definicion de $\sim$ tenemos que  $$x^2 = y^2 \wedge y^2 = z^2$$. De aqui se obtiene que $x^2 = z^2$; i.e.,  $x \sim z$.  
Por tanto, $\sim$ es relación de equivalencia.  $\blacksquare$

**Otro ejemplo:**  
En $\mathbb{R}$ definimos $$x \mathbin{\Delta} y \Longleftrightarrow (\exists z \in \mathbb{Z})(y = x + z) \quad y-x \in \mathbb{Z}$$. 
¿Es $\Delta$ relación de equivalencia?  

**Demostrar:**
En esta relacion tenemos que
$$
\begin{align}
1.1 \; \mathbin{\Delta} \; 0.1 && \text{pues } && 0.1 = 1.1 + (-1) \\
3.73 \; \mathbin{\Delta} \;  -5.73 && \text{pues } && -5.73 = 3.73 + (-8) \\
\neg (1.1 \; \mathbin{\Delta} \; 1) && \text{pues } && 1 - 1.1 = 0.1 \notin \mathbb{Z} \\
\end{align}
$$

- **(i) Reflexividad**: Sea $x \in \mathbb{R}$. 
	Como $x = x + 0$, entonces $x \mathbin{\Delta} x$.  
- **(ii) Simetría**: Sean $x, y \in \mathbb{R}$ y supongamos que $x \mathbin{\Delta} y$. Entonces existe $c \in \mathbb{Z}$ tal que $$y = x + c$$. De aqui, $$x = y - c = y + (-c)$$con $-c \in \mathbb{Z}$. Por tanto, $y \mathbin{\Delta} x$.  
- **(iii) Transitividad**: 
	Sean $\alpha, \beta, \gamma \in \mathbb{R}$ y supongamos que $\alpha \mathbin{\Delta} \beta$ e $\beta \mathbin{\Delta} \gamma$. Entonces  existen $a, b \in \mathbb{Z}$ talque $$\beta = \alpha + a$$ y $$\gamma = \beta + b$$. Luego, $$\gamma = \beta + b = (\alpha + a) + b =  \alpha + (a + b)$$ con $a + b \in \mathbb{Z}$; Asi, $\alpha \mathbin{\Delta} \gamma$ .  $\blacksquare$
	
Por tanto, $\Delta$ es relación de equivalencia.

Que hacen las relaciones de equivalencia? Particionan al conjunto donde estan definidas en "pedazos" llamados "**clases de equivalencia**".

Sea $R \subseteq A^2$ una relación de equivalencia y sea $a \in A$. La **clase de equivalencia** de $a$ es:  
$$
[a] = \{x \in A : x \mathbin{R} a\}.
$$  
Por reflexividad, para todo $a \in A$, $[a] \neq \emptyset$. A saber, por lo menos  $a \in [a]$.
Si $\neg(a \mathbin{R} b)$, entonces $[a] \cap [b] = \emptyset$.  
En efecto, supongamos que $x \in [a] \cap [b]$.
Entonces $x \in [a]$ y $x \in [b]$, luego $$x \mathbin{R} a \qquad \text{ y } \qquad x \mathbin{R} b$$, y de aqui se obtendra que $a \mathbin{R} b$, lo que contradice lo supuesto.
Si $a \mathbin{R} b$, entonces $[a] = [b]$.  
Por ultimo es evidente que $$\bigcup_{a \in A} [a] = A$$.  

Entonces podemos coleccionar todoas las clases de equvialentecia que forma la relacion de equivalencia $\mathbin{R} \subseteq A^2$ y obtenemos el conjunto $$A/\mathbin{R} = \{[a] : a \in A\}$$ que se llama el **conjunto cociente** de A por R.

Si $\mathbin{R} \subseteq A^2$ es una relacion de equivalencia y $[a] = \{x \in A : x \mathbin{R} a\}$ es una clase de equivalencia en $A/\mathbin{R}$, el elemento $a$ se llama el **representante** de la clase.

**Observacion**
i. Si $\mathbin{R},\mathbin{S} \subseteq A^2$ son ambas relaciones de equivalencia, para evitar confusiones, escribimos $[a]_R$ y $[a]_S$ para indicar la clase de equivalencia de $a \in A$ respecto de $\mathbin{R}$ y $\mathbin{S}$, respectivamente.
ii. Calcular
$$
[a] = \{x \in A : x \mathbin{R} a\}
$$

suele reducirse a "resolver" $x \mathbin{R} a$, donde, obviamente, $x$ es la incognita. $\blacksquare$

**Ejemplo:**
Ya vimos que en $\mathbb{R}$ $$x\sim y \Longleftrightarrow x^2 = y^2$$ es una relacion de equivalencia. Calculamos $[a]$ con $a \in \mathbb{R}$.

$$
\begin{align}
[a] &= \{x \in \mathbb{R} : x \sim a\}\\
&= \{x \in \mathbb{R} : x^2 = a^2\}\\
&= \{x \in \mathbb{R} : x^2 - a^2 = 0\}\\
&= \{x \in \mathbb{R} : (x - a)(x + a) = 0\}\\
&= \{x \in \mathbb{R} : x = a \vee x = -a\}\\
&= \{a,-a\}\\
\end{align}
$$

Podemos "graficar" esto:
![[Pasted image 20250530004123.png]]

**Ejemplo:**  
Por ejemplo,
$$
\begin{align}
[1] &= \{1,-1\} = [-1]\\
[-\frac{3}{2}] &= \left\{-\frac{3}{2},\frac{3}{2}\right\} = [\frac{3}{2}]\\
[\sqrt{2}] &= \{\sqrt{2},-\sqrt{2}\} = [-\sqrt{2}]\\
[e] &= \{e,-e\} = [-e]\\
\end{align}
$$

Por tanto,
$$R/\sim = [0,+ \inf) = (-\inf,+ 0]$$ $\blacksquare$

**Ejemplo:**
En $\mathbb{R}^2$ sea $\mathcal{L}$ el conjunto de todas las rectas en $\mathbb{R}^2$. En $\mathcal{L}$ definimos:  
$$
\ell_1 \sim \ell_2 \Longleftrightarrow \ell_1 \parallel \ell_2.
$$

Es evidente que $\sim$ es una relación de equivalencia, dada

$$\ell: y - 2 = \frac{2}{3}(x - 1)$$, calcular $[\ell]$ y bosquejar $\mathcal{L}/\sim$
**Solucion**
Primero reeescribimos la ecuacion de L.
$$ 
\begin{align}
y - 2 &= \frac{2}{3}(x - 1)\\
y     &= \frac{2}{3}x - \frac{2}{3}+ 2\\
y     &= \frac{2}{3}x - \frac{4}{3}\\
\end{align}
$$

Sabemos que dos rectas son paralelas si tienen igual pendiente.

$$
\begin{align}
  \left[\ell: y = \frac{2}{3}x - \frac{4}{3}\right] &= \{M \in \mathcal{L}: M \sim \mathcal{L}\} \\
  &= \{M \in \mathcal{L}: M \parallel \mathcal{L}\} \\
  &= \left\{M \in \mathcal{L}: m_M = \frac{2}{3}\right\} \\
  &= \left\{ \left\{ \ell: y = \frac{2}{3}x + b \right\} : b \in \mathbb{R} \right\} \\
  &= \left[ y = \frac{2}{3}x \right] \\
\end{align}
$$  
De forma análoga:
$$
[\ell : y = 3x - 1] = \{ \{ \ell: y = 3x + c \} : c \in \mathbb{R} \} = [ \ell : y = 3x ] 
$$

El conjunto cociente es:  

![[Pasted image 20250530015736.png]]
  $$
  \mathcal{L}/{\sim} = \left\{ \left\{ y = mx + c : c \in \mathbb{R} \right\} : m \in \mathbb{R} \right\} \quad (\text{conjunto de todas las direcciones}).
  $$  
$\blacksquare$

**Ejemplo:** En teoria de numeros la siguiente relacion es, quizad la mas importante.
En $\mathbb{Z}$ sea $n \in \mathbb{Z}$ con $n>1$ y definimos $$a \sim b \Longleftrightarrow(\exists \; c \in \mathbb{Z})(a-b = c \cdot n)$$
Es una relacion de equivalencia:

i. Reflexividad : Sea $a \in \mathbb{Z}$. Como $$a-a = 0 = 0 \cdot n$$, se tiene que $a \sim a$.

ii. Simetria: Sean $a,b \in \mathbb{Z}$ tal que $a \sim b$. Entonces, existe $c \in \mathbb{Z}$ tal que $$a - b = c \cdot n$$ con $c \in \mathbb{Z}$.
Multiplicamos esto por $-1$ obtenemos $$b-a = (-c)\cdot n$$, con $-c \in \mathbb{Z}$. Asi, $b \sim a$.
 
iii. Transitividad: Sean $a,b,c \in \mathbb{Z}$ tal que $a \sim b$ y $b \sim c$. Entonces, existen $\alpha, \beta \in \mathbb{Z}$ talque 
$$
a - b = \alpha \cdot n \qquad \text{y} \qquad  b - c = \beta \cdot n
$$
Sumando estas dos igualdades:
$$
\begin{align}
(a - b) + (b - c) &= \alpha \cdot n + \beta \cdot n\\
a - c &= (\alpha + \beta ) \cdot n\\
\end{align}
$$, i,e, $a \sim c$.
Esta relacion de equivalencia se llama **congruencia modulo n** y se denota por 
$$
a \equiv b \pmod{n} \Leftrightarrow (\exists c \in \mathbb{Z})(a - b = c \cdot n).
$$


**Ejemplo:** Sea $n = 5$. La clase de $7$ es:  
$$
\begin{align}
[7] &= \{x \in \mathbb{Z} : x \equiv 7 \pmod{5}\} \\
&= \{x \in \mathbb{Z} : (\exists c \in \mathbb{Z}) (x - 7 = 5\cdot c)\} \\
&= \{x \in \mathbb{Z} : (\exists c \in \mathbb{Z}) (x = 7 + 5\cdot c)\} \\
&= \{x \in \mathbb{Z} : (\exists c \in \mathbb{Z}) (x = 2 + 5\cdot (c+1)\} \\
&= \{ 5 \cdot k + 2 : k \in \mathbb{Z}\} \\
&= \{\ldots, -8,-3, 2, 7, 12, \ldots\} = [2].
\end{align}
$$  
**Observacion**
Notemos que la clase de equivalencia $[7]$ que acabamos de calcular tiene infinitos elementos por ente $[7]$ tiene infinitos representantes. e.g
$$
[7] = [2] = [12] = [-3] = [-8] = \dots
$$
$\blacksquare$

El **Algoritmo de la division** nos garantiza que esta relacion de equivalencia solo tiene 5 clases de equivalencia a saber:

El conjunto cociente es $\mathbb{Z}/\equiv_5 = \{[0], [1], [2], [3], [4]\}$.  
$\blacksquare$

Entonces una relacion de equivalentecia es una **clasificacion** de los elementos de l conjunto.

Sea $\{A_i\}_{i \in I}$ una familila de subconjuntos de $\mathbin{X}$, se denomina una **particion** de $\mathbin{X}$ si:

(i) $(\forall i \in I)(A_i \neq \emptyset)$;
(ii) $(\forall i,j \in I)(A_i \cap A_j = \emptyset)$;
(ii) $\bigcup_{i \in I} A_i = X$.

Lo visto anteriormente nos muestra que si $\mathbin{R} \subseteq A^2$ es una  relacion de equivalencia, entonces $$A/\mathbin{R}=\{[x]: x \in A\}$$
es una partición de A. 

Asi, tenemos el **Teorema fundamental de las relaciones de equivalencia**.

**Teorema:**  
Sea $A \neq \emptyset$ y sea $R \subseteq A^2$ una relación de equivalencia, entonces $A/\mathbin{R}$ es una partición de $A$. Recíprocamente, si $\{A_i\}_{i \in I}$ es una partición de $A$, podemos definir una relación de equivalencia a saber,
$$
x \mathbin{R} y \Leftrightarrow (\exists i \in I)(x,y \in A_i).
$$  

**B. Relaciones de orden**  
Ahora generalizamos el concepto de orden de los números reales. La relación $\leq$ en $\mathbb{R}$ satisface:  
(i) $\forall x \in \mathbb{R}$, $x \leq x$;  
(ii) $\forall a, b, c \in \mathbb{R}$, $a \leq b \land b \leq c \Rightarrow a \leq c$;  
(iii) $\forall a, b \in \mathbb{R}$, $a \leq b \land b \leq a \Rightarrow a = b$.  

Generalizamos estas propiedades:  
Sea $A \neq \emptyset$ y $R \subseteq A \times A$. Decimos que $R$ es un **orden parcial** (o relación de orden) si satisface:  
- **(i) Reflexividad**: $\forall x \in A$, $x \mathbin{R} x$.  
- **(ii) Transitividad**: $\forall x, y, z \in A$, $x \mathbin{R} y \land y \mathbin{R} z \Rightarrow x \mathbin{R} z$.  
- **(iii) Antisimetría**: $\forall x, y \in A$, $x \mathbin{R} y \land y \mathbin{R} x \Rightarrow x = y$.  

**Ejemplo:** En $\mathbb{R}$ definimos:  
$$
x \preccurlyeq y \Leftrightarrow (\exists z \geq 0)(x + z = y).
$$  
Esta es un orden parcial sobre $\mathbb{R}$:  
- **(i) Reflexividad**: $\forall x \in \mathbb{R}$, $x + 0 = x$, luego $x \preccurlyeq x$.  
- **(ii) Transitividad**: Si $x \preccurlyeq y$ e $y \preccurlyeq z$, existen $a, b \geq 0$ con $y = x + a$ y $z = y + b$. Entonces $z = x + (a + b)$ con $a + b \geq 0$; luego $x \preccurlyeq z$.  
- **(iii) Antisimetría**: Si $x \preccurlyeq y$ e $y \preccurlyeq x$, existen $a, b \geq 0$ con $y = x + a$ y $x = y + b$. Sustituyendo: $y = (y + b) + a \Rightarrow 0 = a + b$. Como $a, b \geq 0$, $a = b = 0$; luego $x = y$.  

**Orden total:** Un orden parcial $R$ es **total** si $\forall a, b \in A$, $a \mathbin{R} b \lor b \mathbin{R} a$.  

**Relación de orden estricto:**  
Toda relación de orden $R \subseteq A \times A$ tiene asociada una relación $S \subseteq A \times A$ que satisface:  
(i) **Irreflexividad**: $\forall a \in A$, $\neg(a \mathbin{S} a)$.  
(ii) **Transitividad**: $\forall a, b, c \in A$, $a \mathbin{S} b \land b \mathbin{S} c \Rightarrow a \mathbin{S} c$.  
Esta relación $S$ se llama **orden estricto**.  


**Ejemplo:** En $\mathbb{R}$ definimos para todo $a,b \in \mathbb{R}$:  
$$
a < b \Leftrightarrow (\exists c \in \mathbb{R})(c > 0 \land b = a + c).
$$  
Esto define un orden estricto.  $\blacksquare$

En un cojunto ordenado ($\mathbin{R} \subseteq A^2$ un orden) tenemos algunos elementos especiales

Sea $B \subseteq A$, entonces

1. **Mínimo**: Se dice que $b\in B$ es el **minimo** de $B$ o el **primer elemento** de $B$ si $$(\forall c \in B)(b \mathbin{R} c)$$
	Si existe, se escribe $b=\text{min }B$.
2. **Máximo**: Se dice que $k\in B$ es el **maximo** de $B$ o el **ultimo elemento** de B si $$(\forall c \in B)(c \mathbin{R} k)$$
	Si existe, se escribe $k=\text{max } B$

**Ejemplo:** En $\mathbb{R}$ con el orden usual sean $A=(1,2)$, $A=[1,2)$ y $A=[1,2]$

Etonces:
min A no existe
max A no existe

min B = 1
max B no existe

min C = 1
max C = 2

**Ejemplo:** En $\mathbb{R}$ con el orden usual:  
- $A = (1, 2)$: $\min A$ no existe, $\max A$ no existe.  
- $B = [1, 2)$: $\min B = 1$, $\max B$ no existe.  
- $C = [1, 2]$: $\min C = 1$, $\max C = 2$.  



3. **Cotas inferiores**: Se dice que $a \in A$ es una **cota inferior** de $B$ si $$(\forall x \in B)(a \mathbin{R} x)$$. 
	El conjunto de todas las cotas inferiores de B se denota por $B^-$.  
4. **Cotas superiores**: Se dice que $b \in A$ es una **cota superior** de $B$ si $$(\forall x \in B)(x \mathbin{R} b)$$.
	El conjunto de todas las cotas superiores de B se denota por $B^+$.  
5. **Ínfimo o maxima cota inferior**: Se dice que $a \in A$ es el **ínfimo** de $B$ si es el máximo de $B^-$. 
	Si existe, escribimos $a = \text{inf } B$ y $\text{inf B} = \text {max } B^-$.  
6. **Supremo o minima cota superior** : Se dice que $b \in A$ es el **supremo** de $B$ si es el mínimo de $B^+$. 
	Si existe, escribimos $b = \text{sup } B$ y $\text{sup } B = \text{min } B^+$.  
7. **Elementos minimales**: Se dice que $b \in B$ es **minimal** o un **elemento minimal** si $$x \mathbin{R} b \Rightarrow x = b $$. I. e., un elemento minimal no tiene ningun elemento menor que el sin que esto signifique que es el minimo
	**Observacion** Minimo implica minimal, pero minimal no neceriamente implica minimos. $\blacksquare$
- **Elementos maximales**: Se dice que $d \in B$ es **maximal** o un **elemento maximal** si $$d \mathbin{R} x \Rightarrow x = d $$. I. e., un elemento maximal no tiene ningun elemento mayor que el sin que esto signifique que es el maximo.
	**Observacion** Maximo implica maximal, pero maximal no neceriamente implica maximo. $\blacksquare$  


Los conjuntos (parcialmente) ordenados, a veces llamamos **c.o.p.o.s**, que son finitios son representados graficamente por unos diagramas llamados **diagramas de Hasse:**

Construimos el diagrama de Hasse de la siguiete forma:


1. Colocamos los elemtnso del copo en un plano : si $a \leq b$, dibujamos $a$ por debajo de $b$ y los unimos con un segmento de recta
```  
    b        b     b
    |       /       \
    a      a         a
```  

2. Las interconexiones entre tres o mas puntos nos indican transitividad; i.e no colocamos las "lineas de transitividad"
```  
  d   c              ---- c
   \ /             /    /
    b            b    /
     \             \ /
      a              a
```  
3. No se dibujan bucles i,e, no se dibuja una linea que conecte cada elemento consigo mismo, pero se **sobreentiende la reflexiviodad**.  

```  
     () c              
     /             
    () b               
     \            
      () a              
```  


No se dibuja los bucles para evitar sobrecargar el diagrama

**Ejemplo:** Sea $D(12)$ el conjunto de divisores de $12$: $\{1, 2, 3, 4, 6, 12\}$. Ordenamos por divisibilidad:  
$$
x \preccurlyeq y \Leftrightarrow (\exists k \in \mathbb{N})(y = k \cdot x).
$$  
Diagrama de Hasse:  
```  
    12  
    / \  
   6   4  
   |   |  
   3   2  
    \ /  
     1  
```  
- $\min D(12) = 1$, $\max D(12) = 12$.  

**Ejemplo con incomparabilidad:**  
Sea $X = \{a, b, c, d, e, f, g, h\}$ con diagrama de Hasse:  
```  
    h  
   /|\  
  f g d  
  | | |  
  e c b  
    |  
    a  
```  
- $\max X = h$, $\min X$ no existe.  
- Para $Z = \{d, e\}$:  
  Cotas superiores: $Z^+ = \{d, g, h\}$, $\sup Z$ no existe.  
  Cotas inferiores: $Z_- = \{a, c\}$, $\inf Z$ no existe.  
- Elementos minimales: $a, b$.  
- Elementos maximales: $h$.  

**Aplicación en economía:**  
En microeconomía, las relaciones de orden total modelan preferencias de consumidores "racionales". La antisimetría corresponde a la **indiferencia** entre opciones equivalentes.  

**B. Funciones**  
*(El texto original termina aquí abruptamente)*.


falta 13-mayo