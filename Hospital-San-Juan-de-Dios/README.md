# Hospital San Juan de Dios – Análisis de Datos y Business Intelligence

## Descripción del proyecto

Proyecto de análisis y visualización de datos desarrollado con **SQL Server y Microsoft Power BI**, orientado al análisis de la actividad hospitalaria y la generación de información relevante para facilitar la toma de decisiones.

El trabajo abarca desde la preparación, estructuración y consulta de los datos en SQL Server hasta el desarrollo de un dashboard interactivo en Power BI, integrando diferentes técnicas de modelado, transformación y visualización de información.

## Tecnologías y herramientas utilizadas

### SQL Server

Utilización de Microsoft SQL Server para la creación y administración de la base de datos relacional.

Principales tareas realizadas:

- Importación y estructuración de archivos CSV en tablas independientes.
- Diseño y organización de tablas para representar las distintas entidades del modelo.
- Definición de claves primarias y relaciones mediante claves foráneas (Primary Keys y Foreign Keys).
- Validación de integridad referencial y consistencia de los datos.
- Desarrollo de consultas SQL para la extracción y análisis de información.
- Aplicación de funciones de agregación y funciones estadísticas.
- Cálculo de la mediana de los tiempos de atención por profesional mediante consultas SQL.

### Microsoft Power BI

Desarrollo de un dashboard interactivo para explorar y analizar diferentes indicadores de la actividad hospitalaria.

**Modelado y transformación de datos**
- Utilización de Power Query para la limpieza, transformación y preparación de los datos.
- Integración de las diferentes tablas provenientes de SQL Server.
- Construcción y organización del modelo de datos.
- Configuración de relaciones entre las distintas entidades.

**Análisis y cálculos**
- Desarrollo de medidas y expresiones DAX para la construcción de indicadores.
- Aplicación de funciones de agregación y cálculos personalizados.
- Creación de métricas para analizar la evolución y distribución de las atenciones.

**Interactividad y experiencia de usuario**
- Implementación de marcadores (Bookmarks) para generar diferentes vistas y estados de navegación dentro del reporte.
- Utilización de parámetros para brindar flexibilidad en la exploración y presentación de la información.
- Incorporación de elementos interactivos y filtros para facilitar el análisis desde distintas perspectivas.
- Diseño de una interfaz orientada a la navegación y comprensión de los indicadores.

## Indicadores y visualizaciones desarrolladas

El dashboard contempla diferentes perspectivas de análisis:

- **Participación por centro:** distribución de las atenciones según el centro hospitalario.
- **Evolución mensual:** seguimiento de la cantidad de atenciones a lo largo del tiempo.
- **Análisis por día de la semana:** comparación del promedio de atenciones según el día.
- **Top 10 especialidades:** identificación de las especialidades con mayor volumen de atenciones.
- **Distribución de tiempos de atención:** análisis mediante gráficos de caja y bigotes (Boxplot), segmentado por centro.

## Objetivo del desarrollo

El objetivo principal fue transformar datos operativos en información clara, estructurada y visualmente accesible, permitiendo identificar patrones, comparar indicadores y analizar el comportamiento de la actividad hospitalaria.

El proyecto integra conocimientos de bases de datos relacionales, SQL, modelado de datos, transformación de información, DAX y desarrollo de soluciones de Business Intelligence.
