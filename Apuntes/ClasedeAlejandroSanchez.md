# Clase de Alejandro Sanchez

## Secuenciación masiva y bioinformática durante una pandemia

- Vigilancia genomica del Sars-cov2 en el pais
- Segundo centro de secuenciación mas grande del pais
- Inicios de la era genomica, no es un termino nuevo pues inicia en los 70-80 con friederich sanger. Por su metodo de secuenciación de ADN
- Primero se amplifica la señal haciendo varias copias de la misma molecula
- El metodo de sanger consiste en reacciones que se interrumpen debido a la incorporación de nucleotidos que estan modificados por el extremo 3'.
- Por lo que por tamaños se puede ilucidar la secuencia en un gel de agarosa
- La primer secuenciación fue del fago phi 360, un virus de cadena sencilla con 11 genes
- Hay una serie de posicionamientos que orientan sobre la curvatura del dna, repetidos invertidos, energia de empacamiento.
- La secuenciación se ponen 4 reacciones de los nucleotidos modificados. 
- La maquina da una interpretación como picos de fluorescencia y se va ordenando la secuencia.
- Hace muchos años secuenciar un gen se hacia de manera manual por lo que era digno de una tesis de doctorado.
- Tecnologias:
  - 454 -> pirosecuenciación, 
    - Fragmentar adn
    - Poner adaptadores
    - unir los fragmentos a fase solida como la perla con secuencias complemantarias
    - Se anclan las moleculas a las perlas, una perla tendra una molecula
    - por perla se caracteriza un fragmento
    - Se utiliza una emulsión para generar micelas y encerrar las perlas, los nucleotidos o polimerasas.
    - la perla contendra miles de copias de la misma molecula
    - Las perlas se introducen en una rendija con muchos pozos
    - El proceso de secuenciación aprovecha la reacción del enlace fosfodiester y la liberación del pirofosfato y sera tomado por otra enzima que censara cual nucleotido se ha incorporado de acuerdo a los nucleotidos que se adicionen.
    - Muy costosa esta tecnologia
  - Ilumina:
    - Una iniciativa de cambridge, la tecnologia consiste de tres pasos fundamentalmente
    - Tratamiento preparación -> Se tiene la cadena y se le ponen adaptadores
    - Generación de clusters secuenciación -> Por dilusion inyectar en la laminilla moleculas que se exparsan y se peguen a la placa, el adn se dobla y se hace la polimerización en puente.
    - Se generan ramilletes y posteriormente se incorporan las bases modificadas con un fluoroforo las cuales liberan fluorescencia.
    - Analisis bioinformatico,  con esto se puede hacer secuenciación pareada. De este modo se comparan con un genoma de referencia.
  - ion torrent
    - Esta tecnologia aprovecha el ion hidrogenoliberado por la polimerasa. 
    - Dependiendo cuantos iones hidrogeno se liberen se pueden identificar los cambios de pH en los pozos, de modo que se sabe que se incorporo una base.
    - Dependiendo la intensidad se sabe cuantas bases se incorporaron
    - Cuando se incorporan muchas bases existen problemas en la deteccion y podria generar una inserción o una deleción.
    - Esta tecnologia no tuvo exito por los mismos problemas que la 454, las emulsiones y las lecturas pequeñas. Aunque su error es menor.
    - Sirve para detactar cancer
  - Pacbio
    - Tecnologias de tercera generación.
    - Tiempo real y una sola molecula
    - Evita los errores de amplificar el numero de copias
    - Esta tecnologia se basa en nanotecnologia con chips con pozos oscuros en los que se emite luz desde el fondo de acuerdo con la incorporación de bases.
    - En cada pozo hay una polimerasa y estan enriquecidos con nucleotidos.
    - Se obtiene la señal del color de nucleotidos añadidos
    - Genera lecturas muy largas utiles en ensambles de genomas, tambien se pueden detectar isoformas de RNA
  - Oxford nanopore
    - Salio en 2015 , tardo 15 años en salir
    - Esta tecnologia esta hecha con poros proteicos que permiten intercambiar moleculas entre dos lugares, por lo que se registra el cambio de voltaje entre estos dos lugares a traves del poro
    - De este modo es que cada base tiene su nivel de voltaje definido
    - Miles de nanopozos con poros
    - Puede detectar modificaciones del adn como las metilzaciones
