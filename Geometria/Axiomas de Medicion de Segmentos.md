**Axioma $III_1$**  
A todo par de puntos del plano corresponde un número mayor o igual a cero. Este número es cero si y solo si los puntos son coincidentes.  

---

**Distancia**  
El número al que se refiere este axioma se denomina *distancia entre los puntos* o *longitud del segmento* determinado por los dos puntos.  

---

**Axioma $III_2$**  
Los puntos de una recta pueden ser siempre colocados en correspondencia biunívoca con los números reales, de modo que la diferencia entre estos números mida la distancia entre los puntos correspondientes.  
*Axioma de la regla infinita*.  

---

**Coordenada de un punto**  
El número que corresponde a un punto de la recta se denomina *coordenada* de dicho punto.  

De acuerdo con el axioma $III_1$, la longitud de un segmento $\overline{AB}$ es siempre mayor que cero. Asimismo, si $a$ y $b$ son las coordenadas de los extremos de ese segmento, su longitud será la diferencia entre el mayor y el menor de estos números. Esto es equivalente a tomar la diferencia entre $a$ y $b$ en cualquier orden y, luego, considerar su valor absoluto.  
La longitud del segmento $AB$ se representa con el símbolo $\overline{AB}$. Por lo tanto:  
$$\overline{AB} = |b - a|$$  

---

**Axioma $III_3$**  
Si el punto $C$ se encuentra entre $A$ y $B$, entonces:  
$$\overline{AC} + \overline{CB} = \overline{AB}$$  

Los números reales están ordenados por la relación *menor que*, y tiene sentido afirmar que un número $c$ está entre otros dos números $a$ y $b$ cuando ocurre:  
$$a < c < b$$  
o  
$$b < c < a$$.

---

**Proposición 2.1**  
Si en una semirrecta $S_{AB}$ consideramos un segmento $\overline{AC}$ con $\overline{AC} < \overline{AB}$, entonces el punto $C$ estará entre $A$ y $B$.  

**Demostración:**  

1. **Ubicación de $C$:**  
   - Por hipótesis, $C$ está en $S_{AB}$ .  
   - Esto implica que $B$ y $C$ están en la misma semirrecta con origen $A$.  

2. **Exclusión de casos imposibles:**  
   - **$A$ no puede estar entre $B$ y $C$:**  
     Si $A$ estuviera entre $B$ y $C$, entonces $C$ estaría en la semirrecta opuesta a $S_{AB}$, lo que contradice la definición de $S_{AB}$.  

3. **Análisis del caso restante:**  
   - Supongamos que **$B$ está entre $A$ y $C$** (por contradicción).  
   - Por el **Axioma $III_3$**:  
     $$  
     \overline{AC} = \overline{AB} + \overline{BC}.  
     $$  
   - Esto implica:  
     $$  
     \overline{AC} > \overline{AB} \quad \text{(porque } \overline{BC} > 0\text{)}.  
     $$  
   - **Contradicción:** Esto contradice la hipótesis $\overline{AC} < \overline{AB}$.  

4. **Conclusión:**  
   - La única posibilidad restante es que **$C$ esté entre $A$ y $B$**.  


---

**Teorema 2.2**  
Sean $A$, $B$ y $C$ puntos distintos de una misma recta cuyas coordenadas son, respectivamente, $a$, $b$ y $c$. El punto $C$ está entre $A$ y $B$ si y solo si el número $c$ está entre $a$ y $b$.  

**Demostración**  

Sean $A$, $B$, y $C$ puntos de una recta con coordenadas $a$, $b$, y $c$. Entonces:  
$$
C \text{ está entre } A \text{ y } B \quad \iff \quad c \text{ está entre } a \text{ y } b.
$$

**($\Rightarrow$)**  *Si $C$ está entre $A$ y $B$, entonces $c$ está entre $a$ y $b$.*

