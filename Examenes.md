### Preguntas de Examen

#### Lógica
1. Simbolice la siguiente inferencia y demuéstrela: "Si $x=a$ e $y=b$, entonces $z=c$. Si, si $y=b, z=c$, entonces $w=k . x=a$. Por consiguiente, $w=k$."
2. Se sabe que $(r \rightarrow q)$ es verdadera, $(n \wedge r)$ es falsa, $(m \vee n)$ es verdadera, y que $(p \vee m)$ es falsa. Determinar (sin hacer la tabla de verdad) el valor de verdad de: $[(m \vee \neg n) \rightarrow(p \wedge \neg r)] \leftrightarrow(m \wedge q)$.
3. Simbolice la siguiente inferencia y demuéstrela: "Si $x=a$ e $y=b$, entonces $z=c$. Si, si $y=b, z=c$, entonces $w=k . x=a$. Por consiguiente, $w=k$."
4. Se sabe que $(r \rightarrow q)$ es verdadera, $(n \wedge r)$ es falsa, $(m \vee n)$ es verdadera, y que $(p \vee m)$ es falsa. Determinar (sin hacer la tabla de verdad) el valor de verdad de: $[(m \vee \neg n) \rightarrow(p \wedge \neg r)] \leftrightarrow(m \wedge q)$.
5. Definimos el símbolo $\lim _{x \rightarrow a} f(x)=f(a)$ por $(\forall \varepsilon>0)(\exists \delta>0)(\forall x)(0 \leq|x-a|<\delta \Rightarrow|f(x)-f(a)|<\varepsilon)$. Escriba la negación de esta definición.

#### Teoría de Conjuntos
1. Demuestre que $(A \times B) \backslash(C \times D)=[(A \backslash C) \times B] \cup[A \times(B \backslash D)]$.
2. Considere la familia de conjuntos $\left\{Z_j\right\}_{j \in \mathbb{N}}$, donde $Z_j=(-\infty, j] \cup[j, \infty)$. Calcule $\left(\bigcap_{j \in \mathbb{N}} Z_j\right)^c$.
3. Simplifique lo siguiente: $\left\{\left[(A \cup B) \cap(B \backslash C)^c\right] \cup\left[C \backslash\left(A^c \cap B\right)\right]^c\right\} \backslash(C \backslash B)$.
4. Demuestre que $(A \times B) \backslash(C \times D)=[(A \backslash C) \times B] \cup[A \times(B \backslash D)]$.
5. Simplifique lo siguiente: $\left\{\left[(A \cup B) \cap(B \backslash C)^c\right] \cup\left[C \backslash\left(A^c \cap B\right)\right]^c\right\} \backslash(C \backslash B)$.

#### Funciones
1. Sea $f: X \rightarrow Y$ una función. Demuestre que:
	- Si $B \subset Y$, entonces $f\left(f^{-1}(B)\right) \subset B$. 
	- Si $f$ es suryectiva, entonces $f\left(f^{-1}(B)\right)=B$ para todo $B \subset Y$.
2. Sean $X$ e $Y$ conjuntos no vacíos, y sea $f: X \rightarrow Y$ una función. Definimos en $X$ la relación $x \sim y \Leftrightarrow f(x)=f(y)$. 
	- Demuestre que esta relación es de equivalencia. ¿A qué es igual $[x]$, la clase de equivalencia de $x$? 
	- Definimos la aplicación $\bar{f}: X / \sim \rightarrow Y$ por $\bar{f}([x])=f(x)$. ¿Es $\bar{f}$ inyectiva? (Justifique su respuesta).
3. Sea $f: A \rightarrow B$ una función inyectiva. Demuestre que existe $g: B \rightarrow A$ tal que $g \circ f=\operatorname{id}_A$.
4. Sea $g: X \rightarrow Y$ una función y sea $B \subseteq Y$. Demuestre que $g^*(Y \backslash B)=X \backslash g^*(B)$.
5. Sea $f: X \rightarrow Y$ una función. Demuestre que: 
	- Si $A \subset X$, entonces $A \subset f^{-1}[f(A)]$. 
	- Si $f$ es inyectiva, entonces $f^{-1}[f(A)]=A$ para todo $A \subset X$.

