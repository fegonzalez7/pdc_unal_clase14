# Programación de Computadores - UNAL

## Taller 2

1. Desarrollar un programa que ingrese un número entero n y separe todos los digitos que componen el número. **Pista:** Utilice los operadores módulo (%) y división entera (//).
2. Desarrollar un programa que ingrese un número flotante n y separe su parte entera de la parte decimal, y luego entregue los dígitos tanto de la parte entera como de la decimal.
3. Desarrollar un programa que permita ingresar dos números enteros y determinar si se tratan de números espejos, definiendo números espejos como dos números a y b tales que a se lee de izquierda a derecha igual que se lee b de derecha a izquierda, y viceversa.
4. Diseñar una función que permita calcular una aproximación de la función coseno alrededor de 0 para cualquier valor x (real), utilizando los primeros n términos de la serie de Taylor. **nota:** use *math* para traer la función coseno y mostrar la diferencia entre el valor real y la aproximación. Calcule con cuántos términos de la serie (i.e: cuáles valores de n), se tienen errores del 10%, 1%, 0.1% y 0.001%.
$$cos(x) \approx cos(x,n) \approx \sum_{i=0}^{n} (-1)^i \frac{x^{2i}}{(2i)!}$$
5. Desarrollar un programa que permita determinar el Minimo Comun Multiplo de dos numeros enteros. Abordar el problema desde una perpectiva tanto iterativa como recursiva. **Pista:** Puede ser de utilidad chequear el [Algoritmo de Euclides](https://es.wikipedia.org/wiki/Algoritmo_de_Euclides) para el cálculo del Máximo Común Divisor, y revisar cómo se relaciona este último con el Mínimo Común Múltiplo.
6. Desarrollar un programa que determine si en una lista existen o no elementos repetidos. **Pista:** Maneje valores booleanos y utilice el operador *in*.
7. Desarrollar un programa que determine si en una lista se encuentra
una cadena de caracteres con dos o más vocales. Si la cadena existe debe imprimirla y si no existe debe imprimir 'No existe'.
8. Desarrollar un programa que dadas dos listas determine que elementos tiene la primer lista que no tenga la segunda lista. **Ejemplo:**
<center>
<table border="1">
<tr>
<td>
lista1: [1, 'Hola', -12.3 ,True]<br>
lista2: [11, -12.3, 'Hola', False]
</td>
</tr>
<tr>
<td>
salida: [1, True]
</td>
</tr>
</table>
</center>

9. Resolver el punto 7 del [taller 1](https://github.com/fegonzalez7/pdc_unal_clase8) usando operaciones con vectores.

10. Suponga que se tiene una lista A con ciertos números enteros. Desarrolle una función que, independientemente de los números que se encuentran en la lista A, tome aquellos números que son múltiplos de 3 y los guarde en una lista nueva, la cual debe ser **retornada** por la función. Implemente la perspectiva de un *patrón de acumulación* y también de *comprensión de listas*. **Desafío:** Si ya lo logró, inténtelo ahora sin utilizar el módulo (%). **Pista:** Un número es multiplo de 3 si la suma de sus dígitos también lo es, ¿verdad?

### Bono
11. Desarrollar un algoritmo que determine si una matriz es mágica. Se dice que una matriz cuadrada es mágica si la suma de cada una de sus filas, de cada una de sus columnas y de cada diagonal es igual.


### Condiciones de entrega:

<table cellspacing="1" bgcolor="">
	<tr bgcolor="#252582">
		<th><b>Item</b></th>
    <th><b>Condición</b></th>
	</tr>
	<tr style="text-align: left; vertical-align: middle;" bgcolor="#e4e4ed">
		<td style="color:#141414">Entregables</td>
    <td style="color:#141414">Se debe elaborar un repo donde presente la solución a todos los problemas planteados. Para los puntos impares debe realizar un programa individual con extensión <i>.py</i> y para los pares debe elaborar un notebook <i>.ipynb</i> con las soluciones. El repo debe contener la explicación de la solución de cada punto. Todos los archivos se deben adjuntar al repo.<br>
    El repo debe ir con los integrantes del equipo, el nombre del grupo y un logo genial.
    </td>
	</tr>
  <tr style="text-align: left; vertical-align: middle;" bgcolor="#e4e4ed">
    <td style="color:#141414">Fechas</td>
    <td style="color:#141414">Se creará el canal taller 2 con un archivo de Google Sheets donde se debe colocar la dirección del repo, si éste tiene un commit posterior al corte, se toma como referencia el más cercano a la fecha establecida.</td>
	</tr>
  <tr style="text-align: left; vertical-align: middle;" bgcolor="#e4e4ed">
    <td style="color:#141414">Forma de trabajo</td>
    <td style="color:#141414">Grupal</td>
	</tr>
  <tr style="text-align: left; vertical-align: middle;" bgcolor="#e4e4ed">
    <td style="color:#141414">Condiciones Extra</td>
    <td style="color:#141414">
    Los códigos elaborados deben estar apropiadamente comentados.<br>
    Todos los programas deben incorporar el uso de funciones.</td>
	</tr>
</table>
