# Algunas Preguntas Frecuentes Sobre Data Science y Machine Learning

Desde que inicié este lindo recorrido llamado Ciencia de datos, me he dado cuenta que las personas tienen las mismas dudas. Ya sea cuando apenas están arrancando con esta disciplina ó incluso si llevan algún tiempo. Lo que intento con esto es resumir algunas de las respuestas a preguntas frecuentes. Aquí también podrás encontrar recursos para cada una de ellas. 

Mi recomendación es usar esto como una guía de estudio y un checklist de skills por desarrollar. 

Si este repositorio es de valor para tí, no olvides darle fork y estrellita. 

Sin más retraso, acá hay algunas de las preguntas más frecuentes entre las personas que estan estudiando Data Science y Machine Learning. 

## 1. ¿Qué habilidades concretas necesito para arrancar con Data Science?

La ciencia de datos son básicamente tres cosas:

- **Ciencias de la Computación**: programación, para ser más específicos
- **Matemáticas**: estadística mayormente, algo de álgebra lineal y cálculo
- **Conocimiento de negocio**

Para ser un científico de datos hay que desarrollar estas tres areas. También hay que tener en cuenta que Data Science tiene varias subramas:

- **Análisis de Datos y Business Intelligence**: que se encarga de tomar los datos recogidos para analisis respecto a una necesidad de negocio y ayudar a los líderes a toamr decisiones basadas en datos. 
- **Ingenieria y Arquitectura de Datos**: que se encarga del proceso de ETL (extraer, transformar y cargar). Es decir, tomar datos de diferentes fuentes (bases de datos, web scraping, APIs, etc), limpiar los datos y entregarlos en un sitio donde los científicos de datos podrán disponer de ellos (data warehouses, bases de datos, cloud, etc).
- **Científico de datos**: que se encarga de tareas similares al analista de datos, aunado a utilizar la data disponible para entrenar modelos de machine learning.
- **Ingenieros de Machine Learning, Deep Learning e Inteligencia Artificial**: que se encargan no solo de entrenar modelos con la data discponible, sino también desplegarlos para que sigan siendo re-entrenados con data entrante.

Para cada una de estas subramas, las habilidades especificas que necesitas son las siguientes:



## 2. ¿Que lenguajes de programación necesito para data science?

**Python y/o R, dependiendo de los objetivos que tengas**. Los conceptos clave que son importantes entender antes de brincar a data science es la programación orientada a objetos y la estrutura de datos. El uso de librerías también es imoprtante ya que tienen cargados todos los módulos para facilitar tu trabajo. 

Python es un lenguaje multipropósito, el cual funciona bien si tu trabajo estará vinculado al equipo de desarrollo. Las librerías más importantes que deberías dominar si optas por Python son:

- *Numpy* tiene varias funcionalidades de algebra lineal, que te permiten trabajar con vectores (arrays y columnas) y matrices (arrays de arrays y tablas).
- Pandas: que te permite procesar matrices como si fueran tablas de Exel y manipular datos. También es de utilidad para exportar datos en formato json, excel, csv y más. 
- *SciPy*: sirve para tener muchas de las funciones estadísticas para trabajar.
- *Matplotlib*: es la librería principal para visualizar datos, aunque también puedes mirar Plolty y Seaborn.
- *Scikit Learn*: que tiene varios modulos para realizar machine learning (más de esto a continuación). 
- *TensorFlow y Pytorch*: que son las librerías principales para deep learning (más de esto a continuación). 

R es un lenguaje para uso estadístico y es recomendable aprender cuando no estarás trabajando directamente con un equipo de desarrollo. Las librerías más importantes para data science son: 

- *ggplot2*: que es la librería principal para visualización de datos. 
- *dplyr y tidy*: con los cuales puedes hacer manipulación de datos. 
- *mlr3*: que es la libreria principal para machine learning. Otras librerías interesantes son caret y XGBoost.

