# Proyecto-BT1013.301
## Propuesta de proyecto: México vs el mundo

Este proyecto analizará secuencias del SARS-CoV-2 recolectadas en México durante el año 2021 y las comparará con secuencias obtenidas en otras regiones del mundo durante el mismo periodo. Para la comparación se seleccionarán secuencias de México, Estados Unidos, Reino Unido, China y Brasil, con el objetivo de observar si las variantes circulantes en México compartieron mutaciones similares con las variantes dominantes a nivel global.

El análisis se enfocará en el gen **S**, que codifica la proteína **Spike**, debido a que esta proteína es fundamental para la entrada del virus a la célula humana y porque muchas de las mutaciones características de las variantes del SARS-CoV-2 se encuentran en esta región.

Se utilizarán **5 secuencias por país**, descargadas desde la base de datos **NCBI** en formato FASTA. En total, se analizarán **25 secuencias**:

| Región | País | Número de secuencias | Año |
|--------|------|---------------------:|----:|
| Norteamérica | México | 5 | 2021 |
| Norteamérica | Estados Unidos | 5 | 2021 |
| Europa | Reino Unido | 5 | 2021 |
| Asia | China | 5 | 2021 |
| Sudamérica | Brasil | 5 | 2021 |

La hipótesis del proyecto es que las secuencias del SARS-CoV-2 recolectadas en México durante 2021 compartirán mutaciones características en la proteína Spike con secuencias de Estados Unidos, Reino Unido, China y Brasil del mismo periodo. Esto podría indicar que las variantes presentes en México estuvieron relacionadas con linajes que también circularon internacionalmente, aunque podrían observarse diferencias dependiendo de la región geográfica y la fecha de recolección.

La metodología consistirá en descargar las secuencias desde NCBI y organizarlas por país. Posteriormente, cada secuencia será comparada contra la cepa de referencia de Wuhan (NC_045512.2) para identificar mutaciones de sustitución no sinónimas en el gen S. A partir de estas comparaciones, se identificarán las mutaciones compartidas entre países y las diferencias regionales. Los resultados se presentarán mediante tablas comparativas de mutaciones y gráficas de frecuencia por región. De ser posible dentro del alcance del proyecto, se explorará la construcción de un árbol filogenético sencillo para visualizar la relación entre las secuencias analizadas.

El objetivo del proyecto no es reconstruir toda la evolución del virus, sino comparar de manera puntual si las secuencias mexicanas del SARS-CoV-2 presentan patrones genéticos similares a los observados en otros países durante 2021. Este enfoque permite relacionar el análisis bioinformático con un fenómeno local y global: la circulación de variantes durante la pandemia.
