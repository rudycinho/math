En el proyecto de una cafetería se calcula que si hay lugares para 40 a 80 personas, la ganancia diaria bruta será de $8 por lugar. Sin embargo, si la capacidad de asientos sobrepasa los 80 lugares, la ganancia diaria bruta en cada lugar disminuirá en 4 centavos ($0.04) por el número de lugares excedentes. ¿Cuál deberá ser la capacidad de asientos para obtener la mayor ganancia diaria bruta?

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
		4. Remplazamos en 