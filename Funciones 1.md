### B. Funciones

Ahora estudiamos un tipo especial de relación: las funciones.

Cuando $(a,b) \in f$, escribimos $$b = f(a)$$, donde $f(a)$ se lee "f de a".

**Observacion:** Es casi universal escribir $f(a)$; sin embargo, hay algunos autores que escriben $(a) f$. Es el caso de I.N. Herstein en su libro *Abstract Algebra*. $\blacksquare$

Según esta definición, las siguientes relaciones no son funciones:

![[Pasted image 20250530222604.png]]

![[Pasted image 20250530222629.png]]
En cambio, las siguientes sí son funciones:
![[Pasted image 20250530222723.png]]
![[Pasted image 20250530222739.png]]

Si $f: A \to B$ es una función, el conjunto $A$ se llama el **dominio** de $f$, y el conjunto $B$ se llama el **codominio** de $f$. El subconjunto de $B$ dado por $R_f = \{b \in B : (\exists a \in A) \, (b = f(a))\}$ se llama el **recorrido** o **rango** de $f$.

En álgebra, para determinar una función, debemos dar simultáneamente tres "datos":  

- (i) el dominio;  
- (ii) el codominio;  
- (iii) la regla de **correspondencia** que indica cómo se asigna un elemento del codominio a cada elemento del codominio. Esto se hace mediante fórmulas algebraicas, diagramas de Venn o asignaciones explícitas.

Las funciones  
$$
\begin{align}
f: \mathbb{R} & \to \mathbb{R} \\ x & \mapsto \sin x 
\end{align}
$$  
y  
$$
\begin{align}
g: \mathbb{R} & \to [-1, 1] \\ t &\mapsto \sin t
\end{align}
$$  
como conjuntos son idénticas, pero como funciones son distintas.

**Observacion:** Cuando $g : W \to Z$ es una función escribimos $w \mapsto g(w)$ para indicar la regla de correspondencia. 
El símbolo $\mapsto$ se lee "se aplica a". $\blacksquare$

**Ejemplo:** Sea $f: A \to B$, donde $A = \{a,i,u,e,o\}$ y $B = \{2, 3, 5, 7, 11\}$, la función dada por:  
$$
\begin{flalign}
    a \mapsto 2   & \quad & 
    i \mapsto 3   & \quad &
    u \mapsto 5   & \quad &
    e \mapsto 7   & \quad &
    o \mapsto 11. \\
    f(a) = 2      & \quad &
    f(i) = 3      & \quad &
    f(u) = 5      & \quad &
    f(e) = 7      & \quad &
    f(o) = 11.
\end{flalign}
$$
$\blacksquare$

Las funciones se clasifican en tres:  
(i) **Inyectividad.** Sea $f: A \to B$ una función; se dice que es **inyectiva** o **uno-a-uno** si 
$$a \neq b \implies f(a) \neq f(b)$$

con $a, b \in A$. O equivalentemente $f(a) = f(b)$

**Ejemplo:** Sea $f: \mathbb{R} \to \mathbb{R}$ dada por $f(x) = x^2 + 1$. ¿Es inyectiva?  

**Solución:** No, no es inyectiva pues 
$$
\begin{align}
f(1) &= 1^2 + 1 = 2 \\
f(-1) &= (-1)^2 + 1 = 2
\end{align}
$$
, pese a que $1 \neq -1$. Por tanto, $f$ no es inyectiva.
Por otro lado supongamos que 
$$
\begin{align}
f(a) &= f(b)  \\
a^2+1 &= b^2+1  \\
a^2-b^2 &= 0  \\
(a+b)(a-b) &= 0  \\
a=b &\lor a=-b \\
\end{align}
$$
$\therefore f$ no es inyectiva 