Existen otros lenguajes con los que se puede trabajar en Data Science, como Java, JavaScript o Ruby. Pero lo más recomendable es iniciar con Python y/o R. 

Toma en consideración aprender a **usar otras herramientas fuera de la programación para el análisis y visualización de datos**. Algunas de las más importantes son Excel, Power BI Tableau o Google Data Studio. 

## 3. ¿Que necesito saber de SQL?

El mayor valor de SQL para un data scientist es la posibilidad de hacer consultas a la bases de datos. Con SQL puedes crear, modificar, administrar y eliminar bases de datos y columnas. Sin embargo, esta no es tradicionalmente la tarea de un científico de datos. 

- El primer paso para aprender SQL es conocer como realizar consultas usando el standard del lenguage. Es decir, las sentencias SELECT, FROM, WHERE, ORDER BY, GROUP BY, HAVING, AS, WITH y los diferentes JOINS. 
- Despues puedes avanzar a funciones más avanzadas como window functions o trigger functions. Estas pertencen a las particularidades de motores de bases de datos como MySQL, PostgreSQL, Oracle o SQL Server. 
- Finalmente, aprender sobre soluciones de cloud como (Amazon Web Services, Google Cloud Platform, Azure, IBM, etc) es importantísimo para aprovechar las bondades de la Big Data (es decir, los millones de tera bytes disponibles). En este sentido, conviene enfocarse a las búsquedas columnares. 

Aunque NoSQL (es decir bases de datos basadas en documentos, key-values, optimizadas para busqueda, para memoria o basadas en grafos) no son parte común del trabajo de un científico de datos, conviene saber algo de MongoDB o Firebase para poder tener un acceso aún mayor a datos.

## 4. ¿Qué es machine learning?

Machine learning es la parte de data science que se encarga de ensñarle a las maquinas una habilidad que no puede ser directamente programada, a partir de datos entrantes. La idea central de de machine learning es encontrar patrones poco obvios entre nuestros data points. De esta manera podemos hacer predicciones a partir de datos históricos. 

Una forma fácil de imaginar esto es que nuestro modelo es un niño que está aprendiendo hablar. Lo que el niño dice depende del vocaublario que le enseñenos. Si al niño le enseñamos groserias, dirá groserías. Si al niño le enseñaos jerga, hablará en jerga. Por ende, una parte importante de entrenar un modelo es obtener datos verídicos y representativos del fenómeno que queremos analizar. 

Habiendo dicho lo anterior, lo que hay que entender es que

XXXX

## 5. ¿Y que hay con deep learning e inteligencia artificial?

## 6. ¿Que matemáticas necesito?

**No necesitas matemáticas para arrancar con data science, pero es una habilidad que necesitarás para dominar esta discplina**. Lo más importante es que entiendas e internalices los conceptos matemáticos clave. La computadora es la encargada de realizar los cálculos necesarios, por lo que debes concentrarte en conocer cuales son las herramientas matemáticas que pueden explicar el fenómeno que estas analizando. 

Específicamente, necesitas saber lo siguiente:

**Estadística básica**

Durante el Análisis Exploratorio de Datos, tendrás que aplicar los conceptos elementales de estadística. En un principio tienes un número de data points, los cuales necesitan ser comprendidos antes de ser procesdos en un modelo de machine o deep learning. Cuando queremos entender los datos, estamos hablando de estadística descrpitiva. Los conceptos clave a entender son:

- *Media, moda, mediana*: lo cual nos dice que tan frecuentes son ciertos datos y nos permite identificar datos raros (mejor conocidos como outliers).
- *Distribución, varianzas y desviaciones estándard*: con lo que podemos identificar rangos dentro de los cuales se encuentran la mayoría de nuestros datos.
- *Teorema de Bayes y probabilidades condicionales*: : es decir la posibilidad de que ocurra un evento dado eventos o información previa. 
- *Diseño de experimentos*: saber crear hipótesis que pondrás aprueba con la evidencia (datos) con la que dispongas. 

