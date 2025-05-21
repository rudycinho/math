# Logica Basica
A la mayoría de la gente le gusta pensar que son lógicos.
Decirle a alguien "No estas siendo lógico" es habitualmente una forma de critica. Ser ilógico es estar confundido, o ser irracional.
Pero, que es la lógica? En Alicia en el Pais de las Maravillas podemos leer:
> "Por el contrario! Si hubiese sido así, entonces lo seria; y siéndolo, quizá, lo fuera, pero como no fue así, tampoco lo es asa. Es lógico!"

En esta parodia, Tweedledee esta razonando. Y de eso trata la lógica.
Todos razonamos. Intentamos averiguar que es lo que pasa, razonando sobre la base de lo que ya sabemos. Tratamos de persuadir a otros de que algo es así dándoles razones.

Debemos entender esta afirmación en cierta forma. He aquí dos ejemplos - los lógicos las llaman inferencias.
Ej 
(1) Roma es la capital de Italia, y este avion aterriza en Roma; entonces el avion aterriza en Italia.
(2) Moscu es la capital de EEUU; entonces no podemos ir a Moscu sin ir a EEUU. $\quad\blacksquare$
En cada caso, las afirmaciones antes del "entonces" - los llamamos **premisas** - son las razones dadas, la afirmación después del 'entonces' - la llamamos conclusion - es el porque de las razones.
La primera inferencia esta bien, pero, la segunda es irremediable.
A la lógica le interesa si la conclusion se sigue a partir de las premisas.
No le interesa si las premisas de un inferencia son ciertas o falsas, eso es problema de otra persona.
Una inferencia donde la conclusion en verdad se sigue a partir de las premisas, se llama **valida**. Entonces el objetivo central de la lógica es entender la **validez**.
Debemos distinguir entre dos tipos diferentes de validez. Condensamos las siguientes tres inferencias.
Ej 
(1) Si el ladrón hubiese entrado por la ventana de la cocina, habría huellas de pisadas afuera; entonces el ladrón no entro por la ventana de la  cocina.
(2) Juan tiene los dientes tenidos de amarillo; entonces Juan es un fumador.
(3) Juan compra dos cajetillas de cigarrillos al dia; entonces alguien deja huellas de pisadas a fuera de la ventana de la cocina $\qquad \blacksquare$
La primera inferencia es muy directa.
Si las premisas son ciertas, también debe serlo la conclusion. O, dicho de otra forma, las premisas no podrían ser ciertas sin que la conclusion también lo sea. Llamamos a este tipo de inferencia, **deductivamente  valida** [^1].
La segunda es un poco diferente. La premisa claramente da una buena razón para la conclusion, pero no es completamente concluyente: Juan pudo simplemente tenir sus dientes por hacer creer a la gente que un fumador. Entonces no se trata de una inferencia **deductivamente valida**.
Obs .- La **validez inductiva** [^2] es una noción muy importante . Razonamos inductivamente todo el tiempo; por ejemplo; al intentar resolver problemas como "por que se descompuso al carro?", "por que una persona esta enferma?" o "quien cometió un crimen?" Pese a esto, históricamente, se ha dedicado mucho mas esfuerzo a comprender la validez deductiva - tal vez por que los lógicos han tendido a ser filósofos o matemáticos, y no medicos o detectives  $\qquad \blacksquare$
Nos concentraremos en la validez deductiva. Salvo que se diga lo contrario, "valido" simplemente significara "deductivamente valido".

