# 📊 Proyecto ETL de Indicadores Económicos del Perú 🇵🇪

Este proyecto tiene como objetivo automatizar la recolección, transformación y análisis de indicadores económicos relevantes del Perú, utilizando herramientas de Python, Power BI y técnicas de ETL modernas.

---

## ⚙️ Tecnologías utilizadas

- **Python**: para la conexión con la API del BCRP, procesamiento y exportación de datos.
- **Bibliotecas**: `requests`, `pandas`, `datetime`, `os`, entre otras.
- **Power BI**: para la visualización dinámica de los indicadores.
- **CSV**: como formato intermedio de almacenamiento de datos consolidados.

---

## 🛠️ Flujo del proyecto

1. **Extracción (Extract)**:
   - Conexión a la [API del BCRP](https://estadisticas.bcrp.gob.pe/estadisticas/series/) mediante Python.
   - Obtención de series económicas clave: PBI, tipo de cambio, inflación, gasto público, etc.

2. **Transformación (Transform)**:
   - Limpieza y validación de datos.
   - Conversión de fechas con `datetime`.
   - Normalización y consolidación de tablas.

3. **Carga (Load)**:
   - Exportación de los datasets transformados a archivos `.csv`.
   - Carga de los CSV a Power BI para modelado y visualización.

4. **Visualización**:
   - Tableros interactivos de evolución histórica, comparativos y análisis por periodos.
   - Uso de filtros temporales, KPIs y tarjetas DAX personalizadas.

---

## 📁 Estructura de archivos

├── data/
│ ├── indicadores_macro.csv
│ ├── precios_mensuales.csv
│ └── gasto_gobierno.csv
├── scripts/
│ └── etl_bcrp.py
├── dashboard/
│ └── powerbi_report.pbix
├── README.md

yaml
Mostrar siempre los detalles

Copiar

---

## 📌 Objetivo del proyecto

Desarrollar un sistema automatizado de análisis económico para monitorear en tiempo real los principales indicadores macroeconómicos del país. Esto permite facilitar la toma de decisiones, la elaboración de reportes y el análisis de tendencias con información oficial y actualizada.

---

## 🚀 Próximos pasos

- Integrar otras fuentes oficiales como INEI o SUNAT.
- Implementar control de versiones y actualizaciones automáticas.
- Desplegar el dashboard en Power BI Service con actualizaciones programadas.

---

**Autor**: Jeffersson Pretell  
**Contacto**: [LinkedIn](https://www.linkedin.com/in/jpretell) | [Correo](mailto:jpretell66@gmail.com)
"""
