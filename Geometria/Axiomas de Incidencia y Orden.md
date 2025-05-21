Las figuras geométricas en el plano son los puntos y las rectas.  
El plano está compuesto de puntos, y las rectas son subconjuntos distintos de puntos del plano.  

**Axioma $I_1$**  
Cualquiera que sea la recta, existen puntos que pertenecen a ella y puntos que no le pertenecen.  

---

**Axioma $I_2$**  
Dados dos puntos distintos, existe una única recta que los contiene.  

---

Cuando dos rectas tienen un punto en común, se dice que **se intersecan** o que **se cortan** en dicho punto.  

**Proposición $1.1$**  
Dos rectas distintas no se intersecan o lo hacen en un solo punto.  

**Demostración**:  
1. Sean $m$ y $n$ dos rectas distintas.  
2. Si su intersección tuviera dos o más puntos, por el **Axioma $I_2$**, $m$ y $n$ coincidirían (contradicción).  
3. Luego, $m \cap n$ contiene a lo sumo un punto.  


Utilizaremos letras mayúsculas $A$, $B$, $C$, ... para designar *puntos*,  
y letras minúsculas $a$, $b$, $c$, ... para designar *rectas*.  

---

La noción de que un punto se encuentra entre otros dos es una relación, entre puntos de una misma recta, que satisface los axiomas de orden.  

**Axioma $II_1$**  
Dados tres puntos distintos en una recta, uno y solo uno se encuentra entre los otros dos.  
*Axioma de ordenación en una recta*.

---

**Definición $1.2$**  
El conjunto formado por dos puntos $A$, $B$ y por todos los puntos entre ellos se denomina **segmento $AB$**. Los puntos $A$ y $B$ se denominan **extremos** del segmento.  

Muchas figuras planas se forman usando segmentos.  

---

**Triángulo**:  
Figura plana formada por tres puntos que no pertenecen a la misma recta y los segmentos que los unen. Los segmentos se denominan **lados**, y los puntos son **vértices**.  

---

**Definición $1.3$**  
Sean $A$ y $B$ dos puntos distintos. El conjunto formado por los puntos del segmento $AB$ y todos los $C$ tales que $B$ se encuentra entre $A$ y $C$ es la **semirrecta** de origen $A$ que contiene al punto $B$, representada por $S_{AB}$. El punto $A$ es el **origen** de la semirrecta $S_{AB}$.  

Dos puntos $A$ y $B$ determinan dos semirrectas $S_{AB}$ y $S_{BA}$, las cuales contienen al segmento $AB$.  

---

**Proposición $1.4$**  
Para las semirrectas determinadas por dos puntos $A$ y $B$, se tiene que:  
a) $S_{AB} \cup S_{BA}$ es la recta determinada por $A$ y $B$.  
b) $S_{AB} \cap S_{BA} = AB$.  

**Demostración**  

**a) $S_{AB} \cup S_{BA} = m$**  
**Demostración:**  
Sea $m$ la recta determinada por $A$ y $B$.  

1. **Contención ($S_{AB} \cup S_{BA} \subseteq m$):**  
   - Por definición, $S_{AB}$ y $S_{BA}$ son subconjuntos de $m$.  
   - Por tanto, su unión también está contenida en $m$:  
     $$ S_{AB} \cup S_{BA} \subseteq m. $$

2. **Contención ($m \subseteq S_{AB} \cup S_{BA}$):**  
   Sea $C \in m$. Por el **Axioma de ordenación en una recta $II_1$**, una de las siguientes posibilidades ocurre:  
   - **Caso 1:** $C$ está **entre $A$ y $B$**.  
     - Entonces $C \in AB \subseteq S_{AB}$ y $C \in S_{BA}$, por lo que $C \in S_{AB} \cup S_{BA}$.  
   - **Caso 2:** $A$ está **entre $B$ y $C$**.  
     - Esto implica que $C$ está en la semirrecta $S_{BA}$ (dirección $B \to A$ extendida).  
     - Por tanto, $C \in S_{BA} \subseteq S_{AB} \cup S_{BA}$.  
   - **Caso 3:** $B$ está **entre $A$ y $C$**.  
     - Esto implica que $C$ está en la semirrecta $S_{AB}$ (dirección $A \to B$ extendida).  
     - Por tanto, $C \in S_{AB} \subseteq S_{AB} \cup S_{BA}$.  

   En todos los casos, $C \in S_{AB} \cup S_{BA}$. Por lo tanto:  
   $$ m \subseteq S_{AB} \cup S_{BA}. $$  
3. **Conclusión:**  
   $$ S_{AB} \cup S_{BA} = m. $$

**b) $S_{AB} \cap S_{BA} = AB$**  
**Demostración:**  

1. **Contención ($AB \subseteq S_{AB} \cap S_{BA}$):**  
   - Sea $C \in AB$. Por definición de segmento:  
     - $C$ está entre $A$ y $B$ (incluyendo $A$ y $B$).  
     - Como $S_{AB}$ contiene todos los puntos desde $A$ hacia $B$ (y más allá), $C \in S_{AB}$.  
     - Como $S_{BA}$ contiene todos los puntos desde $B$ hacia $A$ (y más allá), $C \in S_{BA}$.  
     - Por tanto, $C \in S_{AB} \cap S_{BA}$.  

2. **Contención ($S_{AB} \cap S_{BA} \subseteq AB$):**  
   Sea $C \in S_{AB} \cap S_{BA}$.  
   - **Definición de $S_{AB}$:** $C$ no está más allá de $B$ desde $A$ (es decir, $B$ no está entre $A$ y $C$).  
   - **Definición de $S_{BA}$:** $C$ no está más allá de $A$ desde $B$ (es decir, $A$ no está entre $B$ y $C$).  
   - Por el **Axioma de ordenación en una recta $II_1$** , las únicas posibilidades son:  
     - $C = A$, $C = B$, o $C$ está **entre $A$ y $B$**.  
   - En cualquier caso, $C \in AB$.  

3. **Conclusión:**  
   $$ S_{AB} \cap S_{BA} = AB. $$  
---

**Axioma $II_2$**  
Dados dos puntos distintos $A$ y $B$, siempre existen:  
- Un punto $C$ entre $A$ y $B$,  
- Y un punto $D$ tal que $B$ está entre $A$ y $D$.  

Una consecuencia inmediata de este axioma es que, entre dos puntos de una recta, existe una infinidad de puntos. Otra consecuencia es que la semirrecta $S_{AB}$ contiene una infinidad de puntos además de aquellos contenidos en el segmento $AB$.  

---

Considere una recta $m$ y dos puntos $A$ y $B$ que no pertenecen a esta. Decimos que $A$ y $B$ están en un mismo lado de la recta $m$ si el segmento $AB$ no la interseca.  


**Definición $1.5$**  
Sea $m$ una recta y $A$ un punto que no pertenece a $m$. El conjunto formado por los puntos de $m$ y por todos los puntos $B$ tales que $A$ y $B$ están en un mismo lado de la recta $m$ se define como **semiplano** determinado por $m$ que contiene al punto $A$, representado por $P_{mA}$.  

---

**Axioma $II_3$**  
Una recta $m$ determina exactamente dos semiplanos distintos cuya intersección es la recta $m$.  

---

**Convexidad**  
Un subconjunto del plano es **convexo** si el segmento que une dos puntos cualesquiera del conjunto está contenido en él. Ejemplos: el plano, un segmento, un semiplano.  

---

**Colinealidad**  
Se dice que tres o más puntos son **colineales** cuando todos pertenecen a una misma recta. De lo contrario, se denominan **no colineales**.  
