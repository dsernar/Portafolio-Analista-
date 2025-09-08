# 📊 Portafolio de Análisis de Datos

Este repositorio contiene proyectos de análisis de datos desarrollados con **R**, **SQL** , **Python** y herramientas de visualización.

---

## 📈 Proyecto 1: Análisis de Ventas

**Descripción:**  
Este proyecto analiza un dataset simulado de **1.000 transacciones de ventas**, con variables como fecha, región, categoría, producto, ventas y unidades.  
El objetivo fue construir KPIs y visualizaciones que permitan identificar patrones de consumo, productos estratégicos y desempeño por región y categoría.

**Tareas realizadas:**
- Limpieza y carga de datos (`ventas.csv`).
- Cálculo de KPIs clave:
  - Ventas totales.
  - Promedio de ventas por transacción.
  - Total de unidades vendidas.
  - Precio promedio por unidad.
- Agrupación y análisis de ventas por región y categoría.
- Identificación del **Top 5 de productos más vendidos**.
- Evolución mensual de las ventas para detectar patrones estacionales.
- Visualización mediante gráficos con **ggplot2**.

**Principales hallazgos:**
- La **región Sur** tiene el mayor valor promedio por transacción.  
- La categoría **Hogar** genera más ingresos, mientras que **Ropa y Alimentos** lideran en unidades vendidas.  
- Existen patrones de estacionalidad en las ventas que podrían aprovecharse para campañas de marketing.  
- Los **Top 5 productos** concentran gran parte de las ventas totales.  

📂 Archivos:  
- `data/ventas.csv` → dataset base.  
- `analisis/Analisis_ventas.Rmd` → análisis reproducible en R Markdown.  
- `analisis/Analisis_ventas.html` → reporte visual con gráficos.  

---

## 🌍 Proyecto 2: Energía Renovable, Crecimiento Económico y Emisiones de CO₂

**Descripción:**  
Este proyecto analiza la relación entre **uso de energías renovables, crecimiento económico y emisiones de CO₂** en diferentes países.  
Se utilizó **SQL** para el procesamiento de datos y **Google Looker Studio** para la construcción de un dashboard interactivo.

**Metodología:**
1. Creación de una tabla base con métricas per cápita para controlar el tamaño poblacional.  
2. Selección de los **Top 5 países con mayor participación de energías renovables en 2022** (China, Nueva Zelanda, Dinamarca, Filipinas y Perú).  
3. Construcción del dataset final con evolución de:
   - % de Energía Renovable.  
   - Emisiones de CO₂ per cápita.  
   - PIB per cápita.  
4. Creación de un dashboard con dos páginas en Google Looker Studio:  
   - **Página 1:** series temporales y KPIs por país.  
   - **Página 2:** gráfico de dispersión relacionando energía renovable, CO₂ y PIB.  

**Conclusiones principales:**
- Es posible **desacoplar crecimiento económico de las emisiones**, pero depende de políticas energéticas y del desarrollo tecnológico.  
- **Dinamarca y Nueva Zelanda** muestran un crecimiento económico sostenible con reducción de emisiones.  
- **China y Perú** presentan crecimiento acompañado de mayores emisiones.  
- El uso de **energía renovable es un factor clave** para lograr sostenibilidad.

  
## 📌 Proyecto 3: Análisis y Predicción de Ventas Walmart

**Objetivo:** Analizar ventas históricas de Walmart, explorar patrones por tienda y departamento, y realizar una predicción de ventas.  

**Herramientas utilizadas:** R, RMarkdown, ggplot2, forecast  

**Análisis realizado:**  
- 📊 Ventas totales por tienda (Top 15 sucursales).  
- 📈 Evolución semanal de las ventas.  
- 🏷️ Top 10 departamentos con más ingresos.  
- 🏬 Comparación de ventas por **tipo de tienda** y análisis del impacto del **tamaño de tienda**.  
- 🔮 Predicción de ventas (modelo ARIMA, 12 semanas para la Tienda 1).  

**Conclusiones principales:**  
- Un pequeño grupo de tiendas concentra la mayoría de ventas (>250M cada una).  
- Las ventas muestran picos en semanas festivas (Acción de Gracias y Navidad).  
- Jardinería y Automotriz son los departamentos más relevantes en ingresos.  
- Las tiendas **Tipo A** y de mayor tamaño muestran mejor desempeño.  
- El modelo ARIMA proyecta ventas estables con picos recurrentes; puede mejorarse incluyendo variables externas.  


📂 Archivos:  
- `analisis/Analisis_Energia_CO2_SQL.pdf` → reporte en PDF con metodología y consultas SQL.  
- [Dashboard en Looker Studio](#) *https://lookerstudio.google.com/s/hhUnXdyarZs*.  

---

## 🚀 Tecnologías utilizadas
- **Lenguajes:** R, SQL.  
- **Librerías en R:** dplyr, ggplot2, knitr.  
- **Visualización:** R Markdown, Google Looker Studio.  
- **Control de versiones:** Git & GitHub.  

---

✍️ *Autora: Dayana Serna Restrepo*  
📅 *Última actualización: Septiembre 2025*  
