# Final-Project-KC

## Keepcoding project: [Airbnb](https://public.opendatasoft.com/explore/dataset/air-bnb-listings/export/?disjunctive.neighbourhood&disjunctive.column_10&disjunctive.city&q=Madrid&sort=minimum_nights&location=7,40.5931,-4.422&basemap=jawg.light)

El objetivo general de este proyecto final es aplicar todos los conocimientos adquiridos durante el curso a través de un análisis completo de un conjunto de datos extraídos de Airbnb. El proyecto abarca desde la definición del dataset hasta la presentación de los resultados en un informe detallado, pasando por la exploración y validación de los datos, el análisis exploratorio, la visualización de métricas relevantes, el preprocesamiento y modelado de los datos. La meta es demostrar la capacidad para llevar a cabo todas estas etapas de manera efectiva, identificando patrones, tendencias y características significativas en los datos que puedan ser útiles para la toma de decisiones en un entorno empresarial.

### Definición del Conjunto de Datos

El conjunto de datos utilizado en este proyecto proviene de Airbnb y contiene información sobre listados de alojamientos en la ciudad de Madrid, España. A continuación, se proporciona un resumen de las principales características del conjunto de datos:

- **Dimensiones**: El conjunto de datos consta de 21,255 filas y 10 columnas.
- **Columnas Principales**:
  1. **Room ID**: Identificador único de la habitación.
  2. **Host ID**: Identificador único del anfitrión.
  3. **Neighbourhood**: Barrio donde se encuentra el alojamiento.
  4. **Room type**: Tipo de habitación (por ejemplo, apartamento completo, habitación privada).
  5. **Room Price**: Precio del alojamiento por noche.
  6. **Minimum nights**: Número mínimo de noches para reservar.
  7. **Rooms rent by the host**: Número de habitaciones que el anfitrión tiene en alquiler.
  8. **Availability**: Número de días disponibles para reservar en un año.
  9. **Coordinates**: Coordenadas geográficas del alojamiento.
  10. **Location**: Ubicación del alojamiento (país, ciudad, barrio).

Estos datos osn importantes para nuestro análisis exploratorio y modelado predictivo, ya que contiene información detallada sobre los alojamientos disponibles en Madrid, lo que nos permitirá realizar predicciones y extraer información relevante para nuestro proyecto.

### Arquitectura y validación de los datos
   a. Muestreo y exploración inicial de los datos.
   b. Implementación de un Datawarehouse para almacenar y procesar la información.
   c. Ingesta de datos utilizando un proceso ETL para cargar los datos en el Datawarehouse y validación de su correcta carga.

### Análisis Exploratorio
- Análisis estadísticos detallados utilizando R y Python, incluyendo:
   a. Revisión de la calidad de los datos.
   b. Detección de outliers y posterior imputación de valores nulos.
   c. Visualización de distribuciones mediante boxplots, histogramas, etc.
   d. Normalización de los valores de las tablas según sea necesario.

### Visualización de las métricas
- Utilización de los datos de Airbnb para obtener KPIs relevantes y creación de un dashboard interactivo que responda a una pregunta relevante sobre los datos.

### Pre-procesamiento y Modelado
- Para finalizar el proyecto se llevan a cabo un pequeño resumen de todo:
1. **Carga de datos**: Se utilizaron datos de listados de Airbnb en Madrid.
2. **Preprocesamiento**: Eliminación de columnas irrelevantes e imputación de valores faltantes.
3. **Transformación de variables**: Conversión de variables categóricas a numéricas para el modelado.
4. **Modelado**: Se ajustó un modelo de regresión lineal para predecir los precios de las habitaciones.
5. **Validación del modelo**: Evaluación del rendimiento del modelo y cálculo de métricas de error.

### Informe
- Presentación de un informe detallado simulando la presentación de resultados en un entorno empresarial, incluyendo:
   - Suposiciones iniciales y su validación.
   - Evaluación de las métricas seleccionadas y la efectividad del modelo.
   - Reflexiones sobre lo aprendido y posibles mejoras en el enfoque del proyecto.
   - Conclusiones y lecciones aprendidas.
