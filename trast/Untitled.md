### B. Funciones

Ahora estudiamos un tipo especial de relación: las funciones.

Cuando \((a,b) \in f\), escribimos \(b = f(a)\), y a \(f(a)\) se le llama "f de a".

**Obs:** Es casi universal escribir \(f(a)\); sin embargo, hay algunos autores que escriben \(f a\). Es el caso de I.N. Herstein en su libro *Abstract Algebra*.

Según esta definición, las siguientes relaciones no son funciones (debido a que algún elemento del dominio no tiene imagen única o no tiene imagen):

- **Diagrama 1:**  
  \(A = \{e, 2, 3\}\),  
  \(B = \{2, 3, 20, 4\}\)  
  (ejemplo: si \(e\) se relaciona con múltiples elementos en \(B\)).

- **Diagrama 2:**  
  \(A = \{2, 3, 4\}\),  
  \(B = \{8\}\)  
  (ejemplo: si algún elemento de \(A\) no tiene imagen).

En cambio, las siguientes sí son funciones:

- **Diagrama 3:**  
  \(A = \{1, 2, 3\}\),  
  \(B = \{2\}\)  
  con \(f(a) = 2\) para todo \(a \in A\).

- **Diagrama 4:**  
  \(A = \{2, 3\}\),  
  \(B = \{2, 3\}\)  
  con \(f(2) = 2\) y \(f(3) = 3\).

Si \(f: A \to B\) es una función, el conjunto \(A\) se llama el **dominio** de \(f\), y al conjunto \(B\) se llama el **codominio** de \(f\). El subconjunto de \(B\) dado por \(R_f = \{b \in B : (\exists a \in A) \, (b = f(a))\}\) se llama el **recorrido** o **rango** de \(f\).

En álgebra, para determinar una función, debemos dar simultáneamente tres "datos":  
(i) el dominio;  
(ii) el codominio;  
(iii) la regla de correspondencia que indica cómo se asigna a cada elemento del dominio un elemento del codominio. Esto se hace mediante fórmulas algebraicas, diagramas de Venn o asignaciones explícitas.

Las funciones  
\[
f: \mathbb{R} \to \mathbb{R}, \, x \mapsto x^2 + 1
\]  
y  
\[
g: \mathbb{R} \to [-1, 1], \, x \mapsto \sin x
\]  
tienen el mismo conjunto de pares, pero no son idénticas, puesto que tienen distintos codominios. Son distintas funciones.

**Obs:** Cuando se define una función, escribimos \(f: w \mapsto y(w)\) para indicar la regla de correspondencia. El símbolo \(\mapsto\) se lee "se aplica a" o "mapea a".

Sea \(f: A \to B\), donde \(A = \{\alpha, \beta, \gamma, \delta, \epsilon\}\) y \(B = \{2, 3, 5, 7, 15\}\), la función dada por:  
\[
f(\alpha) = 2, \, f(\beta) = 3, \, f(\gamma) = 5, \, f(\delta) = 7, \, f(\epsilon) = 15.
\]

Las funciones se clasifican en tres:  
(i) **Inyectividad.** Sea \(f: A \to B\) una función; se dice que es **inyectiva** si para todo \(a, b \in A\), \(f(a) = f(b)\) implica \(a = b\). Equivalentemente, si \(a \neq b\) entonces \(f(a) \neq f(b)\).  
**Ej:** Sea \(f: \mathbb{R} \to \mathbb{R}\) dada por \(f(x) = x^2 + 1\). ¿Es inyectiva?  
**Solución:** No, no es inyectiva porque \(f(1) = 1^2 + 1 = 2\) y \(f(-1) = (-1)^2 + 1 = 2\), pese a que \(1 \neq -1\). Supongamos que \(f(a) = f(b)\), entonces \(a^2 + 1 = b^2 + 1 \Rightarrow a^2 = b^2 \Rightarrow (a - b)(a + b) = 0 \Rightarrow a = b\) o \(a = -b\). Como existe \(a \neq b\) con \(f(a) = f(b)\) (e.g., \(a = 1, b = -1\)), \(f\) no es inyectiva.  

**Ej:** Sea \(g: \mathbb{Q} \to \mathbb{Q}\) dada por \(g(q) = \frac{2 - 3q}{1 + 2q}\). ¿Es inyectiva?  
**Solución:** Supongamos que \(g(w) = g(v)\), entonces:  
\[
\frac{2 - 3w}{1 + 2w} = \frac{2 - 3v}{1 + 2v}
\]  
\[
(2 - 3w)(1 + 2v) = (2 - 3v)(1 + 2w)
\]  
\[
2 + 4v - 3w - 6vw = 2 + 4w - 3v - 6vw
\]  
\[
4v - 3w = 4w - 3v
\]  
\[
7v = 7w \Rightarrow v = w.
\]  
Por tanto, \(g\) es inyectiva.  