**Ej:** Sea $g : \mathbb{Q} \setminus \left\{-\frac{1}{2}\right\} \to \mathbb{Q} \setminus \left\{-\frac{3}{2}\right\}$ dada por $g(q) = \frac{2 - 3q}{1 + 2q}$. ¿Es inyectiva?  
**Solución:** Supongamos que
$$
\begin{align}
g(w) &= g(v)\\
\frac{2 - 3w}{1 + 2w} &= \frac{2 - 3v}{1 + 2v}\\
(2 - 3w)(1 + 2v) &= (2 - 3v)(1 + 2w)\\
2 + 4v - 3w - 6vw &= 2 + 4w - 3v - 6vw\\
4v - 3w &= 4w - 3v\\
7v &= 7w\\
v &= w.
\end{align}
$$

$\therefore f$ no es inyectiva. $\blacksquare$

**Ej:** Sea $h: (-\infty, \frac{2}{3}] \to \mathbb{R}$ dada por $h(x) = \sqrt{2 - 3x} + 1$. ¿Es inyectiva?  
**Solución:** Supongamos que

$$
\begin{align}
h(a) &= h(b) \\
\sqrt{2 - 3a} + 1 &= \sqrt{2 - 3b} + 1\\
\sqrt{2 - 3a} &= \sqrt{2 - 3b} \\
2 - 3a &= 2 - 3b \\
-3a &= -3b \\
a &= b.
\end{align}
$$
$\therefore h$ no es inyectiva. $\blacksquare$

(ii) **Suryectividad** (*sobreyectividad*;*epiyectividad*).  
Sea $g: Z \to W$ una función; se dice que g es **suryectiva** (o **sobreyectiva** o **epiyectiva**) si $$(\forall b \in W) \, (\exists a \in Z) \, (b = g(a))$$.

Para chequear la suryectividad, hay que resolver la ecuación $b = g(a)$ para "$a$" sin introducir restricciones nuevas implícita o explícitamente. 

Repetimos los ejemplos:  

**Ejemplo:** $f: \mathbb{R} \to \mathbb{R}$, $x \mapsto x^2 + 1$. ¿Es suryectiva?  

**Solución:** 
Sea $y = 0$, entonces resolvemos $$0 =f(x) = x^2 + 1 \Rightarrow x^2 = -1$$; esta ecuacion no tiene solución en $\mathbb{R}$.

$\therefore f$ no es suryectiva. 

Alternativamente, sea $y \in \mathbb{R}$ y resolvemos:  
$$
\begin{align}
y = x^2 + 1 & \implies x^2 = y - 1 & \\ 
& \implies x = \pm \sqrt{y - 1}, & \text{ si } \quad y - 1 \geq 0\\
& & y \geq 1\\ 
\end{align}
$$
$\therefore f$ no es suryectiva. $\blacksquare$

**Ejemplo:** $g : \mathbb{Q} \setminus \left\{-\frac{1}{2}\right\} \to \mathbb{Q} \setminus \left\{-\frac{3}{2}\right\}$ , $g(q) = \frac{2 - 3q}{1 + 2q}$. ¿Es suryectiva? 

**Solución:** Sea $y \in \mathbb{Q} \setminus \left\{-\frac{3}{2}\right\}$ , resolvamos 
$$
\begin{align}
y &= g(q)\\
y &= \frac{2 - 3q}{1 + 2q}\\
y\cdot(1 + 2q) &= 2 - 3q\\
y + 2qy &= 2 - 3q\\
2qy + 3q &= 2 + y\\
q\cdot(2y + 3) &= 2 + y\\
q &= \frac{2 - y}{2y + 3}, & \text{si } 2y + 3 & \neq 0\\
&& 2y & \neq -3\\
&& y & \neq -\frac{3}{2}\\
\end{align}
$$

$\therefore g$ si es suryectiva. $\blacksquare$


**Ej:** $h: (-\infty, \frac{2}{3}] \to \mathbb{R}$, $x \mapsto \sqrt{2 - 3x} + 1$. ¿Es suryectiva?  
**Solución:** Sea $z \in \mathbb{R}$, resolvemos:

