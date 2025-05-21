Dados: d=6, e=4, f=-2. Evaluar las siguientes expresiones en octave.

#   Verifica los resultados con octave.

## (a) y=d+f>=e>d-e

### Evaluación
$$
	\begin{array}{llr}
		y &= d+f>=e>d-e\\
		  &= 6-2>=4>6-4 & \text{ Reemplazando.}\\ 
		  &= 4>=4>2 & \text{ Sumas y Restas.}\\
		  &= (4>=4)>2 & \text{ Asociando por derecha.}\\
		  &= 1>2 & 4>=4\text{ es Verdadero, por lo que el resultado es 1.}\\
		  &= 0 & 1>2\text{ es Falso, por lo que el resultado es 0.}\\ 
	\end{array}
$$

### Código

```octave
d=6;
e=4;
f=-2;
y=d+f>=e>d-e
```

### Ejecución
```
y = 0
```

## (b) y=e>d>f

### Evaluación
$$
	\begin{array}{llr}
		y &= e>d>f\\
		  &= 4>6>-2 & \text{ Reemplazando.}\\ 
		  &= (4>6)>-2 & \text{ Asociando por derecha.}\\ 
		  &= 0>-2 & 4>6\text{ es Falso, por lo que el resultado es 0.}\\ 
		  &= 1 & 0>-2 \text{ es Verdadero, por lo que el resultado es 1.}\\ 
	\end{array}
$$
### Código
```octave
d=6;
e=4;
f=-2;
y=e>d>f
```

### Ejecución
```
y = 1
```

## (c) y=e-d<=d-e == f / f
### Evaluación
$$
	\begin{array}{llr}
		y &=  e-d<=d-e == f / f\\
		y &=  4-6<=6-4 == (-2) / (-2) & \text{ Reemplazando.}\\ 
		y &=  4-6<=6-4 == 1 & \text{ Division.}\\ 
		y &=  -2<=2 == 1 & \text{ Restas.}\\ 
		y &=  (-2<=2) == 1 & \text{ Asociando por derecha.}\\ 
		y &=  1 == 1 & -2<=2\text{ es Verdadero, por lo que el resultado es 1.}\\ 
		y &=  1 & 1 == 1\text{ es Verdadero, por lo que el resultado es 1.}\\ 
	\end{array}
$$

### Código
```octave
d=6;
e=4;
f=-2;

y=e-d<=d-e == f / f
```

### Ejecución
```
y = 1
```

## (d) y=(d/e\*f <f) > -1* (e-d) / f

### Evaluación
$$
	\begin{array}{llr}
		y &= (d/e*f <f) > -1* (e-d) / f\\
		y &= [6/4*(-2) <(-2)] > -1* (4-6) / (-2) & \text{ Reemplazando}\\ 
		y &= [6/4*(-2) <(-2)] > -1* (-2) / (-2) & \text{ Parentesis}\\ 
		y &= [(6/4)*(-2) <(-2)] > (-1* (-2)) / (-2) & \text{ Asociando por Derecha}\\ 
		y &= [(1.5)*(-2) <(-2)] > 1 / (-2) & \text{ Division y Multiplicacion}\\ 
		y &= [(-3) <(-2)] > (-0.5) & \text{ Division y Multiplicacion}\\ 
		y &= 1 > (-0.5) & -3 <-2\text{ es Verdadero, por lo que el resultado es 1.}\\ 
		y &= 1 & 1 > (-0.5) \text{ es Verdadero, por lo que el resultado es 1.}\\ 
	\end{array}
$$

### Código
```octave
d=6;
e=4;
f=-2;

y=(d/e*f <f) > -1* (e-d) / f
```

### Ejecución
```
y = 1
```
