### **11.1 INTRODUCCIÓN**  
- **Fórmulas clave**:  
  - Representación:  
    - Binómica: $z = (a, b)$  
    - Trigonométrica: $z = r(\cos \theta + i \sin \theta)$  
    - Exponencial: $z = r e^{i\theta}$.  
- **Explicación breve**:  
  Extensión de $\mathbb{R}$ a $\mathbb{C}$ para resolver ecuaciones sin solución real (ej. $x^2 + 1 = 0$). Se definen operaciones y se introducen formas alternativas.  
- **Tips**:  
  - $\mathbb{R}$ es isomorfo a complejos con parte imaginaria nula: $(a, 0) \equiv a$.  
  - En $\mathbb{C}$, la radicación $n$-ésima siempre tiene **$n$ soluciones** (en $\mathbb{R}$ no siempre).  

---

### **11.2.1 ECUACIONES SIN SOLUCIONES EN $\mathbb{R}$**  
- **Fórmulas clave**:  
  - Discriminante: $\Delta = b^2 - 4ac$.  
- **Explicación breve**:  
  Ecuaciones como $x^2 + 1 = 0$ o cuadráticas con $\Delta < 0$ no tienen raíces reales. Esto motiva la creación de $\mathbb{C}$.  
- **Tips**:  
  - En $\mathbb{C}$, **todas las ecuaciones polinómicas tienen solución** (Teorema Fundamental del Álgebra).  

---

### **11.2.2 RELACIÓN DE EQUIVALENCIA EN $\mathbb{R}^2$**  
- **Fórmulas clave**:  
  - $z = (a, b)$,  
  - $\text{Re}(z) = a$, $\text{Im}(z) = b$.  
- **Explicación breve**:  
  $\mathbb{C}$ se define como pares ordenados en $\mathbb{R}^2$ con relación de equivalencia trivial (identidad). Interpretación geométrica en el plano complejo.  
- **Tips**:  
  - **Complejo real**: $\text{Im}(z) = 0$ (eje $x$).  
  - **Imaginario puro**: $\text{Re}(z) = 0$ (eje $y$).  
  - $\text{Re}(z) = k$: recta vertical.  
  - $\text{Im}(z) \leq k$: semiplano horizontal.  

---

### **11.2.3 OPERACIONES EN $\mathbb{C}$**  
- **Fórmulas clave**:  
  - Suma: $(a,b) + (c,d) = (a+c, b+d)$.  
  - Producto: $(a,b) \cdot (c,d) = (ac - bd, ad + bc)$.  
  - Inverso aditivo: $-(a,b) = (-a, -b)$.  
  - Inverso multiplicativo: $(a,b)^{-1} = \left( \frac{a}{a^2+b^2}, \frac{-b}{a^2+b^2} \right)$.  
- **Explicación breve**:  
  ($\mathbb{C}, +, \cdot$) es un **cuerpo conmutativo no ordenado**. Cumple propiedades de grupo abeliano para suma y producto.  
- **Tips**:  
  - **Radicación**: $\sqrt[n]{z}$ tiene **exactamente $n$ raíces** en $\mathbb{C}$ (ej. $\sqrt[3]{1} = 1, \frac{-1 \pm i\sqrt{3}}{2}$).  
  - $\mathbb{C}$ **no es ordenado**: Si $i > 0$, entonces $i^2 = -1 > 0$ (contradicción).  
  - El inverso multiplicativo requiere $a^2 + b^2 \neq 0$.  

---  

### **11.3 ISOMORFISMO DE LOS COMPLEJOS REALES EN LOS REALES**  
- **Fórmulas clave**:  
  - Conjunto complejos reales: $\mathbb{C}_{\mathbb{R}} = \{(a, b) \in \mathbb{C} \mid b = 0\}$.  
  - Isomorfismo: $f: \mathbb{C}_{\mathbb{R}} \to \mathbb{R}$ definida por $f(a, 0) = a$.  
- **Explicación breve**:  
  Existe un isomorfismo algebraico (biyectivo y preserva operaciones) entre los complejos de parte imaginaria nula $(a, 0)$ y los números reales $a$. Esto justifica identificar $(a, 0) \equiv a$.  
- **Tips**:  
  - **Identificación práctica**: En cálculos, $(a, 0)$ se reemplaza por $a$ (ej: $(3, 0) + (2, 0) = 5$).  
  - $f$ preserva:  
    - **Suma**: $f[(a,0) + (c,0)] = f(a,0) + f(c,0)$.  
    - **Producto**: $f[(a,0) \cdot (c,0)] = f(a,0) \cdot f(c,0)$.  
  - $\mathbb{C}_{\mathbb{R}}$ y $\mathbb{R}$ son **algebraicamente idénticos**.  

---  

### **11.4 FORMA BINÓMICA DE UN COMPLEJO**  

