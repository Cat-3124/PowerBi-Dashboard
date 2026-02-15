# 📊 Caso de Estudio: Análisis de Consumo Energético Enosa (Distriluz)

Este proyecto analiza el comportamiento de la demanda eléctrica y la recaudación de **Enosa**, utilizando datos oficiales para el periodo **Enero - Junio 2025**.

---

### 1. Objetivo del Proyecto
El objetivo principal es centralizar la información operativa para:
* Monitorear la **recaudación total mensual**.
* Analizar la **variación de consumo** (crecimiento o decrecimiento porcentual).
* Identificar los distritos con mayor **demanda eléctrica**.
* Aplicar el **Análisis de Pareto** para detectar las provincias que representan el mayor impacto en el negocio.

---

### 2. Metodología y Datos (ETL)
* **Fuente:** [Plataforma Nacional de Datos Abiertos del Perú](https://www.datosabiertos.gob.pe/dataset/consumo-energético-de-clientes-enosa-distriluz-dlz).
* **Dataset:** Consumo energético de clientes ENOSA [Distriluz-DLZ].
* **Proceso:** Limpieza de datos en Power Query, normalización de nombres de distritos y creación de un modelo de datos optimizado para grandes volúmenes de información.

---

### 3. Hallazgos Clave (Resumen Enero - Junio 2025)
Tras el procesamiento de la data, se obtuvieron los siguientes resultados:

* **Crecimiento de la Demanda:** Se registró una variación positiva del **8.39%** en el consumo respecto al inicio del periodo.
* **Métricas Globales:** * **Demanda Eléctrica:** 7,774.00 millones de KWH.
    * **Recaudación Total:** S/ 58.09 millones de soles.
* **Análisis Geográfico:**
    * La provincia de **Trujillo** es el foco principal, representando el **42.13%** del consumo total.
    * El distrito de **Trujillo Centro** destaca individualmente, acumulando el **20.23%** del consumo de la provincia.
* **Ley de Pareto:** Se identificó que las provincias de **Trujillo, Santa, Cajamarca, Huaraz, Ascope y Pacasmayo** componen la mayor parte de la demanda de KWH.

---

### 4. Herramientas Utilizadas
* **Power BI Desktop:** Para el modelado y visualización.
* **DAX:** Medidas para cálculo de variaciones porcentuales y acumulados de recaudación.
* **Análisis Predictivo:** Uso de tendencias mensuales para proyecciones de demanda futura.

---

### 5. Conclusiones y Acciones
El dashboard funciona como una herramienta de toma de decisiones para:
1. Anticipar la carga en provincias críticas según el modelo de Pareto.
2. Evaluar acciones comerciales en distritos de baja recaudación pero alto consumo.
3. Pronosticar la demanda de los próximos meses basándose en el comportamiento del primer semestre de 2025.

---
🔗 **[Descargar archivo .PBIX de este proyecto](https://drive.google.com/file/d/1UHu9LNRpiwS9V94Eyc2eEmllf22EjU5l/view?usp=sharing)**