- En 2019 estas tecnologias fueron muy utilizadas para secuenciar el virus sars cov 2
- Ya hay secuenciadores de mayor rendimiento como lo son los hiseq, novaseq etc, secuencias largas son mas caras
- Con el tiempo ha bajado mucho el costo de secuenciación por genoma.
- Gracias a esto es que la mayor parte del dinero va destinado al bioinformático que analizara aquello que hayas secuenciado.
- El bioinformatico es la intersección de mucho conocimiento, biologia, computación, matematica etc
- La bioinformatica no es facil porque requiere mucho conocimiento

![image-20211014001105146](C:\Users\10\AppData\Roaming\Typora\typora-user-images\image-20211014001105146.png)

![image-20211014001328928](C:\Users\10\AppData\Roaming\Typora\typora-user-images\image-20211014001328928.png)

## Proyecto de alejandro Sanchez

Cimoto exigua, es un crustaceo que vive en el oceano y es un parasito.

- Es un hermafrodita protandrico, nacen como machos y de adultos se transforman en hembras.
- Siendo larvas infectan a los peces por medio de las branquias y se alojan en la cavidad bucal.
- En la cavidad bucal se empieza a alimentar de la arteria lingual del pez y pasa a ser hembra
- La lengua muere y la hembra se convierte en la lengua que sera fecundada por un macho despues.
- Diferentes estados larvarios.

Que estrategias se involucrarian en este proyecto?

- El parasito tiene un genoma enorme
- ¿Por que casi no hay insectos marinos y por que casi no hay crustaceos terrestres?

![image-20211014001807282](C:\Users\10\AppData\Roaming\Typora\typora-user-images\image-20211014001807282.png)

![image-20211014002026012](C:\Users\10\AppData\Roaming\Typora\typora-user-images\image-20211014002026012.png)

![image-20211014002139503](C:\Users\10\AppData\Roaming\Typora\typora-user-images\image-20211014002139503.png)

![image-20211014002218268](C:\Users\10\AppData\Roaming\Typora\typora-user-images\image-20211014002218268.png)

![image-20211014002303373](C:\Users\10\AppData\Roaming\Typora\typora-user-images\image-20211014002303373.png)

![image-20211014002414964](C:\Users\10\AppData\Roaming\Typora\typora-user-images\image-20211014002414964.png)

- Se busco para poder sacar el anticoagulante del bicho

- En el genoma mitocondrial se encontraron muchas diferencias entre los isopodos.
- En transcriptomica se hicieron con las muestras de 4 tejidos.

![image-20211014002741499](C:\Users\10\AppData\Roaming\Typora\typora-user-images\image-20211014002741499.png)

![image-20211014002754546](C:\Users\10\AppData\Roaming\Typora\typora-user-images\image-20211014002754546.png)

![image-20211014002833258](C:\Users\10\AppData\Roaming\Typora\typora-user-images\image-20211014002833258.png)

![image-20211014002908292](C:\Users\10\AppData\Roaming\Typora\typora-user-images\image-20211014002908292.png)

![image-20211014002917234](C:\Users\10\AppData\Roaming\Typora\typora-user-images\image-20211014002917234.png)

# Parte 2

La estrategia de secuenciación define el tipo de analisis. Si se utiliza un marcador como el 16s, se utilizaran amplicones. Se utiliza la plataforma de ilumina miseq.

