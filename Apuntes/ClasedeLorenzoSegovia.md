# Clase de lorenzo segovia

# Puntos importantes:

## Extracción y alineamiento del adn

- Metagenomica del golfo de mexico

- Es caro hacer metagenomica del golfo por el barco y muchos dias

- Se agarraba agua de mar y se filtraba para tener solamente bacterias y se obtenia su adn purificandolo para que se secuenciara

- Joe handelsman

- Habia un numero mayor en la muestra de la que en realidad se pueden hacer crecer, solo el 5% se puede hacer crecer.

- Lo complejo es determinar a que corresponden los pedacitos de DNA.

- D18 max la capa de maxima fluorescencia a 100 metros de profundidad, muchos vibrios. Si se busca entre genomas de bacterias se obtiene un 17% y si se saca de gene bank se gana otro 11% y otro 50% es una perspectiva mas general de otro ambiente.

- Los sedimentos es de las zonas donde menos conocemos cosas.

- Conocer que bacterias nos indica que tan limpio esta el golfo.

- Hay bacterias hidrocarbonoclasticas.

- Esta limpio el golfo.

- No les gusta tanto el chapopote pero no les gusta tanto.

- ¿Que hay en los sedimentos?

  

## Identificación de genes de sintesis de metabolitos secundarios

- En europa hicieron el proyecto Tara que consistio en un barco que tomaba muestras en todo el oceano, pero se procesaba de inmediato debido a que podia ocurrir un efecto botella.
- Se subio esta info a una base de datos.
- Tambien se proporcionan otros datos que se presentaron durante el muestreo como temperatura, ph, salinidad etc.
- Una de sus estudiantes quizo averiguar que tipos de genes antibioticos se podian obtener de las muestras del mar.
- Se buscaron los genes bgcs
- Se reconstruyeron contigs de todo el mar, pero solo se trabajo con lamitad de las muestras.
- Agarro cierto numero de metagenomas en cada mar.
- Se hicieron analisis con AntiSMASH que utiliza varios elementos de analisis de secuencia como los modelos de markov que es un sistema muy sensible para identificar homologia al comparar perfiles de secuencia.
- La caracteristica de los genes que involucran metabolitos secundarios es que forman clusters, por lo que evalua la proximidad entre los genes.
- Ademas identifica dominios y propone la molecula que se ha formado y su función.
- Se identificaron muchas moleculas, muchos de ellos de interes biotecnologico.
- Se encontraron mas putativos, que son nuevos.
- la mitad de los clusters identificados eran putativos.
- Se obtuvieron un cuarto de millon de genes involucrados en metabolismo secundario, los cuales dicen que son bgcs interesantes.
- Genes involucrados en antibioticos particulares.
- Lantibioticos son interesantes.
- El problema de armar los metagenomas es que esta todo en cachos y vuelve dificil encontrar los bacterial gene clusters.
- Ademas suele haber cambios y modificaciones en las moleculas, como peptidos circulares.
- Lo que se buscaba era caracterizar los smcogs
- Para clasificar los datos se utilizaron algoritmos de agrupamiento como:
  - K-means y k-modes -> No salio, los datos eran un desastre
  - orthoMCL -> Hacer anotaciones y utilizarlas para agrupar, pero tambien se debe checar si hay diferencias entre los clusters
- kmeans -> Muchos genes caian en la categoria de sacaridos, las cuales son moleculas para romper biofilms y tienen interes en el fraking.
- Busqueda de parametros en orthomcl, para que los resultados fueran lo mas fiable posibles
- La bioinformatica tambien requiere controles para calibrar el sistema.
- Mediciones de agrupamiento y viendo como se agrupan.
- Buen agrupamiento.
- ¿Cuantas cosas nuevas se encontraran y cuantos grupos podemos identificar con una función en particular?
- 140 grupos nuevos, diferentes y confiables.
- Se encontraron grupos identificables
- 14 grupos de antibioticos nuevos candidatos.
- Muchos de esos que se encontraron son hidrofobicos, por lo que podrian servir como pomada a lo mucho.
- Esto permite entender la biodiversidad y variabilidad.
- Lo malo de los probioticos es que hacen mas lenta la recuperación del microbioma

## The age of the machines

- Ha habido una gran explosión respecto a la inteligencia artificial y todo lo relacionado con el computo
- Alphafold2 es un programa que hace propuestas para la predicción estructural en tercera dimensión de una proteína. Muy poderoso
- La diferencia entre machine learning son las clasificaciones que llevan a arboles de decisión. Haciendo una red neural.

![image-20211012200100630](C:\Users\10\AppData\Roaming\Typora\typora-user-images\image-20211012200100630.png)

El chiste de las redes neurales es que se podrán definir pesos y el algoritmo para obtener determinado resultado.

- Muchos datos
- Hay que dividir los datos anotados en un set de entrenamiento y otro de validación.
- loss function es una función de calificación que define que tan bien se esta realizando la clasificación.
- Descenso de gradiente, que tan cerca me estoy acercando al minimo.
- Llegar al valle que yo quiero llegar
- Hay que meter mas capas a las redes neuronales. Poner reglas en lo profundo, para que sea confiable en el reconocimiento.
- Ven distribuciones de valores en un vector.
- Hacer convolución para transformar muchos datos en valores mas pequeños que resumen la información.
- Se esta desarrollando una red neuronal para los datos de metagenomica del oceano ya que estos clasificadores son mejores que los de machine learning.
- Se pueden incluir todos los genes.

## Pan BCGS

- Una de las cosas que se saben en los BCGs es que a veces estan todos los genes juntos pero a veces hay nuevas combinaciones de genes, no se sabe si son excluyentes o no se han encontrado juntos.
- Se quiere experimentar moviendo los genes para ver que tanto se modifica la molecula original.
- Ver que cobinaciones se pueden hacer entre el core y los cloud
- Las nrp, son modulares y cada uno de los modulos reconocen un aminoacido diferente.
- Se hacen modificaciones de la moleculas que poseen decoraciones distintas las cuales les atribuiran diferentes.
- De esta manera podremos ver las diferentes funciones que se pueden tener.
- Se uso levadura
- Es muy practico usar levadura porque practicamente se le pueden añadir cromosomas bacterianos.
- Es sencillo trabajar con ecoli, por lo que se utilizaron BCGs parecidos a ecoli

## MAGS

- MAGS -> Procura que el armado de metagenomas se vea casi bien.

- Se ensamblan los cachitos con megahit

- Que genes hay en los cachitos, a que especie pertenece

- Busquedas con diamond para determinar que tanto se parecen.

- Binning -> Clasificación de contigs como provenientes de un mismo genoma de acuerdo a su composición:

  - Dos algoritmos: Maxbin y Metabat
  - Anotar los genomas de acuerdo a lo que se parece, contaminación y su calificación de completes
  - union de resultados con DAS tool
  - Calculo de coberturas y valores con RPKM

- Contaminación baja es un buen armado del genoma.

- Se encontro:

  - Tres nuevos ordenes
  - Dos nuevas familias
  - Una nueva especie

  