$$
\begin{align}
z &= h(x)  \\
z &= \sqrt{2 - 3x} + 1 \\  
z - 1 &= \sqrt{2 - 3x} \qquad(*) \\
(z - 1)^2 &= 2 - 3x \\
(z - 1)^2 -2 &= - 3x \\
x &= \frac{2 - (z - 1)^2}{3}\\
\end{align}
$$

Para $z = -2$, segun lo anterior $$x = \frac{2 - (-3)^2}{3} = -\frac{7}{3}$$.

Veamos:
$$h(-\frac{7}{3}) = \sqrt{2 - 3(-\frac{7}{3})} + 1 = \sqrt{9} + 1 = 4 \neq -2$$. 

El error se debe a que en $(*)$ hay una restriccion implicita
$$
\begin{align}
z - 1 \geq 0\\
z \geq 1\\
\end{align}
$$ 
Por tanto, $h$ no es suryectiva.  $\blacksquare$

(iii) **Biyectividad.**  
Sea $f: A \to B$ una función; se dice que es **biyectiva** si es, al mismo tiempo, inyectiva y suryectiva.  

**Ejemplos:**  
$f: \mathbb{R} \to \mathbb{R}$, $x \mapsto x^2 + 1$ no es biyectiva, pues no es inyectiva ni suryectiva.  

$g : \mathbb{Q} \setminus \left\{-\frac{1}{2}\right\} \to \mathbb{Q} \setminus \left\{-\frac{3}{2}\right\}$, $q \mapsto \frac{2 - 3q}{1 + 2q}$ es biyectiva.

$h: (-\infty, \frac{2}{3}] \to \mathbb{R}$, $x \mapsto \sqrt{2 - 3x} + 1$ no es biyectiva, pues no es suryectiva.

Al igual que con las relaciones, la única operación "natural" entre funciones es la **composición**. Recordemos: Sean $R \subseteq A \times B$ y $S \subseteq B \times C$ dos relaciones, su composición es  
$$
S \circ R = \{(a, c) : (\exists b \in B) \, (a \, R \, b \land b \, S \, c)\},
$$  
y vimos que para que $S \circ R \neq \emptyset$, debe darse que $I_R \cap D_S \neq \emptyset$.  
 
Ahora, sean $f: A \to B$ y $g: B \to C$, entonces como $R_f \subseteq B = D_g$ , la composición siempre existe (el codominio de f, por lo menos debe estar incluido en el dominio de g) asi obtenemos una función:  
$$
g \circ f: A \to C, \quad \text{dada por} \quad (g \circ f)(x) = g(f(x)).
$$

**Observacion:** 
Si escribimos $(x)f$ en lugar de $f(x)$, entonces la composición de $f$ y $g$ se escribe $$(x)(f \circ g) = ((x)f)g$$. $\blacksquare$

El símbolo $g \circ f$ se lee "$g$ compuesta con $f$".  

Supongamos que $g \circ f$ y $f \circ g$ existen ambas; no siempre son iguales.  

**Ejemplo:** Sean $f, g: \mathbb{R} \to \mathbb{R}$ dadas por $f(x) = x^2$, $g(x) = \sqrt{x}$ (con dominio $x \geq 0$ para $g$). Entonces:  
$$
\begin{align}
&(g \circ f)(x) = g(f(x)) = g(x^2) = \sqrt{x^2} = |x|,\\
&(f \circ g)(x) = f(g(x)) = f(\sqrt{x}) = (\sqrt{x})^2 = x \quad \text{si} \quad(x \geq 0).\\
\end{align}
$$  
Así, $g \circ f \neq f \circ g$.  $\blacksquare$

