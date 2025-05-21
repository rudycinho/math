Para demostrar que si $R$ es una relación simétrica, entonces $R^{-1}$ también es simétrica, seguimos los siguientes pasos:

**Definiciones:**
1. **Relación simétrica:** Una relación $R$ en un conjunto $A$ es simétrica si para todo $a, b \in A$,  
   $$ (a, b) \in R \implies (b, a) \in R. $$
2. **Relación inversa:** La inversa de $R$, denotada $R^{-1}$, se define como:  
   $$ R^{-1} = \{ (b, a) \mid (a, b) \in R \}. $$

**Demostración:**
1. **Supongamos que $R$ es simétrica.**
2. **Tomamos un elemento arbitrario $(x, y) \in R^{-1}$.**  
   Por definición de inversa:  
   $$ (x, y) \in R^{-1} \implies (y, x) \in R. $$
3. **Aplicamos la simetría de $R$:**  
   Como $(y, x) \in R$ y $R$ es simétrica:  
   $$ (y, x) \in R \implies (x, y) \in R. $$
4. **Usamos la definición de inversa nuevamente:**  
   Si $(x, y) \in R$, entonces por definición de $R^{-1}$:  
   $$ (y, x) \in R^{-1}. $$
5. **Conclusión:**  
   Hemos demostrado que si $(x, y) \in R^{-1}$, entonces $(y, x) \in R^{-1}$. Por lo tanto, $R^{-1}$ es simétrica.

**Resumen en pasos lógicos:**  
$$
\begin{align*}
R \text{ es simétrica} &\implies \left[ (a, b) \in R \implies (b, a) \in R \right] \\
&\implies \left[ (y, x) \in R \implies (x, y) \in R \right] \quad (\text{def. de simetría}) \\
&\implies \left[ (x, y) \in R^{-1} \implies (y, x) \in R^{-1} \right] \quad (\text{def. de inversa}) \\
&\implies R^{-1} \text{ es simétrica.}
\end{align*}
$$

**Respuesta final:**  
$$\boxed{R^{-1} \text{ es simétrica si } R \text{ es simétrica.}}$$



**Demostración:**  
Queremos probar que si $R$ es una relación simétrica, entonces $R^{-1}$ también lo es.  

**Definiciones:**  
1. **Simetría de $R$:**  
   $$(x, y) \in R \implies (y, x) \in R.$$  
2. **Relación inversa $R^{-1}$:**  
   $$R^{-1} = \{ (y, x) \mid (x, y) \in R \}.$$  

**Pasos lógicos:**  
1. **Supongamos que $R$ es simétrica.**  
2. **Tomemos un par arbitrario $(x, y) \in R^{-1}$.**  
   Por definición de $R^{-1}$:  
   $$(x, y) \in R^{-1} \implies (y, x) \in R.$$  
3. **Aplicamos la simetría de $R$:**  
   Como $(y, x) \in R$, por simetría:  
   $$(y, x) \in R \implies (x, y) \in R.$$  
4. **Usamos la definición de $R^{-1}$ nuevamente:**  
   Si $(x, y) \in R$, entonces:  
   $$(y, x) \in R^{-1}.$$  
5. **Conclusión:**  
   Hemos probado que:  
   $$(x, y) \in R^{-1} \implies (y, x) \in R^{-1}.$$  
   Por lo tanto, $R^{-1}$ es simétrica.  

**Ejemplo concreto:**  
- Si $R = \{(1, 2), (2, 1), (3, 3)\}$ (simétrica),  
- Entonces $R^{-1} = \{(2, 1), (1, 2), (3, 3)\}$ (también simétrica).  

**Respuesta final:**  
$$\boxed{R^{-1} \text{ es simétrica si } R \text{ es simétrica.}}$$
---


Entiendo. Vamos a reconstruir la demostración con una **cadena explícita de implicaciones** y destacando cómo se conectan $R$ y $R^{-1}$. Usaré solo $x, y$ y notación matemática clara.

---

