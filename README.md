# **Apuntes de pyspark**
![Alt Text](https://github.com/Origamologo/pyspark/blob/main/pics/pikachu.gif)

#
:rotating_light: <span style="color:red;">**AVISO**</span> :rotating_light:

* Estos apuntes de pyspark están guapísimos porque se han hecho siguiendo el curso *Big Data y Spark: ingeniería de datos con Python y pyspark*, que está guapísimo y que podéis encontrar [aquí](https://www.udemy.com/course/big-data-y-spark-ingenieria-de-datos-con-python-y-pyspark/?referralCode=F123CAABFC966F4483EC).
* En los apuntes se llama a diferentes fuentes de datos que no están incluídas en este repo. Las encontrareis en el [curso](https://www.udemy.com/course/big-data-y-spark-ingenieria-de-datos-con-python-y-pyspark/?referralCode=F123CAABFC966F4483EC).
* El código a veces difiere, en ocasiones bastante, de lo que se ve en el [curso](https://www.udemy.com/course/big-data-y-spark-ingenieria-de-datos-con-python-y-pyspark/?referralCode=F123CAABFC966F4483EC), sobre todo en la resolución de los ejercicios. Esto se debe a dos motivos:
  1. En el [curso](https://www.udemy.com/course/big-data-y-spark-ingenieria-de-datos-con-python-y-pyspark/?referralCode=F123CAABFC966F4483EC) se hace todo en google collab y yo lo he hecho en local.
  2. Tengo mi propio estilo y manías programando y hay cosas que me gustan de una manera en concreto. Esto no significa que piense que el instructor, que es excelente, lo haga mal, tan sólo quuiere decir que tengo mis manías.\

:warning: Baja un poco más y podrás ver el índice temático con lo que se cubre en cada lección, así te será más fácil encontrar información sobre una temática en concreto.
#
## Contenido

Los apuntes constan de 7 lecciones que encontrarás en  :open_file_folder: Lecciones\
A cada lección le corersponde un jupyter con ejercicios que encontrarás en  :open_file_folder: Ejercicios

## Índice

### :open_file_folder: Lecciones:

#### :mortar_board: **1_SparkSession_RDD.ipynb**
  1. **SparkSession**
     * ¿Qué es?
     * ¿Cómo se crea?
  2. **RDD**
     * ¿Qué es?
     * ¿Cómo se crea?

#### :mortar_board: **2_Transformaciones_RDD.ipynb**
  1. **Transformaciones en un RDD**
     * Tipos de transformaciones
       
       1-1. **Función map**\
       1-2. **Función flatMap**\
       1-3. **Función filter**\
       1-4. **Función coalesce**\
       1-5. **Función repartition**\
       1-6. **Función reduceByKey**


#### :mortar_board: **3_Acciones_RDD.ipynb**
  1. **Acciones en un RDD**
     * Tipos de acciones

       1-1. **Función reduce**\
       1-2. **Función count**\
       1-3. **Función collect**\
       1-4. **Funciones take, max y saveAsTextFile**