1. **Axioma $III_3$:**  
   Si $C$ está entre $A$ y $B$, entonces:  
   $$
   \overline{AC} + \overline{CB} = \overline{AB}. \tag{1}
   $$

2. **Expresión con coordenadas (Axioma $III_2$):**  
   $$
   |c - a| + |b - c| = |b - a|. \tag{2}
   $$

3. **Caso 1: $a < b$:**  
   - **Subcaso 1.1:** $c < a$.  
     - $|c - a| = a - c$, $|b - c| = b - c$.  
     - Sustituyendo en (2):  
       $$
       (a - c) + (b - c) = b - a \implies 2a - 2c = 0 \implies a = c.  
       $$  
       **Contradicción:** $c < a \implies a \neq c$.  

   - **Subcaso 1.2:** $a < c < b$.  
     - $|c - a| = c - a$, $|b - c| = b - c$.  
     - Sustituyendo en (2):  
       $$
       (c - a) + (b - c) = b - a.  
       $$  
       **Se cumple sin contradicción.**  

   - **Subcaso 1.3:** $c > b$.  
     - $|c - a| = c - a$, $|b - c| = c - b$.  
     - Sustituyendo en (2):  
       $$
       (c - a) + (c - b) = b - a \implies 2c = 2b \implies c = b.  
       $$  
       **Contradicción:** $c > b \implies c \neq b$.  

4. **Caso 2: $b < a$:**  
   - **Subcaso 2.1:** $c < b$.  
     - $|c - a| = a - c$, $|b - c| = b - c$.  
     - Sustituyendo en (2):  
       $$
       (a - c) + (b - c) = a - b \implies 2b - 2c = 0 \implies b = c.  
       $$  
       **Contradicción:** $c < b \implies b \neq c$.  

   - **Subcaso 2.2:** $b < c < a$.  
     - $|c - a| = a - c$, $|b - c| = c - b$.  
     - Sustituyendo en (2):  
       $$
       (a - c) + (c - b) = a - b.  
       $$  
       **Se cumple sin contradicción.**  

   - **Subcaso 2.3:** $c > a$.  
     - $|c - a| = c - a$, $|b - c| = c - b$.  
     - Sustituyendo en (2):  
       $$
       (c - a) + (c - b) = a - b \implies 2c = 2a \implies c = a.  
       $$  
       **Contradicción:** $c > a \implies c \neq a$.  

5. **Conclusión:**  
   La igualdad $|c - a| + |b - c| = |b - a|$ **solo se cumple** si $c$ está entre $a$ y $b$. Cualquier otra posición genera contradicciones algebraicas.  


**( $\Leftarrow$ )** *Si $c$ está entre $a$ y $b$, entonces $C$ está entre $A$ y $B$.*
1. **Caso 1: $a < b$:**  
   - Si $a < c < b$:  
     - $|c - a| = c - a$, $|b - c| = b - c$.  
     - Sumando:  
       $$
       (c - a) + (b - c) = b - a = |b - a|.  
       $$
     - Por el **Axioma $III_3$:**  
       $$
       \overline{AC} + \overline{CB} = \overline{AB} \implies C \text{ está entre } A \text{ y } B.  
       $$  

2. **Caso 2: $b < a$:**  
   - Si $b < c < a$:  
     - $|c - a| = a - c$, $|b - c| = c - b$.  
     - Sumando:  
       $$
       (a - c) + (c - b) = a - b = |b - a|.  
       $$  
     - Por el **Axioma $III_3$:**  
       $$
       \overline{AC} + \overline{CB} = \overline{AB} \implies C \text{ está entre } A \text{ y } B.  
       $$  
**Conclusión Final:**  
$$
\boxed{C \text{ está entre } A \text{ y } B \iff c \text{ está entre } a \text{ y } b.}
$$  

---

**Definición 2.3**  
Se **define** como *punto medio* del segmento $\overline{AB}$ a un punto $C$ de este segmento tal que $\overline{AC} = \overline{CB}$.  

