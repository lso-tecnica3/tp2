# Trabajo Práctico 2: Diccionarios

## Ejercicio A
**(Ejercicio 7 de la guía)** Como parte del test que se le está realizando a un velocímetro de una autopista, se capturaron 1000 velocidades de prueba, pero algunas de ellas son datos erróneos. Escribir un programa en PHP que:
1. Cree el diccionario `$velocidades` con [estos](https://pastebin.com/XPyZBiD9) datos.
2. Recorra el diccionario `$velocidades` y elimine aquellas velocidades que están fuera del rango [10, 200], es decir, cuyos valores sean menores a 10 o mayores a 200. Además, se deben contar cuántos de estos valores fueron eliminados.
3. Muestre los datos del diccionario en una tabla, poniendo en color rojo aquellos vehículos que están en infracción (cuya velocidad fue mayor a 120).
4. Informe en una tabla:
    1. La cantidad de velocidades dentro del rango válido.
    2. La cantidad de vehículos en infracción.
    3. La cantidad de velocidades fuera de rango.
5. Muestre por cada vehículo en infracción una tabla con formato de acta de infracción, por ejemplo:
![acta de infracción](https://file.notion.so/f/f/a99bb5a3-e1cf-4a82-babb-1bc6f28ca9a3/81fed63b-e706-4492-8560-6dd5592725cd/image.png?table=block&id=1dca1ac8-165e-8031-b15e-f0e1e9d8fa9d&spaceId=a99bb5a3-e1cf-4a82-babb-1bc6f28ca9a3&expirationTimestamp=1745820000000&signature=zZfrCDWURdLM-X7-ctykIJ7jG2B1zTO3hjbdqLm60gg&downloadName=image.png)

Las actas de infracción deben estar numeradas a partir de 1. Además, tener en cuenta que si la velocidad es mayor a 160 se deberá pagar un total de $100.000, sino, $50.000. 

## Ejercicio B
**(Ejercicio 8 de la guía)** 

El siguiente gráfico contiene información sobre las temperaturas de un determinado año:

![temperaturas](https://file.notion.so/f/f/a99bb5a3-e1cf-4a82-babb-1bc6f28ca9a3/36e0eacd-b63f-4206-958d-308002eae5ac/image.png?table=block&id=1dca1ac8-165e-801c-b059-d0f4d8b3c871&spaceId=a99bb5a3-e1cf-4a82-babb-1bc6f28ca9a3&expirationTimestamp=1745820000000&signature=l_KrruK-TkweQ15iOziaZyVq5bGJoPXwiTHyNIovqB8&downloadName=image.png)

Escribir un programa en PHP que permita almacenar las temperaturas del gráfico y calcular:

1. El promedio de las temperaturas mínimas y el promedio de las máximas (recordar que el promedio se calcula sumando todas las temperaturas y dividiéndola por la cantidad).
2. La temperatura más baja y la más alta del año (con sus respectivos meses).

De ser necesario utilizar la función [number_format](https://www.php.net/manual/es/function.number-format.php) de PHP.
