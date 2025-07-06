<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <title>Proyecto ETL de Indicadores Económicos del Perú</title>
</head>
<body>

<h1>📊 Proyecto ETL de Indicadores Económicos del Perú 🇵🇪</h1>
<p>Este proyecto tiene como objetivo automatizar la recolección, transformación y análisis de indicadores económicos relevantes del Perú, utilizando herramientas de Python, Power BI y técnicas de ETL modernas.</p>

<hr>

<h2>⚙️ Tecnologías utilizadas</h2>
<ul>
    <li><strong>Python</strong>: para la conexión con la API del BCRP, procesamiento y exportación de datos.</li>
    <li><strong>Bibliotecas</strong>: <code>requests</code>, <code>pandas</code>, <code>datetime</code>, <code>os</code>, entre otras.</li>
    <li><strong>Power BI</strong>: para la visualización dinámica de los indicadores.</li>
    <li><strong>CSV</strong>: como formato intermedio de almacenamiento de datos consolidados.</li>
</ul>

<h2>🛠️ Flujo del proyecto</h2>
<ol>
    <li><strong>Extracción (Extract)</strong>:
        <ul>
            <li>Conexión a la <a href="https://estadisticas.bcrp.gob.pe/estadisticas/series/" target="_blank">API del BCRP</a> mediante Python.</li>
            <li>Obtención de series económicas clave: PBI, tipo de cambio, inflación, gasto público, etc.</li>
        </ul>
    </li>
    <li><strong>Transformación (Transform)</strong>:
        <ul>
            <li>Limpieza y validación de datos.</li>
            <li>Conversión de fechas con <code>datetime</code>.</li>
            <li>Normalización y consolidación de tablas.</li>
        </ul>
    </li>
    <li><strong>Carga (Load)</strong>:
        <ul>
            <li>Exportación de los datasets transformados a archivos <code>.csv</code>.</li>
            <li>Carga de los CSV a Power BI para modelado y visualización.</li>
        </ul>
    </li>
    <li><strong>Visualización</strong>:
        <ul>
            <li>Tableros interactivos de evolución histórica, comparativos y análisis por periodos.</li>
            <li>Uso de filtros temporales, KPIs y tarjetas DAX personalizadas.</li>
        </ul>
    </li>
</ol>

<h2>📁 Estructura de archivos</h2>
<pre>
├── data/
│   ├── indicadores_macro.csv
│   ├── precios_mensuales.csv
│   └── gasto_gobierno.csv
├── scripts/
│   └── etl_bcrp.py
├── dashboard/
│   └── powerbi_report.pbix
├── README.md
</pre>

<h2>📌 Objetivo del proyecto</h2>
<p>Desarrollar un sistema automatizado de análisis económico para monitorear en tiempo real los principales indicadores macroeconómicos del país. Esto permite facilitar la toma de decisiones, la elaboración de reportes y el análisis de tendencias con información oficial y actualizada.</p>

<h2>🚀 Próximos pasos</h2>
<ul>
    <li>Integrar otras fuentes oficiales como INEI o SUNAT.</li>
    <li>Implementar control de versiones y actualizaciones automáticas.</li>
    <li>Desplegar el dashboard en Power BI Service con actualizaciones programadas.</li>
</ul>

<hr>

<p><strong>Autor:</strong> Jeffersson Pretell<br>
<strong>Contacto:</strong> <a href="https://www.linkedin.com/in/jpretell" target="_blank">LinkedIn</a> | <a href="mailto:jpretell66@gmail.com">Correo</a></p>

</body>
</html>