Entonces, que es una inferencia valida? Vimos que, donde las premisas no pueden ser ciertas sin que la conclusion también lo sea. Pero, que quiere decir esto? En particular, que quiere decir el "no pueden"? En general "no puede(n)" puede significar muchas cosas diferentes. Consideremos, por ejemplo: "Maria puede tocar el piano, pero Juan no puede"; aquí estamos hablando de una habilidad humana. Compare con "No puede entrar aquí, necesitas un permiso"; aquí estamos hablando de posibilidad que algún código de reglas permite. 
En nuestro caso, en natural entender el "no puede(n)" relevante en la siguiente forma: decir que las premisas no pueden ser ciertas sin que la conclusion sea cierta es decir que en todas las situaciones en las cuales las premisas son ciertas; también lo es la conclusion. 
Hasta ahora, todo bien; pero, que, exactamente, es una situación? Que tipo de cosas las componen, y como estas cosas se relacionan unas con otras?. Y, que es ser "verdad"? Como se puede saber que es cierto en **todas** las situaciones? Es imposible examinar todas las situaciones.
En lo que nos toca el discurso científico es la forma de comunicar contenidos científicos a través de un texto técnico. Se caracteriza por ser objetivo, expósito, impersonal y universal. El discurso científico se construye con un lenguaje especializado, preciso, formal y literal. Se utiliza para expresar descubrimientos, teorías, hipótesis, estudios, análisis y técnicas.
Todo desarrollo matemático exige razonar en forma valida acerca de cosas trascendentales y particularmente abstractas. Hay que comenzar por eliminar las ambigüedades del lenguaje ordinario, con símbolos cuyo uso descarta las contingencias, aparta la claridad y economía de pensamiento.
Recordemos que a la lógica propiamente no le interesa si las premisas o la conclusion son verdades o falsas; lo único que interesa es la validez del argumento.
Obs.- Antes de entrar en detalles cabe una aclaración. Estudiaremos lo que suele llamarse **lógica aristotélica** o **lógica binarias**; esto quiere decir que tenemos solo dos **valores de verdad**, a saber verdadero $(V/1)$ y falso $(F/0)$. Existe desde luego, **lógicas no binarias** que pueden tener infinitos valores de verdad. $\quad\blacksquare$
En una inferencia, las premisas y la conclusion son afirmaciones sobre objetos dados. Requerimos que estas afirmaciones sean de tal forma que podamos decir si son **verdaderas** o **falsas**. A estas afirmaciones las llamamos **proporciones**.
Ej
1. p: "El numero 6 es par"
2. q: "El numero 8 es primo"
son proposiciones. Pero
1. "Manana tal ves estudie"
2. "Scarlet Johansson es la mujer mas hermosa del mundo"
no son proposiciones. [^3]

Como con los números y sus operaciones (aritméticas), dadas dos proposiciones p, q podemos construir a partir de ellas nuevas proposiciones usando **operaciones** (lógicas). Las operaciones que consideramos son las siguientes:
### Negación
Dada una proposición p, su **negación** se escribe $\neg p$ y se lee "no p".
Ej:
$p$ : "7 es un numero primo".
$\neg p$ : "7 no es un numero primo". $\quad\blacksquare$
### Conjunción
Dadas dos proposiciones p, q, su **conjunción** se escribe $p \wedge q$ y se lee "p y q"
Ej: 
$w$ : "Juan estudia leyes".
$q$ : "Juan trabaja de mesero".
$w \wedge q$ : "Juan estudia leyes y trabaja de mesero." $\quad\blacksquare$
### Disyunción
Dadas dos proposiciones p, q su **disyunción** se escribe $p \vee q$ y se lee "p o q".
Ej:
$p$ : "x es un numero entero par".
$q$ : "x es un entero impar".
$p \vee q$ : "x es un numero par o impar" $\quad\blacksquare$
### Implicación
Dadas dos proposiciones p, q, la **implicación** $p \Rightarrow q$ y se lee "p implica q" o "si p, entonces q" o "q se sigue de p" o "q, si p".
Ej.
$p$ : "x es un numero impar".
$q$ : "$x^2$ es un numero impar".
$p \Rightarrow q$ : "si $x$ es un numero entero impar, entonces $x^2$ también lo es" $\quad\blacksquare$
### Equivalencia
Dadas dos proposiciones p, q, decimos que son **equivalentes** escribiendo $p \Leftrightarrow q$ o $p \equiv q$ que se lee "p es equivalente a q" o "p si y solo si q".
Ej.
$p \Leftrightarrow q$ : "$x$ es un entero impar si y solo si $x^2$ es un entero impar" $\quad\blacksquare$

Las proposiciones que se obtienen a partir de estas operaciones, suelen llamarse **compuestas**. Para determinar el valor de verdad de una proposición compuesta usamos las siguientes definiciones (tablas).

| $p$ | $\neg\; p$ |
| --- | ---------- |
| V   | F          |
| F   | V          |

| $p$ | $q$ | $p \wedge q$ | $p \vee q$ | $p \Rightarrow q$ | $p \Leftrightarrow q$ |
| --- | --- | ------------ | ---------- | ----------------- | --------------------- |
| V   | V   | V            | V          | V                 | V                     |
| V   | F   | F            | V          | F                 | F                     |
| F   | V   | F            | V          | V                 | F                     |
| F   | F   | F            | F          | V                 | V                     |

Obs. En general, si tenemos n proposiciones, sus valores de verdad se combinan en $2^n$ posibilidades.

![[Pasted image 20250218012540.png]] $\quad\blacksquare$

Si una proposición compuesta $P(p_1,\dots , p_n)$ es siempre verdadera (independientemente de los valores de verdad de $p_1,\dots , p_n$ ), decimos que $P$ es una **tautología** o **ley lógica**. Por otro lado, si es siempre falsa decimos que es una **contradicción**. Finalmente si es a veces verdadera y a veces falsa, decimos que es una **contingencia**.

Observación.
Al igual que las operaciones algebraicas, las "operaciones lógicas" también tiene niveles de precedencia. A saber 