**Ej:** Sea \(h: (-\infty, \frac{2}{3}] \to \mathbb{R}\) dada por \(h(x) = \sqrt{2 - 3x} + 1\). ¿Es inyectiva?  
**Solución:** Supongamos \(h(a) = h(b)\), entonces:  
\[
\sqrt{2 - 3a} + 1 = \sqrt{2 - 3b} + 1 \Rightarrow \sqrt{2 - 3a} = \sqrt{2 - 3b}
\]  
\[
\Rightarrow 2 - 3a = 2 - 3b \Rightarrow -3a = -3b \Rightarrow a = b.
\]  
Por tanto, \(h\) es inyectiva.  

(ii) **Sobreyectividad** (también llamada *suryectividad* o *epiyectividad*).  
Sea \(g: A \to B\) una función, se dice que es **sobreyectiva** si \((\forall b \in B) \, (\exists a \in A) \, (b = g(a))\).  
Para chequear la sobreyectividad, hay que resolver la ecuación \(b = g(a)\) para "\(a\)" sin introducir restricciones nuevas implícita o explícitamente.  
Repetimos los ejemplos:  
**Ej:** \(f: \mathbb{R} \to \mathbb{R}\), \(x \mapsto x^2 + 1\). ¿Es sobreyectiva?  
**Solución:** Sea \(y = 0\), resolvemos \(0 = x^2 + 1 \Rightarrow x^2 = -1\), no tiene solución en \(\mathbb{R}\). Alternativamente, sea \(y \in \mathbb{R}\):  
\[
y = x^2 + 1 \Rightarrow x = \pm \sqrt{y - 1}, \text{ válido solo si } y - 1 \geq 0.
\]  
Para \(y < 1\), no hay solución. Por tanto, \(f\) no es sobreyectiva.  

**Ej:** \(g(q) = \frac{2 - 3q}{1 + 2q}\). ¿Es sobreyectiva? (asumiendo \(g: \mathbb{Q} \to \mathbb{Q}\))  
**Solución:** Resolvamos \(y = g(q)\):  
\[
y(1 + 2q) = 2 - 3q
\]  
\[
y + 2qy = 2 - 3q
\]  
\[
2qy + 3q = 2 - y
\]  
\[
q(2y + 3) = 2 - y
\]  
\[
q = \frac{2 - y}{2y + 3}, \quad \text{si } 2y + 3 \neq 0.
\]  
Si \(2y + 3 = 0\) (i.e., \(y = -\frac{3}{2}\)), la ecuación es \(0 \cdot q = 2 - (-\frac{3}{2}) = \frac{7}{2} \neq 0\), imposible. Luego, \(y = -\frac{3}{2}\) no tiene preimagen. Por tanto, \(g\) no es sobreyectiva.  

**Ej:** \(h: (-\infty, \frac{2}{3}] \to \mathbb{R}\), \(h(x) = \sqrt{2 - 3x} + 1\). ¿Es sobreyectiva?  
**Solución:** Sea \(z \in \mathbb{R}\), resolvemos \(z = \sqrt{2 - 3x} + 1\):  
\[
z - 1 = \sqrt{2 - 3x} \quad (\text{implica } z - 1 \geq 0)
\]  
\[
(z - 1)^2 = 2 - 3x
\]  
\[
x = \frac{2 - (z - 1)^2}{3}.
\]  
Para \(z = -2\), \(x = \frac{2 - (-3)^2}{3} = -\frac{7}{3}\), pero \(h(-\frac{7}{3}) = \sqrt{2 - 3(-\frac{7}{3})} + 1 = \sqrt{9} + 1 = 4 \neq -2\). La restricción \(z - 1 \geq 0\) (i.e., \(z \geq 1\)) limita el rango. Para \(z < 1\), no hay solución. Por tanto, \(h\) no es sobreyectiva.  

(iii) **Biyectividad.**  
Sea \(f: A \to B\) una función; se dice que es **biyectiva** si es, al mismo tiempo, inyectiva y sobreyectiva.  
**Ejemplos:**  
- \(f: \mathbb{R} \to \mathbb{R}\), \(x \mapsto x^2 + 1\) no es biyectiva (no inyectiva ni sobreyectiva).  
- \(g: \mathbb{Q} \to \mathbb{Q}\), \(g(q) = \frac{2 - 3q}{1 + 2q}\) es inyectiva pero no sobreyectiva (pues \(y = -\frac{3}{2}\) no está en el rango), luego no es biyectiva.  
- \(h: (-\infty, \frac{2}{3}] \to \mathbb{R}\), \(h(x) = \sqrt{2 - 3x} + 1\) es inyectiva pero no sobreyectiva (rango \([1, \infty)\)), luego no es biyectiva.  