#### **11.4.1. Unidad imaginaria**  
- **Fórmulas clave**:  
  - Unidad imaginaria: $i = (0, 1)$.  
  - Producto con real: $(b, 0) \cdot i = (0, b)$ → $b \cdot i = bi$.  
  - Potencias cíclicas de $i$:  
    $$
    i^0 = 1, \quad i^1 = i, \quad i^2 = -1, \quad i^3 = -i, \quad i^4 = 1.
    $$  
  - Generalización ($n \in \mathbb{N}$): Si $n = 4q + r$ ($0 \leq r < 4$):  
    $$
    i^n = i^r.
    $$  

- **Explicación breve**:  
  La unidad imaginaria $i$ permite convertir complejos reales en imaginarios puros. Sus potencias son periódicas cada 4 términos.  
- **Tips**:  
  - **Regla mnemotécnica**: $i^2 = -1$ (base para simplificaciones).  
  - **Cálculo rápido de $i^n$**: Usa el resto de $n/4$:  
    - Resto $0$ → $1$,  
    - Resto $1$ → $i$,  
    - Resto $2$ → $-1$,  
    - Resto $3$ → $-i$.  

---  

#### **11.4.2. Forma binómica de los complejos**  
- **Fórmulas clave**:  
  - Conversión: $(a, b) = a + b \cdot i$.  
  - Suma: $(a + bi) + (c + di) = (a + c) + (b + d)i$.  
  - Multiplicación:  
    $$
    (a + bi)(c + di) = (ac - bd) + (ad + bc)i.
    $$  
- **Explicación breve**:  
  La forma binómica $z = a + bi$ simplifica operaciones algebraicas usando $i^2 = -1$, evitando el manejo de pares ordenados.  
- **Tips**:  
  - **Operaciones más eficientes**: Usa álgebra estándar + regla $i^2 = -1$ (ej: $(3i)(2i) = 6i^2 = -6$).  
  - **División**: Multiplica numerador y denominador por el conjugado del denominador:  
    $$
    \frac{a + bi}{c + di} = \frac{(a + bi)(c - di)}{c^2 + d^2}.
    $$  
  - **Ejemplo práctico**:  
    $$
    (-2 + 3i) - (1 + 2i) = -3 + i \quad ; \quad (-3 + i)^2 = 8 - 6i.
    $$  

---  

### **11.5 LA CONJUGACIÓN EN C**  

#### **11.5.1. Complejos conjugados**  
- **Fórmulas clave**:  
  - Conjugado: Si $z = a + bi$, entonces $\overline{z} = a - bi$.  
  - Propiedad: $\overline{\overline{z}} = z$.  
- **Explicación breve**:  
  Dos complejos son conjugados si tienen igual parte real y partes imaginarias opuestas. Son simétricos respecto al eje real en el plano complejo.  
- **Tips**:  
  - Identificación rápida: cambiar el signo de la parte imaginaria.  
  - Representación gráfica: simetría axial respecto al eje real.  

---

#### **11.5.2. Propiedades de la conjugación**  
- **Fórmulas clave**:  
  - Suma: $z + \overline{z} = 2 \operatorname{Re}(z)$.  
  - Producto: $z \cdot \overline{z} = a^2 + b^2 = |z|^2$ (real no negativo).  
- **Explicación breve**:  
  La suma de conjugados es el doble de la parte real. El producto es el cuadrado del módulo.  
- **Tips**:  
  - Usar $z \cdot \overline{z}$ para obtener un real no negativo.  

---

#### **11.5.3. Caracterización de complejos reales**  
- **Fórmulas clave**:  
  - $z$ es real $\Leftrightarrow z = \overline{z}$.  
- **Explicación breve**:  
  Un complejo es real si y solo si coincide con su conjugado (su parte imaginaria es cero).  
- **Tips**:  
  - Verificación: si $z = \overline{z} \Rightarrow b = 0$.  

---

#### **11.5.4. Automorfismo en C**  
- **Fórmulas clave**:  
  - Función conjugación: $f(z) = \overline{z}$ es automorfismo (isomorfismo de C en sí mismo).  
  - Propiedades:  
    $$
    \overline{z + z'} = \overline{z} + \overline{z'}, \quad \overline{z \cdot z'} = \overline{z} \cdot \overline{z'}.
    $$  
- **Explicación breve**:  
  La conjugación es biyectiva y preserva las operaciones de suma y producto.  
- **Tips**:  
  - El conjugado de una suma/producto es la suma/producto de los conjugados.  

---

### **11.6 MÓDULO DE UN COMPLEJO**  

#### **11.6.1. Definición**  
- **Fórmulas clave**:  
  - Módulo: $|z| = \sqrt{a^2 + b^2}$ para $z = a + bi$.  
- **Explicación breve**:  
  El módulo es la distancia del punto $(a,b)$ al origen en el plano complejo.  
- **Tips**:  
  - Ejemplo: $|-3 + 4i| = \sqrt{(-3)^2 + 4^2} = 5$.  

---