| operador          | precedencia |     |
| ----------------- | ----------- | --- |
| $\neg$            | $1$         |     |
| $\wedge$          | $2$         |     |
| $\vee$            | $3$         |     |
| $\Rightarrow$     | $4$         |     |
| $\Leftrightarrow$ | $5$         |     |

[^4]
$$\blacksquare$$



Las proposiciones compuestas $P$ y $Q$ se llama **lógicamente equivalentes** si $P \Leftrightarrow Q$ es una tautologia. En este caso escribimos $P \equiv Q$.

Algunas equivalencias importantes son las siguiente:

| equivalencia                                               | nombre                |     |
| ---------------------------------------------------------- | --------------------- | --- |
| $p \wedge \mathbb V \equiv p$                              | Leyes de identidad    |     |
| $p \vee   \mathbb F \equiv p$                              |                       |     |
| $p \vee   \mathbb V \equiv \mathbb V$                      | Leyes de dominación   |     |
| $p \wedge \mathbb F \equiv \mathbb F$                      |                       |     |
| $p \vee   p \equiv p$                                      | Leyes de idempotencia |     |
| $p \wedge   p \equiv p$                                    |                       |     |
| $\neg ( \neg p ) \equiv p$                                 | Ley de doble negación |     |
| $p \vee q \equiv q \vee p$                                 | Leyes conmutativas    |     |
| $p \wedge q \equiv q \wedge p$                             |                       |     |
| $(p \vee q) \vee r \equiv p \vee (q \vee r)$               | Leyes asociativas     |     |
| $(p \wedge q) \wedge r \equiv p \wedge (q \wedge r)$       |                       |     |
| $p \vee (q \wedge r) \equiv (p \vee q) \wedge (p\vee r)$   | Leyes distributivas   |     |
| $p \wedge (q \vee r) \equiv (p \wedge q) \vee (p\wedge r)$ | factorizacion         |     |
| $\neg(p \wedge q) \equiv \neg p \vee \neg q$               | Leyes de DeMorgan     |     |
| $\neg(p \vee   q) \equiv \neg p \wedge \neg q$             |                       |     |
| $p \vee (p \wedge q) \equiv p$                             | Leyes de absorción    |     |
| $p \wedge (p \vee q) \equiv p$                             |                       |     |
| $p \vee \neg p \equiv \mathbb V$                           | Leyes de negación     |     |
| $p \wedge \neg p \equiv \mathbb F$                         |                       |     |


Ejemplo.
Demostrar que
$$\neg ( p \vee (\neg p \wedge q)) \equiv \neg p \wedge \neg q$$

Solucion.
Una forma, la mas "simple" y aburrida es hacer la tabla de verdad de
$$\neg ( p \vee (\neg p \wedge q)) \Leftrightarrow \neg p \wedge \neg q$$
y obtener una tautologia.
La segunda forma, mas interesante, de "demostrar" la equivalencia:

$$
	\begin{aligned}
		\neg ( p \vee (\neg p \wedge q)) \; \equiv & \; \neg p \wedge \neg (\neg p \wedge q) & \text{DeMorgan}\\
		\equiv & \; \neg p \wedge (\neg \neg p \vee \neg q) & \text{DeMorgan}\\
		\equiv & \; \neg p \wedge (p \vee \neg q) & \text{Doble Negacion}\\
		\equiv & \; (\neg p \wedge p) \vee ( \neg p \wedge \neg q) & \text{Distributiva}\\
		\equiv & \; \mathbb F \vee ( \neg p \wedge \neg q) & \text{Negacion}\\
		\equiv & \; \neg p \wedge \neg q & \text{Identidad}\\
		& & \blacksquare
	\end{aligned}
$$

Ejemplo.
Mostrar que $(p \wedge q) \Rightarrow (p \vee q)$ es una tautologia.
$$
	\begin{aligned}
		(p \wedge q) \Rightarrow (p \vee q) \; \equiv & \; \neg (p \wedge q) \vee (p \vee q) & \text{Definicion Condicional}\\
		\equiv & \; (\neg p \vee \neg q) \vee (p \vee q) & \text{DeMorgan}\\
		\equiv & \; (\neg p \vee p) \vee (\neg q \vee q) & \text{Asociativa}\\
		\equiv & \; \mathbb V \vee \mathbb V & \text{Idempotencia}\\
		\equiv & \; \mathbb V \\
	\end{aligned}
$$
[^5]

## La implicación.
Debido a su importancia, retomamos un poco la implicación. Su importancia se debe a que **todos** los teoremas en matemáticas son de la forma
$$ p \Rightarrow q $$
alguna variante de esto:
$$
p \Rightarrow (q \vee r) \;;\;
p \Rightarrow (q \wedge r) \;;\;
p \Leftrightarrow q 
$$

En la implicación $p \Rightarrow q$, $p$ se llama el **antecedente** y $q$ el **consecuente**, a p también se le llama **hipótesis** y a q **tesis**.

