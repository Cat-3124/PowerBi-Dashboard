# 📊 Explicación del Dashboard: Consumo Energético Enosa (Distriluz)

Este proyecto tiene como objetivo analizar y visualizar los datos de consumo de energía eléctrica de los clientes de **Enosa**, bajo el grupo **Distriluz**. A continuación, se detallan los puntos clave del desarrollo:

---

### 1. Objetivo del Análisis
Identificar patrones de consumo, tendencias temporales y distribución geográfica de la demanda para optimizar la toma de decisiones operativa y comercial.

---

### 2. Proceso de Datos (ETL)

* **Extracción:** Los datos fueron obtenidos de [Menciona aquí tu fuente, ej: Archivos Excel / CSV].
* **Transformación (Power Query):**
    * Limpieza de valores nulos y duplicados.
    * Estandarización de formatos de fecha y categorías de clientes.
    * Creación de columnas personalizadas para segmentación de consumo.
* **Carga:** Los datos se estructuraron en un **modelo de estrella** para mejorar el rendimiento de las consultas y la eficiencia del reporte.

---

### 3. Modelado y DAX
Se implementaron medidas calculadas utilizando lenguaje **DAX** para obtener métricas clave como:

* **Consumo Total (kWh):** Sumatoria del consumo en el periodo seleccionado.
* **Variación Interanual:** Comparativa de consumo versus el año anterior (Year-over-Year).
* **Promedio de Consumo por Cliente:** Segmentación por categoría tarifaria para identificar usuarios de alto impacto.

---

### 4. Visualizaciones Clave
* **Mapa de Calor:** Distribución del consumo por zonas geográficas para identificar focos de demanda.
* **Gráfico de Líneas:** Evolución mensual del consumo para detectar estacionalidad y tendencias a largo plazo.
* **Treemap:** Desglose del consumo por tipo de cliente (Residencial, Comercial, Industrial).

---

### 5. Conclusiones
El dashboard permite visualizar de manera rápida qué sectores presentan picos de demanda inusuales, facilitando la planificación de mantenimiento preventivo y la creación de estrategias de ahorro energético más efectivas.

---
_Link de descarga https://drive.google.com/file/d/1UHu9LNRpiwS9V94Eyc2eEmllf22EjU5l/view?usp=sharing ._
