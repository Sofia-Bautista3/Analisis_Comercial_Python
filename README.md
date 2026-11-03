# Analisis_Comercial_Python

## Proyecto 2: Análisis Comercial - Python
- Contexto de Negocio:

Una empresa del sector comercial requiere unificar y sanear su información operativa dispersa en múltiples archivos Excel sin estructura uniforme e inconsistencias en formatos, categorías y registros. La meta del proyecto consiste en procesar y reconstruir los datos, calcular KPIs comerciales, medir el cumplimiento de metas y automatizar la generación de reportes ejecutivos en Excel e imágenes analíticas de forma que se convierta en informacion accionable para la toma de decisiones.

- Fuentes de Datos:

El proyecto integra 6 archivos Excel:
1. 01_ventas.xlsx
2. 02_clientes.xlsx
3. 03_productos.xlsx
4. 04_vendedores.xlsx
5. 05_sucursales.xlsx
6. 06_metas.xlsx

- Proceso de Análisis:

El proyecto fue desarrollado en Python utilizando pandas y matplotlib. Etapas principales:

1. Carga de múltiples fuentes de datos
2. Diagnóstico de calidad de datos
3. Limpieza y estandarización:
   - normalización de textos
   - homologación de categorías
   - conversión de fechas
4. Cruce de tablas (joins)
5. Construcción de base consolidada
6. Cálculo de KPIs
7. Visualización de resultados

- Resultados e Insights:

1. Desempeño Comercial y Márgenes: Determinadas categorías (Tecnologia, Hogar y Moda) generan volumen de ventas alto pero margen ajustado, mientras que ciertos productos específicos del Top 10 aportan la mayor parte de la utilidad operativa.
2. Efectividad del Canal de Venta: Se identificaron canales (Tienda y Distribuidor) con mayor tasa de penetración y ticket promedio más elevado.
3. Brecha en Metas (Actual vs. Proyectado): La comparativa visual evidenció sucursales que sobrepasaron su meta de unidades/ventas versus aquellas con desfases recurrentes en el periodo de tiempo analizado. 

- Tecnologías Utilizadas:

1. Pandas
2. Matplotlib
3. Google Colab

