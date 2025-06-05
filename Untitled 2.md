

1. Comprender el problema
	Variables : x = numero de lugares
	            g(x) = funcion ganancia
	- Para 40<=x<=80
	  g(x) = 8x (lineal)
	- Para x>80
	  excedente de lugares : x-80
	  restriccion impuesta : 0.004 (x-80)
	  ganancia por lguar : 80 - 0.004 (x-80)
	  ganancia diaria bruta : g(x) = x(8 - 0.004 (x-80))
	  
	desarrollamos :
	g(x) = x(8 - 0.004 (x-80)) = x(8 - 0.004x + 3.2) = x(11.2 - 0.004x) = 11.2x - 0.004x2
	Obtenemos:
		g(x) = 8x11.2x−0.04x2​si 40≤x≤80,si x>80.​
	  
2. Concebir un plan
	Analizamos la funcionparable 
		g(x) = 8x11.2x−0.04x2​si 40≤x≤80,si x>80.​
	para 40<=x<=80:
		debido a que g(x)=8x es lineal entonces g(80)=640 valor maximo del tramo
	para x>80
		g(x) = 11.2x - 0.04x2 es una parabalo que se abre hacia abajo (debido que el cofeociente x2 es negativo), por tanto tiene un maximo.
	entonces:
	1. debemos hallar el maximo de g(x)
	2. debemos igualar g'(x) a cero
	3. debemos encontrar x , el punto critico
	4. debemos reemplazarlo en g(x)
3. Ejecutar el plan
		1. Calculamos la derivada de g
		g'(x)=11.2-0.08x
		2. igualoamos a cero para
		g'(x)=11.2-0.08x=0
		3. buscamos el punto critico
		11.2-0.08x=0 => 11.2=0.08x => x=140
		obtibimos el maximo numero de lugares
		4. Remplazamos en g(x)
		g(140)= 11.2(140)−0.04(140)2=1568−0.04×19600=1568−784=784.
		5. comprabamos con g(x)
		   como g(140)>g(80) => 784>640.
		Hemos hallado el maximo
4. Verificamos
Para saber si es maximo verificamos con valores cercanos:
- x=130:
    g(130)=11.2(130)−0.04(130)2=1456−0.04×16900=1456−676=780.
- x=131:
    g(131)=11.2(131)−0.04(131)2=1467.2−0.04×17161=1467.2−686.44=780.76.
- x=140: 784
- x=141
- g(141)=11.2(141)−0.04(141)2=1579.2−0.04×19881=1579.2−795.24=783.96.
- x=150
- g(150)=11.2(150)−0.04(150)2=1680−0.04×22500=1680−900=780.

Por tanto la maxima ganancia bruta diaria es 784