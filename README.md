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

![Skills data science](https://1onjea25cyhx3uvxgs4vu325-wpengine.netdna-ssl.com/wp-content/uploads/2014/11/Data-Science-Skills-Udacity-Matrix.png)

## 2. ¿Que lenguajes de programación necesito para data science?

**Python y/o R, dependiendo de los objetivos que tengas**. Los conceptos clave que son importantes entender antes de brincar a data science es la programación orientada a objetos y la estrutura de datos. El uso de librerías también es imoprtante ya que tienen cargados todos los módulos para facilitar tu trabajo. 

[Python](https://docs.python.org/) es un lenguaje multipropósito, el cual funciona bien si tu trabajo estará vinculado al equipo de desarrollo. Las librerías más importantes que deberías dominar si optas por Python son:

- [*Numpy*](https://numpy.org/doc/) tiene varias funcionalidades de algebra lineal, que te permiten trabajar con vectores (arrays y columnas) y matrices (arrays de arrays y tablas).
- [*Pandas*](https://pandas.pydata.org/docs/): que te permite procesar matrices como si fueran tablas de Exel y manipular datos. También es de utilidad para exportar datos en formato json, excel, csv y más. 
- [*SciPy*](https://www.scipy.org/docs.html): sirve para tener muchas de las funciones estadísticas para trabajar.
- [*Matplotlib*](https://matplotlib.org/3.3.3/contents.html): es la librería principal para visualizar datos, aunque también puedes mirar Plolty y Seaborn.
- [*Scikit Learn*](https://scikit-learn.org/): que tiene varios modulos para realizar machine learning (más de esto a continuación). 
- [*TensorFlow*](https://www.tensorflow.org/api_docs) y [*Pytorch*](https://pytorch.org/docs/stable/index.html): que son las librerías principales para deep learning (más de esto a continuación). 

[R](https://www.rdocumentation.org/) es un lenguaje para uso estadístico y es recomendable aprender cuando no estarás trabajando directamente con un equipo de desarrollo. Las librerías más importantes para data science son: 

- [*ggplot2*](https://ggplot2.tidyverse.org/reference/): que es la librería principal para visualización de datos. 
- [*dplyr*](https://www.rdocumentation.org/packages/dplyr/versions/0.7.8) y [*tidy*](http://www.html-tidy.org/documentation/): con los cuales puedes hacer manipulación de datos. 
- [*mlr3*](https://mlr3.mlr-org.com/): que es la libreria principal para machine learning. Otras librerías interesantes son caret y XGBoost.

Existen otros lenguajes con los que se puede trabajar en Data Science, como [Java](https://towardsdatascience.com/when-to-use-java-as-a-data-scientist-74e5f2ec8c80), [JavaScript](https://js4ds.org/) o [Ruby](https://medium.com/@wowinter13/the-good-the-bad-and-the-ugly-aka-ruby-data-science-f6b729b2bf35). Pero lo más recomendable es iniciar con Python y/o R. 

Toma en consideración aprender a **usar otras herramientas fuera de la programación para el análisis y visualización de datos**. Algunas de las más importantes son Excel, Power BI Tableau o Google Data Studio. 

## 3. ¿Que necesito saber de SQL?

**El mayor valor de [SQL](https://dev.mysql.com/doc/) para un data scientist es la posibilidad de hacer consultas a la bases de datos**. Con SQL puedes crear, modificar, administrar y eliminar bases de datos y columnas. Sin embargo, esta no es tradicionalmente la tarea de un científico de datos. 

- El primer paso para aprender SQL es conocer como realizar consultas usando el standard del lenguage. Es decir, las sentencias SELECT, FROM, WHERE, ORDER BY, GROUP BY, HAVING, AS, WITH y los diferentes JOINS. 
- Despues puedes avanzar a funciones más avanzadas como window functions o trigger functions. Estas pertencen a las particularidades de motores de bases de datos como [MySQL](https://www.mysql.com/), [PostgreSQL](https://www.postgresql.org/), [Oracle](https://www.oracle.com/mx/index.html) o [SQL Server](https://www.microsoft.com/es-mx/sql-server/sql-server-downloads). 
- Finalmente, aprender sobre soluciones de cloud como ([Amazon Web Services](https://aws.amazon.com/), [Google Cloud Platform](https://cloud.google.com/), [Azure](https://azure.microsoft.com/es-mx/), [IBM Cloud](https://cloud.ibm.com/), etc) es importantísimo para aprovechar las bondades de la Big Data (es decir, los millones de tera bytes disponibles). En este sentido, conviene enfocarse a las búsquedas columnares. 

Aunque NoSQL (es decir bases de datos basadas en documentos, key-values, optimizadas para busqueda, para memoria o basadas en grafos) no son parte común del trabajo de un científico de datos, conviene saber algo de [MongoDB](https://www.mongodb.com/es) o [Firebase](https://firebase.google.com/?hl=es) para poder tener un acceso aún mayor a datos.

## 4. ¿Qué es machine learning?

Machine learning es la parte de data science que se encarga de enseñarle a las maquinas una habilidad que no puede ser directamente programada, a partir de datos entrantes. La idea central de de machine learning es encontrar patrones poco obvios entre nuestros data points. De esta manera podemos hacer predicciones a partir de datos históricos. 

Una forma fácil de imaginar esto es que nuestro modelo es un niño que está aprendiendo hablar. Lo que el niño dice depende del vocaublario que le enseñenos. Si al niño le enseñamos groserias, dirá groserías. Si al niño le enseñaos jerga, hablará en jerga. Por ende, una parte importante de entrenar un modelo es obtener datos verídicos y representativos del fenómeno que queremos analizar. 

Dentro de un algoritmo de machine learning encontramos redes neuronales artificiales. Estas redes procuran emular el proceso en el que un cerebro humano aprende. Es decir, a partir de la sinopsis (unión) de neuronas (nodos). 

![Red neuronal machine learning](https://www.analyticsvidhya.com/wp-content/uploads/2016/08/Artificial-Intelligence-Neural-Network-Nodes.jpg)

Una gran ventaja del uso de librerías como ScikitLearn es que estas redes neuronales ya vienen preconstruidas. Por ende, nosotros debemos de preocuparnos solo de los datos que usaremos para entrenar el modelo y los parámetros que optimizaran el aprendizaje. 

## 5. ¿Y que hay con deep learning e inteligencia artificial?

La diferencia entre Deep learning o aprendizaje profundo y machine learning es que Deep Learning usa más de dos capas para entrenar a un modelo. 

![Deep learning](https://miro.medium.com/max/1199/1*N8UXaiUKWurFLdmEhEHiWg.jpeg)

A nivel práctico, los modelos de deep learning se realizan con librerías como TensorFlow y Pytorch. Además de que los problemas que resolvemos en machine learning  tienden a ser enfocados a predecir unidimensionalidades. Es decir: cifras numéricas o textos. En deep learning, las predicciones están más orientadas a identificar multidimensionalidades. Es decir: imágenes, video, audio, etc. 

Otra consideración a la hora de trabajar con Deep Learning es que las librerías con las que trabajamos son de bajo nivel. Lo anterior quiere decir que en TensforFlow y Pytorch debemos de tener más cuidado al diseñar las capas, nodos, tasas de aprendizaje y funciones de activación a diferencia de librerías de alto nivel como Scikit Learn. 

En cuanto Inteligencia Artificial, tanto machine como deep learning son insumos para diseñar inteligencias artificiales. Cuando realizamos una predicción con Machine o Deep Learning ya estamos creando una inteligencia artificial. Por ende, debemos de tener cuidado de los datos que utilizamos para entrenar a nuestra Inteligencia Artificial.

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
- *Operaciones de Vectores y Matrices*: las cuales son utiles para debugar redes neuronales, transformar tu informacion e incluso optimizar calculos.
- *Matrices de covarianza*: que nos permite medir la relación linear dentro de un conjunto de datos.
- *Vectores de soporte*: los cuales son cruciales para entender que separa a grupos de datos cuando hacemos clasificaciones.
- *Análisis de Componentes Principales (PCA)*: que es crucial cuando no podemos decidir cuales son los features que más impactan a un conjunto de datos o el numero de predictores es muy grande y quieres reducirlo. 

**Cálculo**

Con cálculo podemos analizar las tasas de cambio de las cantidades. Esto genera curvas las cuales podemos medir según su longitud u area, que nos permite optimizar nuestros algoritmos de machine learning. En especial, necesitamos cálculos para: 

- *Derivadas e integrales*: es decir, como podemos partir un problema en pedazos más pequeños y luego rearmarlos para entender tasas de cambio. 
- *Gradiente descendente*: con el cual podemos reducir las pérdidas mientras entrenamos un modelo y medir el error de nuestras predicciones.

Las matemáticas suelen ser un tema que asusta y detiene a muchas personas para entrar a data science y machine learning. Mi consejo es: no te preocupes por hacer cálculos (para eso tienes la computadora). Más bien enfócate en desarrollar un pensamiento probablístico y matemático que te lleve a a saber seleccionar la mejor solución para el problema que te estas enfrentando. 

Finalmente, es estadísticamente probable que estes enfrentando un problema que alguien más ya soluciono. La clave del éxito es montarte en hombros de gigante y aprovechar los recursos ya existentes. 

## 7. ¿Que quiere decir conocimientos de negocio?

Al hablar de conocimiento de negocio nos referimos a responder preguntas como:

- *¿Cual es el objetivo de negocio?*
- *¿Cuales son las métricas para medir el éxito del negocio?*
- *¿De donde obtenemos datos para tomar decisiones?*
- *¿Cuales son los datos de valor para el negocio?*

Es importante a tomar en cuenta que los científicos de datos son aquellos que conocen mejor que nadie los datos más importantes de una empresa. Por un lado, un analista de datos o business intelligence se encarga de obtener todos los datos para presentarlos y facilitar la toma de decisiones. La gran diferencia que tienen con un científico de datos es que este último puede hacer uso de machine learning (estadística inferencial) para hacer proyecciones sobre lo que podría suceder con el negocio.

## 8. ¿Que hay que saber sobre visualización de datos?

Comunmente se dice que el data scientist es un story teller. Esto es cierto en el sentido que debe de reconstruir hechos para explicar un fenómeno. Debes de considerar también que como científico de datos, debes de presentar la información a personas que tienes menos conocimientos matemáticos que tú. La forma más adecuada de hacerlo es através de gráficos. 

Lo más recomendable es estudiar para que sirven cada uno de los diferentes gráficos. Así mismo, toma en cuenta sus caracaterísticas únicas para sacarle mayor jugo. 

Matplotlib, Seaborn y Plolty son las librerías principales si programas en Python, mientras ggplot es ideal para R. Fuera del código, vale la pena familiarizarse con Google Data Studio y Tableau para la creación de tableros. 

Por último, recuerda que la visualización de gráficas y la estadística se  pueden usar para confundir o engañar. Hacer uso responsable de estas herramientas es parte importante del trabajo de un científico de datos.

## 9. ¿Jupyter Notebooks o Google Colab?

Un [Jupyter Notebook](https://jupyter.org/) es parte de la colección [Anaconda](https://www.anaconda.com/products/individual) que tiene casí todas las librerías para trabajar en Machine Learning y Data Science. La ventaja que tiene es que puedes probar pedazos de código sin tener la necesidad de saltar entre un IDE y la terminal. 

Por su lado, [Google Colab](https://colab.research.google.com/) tiene casi todas las librerías precargadas y no hay necesidad de instalarlas usando pip. 

Es cuestión de gusto personal cual de los dos usar. La ventaja de Jupypter Notebook es que corre en local host, por lo que no dependes de tu conexión de internet para trabajar. Por otra parte, Anaconda es muy pesado cuando se instalan sus paquetes. Por ello conviene en ese caso trabajar en un Colab, ya que además ofrece memoria RAM suficiente para trabajar. 

## 9. ¿Que debería de saber sobre ingenieria de software/web?

Idealmente, como científico de datos debería de tener una idea clara de como es el desarrollo de software. 

Una de los grandes problemas del gremio es que son muchos los data scientists que solo saben trabajar con Jupyter Notebooks. Es por ello que vale la pena construir ventajas competitivas. Entre las más importantes incluyen:

- Conocer un framework de backend. Si estás trabajando con Python, es recomendable empezar con Django. Aunque Flask o FastAPI con más fáciles de aprender y operar, la mayoría de proyectos profesionales son desarrollados en Django. 
- Cloud, como aquellos que mencionamos en la pregunta 3.
- DevOps es un buen complemento para un científico e ingeniero de datos, ya sea conociendo Bash Shell o administrando servidores Linux. 

## 10. ¿Cual es el flujo de trabajo de un data scientist?

## 11. ¿Cuanto tiempo puedo tardar para adquirir las habilidades para data science?

## 12. ¿Que hay sobre la parte legal y ética?

## 13. ¿Cuales son las opotunidades laborales?

## Algunos pensamientos finales

## Recursos externos

## Contacto 

