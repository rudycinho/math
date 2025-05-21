
**Demostración Formal en Notación Lógica:**

---

**1. $A \cap B \subseteq A$:**

$$
\begin{align*}
&1.\ \forall x \ (x \in A \cap B \implies x \in A \land x \in B) \quad &\text{(Definición de } \cap \text{)} \\
&2.\ \text{Sea } x \in A \cap B \text{ arbitrario} \quad &\text{(Hipótesis)} \\
&3.\ x \in A \land x \in B \quad &\text{(Aplicación de 1 en 2)} \\
&4.\ x \in A \quad &\text{(Eliminación de } \land \text{ en 3)} \\
&5.\ \forall x \ (x \in A \cap B \implies x \in A) \quad &\text{(Generalización Universal de 2–4)} \\
&6.\ A \cap B \subseteq A \quad &\text{(Definición de } \subseteq \text{ en 5)}
\end{align*}
$$

**2. $A \cap B \subseteq A \cup B$:**

$$
\begin{align*}
&1.\ \forall x \ (x \in A \cap B \implies x \in A \land x \in B) \quad &\text{(Definición de } \cap \text{)} \\
&2.\ \text{Sea } x \in A \cap B \text{ arbitrario} \quad &\text{(Hipótesis)} \\
&3.\ x \in A \land x \in B \quad &\text{(Aplicación de 1 en 2)} \\
&4.\ x \in A \quad &\text{(Eliminación de } \land \text{ en 3)} \\
&5.\ \forall x \ (x \in A \implies x \in A \cup B) \quad &\text{(Definición de } \cup \text{ y } \lor\text{-Introducción)} \\
&6.\ x \in A \cup B \quad &\text{(Modus Ponens: 4 y 5)} \\
&7.\ \forall x \ (x \in A \cap B \implies x \in A \cup B) \quad &\text{(Generalización Universal de 2–6)} \\
&8.\ A \cap B \subseteq A \cup B \quad &\text{(Definición de } \subseteq \text{ en 7)}
\end{align*}
$$

---

**Notación Clave:**  
- $\land$: Conjunción ("y").  
- $\lor$: Disyunción ("o").  
- $\implies$: Implicación.  
- $\forall x$: Cuantificador universal ("para todo \( x \)").  
- $\subseteq$: Subconjunto.  

Esta estructura sigue las reglas de la **deducción natural** y axiomas de la teoría de conjuntos.
