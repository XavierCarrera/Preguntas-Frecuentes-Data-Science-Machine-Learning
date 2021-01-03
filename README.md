# Algunas Preguntas Frecuentes Sobre Data Science y Machine Learning

Desde que inicié este lindo recorrido llamado Ciencia de datos, me he dado cuenta que las personas tienen las mismas dudas. Ya sea cuando apenas están arrancando con esta disciplina ó incluso si llevan algún tiempo. Lo que intento con esto es resumir algunas de las respuestas a preguntas frecuentes. Aquí también podrás encontrar recursos para cada una de ellas. 

Mi recomendación es usar esto como una guía de estudio y un checklist de skills por desarrollar. 

Si este repositorio es de valor para tí, no olvides darle fork y estrellita. 

Sin más retraso, acá hay algunas de las preguntas más frecuentes entre las personas que estan estudiando Data Science y Machine Learning. 

## 1. ¿Qué habilidades concretas necesito para arrancar con Data Science?

La ciencia de datos son básicamente tres cosas:

- **Ciencias de la Computación**: Programación, para ser más específicos.
- **Matemáticas**: Estadística mayormente, álgebra lineal y cálculo.
- **Conocimiento de negocio**: Con esta le daras contexto a tus analisis.

Para ser un científico de datos hay que desarrollar estas tres areas. También hay que tener en cuenta que Data Science tiene varias subramas:

- **Análisis de Datos y Business Intelligence**: que se encarga de tomar los datos recogidos para analisis respecto a una necesidad de negocio y ayudar a los líderes a tomar decisiones basadas en datos. 
- **Ingenieria y Arquitectura de Datos**: que se encarga del proceso de ETL (extraer, transformar y cargar). Es decir, tomar datos de diferentes fuentes (bases de datos, web scraping, APIs, etc), limpiar los datos y entregarlos en un sitio donde los científicos de datos podrán disponer de ellos (data warehouses, bases de datos, cloud, etc).
- **Científico de datos**: que se encarga de tareas similares al analista de datos, aunado a utilizar la data disponible para entrenar modelos de predictivos.
- **Ingenieros de Machine Learning, Deep Learning e Inteligencia Artificial**: que se encargan no solo de entrenar modelos con la data discponible, sino también desplegarlos, mantenerlos actualizados, monitorearlos y generar pipelines para orquestar todos estos procesos automaticamente.

Para cada una de estas subramas, las habilidades especificas que necesitas son las siguientes:
<br></br>
<p align="center">
    <img src="https://1onjea25cyhx3uvxgs4vu325-wpengine.netdna-ssl.com/wp-content/uploads/2014/11/Data-Science-Skills-Udacity-Matrix.png" alt="Data Science Skills" style="display:block;margin-left:auto;margin-right:auto;width:90%">
</p>
<p align="center">Fig 1. Data Science Skills</p>

## 2. ¿Que lenguajes de programación necesito para data science?

**Python y/o R, dependiendo de los objetivos que tengas**. Los conceptos clave que son importantes entender antes de brincar a data science es la programación orientada a objetos y las estruturas de datos. El uso de librerías también es imoprtante ya que tienen cargados todos los módulos para facilitar tu trabajo. 

