# 🏢 Cloud Analytics e Inteligencia de Negocios Inmobiliarios (*KC Housing*)

Proyecto enfocado en la arquitectura de datos, automatización de procesos ETL (Extract, Transform, Load) y análisis exploratorio masivo de bienes raíces utilizando tecnologías en la nube y Python.

---

## 📋 Tabla de Contenidos
1. [Descripción del Proyecto](#descripción-del-proyecto)
2. [Stack Tecnológico](#stack-tecnológico)
3. [ETL Avanzado y Tablas Derivadas (Python)](#etl-avanzado-y-tablas-derivadas-python)
4. [Tableros Interactivos y KPIs (Looker Studio)](#tableros-interactivos-y-kpis-looker-studio)
5. [Insights y Conclusiones de Negocio](#insights-y-conclusiones-de-negocio)

---

## 🏗️ 1. Descripción del Proyecto
El objetivo principal fue procesar y analizar el comportamiento histórico de precios de vivienda del dataset `kc_house_data`. Mediante herramientas de análisis avanzado y computación en la nube, se transformaron datos en bruto para calcular métricas clave de valorización por zona, tamaño habitable en metros cuadrados y características constructivas.

---

## 🛠️ 2. Stack Tecnológico
* **Lenguaje:** Python (Pandas, NumPy).
* **Cloud & Datos:** AWS (S3, RDS), SQL.
* **Business Intelligence:** Looker Studio (Google Data Studio).
* **Control de Versiones:** Git, GitHub.

---

## 🔄 3. ETL Avanzado y Tablas Derivadas (Python)
Se diseñó un pipeline en Python para la limpieza y generación de dos tablas analíticas adicionales:
* **Tabla 1:** Promedio de precio, tamaño ($m^2$) y número de habitaciones por casa, agrupado por código postal (`zipcode`) y año.
* **Tabla 2:** Tendencia del precio promedio y mediana anual por zona geográfica.

---

## 📊 4. Visualización Interactiva (Looker Studio)
* Conexión directa de las tablas procesadas hacia Looker Studio.
* Incorporación de filtros dinámicos (por año, rango de precios y códigos postales) y tarjetas de KPI directivas.
* [🔗 Enlace al Reporte en Looker Studio](#) *(Insertar enlace público aquí)*

---

## 💡 5. Insights y Conclusiones de Negocio
* **Plusvalía Geográfica:** Identificación clara del Top de códigos postales con mayor resiliencia y valor por metro cuadrado.
* **Impacto Constructivo:** Demostración analítica de cómo la calidad de los acabados y las remodelaciones incrementan exponencialmente el valor comercial del inmueble.

---
*Desarrollado por **Marco Antonio Ruiz** - Analista de Datos*
