### Ejemplo 3-11: Congruencia módulo $n$ en $\mathbb{Z}$  
**Definición**:  
Dos enteros $a$ y $b$ son **congruentes módulo $n$** si $n$ divide a $a - b$:  
$$
a \equiv b \pmod{n} \ \Leftrightarrow \ n \mid (a - b)  
$$  

**Propiedades**:  
1. **Reflexiva**: $a \equiv a \pmod{n}$ (pues $n \mid 0$).  
2. **Simétrica**: $a \equiv b \pmod{n} \Rightarrow b \equiv a \pmod{n}$.  
3. **Transitiva**: $a \equiv b \pmod{n} \land b \equiv c \pmod{n} \Rightarrow a \equiv c \pmod{n}$.  

**Clases de equivalencia**:  
Para $a \in \mathbb{Z}$,  
$$
K_a = \{x \in \mathbb{Z} \mid x \equiv a \pmod{n}\} = \{a + kn \mid k \in \mathbb{Z}\}  
$$  

**Conjunto cociente**:  
$$
\mathbb{Z}/n\mathbb{Z} = \{\overline{0}, \overline{1}, \dots, \overline{n-1}\}  
$$  
donde $\overline{k} = \{k + mn \mid m \in \mathbb{Z}\}$.  

**Ejemplo para $n = 3$**:  
$$
\mathbb{Z}/3\mathbb{Z} = \{\overline{0}, \overline{1}, \overline{2}\}  
$$  
- $\overline{0} = \{\dots, -6, -3, 0, 3, 6, \dots\}$  
- $\overline{1} = \{\dots, -5, -2, 1, 4, 7, \dots\}$  
- $\overline{2} = \{\dots, -4, -1, 2, 5, 8, \dots\}$  

**Representación cartesiana**:  
La relación $R = \{(x, y) \in \mathbb{Z}^2 \mid x \equiv y \pmod{3}\}$ corresponde a las rectas:  
$$
y = x - 3k \quad \text{para } k \in \mathbb{Z}  
$$  
```
    y
    |   ● (x, x-3k)
    |  /
    | /
    |/ 
    +-----------x
```  

**Relación como unión**:  
$$
R = \bigcup_{k \in \mathbb{Z}} \{(x, y) \in \mathbb{Z}^2 \mid y = x - 3k\}  
$$  