Sin embargo, es fácil demostrar que la composición de funciones es asociativa:  
$$
h \circ (g \circ f) = (h \circ g) \circ f.
$$  
También es fácil demostrar que para $f: A \to B$ y $g: B \to C$ funciones:  
- (i) $f, g \text{ inyectivas } \implies g \circ f \text{ inyectiva}$.  
- (ii) $f, g \text{ suryectivas } \implies g \circ f \text{ suryectiva}$.  
- (iii) $f, g \text{ biyectivas } \implies g \circ f \text{ biyectiva}$.  

FALTA

Dada una función $f: A \to B$, ¿es su relación inversa $f^{-1} \subseteq B \times A$ una función?  

- Si $f$ es solo inyectiva  
  ![[Pasted image 20250531021718.png]]
$$
  A = \{a, b, c\}, \quad B = \{1, 2, 3, 4\}, \quad f(a) = 1, \, f(b) = 2, \, f(c) = 4.
  $$  
Relación inversa:
![[Pasted image 20250531022020.png]]

no es una funcion.

- Si $f$ es solo suryectiva:  
 
![[Pasted image 20250531022230.png]]


  
  

  Su relación inversa
  ![[Pasted image 20250531022653.png]]

  no es una función.  
  
- Si $f$ es biyectiva:  

![[Pasted image 20250531023043.png]]  $$
  A = \{a, b, c\}, \quad B = \{1, 2, 3\}, \quad f(a) = 3, \, f(b) = 2, \, f(c) = 1.
  $$  

 Su relación inversa: 
 ![[Pasted image 20250531023212.png]]
 es una función que es biyectiva.  

Entonces, sea $f: A \to B$ una función; decimos que $f$ es **invertible** si existe $g: B \to A$ tal que $$g \circ f = \text{1}_A \qquad \text{y} \qquad f \circ g = \text{1}_B$$. Cuando $g$ existe, es única y se llama la **inversa** de $f$, denotada por $f^{-1}$. 
Para calcular $f^{-1}$, resolvemos en $x$ la ecuación $$y = f(x)$$.  

Se debe demostrar que $f$ es invertible si y solo si es biyectiva.  

**Ejemplo:** De los tres ejemplos anteriores, solo $g: \mathbb{Q} \setminus \{-\frac{1}{2}\} \to \mathbb{Q} \setminus \{-\frac{3}{2}\}$ dada por $g(q) = \frac{2 - 3q}{1 + 2q}$ es biyectiva (al restringir dominio y codominio). 
Al chequear la suryectividad, hemos resuelto la ecuacion $$
\begin{align}
w &= g(q) \\
w &= \frac{2 - 3q}{1 + 2q} \\
(1 + 2q)\cdot w &= 2 - 3q \\
w + 2qw &= 2 - 3q \\
2qw + 3q &= 2 - w \\
q \cdot (2w + 3) &= 2 - w \\
q &= \frac{2 - w}{2w + 3}  \\
\end{align}
$$
Esta igualdad nos da la formula de la inverda:

$$g^{-1}(w) = \frac{2 - w}{2w + 3}$$

o alternativamente
$$\quad g^{-1}(q) = \frac{2 - q}{2q + 3}$$

Verificamos la composición:

$$
\begin{align}
(g \circ g^{-1})(q) &= g\left(g^{-1}(q)\right) \\  
&= g\left(\frac{2 - q}{2q + 3}\right) \\
&= \frac{2 - 3 \cdot \frac{2 - q}{2q + 3}}{1 + 2 \cdot \frac{2 - q}{2q + 3}} \\ 
&= \frac{\frac{2(2q + 3) - 3(2 - q)}{2q + 3}}{\frac{(2q + 3) + 2(2 - q)}{2q + 3}} \\ 
&= \frac{4q + 6 - 6 + 3q}{2q + 3 + 4 - 2q} \\
&= \frac{7q}{7} \\
&= q  
\end{align}
$$
$\blacksquare$

Vimos que la composicion de funciones inyectivas, suryectivas o biyectivas es, de nuevo inyectiva, suryectiva  o biyectiva. Que hay del reciproco?
Lastimosamente, no son ciertos, pero tenemos reciprocos parciales.