### **Demostración Encadenada (Paso a Paso):**
**Objetivo:**  
Demostrar que $R$ es simétrica $\implies R^{-1}$ es simétrica.

**Definiciones:**  
1. **Simetría de $R$:**  
   $$
   \forall x, y \in A: \, (x, y) \in R \implies (y, x) \in R.
   $$ 
2. **Relación inversa $R^{-1}$:**  
   $$
   R^{-1} = \{(y, x) \mid (x, y) \in R\}.
   $$

---

**Cadena Lógica:**  
1. **Partimos de la simetría de $R$:**  
   $$
   R \text{ es simétrica } \iff \forall x, y: \, (x, y) \in R \implies (y, x) \in R. \tag{1}
   $$

2. **Tomamos un par arbitrario en $R^{-1}$:**  
   Supongamos que $(x, y) \in R^{-1}$.  
   Por definición de $R^{-1}$:  
   $$
   (x, y) \in R^{-1} \implies (y, x) \in R. \tag{2}
   $$

3. **Aplicamos la simetría de $R$ al resultado anterior:**  
   De (2), $(y, x) \in R$.  
   Por (1) (simetría de $R$):  
   $$
   (y, x) \in R \implies (x, y) \in R. \tag{3}
   $$

4. **Relacionamos $(x, y) \in R$ con $R^{-1}$:**  
   Por definición de $R^{-1}$, si $(x, y) \in R$, entonces:  
   $$
   (y, x) \in R^{-1}. \tag{4}
   $$

5. **Unimos todas las implicaciones:**  
   Juntando (2), (3) y (4):  
   $$
   (x, y) \in R^{-1} \implies (y, x) \in R \implies (x, y) \in R \implies (y, x) \in R^{-1}. 
   $$ 
   Simplificando:  
   $$
   (x, y) \in R^{-1} \implies (y, x) \in R^{-1}. \tag{5}
   $$

6. **Conclusión final:**  
   La implicación (5) es precisamente la definición de simetría para $R^{-1}$.  
   Por lo tanto, $R^{-1}$ es simétrica.

---

### **Explicación de la Conexión $R \leftrightarrow R^{-1}$:**
- **Paso clave:** La simetría de $R$ garantiza que **"invertir un par en $R$ no lo saca de $R$"**.  
- **En $R^{-1}$:** Invertir un par de $R^{-1}$ equivale a **"volver al par original en $R$"**, y como $R$ es simétrica, ese par invertido ya estaba en $R$, lo que lo incluye automáticamente en $R^{-1}$.  

---

### **Ejemplo con Encadenamiento:**
- Sea $R = \{(1, 2), (2, 1)\}$ (simétrica).  
- Entonces $R^{-1} = \{(2, 1), (1, 2)\}$.  
- **Cadena para $(2, 1) \in R^{-1}$:**  
  $$
  (2, 1) \in R^{-1} \implies (1, 2) \in R \implies (2, 1) \in R \implies (1, 2) \in R^{-1}.
  $$
  Esto muestra que $R^{-1}$ hereda la simetría.

---

### **Resumen en Fórmulas:**
$$
\begin{align*}
R \text{ es simétrica} 
&\implies \big[(x, y) \in R \implies (y, x) \in R\big] \quad \text{(Def. simetría)} \\
&\implies \big[(x, y) \in R^{-1} \implies (y, x) \in R\big] \quad \text{(Def. inversa)} \\
&\implies \big[(y, x) \in R \implies (x, y) \in R^{-1}\big] \quad \text{(Def. inversa)} \\
&\implies \big[(x, y) \in R^{-1} \implies (y, x) \in R^{-1}\big] \quad \text{(Combinación)} \\
&\implies R^{-1} \text{ es simétrica.}
\end{align*}
$$

---

**Respuesta Final:**  
$$
\boxed{R^{-1} \text{ es simétrica porque la simetría de } R \text{ garantiza que } (x, y) \in R^{-1} \implies (y, x) \in R^{-1}.}
$$