[Python](https://docs.python.org/) es un lenguaje multipropósito, el cual funciona bien si tu trabajo estará vinculado al equipo de desarrollo. Las librerías más importantes que deberías dominar si optas por Python son:

- [*Numpy*](https://numpy.org/doc/): Tiene varias funcionalidades de algebra lineal, que te permiten trabajar con vectores (arrays y columnas) y matrices (arrays de arrays y tablas).
- [*Pandas*](https://pandas.pydata.org/docs/): Te permite procesar y manipular datos como si fueran tablas de Excel utilizando Data Frames. También es de utilidad para exportar datos en formato json, excel, csv y más. 
- [*SciPy*](https://www.scipy.org/docs.html): Es una extension de numpy la cual añade mas funcionalidades de estadísticas, algebra lineal, integracion, optimizacion, etc.
- [*Matplotlib*](https://matplotlib.org/3.3.3/contents.html): Es la librería principal para visualizar datos, aunque también puedes mirar [Ploty](https://plotly.com/python/) y [Seaborn](https://seaborn.pydata.org/).
- [*Scikit Learn*](https://scikit-learn.org/): Tiene varios modulos para realizar machine learning (más de esto a continuación). 
- [*TensorFlow*](https://www.tensorflow.org/api_docs) y [*Pytorch*](https://pytorch.org/docs/stable/index.html): Son librerías de diferenciacion automatica principalmente usadas para deep learning (más de esto a continuación). 

[R](https://www.rdocumentation.org/) es un lenguaje para uso estadístico y es recomendable aprender cuando no estarás trabajando directamente con un equipo de desarrollo. Las librerías más importantes para data science son: 

- [*ggplot2*](https://ggplot2.tidyverse.org/reference/): La cual es la librería principal para visualización de datos. 
- [*dplyr*](https://www.rdocumentation.org/packages/dplyr/versions/0.7.8) y [*tidy*](http://www.html-tidy.org/documentation/): Con los cuales puedes hacer manipulación de datos. 
- [*mlr3*](https://mlr3.mlr-org.com/): Es la libreria principal para machine learning. Otras librerías interesantes son [Caret](https://topepo.github.io/caret/) y [XGBoost](https://xgboost.readthedocs.io/en/latest/R-package/index.html#).

Existen otros lenguajes con los que se puede trabajar en Data Science, como [Java](https://towardsdatascience.com/when-to-use-java-as-a-data-scientist-74e5f2ec8c80), [JavaScript](https://js4ds.org/), [Ruby](https://medium.com/@wowinter13/the-good-the-bad-and-the-ugly-aka-ruby-data-science-f6b729b2bf35), [Scala](https://towardsdatascience.com/scala-for-data-science-engineering-part-1-6a0a5738d7b0) o [Julia](https://towardsdatascience.com/introducing-julia-an-alternative-to-python-and-r-for-data-science-dcbf98346253). Pero lo más recomendable es iniciar con Python y/o R. 

Toma en consideración aprender a **usar otras herramientas fuera de la programación para el análisis y visualización de datos**. Algunas de las más importantes son [Excel](https://towardsdatascience.com/excel-for-data-science-a82247670d7a), [Power BI](https://towardsdatascience.com/tagged/power-bi), [Tableau](https://towardsdatascience.com/is-tableau-useful-for-data-scientists-46d355a14b62) o [Google Data Studio](https://towardsdatascience.com/tagged/google-data-studio). 

## 3. ¿Que necesito saber de SQL?

**El mayor valor de [SQL](https://es.wikipedia.org/wiki/SQL) para un data scientist es la posibilidad de hacer consultas a la bases de datos**. Con SQL puedes crear, modificar, administrar y eliminar bases de datos y columnas. Sin embargo, esta no es tradicionalmente la tarea de un científico de datos. 

- El primer paso para aprender SQL es conocer como realizar consultas usando el estandar del lenguaje. Es decir, las sentencias SELECT, FROM, WHERE, ORDER BY, GROUP BY, HAVING, AS, WITH y los diferentes JOINS. 
- Despues puedes avanzar a funciones más avanzadas como window functions, trigger functions, stored procedures, tablespaces y PLSQL. Estas pertencen a las particularidades de motores de bases de datos como [MySQL](https://www.mysql.com/), [PostgreSQL](https://www.postgresql.org/), [Oracle](https://www.oracle.com/mx/index.html) o [SQL Server](https://www.microsoft.com/es-mx/sql-server/sql-server-downloads). 
- Finalmente, aprender sobre soluciones de cloud como ([Amazon Web Services](https://aws.amazon.com/es/products/databases/), [Google Cloud Platform](https://cloud.google.com/products/databases), [Azure](https://azure.microsoft.com/es-es/product-categories/databases/), [IBM Cloud](https://www.ibm.com/cloud/databases), etc) es importantísimo para aprovechar las bondades de la Big Data (es decir, los millones de tera bytes disponibles). Por otra parte, para analisis conviene enfocarse a las búsquedas columnares con motores como [Redshift](https://aws.amazon.com/es/redshift/) o [Big Query](https://cloud.google.com/bigquery) las cuales son las mas populares . 

Aunque NoSQL (es decir bases de datos basadas en documentos, key-values, optimizadas para busqueda, para memoria o basadas en grafos) no son parte común del trabajo de un científico de datos conviene saber algo de ellas, algunas poplares son [MongoDB](https://www.mongodb.com/es) o [Firebase](https://firebase.google.com/?hl=es) para poder tener un acceso aún mayor a datos.

## 4. ¿Qué es machine learning?

Machine learning es la parte de data science que se encarga de crear modelos que generen predicciones a partir de datos históricos. La idea central de de machine learning es encontrar patrones poco obvios entre nuestros data points. 

Una forma fácil de imaginar esto es que nuestro modelo es un niño que está aprendiendo hablar. Lo que el niño dice depende del vocaublario que le enseñenos. Si al niño le enseñamos groserias, dirá groserías. Si al niño le enseñaos jerga, hablará en jerga. Por ende, una parte importante de entrenar un modelo es obtener datos verídicos y representativos del fenómeno que queremos analizar. 

Dentro de un algoritmo de machine learning encontramos redes neuronales artificiales. Estas redes procuran emular el proceso en el que un cerebro humano aprende. Es decir, a partir de la sinapsis (unión) de neuronas (nodos). Los nodos se las redes neuronales están divididos en nodos de entrada, nodos en capas escondidas y nodos de salida.
<br></br>
<img src="https://www.analyticsvidhya.com/wp-content/uploads/2016/08/Artificial-Intelligence-Neural-Network-Nodes.jpg" alt="Data Science Skills" style="display:block;margin-left:auto;margin-right:auto;width:90%">
<p style="text-align:center;">Fig 2. Red Neuronal, machine learning</p>

Una gran ventaja del uso de librerías como Scikit Learn es que lo modelos ya estan preconstruidas. Por ende, nosotros debemos de preocuparnos solo de los datos que usaremos para entrenar el modelo y los hiperparámetros que optimizaran el aprendizaje. 

Para poder realizar machine learning adecuadamente es recomendable analizar bien el problema que atendemos para saber que algoritmo es el más recomendable.
<br></br>
<img src="https://scikit-learn.org/stable/_static/ml_map.png" alt="Data Science Skills" style="display:block;margin-left:auto;margin-right:auto;width:90%">
<p style="text-align:center;">Fig 3. <a href="https://scikit-learn.org/stable/tutorial/machine_learning_map/index.html">Cheat sheet para seleccion de modelo con Scikit learn</a></p>

Al mismo tiempo, hay que conocer la teoría detrás de estos algoritmos (en gran medida basada en estadística bayesiana). Aunque puedes empezar haciendo machine leaning sin conocimientos matemáticos, es importante que evenutalmente también seas consciente de eso para poder optimizar mejor tus modelos. 

## 5. ¿Y que hay con deep learning e inteligencia artificial?

Principalmente la Inteligencia artificial es un super set del Machine Learning y este a su vez del Deep learning. La inteligencia artificial en ciencias de la computacion, es darle a una maquina una capacidad "cognitiva" de resolver una tarea.
La diferencia entre Deep learning o aprendizaje profundo y machine learning es que el Deep learning puede aprovechar su arquitectura para llevar a cabo transformaciones lineales, con las cuales es posible hacer que la maquina aprenda features no necesariamente explicitas, que pueden estar presentes en cualquier tipo de dato que se utilice para entrenar el modelo. 
<br></br>
<p align="center">
    <img src="https://miro.medium.com/max/1199/1*N8UXaiUKWurFLdmEhEHiWg.jpeg" alt="Data Science Skills">
</p>
<p align="center">Fig 4. Deep Learning / Deep Artificial Neural Network</p>


A nivel práctico, los modelos de deep learning se realizan con librerías de diferenciacion automatica como TensorFlow y Pytorch. Además de que los problemas que resolvemos en machine learning  tienden a ser enfocados a predecir unidimensionalidades. Es decir: cifras numéricas o textos. En deep learning, las predicciones están más orientadas a identificar multidimensionalidades. Es decir: imágenes, video, audio, etc. 

Otra consideración a la hora de trabajar con Deep Learning es que las librerías con las que trabajamos son de bajo nivel. Lo anterior quiere decir que en TensforFlow y Pytorch debemos de tener más cuidado al diseñar las capas, nodos, tasas de aprendizaje y funciones de activación a diferencia de librerías de alto nivel como Scikit Learn. 

En cuanto Inteligencia Artificial, tanto machine como deep learning son insumos para diseñar inteligencias artificiales. Cuando realizamos una predicción con Machine o Deep Learning ya estamos creando una inteligencia artificial. Por ende, debemos de tener cuidado de los datos que utilizamos para entrenarla.

## 6. ¿Que matemáticas necesito?

**No necesitas matemáticas para arrancar con data science, pero es una habilidad que necesitarás para dominar esta discplina**. Lo más importante es que entiendas e internalices los conceptos matemáticos clave. La computadora es la encargada de realizar los cálculos necesarios, por lo que debes concentrarte en conocer cuales son las herramientas matemáticas que pueden explicar el fenómeno que estas analizando. 

Específicamente, necesitas saber lo siguiente:

**Estadística básica**

Durante el Análisis Exploratorio de Datos, tendrás que aplicar los conceptos elementales de estadística. En un principio tienes un número de data points, los cuales necesitan ser comprendidos antes de ser procesdos en un modelo de machine o deep learning. Cuando queremos entender los datos, estamos hablando de estadística descrpitiva. Los conceptos clave a entender son:

- *Media, moda, mediana*: Lo cual nos dice que tan frecuentes son ciertos datos y nos permite identificar datos raros (mejor conocidos como outliers).
- *Varianzas y desviaciones estándard*: Con lo que podemos identificar rangos dentro de los cuales se encuentran la mayoría de nuestros datos.
- *Distribuciónes*: Las cuales asignan una probabilidad a cada valor dentro de los datos.
- *Teorema de Bayes y probabilidades condicionales*: Es decir como se ven afectados las probabilidades de los eventos estudiados dado la informacion de algun otro fenomeno que les afecte. 
- *Diseño de experimentos*: Saber crear hipótesis que pondrás aprueba con la evidencia (datos) con la que dispongas. 

**Estadística avanzada**

En el caso de estadística avanzada, nos enfocamos a usar la estadística para explicar los algoritmos de machine learnig. En este caso, queremos usar datos históricos para predecir eventos o datos futuros. A esto lo llamamos estadística inferencial. Lo importante a entender es:

- *Regresion lineal*: Es decir, encontrar relaciones lineales entre conjuntos de datos. Por ejemplo, a más horas de ejercicio (variable correlacionada 1) habrá menos colesterol en la sangre (variable correlacionada 2). 
- *Regresión logística y ensayos de Bernoulli*: En donde el resultado solo puede ser binario (cierto o falso). Por ejemplo, una mujer está embarazada o no. 
- *Clasificación estadística y Naive Bayes*: que nos ayuda a agrupar datos según sus características. Comprender esto te permitirá avanzar con algoritmos como KNN o clustering. 
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
- *Autocomposiciones*: Se trata de estudiar un poco las matrices ya que algunas de elals poseen ciertas porpiedades que permiter optimizar calculos, entre ellas podemos encontrar los autovalores y autovectores.


**Cálculo**

Con cálculo podemos analizar las tasas de cambio de las cantidades. Esto genera curvas las cuales podemos medir según su longitud u area, que nos permite optimizar nuestros algoritmos de machine learning. En especial, necesitamos cálculo para: 

- *Derivadas*: Usualemente para entener variaciones variables respecto a otras, principalmente utilizada en los algorimos de Deep Learning en el paso de backpropagation y se aplican a traves de regla de cadena. 
- *Algoritmos de Optimizacion*: En general el aprendizaje de maquina los algoritmos de optimizacion se utilizan para hallar el valor que se acerque mas a nuestro objetivo, sea este hacer una regresion o clasificacion. Entre los algoritmos mas usados esta el Gradiente descendiente, pero tambien se encuenta el gradiente adaptativo y momentum. 
- *Diferenciacion Automatica*: Dentro del Deep learning, en realidad, la transformacion de datos se da a traves de la construccion de un grafo computacional, y se aprochan para formar funciones las cuales se pueden derivar, en general este parte la cumplen librerias como Tensorflo y Pytorch.
- *Integracion*: La integracion es el metodo para encontrar el area bajo la curva y puede ser utilizado como metrica en algoritmos de clasificacion, un ejemplo de este es las metrica AUC que literalmente se conoce como Area Under the Curve del comportamiento de un clasificador.
- *Calculo Multivariable*: El cual permitira enfrentarse a problemas con mas de una variable utilizando conceptos fundamentalmente similares de derivacion e integracion. Son importantes para hablar de reglas de cadena, convergencia, divergencia y gradientes.

Las matemáticas suelen ser un tema que asusta y detiene a muchas personas para entrar a data science y machine learning. Mi consejo es: no te preocupes por hacer cálculos (para eso tienes la computadora). Más bien enfócate en desarrollar un pensamiento probablístico y matemático que te lleve a a saber seleccionar la mejor solución para el problema que te estas enfrentando. 

Finalmente, es estadísticamente probable que estes enfrentando un problema que alguien más ya soluciono. La clave del éxito es montarte en hombros de gigante y aprovechar los recursos ya existentes. 

## 7. ¿Que quiere decir conocimientos de negocio?

Al hablar de conocimiento de negocio nos referimos a responder preguntas como:

- *¿Cual es el objetivo de negocio?*
- *¿Cuales son las métricas para medir el éxito del negocio?*
- *¿De donde obtenemos datos para tomar decisiones?*
- *¿Cuales son los datos de valor para el negocio?*

Es importante a tomar en cuenta que los científicos de datos son aquellos que conocen mejor que nadie los datos más importantes de una empresa. Por un lado, un analista de datos o business intelligence se encarga de obtener todos los datos para presentarlos y facilitar la toma de decisiones. La gran diferencia que tienen con un científico de datos es que este último puede hacer uso de machine learning y estadística inferencial para hacer proyecciones sobre lo que podría suceder con el negocio.

## 8. ¿Que hay que saber sobre visualización de datos?

Comunmente se dice que el data scientist es un story teller. Esto es cierto en el sentido que debe de reconstruir hechos para explicar un fenómeno. Debes de considerar también que como científico de datos, debes presentar la información a personas que tienen menos conocimientos matemáticos que tú. La forma más adecuada de hacerlo es [através de gráficos](https://www.data-to-viz.com/). 

Lo más recomendable es estudiar para que sirven cada uno de los diferentes gráficos. Así mismo, toma en cuenta sus caracaterísticas únicas para sacarle mayor jugo. 

Matplotlib, Seaborn y Plolty son las librerías principales si programas en Python, mientras ggplot es ideal para R. Fuera del código, vale la pena familiarizarse con Google Data Studio y Tableau para la creación de tableros. 

Por último, recuerda que la visualización de gráficas y la estadística se pueden usar para confundir o engañar. Hacer uso responsable de estas herramientas es parte importante del trabajo de un científico de datos.

## 9. ¿Jupyter Notebooks o Google Colab?

Un [Jupyter Notebook](https://jupyter.org/) es parte de la colección [Anaconda](https://www.anaconda.com/products/individual) que tiene casí todas las librerías para trabajar en Machine Learning y Data Science. La ventaja que tiene es que puedes probar pedazos de código sin tener la necesidad de saltar entre un IDE y la terminal. 

Por su lado, [Google Colab](https://colab.research.google.com/) tiene casi todas las librerías precargadas y no hay necesidad de instalarlas usando pip. 

Es cuestión de gusto personal cual de los dos usar. La ventaja de Jupypter Notebook es que corre en local host, por lo que no dependes de tu conexión de internet para trabajar. Por otra parte, Anaconda es muy pesado cuando se instalan sus paquetes. Por ello conviene en ese caso trabajar en un Colab, ya que además ofrece memoria RAM suficiente para trabajar. 

## 10. ¿Que debería de saber sobre ingenieria de software/web?

Idealmente, como científico de datos deberías tener una idea clara de como es el desarrollo de software. 

Una de los grandes problemas del gremio es que son muchos los data scientists que solo saben trabajar con Jupyter Notebooks. Es por ello que vale la pena construir ventajas competitivas. Entre las más importantes incluyen:

- Conocer un framework de backend. Si estás trabajando con Python, es recomendable empezar con Django. Aunque Flask o FastAPI con más fáciles de aprender y operar, la mayoría de proyectos profesionales son desarrollados en Django. 
- Cloud, como aquellos que mencionamos en la pregunta 3.
- DevOps es un buen complemento para un científico e ingeniero de datos, ya sea conociendo Bash Shell o administrando servidores Linux. Ademas esta podria ser la ventana a MLOps 

## 11. ¿Cuanto tiempo puedo tardar para adquirir las habilidades para data science?

**Entre 6 meses y 2 años** es un periodo sensato para adquirir las habiliades para data science, dependiendo de los conocimientos previos que se tengan y el tiempo invertido para aprender.

Aunque nada esta escrito sobre piedra, esta es **una estimación vaga** de tiempo para aprender cada una de los skills para data science:

(Nota: estamos hablando de obtener los conocimientos para usar estas herramientas para data science, más no en su completitud. Por ejemplo, en SQL nos referimos a hacer queries complejos, más no crear, administrar u optimizar una base de datos)

| Skill | 1 hora diaria | 1 - 2 horas diarias | 2 - 4 horas diarias |
| ------------- | ------------- | ------------- | ------------- |
| Python o R  | 16-20 semanas  | 10-16 semanas | 8-10 semanas |
| SQL  | 6-8 semanas  | 4-6 semanas | 2-4 semanas |
| Estadística  | 12-16 semanas  | 4-12 semanas | 4-5 semanas |
| Algebra lineal  | 12-16 semanas  | 6-12 semanas | 4-8 semanas |
| Cálculo  | 12-16 semanas  | 6-12 semanas | 4-8 semanas |
| Cloud  | 6-10 semanas  | 3-6 semanas | 2-3 semanas |
| Machine Learning  | 8-12 semanas  | 6-8 semanas | 4-6 semanas |
| Django  | 8-16 semanas  | 6-10 semanas | 4-8 semanas |

## 12. ¿Que hay sobre la parte legal y ética?

Cada país tiene sus propias leyes respecto al uso de datos. Por lo general, dentro de las empresas **los data scientists no son los responsables directos de hacer cumplir estos reglamentos**. Sin embargo, conviene saber sobre lo siguiente:

- Los datos solo son de valor para el científico de datos cuando vienen en volumen. Ergo, los datos individuales de un usuario no sirven para el trabajo cotidiano en nuestra area.
- Al hacer el análisis de los datos, hay que procurar que vengan anonimizados. Lo anterior es especialmente importante si son datos bancarios o médicos.
- Conocer un poco de seguridad informática (sobre todo respecto a las buensa prácticas del almacenamiento y tratamiento de datos) es recomendable.

Algunas regularidades que podemos encontrar son la HIPAA, PCI-compliance y GDPR-compliance.

## 13. ¿Cuales son las opotunidades laborales?

Dentro de la industria tech, [**data science es de las disciplinas de mayor demanda laboral**](https://www.xataka.com/otros/cientifico-datos-asi-profesion-demandada). Debido a que son muchos los puestos que quedan vacantes para esta posición y pocos los solicitantes, los sueldos en esta area son bastante más elevados en comparación a otros roles en la industria.  

## Recursos externos

- El mejor lugar para conseguir retos y ejercicios es [Kaggle](https://www.kaggle.com).
- Dentro de Kaggle podrás encontrar cursos gratuitos de [Python](https://www.kaggle.com/learn/python), [SQL](https://www.kaggle.com/learn/intro-to-sql) y [más](https://www.kaggle.com/learn/overview). 
- Cursos pagados que valen la pena incluyen [Platzi](https://platzi.com/datos/), [Data Camp](https://www.datacamp.com/) y [Data Quest](https://www.dataquest.io/)
- Un excelente recurso gratuito para aprender estadística es [Crash Course Statistics](https://www.youtube.com/watch?v=zouPoc49xbk&list=PL8dPuuaLjXtNM_Y-bUAhblSAdWRnmBUcr)
- Otro recurso de paga que recomiendo para aprender matemáticas es [Brilliant](https://brilliant.org/)
- [Stack Overflow](https://stackoverflow.com/) y [Towards Data Science](https://towardsdatascience.com/) son recursos válidos para encontrar respuestas a problemas comunes de data science.
- Algunas certificaciones que valen la pena tomar incluyen [AWS para Machine Learning](https://aws.amazon.com/es/machine-learning/) y [Google Cloud Platform para Ingenieria de Datos](https://cloud.google.com/certification/data-engineer).

Finalmente, **es fundamental siempre consultar la documentación de las tecnologías que usamos y mantener bien documentados nuestros propios proyectos para futura referencia**. 

(Nota: he utilizado todos estos recursos y no recibó ninguna comisión por promoverlos)

## Contacto 

Este apunte fue hecho en conjunto por Xavier Carrera y Gerson Pedromo. 

Si quieres contactar con Xavier, puedes visitar su [sitio web](https://www.xaviercarrera.com/), escribirle [en twitter](https://twitter.com/XaviGrowth) o mandarle un correo a hola@xaviercarrera.com. :nerd_face:

Para contacar con Gerson, puedes enviar un correo a ing.gersonp@gmail.com o encontrarlo en twtter como [@gersonrpq](https://twitter.com/gersonrpq). :robot:  
