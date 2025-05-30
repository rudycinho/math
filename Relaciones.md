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
**B. Relaciones de equivalencia**  
En $\mathbb{R}$ definimos $x \sim y \Leftrightarrow x^2 = y^2$. ¿Es $\sim$ una relación de equivalencia?  
- **(i) Reflexividad**: ($\forall x \in \mathbb{R}$) ($x \sim x$). Para todo $x \in \mathbb{R}$, es obvio que $x^2 = x^2$; luego $x \sim x$.  
- **(ii) Simetría**: ($\forall x, y \in \mathbb{R}$) ($x \sim y \Rightarrow y \sim x$). Por simetría de la igualdad, $x^2 = y^2$ implica $y^2 = x^2$; luego $y \sim x$.  
- **(iii) Transitividad**: ($\forall x, y, z \in \mathbb{R}$) ($x \sim y \land y \sim z \Rightarrow x \sim z$). Sean $x, y, z \in \mathbb{R}$ tales que $x \sim y$ y $y \sim z$. Entonces $x^2 = y^2$ y $y^2 = z^2$, de donde $x^2 = z^2$; luego $x \sim z$.  
Por tanto, $\sim$ es relación de equivalencia.  

**Otro ejemplo:**  
En $\mathbb{R}$ definimos $x \mathbin{\Delta} y \Leftrightarrow (\exists c \in \mathbb{R})(y = x + c)$. ¿Es $\Delta$ relación de equivalencia?  
- **(i) Reflexividad**: ($\forall x \in \mathbb{R}$) ($x \mathbin{\Delta} x$). Como $x = x + 0$ con $0 \in \mathbb{R}$, entonces $x \mathbin{\Delta} x$.  
- **(ii) Simetría**: ($\forall x, y \in \mathbb{R}$) ($x \mathbin{\Delta} y \Rightarrow y \mathbin{\Delta} x$). Sean $x, y \in \mathbb{R}$ tales que $x \mathbin{\Delta} y$. Existe $c \in \mathbb{R}$ con $y = x + c$. Entonces $x = y + (-c)$ con $-c \in \mathbb{R}$; luego $y \mathbin{\Delta} x$.  
- **(iii) Transitividad**: ($\forall x, y, z \in \mathbb{R}$) ($x \mathbin{\Delta} y \land y \mathbin{\Delta} z \Rightarrow x \mathbin{\Delta} z$). Sean $x, y, z \in \mathbb{R}$ tales que $x \mathbin{\Delta} y$ e $y \mathbin{\Delta} z$. Existen $c, d \in \mathbb{R}$ con $y = x + c$ y $z = y + d$. Sustituyendo, $z = (x + c) + d = x + (c + d)$ con $c + d \in \mathbb{R}$; luego $x \mathbin{\Delta} z$.  
Por tanto, $\Delta$ es relación de equivalencia.  

**Clases de equivalencia y particiones**  
Las relaciones de equivalencia particionan el conjunto donde están definidas en "partes" llamadas **clases de equivalencia**.  
Sea $R \subseteq A \times A$ una relación de equivalencia y $a \in A$. La clase de equivalencia de $a$ es:  
$$
[a] = \{x \in A : x \mathbin{R} a\}.
$$  
Por reflexividad, para todo $a \in A$, $[a] \neq \emptyset$ (pues $a \in [a]$).  
- Si $a \mathbin{R} b$, entonces $[a] = [b]$.  
- Si $\neg(a \mathbin{R} b)$, entonces $[a] \cap [b] = \emptyset$.  
- Además, $\bigcup_{a \in A} [a] = A$.  

La colección de todas las clases de equivalencia forma el **conjunto cociente** de $A$ por $R$, denotado $A/R$.  

**Ejemplo:**  
Para $\sim$ en $\mathbb{R}$ ($x \sim y \Leftrightarrow x^2 = y^2$):  
$$
[x] = \{y \in \mathbb{R} : y^2 = x^2\} = \{x, -x\}.
$$  
Gráficamente: $[0] = \{0\}$, $[-2] = \{-2, 2\} = [2]$, $[3] = \{-3, 3\}$.  
Luego, $\mathbb{R}/{\sim} = \{\{x, -x\} : x \in \mathbb{R}\}$.  

**Ejemplo en $\mathbb{R}^2$:**  
Sea $L$ el conjunto de todas las rectas en $\mathbb{R}^2$. En $L$ definimos:  
$$
\ell_1 \parallel \ell_2 \Leftrightarrow \text{$\ell_1$ y $\ell_2$ son paralelas}.
$$  
Es evidente que $\parallel$ es relación de equivalencia.  
- Para la recta $\ell: y - 2 = \frac{2}{3}(x - 1)$ (i.e., $y = \frac{2}{3}x + \frac{4}{3}$), su clase es:  
  $$
  [\ell] = \{m \in L : m \parallel \ell\} = \left\{ \text{rectas con pendiente } \frac{2}{3} \right\} = \left\{ y = \frac{2}{3}x + b : b \in \mathbb{R} \right\}.
  $$  
