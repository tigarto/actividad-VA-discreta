# Variable aleatoria discreta

## Actividad

Teniendo en cuenta lo información dada en la siguiente tabla:

| Tema  | Juan Diego Taborda | Juan Camilo Quiroga | Samuel Toro| Santiago Ramirez| Julian Hernandez|
| ---  | ----| --- | --- | --- | --- |
| **Binomial**  | 2 | 1 | 2 | 4 | 5 |
| **Geometrica**  | 5 | 3 | 4 | 1 | 2 |
| **Hipergeometrica**  | 4 | 2 | 5 | 3 | 1 |
| **Poisson**  | 1 | 5 | 3 | 4 | 2 |

Resuelva cada uno de los problemas claramente a **mano** (tal y como se vio en clase) y usando **python**. Los problemas resueltos a mano deberan ser entregados en clase en hojas mostrando la solución de manera clara, ordenada y bien explicada. Las notebooks de python (archivos con extención **ipynb**) que implementan la solución de los problemas que se la asigno, deberan ser subidos a este repositorio en una carpeta con las iniciales del autor y dentro de esta con los nombres de los archivos siguiendo el siguiente formato de acuerdo a la distribución que se toco y el numero que se le asigno:

|Distribución|Nombre|
|---|---|
|Binomial|**```bin_#.ipybn```**|
|Geometrica|**```geom_#.ipybn```**|
|Hipergeometrica|**```hiper_#.ipybn```**|
|Poisson|**```poisson_#.ipybn```**|

Por ejemplo, de la tabla se puede ver que al estudiante **Juan Diego Taborda** le toco resolver los siguientes problemas:
* **Binomial**: 2
* **Geometrica**: 5
* **Hipergeometrica**: 4
* **Poisson**: 1

Teniendo en cuenta lo anterior, el estudiante **Juan Diego Taborda** debera crear una carpeta con sus iniciales **JDT** y colocar dentro de esta la solución de los problemas de acuerdo nombrandolos de la siguiente manera:

|Distribución|Ejercicio Asignado|Nombre|
|---|---|---|
|Binomial|2|**```bin_2.ipybn```**|
|Geometrica|5|**```geom_5.ipybn```**|
|Hipergeometrica|4|**```hiper_4.ipybn```**|
|Poisson|1|**```poisson_1.ipybn```**|