i) $g \circ f \; \text{ inyectiva} \implies f \text{ inyectiva}$
ii) $g \circ f \; \text{ suryectiva} \implies f \text{ suryectiva}$

**Demostracion:**

![[Pasted image 20250531105750.png]]




Sea $\gamma \in C$. Queremos hallar $b \in B$ tal que $g(b)=\gamma$. 
Por hipotesis, $g \circ f$ is suryectiva. Es decir, existe $a \in A$ tal que
$$
\gamma=(g \circ f)(a)
$$, pero esto se puede escribir:
$$
γ= (g \circ f) (a) = g(f(a))
$$
, con $f(a) \in B$. Entonces si ponemos $b=f(a)$, tenemos que $g(b)=\gamma$. $\blacksquare$

**Observacion:** Sea $f : A \to B$ una función, y $a_1,a_2 \in A$. Si $a_1 = a_2$, entonces por la definición de funcion
$$
f(a_1)=f(a_2)
$$
$\blacksquare$

Dada una función $f: X \to Y$, obtenemos dos funciones inducidas
$$
f_* : 2^X \to 2^Y \qquad f^* : 2^Y \to 2^X 
$$
dadas por

$$f_*(A) = \underbrace{f(A)=\{f(a) : a \in Α \}}_{\text{imagen de A}}$$

donde $A \in 2^X$, i.e. , $A \subseteq X$; y

$$f^*(B) = \underbrace{f^{-1}(B)=\{a \in X : f(a) \in B  \}}_{\text{preimagen de A}}$$
donde $B \in 2^Y$, i.e. , $B \subseteq Y$.

**Observacion:** Pese a la notación, $f^{-1}(B)$ no tiene nada que ver con la inversa de f, pues puede que no exista. $\blacksquare$

Como $f$ es una función, para todo $\emptyset \neq A \subseteq X$. 
$f_*(A)=f(A)=\emptyset$. Pero si $B\subseteq Y$ y $B \cap R_f=\emptyset$, entonces $f^*(B)=f^{-1}(B)=\emptyset$, pues


![[Pasted image 20250531115332.png]]


Si tomamos $y \in B$, entonces $f^* (\{y\}) = f^{-1}(\{y\})$ se escribe

$$f^{-1}(y) = \{x \in X : f(x) = y\}$$

y se llama el **levantamiento** de y.

**Ejemplo:** Sea $g: \mathbb{Z} \to \mathbb{Z^+_\circ}$ dada por $g(n) = n^2$

Sea $A = \{1, - 3, 0, 11\}$ entonces
$$g(A)=g(A)=\{1,9,0,121\}$$

Sea $B=\{0,9,3\}\subseteq \mathbb{Z^+_\circ}$, entonces $$g^*(B) = g^{-1}(B) = \{0, \pm 3\}$$ 
Sea $B_1 = \{3, 5, 7\}$, entonces $$g^{-1}(B)=\emptyset$$. $\blacksquare$

**Ejemplo:** Sea $h: \mathbb{R} \to \mathbb{R}$ dada por $h(x) = |x + 1|$
Sea $A = (-2, 3]$, entonces $h(A) = [0, 4]$

Sea $B = (-2, -1)$ , entonces $$h^{-1}(B) = \emptyset$$. 
Sea $B_o = (1, 3)$ , entonces $$h^{-1}(Bo) = (-4,2) \cup (0,2)$$
$\blacksquare$

$$
\begin{align}
1 &< h(x) < 3 \\
1 &< |x + 1| < 3 \\
1< |x + 1| \quad & \land \quad |x + 1| < 3 \\
x+1>1 \; \lor \; x+1<-1 \quad & \land \quad -3 < x + 1 < 3 \\
x>0 \; \lor \; x<-2 \quad & \land \quad -4 < x < 2 \\
\end{align}
$$

