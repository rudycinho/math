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
