**Definición 4.1**  
Dos segmentos $AB$ y $CD$ son **congruentes** si $\overline{AB} = \overline{CD}$. Dos ángulos $\hat A$ y $\hat B$ son **congruentes** si tienen la misma medida.  

**Observación.** Con esta definición, las propiedades de igualdad de números se aplican a la congruencia de segmentos y ángulos. Como consecuencia, un segmento es siempre congruente a sí mismo, y dos segmentos congruentes a un tercero son congruentes entre sí. Lo mismo se cumple para los ángulos.  

**Notación:**  
Para simplificar, utilizaremos el símbolo $=$ para denotar congruencia. Así, $AB = CD$ se lee como "el segmento $AB$ es congruente al segmento $CD$", y $\hat A = \hat B$ significa "el ángulo $A$ es congruente al ángulo $B$".  

---

**Definición 4.2**  
Dos triángulos son **congruentes** si es posible establecer una correspondencia biunívoca entre sus vértices tal que los lados y ángulos correspondientes sean congruentes.  

Si $ABC$ y $EFG$ son congruentes bajo la correspondencia:  
$$
\begin{align}
A &\longleftrightarrow E, \\
B &\longleftrightarrow F, \\
C &\longleftrightarrow G,
\end{align}
$$  
entonces se cumplen simultáneamente las siguientes relaciones:  
$$
\begin{align}
AB &= EF, & BC &= FG, & AC &= EG, \\
\hat A &= \hat E, & \hat B &= \hat F, & \hat C &= \hat G.
\end{align}
$$  

**Notación:**  
$ABC = EFG$ indica que los triángulos $ABC$ y $EFG$ son congruentes.  

---

**Axioma IV**  
**Primer caso de congruencia (LAL)**  
Dados dos triángulos $ABC$ y $EFG$, si $AB = EF$, $AC = EG$ y $\hat A = \hat E$, entonces $ABC=EFG$.  

**Observación:**  
A diferencia de la Definición 4.2, que requiere seis relaciones (tres pares de lados y tres pares de ángulos), este axioma solo necesita tres condiciones:  
$$
\left.
\begin{aligned}
AB &= EF, \\
AC &= EG, \\
\hat A &= \hat E
\end{aligned}
\right\}
\implies
\left\{
\begin{aligned}
AB &= EF, & BC &= FG, & AC &= EG, \\
\hat A &= \hat E, & \hat B &= \hat F, & \hat C &= \hat G
\end{aligned}
\right.
$$  

---

**Teorema 4.3**  
**Segundo caso de congruencia (ALA)**  
Dados dos triángulos $ABC$ y $EFG$, si $AB=EF$, $\hat A = \hat E$ y $\hat B = \hat F$, entonces $ABC = EFG$.  

---

**Definición 4.4**  
Un triángulo es **isósceles** si tiene dos lados congruentes. Estos lados se llaman **laterales**, y el tercero se denomina **base**.  

---

**Proposición 4.5**  
En un triángulo isósceles, los ángulos adyacentes a la base son congruentes.  

---

**Proposición 4.6**  
Si en un triángulo $ABC$ dos de sus ángulos son congruentes, entonces el triángulo es isósceles.  

---

**Definición 4.7**  
Sea $ABC$ un triángulo y $D$ un punto en la recta que contiene a $B$ y $C$:  
- **Mediana**: El segmento $AD$ es una mediana relativa al lado $BC$ si $D$ es el punto medio de $BC$.  
- **Bisectriz**: El segmento $AD$ es una bisectriz del ángulo $\hat A$ si la semirrecta $AD$ divide $B\hat{A}C$ en dos ángulos congruentes, es decir, $B\hat{A}D = C\hat{A}D$.  
- **Altura**: El segmento $AD$ es una altura relativa al lado $BC$ si $AD$ es perpendicular a la recta que contiene a $B$ y $C$.  

---

**Proposición 4.8**  
En un triángulo isósceles, la mediana relativa a la base es también bisectriz y altura.  

---

**Teorema 4.9**  
**Tercer caso de congruencia (LLL)**  
Si dos triángulos tienen sus tres lados correspondientes congruentes, entonces los triángulos son congruentes.  
