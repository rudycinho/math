### Demostraciones en cadena de implicaciones

---

#### i) $R$ es simétrica $\Rightarrow$ $R^{-1}$ es simétrica  
**Hipótesis:** $R$ es simétrica, es decir:  
$$\forall a,b \in A: (a,b) \in R \Rightarrow (b,a) \in R$$  
**Demostración:**  
1. Sea $(c,d) \in R^{-1}$ (suposición inicial).  
2. Por definición de inversa: $(c,d) \in R^{-1} \iff (d,c) \in R$.  
3. Por simetría de $R$: $(d,c) \in R \Rightarrow (c,d) \in R$.  
4. Por definición de inversa: $(c,d) \in R \Rightarrow (d,c) \in R^{-1}$.  
**Conclusión:**  
$$\boxed{(c,d) \in R^{-1} \Rightarrow (d,c) \in R^{-1}}$$  
$$\boxed{R \text{ simétrica } \implies R^{-1} \text{ simétrica}}$$

---

#### ii) $R$ es transitiva $\Rightarrow$ $R^{-1}$ es transitiva  
**Hipótesis:** $R$ es transitiva, es decir:  
$$\forall a,b,c \in A: \left( (a,b) \in R \land (b,c) \in R \right) \Rightarrow (a,c) \in R$$  
**Demostración:**  
1. Sean $(x,y) \in R^{-1}$ e $(y,z) \in R^{-1}$ (suposición inicial).  
2. Por definición de inversa:  
   - $(x,y) \in R^{-1} \iff (y,x) \in R$  
   - $(y,z) \in R^{-1} \iff (z,y) \in R$  
3. Por transitividad de $R$: $(z,y) \in R \land (y,x) \in R \Rightarrow (z,x) \in R$.  
4. Por definición de inversa: $(z,x) \in R \iff (x,z) \in R^{-1}$.  
**Conclusión:**  
$$\boxed{\left( (x,y) \in R^{-1} \land (y,z) \in R^{-1} \right) \Rightarrow (x,z) \in R^{-1}}$$  
$$\boxed{R \text{ transitiva } \implies R^{-1} \text{ transitiva}}$$

---

### 3-38. $R$ y $R'$ transitivas $\Rightarrow$ $R \cap R'$ transitiva  
**Hipótesis:** $R$ y $R'$ son transitivas, es decir:  
$$\begin{cases} 
\forall a,b,c \in A: \left( (a,b) \in R \land (b,c) \in R \right) \Rightarrow (a,c) \in R \\ 
\forall a,b,c \in A: \left( (a,b) \in R' \land (b,c) \in R' \right) \Rightarrow (a,c) \in R' 
\end{cases}$$  
**Demostración:**  
1. Sean $(p,q) \in R \cap R'$ y $(q,r) \in R \cap R'$ (suposición inicial).  
2. Por definición de intersección:  
   - $(p,q) \in R \land (p,q) \in R'$  
   - $(q,r) \in R \land (q,r) \in R'$  
3. Por transitividad de $R$: $(p,q) \in R \land (q,r) \in R \Rightarrow (p,r) \in R$.  
4. Por transitividad de $R'$: $(p,q) \in R' \land (q,r) \in R' \Rightarrow (p,r) \in R'$.  
5. Por definición de intersección: $(p,r) \in R \land (p,r) \in R' \Rightarrow (p,r) \in R \cap R'$.  
**Conclusión:**  
$$\boxed{\left( (p,q) \in R \cap R' \land (q,r) \in R \cap R' \right) \Rightarrow (p,r) \in R \cap R'}}$$  
$$\boxed{R \text{ y } R' \text{ transitivas } \implies R \cap R' \text{ transitiva}}$$

---

### 3-39. $R$ y $R'$ antisimétricas $\Rightarrow$ $R \cap R'$ antisimétrica  
**Hipótesis:** $R$ y $R'$ son antisimétricas, es decir:  
$$\begin{cases} 
\forall a,b \in A: \left( (a,b) \in R \land (b,a) \in R \right) \Rightarrow a = b \\ 
\forall a,b \in A: \left( (a,b) \in R' \land (b,a) \in R' \right) \Rightarrow a = b 
\end{cases}$$  
**Demostración:**  
1. Sean $(s,t) \in R \cap R'$ y $(t,s) \in R \cap R'$ (suposición inicial).  
2. Por definición de intersección:  
   - $(s,t) \in R \land (s,t) \in R'$  
   - $(t,s) \in R \land (t,s) \in R'$  
3. Por antisimetría de $R$: $(s,t) \in R \land (t,s) \in R \Rightarrow s = t$.  
**Conclusión:**  
$$\boxed{\left( (s,t) \in R \cap R' \land (t,s) \in R \cap R' \right) \Rightarrow s = t}}$$  
$$\boxed{R \text{ y } R' \text{ antisimétricas } \implies R \cap R' \text{ antisimétrica}}$$