$$\underbrace{p}_{\text{antecedente o hiposetes}}\Rightarrow \underbrace{q}_{\text{consecuente o tesis}}$$

Analizando la tabla de verdad de la implicación

| $p$      | $q$ | $p\Rightarrow q$ |
| -------- | --- | ---------------- |
| $V$      | $V$ | $V$              |
| $V$      | $F$ | $F$              |
| $F$ [^6] | $V$ | $V$              |
| $F$ [^6] | $F$ | $V$              |

notamos lo siguiente:
- i. si $p\Rightarrow q$ es $V$ y $p$ es $V$, entonces $q$ es $V$; decimos entonces que el antecedente es **condición suficiente** para el consecuente;
- ii. si $p$ es $F$, nada podemos decir del consecuente;
- iii. cuando $p\Rightarrow q$ es $V$, si $q$ es $V$, entonces nada podemos decir del antecedente; en cambio, para que $p$ sea $V$ es necesario que $q$ lo sea. Decimos entonces que el consecuente es **condición necesaria** para el antecedente.

Resumiendo, si $p \Rightarrow q$ es $V$, entonces $p$ es condición suficiente para $q$ y $q$ es condición necesaria para $p$.[^7]

Hay muchas formas de expresar la implicación $p \Rightarrow q$:
- **Si $p$, entonces $q$**
- **Si $p$, $q$**
- **$p$ implica $q$**
- **$p$ solo si $q$**
- $p$ es suficiente para $q$
- $q$ si $p$
- $q$ cuando $p$
- una condición necesaria para $p$ es $q$
- $q$ a menos que $\neg p$
- una condición suficiente para $q$ es $p$
- $q$ siempre que $p$
- $q$ es necesario para $p$
- $q$ se sigue de $p$

La implicación $p \Rightarrow q$ tiene otras tres implicaciones asociadas.

![[Pasted image 20250221001944.png]]

Es fácil verificar que las implicaciones contrareciprocas son equivalentes.

| $p$ | $\Rightarrow$ | $q$ | $\Leftrightarrow$ | $\neg q$ | $\Rightarrow$ | $\neg p$ |
| --- | ------------- | --- | ----------------- | -------- | ------------- | -------- |
| V   | V             | V   | V                 | F        | V             | F        |
| V   | F             | F   | V                 | V        | F             | F        |
| F   | V             | V   | V                 | F        | V             | V        |
| F   | V             | F   | V                 | V        | V             | V        |

He aquí algunas equivalencias importantes:
- $p \Rightarrow q \equiv \neg p \vee q$
- $\boxed{p \Rightarrow ( q \wedge r) \equiv (p \Rightarrow q) \wedge (p \Rightarrow r)}$
- $p \Rightarrow q \equiv \neg q \Rightarrow \neg p$
- $p \vee q \equiv \neg p \Rightarrow q$
- $p \wedge q \equiv \neg (p \Rightarrow \neg q)$  método de contradicción
- $\neg (p \Rightarrow q) \equiv p \wedge \neg q$  
- $(p \vee q) \Rightarrow r \equiv (p \Rightarrow q) \wedge (q \Rightarrow r)$
- $p \Rightarrow (q \vee r) \equiv (p \Rightarrow q) \vee (p \Rightarrow r)$
- $\boxed{p \Rightarrow (q \vee r) \equiv (p \wedge \neg q) \Rightarrow r}$
- $(p \wedge q) \Rightarrow r \equiv (p \Rightarrow r) \vee (q \Rightarrow r)$


$$
	\begin{align}
		p \Rightarrow (q \wedge r) &\equiv \neg p \vee (q \wedge r)\\
		&\equiv (\neg p \vee q)  \wedge (\neg p \vee r)\\
		&\equiv (p \Rightarrow q)  \wedge (p \Rightarrow r)\\
	\end{align} 
$$


$$
	\begin{align}
		p \Rightarrow (q \vee r) &\equiv \neg p \vee (q \vee r)\\
		&\equiv (\neg p \vee q)  \vee r\\
		&\equiv (\neg p \vee \neg \neg q)  \vee r\\
		&\equiv \neg ( p \wedge \neg q)  \vee r\\
		&\equiv ( p \wedge \neg q)  \Rightarrow r\\
	\end{align}
$$

$$
	\begin{align}
		p \Rightarrow (q \vee r) &\equiv  \neg p \vee (r \vee q)\\
		&\equiv (\neg p \vee r)  \vee q\\
		&\equiv (\neg p \vee \neg \neg r)  \vee q\\
		&\equiv \neg ( p \wedge \neg r)  \vee q\\
		&\equiv ( p \wedge \neg r)  \Rightarrow q\\
	\end{align}
$$