---

**Teorema 2.4**  
Un segmento tiene exactamente un punto medio.  

**Demostración:**  

**Existencia del Punto Medio**  
1. **Coordenadas de los extremos:**  
   Sean $A$ y $B$ los extremos del segmento $\overline{AB}$, con coordenadas $a$ y $b$.  

2. **Definición del punto medio:**  
   Sea $c = \frac{a + b}{2}$. Por el **Axioma $III_2$** (regla infinita), existe un punto $C$ en la recta con coordenada $c$.  

3. **Cálculo de las distancias:**  
   - $\overline{AC} = |c - a| = \left| \frac{a + b}{2} - a \right| = \frac{|b - a|}{2}$.  
   - $\overline{CB} = |b - c| = \left| b - \frac{a + b}{2} \right| = \frac{|b - a|}{2}$.  

   Por tanto:  
   $$  
   \overline{AC} = \overline{CB}.  
   $$  

4. **Posición de $C$ (usando la Proposición 2.1):**  
   - Como $\overline{AC} = \frac{|b - a|}{2} < |b - a| = \overline{AB}$, por la **Proposición 2.1**, $C$ está entre $A$ y $B$.  

   **Conclusión:** $C$ es punto medio de $\overline{AB}$.  


**Unicidad del Punto Medio**  
Supongamos que existe otro punto medio $C'$ en $\overline{AB}$, con coordenada $c'$.  

1. **Condición de punto medio:**  
   $\overline{AC'} = \overline{C'B}$.  

2. **Expresión en coordenadas:**  
   - **Caso 1:** Si $a < c' < b$:  
     $$  
     c' - a = b - c' \implies 2c' = a + b \implies c' = \frac{a + b}{2}.  
     $$  
   - **Caso 2:** Si $b < c' < a$:  
     $$  
     a - c' = c' - b \implies 2c' = a + b \implies c' = \frac{a + b}{2}.  
     $$  

3. **Igualdad de coordenadas:**  
   En ambos casos, $c' = \frac{a + b}{2} = c$.  

4. **Conclusión por el Axioma $III_2$:**  
   Como $c' = c$, los puntos $C$ y $C'$ coinciden ($C = C'$).  


**Conclusión Final:**  
$$  
\boxed{\text{Existe un único punto medio en todo segmento.}}  
$$  


---

**Definición 2.5**  
Sea $A$ un punto del plano y $r$ un número real positivo. El *círculo* de centro $A$ y radio $r$ es el conjunto de todos los puntos $B$ del plano tales que $\overline{AB} = r$.  

Como consecuencia del axioma $III_2$, es posible trazar un círculo con cualquier centro y radio.  

Un punto $C$ que satisface $\overline{AC} < r$ se **ubica dentro** del círculo. Si $\overline{AC} > r$, entonces $C$ se **ubica fuera** del círculo.  

El conjunto de puntos dentro del círculo se **conoce como** *disco* de radio $r$ y centro $A$.  

Además, por el axioma $III_2$, el segmento que une un punto fuera del círculo con su centro interseca al círculo en exactamente un punto.  

**Demostración:**  

1. **Parametrización de la recta:**  
   - Sea $A$ el centro del círculo (radio $r$) y $D$ un punto exterior ($\overline{AD} > r$).  
   - La recta $AD$ se parametriza como $A + t(D - A)$, donde $t \in \mathbb{R}$.  

2. **Punto de intersección:**  
   - Buscamos $t$ tal que $\overline{AC} = r$ para $C = A + t(D - A)$.  
   - Resolviendo:  
     $$  
     |t| \cdot \overline{AD} = r \implies t = \frac{r}{\overline{AD}} \quad (\text{única solución positiva}).  
     $$  

**Conclusión:**  
$$  
\boxed{\text{Existe exactamente un punto de intersección.}}  
$$  
