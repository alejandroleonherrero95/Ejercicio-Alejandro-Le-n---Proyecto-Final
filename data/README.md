# Dashboard de Empleo en Europa – Proyecto Final

##  Descripción

Este proyecto consiste en la creación de un **dashboard interactivo en Excel** a partir de datos simulados basados en el portal de estadísticas de empleo de **Eurostat**.  
El objetivo era **analizar y visualizar el comportamiento del empleo en Europa** mediante diferentes variables, aplicando un flujo completo de trabajo que abarca desde la limpieza de datos hasta la representación visual final.

---

##  Objetivo del Proyecto

- Diseñar un **dashboard dinámico e intuitivo** que permita explorar el empleo por país, género, tipo de contrato, categoría profesional y empresa.  
- Aplicar técnicas de **limpieza, análisis y preparación de datos en Python**.  
- Consolidar la información en un archivo de Excel mediante **tablas dinámicas y segmentaciones interactivas**.

---

##  Estructura del Proyecto

| Archivo | Descripción |
|----------|-------------|
| `employment_eurostat.tsv.gz` | Dataset original con datos de empleo (Eurostat) |
| `job_postings_europe.csv` | Dataset con ofertas de empleo en Europa |
| `01_EDA_Limpieza.ipynb` | Limpieza inicial, eliminación de nulos y duplicados |
| `02_EDA_Basico.ipynb` | Análisis exploratorio básico de los datos limpios |
| `03_EDA_Avanzado.ipynb` | Análisis avanzado y visualización previa |
| `04_Preparacion_Excel.ipynb` | Fusión y exportación final de los datos para Excel |
| `employment_clean.csv` | Dataset limpio de empleo |
| `job_postings_clean.csv` | Dataset limpio de ofertas |
| `fusionado_reducido.csv` | Dataset combinado con variables clave |
| `analisis_para_excel_completo.csv` | Archivo final utilizado en Excel |
| `analisis_para_excel_final.xlsx` | Dashboard interactivo final con gráficos dinámicos |

---

##  Metodología

### 1️⃣ Limpieza de Datos (Python)
- Carga de los datasets originales de empleo y ofertas.  
- Eliminación de valores nulos y duplicados.  
- Normalización de columnas, formatos y tipos de datos.  
- Filtrado de variables relevantes (país, tipo de contrato, género, edad, categoría profesional).  
- Exportación de los datos limpios a formato `.csv`.

### 2️⃣ Análisis Exploratorio de Datos (EDA)
- Cálculo de estadísticas descriptivas.  
- Identificación de tendencias en empleo por país y sector.  
- Detección de valores atípicos.  
- Creación de visualizaciones previas con Python para validar consistencia.

### 3️⃣ Preparación de Datos para Excel
- Integración de los datasets limpios.  
- Creación del dataset final `analisis_para_excel_completo.csv`.  
- Validación del formato y estructura de columnas.  
- Exportación a Excel para la fase de visualización.

### 4️⃣ Creación del Dashboard en Excel
- Importación de los datos finales en una hoja llamada **Datos_Limpios**.  
- Creación de **8 tablas dinámicas** para distintos enfoques de análisis.  
- Inserción de **segmentadores** por país (`geo`), tipo de empleo (`job_type`), género (`sex`) y año (`year`).  
- Generación de **gráficos dinámicos** y conexión con los filtros.  
- Diseño final con formato visual coherente (paleta verde, títulos destacados y distribución equilibrada).

---

## 📊 Gráficos Incluidos

1. Empleo total por país (2018)  
2. Suma total de empleo por tipo de trabajo y país  
3. Distribución del empleo por género y país  
4. Promedio de empleo por tipo de contrato y género  
5. Distribución del empleo por país y categoría profesional  
6. Top 10 empresas por volumen de empleo  
7. Suma total de empleo por categoría profesional  
8. Promedio de empleo por edad y sexo  

---

##  Diseño del Dashboard

- Paleta de colores en tonos verdes (coherente y legible).  
- Títulos con fondo verde oscuro y texto blanco.  
- Gráficos alineados y organizados por bloques temáticos.  
- Segmentadores dispuestos a la izquierda para una navegación intuitiva.  
- Cifras con separador de miles para facilitar la lectura.  

---

##  Resultados Finales

El dashboard permite:

- Visualizar comparativamente el empleo entre países europeos.  
- Analizar la distribución por tipo de contrato, género y edad.  
- Identificar las categorías profesionales más representativas.  
- Observar el ranking de las principales empresas en volumen de empleo.  
- Modificar los filtros de forma interactiva para obtener perspectivas distintas.

---

##  Fuente de Datos

Los datos utilizados son **simulados con base en estadísticas de Eurostat**, adaptados con fines académicos y de práctica analítica.  
- [Eurostat – Employment Statistics](https://ec.europa.eu/eurostat)

---

##  Conclusión

Este proyecto integra todo el proceso de análisis de datos:
- Desde la **limpieza y preparación de datos con Python**,  
- hasta la **creación de un dashboard profesional en Excel** con tablas y gráficos dinámicos.  

El resultado es una herramienta clara, interactiva y funcional para el análisis visual del empleo en Europa.