$p \Leftrightarrow q \equiv  (p \Rightarrow q) \wedge (q \Rightarrow p)$
$p \Leftrightarrow q \equiv  \neg p \Leftrightarrow \neg q$
$p \Leftrightarrow q \equiv  (p \wedge q) \vee (\neg p \wedge \neg q)$
$\neg (p \Leftrightarrow q) \equiv  p \Leftrightarrow \neg q$

## Inferencias, razonamiento deductivo valido
Retomamos las inferencias. En matemáticas nos interesa el tipo de razonamiento llamado **deductivo**. Recordemos que una inferencia esta compuesta por un conjunto finito $\{p_1,p_2,\dots,p_n\}$ de proposiciones llamadas **premisas**, y una proposición $q$ llamada **conclusion**. Escribimos una inferencia de la siguiente forma:

$$
\begin{array}{c}
    \text{premisas } \left\{
        \begin{array}{c}
            p_1 \\
            p_2 \\
            \vdots \\
            p_n \\
        \end{array} 
    \right. \\
    \hline			
    && \left. \underbrace{\therefore}_{\text{entonces}} q  \quad \right\} \quad \text{conclusion}
\end{array}
$$

![[Pasted image 20250307110433.png]]

Como sabemos si esta inferencia es valida? Hay dos formas de hacerlo. La primera es fácil (y aburrida): para verificar la validez de la inferencia basta verificar que $$(p_1 \wedge p_2 \wedge \dots \wedge p_n) \Rightarrow q$$ es una tautologia.

Ej.
Verificar la validez de la siguiente inferencia

$$
\begin{array}{l}
	\text{1.}\quad p\Rightarrow q \\
    \text{2.}\quad \neg r \Rightarrow \neg q \\
    \text{3.}\quad \neg (\neg p \Rightarrow \neg t )\\
    \text{4.}\quad t\Rightarrow s \\
	\text{5.}\quad \neg r \\
    \hline
    & \therefore s
\end{array}
$$

![[Pasted image 20250307110712.png]]

Por tanto, es una tautologia, lo que quiere decir que la inferencia valida. $\qquad \blacksquare$

Veamos
Ej. Mostrar que la siguiente inferencia es válida:

$$
\begin{array}{l}
	\text{1. }& x>5 \Rightarrow x=6 \vee x>6 \\
	\text{2. }& x\neq 5 \wedge x \not< 5 \Rightarrow x>5 \\
	\text{3. }& x<5 \Rightarrow x \neq 3+4 \\
	\text{4. }& x=3+4 \wedge x \neq 6 \\
	\text{5. }& x=3+4 \Rightarrow x \neq5 \\
	\hline
	&&\therefore x > 6
\end{array}
$$


Solucion.
Debemos mostrar que la siguiente implicación es una tautologia

![[Pasted image 20250225202806.png]]

La segunda opción para verificar la validez de una inferencia es mucho más interesante: **hay que demostrar la inferencia!**

Pero, ¿qué es una "Demostración"? 
Una **demostración** es una sucesión finita

$$
	q_1, q_2, \dots q_m \qquad (1)
$$

tal que cada una de ellas se ha obtenido mediante una "regla de inferencia" aplicada a una o más premisas o a proposiciones anteriores de la misma sucesión (1), y tal que la ultima proposición de la sucesión es la conclusión de la inferencia, i. e. $q_m=q$.
[^8]

Y, qué es una "regla de inferencia"? 
Una **regla de inferencia** es todo esquema válido de razonamiento; son tautologias que "trasforman proposiciones verdaderas en proposiciones tambien verdaderas. Con estas reglas de inferencia, obtenemos otras proposiciones - pero de una forma diferente que con las operaciones lógicas ya vistas.

El paso lógico de los premisas a la conclusión es una **deducción**[^9] o **demostración**. La conclusión que se obtiene se dice que es una **consecuencia lógica** de las premisas si cada paso que se da para llegar a la conclusión esta permitido por una regla.

Las principales reglas de inferencia son:

a. Modus Ponendo Ponens (MPP)[^10]
$$
\begin{array}{l}
p \Rightarrow q \\
p \\
\hline
q
\end{array}
$$

b. Modus Tollendo Tollens (MTT)[^11]
$$
\begin{array}{l}
p \Rightarrow q \\
\neg q \\
\hline
\neg p
\end{array}
$$

c. Ley del Silogismo Hipotetico (LSH)
$$
\begin{array}{l}
p \Rightarrow q \\
q \Rightarrow r \\
\hline
p \Rightarrow r \\

\end{array}
$$
d. Modus Tollendo Ponens (MTP)[^12]

$$
\begin{array}{l}
p \vee q \\
\neg p \\
\hline
q
\end{array}
$$
$$
\begin{array}{l}
p \vee q \\
\neg q \\
\hline
p
\end{array}
$$

