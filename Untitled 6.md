### **A. Relaciones**
- **Definición**: $R \subseteq A \times B$
- **Dominio**: $D_R = \{a \in A : (\exists b \in B) ((a, b) \in R)\}$  
- **Imagen**: $I_R = \{b \in B : (\exists a \in A) ((a, b) \in R)\}$  

---

### **Relaciones de equivalencia**
- **Propiedades**:  
  - *Reflexividad*: $\forall x \, (x \sim x)$  
  - *Simetría*: $\forall x,y \, (x \sim y \Rightarrow y \sim x)$  
  - *Transitividad*: $\forall x,y,z \, (x \sim y \land y \sim z \Rightarrow x \sim z)$  
- **Clase de equivalencia**: $[a] = \{x \in A : x \mathbin{R} a\}$  
- **Conjunto cociente**: $A/{\mathbin{R}} = \{[a] : a \in A\}$  
- **Congruencia módulo $n$**:  
  $$a \equiv b \pmod{n} \Leftrightarrow (\exists c \in \mathbb{Z})(a - b = c \cdot n)$$  

---

### **Particiones**
- **Definición**: $\{A_i\}_{i \in I}$ es partición de $X$ si:  
  (i) $\forall i \in I \, (A_i \neq \emptyset)$  
  (ii) $\forall i,j \in I \, (A_i \cap A_j = \emptyset)$  
  (iii) $\bigcup_{i \in I} A_i = X$  
- **Relación inducida**: $x \mathbin{R} y \Leftrightarrow (\exists i \in I)(x,y \in A_i)$  

---

### **B. Relaciones de orden**
- **Orden parcial**: $R \subseteq A^2$ satisface:  
  - *Reflexividad*: $\forall x \, (x \mathbin{R} x)$  
  - *Transitividad*: $\forall x,y,z \, (x \mathbin{R} y \land y \mathbin{R} z \Rightarrow x \mathbin{R} z)$  
  - *Antisimetría*: $\forall x,y \, (x \mathbin{R} y \land y \mathbin{R} x \Rightarrow x = y)$  
- **Orden total**: $\forall a,b \, (a \mathbin{R} b \lor b \mathbin{R} a)$  
- **Orden estricto**: $\overline{R}$ satisface:  
  - *Arreflexividad*: $\forall a \, (\neg(a \overline{R} a))$  
  - *Transitividad*: $\forall a,b,c \, (a \overline{R} b \land b \overline{R} c \Rightarrow a \overline{R} c)$  

---

### **Elementos en conjuntos ordenados**
- **Mínimo**: $\min B = b$ si $\forall c \in B \, (b \mathbin{R} c)$  
- **Máximo**: $\max B = k$ si $\forall c \in B \, (c \mathbin{R} k)$  
- **Cotas inferiores**: $B^- = \{a \in A : \forall x \in B \, (a \mathbin{R} x)\}$  
- **Cotas superiores**: $B^+ = \{b \in A : \forall x \in B \, (x \mathbin{R} b)\}$  
- **Ínfimo**: $\inf B = \max B^-$  
- **Supremo**: $\sup B = \min B^+$  
- **Elemento minimal**: $b \in B$ minimal si $x \mathbin{R} b \Rightarrow x = b$  
- **Elemento maximal**: $d \in B$ maximal si $d \mathbin{R} x \Rightarrow x = d$