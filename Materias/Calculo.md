# Cap O Preliminares

$\frac{a}{b} = \sqrt{2}$
$\mathcal{p} \wedge \neg{p}$
$p_1 \rightarrow p_2 \rightarrow p_3$

## Proposición


$\sqrt{2}$ es irracional (no es racional).
Supongamos que $\sqrt{2}$ es racional, entonces $\sqrt{2} = \frac{b}{a}$ , $a$ y $b$ no tienen factores comunes, $b \in \mathbb Z$ y $a \in \mathbb N$. Luego $2 = \frac{b^2}{a^2}$, de donde $b^2 = 2a^2$ y así $b^2$ es par. Entonces $b$ es par luego $b=2k$. Sustituyendo $(2k)^2 = 2a^2$, luego $4k^2 = 2a^2$ y así $a^2=2k^2$, luego $a^2$ es par y así $a$ por contradicción.

$p \rightarrow q \equiv \neg q \rightarrow \neg p$


$$
\begin{aligned}
p &\rightarrow q\\
\text{Si } \underbrace{b^2 \text{ es par}}_{\text{hipotesis}} &\text{, entonces } \underbrace{b \text{ es par}}_{\text{tesis}}.
\end{aligned}
$$

$$
\begin{aligned}
\neg q &\rightarrow \neg p\\
\text{Si } b \text{ es impar} &\text{, entonces } b^2 \text{ es impar}.
\end{aligned}
$$

$$
	b^2=2\cdot k
$$

Demostración.
Si $b$ es impar, entonces $b=2k+1, k \in Z$. Elevando al cuadrado $b^2=(2k+1)^2 = 4k^2 + 4k + 1 = 2(2k^2 + 2k) + 1$ que es impar.



# Cap 1. El conjunto de los números reales $\mathbb R$

Denotaremos por $\mathbb R$ el conjunto de los números reales y consideramos en $\mathbb R$ dos operaciones, la suma y el producto. Veamos la suma:
Dados $a$ y $b$, la suma será denotada por $a + b$:
 
P1. Si $a$ $b$ y $c$ son números reales ($a,\, b,\, c \in \mathbb R$)
$$
	(a + b) + c = a + (b + c)
$$
P2. Existe un número, llamado cero y denotado como $0$ ($\exists! \, 0 \in \mathbb R$), tal que  
$$
	a + 0 = 0 + a = a , \text{ para todo } \;a\; \text{ real } (\forall a \in \mathbb R) 
$$
P3. Para cada número $a$, existe un número $-a$ tal que:

$$
a + (-a) = (-a) + a = 0 \quad \forall a \in R.
$$

P4. Si $a$ y $b$ son reales, entonces

$$
a + b = b + a$$

P5. Para todo $a, b, c$ :

$$
(a\cdot b)\cdot c = a\cdot (b\cdot c)
$$

P6. Existe un número, la unidad, denotada como $1$, con $1\neq0$, tal que
$$
	a\cdot 1=1\cdot a=a
$$
P7. Para todo $a \neq 0$, existe $a^{-1}$ tal que

$$
a \cdot a^{-1} = a^{-1} \cdot a = 1
$$

P8. Para todo $a, b$ reales:

$$
a \cdot b = b \cdot a 
$$

P9 Para todo $a, b, c$ reales

$$
a\cdot(b + c) = a\cdot b + a\cdot c
$$


---

# Números Reales

$\mathbb R$ (Axiomática).

Constructiva
$$
	\mathbb N \rightarrow \mathbb Z \rightarrow \mathbb Q \rightarrow \mathbb R  
$$

P1. $a+(b+c)=(a+b)+c$
P2. $a + 0 = 0 + a = a$
P3. $a + (- a) = (- a) + a = 0$
P4. $a+b = b+a$
P5. $a\cdot (b\cdot c)=(a\cdot b) \cdot c$
P6. $a \cdot 1 = 1 \cdot a = a \qquad 1 \neq 0$
P7. $a\cdot a^{-1} = a^{-1} \cdot a = 1 \qquad a\neq 0$
P8. $a\cdot b=b\cdot a$
P9. $a \cdot (b+c)=a\cdot b + a\cdot c$


$(-a) \cdot b = - (a\cdot b)$
$(-a) \cdot (-b) = a\cdot b$
$-(-a)=a$

## Orden

$x < y$ "x es menor que y"
$y > x$ "y es mayor que x"
$0 < y$ "y es positivo"

P1O. Existe un conjunto $\mathbb P$ de números tal que para todo $a$ real se cumple una y sola una de las siguientes condiciones:

$$
	\left.
	\begin{array}{rl}
		i  &  \; a \in \mathbb P \qquad \text{es positivo}\\
		ii &  \; a = 0  \qquad a=0\\
		iii& \; -a \in \mathbb P \quad \text{es negativo}
	\end{array}
	\right\} \text{Tricotomia}
$$


P11. Si $a,b$ están en $\mathbb P$, entonces $a+b$ está en $\mathbb P$

P12. Si $a,b$ están en $\mathbb P$, entonces $a\cdot b$ está en $\mathbb P$

**Notación**. $\mathbb P$ se denomina los números positivos $a \in \mathbb P$ "a es positivo".

Definicion
$$
\begin{align}
	a<b , &\text{ si } b-a \text{ es positivo } (b-a \in \mathbb P)\\
	b>a , &\text{ si } a<b \\
	a \leq b , &\text{ si } a<b \text{ o } a=b\\
	b \geq a , &\text{ si } a \leq b\\
\end{align}
$$

P10'. Para todo $a,b$ real, se verifica una y solo una de lu siguientes conclusiones