e. Regla de Simplicacion (RS)
$$
\begin{array}{l}
p \wedge q \\
\hline
p
\end{array}
$$
$$
\begin{array}{l}
p \wedge q \\
\hline
q
\end{array}
$$
f. Regla de Adjuncion
$$
\begin{array}{l}
p \\
q \\
\hline
p \wedge q
\end{array}
$$
g. Ley condicional (LC)
$$
\begin{array}{l}
p \Rightarrow q \\
\hline
\neg p \vee q
\end{array}
$$
$$
\begin{array}{l}
\neg p \vee q \\ 
\hline
p \Rightarrow q
\end{array}
$$
h. Leyes de DeMorgan (LdDM)
$$
\begin{array}{l}
\neg (p \wedge q) \\
\hline
\neg p \vee \neg q \\
\end{array}
$$
$$
\begin{array}{l}
\neg (p \vee q) \\
\hline
\neg p \wedge \neg q \\
\end{array}
$$
i. Ley del silogismo disyuntivo (LSD)
$$
\begin{array}{l}
p \vee r \\ 
p \Rightarrow q \\
r \Rightarrow s \\
\hline
q \vee s \\ 
\end{array}
$$
j. Ley de la contrareciproca (LdC)
$$
\begin{array}{l}
p \Rightarrow q \\
\hline
\neg q \Rightarrow \neg p   \\
\end{array}
$$

k. Ley de la doble negacion (LDN)
$$
\begin{array}{l}
\neg \neg p\\
\hline
p   \\
\end{array}
$$
$$
\begin{array}{l}
p   \\
\hline
\neg \neg p\\
\end{array}
$$
l. Ley de la bicondicional (LdB)

$$
\begin{array}{l}
p \Rightarrow q \\
q \Rightarrow p \\
\hline
p \Leftrightarrow q \\
\end{array}
$$

$$
\begin{array}{c}
p \Leftrightarrow q \\
\hline
(p \Rightarrow q) \wedge (q \Rightarrow p) \\
\end{array}
$$


m. Simplificacion disyuntiva (SD)
$$
\begin{array}{c}
p \vee p \\
\hline
p 
\end{array}
$$

n. Ley de la adicion
$$
\begin{array}{c}
p\\
\hline
p \vee q 
\end{array}
$$


Ejemplo.
Demostrar la siguiente inferencia

$$
\begin{array}{l}
1. & p \Rightarrow q\\
2. & \neg r \Rightarrow \neg q\\
3. & \neg (\neg p \wedge \neg t)\\
4. & t \Rightarrow s\\
5. & \neg r\\
\hline
&&& \therefore s \\
6. & \neg \neg p \vee \neg \neg t & \text{[LdDM 3]}\\
7. & p \vee t & \text{[LDN 6]} \\
8. & \neg q & \text{[MPP 2,5]} \\
9. & \neg p & \text{[MTT 1,8]} \\
10.& t& \text{[MTP 7,9]} \\
11.& s& \text{[MPP 4,10]}  & \blacksquare \\
\end{array}
$$
[^13]

Ejemplo
Demostrar la siguiente inferencia:

$$
\begin{array}{l}
1. & x>5 \Rightarrow x=6 \vee x>6 \\
2. & x\neq 5 \wedge x \not < 5 \Rightarrow x>5 \\
3. & x<5 \Rightarrow x\neq 3+4 \\
4. & x=3+4 \wedge x\neq 6 \\
5. & x=3+4 \Rightarrow x\neq 5 \\
\hline
&&& \therefore x > 6\\
6. & x=3+4 & \text{[RS 4]} \\
7. & \neg (x\neq3+4) & \text{[LDN 6]} \\
8. & x \not < 5 & \text{[MTT 3,7]} \\
9. & x \neq 5 & \text{[MPP 5,6]} \\
10. & x \neq 5 \wedge x\not < 5 & \text{[R Adj 9,8]} \\
11. & x>5 & \text{[MPP 2,10]} \\
12. & x=6 \vee x>6 & \text{[MPP 1,11]} \\
13. & x \neq 6 & \text{[RS 4]} \\
14. & x>6 & \text{[MTP 12,13]} &\blacksquare \\
\end{array}
$$
[^14]
Ejemplo
Demostrar la siguiente inferencia:
$$
\begin{array}{l}
1. &x>y \vee x < 6 \\
2. &x>y \Rightarrow x > 4 \\
3. &x>4 \Rightarrow x = 5 \wedge x < 7 \\
4. &x<6 \Rightarrow x = 5 \wedge x < 7 \\
5. &x<7 \wedge x =5 \Rightarrow z>x \vee y<z \\
6. &x>y \Rightarrow \neg (y<z \vee z>x) \\
\hline
&&& \therefore x < 6\\
7. &x>y \Rightarrow x = 5 \wedge x < 7  & \text{[LSH 2,3]} \\
8. &(x = 5 \wedge x < 7) \vee (x = 5 \wedge x < 7)  & \text{[LSD 1,7,4]} \\
9. &x=5 \wedge x < 7 & \text{[SD 8]} \\
10. &z>x \vee y<z  & \text{MPP 9,5]} \\
11. &\neg (x>y)  & \text{[MTT 6,10]} \\
12. &x<6  & \text{[MTP 1,11]}&\blacksquare \\
\end{array}
$$




