Se considera la relación $R \subseteq \mathbb{Z}^2$ definida por 
$$(x, y) \in R \iff x - y \in \mathbb{Z}$$  
1. Reflexividad
$$a \in R \Rightarrow a - a = 0 \in \mathbb{Z} \Rightarrow (a , a) \in R$$
2. Simetría
$$(a,b) \in R \Rightarrow a - b \in \mathbb{Z} \Rightarrow b - a  \in \mathbb{Z} \Rightarrow  (b ,a) \in R$$
Si un número es entero, su opuesto también lo es.

3. Transitividad
$$
\begin{align}
(a,b) \in R \wedge (b,c) \in R & \Rightarrow a - b \in \mathbb{Z} \wedge b - c \in \mathbb{Z} \\
& \Rightarrow (a - b)+(b - c ) \in \mathbb{Z} \\
& \Rightarrow a - c \in \mathbb{Z} \\
& \Rightarrow (a,c) \in R \\
\end{align}
$$

4. R no es antisimétrica, pues
$$(3,2)\in R \wedge (2,3)\in R \Rightarrow 2 = 3 \text{ es F}$$


**Gráfico de $R$**: 
A $R$ pertenecen los pares de reales $(x,y)$ tales que $x-y \in \mathbb{Z}$
Ahora bien
$$
\begin{align}
x-y \in \mathbb{Z} &\Rightarrow x - y = k \;/ \;k \in Z\\
&\Rightarrow y = x - k \text{ con } k\in Z
\end{align}
$$
Para cada entero k, se tiene una recta paralela a la primera bisectriz.
La relación consiste en todos los pares $(x,y)\in R^2$ pertenecientes a la familia de rectas paralelas a $y = x$:  
$$R = \bigcup_{k \in \mathbb{Z}} \{(x, y) \in \mathbb{R}^2 \mid y = x - k\}$$  