#### **11.6.2. Propiedades del módulo**  
- **Fórmulas clave**:  
  - I: $|\operatorname{Re}(z)| \leq |z|$ y $|\operatorname{Im}(z)| \leq |z|$.  
  - II: $z \cdot \overline{z} = |z|^2$.  
  - III: $|z \cdot z'| = |z| \cdot |z'|$.  
  - IV: $|z + z'| \leq |z| + |z'|$ (desigualdad triangular).  
  - V: $|z^n| = |z|^n$ (para $n$ natural).  
- **Explicación breve**:  
  Propiedades de acotación, multiplicatividad y aditividad del módulo.  
- **Tips**:  
  - **División**: $\left| \frac{z}{z'} \right| = \frac{|z|}{|z'|}$ (si $z' \neq 0$).  
  - **Desigualdad triangular**: útil para acotar sumas.  
  - Cálculo del inverso: $z^{-1} = \frac{\overline{z}}{|z|^2}$.  

---

#### **Ejemplos aplicados** (basados en 11.4 a 11.6)  
- **Ecuaciones con conjugados y módulos**:  
  - $z = -\overline{z}$ → $z$ es imaginario puro.  
  - $|z| = 1$ → circunferencia unidad.  
  - $|z - 1 + 2i| = 2$ → circunferencia centro (1,-2) y radio 2.  
  - $|z - \operatorname{Re}(z)| = [\operatorname{Im}(z)]^2$ → rectas $y=0$ y $y=1$.  
  - $z = -\overline{z} + 2$ → recta $x=1$.  
- **Tips**:  
  - Traducir ecuaciones complejas a geometría en el plano: 
    - $|z - z_0| = r$ → circunferencia.  
    - $\operatorname{Re}(z) = c$ → recta vertical.  
    - $\operatorname{Im}(z) = k$ → recta horizontal.  

---  

### **11.7 RAIZ CUADRADA EN C**  
- **Fórmulas clave**:  
  - Dado $z = a + bi$, las raíces cuadradas $w = x + yi$ satisfacen:  
    $$
    w^2 = z \quad \iff \quad 
    \begin{cases} 
    x^2 - y^2 = a, \\ 
    2xy = b. 
    \end{cases}
    $$  
  - Relación con el módulo:  
    $$
    x^2 + y^2 = |z| = \sqrt{a^2 + b^2}.
    $$  
  - Solución:  
    $$
    x = \pm \sqrt{\frac{|z| + a}{2}}, \quad y = \pm \sqrt{\frac{|z| - a}{2}}.
    $$  
- **Explicación breve**:  
  Para hallar $\sqrt{z}$:  
  1. Calcula $|z| = \sqrt{a^2 + b^2}$.  
  2. Resuelve para $x$ e $y$ usando las fórmulas anteriores.  
  3. **Combina signos** según el signo de $b$:  
    - Si $b > 0$: $x$ e $y$ con mismo signo ($(+,+)$ o $(-,-)$).  
    - Si $b < 0$: $x$ e $y$ con signos opuestos ($(+,-)$ o $(-,+)$).  
  Siempre hay **dos soluciones** (excepto si $z = 0$).  
- **Tips**:  
  - **Número de raíces**: En $\mathbb{C}$, todo complejo no nulo tiene **exactamente dos raíces cuadradas** (ej: $\sqrt{-9} = \pm 3i$).  
  - **Caso $b = 0$**:  
    - Si $a > 0$: soluciones reales $\pm \sqrt{a}$.  
    - Si $a < 0$: soluciones imaginarias puras $\pm \sqrt{|a|} \, i$.  
  - **Verificación**: Usa $w^2 = z$ para comprobar resultados.  
  - **Eficiencia**: La fórmula evita resolver el sistema no lineal directamente.  

---  
**Ejemplos**:  
1. $\sqrt{-4 - 3i}$:  
   - $|z| = 5$, $a = -4$, $b = -3 < 0$,  
   - $x = \pm \sqrt{\frac{5-4}{2}} = \pm \frac{\sqrt{2}}{2}$, $y = \pm \sqrt{\frac{5+4}{2}} = \pm \frac{3\sqrt{2}}{2}$,  
   - **Signos opuestos**: $\pm \left( \frac{\sqrt{2}}{2} - \frac{3\sqrt{2}}{2} i \right)$.  
2. $\sqrt{-2i}$:  
   - $|z| = 2$, $a = 0$, $b = -2 < 0$,  
   - $x = \pm 1$, $y = \pm 1$,  
   - **Signos opuestos**: $\pm (1 - i)$.  
3. $\sqrt{-9}$:  
   - $|z| = 9$, $a = -9$, $b = 0$,  
   - $x = 0$, $y = \pm 3$: $\pm 3i$.  

---  

### **11.8 FORMA POLAR O TRIGONOMÉTRICA**  
- **Fórmulas clave**:  
  - Dado $z = a + bi \neq 0$:  
    $$
    \rho = |z| = \sqrt{a^2 + b^2}, \quad \varphi = \operatorname{Arg}(z)
    $$  
  - Paso de cartesianas a polares:  
    $$
    a = \rho \cos \varphi, \quad b = \rho \sin \varphi
    $$  
  - **Forma polar**:  
    $$
    z = \rho (\cos \varphi + i \sin \varphi)
    $$  
- **Explicación breve**:  
  1. **Módulo $\rho$**: Distancia del origen al punto $(a, b)$.  
  2. **Argumento $\varphi$**: Ángulo con el eje real positivo (en radianes).  
  3. **Argumento principal**: $\operatorname{Arg}(z) \in [0, 2\pi)$ (valor único).  
  4. **Igualdad de complejos en polar**:  
    $$
    \rho (\cos \varphi + i \sin \varphi) = \rho' (\cos \varphi' + i \sin \varphi') \iff \rho = \rho' \quad \text{y} \quad \varphi \equiv \varphi' \pmod{2\pi}.
    $$  
- **Tips**:  
  - **Cálculo de $\varphi$**:  
    - Usa $\tan \varphi = \frac{b}{a}$, pero **considera el cuadrante**:  
      - **Cuadrante I** ($a > 0, b > 0$): $\varphi = \arctan(b/a)$.  
      - **Cuadrante II** ($a < 0, b > 0$): $\varphi = \arctan(b/a) + \pi$.  
      - **Cuadrante III** ($a < 0, b < 0$): $\varphi = \arctan(b/a) + \pi$.  
      - **Cuadrante IV** ($a > 0, b < 0$): $\varphi = \arctan(b/a) + 2\pi$.  
    - **Casos especiales**:  
      - $a > 0, b = 0$ → $\varphi = 0$.  
      - $a < 0, b = 0$ → $\varphi = \pi$.  
      - $a = 0, b > 0$ → $\varphi = \pi/2$.  
      - $a = 0, b < 0$ → $\varphi = 3\pi/2$.  
  - **Convención alternativa**: Algunos usan $\operatorname{Arg}(z) \in (-\pi, \pi]$.  
  - **Multiplicación/división en polar**:  
    $$
    z_1 \cdot z_2 = \rho_1 \rho_2 \left( \cos(\varphi_1 + \varphi_2) + i \sin(\varphi_1 + \varphi_2) \right)
    $$  

---  
**Ejemplos**:  
1. $z = -2 + 2i$:  
   - $\rho = \sqrt{(-2)^2 + 2^2} = \sqrt{8} = 2\sqrt{2}$.  
   - $a = -2 < 0$, $b = 2 > 0$ → **Cuadrante II**.  
   - $\tan \varphi = \frac{2}{-2} = -1 \implies \varphi = \arctan(-1) + \pi = \frac{3\pi}{4}$ (135°).  
   - **Forma polar**: $z = 2\sqrt{2} \left( \cos \frac{3\pi}{4} + i \sin \frac{3\pi}{4} \right)$.  

2. $z = -3i$ (corrección):  
   - $\rho = \sqrt{0^2 + (-3)^2} = 3$.  
   - $a = 0$, $b = -3 < 0$ → **Eje imaginario negativo** → $\varphi = \frac{3\pi}{2}$ (270°).  
   - **Forma polar**: $z = 3 \left( \cos \frac{3\pi}{2} + i \sin \frac{3\pi}{2} \right)$.  
   - *Nota*: En el ejemplo original se menciona $\varphi = \pi$, pero eso corresponde a $-3$ (no a $-3i$).  

---  
**Errores comunes**:  
- **Confundir $-3$ con $-3i$**:  
  - Si $z = -3$ (real negativo): $\varphi = \pi$.  
  - Si $z = -3i$ (imaginario puro negativo): $\varphi = 3\pi/2$.  
- **Olvidar ajustar el cuadrante en $\varphi$**: $\arctan(b/a)$ solo da valores correctos en cuadrantes I y IV.  

---  

### **11.9 OPERACIONES EN FORMA POLAR**  
#### **11.9.1 Multiplicación**  
- **Fórmula clave**:  
  $$
  z \cdot z' = \rho \rho' \left[ \cos(\varphi + \varphi') + i \sin(\varphi + \varphi') \right]
  $$  
- **Explicación breve**:  
  El producto de dos complejos en forma polar tiene:  
  - **Módulo**: Producto de los módulos ($\rho \cdot \rho'$).  
  - **Argumento**: Suma de los argumentos ($\varphi + \varphi'$).  

#### **11.9.2 Cociente**  
- **Fórmula clave** ($z' \neq 0$):  
  $$
  \frac{z}{z'} = \frac{\rho}{\rho'} \left[ \cos(\varphi - \varphi') + i \sin(\varphi - \varphi') \right]
  $$  
- **Explicación breve**:  
  El cociente de dos complejos en forma polar tiene:  
  - **Módulo**: Cociente de los módulos ($\rho / \rho'$).  
  - **Argumento**: Diferencia de los argumentos ($\varphi - \varphi'$).  

#### **11.9.3 Potenciación (Fórmula de De Moivre)**  
- **Fórmula clave** ($n \in \mathbb{N}$):  
  $$
  z^n = \rho^n \left[ \cos(n\varphi) + i \sin(n\varphi) \right]
  $$  
- **Explicación breve**:  
  La potencia $n$-ésima de un complejo en forma polar tiene:  
  - **Módulo**: Potencia $n$-ésima del módulo ($\rho^n$).  
  - **Argumento**: Argumento multiplicado por $n$ ($n\varphi$).  

#### **11.9.4 Interpretación geométrica**  
- **Producto**:  
  - Rotación del vector $z$ por el ángulo $\varphi'$.  
  - Escalamiento del módulo por $\rho'$.  
- **Cociente**:  
  - Rotación inversa del vector $z$ por $\varphi'$.  
  - Escalamiento inverso del módulo por $1/\rho'$.  

---

### **Tips clave**  
1. **Argumento principal**:  
   - Usar $\operatorname{Arg}(z) \in [0, 2\pi)$ para evitar ambigüedades.  
   - Ejemplo: $\operatorname{Arg}(-3i) = \frac{3\pi}{2}$ (no $\pi$).  

2. **Operaciones con raíces**:  
   - La radicación $n$-ésima tiene **$n$ soluciones** (fórmula en 11.8).  
   - Ejemplo: $\sqrt[3]{i}$ tiene 3 soluciones (ver 11.8).  

3. **Verificación rápida**:  
   - Para $z^n$: $|z^n| = |z|^n$ y $\operatorname{Arg}(z^n) = n \cdot \operatorname{Arg}(z) \mod 2\pi$.  

4. **Errores comunes**:  
   - **Suma/resta**: ¡No se puede hacer en forma polar! Usar forma binómica.  
   - **Confundir $-a$ con $-ai$**:  
     - $z = -3$ → $\operatorname{Arg}(z) = \pi$.  
     - $z = -3i$ → $\operatorname{Arg}(z) = \frac{3\pi}{2}$.  

---

### **Ejemplos resueltos**  
#### **Multiplicación y cociente**  
Dados $z = -1 + i\sqrt{3}$ y $z' = \frac{3}{2} + i \frac{3\sqrt{3}}{2}$:  
1. **Forma polar**:  
   - $z$: $\rho = 2$, $\varphi = 120^\circ$ → $z = 2(\cos 120^\circ + i \sin 120^\circ)$.  
   - $z'$: $\rho' = 3$, $\varphi' = 60^\circ$ → $z' = 3(\cos 60^\circ + i \sin 60^\circ)$.  

2. **Producto $z \cdot z'$**:  
   $$
   z \cdot z' = 2 \cdot 3 \left[ \cos(120^\circ + 60^\circ) + i \sin(180^\circ) \right] = 6 \left[ -1 + i \cdot 0 \right] = -6.
   $$  

3. **Cociente $z / z'$**:  
   $$
   \frac{z}{z'} = \frac{2}{3} \left[ \cos(120^\circ - 60^\circ) + i \sin(60^\circ) \right] = \frac{2}{3} \left( \frac{1}{2} + i \frac{\sqrt{3}}{2} \right) = \frac{1}{3} + i \frac{\sqrt{3}}{3}.
   $$  

#### **Potenciación (De Moivre)**  
- $z = -1 + i\sqrt{3}$ → $\rho = 2$, $\varphi = 120^\circ$.  
- Calcular $z^6$:  
  $$
  z^6 = 2^6 \left[ \cos(6 \cdot 120^\circ) + i \sin(720^\circ) \right] = 64 \left[ \cos 0^\circ + i \sin 0^\circ \right] = 64.
  $$  

#### **Aplicación trigonométrica**  
- Obtener $\sin 2\theta$ y $\cos 2\theta$:  
  - Sea $w = \cos \theta + i \sin \theta$.  
  - Por binomio: $w^2 = (\cos \theta + i \sin \theta)^2 = \cos^2 \theta - \sin^2 \theta + i \cdot 2 \sin \theta \cos \theta$.  
  - Por De Moivre: $w^2 = \cos 2\theta + i \sin 2\theta$.  
  - Igualando:  
    $$
    \cos 2\theta = \cos^2 \theta - \sin^2 \theta, \quad \sin 2\theta = 2 \sin \theta \cos \theta.
    $$  

---

### **11.10 RADICACIÓN EN $\mathbb{C}$**  
#### **Fórmulas clave**  
- Dado $z = \rho (\cos \varphi + i \sin \varphi) \neq 0$, sus $n$ raíces $n$-ésimas son:  
$$
w_k = \sqrt[n]{\rho} \left( \cos \frac{\varphi + 2k\pi}{n} + i \sin \frac{\varphi + 2k\pi}{n} \right), \quad k = 0, 1, \dots, n-1.
$$  
- **Módulo común**: $\sqrt[n]{\rho}$ para todas las raíces.  
- **Argumentos**: Diferenciados por $\frac{2\pi}{n}$ entre raíces consecutivas.  

#### **Explicación breve**  
1. **Paso a forma polar**: Calcula $\rho = |z|$ y $\varphi = \operatorname{Arg}(z)$.  
2. **Aplica la fórmula**: Genera las $n$ raíces usando $k = 0, 1, \dots, n-1$.  
3. **Geometría**: Las raíces son vértices de un **polígono regular de $n$ lados**, centrado en el origen y radio $\sqrt[n]{\rho}$.  

#### **Tips esenciales**  
- **Número exacto de raíces**: Siempre $n$ raíces distintas si $z \neq 0$ (ejemplo: $\sqrt[3]{1}$ tiene 3 soluciones).  
- **Raíces de la unidad**: Caso particular cuando $z = 1$ ($\rho = 1$, $\varphi = 0$):  
  $$
  w_k = \cos \frac{2k\pi}{n} + i \sin \frac{2k\pi}{n}.
  $$  
- **Periodicidad**: Valores $k \geq n$ repiten raíces ($w_{k+n} = w_k$).  
- **Errores frecuentes**:  
  - Usar $k$ fuera de $\{0, 1, \dots, n-1\}$.  
  - Olvidar ajustar $\varphi$ al cuadrante correcto en $z$.  

---

### **Ejemplos resueltos**  
#### **1. $\sqrt[4]{-4 + 4i\sqrt{3}}$**  
- **Paso a polar**:  
  $$
  \rho = \sqrt{(-4)^2 + (4\sqrt{3})^2} = 8, \quad \varphi = \frac{2\pi}{3} \quad (\text{II cuadrante}).
  $$  
- **Raíces cuartas** ($n = 4$):  
  $$
  w_k = \sqrt[4]{8} \left( \cos \left( \frac{\pi}{6} + \frac{k\pi}{2} \right) + i \sin \left( \frac{\pi}{6} + \frac{k\pi}{2} \right) \right).
  $$  
  - $k=0$: $w_0 = \sqrt[4]{8} \left( \cos 30^\circ + i \sin 30^\circ \right) = \sqrt[4]{8} \left( \frac{\sqrt{3}}{2} + i \frac{1}{2} \right)$.  
  - $k=1$: $w_1 = \sqrt[4]{8} \left( \cos 120^\circ + i \sin 120^\circ \right) = \sqrt[4]{8} \left( -\frac{1}{2} + i \frac{\sqrt{3}}{2} \right)$.  
  - $k=2$: $w_2 = \sqrt[4]{8} \left( \cos 210^\circ + i \sin 210^\circ \right) = \sqrt[4]{8} \left( -\frac{\sqrt{3}}{2} - i \frac{1}{2} \right)$.  
  - $k=3$: $w_3 = \sqrt[4]{8} \left( \cos 300^\circ + i \sin 300^\circ \right) = \sqrt[4]{8} \left( \frac{1}{2} - i \frac{\sqrt{3}}{2} \right)$.  
- **Representación**: Cuadrado inscrito en circunferencia de radio $\sqrt[4]{8}$.  

#### **2. $\sqrt[3]{1}$ (Raíces cúbicas de la unidad)**  
- **Paso a polar**: $\rho = 1$, $\varphi = 0$.  
- **Raíces cúbicas** ($n = 3$):  
  $$
  w_k = \cos \frac{2k\pi}{3} + i \sin \frac{2k\pi}{3}.
  $$  
  - $k=0$: $w_0 = 1$.  
  - $k=1$: $w_1 = -\frac{1}{2} + i \frac{\sqrt{3}}{2}$.  
  - $k=2$: $w_2 = -\frac{1}{2} - i \frac{\sqrt{3}}{2}$.  
- **Representación**: Triángulo equilátero en circunferencia unitaria.  

---

### **Diagrama de raíces**  
```  
        w₁ (120°)          w₂ (210°)  
          ●                 ●  
         / \               / \  
        /   \             /   \  
       /     \           /     \  
      ●-------●-------●-------●  
    w₀ (0°)  Centro  w₃ (300°)  w₄ (no existe)  
```  
- **Radio**: $\sqrt[n]{\rho}$, **separación angular**: $\frac{2\pi}{n}$.  

---  

### **11.12 LOGARITMACIÓN EN $\mathbb{C}$**  
- **Definición**: $w = \log z$ si y solo si $e^w = z$ ($z \neq 0$).  
- **Fórmula general** (multivaluada):  
  $$
  \log z = \ln |z| + i (\operatorname{Arg}(z) + 2k\pi i, \quad k \in \mathbb{Z}.
  $$  
- **Valor principal** (rama principal):  
  $$
  \operatorname{Log} z = \ln |z| + i \operatorname{Arg}(z), \quad \text{con } \operatorname{Arg}(z) \in (-\pi, \pi].
  $$  

#### **Explicación breve**  
1. **Paso a forma exponencial**: $z = \rho e^{i\varphi}$ con $\rho = |z|$, $\varphi = \operatorname{Arg}(z)$.  
2. **Resuelve $e^{u+iv} = \rho e^{i\varphi}$** → $e^u = \rho$ y $v = \varphi + 2k\pi$.  
3. **Solución**: $u = \ln \rho$, $v = \varphi + 2k\pi$ → $\log z = \ln \rho + i(\varphi + 2k\pi)$.  
4. **Valor principal**: $k = 0$ → $\operatorname{Log} z = \ln \rho + i \varphi$.  

#### **Tips clave**  
- **Parte real fija**: Todos los logaritmos tienen $\operatorname{Re}(w) = \ln |z|$.  
- **Infinitos valores**: Diferenciados por $2k\pi i$ en la parte imaginaria.  
- **Singularidad**: No definido para $z = 0$.  
- **Propiedad engañosa**:  
  $$
  \log(z_1 z_2) \neq \log z_1 + \log z_2 \quad \text{(por la multivaluación)}.
  $$  

---  
### **Ejemplos resueltos**  
1. **$\log(-2)$**  
   - $|z| = 2$, $\operatorname{Arg}(z) = \pi$ (valor principal).  
   - **Valor principal**: $\operatorname{Log}(-2) = \ln 2 + i\pi$.  
   - **Multivaluado**: $\log(-2) = \ln 2 + i(\pi + 2k\pi)$.  

2. **$\log\left(-\frac{e}{\sqrt{2}} - i \frac{e}{\sqrt{2}}\right)$**  
   - $|z| = \sqrt{\left(-\frac{e}{\sqrt{2}}\right)^2 + \left(-\frac{e}{\sqrt{2}}\right)^2} = e$.  
   - $\operatorname{Arg}(z) = \frac{5\pi}{4}$ (III cuadrante) → **¡Error!**  
     **Corrección**: $\operatorname{Arg}(z) \in (-\pi, \pi]$ → $\varphi = -\frac{3\pi}{4}$.  
   - **Valor principal**: $\operatorname{Log} z = \ln e + i\left(-\frac{3\pi}{4}\right) = 1 - i\frac{3\pi}{4}$.  
   - **Multivaluado**: $\log z = 1 + i\left(-\frac{3\pi}{4} + 2k\pi\right)$.  

---  
### **11.13 EXPONENCIAL COMPLEJA GENERAL**  
- **Definición**: Para $z_1 \neq 0$ y $z_2 \in \mathbb{C}$:  
  $$
  z_1^{z_2} = e^{z_2 \log z_1}.
  $$  
- **Valor principal**:  
  $$
  \text{V.P. } z_1^{z_2} = e^{z_2 \operatorname{Log} z_1}.
  $$  

#### **Explicación breve**  
1. **Usa logaritmo**: $w = z_1^{z_2} = e^{z_2 \log z_1}$.  
2. **Multivaluación**: Si $\log z_1$ tiene infinitos valores, $z_1^{z_2}$ puede tener infinitos valores.  
3. **Valor principal**: Usa $\operatorname{Log} z_1$ (argumento principal).  

#### **Tips**  
- **Caso real positivo**: Si $z_1 > 0$ (real), $\operatorname{Log} z_1 = \ln z_1$ → $z_1^{z_2} = e^{z_2 \ln z_1}$.  
- **Exponente entero**: Si $z_2 \in \mathbb{Z}$, es univaluado.  

---  
### **Ejemplo resuelto**  
#### **Valor principal de $\left( \frac{1-i}{1+i} \right)^i$**  
1. **Simplifica la base**:  
   $$
   \frac{1-i}{1+i} = \frac{(1-i)^2}{(1+i)(1-i)} = \frac{1 - 2i - 1}{2} = \frac{-2i}{2} = -i.
   $$  
2. **Forma polar de $z_1 = -i$**  
   - $|z_1| = 1$, $\operatorname{Arg}(z_1) = -\frac{\pi}{2}$ (eje imaginario negativo).  
   - **Valor principal del logaritmo**:  
     $$
     \operatorname{Log}(-i) = \ln 1 + i\left(-\frac{\pi}{2}\right) = -i\frac{\pi}{2}.
     $$  
3. **Aplica la definición**:  
   $$
   (-i)^i = e^{i \cdot \operatorname{Log}(-i)} = e^{i \cdot \left(-i \frac{\pi}{2}\right)} = e^{\frac{\pi}{2}}.
   $$  
   **Explicación**: $i \cdot (-i \pi/2) = -i^2 \pi/2 = -(-1)\pi/2 = \pi/2$.  

---  
### **11.13 EXPONENCIAL COMPLEJA GENERAL**  
#### **Fórmulas clave**  
- **Definición**: Para $z_1 \neq 0$ y $z_2 \in \mathbb{C}$:  
  $$
  z_1^{z_2} = e^{z_2 \log z_1}
  $$  
- **Valor principal** (usando logaritmo principal):  
  $$
  \text{V.P. } z_1^{z_2} = e^{z_2 \operatorname{Log} z_1}, \quad \text{donde} \quad \operatorname{Log} z_1 = \ln |z_1| + i \operatorname{Arg}(z_1), \quad \operatorname{Arg}(z_1) \in (-\pi, \pi].
  $$  

#### **Explicación breve**  
1. **Paso 1**: Calcula $\operatorname{Log} z_1$ (logaritmo principal).  
2. **Paso 2**: Multiplica por $z_2$.  
3. **Paso 3**: Evalúa la exponencial $e^{\text{(resultado)}}$.  
- **Multivaluación**: Si se usa $\log z_1$ (multivaluado), se obtienen infinitos valores.  

#### **Tips clave**  
- **Exponente entero**: Si $z_2 \in \mathbb{Z}$, la exponencial es univaluada.  
- **Base real positiva**: Si $z_1 > 0$ (real), $\operatorname{Log} z_1 = \ln z_1$ y $z_1^{z_2} = e^{z_2 \ln z_1}$.  
- **Error común**: Usar argumento no principal (ej: $\varphi = \frac{3\pi}{2}$ en lugar de $-\frac{\pi}{2}$ para $-i$).  

---  
### **Ejemplo resuelto (11.14)**  
#### **Valor principal de $\left( \frac{1-i}{1+i} \right)^i$**  
1. **Simplificar la base**:  
   $$
   \frac{1-i}{1+i} = \frac{(1-i)^2}{(1+i)(1-i)} = \frac{1 - 2i - 1}{2} = -i.
   $$  
   Entonces $z = (-i)^i$.  

2. **Logaritmo principal de $-i$**:  
   - $|z| = 1$, $\operatorname{Arg}(-i) = -\frac{\pi}{2}$ (eje imaginario negativo).  
   $$
   \operatorname{Log}(-i) = \ln 1 + i \left(-\frac{\pi}{2}\right) = -i\frac{\pi}{2}.
   $$  

3. **Aplicar la definición**:  
   $$
   (-i)^i = e^{i \cdot \operatorname{Log}(-i)} = e^{i \cdot \left(-i \frac{\pi}{2}\right)} = e^{\frac{\pi}{2}}.
   $$  
   **Explicación**: $i \cdot (-i \frac{\pi}{2}) = -i^2 \frac{\pi}{2} = \frac{\pi}{2}$.  

**Resultado**: $\text{V.P. } z = e^{\pi/2}$.  

---

### **11.14 RAÍCES PRIMITIVAS DE LA UNIDAD**  
#### **Definición**  
- Las **raíces $n$-ésimas de la unidad** son:  
  $$
  w_k = \cos \frac{2k\pi}{n} + i \sin \frac{2k\pi}{n}, \quad k = 0, 1, \dots, n-1.
  $$  
- **Raíz primitiva de orden $n$**: Es una raíz $n$-ésima que **no** es raíz de orden $d < n$.  
  - **Condición**: $w_k$ es primitiva $\iff \gcd(k, n) = 1$.  

#### **Propiedades clave**  
1. **Número de raíces primitivas**: $\phi(n)$ (función phi de Euler).  
2. **Estructura de grupo**: Las raíces $n$-ésimas forman un grupo cíclico multiplicativo bajo la multiplicación.  
3. **Generadores**: Las raíces primitivas generan todas las raíces $n$-ésimas mediante potencias.  

#### **Ejemplo resuelto (11.15)**  
**Raíces primitivas de orden 6**:  
- Raíces 6-ésimas: $w_k = \cos \frac{2k\pi}{6} + i \sin \frac{2k\pi}{6}, \quad k = 0, 1, 2, 3, 4, 5$.  
- Valores de $k$ con $\gcd(k, 6) = 1$: $k = 1, 5$.  
- **Cálculo**:  
  - $w_1 = \cos \frac{\pi}{3} + i \sin \frac{\pi}{3} = \frac{1}{2} + i \frac{\sqrt{3}}{2}$,  
  - $w_5 = \cos \frac{5\pi}{3} + i \sin \frac{5\pi}{3} = \frac{1}{2} - i \frac{\sqrt{3}}{2}$.  

**Representación geométrica**:  
- Las 6 raíces forman un hexágono regular en la circunferencia unitaria.  
- Raíces primitivas: $w_1$ (60°) y $w_5$ (300°).  

```  
        w₁ (60°)      
          ●        
         / \       
        /   \      
       /     \     
  w₂ ●       ● w₀ (0°)  
      \     /      
       \   /       
        \ /        
         ● w₅ (300°)  
```  

#### **Tips**  
- **Identificación rápida**: $k$ y $n$ coprimos $\implies$ raíz primitiva.  
- **No primitivas**:  
  - $k = 0$: Siempre $w_0 = 1$ (raíz de orden 1).  
  - $k = 2, 3, 4$: $\gcd(k, 6) > 1$ → no primitivas.  
- **Aplicación**: Criptografía y polinomios ciclotómicos.  

---  
**Próximo apartado**: Indica el tema o continúa con la secuencia.