# Cuantificadores

Consideremos la inferencia

$$
\begin{array}{l}
\text{Todos los hombres son mortales.}\\
\text{Sócrates es un hombre.}\\
\hline
\text{Sócrates es mortal.}\\
\end{array}
$$

que consideramos corno válida. En este caso, la validez depende no sobre las relaciones entre las premisas y la conclusión, sino sobre relaciones entre las **partes** de los enunciados involucrados y sobre las formas de los enunciados mismos.

La anterior inferencia puede representarse en la forma:

$$
\begin{array}{l}
\text{Todos los A son B.}\\
\text{C es un A.}\\
\hline
\text{C es B.}\\
\end{array}
$$

Debemos entender la naturaleza de premisa "Todos los A son B". Todo enunciado simple en español tiene la forma

$$\text{sujeto } + \underbrace{\text{verbo } + \text{complemento}}_{\text{predicado}}$$,

donde el predicado se refiere a una "propiedad" que el sujeto tiene.

Ejemplo
$$
\begin{align}
\text{"Sócrates es un hombre". }\\
\text{"Yo escribo libros". }\\
\blacksquare\\
\end{align}
$$

Representamos los predicados por letras (romanas, griegas, etc.).

Si A representa el predicado "es un hombre" y s representa al sujeto "Sócrates", entonces

$$
\begin{array}{l}
A(s):\text{``Sócrates es un hombre''. }\\
A(Socrates) : \text{``Sócrates es un hombre''. }\\
\end{array}
$$

Si n représenta a "Napoleón", entonces

$$
\begin{array}{l}
A(n):\text{``Napoleón es un hombre''. }\\
& \blacksquare\\
\end{array}
$$

En matemáticas, es usual escribir proposiciones como:  

> "Todo entero tiene un factor primo".  

Esto podemos escribirlo en la siguiente forma:  

> (\*) "Para todo $x$, si $x$ es un entero, entonces $x$ tiene un factor primo"*.  

Si tenemos los predicados:  
- $I(x)$: "$x$ es un entero"  y
- $P(x)$: "$x$ tiene un factor primo",  

entonces (\*) se puede escribir:  
$$  
\text{Para todo }x, (I(x) \Rightarrow P(x))  
$$  
La frase *"para todo $x$"* se llama **cuantificador universal** y se simboliza por $(\forall x)$; entonces, (\*) se escribe finalmente:  
$$  
(\forall x) \, (I(x) \Rightarrow P(x))  
$$  

El símbolo $x$ no debe causar confusión y no suponemos nada sobre su naturaleza: podemos haber escrito  
$$  
\begin{align}
\forall y \, (I(y) \Rightarrow P(y)), &\\
\forall z \, (I(z) \Rightarrow P(z)), &\text{ etc.} 

\end{align}
$$  

Usamos las letras $x$, $y$, $z$ como variables.  

Hay otro tipo de cuantificador:  

> (\*\*) "Algunos cerdos tienen alas"
 
, que se puede escribir como:  

> "Existe por lo menos un objeto $x$ tal que $x$ es un cerdo y $x$ tiene alas"*.  

La frase *"existe por lo menos un objeto $x$ tal que"* se llama **cuantificador existencial** y se simboliza por $(\exists x)$. La proposición (\*\*) se puede escribir:  
$$  
\exists x \, (P(x) \land W(x))  
$$  
donde:  
- $P(x)$: "$x$ es un cerdo"  
- $W(x)$: "$x$ tiene alas"  

En general, si $A$ representa un predicado, podemos escribir:  
$$  
(\forall x) \, (A(x)) \quad \text{y} \quad (\exists x) \, (A(x))  
$$  

**Obs.** El cuantificador existencial tiene una variante, a saber:  
$$  
(\exists! x) \, (\varphi(x))  
$$  
que se lee *"existe un único objeto $x$ tal que ..."*
$\blacksquare$

Es común encontrar en matemáticas proposiciones como:  
$$  
\begin{align}
(\forall x \in \mathbb{R}) &\, (x^2 \geq 0)  \\
(\exists t \in \mathbb{Z}) &\, (t^2 = 1)  
\end{align}
$$

En ellas, los cuantificadores se llaman **restringidos**; representan las siguientes proposiciones:  
  