Al igual que con las relaciones, la única operación "natural" entre funciones es la **composición**. Recordemos: Sean \(R \subseteq A \times B\) y \(S \subseteq B \times C\) dos relaciones, su composición es  
\[
S \circ R = \{(a, c) : (\exists b \in B) \, (a \, R \, b \land b \, S \, c)\}.
\]  
Para que \(S \circ R \neq \varnothing\), debe darse que el rango de \(R\) esté contenido en el dominio de \(S\).  

Ahora, sean \(f: A \to B\) y \(g: B \to C\). Como el rango de \(f\) está contenido en \(B =\) dominio de \(g\), la composición siempre existe, y obtenemos una función:  
\[
g \circ f: A \to C, \quad (g \circ f)(x) = g(f(x)).
\]  
Además, si escribimos \((x)f\) en lugar de \(f(x)\), entonces la composición se escribe \((x)(g \circ f) = ((x)f)g\). El símbolo \(g \circ f\) se lee "\(g\) compuesta con \(f\)".  

Supongamos que \(g \circ f\) y \(f \circ g\) existen ambas; no siempre son iguales.  
**Ej:** Sean \(f, g: \mathbb{R} \to \mathbb{R}\) dadas por \(f(x) = x^2\), \(g(x) = \sqrt{x}\) (con dominio \(x \geq 0\) para \(g\)). Entonces:  
\[
(g \circ f)(x) = g(f(x)) = g(x^2) = \sqrt{x^2} = |x|,
\]  
\[
(f \circ g)(x) = f(g(x)) = f(\sqrt{x}) = (\sqrt{x})^2 = x \quad (x \geq 0).
\]  
Así, \(g \circ f \neq f \circ g\).  

Sin embargo, es fácil demostrar que la composición de funciones es asociativa:  
\[
h \circ (g \circ f) = (h \circ g) \circ f.
\]  
También es fácil demostrar que para \(f: A \to B\) y \(g: B \to C\):  
(i) Si \(f\) y \(g\) son inyectivas, entonces \(g \circ f\) es inyectiva.  
(ii) Si \(f\) y \(g\) son sobreyectivas, entonces \(g \circ f\) es sobreyectiva.  
(iii) Si \(f\) y \(g\) son biyectivas, entonces \(g \circ f\) es biyectiva.  

Dada una función \(f: A \to B\), ¿es su relación inversa \(f^{-1} \subseteq B \times A\) una función?  
- Si \(f\) es solo inyectiva (no sobreyectiva):  
  \[
  A = \{a_1, a_2, a_3\}, \quad B = \{1, 2, 3, 4\}, \quad f(a_1) = 1, \, f(a_2) = 2, \, f(a_3) = 3.
  \]  
  Relación inversa: \(1 \mapsto a_1\), \(2 \mapsto a_2\), \(3 \mapsto a_3\), pero \(4\) no tiene preimagen. **No es función.**  
- Si \(f\) es solo sobreyectiva (no inyectiva):  
  \[
  A = \{5, -2, 3\}, \quad B = \{2, 3\}, \quad f(5) = 2, \, f(-2) = 3, \, f(3) = 2.
  \]  
  Relación inversa: \(2 \mapsto 5\) o \(3\), \(3 \mapsto -2\); no única. **No es función.**  
- Si \(f\) es biyectiva:  
  \[
  A = \{a, b, c\}, \quad B = \{2, 3, 5\}, \quad f(a) = 2, \, f(b) = 3, \, f(c) = 5.
  \]  
  Relación inversa: \(2 \mapsto a\), \(3 \mapsto b\), \(5 \mapsto c\). Es una función biyectiva.  

Entonces, sea \(f: A \to B\) una función; decimos que \(f\) es **invertible** si existe \(g: B \to A\) tal que \(g \circ f = \text{id}_A\) y \(f \circ g = \text{id}_B\). Cuando \(g\) existe, es única y se llama la **inversa** de \(f\), denotada por \(f^{-1}\). Para calcular \(f^{-1}\), resolvemos en \(x\) la ecuación \(y = f(x)\).  

Se debe demostrar que \(f\) es invertible si y solo si es biyectiva.  
**Ej:** Si \(f\) no es sobreyectiva (e.g., dominio \(A = \{0, -1\}\), codominio \(B = \{1, 2, 3\}\), \(f(0) = 1\), \(f(-1) = 2\)), entonces no es biyectiva y no es invertible.  