Para cada archivo puede usar la plantilla mostrada en el siguiente [link](ha/bin_6.ipynb) adaptandola a su problema en especifico. Recuerde que en al aula virtual del curso se encuentra abundante material de consulta (diapositivas, ejemplos, etc). Tambien, los ejemplos resueltos en clase usando python se encuentran recopilados en el siguiente [link](https://github.com/estocasticos-udem/curso_2023-1/tree/main/variables_aleatorias_discretas) para que recuerde los conceptos claves antes de empezar.


## Problemas

### Distribución de probabilidad Binomial

1. Se construye un complejo sistema electrónico con cierto número de piezas de respaldo en sus subsistemas. Un subsistema tiene cuatro componentes idénticos, cada uno con una probabilidad de 0.2 de fallar en menos de 1000 horas. El subsistema funciona si dos de los cuatro componentes están operando. Suponga que los componentes operan de manera independiente. Encuentre la probabilidad de que
   <ol style="list-style-type: lower-alpha">
   <li>Exactamente dos de los cuatro componentes dure más de 1000 horas. (<b>Rta</b>: 0.1536) </li>
   <li>El subsistema opere más de 1000 horas. (<b>Rta</b>: 0.9728)</li>
   </ol>

2. El sistema de seguridad de una casa está diseñado para tener un 99% de confiabilidad. Suponga que nueve casas equipadas con este sistema experimentan un intento de robo. Encuentre las probabilidades de estos eventos:
   <ol style="list-style-type: lower-alpha">
   <li>Al menos una de las alarmas se activó. (<b>Rta</b>: 1) </li>
   <li>Más de siete de las alarmas se activaron  (<b>Rta</b>: 0.997)</li>
   <li>Ocho o menos alarmas se activaron   (<b>Rta</b>: 0.086)</li>
   </ol>

3. Muchas empresas que generan energía eléctrica promueven el ahorro de energía, para lo cual ofrecen tarifas de descuento a consumidores que mantengan su uso por debajo de ciertos estándares establecidos de subsidio. Un reciente informe de la EPA (agencia de protección ambiental) observa que 70% de los residentes en Puerto Rico han reducido su consumo de electricidad lo suficiente para tener derecho a tarifas de descuento. Si se seleccionan al azar cinco suscriptores residenciales de San Juan, Puerto Rico, encuentre la probabilidad de cada uno de los siguientes eventos:
   <ol style="list-style-type: lower-alpha">
   <li>Los cinco tienen derecho a las tarifas favorables. (<b>Rta</b>: 0.1681) </li>
   <li>Al menos cuatro tienen derecho a tarifas favorables.  (<b>Rta</b>: 0.5282)</li>
   </ol>

4. Problema Unos registros muestran que 30% de todos los pacientes ingresados en una clínica médica no pagan sus cuentas y que, en última instancia, esas cuentas son olvidadas. Suponga que n = 4 nuevos pacientes representan una selección aleatoria de entre un gran conjunto de prospectos de pacientes atendidos por la clínica. Encuentre estas probabilidades::
   <ol style="list-style-type: lower-alpha">
   <li>Las cuentas de todos los pacientes tendrán finalmente que olvidarse. (<b>Rta:</b> 0.0081) </li>
   <li>Una tendrá que olvidarse. (<b>Rta</b>: 0.4416)</li>
   <li>Ninguna tendrá que olvidarse.(<b>Rta</b>: 0.2401)</li>
   </ol>

5. Un estudiante que está tratando de escribir un ensayo para un curso tiene la opción de dos temas, A y B. Si selecciona el tema A, el estudiante pedirá dos libros mediante préstamo interbiblioteca, mientras que, si selecciona el tema B, el estudiante pedirá cuatro libros. El estudiante cree que un buen ensayo necesita recibir y utilizar por lo menos la mitad de los libros pedidos para uno u otro tema seleccionado. Si la probabilidad de que un libro pedido mediante préstamo interbiblioteca llegue a tiempo es de .9 y los libros llegan independientemente uno de otro
   <ol style="list-style-type: lower-alpha">
   <li>¿Qué tema deberá seleccionar el estudiante para incrementar al máximo la probabilidad de escribir un buen ensayo? (<b>Rta</b>: 0.0081) </li>
   <li>¿Qué pasa si la probabilidad de que lleguen los libros es de sólo 0.5 en lugar de 0.9? (<b>Tema A</b>: 0.99; <b>Tema B</b>: 0.9963)</li>
   <li>Ninguna tendrá que olvidarse.(<b>Tema A</b>: 0.75; <b>Tema B</b>: 0.6875)</li>
   </ol>

### Distribución de probabilidad Geometrica

1. Suponga que la probabilidad de mal funcionamiento de un motor durante cualquier periodo de una hora es p = 0.02. Encuentre la probabilidad de que un motor determinado funcione bien dos horas. (**Rta**: 0.9604)
   
2. Un contador público certificado (CPA, por sus siglas en inglés) ha encontrado que nueve de cada diez compañías auditadas contienen errores importantes. Si el CPA hace auditoría a una serie de cuentas de empresas
   <ol style="list-style-type: lower-alpha">
   <li>¿Cuál es la probabilidad de que la primera cuenta que contenga errores importantes sea la tercera en ser auditada?. (<b>Rta</b>: 0.009) </li>
   <li>¿Cuál es la probabilidad de que la primera cuenta que contenga errores importantes cualquier cuenta después de la segunda? (<b>Rta</b>: 0.01)</li>
   </ol>

3. La probabilidad de que llegue un cliente al mostrador de servicio de una tienda en un segundo cualquiera es igual a 0.1. Suponga que llegan clientes en forma aleatoria y por tanto que una llegada en un segundo cualquiera es independiente de las otras. Encuentre la probabilidad de que la primera llegada:
   <ol style="list-style-type: lower-alpha">
   <li>Ocurra durante el tercer intervalo de un segundo. (<b>Rta</b>: 0.081) </li>
   <li>No ocurra hasta al menos el tercer intervalo de un segundo. (<b>Rta</b>: 0.81)</li>
   </ol>
   
4. Una empresa de exploración petrolera va a hacer una serie de perforaciones de sondeo en una zona determinada en busca de un pozo productivo. La probabilidad de que tenga éxito en un intento dado es 0.2.
   <ol style="list-style-type: lower-alpha">
   <li>¿Cuál es la probabilidad de que la tercera perforación sea la primera en dar un pozo productivo? (<b>Rta</b>: 0.128) </li>
   <li>Si la empresa puede darse el lujo de perforar a lo sumo diez pozos, ¿cuál es la probabilidad de que no encuentre un pozo productivo? (<b>Rta</b>: 0.107)</li>
   </ol>

5. Suponga que 30% de los solicitantes para cierto trabajo industrial posee capacitación avanzada en programación computacional. Los candidatos son elegidos aleatoriamente entre la población y entrevistados en forma sucesiva. 
   <ol style="list-style-type: lower-alpha">
   <li>Encuentre la probabilidad de que el primer solicitante con capacitación avanzada en programación se encuentre en la quinta entrevista. (<b>Rta</b>: 0.07203) </li>
   <li>¿Cuál es el número esperado de solicitantes que será necesario entrevistar para hallar el primero con capacitación avanzada? (<b>Rta</b>: 3.33)</li>
   </ol>
   
### Distribución de probabilidad Hipergeometrica

1. En el sur de California, un creciente número de personas que buscan una credencial para enseñanza están escogiendo internados pagados en los tradicionales programas estudiantiles para enseñanza. Un grupo de ocho candidatos para tres posiciones locales de enseñanza estaba formado por cinco candidatos, que se habían inscrito en internados pagados y tres candidatos que se habían inscrito en programas tradicionales estudiantiles para enseñanza. Supongamos que los ocho candidatos están igualmente calificados para las posiciones. Represente con x el número de candidatos capacitados en un internado que son contratados para estas tres posiciones.
   <ol style="list-style-type: lower-alpha">
   <li>Encuentre la probabilidad de que tres candidatos capacitados en internado sean contratados para estas posiciones. (<b>Rta</b>: 0.1786) </li>
   <li>¿Cuál es la probabilidad de que ninguno de los tres contratados sea capacitado en internado? (<b>Rta</b>: 0.01786)</li>
   <li>Encuentre P(X >= 1) (<b>Rta</b>: 0.2857)</li>
   </ol>

2. Es frecuente que las semillas sean tratadas con fungicidas para protegerlas en ambientes húmedos y con desecación defectuosa. Un intento a pequeña escala, que comprende cinco semillas tratadas y cinco no tratadas, fue realizado antes de un experimento a gran escala para explorar cuánto fungicida aplicar. Las semillas se plantaron en un suelo húmedo y se contó el número de plantas que brotaron. Si la solución no era efectiva y cuatro plantas brotaron en realidad, cuál es la probabilidad de que:
   <ol style="list-style-type: lower-alpha">
   <li>Las cuatro plantas brotaran de semillas tratadas. (<b>Rta</b>: 0.0238) </li>
   <li>Tres o menos brotaran de semillas tratadas. (<b>Rta</b>: 0.9762)</li>
   <li>Al menos una brotara de semillas no tratadas (<b>Rta:</b>: 0.9762)</li>
   </ol>

3. Un producto industrial se envía en lotes de 20. Es costoso realizar pruebas para determinar si un artículo es defectuoso y, por tanto, el fabricante muestrea su producción en lugar de usar un plan de inspección al 100%. Un plan de muestreo, construido para minimizar el número de piezas defectuosas enviadas a los clientes, exige muestrear cinco artículos de cada lote y rechazar el lote si se observa más de una pieza defectuosa. (Si el lote es rechazado, cada artículo del mismo se prueba posteriormente.) Si un lote contiene cuatro piezas defectuosas: 
   <ol style="list-style-type: lower-alpha">
   <li>¿cuál es la probabilidad de que sea rechazado?  (<b>Rta</b>: 0.2487) </li>
   <li>¿Cuál es el número esperado de piezas defectuosas en la muestra de tamaño 5? (<b>Rta</b>: 1)</li>
   <li>¿Cuál es la varianza del número de piezas defectuosas de la muestra de tamaño 5? (<b>Rta</b>: 0.632)</li>
   </ol>

4. Se capturaron, etiquetaron y liberaron cinco individuos de una población de animales que se piensa están al borde la extinción en una región para que se mezclen con la población. Después de haber tenido la oportunidad de mezclarse, se selecciona una muestra aleatoria de 10 de estos animales. Sea **X = el número de animales etiquetados en la segunda muestra**. Si en realidad hay 25 animales de este tipo en la región, ¿cuál es la probabilidad de que:
   <ol style="list-style-type: lower-alpha">
   <li>El numero de animales etiquetados en la segunda muestra sea de dos(<b>Rta</b>: 0.385) </li>
   <li>El numero de animales etiquetados en la segunda muestra no supere los dos (<b>Rta</b>: 0.699)</li>
   <li>Calcule la media y la varianza del problrma (<b>Media</b>: 2.0; <b>Varianza</b>: 1.0)</li>
   </ol>

5. Una corporación está muestreando sin reemplazo para n = 3 firmas para determinar aquella de la cual comprar ciertos abastecimientos. La muestra se ha de seleccionar de un grupo de seis fi rmas, de las cuales cuatro son locales y dos no. Denote con Y el número de fi rmas no locales de entre las tres seleccionadas.
   <ol style="list-style-type: lower-alpha">
   <li>P(Y = 1) (<b>Rta</b>: 0.6) </li>
   <li>P(Y >= 1) (<b>Rta</b>: 0.8)</li>
   <li>P(Y <= 1) (<b>Rta</b>: 0.8)</li>
   </ol>

### Distribución de probabilidad de Poisson

1. El número de errores mecanográficos hechos por una secretaria tiene una distribución de Poisson con
un promedio de cuatro errores por página. Si en una página se dan más de cuatro errores, la secretaria
debe volver a escribir toda la página. ¿Cuál es la probabilidad de que una página seleccionada al azar no
tenga que volver a ser escrita? (**Rta**: 0.6288)

2. El número promedio de accidentes de tránsito en cierto crucero de carretera es dos por semana. Suponga que el número de accidentes sigue una distribución de Poisson con $\lambda = 2$
   <ol style="list-style-type: lower-alpha">
   <li>Encuentre la probabilidad de que no haya accidentes en este crucero de carretera durante un periodo de 1 semana. (<b>Rta</b>: 0.135335) </li>
   <li>Encuentre la probabilidad de que haya tres accidentes como máximo en esta sección de carretera durante un periodo de 2 semanas. (<b>Rta</b>: 0.433471)</li>
   </ol>

3. El incremento del número de vuelos regionales cortos en aeropuertos importantes ha aumentado la preocupación por la seguridad en el aire. Un aeropuerto de la región este ha registrado un promedio mensual de cinco accidentes a punto de ocurrir en aterrizajes y despegues en los últimos 5 años.
   <ol style="list-style-type: lower-alpha">
   <li>Encuentre la probabilidad de que durante un mes determinado no haya accidentes a punto de ocurrir en aterrizajes y despegues en el aeropuerto. (<b>Rta</b>: 0.0067) </li>
   <li>Encuentre la probabilidad de que durante un mes determinado haya cinco accidentes a punto de ocurrir. (<b>Rta</b>: 0.1755)</li>
   <li>Encuentre la probabilidad de que haya al menos cinco accidentes a punto de ocurrir durante un mes particular. (<b>Rta</b>: 0.560)</li>
   </ol>

4. De acuerdo con un estudio realizado por el Departamento de Pediatría de la Universidad de California, en San Francisco, los niños que se lesionan dos o más veces tienden a sufrir estas lesiones durante un tiempo relativamente limitado, por lo general un año o menos. Si el número promedio de lesiones por año para niños en edad escolar es de dos, ¿cuáles son las probabilidades de estos eventos?
   <ol style="list-style-type: lower-alpha">
   <li>Un niño en edad escolar sufrirá dos lesiones durante el año. (<b>Rta</b>: 0.271) </li>
   <li>Un niño en edad escolar sufrirá dos o más lesiones durante el año. (<b>Rta</b>: 0.594)</li>
   <li>Un niño en edad escolar sufrirá a lo sumo una lesión durante el año. (<b>Rta</b>: 0.406)</li>
   </ol>

5. El número de solicitudes de ayuda recibidas por un servicio de grúas es un proceso de Poisson con razón cuatro por hora.
   <ol style="list-style-type: lower-alpha">
   <li>Calcule la probabilidad de que exactamente diez solicitudes sean recibidas durante un periodo particular de 2 horas. (<b>Rta</b>: 0.099) </li>
   <li>Si los operadores del servicio de grúas hacen una pausa de 30 minutos para el almuerzo, ¿cuál es la probabilidad de que no dejen de atender llamadas de ayuda? (<b>Rta</b>: 0.135)</li>
   <li>¿Cuántas llamadas esperaría durante esta pausa? (<b>Rta</b>: 2)</li>
   </ol>
