# Taller1-Data_science

## Requerimiento

Una vez que ya se entendieron los datos se procede a dar respuesta a las siguientes preguntas del negocio:
1. Describa el conjunto de datos, tipos de variables y destaque cualquier problema de calidad de datos y procesos de limpieza que deba implementar.
2. ¿Cuál es el top 10 de artistas más activos de los últimos 10 años?
3. ¿Cómo se diferencian las canciones de los géneros de Latin y Folk/Acoustic en relación con su duración? Halle la diferencia del tiempo promedio de ambos géneros.
4. Halle el top 5 de los géneros del 2019 según la cantidad de canciones. ¿Cómo ha variado la cantidad de canciones del Top de géneros en los años 2000, 2005, 2010, 2015, 2019? 
5. ¿Cómo ha sido la progresión de nuevos artistas? Asuma que un artista nuevo es aquel del cual no se tiene registros pasados y solo es nuevo durante el primer año de aparición.
6. Grafique la progresión de la popularidad promedio por género y por año. Concluya sobre la gráfica, ej: ¿existen tendencias?
7. Compare los géneros Pop y Rock según sus características de: energy, valence y tempo.Concluya sobre su análisis.
8. Plantee una pregunta de negocio de su interés, ya sea por tipo de música, artistas u otra dimensión, mediante la cual se analicen al menos 3 variables del dataset y concluya.


## Soluciones

### 1. Describa el conjunto de datos, tipos de variables y destaque cualquier problema de calidad de datos y procesos de limpieza que deba implementar.

#### Limpieza de los datos
En cuanto a la limpieza se realizaron las siguientes operaciones:
1. Formato de datos
2. Eliminar valores nulos
3. Separación One hot de registros que tienen más de un valor en cada columna
4. Corregir columnas con el mismo nombre. (Resultante de la anterior operación)
5. Eliminar valores repetidos

### 2. ¿Cuál es el top 10 de artistas más activos de los últimos 10 años?

Los artistas más activos son:
Calvin Harris    7
Drake            7
Avicii           7
David Guetta     6
Chris Brown      6
Taylor Swift     5
Ariana Grande    5
Lana Del Rey     5
Ed Sheeran       4
Selena Gomez     4

### 3. ¿Cómo se diferencian las canciones de los géneros de Latin y Folk/Acoustic en relación con su duración? Halle la diferencia del tiempo promedio de ambos géneros.

La duración promedio en segundos del género Folk/Acoustic es: 220.18 seconds
La duración promedio en segundos del género Latin es:  226.58 seconds
La diferencia del promedio de duración entre ambos géneros, Folk/Acoustic y Latin es:  6.4 seconds

### 4. Halle el top 5 de los géneros del 2019 según la cantidad de canciones. ¿Cómo ha variado la cantidad de canciones del Top de géneros en los años 2000, 2005, 2010, 2015, 2019? 
 El top 5 de géneros del 2019 según la cantidad son:
 pop                 62
hip hop             35
Dance/Electronic    20
R&B                  9
latin                8

[Graph]
### 5. ¿Cómo ha sido la progresión de nuevos artistas? Asuma que un artista nuevo es aquel del cual no se tiene registros pasados y solo es nuevo durante el primer año de aparición.

[Graph]
### 6. Grafique la progresión de la popularidad promedio por género y por año. Concluya sobre la gráfica, ej: ¿existen tendencias?

[Graph]
#### Conclusiones

* Se concluye que el Pop ha sido el género más popular en el periodo de 1999 al 2020.
* En los últimos años, el hip hop ha tomado una tendencia positiva a tal punto de que en el último año igualó al género Pop. Y parece que en los futuros años va a ocupar el primer lugar en popuularidad.
* Se determina que desde el 2019, el género World/Traditional, ha crecido en popularidad rápidamente. Es posible que se vuelva tendencia en el próximo año.
* En el último año, se evidencia que varios generos como Dance/Electronic, R&B, Rock, entre otros, no tienen popularidad, pero esto puede ser causado porque aún no se han registrado las canciones de estos géneros.

### 7. Compare los géneros Pop y Rock según sus características de: energy, valence y tempo.Concluya sobre su análisis.

[table]

#### Conclusiones

Energy: 
* El género rock tiene un valor de energy 11% mayor que pop
* Cuando la cancion pertenece a ambos géneros, la energy toma un valor 6% menor que una cancion de rock y 5% más que una cancion de pop

Valence: 
* El género pop, en promedio es 3% más positivo que el género Rock.
* Cuando la canción pertenece a ambos géneros, la canción es casi igual de positiva que cación de rock y tiene 3% menos positivad que una canción de pop

Tempo:
* Por lo general, las canciones de rock tienen un tempo de 127 mientras que el pop tiene un tempo de 119. 

### 8. Plantee una pregunta de negocio de su interés, ya sea por tipo de música, artistas u otra dimensión, mediante la cual se analicen al menos 3 variables del dataset y concluya.

#### ¿Cuáles son las top 5 canciones acusticas(con certeza mayor al 50%) e instrumentales(mayor al 50%) más populares?
[Table]

##### Conclusiones

* La canción acustica más popular es Another Love de Tom Odell
* La canción del top 5, con más certeza de ser acústica es Lovely (with Khalid) de	Billie Eilish
* La quinta canción más popular en promedio es All of Me de John Legend