![[Pasted image 20250531122935.png]]

**Observacion:** Sean $f: A \to B$ y $f: B \to C$ funciones.


![[Pasted image 20250531124620.png]]


Es fácil demostrar que $$(g \circ f)_* = g_* \circ f_*$$

Por otro lado,

![[Pasted image 20250531125442.png]]

Es fácil demostrar que $$(g \circ f)^* = g^* \circ f^*$$
$\blacksquare$

La "imagen" tiene las siguiente propiedades
i. $A \subset B \Longrightarrow f(A) \subset f(B)$, $A, B \subset X$.  
ii. $f(A \cup B) = f(A) \cup f(B)$.  
iii. $f(A \cap B) \subset f(A) \cap f(B)$.  

**Demostración de (i):**
Sea $y \in f(A)$. Es decir, 
$$
\begin{align}
&(\exists a \in A)(f(a) = y)\\
\Rightarrow & (\exists a \in B)(f(a) = y)\\
\Rightarrow & y \in f(B)\\
\end{align}
$$
**Demostración de (2):** $f(A) \cup f(B) \subseteq f(A \cup B)$  
Sea $\alpha \in f(A) \cup f(B)$, entonces $\alpha \in f(A)$ o $\alpha \in f(B)$. Por definición de imagen:

$$(\exists a \in A)(f(a) = \alpha) \qquad \text{o} \qquad (\exists b \in B)(f(b) = \alpha)$$
Luego, $a,b \in A \cup B$ y
$$f(a) = \alpha = f(b)$$

I.e. $\alpha \in f(A \cup B) \qquad \therefore f(A)\cup f(B) \subset f(A\cup B)$

**Demostración de (3):**  
Sea $y \in f(A \cap B)$. Entonces $(\exists a \in A \cap B)(f(a) = y)$. existe $a \in A \cap B$, entonces
$$
\begin{align}
a\in A \quad &\text{y} \quad a \in B\\
f(a)\in f(A) \quad &\text{y} \quad f(a) \in f(B)\\
\end{align}
$$
Asi:
$$
y = f(a) \in f(A) \cap f(B)\\
$$

En general, no se cumple que:
$$f(A \cap B) = f(A) \cap f(B)$$  
Por ejemplo, sea $g:\mathbb{Z} \to \mathbb{N}$ dada por $g(x) = x^2$. Sean $$A = \{-2, -3, 4\} \qquad \text{y}\qquad B = \{2, 3, 4\}$$.  
en este caso,
$$
\begin{align}
f(A) = \{4, 9, 16\} &, f(B) = \{4, 9, 16, 25\}\\
f(A) \cap f(B) &= \{4, 9, 16\}
\end{align}
$$

pero
∴ $f(A \cap B) = g({4}) = {16}$.  

La "preimagen" tiene las siguientes propiedades para $f: X \to Y$ y $W,V \subseteq Y$
 
1. $f^{-1}(W \cup V) = f^{-1}(W) \cup f^{-1}(V)$  
2. $f^{-1}(W \cap V) = f^{-1}(W) \cap f^{-1}(V)$  
3. $f^{-1}(W^c) = \left[f^{-1}(W)\right]^c$  

$f^{-1}(Y \setminus W) = X \setminus f^{-1}(W)$  

**Demostración de (3):** 

Sea $x \in f^{-1}(W^c)$, entonces $f(x) \in W^c$. Esto quiere decir que  $f(x) \notin W$. Entonces $x \notin f^{-1}(W)$, y esto quiere decir que  $x \in \left[f^{-1}(W)\right]^c$.

Recíprocamente, sea $z \in \left[f^{-1}(W)\right]^c$, entonces $z \notin f^{-1}(W)$. Luego $f(z) \notin W$ y $f(z) \in W^c$. Por tanto, $z \in f^{-1}(W^c)$. $\blacksquare$ 