$$
\begin{align}
i.  &\; a < b\\
ii. &\; a = b\\
iii.&\; b < a
\end{align}
$$



$$
\begin{aligned}
x &= b - a \quad
\left\{
\begin{array}{ll}
x \in \mathbb{P} & \quad b - a \in \mathbb{P} &\quad  a < b \\
x = 0 & \quad b - a = 0 &\quad a = b \\
-x \in \mathbb{P} & \quad -(b - a) \in \mathbb{P} \quad a - b \in \mathbb{P} &\quad  b < a
\end{array}
\right.
\end{aligned}
$$



Definicion. $a$ es negativo, si $-a$ es positivo.
Consecuencias
Si $a$ es positivo y $b$ es negativo, entonces $ab$ es negativo.

1) acb

)a-6

1) 0 < a

x-b-a

X-0 b - a = 0 a>b

-XEP-16-aJEP

a-bep bra

VV

Del a is negativo, is a spositivo -(-3)-3

Comstonencias

Si a m positivo y bo on negativo, entomas ab oo negativo Dem GEP, -bep a (6) P --(ab) EP → ab co negativo

Si a y b som negativos, entonces ab co positivo

-acp, -bep (-)(-6) P → ab mpu (gur) (upugler= J^((binada) bandarba =(png) r

1. a es real, entencen a 30 P Si aureal P y (2 あん V a≠0, en traces a>0

Dem Como a 40, por la PD, au positivo

140

1-120

2 = j + 1 > 0

240

a-b-b-aa-b/Siab-ac yato, intrucs b-c

ara-b+b 4a + 1a = 1b + 1b (1 + 1) * a = (1 + 1) * b

ab=ac

integrate a ^ - 1 da

(a'ab (aa)

16-16

↓

a-b

46-6-467 (b+c)-(arc) ep

(b+c)-a-cEP --

(b+c)-(a+c)CP ba

Si pa impar, enhmer po armpar p ^ 2 = 2k + 1 - p ^ 2 - 1 = 2k - (p - 1) * (p + 1) = 2p ^ p

wind & and on inde spor mpar

PP

0 < 1 -> 0 + 1 < 1 + 1

---

P1-P4 PS-P9 P10-P12

bima

producto

orden

a-bb-ab=a

1+1)a=( (1 + 1) * b -ac gato b-c ↓

↓ Delta = 0

Def (Valor absoluto) (xl-d(0) (x)=dlox) = x

-2<-1<0<1<2<3< |x|= x,& Leftrightarrow& x > 0 \\ -x,&in&x<0

(:

1x/max-x,x}

11 (120) Entonces - x <= 0 <= x 2 (x0) Entonces x < 0 < - x max-xx-x=(x)

|x| = 0 , forall x in02

(ww)

x < 0

x > 0 * x > 0; x > 0

((a + b) ^ 2) / ((|a| + |b|) ^ 2)

|a| ^ 2 + 2|a||b| + |b| ^ 2

Desigualdad trangular |a + b| <= |a| + |b| forall a ,b in m

( p vee q) r (p -> r)(q -> r) ((430x600) 40x630) t(a < \mathfrak{o}*\mathfrak{b} < 0) - |a + b| <= la|16|

alpha >= 0 * 0 > 0 = |alpha + k| <=|a|+|b||

n) a > a + b < 0 -> |a + b| <= |a| + |b|

R < 0 + c >=0 longrightarrow|a+b|<=|a|+lb|

a < 0 <= 0 <= 0 <= 0 <= |a + k| <= |a| + |b|

|a_{i} + b_{i}| <= |a_{i}| + |b_{i}| a+b=a+ |a + b| <= |a| + |b|

a/b - b

( matrix sin theta x^ 2 + t^ 2 x^ 2 + sin theta (sin theta)/(sin theta); (sin theta)/(sin theta) \\ sin theta sin theta matrix la ([a] 030 |a| ^ 2 = |a||a| = a|a| = a|a| = a ^ 2 log(pi/2) - (a)\{a\} =(-a\ (-a\ =a* a=a^ 2

aligned a ^ 2 <= b ^ 2 -> 0 <= b ^ 2 - a ^ 2 = (b - a)(b + a) +0 aligned

- b - a >= 0 -> a <= b

- (a + k = 0)

|a + b| <= |a| + |b| a + b <= b <= b_{1} - b_{2}

b <= - b

underline x < y < z -> x < z

x < y < 2

J(2b) )

7210-33

23 13 164 13

(10-6) 10+27-210+) b<o<-b longrightarrow b<-b longrightarrow a + b < a + b < a + b ) longrightarrow|a+b|<|a|+1b|

- (a + b < 0)

|phi_{c} + 1/alpha| <=| phi|+| dot f 0 || - (a + b) * a - b - a - b <= 2 - b

- a < <= G -a-bs0-6 |a + b| <= |a| + |b|

-asa

|a + b| ^ 2 = (a + b) ^ 2 = a ^ 2 + 2ab + b ^ 2 =|a|^ 2 +2ab+1b|^ 2 <=|a|^ 2 +2|ab|+|b|^ 2

C

abslabl

lab=alb

lal<b - 1/b < a < b

= (1al + 1bl) ^ 2

= |a| ^ 2 + 2|a||b| + |b| ^ 2

larb/s/al+16/

|omega| > 6 -bu be a

(一)

3

(a10) 10/26 acb-brocacb-beach

(aco) a|<b -a<b longrightarrow - b < a < 0 <= b Rightarrow-b<a<b



\\(←)

(aro) babasbjukb

(20) -baacbbaacb6

(946 ((acb) vach) n(bcc)

), (6cc)

(lach)a(bcc))v(a-b) a bac) → (acc)v(acc) - acc


---
