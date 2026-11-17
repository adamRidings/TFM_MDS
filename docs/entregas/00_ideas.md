# **ReturnSmart: Optimización inteligente de devoluciones en e-commerce**

**1\. Título y descripción**

Desarrollo de una herramienta basada en Data Science e Inteligencia Artificial que analice productos devueltos por clientes y recomiende la alternativa más rentable para cada uno: reventa, reparación, reacondicionamiento, liquidación o reciclaje.

**2\. Problema y usuario**

Las devoluciones generan importantes costes para las empresas de comercio electrónico debido al transporte, almacenamiento, revisión y pérdida de valor de los productos. La herramienta estaría dirigida a responsables de logística y operaciones, ayudándoles a decidir cómo gestionar cada devolución de forma eficiente y rentable.

**3\. Uso y valor**

El usuario introduciría información del producto devuelto, como su categoría, estado, motivo de devolución, precio original y posibles costes asociados. El sistema analizaría las distintas alternativas y recomendaría la más conveniente económicamente. Su objetivo sería reducir costes, recuperar el máximo valor posible de los productos y disminuir el impacto medioambiental.

**4\. Datos**

Se utilizarán principalmente datasets públicos de comercio electrónico, como el de Olist (Kaggle), que contiene información real anonimizada sobre aproximadamente 100.000 pedidos, productos, precios, pagos y gastos de envío. También se investigarán otras fuentes específicas sobre devoluciones y productos. Para variables difíciles de obtener públicamente, como costes de reparación o reacondicionamiento, se estudiará la posibilidad de utilizar estimaciones o escenarios simulados, diferenciándolos de los datos reales.

**5\. Primera versión o MVP**

Se desarrollaría una aplicación funcional que permita introducir las características de un producto devuelto y obtener una recomendación sobre su gestión. Incluiría el análisis de las distintas alternativas, la estimación de costes e ingresos potenciales y la visualización de resultados mediante un dashboard. Inicialmente quedarían fuera las integraciones con tiendas online y sistemas empresariales.

**6\. Viabilidad y dudas**

El proyecto es técnicamente viable mediante técnicas de Machine Learning, análisis de datos y optimización. La principal dificultad será encontrar datos públicos suficientemente completos sobre devoluciones y su gestión posterior. También será necesario determinar qué variables pueden obtenerse de fuentes reales y cuáles deberán estimarse o simularse, así como validar que las recomendaciones permiten mejorar las decisiones económicas de las empresas.

&nbsp;

# **Criminología Espacial: Predicción y prevención de puntos calientes de delincuencia (Predictive Policing & Geo-Spatial Analytics)**

**1\. Título y descripción**

Este proyecto desarrolla un sistema dinámico de analítica predictiva y geoespacial diseñado para modelar la probabilidad espacio-temporal de delitos urbanos.

**2\. Problema y usuario**

La asignación tradicional de recursos policiales suele ser reactiva o basarse en intuiciones y promedios históricos estáticos. Esto genera una distribución ineficiente de las patrullas, tiempos de respuesta elevados y la incapacidad de anticipar desplazamientos o patrones temporales de delitos. Esta herramienta estaría dirigida principalmente a analistas de inteligencia policial, mandos tácticos y departamentos de seguridad ciudadana, además de también ser útil para planificadores urbanos e investigadores en criminología y políticas públicas.

**3\. Uso y valor**

El usuario selecciona la ciudad/distrito y la franja horaria a predecir. El sistema genera un mapa de calor dinámico interactivo con las zonas de mayor riesgo predicho para después sugerir una distribución óptima de las unidades de patrulla asignadas para maximizar la cobertura en las zonas críticas. Su valor se vería reflejado en la reducción de delitos, eficiencia operativa y mitigación de sesgos.

**4\. Datos**

Se usaron datasets públicos de incidencias delictivas con marca de tiempo, tipo de delito y coordenadas GPS de alguna ciudad, de ubicaciones de puntos calientes de delincuencias, como comercios, bancos, bares, discotecas, etc. Además de datos demográficos, socioeconómicos, meteorológicos y de calendario.

**5\. Primera versión o MVP**

Se desarrollará una aplicación en la que al poner el nombre de un distrito o zona de la ciudad elegida, salga reflejado un mapa de calor en las zonas donde se predice que el nivel de delincuencia sea más alto en el tiempo establecido. Además, da recomendaciones a la hora de actuar en el caso que se refleje.

**6\. Viabilidad y dudas**

Los datasets públicos de delitos y POIs son accesibles, y la infraestructura requerida se puede ejecutar localmente o mediante GCP gratuitos. Los principales retos serían el sesgo de reporte/confirmación, la resolución espacio-temporal óptima y la evaluación de modelos en criminología.

&nbsp;

# **RadarBOE: alertas inteligentes de normativa y ayudas para pyme&nbsp;**

**1\. Título y descripción**  
Herramienta que lee diariamente el Boletín Oficial del Estado, clasifica cada disposición por tema y sector, y avisa a cada pyme solo de las normas y ayudas que le afectan, con un resumen en lenguaje sencillo.

**2\. Problema y usuario**  
El BOE publica cada día un gran volumen de disposiciones en lenguaje jurídico. Las pymes y autónomos no tienen departamento legal, se enteran tarde de nuevas obligaciones y pierden ayudas que podrían solicitar, como el programa Kit Consulting. RadarBOE va más allá de las alertas genéricas por categorías: adapta la información al perfil real de cada empresa. Está dirigida a pymes, autónomos y gestorías que gestionan varios clientes.