#### Relaciones de Equivalencia
1. Sean $X$ e $Y$ conjuntos no vacíos, y sea $f: X \rightarrow Y$ una función. Definimos en $X$ la relación $x \sim y \Leftrightarrow f(x)=f(y)$. 
	- Demuestre que esta relación es de equivalencia. 
	- Definimos la aplicación $\tilde{f}: X / \sim \rightarrow Y$ por $\tilde{f}([x])=f(x)$. Demuestre que $\tilde{f}$ es inyectiva.
2. En $\mathbb{N}^2$ definimos la relación $(a, b) \sim(c, d) \Leftrightarrow a+d=b+c$. 
	-  Demuestre que $\sim$ es una relación de equivalencia.
	- Calcule las clases de equivalencia $[(1,2)],[(2,1)]$ y $[(1,1)]$, y haga un gráfico en el plano $\mathbb{N}^2$.
	- Si en $\mathbb{N}^2 / \sim$ definimos la adición $[(a, b)]+[(c, d)]=[(a+c, b+d)]$. 
		- Calcule $[(2,1)]+[(1,1)]$. ¿Qué le dice esto sobre la clase $[(1,1)]$ para esta adición? 
		- Calcule $[(2,1)]+[(1,2)]$. ¿Qué le dice esto sobre la clase $[(1,2)]$ respecto de la clase $[(2,1)]$ para esta adición?

#### Órdenes Parciales
1. Sea $X=\{a, b, c\}$. En el conjunto $2^X$ definimos la relación de orden $A \preceq B \Leftrightarrow A \subseteq B$. Dibuje el diagrama de Hasse de este orden. Si existen, identifique los siguientes elementos: 
	- $\max 2^X$ y $\min 2^X$. 
	- $\operatorname{Para} Z=\{\{a, b\},\{c\}\}, \inf Z$ y sup $Z$.
2. Sean $R \subset A^2$ y $S \subset B^2$ dos relaciones de orden. Sobre $A \times B$ definimos la relación $\left(a_1, b_1\right) \ll\left(a_2, b_2\right) \Leftrightarrow a_1 R a_2 \wedge b_1 S b_2$. Demuestre que $\ll$ es una relación de orden.
3. Sea $X=\{x, y, z\}$. En el conjunto $\mathcal{W}=2^X \backslash\{X\}$ definimos la relación de orden $A \preceq B \Leftrightarrow A \supseteq B$. 
	- Dibuje el diagrama de Hasse de este orden. 
	- ¿Cuáles son los elementos minimales y maximales de $\mathcal{W}$?

#### Números Complejos
1. Dé una descripción geométrica del siguiente subconjunto de $\mathbb{C}$: $\left\{z: z^2-\bar{z}^2=i\right\}$. Bosqueje un gráfico del conjunto (en $\mathbb{R}^2$).
2. Exprese en la forma $x+i y$: 
	- $\log (1-i \sqrt{3})$. 
	- $i^{\log i}$.
3. Sean $z, w \in \mathbb{C}$. Demuestre la ley del paralelogramo: $|z+w|^2+|z-w|^2=2\left(|z|^2+|w|^2\right)$.

#### Inducción Matemática
1. Demostrar la desigualdad de Bernoulli: para todo $c \in \mathbb{R}$ y $n \in \mathbb{N}$, $(1+c)^n \geq 1+n c$.
2. Demostrar que, para todo $a \in \mathbb{R}$ y todo $n \in \mathbb{N}$, $\frac{1}{a(a+1)}+\frac{1}{(a+1)(a+2)}+\cdots+\frac{1}{(a+n-1)(a+n)}=\frac{n}{a(a+n)}$.


#### Combinatoria
1. Calcular el valor de $\binom{n}{0}+2\binom{n}{1}+2^2\binom{n}{2}+\cdots+2^k\binom{n}{k}+\cdots+2^n\binom{n}{n}$.

#### Teoría de Números
1. Demostrar que si $c \mid a$ y $(a, b)=1$, entonces $(b, c)=1$.
2. En la axiomátización de Peano de los números naturales, demuestre que, para todo $m, n, p \in \mathbb{N}$, $m \cdot(n+p)=m \cdot n+m \cdot p$.