$$
\begin{align}
(\forall P(x)) \,(Q(x)) \equiv (\forall x)\,(P(x) \Rightarrow Q(x)) \\
(\exists \varphi(x)) \,(\psi(x)) \equiv (\exists x)\,(\varphi(x) \Rightarrow \psi(x)) 
\end{align}
$$

Finalmente, tenemos lo siguiente:  
$$  
\begin{align}
\neg \, (\forall x) \, (P(x)) \equiv (\exists x) \, (\neg \, P(x)) \\
\neg \, (\exists x) \, (Q(x)) \equiv (\forall x) \, (\neg \,Q(x))  
\end{align}
$$  

Algunas cuestiones técnicas  

1. **Precedencia de cuantificadores:**  
   Los cuantificadores $\forall$ y $\exists$ tienen precedencia superior a todos los operadores lógicos del cálculo proposicional.  

2. **Variables ligadas y libres:**  
   - Cuando una variable $x$ es cuantificada, decimos que esta ocurrencia de la variable está **ligada**.  
   - Una ocurrencia de una variable que no está ligada por un cuantificador o es igual a un valor particular se dice que es **libre**.   
3. **Alcance de un cuantificador:**  
   La parte de una expresión lógica a la cual un cuantificador se aplica se llama el **alcance** de este cuantificador. Por consiguiente, una variable es libre si está fuera del alcance de todos los cuantificadores en la fórmula que especifica esta variable.  

   **Ejemplo:**  
   En la proposición  
$$
(\exists x)\,(x+y=1)
$$  
   la variable $x$ está ligada por el cuantificador $(\exists x)$, pero la variable $y$ es libre.

   **Ejemplo:**  
   En la proposición  
   $$  
   (\exists x) \, (P(x) \land Q(x)) \lor (\forall x) \, (R(x))  
   $$

	 ![[Pasted image 20250330194439.png]]
	 
   todas las variables estan ligadas. Aqui tenemos:

| **Cuantificador** | **Alcance**       | **Variable ligada** |     |
| ----------------- | ----------------- | ------------------- | --- |
| $\exists x$       | $P(x) \land Q(x)$ | $x$                 |     |
| $\forall x$       | $R(x)$            | $x$                 |     |

   Como los alcances de los dos cuantificadores no se superponen, podríamos escribir la misma proposición como:  
   $$  
   (\exists x)\,(P(x)\land Q(x))\lor(\forall x)\,(R(x))
   \qquad \blacksquare
   $$  

4. **Anidación de cuantificadores:**  
   Podemos "anidar" cuantificadores y escribir proposiciones como:  
	$$  
   (\forall x) \, (\forall y) \, (P(x,y))  
   $$  
   **Ejemplo:**  
   Si $x$ e $y$ son números reales:  
   $$
   \begin{align}  
   (\forall x) \, (\forall y) \, (x + y = y + x) \\ 
   (\forall x, y) \, (x + y = y + x) \\ 
   \end{align}
   $$  
   es la ley conmutativa para la adición de números reales.  

   Cuando anidamos dos cuantificadores diferentes, el orden es importante.  
   $$
   \begin{align}  
   (\forall x) \, (\forall y) \, (P(x,y)) \equiv (\forall y) \, (\forall x)\, (P(x,y))  \\ 
   (\exists x) \, (\exists y) \, (Q(x,y)) \equiv (\exists y) \, (\exists x)\, (Q(x,y))  \\ 
   (\forall x) \, (\exists y) \, (R(x,y)) \not\equiv (\exists y) \, (\forall x) \, (R(x,y)) \\ 
   \end{align}
   $$

	 $$
	 (\forall x)(\exists y)(x+y=0) \qquad (\exists x)(\forall y)(x+y=0)
	 $$



[^1]: Inferencias Deductivas. Va de los general a lo particular. 

[^2]: Inferencias Inductivas. Va de lo particular a lo general.

[^3]: La proposicion debe tener verbo

[^4]: Cabe mencionar que las proposiciones se asocian de izquierda a derecha: $p \Rightarrow q \Rightarrow r \equiv (p \Rightarrow q) \Rightarrow r$.

[^5]: $\mathbb V$ es una tautologia y $V$ es un valor de verdad.

[^6]: Vacuidad.Deducir a partir de premisas falsas conclusion verdadera. Como la conclusion es falsa, entonces tenemos vacuidad.

[^7]: $p \Rightarrow q$ , $p$ es suficiente, $q$ es necesaria.

[^8]: Si no esta demostrado, es entonces una conjetura.

[^9]: Deducción. Reglas generales resultados particulates.

[^10]: Afirmando afirmo.
	Se usa para extraer el consecuente de la implicacion.

[^11]: Negando niego.
	Se usa para extraer el antecedente de la implicacion
	
[^12]: Negaando afirmo.
	
[^13]: Debemos utilizar todas las premisas.

[^14]: Se debe escoger un punto de partida e ir para atras.