**3\. Uso y valor**  
El usuario indica el perfil de su empresa (sector, tamaño y ubicación). Cada día recibe las disposiciones relevantes ordenadas por importancia, con un resumen claro y el enlace oficial. Ahorra tiempo, reduce el riesgo de incumplimientos y evita perder oportunidades de financiación.

**4\. Datos**  
Datos reales y oficiales de la API de datos abiertos del BOE: sumario diario, legislación consolidada y BORME, en JSON y XML, actualizados a diario. El equipo creará además un conjunto de disposiciones etiquetadas para entrenar y evaluar el modelo.

**5\. Primera versión o MVP**  
Aplicación web desplegada online que descarga y procesa el BOE automáticamente cada día, clasifica las disposiciones por sector y las filtra según el perfil de la empresa, con resumen y enlace oficial. Las integraciones con sistemas de gestorías, los avisos por email y los boletines autonómicos quedan para fases posteriores.

**6\. Viabilidad y retos**  
Proyecto viable: datos abiertos y estructurados, y técnicas de clasificación de texto consolidadas (modelos clásicos, embeddings y modelos de lenguaje). Los retos principales son medir la mejora frente a la búsqueda por palabras clave, que abordaremos con una comparación directa, y garantizar la fiabilidad de los resúmenes, que irán siempre enlazados a la fuente oficial.

&nbsp;

# **Licitómetro: medición de competencia y descuento en licitaciones públicas**

**1\. Título y descripción**  
Herramienta que, para cada licitación publicada, estima cuánta competencia habrá y con qué descuento se suele adjudicar, a partir del histórico de la Plataforma de Contratación del Sector Público desde 2012\. Con ello ayuda a una pyme tecnológica a decidir a qué licitaciones presentarse y con qué margen de precio. Incluye un análisis del mercado por órgano de contratación, tipo de contrato y sector.

**2\. Problema y usuario**  
Preparar una oferta cuesta muchas horas, y la empresa no sabe de antemano si competirá con 2 o con 20 rivales ni cuánto tendrá que rebajar su precio para ganar. Hoy decide por intuición, con alertas por palabras clave o con servicios de pago que analizan licitaciones; ya hay productos comerciales construidos sobre estos mismos datos, lo que apunta a que existe demanda. Va dirigida a responsables comerciales o de licitaciones de pymes de software y datos y a consultoras que preparan ofertas.&nbsp;

**3\. Uso y valor**  
El usuario indica su perfil (tipo de contrato, sector, territorio y rango de importe) y ve las licitaciones abiertas con tres datos: relevancia, competencia esperada y descuento habitual, junto con la evolución histórica del órgano que licita. Con eso decide a cuáles presentarse y qué margen tiene. El valor es concentrar el esfuerzo en las oportunidades con mejor relación entre trabajo y probabilidad y ofertar con información de precios. Lo cuantificaremos en horas ahorradas y ofertas descartadas, con supuestos explícitos.

**4\. Datos**  
La fuente son las licitaciones publicadas en los perfiles del contratante de la Plataforma de Contratación del Sector Público, excluyendo contratos menores, que publica el Ministerio de Hacienda: [https\://www\.hacienda.gob.es/es-es/gobiernoabierto/datos%20abiertos/paginas/licitacionescontratante.aspx](https://www.hacienda.gob.es/es-es/gobiernoabierto/datos%20abiertos/paginas/licitacionescontratante.aspx). Según su documentación, se actualiza a diario, cubre desde el 1 de enero de 2012 y se distribuye en ficheros ATOM comprimidos por año y por mes. Una misma licitación aparece varias veces, una por cada modificación, y la cobertura no es homogénea entre organismos. En cuanto al uso, el acceso es gratuito y sin restricciones para fines comerciales y no comerciales, citando la fuente y la fecha de última actualización y sin alterar el contenido ni desnaturalizar el sentido, según el portal de contratación de la Comunidad de Madrid, que se interconecta con la plataforma estatal. Falta confirmarlo en la página estatal.

**5\. Primera versión o MVP**  
Para un territorio \[por ejemplo, la Comunitat Valenciana\] y un tipo de contrato (servicios y suministros TIC): los datos limpios y consultables, un panel con dos vistas (mercado, con competencia y descuentos por órgano y sector, y oportunidades, con las licitaciones abiertas y sus estimaciones) y un modelo que estima competencia y descuento, comparado con una referencia sencilla, la media histórica del órgano y del sector. Quedan fuera las alertas por correo, la predicción de si la empresa ganará, el análisis de los pliegos completos, los contratos menores y otras fuentes.

**6\. Viabilidad y dudas**  
La principal dificultad es la ingeniería de datos (XML anidado, versiones repetidas, cobertura desigual) y comprobar que hay datos suficientes de ofertas y adjudicación. En la actividad 1 mediremos qué porcentaje de licitaciones adjudicadas tiene esos campos. Si faltan, estimaríamos solo el descuento (presupuesto frente a importe adjudicado) o reorientaríamos el producto a ordenar oportunidades por relevancia con búsqueda semántica sobre título y objeto. Dos cautelas: el modelo describe patrones históricos y no indica si una empresa concreta ganará, y las licitaciones anuladas o desiertas pueden sesgar los resultados.

&nbsp;