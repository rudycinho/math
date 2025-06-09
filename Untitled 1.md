Para demostrar que la relación definida por $(a,b) \sim (c,d)$ si y solo si $a + d = b + c$ es una relación de equivalencia, es necesario verificar que cumple las tres propiedades: reflexividad, simetría y transitividad. Asumiremos que los pares ordenados pertenecen a un conjunto donde la suma es conmutativa y asociativa, como $\mathbb{Z} \times \mathbb{Z}$.

### 1. Reflexividad
Para cualquier par $(a,b)$, se debe cumplir que $(a,b) \sim (a,b)$.  
Esto significa que $a + b = b + a$.  
Por la conmutatividad de la suma, $a + b = b + a$ siempre es verdadero.  
Por lo tanto, la relación es reflexiva.

### 2. Simetría
Supongamos que $(a,b) \sim (c,d)$, lo que implica $a + d = b + c$.  
Debemos demostrar que $(c,d) \sim (a,b)$, es decir, $c + b = d + a$.  
Como $a + d = b + c$, y por conmutatividad $b + c = c + b$ y $a + d = d + a$, se tiene que $c + b = d + a$.  
Por lo tanto, $(c,d) \sim (a,b)$, y la relación es simétrica.

### 3. Transitividad
Supongamos que $(a,b) \sim (c,d)$ y $(c,d) \sim (e,f)$.  
Esto significa que:  
- $a + d = b + c$ (1)  
- $c + f = d + e$ (2)  

Debemos demostrar que $(a,b) \sim (e,f)$, es decir, $a + f = b + e$.  
Sumando las ecuaciones (1) y (2):  
$(a + d) + (c + f) = (b + c) + (d + e)$  
Simplificando:  
$a + d + c + f = b + c + d + e$  
Restando $c + d$ a ambos lados:  
$a + f = b + e$  
Por lo tanto, $(a,b) \sim (e,f)$, y la relación es transitiva.

### Conclusión
La relación $\sim$ definida por $(a,b) \sim (c,d) \iff a + d = b + c$ es reflexiva, simétrica y transitiva, por lo que es una relación de equivalencia.