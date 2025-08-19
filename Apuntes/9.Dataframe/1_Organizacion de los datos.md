# Organizacion de los datos

todos los datos estan organizados, y existen distintos formatos para hacerlo, existen 

- inestructurdos

- esructurados

- semi

cuando no hay forma de clasificarlos son sin estructura, como txt, csv, se pueden guardar solo separando por comas, pero pueden surgir problemas.

los semi, no tienen un modelo racional como una tabla para organizarlo, hay signos apra separarlos, y tienen etiquetas para clasificar como xml json. pueden dar cierto orden pero limitado

el estructura, siempre esta ordenado, todos datos se introducen en campos especifico y cada datos tiene un tamaño definido lo que permite mas eficiencia. requiere más gente ordenandolos,son más rigidos.

## Tipos de documentos

tipo texto, cada entrada es info, no hay formato de dichos datos. El problema es que entre ssitemas operativos no son compatibles. 

tipo csv, son separados pro coma, los intros señalan filas, los cmapos separados por coma. tiene un poco más de estructura pero tiene que estar muy bien definida. para info que se puede representar en una tabla es lo más indicado.

xml, lenguaje marcas extensible, combina organizacion de datos, hecho por objetos, la estructura esta aun más rigida, las etiquetas identifican el datos. casi no se usa casi en ciencia de datos.

json rel con java, es mas legible por humanos, usado por cable valor, se usan llaves para iniciar terminar objetos, es comodo y se puede usar entre muchos lenguajes. ya es mas usado que xml

para los datos relacionales, se usan lenguajes de datos, el mayor es SQL, o no relacionales como oracle.

Las no relacionales se orientan a ficheros, recuperar datos que no sean necesariamente tablas rectangulares, los datos conviven de forma más libre, un ejemplo es mysql, permiten agregar datos sin redefinir estructura, partirlos,
son más dinamicas. 

las relacionales son datos que tiene vinculos entre ellos,   primera cada fila puede identificarse con una clave, son univocas, la foranea son resto de filas a las que hace referencia una de otra.

Entonces las primarias son las de la propia categoria que distinguen a las mismas, foraneas son las que provienen de otra categoria. al principio siempre van las propias, luego las foraneas u otras. cada tabla es una entidad.




