# Proyecto de Data Analyst: Análisis de Siniestros Viales

## Introducción
El objetivo de este proyecto es analizar los siniestros viales en la Ciudad Autónoma de Buenos Aires (CABA) con el fin de monitorear y reducir los accidentes mortales, especialmente aquellos que involucran motociclistas. Los KPIs principales son:

1. **Tasa de Homicidios en Siniestros Viales**
2. **Reducción de Accidentes Mortales de Motociclistas en un 7%**
3. **(Inventar un KPI adicional)**

## Objetivos
- Calcular y monitorear la tasa de homicidios en siniestros viales.
- Evaluar la reducción de accidentes mortales de motociclistas.
- Identificar patrones y tendencias en los siniestros viales para implementar medidas preventivas.

## Tecnologías Utilizadas
- **Python**: Lenguaje principal para la manipulación y análisis de datos.
  - **Pandas**: Para la manipulación y análisis de datos.
  - **NumPy**: Para operaciones matemáticas y estadísticas.
  - **Matplotlib**: Para la visualización de datos.
- **Jupyter Notebook**: Para la documentación y ejecución del análisis de datos.
- **Git**: Para el control de versiones.
- **Power BI**: Para la creación de dashboards interactivos y la visualización de KPIs.

## Fuente de Datos
- **Datos de siniestros viales**: Proporcionados por organismos oficiales de tránsito y seguridad vial de CABA.
- **Datos demográficos**: Proporcionados por el Instituto Nacional de Estadística y Censos (INDEC).

## KPIs

1. **Tasa de Homicidios en Siniestros Viales**
   - Fórmula: \((\text{Número de homicidios en siniestros viales} / \text{Población total}) \times 100,000\)

2. **Reducción de Accidentes Mortales de Motociclistas**
   - Fórmula: \((\text{Número de accidentes mortales con víctimas en moto en el año anterior} - \text{Número de accidentes mortales con víctimas en moto en el año actual}) / \text{Número de accidentes mortales con víctimas en moto en el año anterior} \times 100\)

3. **Inventar un KPI adicional** (Por ejemplo: Reducción del número total de siniestros viales en un 5% respecto al año anterior).

## Metodología de Análisis

### 1. Carga y Exploración de Datos
- **Trabajo Realizado**: 
  - Cargar los datos de siniestros viales y demográficos.
  - Realizar un análisis exploratorio de datos (EDA) para entender la estructura y contenido de los datos.

### 2. Preprocesamiento de Datos
- **Identificación y manejo de valores nulos**: 
  - **Trabajo Realizado**: Determinar el porcentaje de valores nulos en cada columna y decidir una estrategia para su imputación.
- **Detección y tratamiento de outliers**: 
  - **Trabajo Realizado**: Identificar valores atípicos y decidir si se eliminan o se corrigen.
- **Manejo de datos duplicados**: 
  - **Trabajo Realizado**: Identificar registros duplicados y eliminarlos para asegurar la integridad de los datos.
- **Normalización y estandarización de datos**: 
  - **Trabajo Realizado**: Asegurar que los datos están en un formato uniforme y adecuado para el análisis.

### 3. Análisis Descriptivo
- **Trabajo Realizado**: 
  - Calcular estadísticas descriptivas básicas.
  - Visualizar la distribución de los datos y las tendencias temporales.

### 4. Cálculo de KPIs
- **Trabajo Realizado**: 
  - Implementar las fórmulas para los KPIs definidos.
  - Visualizar los KPIs a lo largo del tiempo para identificar tendencias y cambios.

### 5. Visualización y Reporte
- **Trabajo Realizado**: 
  - Crear dashboards interactivos en Power BI para monitorear los KPIs.
  - Generar reportes detallados con los hallazgos y recomendaciones basadas en el análisis.

## Implementación en Power BI

### Proceso
1. **Importación de Datos**
   - **Trabajo Realizado**: Importar los datasets de siniestros viales y demográficos a Power BI.
2. **Transformación de Datos**
   - **Trabajo Realizado**: Utilizar el Editor de Consultas para limpiar y transformar los datos:
     - Eliminar valores nulos y registros duplicados.
     - Crear nuevas columnas necesarias para el análisis.
3. **Creación de Dashboards**
   - **Trabajo Realizado**: Diseñar dashboards interactivos que incluyan:
     - Visualización de la Tasa de Homicidios en Siniestros Viales.
     - Visualización de la Reducción de Accidentes Mortales de Motociclistas.
     - (KPI adicional).
4. **Configuración de KPIs**
   - **Trabajo Realizado**: Configurar tarjetas de KPIs para mostrar los valores calculados.
5. **Interactividad**
   - **Trabajo Realizado**: Añadir filtros y segmentaciones para permitir una exploración interactiva de los datos.

### Ejemplo de Visualizaciones en Power BI
- **Mapa de calor**: Mostrar la concentración de siniestros viales en diferentes áreas de CABA.
- **Gráficos de barras**: Comparar el número de siniestros por año y tipo de accidente.
- **Tarjetas de KPIs**: Visualizar los valores actuales de los KPIs principales.
- **Gráficos de línea**: Mostrar la tendencia de la tasa de homicidios en siniestros viales a lo largo del tiempo.

## Conclusiones y Recomendaciones
- **Trabajo Realizado**: Presentar los hallazgos clave del análisis y sugerir medidas para reducir los siniestros viales y mejorar la seguridad de los motociclistas.
- Proponer futuras líneas de investigación y análisis.