- Si se quiere estar seguro de la especie se tendria que buscar marcadores de copia unica.
- Si se tuviera para cada organismo sus 240 marcadores se podria llegar a sus niveles de especie y subespecie
- El sarscov 2 tuvo que hacerse con metagenomica.
- Muchos infectados y peor, muchas muertes.
- Aun se esta lejos de la inmunidad de rebaño
- El genoma de sarscov 2 es una molecula de cadena sencilla de RNA.
- Tiene inserciones y deleciones
- Conocemos los genes de algunas proteínas entre ellas la mas importante que es la spike con la cual infecta.
- Proteínas de membrana y envoltura.
- 

![image-20211014020754543](C:\Users\10\AppData\Roaming\Typora\typora-user-images\image-20211014020754543.png)

Minuto 10:27

- El virus es una pelota con membrana lipidica y proteinas
- Se aspira y contamina las células que contienen el receptor de angiotensina, interaccionan y se fusiona con la célula para que empiece a producir el material genético del virus.
- Cuando hay muchas particulas virales la célula se revienta y provoca inflamacion y que se pueda transmitir a otras personas
-  Hay que vigilar al virus porque muta y esto le confiere ventajas como mayor virulencia o adaptación a nuevos hospederos.
- El Sars-Cov2 cuenta con muchos hospederos debido a su domino de union a la angiotensina.
- En la siguiente imagen podemos ver el cambio de aminoacido y en que posición
- Gracias a esto podemos ver en que hospederos se ha adaptado
- Aun no conocemos el animal intermediario por el cual se dio el salto a humanos, pudo ser en animal domestico
- En el MERs el intermediario eran los camellos
- En los animales la enfermedad es como un resfriado pero no se conoce toda la sintomatologia.

![image-20211029203431420](C:\Users\10\AppData\Roaming\Typora\typora-user-images\image-20211029203431420.png)

- Variantes de procupación y variantes de interes:

![image-20211029203739382](C:\Users\10\AppData\Roaming\Typora\typora-user-images\image-20211029203739382.png)

- Hay evidencia de laboratorios de que estas variantes pueden escapar parcialmente al sistema inmune.

Las variantes de interes se ha observado que se empiezan a reproducir mucho en un lugar

- Las variantes eventualmente son desplazadas conforme pasa el tiempo

![image-20211029204546654](C:\Users\10\AppData\Roaming\Typora\typora-user-images\image-20211029204546654.png)

![image-20211029204653961](C:\Users\10\AppData\Roaming\Typora\typora-user-images\image-20211029204653961.png)

1. Articulo de como fueron introducidas las variantes a mexico

Muestras de los pacientes en mexico

- Primer paciente viajo a bergamo y contagio a otras seis personas en el avion

![image-20211029204733788](C:\Users\10\AppData\Roaming\Typora\typora-user-images\image-20211029204733788.png)

- Se observaron las variantes en mexico y su distribucion dependiendo de si llegaron de europa o estados unidos.
- A mexico llego la primera variante del mundo, no el virus de wuhan
- La H49Y y la D41 , es una cosa muy particular de las muestras de mexico y luego desaparecieron lo que se conoce como homoplasia.
- Se caracterizo como variante de interes el linaje que estuvo en mexico de manera predominante en octubre y enero del año pasado 

Variantes en mexico

![image-20211029205310297](C:\Users\10\AppData\Roaming\Typora\typora-user-images\image-20211029205310297.png)

- Se hizo la filogenetica y se observo que la variante parental era la B.1.1.222 mas tres mutaciones que acumulo dio origen al linaje B.1.1.519

![image-20211029205500715](C:\Users\10\AppData\Roaming\Typora\typora-user-images\image-20211029205500715.png)

![image-20211029205605002](C:\Users\10\AppData\Roaming\Typora\typora-user-images\image-20211029205605002.png)

- Se observan los linajes por mes

![image-20211029205652442](C:\Users\10\AppData\Roaming\Typora\typora-user-images\image-20211029205652442.png)

- Muestras tomadas en agosto, ahora la mayoria son sublinajes de la variante delta.
