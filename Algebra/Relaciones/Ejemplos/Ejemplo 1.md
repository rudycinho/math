## Ejemplo de Relación entre Conjuntos  
**Conjuntos:**  
- $A = \\{a, b, c, d\\}$ (personas evaluadas).  
- $B = \\{1, 2, 3, 4, 5\\}$ (notas: $1$=insuficiente, $2$=aprobado, $3$=bueno, $4$=distinguido, $5$=sobresaliente).  

**Relación $R \subseteq A \times B$:**  
$$R = \\{ (a, 2), (a, 4), (b, 4), (d, 5) \\}$$  ![[Pasted image 20250427152118.png]]

1. **Elementos de $R$:**  
   - $(a, 2) \in R$: La persona $a$ obtuvo un *aprobado* ($2$).  
   - $(a, 4) \in R$: $a$ también logró un *distinguido* ($4$).  
   - $(b, 4) \in R$: $b$ consiguió un *distinguido* ($4$).  
   - $(d, 5) \in R$: $d$ alcanzó un *sobresaliente* ($5$).  

2. **Persona no relacionada ($c$):**  
   - $c \notin \text{Dom}(R)$: No hay pares con $c$ en $R$.  

3. **Cumple la definición formal:**  
   - $$R \subseteq A \times B \iff \forall (x, y) \in R, \; x \in A \land y \in B.$$  

4. **Notación $xRy$:**  
   - $aR2$, $aR4$, $bR4$, $dR5$.  

5. **Propiedad $P(x, y)$:**  
   $$(x, y) \in R \iff P(x, y) \text{ es verdadera},$$  
   donde $P(x, y)$: *“$x$ obtuvo la nota $y$”*.  
