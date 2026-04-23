Analisis RappiPlus

Se realizó un análisis de datos de RappiPlus, un servicio de suscripción dentro del ecosistema de Rappi con operaciones en México, Colombia y Argentina, para aumentar la frecuencia de compra y valor generado por usuario.

El objetivo del análisis fue entender el desempeño del servicio y detectar oportunidades concretas de mejora.

Para ello, se trabajó con tres fuentes de datos:
a) plans.csv: los planes actuales (precio, minutos incluidos, GB incluidos, costo por extra).
b) users_latam.csv: información de clientes: edad, ciudad, fecha de registro, plan contratado.
c) usage.csv: el detalle de uso real: llamadas (duración) y mensajes (longitud).\

Las etapas del análisis realizadas fueron:
1.- Exploración:
- Cargar y explorar plans, users_latam, usage
- Visión clara de la estructura y tipos de columna de cada dataset.

2.- Identificación de problemas de calidad:
- Contar nulos, detectar sentinels, revisar fechas fuera de rango.
- Lista priorizada de problemas que pueden sesgar decisiones.

3.- Limpieza básica:
- Reemplazar sentinels, convertir fechas, imputar o marcar NA según reglas.
- Datos consistentes y listos para análisis estadístico.

4.- Resumen estadístico:
- Revisar las medidas clave en variables categóricas y numéricas.
- Medidas clave (media, mediana, percentiles) que muestran el comportamiento típico y extremo.

5.- Visualizaciones y outliers:
- Creación de histogramas y boxplots.
- Visualización de sesgos, patrones de usuarios o datos atípicos.

6.- Segmentación de clientes:
- Crear segmentaciones basadas en reglas claras; visualizar proporciones con countplots.
- Segmentos accionables que permiten diseñar ofertas, campañas y migraciones de plan.
- Construcción de un perfil estadístico del uso (llamadas y mensajes) por cliente y por segmentos demográficos.

7.- Insight ejecutivo:
- Redactar conclusiones y recomendaciones comerciales basadas en los pasos anteriores.
- Responder a las preguntas del negocio y proponer acciones concretas.
- Visualización de diferencias entre segmentos y extraer insights comerciales relevantes.

8.- Publicación:
- Subir notebook + README a GitHub.
- Entrega reproducible para revisión y ejecución por stakeholders.

Como ejecutar el notebook desde Google Colab

Haz click en el siguiente botón

Open In Colab]

O

Abre el archivo jpynb. en Github
Haz click en Open in colab
Guía de reproducción.

1.- Estructura de archivos:
- README.md
- analysis_connectatel.jpynb
- data: plans.csv, users_latam.csv, usage.csv

2.- Librerías necesarias: - pandas>=1.3.0
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
