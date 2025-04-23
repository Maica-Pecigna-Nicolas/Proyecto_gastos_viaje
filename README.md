# Proyecto_gastos_viaje

Automatización Inteligente de la Imputación de Gastos de Viaje: Un Proyecto Colaborativo de IA, Python y Power BI
La finalidad de este proyecto es el ahorro de tiempo y la sencillez aplicada en la gestión de gastos de viaje, proceso que suele ser bastante tedioso y repetitivo. El trabajo fue llevado a cabo con un equipo excepcional, Natalia, Miriam, José Manuel, Santiago  del que yo tuve la suerte inmensa de formar parte. Colaboramos en el desarrollo de una solución para automatizar la molesta y monótona  tarea de imputación de gastos de viaje, combinando Inteligencia Artificial,  Python y  Power BI que muestra gráficos ilustrativos.

Objetivo: Automatizar la extracción de información clave de facturas de gastos de viaje, eliminando la entrada manual y reduciendo errores, para una gestión más ágil y precisa.
¿Cómo se hizo? Comenzamos  con la captura de imágenes de tickets de gasto. Utilizando Python y la API de OpenAI (específicamente gpt-4o-mini), se procesaron estas imágenes para extraer de forma inteligente la fecha, el coste total (en €), el tipo de gasto, el nombre de la empresa, la ubicación (ciudad, provincia, país), el número de factura y el método de pago.

Conjunto de Datos: El proyecto hizo uso de un conjunto diverso de imágenes de tickets de diferentes proveedores y formatos, lo que permitió validar la capacidad de extracción de la IA en escenarios reales.
Conexión con la API de OpenAI: La integración con la API de OpenAI a través de Python nos ayudó a la comprensión y extracción de la información no estructurada presente en los tickets de compra, convirtiéndola en datos estructurados y listos para su análisis.

Utilizamos  Ingenieria de Prompt, que explicaré a continuación. Los tickets de gastos de viaje no suelen estar estructurados, presentando una gran variedad de formatos, diseños y niveles de detalle. Un prompt bien elaborado actúa como la guía precisa que presentado a la  IA posibilita pedirle que nos muestre la información específica que deseamos  extraer, también cómo interpretarla y en qué formato estructurado deseamos que nos la devuelva.

Visualización y Análisis con Power BI: Los datos estructurados extraídos se almacenan en una base de datos SQLite y se conectan a Power BI a través de un ODBC u  Open Database Connectivity, Esta interfaz nos posibilitó que Power BI y Python pudieran interactuar con bases de datos (DBMS).  Desarrollamos dashboards interactivos que para poder visualizar los gastos por tipo, proveedor, ubicación y periodo, facilitando el seguimiento del presupuesto de viajes, la identificación  de  gastos y la generación de informes personalizados.

Mejoras futuras: Clasificación Inteligente de Gastos: Utilizando modelos de Machine Learning para clasificar automáticamente los tipos de gasto con mayor precisión, incluso en descripciones no estandarizadas.
Detección de Anomalías y Fraude: Desarrollar algoritmos para identificar patrones de gasto inusuales o potencialmente fraudulentos, proporcionando alertas tempranas para su revisión.
Procesamiento Multilingüe: Ampliar la capacidad de la IA para procesar facturas en diferentes idiomas, facilitando la gestión de gastos para equipos globales.
Conexión con Sistemas ERP y Contabilidad: Integrar la solución con sistemas de planificación de recursos empresariales (ERP) y software de contabilidad.
Y por último la inclusión de  otros formatos de documentos  como recibos en PDF o correos electrónicos de confirmación.

Conclusión: Con este proyecto hemos comprobado el gran potencial de IA, Power BI y Python pero sobre todo el gran trabajo con Prompts redactados de manera inteligente, elaborados y gran esfuerzo  que durante días hemos realizado este gran equipo compuesto por Natalia, Miriam, José Manuel y Santiago y yo.

#IA #InteligenciaArtificial #Python #PowerBI #Automatización #GastosDeViaje #Eficiencia #DataDriven #Innovación #Equipo
