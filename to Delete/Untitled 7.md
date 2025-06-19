
**Nombre completo:** \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_
**C.I.:** \_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_\_

1. Sean m y n son enteros positivos tales que $n + n^3 + n^5 = m + m^2$. Probar que $n$ es par.

**Demostración por contradicción:** 
Supongamos que $n$ es impar. Entonces, $n = 2k + 1$ para algún entero $k \geq 0$.

**Potencias de un número impar:**  
Sea $x$ un entero impar, es decir, $x = 2a + 1$ para algún entero $a$.  
- $x^2 = (2a + 1)^2 = 4a^2 + 4a + 1 = 2(2a^2 + 2a) + 1 = 2b + 1$, donde $b = 2a^2 + 2a$, luego $x^2$ es impar.  
- $x^3 = x^2 \cdot x = (2b + 1)(2a + 1) = 4ab + 2a + 2b + 1 = 2(2ab + a + b) + 1 = 2c + 1$, donde $c = 2ab + a + b$, luego $x^3$ es impar.  
- $x^5 = x^3 \cdot x^2 = (2c + 1)(2b + 1) = 4bc + 2b + 2c + 1 = 2(2bc + b + c) + 1 = 2d + 1$, donde $d = 2bc + b + c$, luego $x^5$ es impar.  

Como $n$ es impar, entonces $n$, $n^3$ y $n^5$ son impares.  

**Lado izquierdo de la ecuación:**  
$$n + n^3 + n^5 = \text{impar} + \text{impar} + \text{impar} = \text{impar}.$$  

**Lado derecho de la ecuación:**  
$$m + m^2.$$  
Consideramos dos casos para $m$:  
- **Caso 1:** $m$ es par.  
  Sea $m = 2p$ para algún entero $p$.  
  Entonces $m^2 = (2p)^2 = 4p^2 = 2(2p^2)$, que es par.  
  Así que $m + m^2 = \text{par} + \text{par} = \text{par}$.  
- **Caso 2:** $m$ es impar.  
  Sea $m = 2q + 1$ para algún entero $q$.  
  Entonces $m^2 = (2q + 1)^2 = 4q^2 + 4q + 1 = 2(2q^2 + 2q) + 1$, que es impar.  
  Así que $m + m^2 = \text{impar} + \text{impar} = \text{par}$.  

En ambos casos, $m + m^2$ es par.  

**Conclusión:**  
El lado izquierdo es impar y el lado derecho es par. Esto es una contradicción, ya que un número no puede ser simultáneamente impar y par. Por lo tanto, la suposición inicial es falsa, y $n$ debe ser par.  

$\boxed{\text{Por lo tanto, } n \text{ es par.}}$



1. Sean m y n son enteros positivos tales que $n + n^3 + n^5 = m + m^2$. Probar que $n$ es par.
	
2. Probar que todo entero positivo $n$ se puede expresar como la suma de una o más potencias de 2, distintas entre sí.

3. Consideremos los números enteros del 1 al 2025.
   ¿Cuántos de estos números tienen una suma de dígitos que es múltiplo de 5?
		 
4. ¿Cómo se puede cortar un rectángulo de dimensiones $13\times7$ en 13 rectángulos de áreas y dimensiones diferentes?
5. ¿Existe una solución entera para la ecuación $a \cdot b \cdot (a - b) = 45045\;$?
