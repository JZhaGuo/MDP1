# MDP1

## Notas varias

- Variables a excluir de la BBDD → todas se pueden analizar y no son constantes (haya variabilidad)

- Valores inconsistentes o anómalos → no tenemos valores inconsistentes pero sí anómalos en 3 variables aproximadamente (no hemos utilizado la transformación logarítmica porque casi todas las variables ). En todos los casos el jugador que tiene el valor anómalo, que es el máximo, es Pete Rose. Habíamos decidido eliminarlo para no condicionar los análisis pero Sonia propone que, sabiendo esto, lo dejemos y saquemos las conclusiones del PCA explicando qué ocurre con Pete Rose. 

- Transformación y recodificación de variables → no tenemos que reagrupar y convertir numéricas a categóricas. Si que hemos convertido las 3 categóricas a binarias y dice Sonia que conservemos las columnas originales categóricas para poder comparar si se forman grupos. Además, respecto a la normalidad, tras analizar la simetría/normalidad de las variables, si hay alguna demasiado asimétrica, se realizaría una transformación logarítmica (en nuestro caso, nos ha dicho que no lo hagamos).

- Faltantes → hemos conseguido los sueldos que faltaban excepto 6, que son las filas que eliminamos (no usamos mice porque salary es nuestra variable a predecir). De peso y altura siguen quedando 6 faltantes que se predicen con mice.

	

## Leyenda:	

- *AtBat*: Número de apariciones en ataque (bateo) de un jugador

- *League*: Liga americana o nacional	

- *Hits*: Contacto exitoso con la bola en la que se llega a base

- *Errors*: No coger la bola en defensa cuando te llega o lanzarla mal a su destino

- *HmRuns*: Batea la bola fuera del campo

- *PutOuts*:Eliminar a un corredor, ya sea tocándolo con la bola, pisando base, cogiendo una bolea antes de que toque el suelo, o cogiendo el tercer strike (bola buena)

- *Assists*: Cuando lanzas la bola a un compañero de equipo y este completa una eliminación de un corredor

- *Division*: Dentro de cada liga, si es división este u oeste
 
- *Salary*: Lo que cobraron en la temporada del 86.

- *Walks*: Llegar a base sin batear la bola (el lanzador lanza 4 bolas mal mientras estás bateando)

- *Years*: Años en activo de un jugador

- *Runs*: Carreras, Puntos anotados (dar la vuelta a las bases)

- *RBI*: Puntos impulsados (al batear la bola, a cuánta gente impulsas a marcar carrera)



## PENDIENTE

PCA: 
- hacer los ejercicios sueltos - ejer 5: misLoadings y añadir flechas y leyendas 

- variables categóricas no binarias

- gráficos scores → salary, peso, altura… → no hace falta rangos (cambiar habillage por col.ind→ salary transformación logarítmica


AFC:
- hacer con ejemplos

	
	
	
	
	
	
	
	
	
	
	
	
	
	
	
