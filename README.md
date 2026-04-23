Analisis RappiPlus

Se realizó un análisis de datos de RappiPlus, un servicio de suscripción dentro del ecosistema de Rappi con operaciones en México, Colombia y Argentina, para aumentar la frecuencia de compra y valor generado por usuario.

El objetivo del análisis fue entender el desempeño del servicio y detectar oportunidades concretas de mejora.

Para ello, se trabajó con tres fuentes de datos:  
a) 'rappiplus_orders.csv': cada fila representa un pedido realizado en la plataforma
b) rappiplus_catalog.csv: cada fila representa un producto disponible en la plataforma
c) rappiplus_marketing_spend.csv: cada fila representa una inversión en marketing realizada en un país y canal específico.

Las etapas del análisis realizadas fueron:
1.- Preparación y calidad de datos con Pyton:
- Pregunta clave: ¿Podemos confiar en los datos?
- Evaluar calidad de los datos.
- Detectar inconsistencias.
- Limpiar y estructurar datasets.
- Generar un data.
- Resultado esperado: dataset limpio.

2.- Análisis de rentabilidad del negocio con Python.
- Pregunta clave: ¿El negocio es rentable?
- Cálculo de KPIs (ejemplo ingresos/revenue, costos, ganancias)
- Identificación de segmentos rentables.
- Resultado esperado: KPIs (revenue, cost, profit)

3.- 
- Pregunta clave: ¿
- Resultado esperado:

4.- 
- Pregunta clave: ¿
- Resultado esperado:

5.- 
- Pregunta clave: ¿
- Resultado esperado:
  
6.- 
- Pregunta clave: ¿
- Resultado esperado:

7.- 
- Pregunta clave: ¿
- Resultado esperado:
  
8.- 
- Pregunta clave: ¿
- Resultado esperado:

Como ejecutar el notebook desde Google Colab

Haz click en el siguiente botón

Open In Colab]

O

Abre el archivo jpynb. en Github
Haz click en Open in colab
Guía de reproducción.

1.- Estructura de archivos:
- README.md
- analysis_rappiplus.jpynb
- data: orders.csv, catalog.csv, marketing.csv

2.- Librerías necesarias: 
- pandas>=1.3.0
- numpy>=1.21.0
- matplotlib>=3.4.0
- seaborn>=0.11.0
- jupyter>=1.0.0

3.- Pasos de reproducción:
- Preparación del entorno: descargar repositorio, cargarlo a google colab.
- Flujo de análisis (7 pasos):

3.1 Exploración
3.2 Identificación problemas de calidad
3.3 Limpieza básica
3.4 Resumen estadístico
3.5 Visualizaciones y outliers.
3.6 Segmentación de clientes
3.7 Insight ejecutivo