De los tres ejemplos anteriores, solo \(g: \mathbb{Q} \setminus \{-\frac{1}{2}\} \to \mathbb{Q} \setminus \{-\frac{3}{2}\}\) dada por \(g(q) = \frac{2 - 3q}{1 + 2q}\) es biyectiva (al restringir dominio y codominio). Al chequear la sobreyectividad, hemos resuelto \(w = g(q)\):  
\[
w = \frac{2 - 3q}{1 + 2q} \Rightarrow q = \frac{2 - w}{2w + 3}.
\]  
Esta igualdad da la fórmula de la inversa:  
\[
g^{-1}(w) = \frac{2 - w}{2w + 3}, \quad \text{o} \quad g^{-1}(q) = \frac{2 - q}{2q + 3}.
\]  
Verifique la composición:  
\[
(g \circ g^{-1})(q) = g\left(g^{-1}(q)\right) = g\left(\frac{2 - q}{2q + 3}\right) = \frac{2 - 3 \cdot \frac{2 - q}{2q + 3}}{1 + 2 \cdot \frac{2 - q}{2q + 3}} = \frac{\frac{2(2q + 3) - 3(2 - q)}{2q + 3}}{\frac{(2q + 3) + 2(2 - q)}{2q + 3}} = \frac{4q + 6 - 6 + 3q}{2q + 3 + 4 - 2q} = \frac{7q}{7} = q.
\]  

### Propiedades de imagen y preimagen
Dada una función \(f: X \to Y\), obtenemos dos funciones inducidas:  
\[
f_*: \mathcal{P}(X) \to \mathcal{P}(Y), \quad f_*(A) = f(A) = \{f(a) : a \in A\} \quad (\text{imagen de } A),
\]  
\[
f^*: \mathcal{P}(Y) \to \mathcal{P}(X), \quad f^*(B) = f^{-1}(B) = \{x \in X : f(x) \in B\} \quad (\text{preimagen de } B).
\]  
**Obs:** Aunque se usa \(f^{-1}\), no implica que \(f\) sea invertible. Para \(B = \{y\}\), escribimos \(f^{-1}(y) = \{x \in X : f(x) = y\}\) (fibra de \(y\)).  

**Ej:** Sea \(g: \mathbb{Z} \to \mathbb{Z}\) dada por \(g(n) = n^2\).  
- Si \(A = \{1, -3, 0, 11\}\), entonces \(g(A) = \{1, 9, 0, 121\}\).  
- Si \(B = \{0, 9, 3\}\), entonces \(g^{-1}(B) = \{0, 3, -3\}\).  
- Si \(B_1 = \{3, 5, 7\}\), entonces \(g^{-1}(B_1) = \varnothing\).  

**Ej:** Sea \(h: \mathbb{R} \to \mathbb{R}\) dada por \(h(x) = |x + 1|\).  
- Si \(A = [-2, 3]\), entonces \(h(A) = [0, 4]\).  
- Si \(B = (-2, -1)\), entonces \(h^{-1}(B) = \varnothing\).  
- Si \(B_0 = (1, 3)\), entonces \(h^{-1}(B_0) = (-4, -2) \cup (0, 2)\).  

**Obs:** Sean \(f: A \to B\) y \(g: B \to C\) funciones. Es fácil demostrar que:  
\[
(g \circ f)_* = g_* \circ f_*, \quad \text{pero} \quad (g \circ f)^* = f^* \circ g^*.
\]  

#### Propiedades de la imagen:
(i) \(A \subseteq B \subseteq X \Rightarrow f(A) \subseteq f(B)\).  
(ii) \(f(A \cup B) = f(A) \cup f(B)\).  
(iii) \(f(A \cap B) \subseteq f(A) \cap f(B)\) (en general, no igual).  
**Contraejemplo:** Sea \(g: \mathbb{Z} \to \mathbb{Z}\), \(g(x) = x^2\); \(A = \{-2, -3, 4\}\), \(B = \{2, 3, 4, 5\}\):  
\[
g(A) = \{4, 9, 16\}, \quad g(B) = \{4, 9, 16, 25\}, \quad g(A) \cap g(B) = \{4, 9, 16\},
\]  
\[
g(A \cap B) = g(\{4\}) = \{16\} \neq g(A) \cap g(B).
\]  

#### Propiedades de la preimagen:
Para \(W, V \subseteq Y\):  
(i) \(f^{-1}(W \cup V) = f^{-1}(W) \cup f^{-1}(V)\).  
(ii) \(f^{-1}(W \cap V) = f^{-1}(W) \cap f^{-1}(V)\).  
(iii) \(f^{-1}(W^c) = \left[f^{-1}(W)\right]^c\).  
**Demostración (iii):**  
\[
x \in f^{-1}(W^c) \Leftrightarrow f(x) \in W^c \Leftrightarrow f(x) \notin W \Leftrightarrow x \notin f^{-1}(W) \Leftrightarrow x \in \left[f^{-1}(W)\right]^c.
\]

