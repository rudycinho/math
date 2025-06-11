### Plantilla para Verificar Relaciones de Equivalencia

**Definición:**  
Sea $S$ un conjunto y $\mathcal{R}$ una relación binaria definida en $S$ por:  
$$
x  \mathcal{R}  y \iff [\text{condición específica}]
$$  
para $x, y \in S$.  

**Objetivo:**  
Demostrar si $\mathcal{R}$ es una relación de equivalencia verificando:  
1. **Reflexividad**  
2. **Simetría**  
3. **Transitividad**  

---

#### **Demostración:**
1. **Reflexividad** ($\forall x \in S$, $x  \mathcal{R}  x$)  
   - *Desarrollo*:  
     Sea $x \in S$.  
     \[Demostrar que se cumple la condición específica para $x$ y $x$\].  
     Por tanto, $x  \mathcal{R}  x$.  

2. **Simetría** ($\forall x, y \in S$, $x  \mathcal{R}  y \implies y  \mathcal{R}  x$)  
   - *Desarrollo*:  
     Sean $x, y \in S$ tales que $x  \mathcal{R}  y$.  
     Entonces, \[usar la definición de $x  \mathcal{R}  y$\].  
     \[Demostrar que la condición implica $y  \mathcal{R}  x$\].  
     Por tanto, $y  \mathcal{R}  x$.  

3. **Transitividad** ($\forall x, y, z \in S$, $x  \mathcal{R}  y \land y  \mathcal{R}  z \implies x  \mathcal{R}  z$)  
   - *Desarrollo*:  
     Sean $x, y, z \in S$ tales que $x  \mathcal{R}  y$ y $y  \mathcal{R}  z$.  
     Entonces, \[usar la definición en ambas premisas\].  
     \[Combinar las premisas para deducir $x  \mathcal{R}  z$\].  
     Por tanto, $x  \mathcal{R}  z$.  

**Conclusión:**  
Como se cumplen las tres propiedades, $\mathcal{R}$ es una relación de equivalencia en $S$. En caso contrario, no lo es. $\blacksquare$  

---

### Ejemplo de aplicación (opcional):
- **Ejemplos ilustrativos** (si son útiles):  
  $$
  \begin{align}
  a  \mathcal{R}  b & \quad \text{[explicación breve]} \\
  \neg(c  \mathcal{R}  d) & \quad \text{[explicación breve]} 
  \end{align}
  $$

---

### Notas:
- **Símbolos**: Reemplazar $\mathcal{R}$ por el símbolo de la relación (e.g., $\sim$, $\triangle$, $\star$).  
- **Precisión**: En la condición específica, definir claramente los elementos involucrados (e.g., $z \in \mathbb{Z}$, $k \in \mathbb{N}$).  
- **Contraejemplos**: Si una propiedad falla, mostrar un contraejemplo específico.  
- **Conjunto**: Especificar $S$ (e.g., $\mathbb{R}$, $\mathbb{Z}$, matrices).