- El conjunto cociente es:  
  $$
  L/{\parallel} = \left\{ \left\{ y = mx + b : b \in \mathbb{R} \right\} : m \in \mathbb{R} \right\} \quad (\text{conjunto de todas las direcciones}).
  $$  

**Congruencia módulo $n$:**  
En $\mathbb{Z}$ definimos para $n \in \mathbb{N}$:  
$$
a \equiv b \pmod{n} \Leftrightarrow (\exists c \in \mathbb{Z})(a - b = c \cdot n).
$$  
Esta es una relación de equivalencia:  
- **(i) Reflexividad**: $a - a = 0 = 0 \cdot n$, luego $a \equiv a \pmod{n}$.  
- **(ii) Simetría**: Si $a \equiv b \pmod{n}$, existe $c \in \mathbb{Z}$ con $a - b = c \cdot n$. Entonces $b - a = (-c) \cdot n$, con $-c \in \mathbb{Z}$; luego $b \equiv a \pmod{n}$.  
- **(iii) Transitividad**: Si $a \equiv b \pmod{n}$ y $b \equiv c \pmod{n}$, existen $c_1, c_2 \in \mathbb{Z}$ con $a - b = c_1 n$ y $b - c = c_2 n$. Sumando: $a - c = (c_1 + c_2)n$, luego $a \equiv c \pmod{n}$.  

**Ejemplo:** Sea $n = 5$. La clase de $7$ es:  
$$
[7] = \{x \in \mathbb{Z} : x \equiv 7 \pmod{5}\} = \{x \in \mathbb{Z} : x - 7 = 5k, k \in \mathbb{Z}\} = \{\ldots, -3, 2, 7, 12, \ldots\}.
$$  
El conjunto cociente es $\mathbb{Z}/5\mathbb{Z} = \{[0], [1], [2], [3], [4]\}$.  

**Teorema fundamental:**  
Sea $A \neq \emptyset$ y $R \subseteq A \times A$ una relación de equivalencia. Entonces $A/R$ es una partición de $A$. Recíprocamente, si $\{A_i\}_{i \in I}$ es una partición de $A$, podemos definir una relación de equivalencia:  
$$
x \mathbin{R} y \Leftrightarrow (\exists i \in I)(x \in A_i \land y \in A_i).
$$  

**C. Relaciones de orden**  
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

**Ejemplo:** En $\mathbb{R}$ definimos:  
$$
a < b \Leftrightarrow (\exists c > 0)(b = a + c).
$$  
Esto define un orden estricto.  

**Elementos especiales en conjuntos ordenados:**  
Sea $(A, \preccurlyeq)$ un conjunto parcialmente ordenado y $B \subseteq A$.  
- **Mínimo**: $b \in B$ es mínimo de $B$ si $\forall c \in B$, $b \preccurlyeq c$. Se denota $b = \min B$.  
- **Máximo**: $k \in B$ es máximo de $B$ si $\forall c \in B$, $c \preccurlyeq k$. Se denota $k = \max B$.  
- **Cotas inferiores**: $a \in A$ es cota inferior de $B$ si $\forall x \in B$, $a \preccurlyeq x$. El conjunto de cotas inferiores se denota $B_-$.  
- **Cotas superiores**: $b \in A$ es cota superior de $B$ si $\forall x \in B$, $x \preccurlyeq b$. El conjunto de cotas superiores se denota $B^+$.  
- **Ínfimo**: $a \in A$ es ínfimo de $B$ si es el máximo de $B_-$. Se denota $a = \inf B$.  
- **Supremo**: $b \in A$ es supremo de $B$ si es el mínimo de $B^+$. Se denota $b = \sup B$.  
- **Elemento minimal**: $b \in B$ es minimal si $\neg(\exists x \in B)(x \preccurlyeq b \land x \neq b)$.  
- **Elemento maximal**: $d \in B$ es maximal si $\neg(\exists x \in B)(d \preccurlyeq x \land x \neq d)$.  

**Ejemplo:** En $\mathbb{R}$ con el orden usual:  
- $A = (1, 2)$: $\min A$ no existe, $\max A$ no existe.  
- $B = [1, 2)$: $\min B = 1$, $\max B$ no existe.  
- $C = [1, 2]$: $\min C = 1$, $\max C = 2$.  

**Diagramas de Hasse:**  
Para conjuntos finitos parcialmente ordenados, se usan diagramas de Hasse:  
1. Elementos se dibujan en el plano: si $a \preccurlyeq b$, $a$ va debajo de $b$ y se conectan con un segmento.  
2. Las conexiones implican transitividad (no se dibujan todas las relaciones).  
3. No se dibujan bucles (autoconexiones).  

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