**Estadística avanzada**

En el caso de estadística avanzada, nos enfocamos a usar la estadística para explicar los algoritmos de machine learnig. En este caso, queremos usar datos históricos para predecir eventos o datos futuros. A esto lo llamamos estadística inferencial. Lo importante a entender es:

- *Regresion lineal*: es decir, encontrar relaciones lineales entre conjuntos de datos. Por ejemplo, a más horas de ejercicio (variable correlacionada 1) habrá menos colesterol en la sangre (variable correlacionada 2). 
- *Regresión logística y ensayos de Bernoulli*: en donde el resultado solo puede ser binario (cierto o falso). Por ejemplo, una mujer está embarazada o no. 
- *Clasificación estadística y Naive Bayes*: que nos ayudar a agrupar datos según sus características. Comprender esto te permitirá avanzar con algoritmos como KNN o clustering. 
- *Series de Tiempo*: lo cual nos permite ver la evolución através del tiempo. Por ejemplo, precios de acciones en la bolsa de valores. 
- *Estimadores de máxima verosimilitud*: que nos permite definir los parámetros para mejorar el desempeño de nuestro modelo. 

**Algebra lineal**

La algebra lineal nos permite tener un entendimiento más afondo de los algoritmos de machine learning y como sacarles mayor provecho. En particular, vale la pena tener en cuenta lo siguiente:

- *Normas de vectores y distancias euclidianas*: que nos permite endender nuestras funciones de pérdida. Es decir, cuanto nuestro modelo deja de aprender a medida que procesa los datos o lo muy alejado que se encuentra nuestra prediccion de la realidad.
- *Regularizaciones*: para prevenir que nuestro modelo se sobre-ajuste a los datos que le hemos dado. 
- *Matrices de covarianza*: que nos permite medir la relación linear dentro de un conjunto de datos.
- *Vectores de soporte*: los cuales son cruciales para entender que separa a grupos de datos cuando hacemos clasificaciones.
- *Análisis de Componentes Principales (PCA)*: que es crucial cuando no podemos decidir cuales son los features que más impactan a un conjunto de datos o el numero de predictores es muy grande. 

**Cálculo**

Con cálculo podemos analizar las tasas de cambio de las cantidades. Esto genera curvas las cuales podemos medir según su longitud u area, que nos permite optimizar nuestros algoritmos de machine learning. En especial, necesitamos cálculos para: 

- *Derivadas e integrales*: es decir, como podemos partir un problema en pedazos más pequeños y luego rearmarlos para entender tasas de cambio. 
- *Gradiente descendente*: con el cual podemos reducir las pérdidas mientras entrenamos un modelo y medir el error de nuestras predicciones.

Las matemáticas suelen ser un tema que asusta y detiene a muchas personas para entrar a data science y machine learning. Mi consejo es: no te preocupes por hacer cálculos (para eso tienes la computadora). Más bien enfócate en desarrollar un pensamiento probablístico y matemático que te lleve a a saber seleccionar la mejor solución para el problema que te estas enfrentando. 

Finalmente, es estadísticamente probable que estes enfrentando un problema que alguien más ya soluciono. La clave del éxito es montarte en hombros de gigante y aprovechar los recursos ya existentes. 

## 7. ¿Que quiere decir conocimientos de negocio?

## 8. ¿Que hay que saber sobre visualización de datos?

## 9. ¿Que debería de saber sobre ingenieria de software/web?

## 10. ¿Cual es el flujo de trabajo de un data scientist?

## 11. ¿Cuanto tiempo puedo tardar para adquirir las habilidades para data science?

## 12. ¿Que hay sobre la parte legal y ética?

## 13. ¿Cuales son las opotunidades laborales?

## Algunos pensamientos finales

## Recursos externos

## Contacto 

