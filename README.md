# HenryBootcamp-DS-PIM3-TechCore

📘 Institución: TechoCore

TechoCore es una cadena de tiendas minoristas fundada en 2014, especializada en la venta y distribución de computadores, equipos electrónicos y accesorios tecnológicos. Con operaciones en Colombia, la empresa se ha consolidado como un referente del sector gracias a su amplio portafolio, su enfoque en la innovación y su capacidad para atender tanto a consumidores como a clientes corporativos. Su compromiso con la tecnología accesible la posiciona como un actor clave dentro de un mercado en continua evolución.

🎓 Carrera: Data Science
📍 Módulo 4
📝 Introducción

El presente proyecto tiene como objetivo transformar una base de datos cruda de ventas en un sistema analítico integral que permita comprender el desempeño comercial de TechoCore. A partir de la limpieza, modelado y análisis de los datos, se buscó construir información confiable, estructurada y visualmente accesible para apoyar la toma de decisiones estratégicas.

El trabajo se desarrolló en tres etapas principales:

Limpieza y preparación de datos: estandarización, depuración y revisión de la calidad de la información.

Diseño del modelo relacional: integración de entidades clave del negocio (ventas, productos, clientes, vendedores, sucursales y ciudades).

Construcción del dashboard en Power BI: visualización de métricas estratégicas y análisis de patrones comerciales.

El resultado final es una herramienta analítica robusta y escalable que convierte datos dispersos en conocimiento accionable, ofreciendo una visión clara del comportamiento de las ventas, los clientes y las tendencias del mercado.

![Proceso ETL en Power Query](https://raw.githubusercontent.com/EnzoZambon/HenryBootcamp-DS-PIM3-TechCore/main/Avance_3/Dashboard_Home.jpg)

🚀 Desarrollo del Proyecto
Avance 1 – Carga y Transformación de Datos

El objetivo inicial fue importar, limpiar y preparar la base de datos “ventas.csv” en Power BI.
Entre los procesos realizados se incluyen:

Promoción de encabezados.

Cambio de tipos de datos.

Reemplazo de valores nulos por cero.

Unificación de nombres de columnas.

Corrección y estandarización de clasificaciones.

En total, se aplicaron 43 pasos de limpieza para asegurar un dataset consistente y estructurado.
Finalmente, se exportó la tabla transformada como “VentasTransformed” para utilizarla en los siguientes avances.

![Proceso ETL en Power Query](https://raw.githubusercontent.com/EnzoZambon/HenryBootcamp-DS-PIM3-TechCore/main/Avance_1/ETL_PowerQuery.jpg)


Avance 2 – Diseño del Modelo Relacional

En esta etapa se diseñó e implementó el modelo relacional que integra las distintas entidades del negocio. Para ello se cargó el dataset limpio en Python (VentasTransformed.csv) y se construyeron las siguientes tablas:

Facturas

DetalleFacturas

Productos

Clientes

Sucursales

Ciudades

Vendedores

Posteriormente, todas las tablas fueron exportadas en un único archivo Excel (ModeloVentas.xlsx) y se realizaron consultas para verificar la calidad y consistencia de los datos.

El modelo relacional final sirve como base para la construcción del modelo en Power BI.

![Proceso ETL en Power Query](https://raw.githubusercontent.com/EnzoZambon/HenryBootcamp-DS-PIM3-TechCore/main/Avance_2/Diseño_Modelo_Relacional.jpg)

Avance 3 – Dashboard Interactivo

La última etapa consistió en importar el archivo ModeloVentas.xlsx a Power BI y construir un dashboard profesional orientado a la toma de decisiones.

Se crearon medidas DAX clave, entre ellas:

Total Ventas

Total Unidades Vendidas

Precio Promedio

Ventas Año Actual

Ventas Año Anterior

Variación % Anual

El dashboard incluye una portada con el logo de la empresa y tres páginas con información estratégica sobre ventas, clientes, productos y zonas geográficas.

![Proceso ETL en Power Query](https://raw.githubusercontent.com/EnzoZambon/HenryBootcamp-DS-PIM3-TechCore/main/Avance_3/Dashboard_KPIS.jpg)

📊 Principales Hallazgos

Ventas acumuladas: $456.65 mil millones.

Unidades vendidas: 90 mil.

Precio promedio por unidad: $5.07 millones.

La empresa presentó una caída del 93% en ventas en el último año.

El 2017 fue el año con mayor nivel de ventas ($43 mil millones).

Medellín (45%) y Bogotá (30%) concentran la mayor participación en ventas.

Métodos de pago más utilizados:

Tarjeta de crédito: 40%

Tarjeta de débito: 20%

Transferencia: 15%

Marcas más vendidas: Lenovo, HP, Dell y Apple.

Clientes de 26 a 45 años concentran el 60% de las ventas.

La proporción de compradores hombres es del 65%.

![Proceso ETL en Power Query](https://raw.githubusercontent.com/EnzoZambon/HenryBootcamp-DS-PIM3-TechCore/main/Avance_3/Dashboard_Ventas.jpg)

🧭 Recomendaciones Estratégicas

Analizar causas internas de la fuerte caída del 93% en ventas.

Incrementar inversión comercial en Medellín y Bogotá.

Establecer alianzas con marcas de alta rotación (Lenovo, HP, Dell, Apple).

Implementar promociones temporales para públicos sensibles al precio.

Incentivar el uso de tarjeta de crédito con cuotas sin interés.

Estimular pagos con débito o transferencia mediante descuentos.

Lanzar beneficios y financiamiento especial en temporadas altas.

Ofrecer beneficios exclusivos para profesionales y estudiantes.

Diseñar ofertas corporativas orientadas a PyMEs.

Crear campañas dirigidas a mujeres enfocadas en diseño y usabilidad.

Ofrecer talleres gratuitos para atraer nuevos segmentos y fidelizar clientes.

📝 Conclusión

El proyecto permitió transformar una base de datos cruda en un completo sistema de análisis que ofrece información clave para comprender el desempeño comercial de TechoCore. Mediante limpieza, modelado relacional y visualización en Power BI, se identificaron tendencias, patrones de compra y oportunidades de mejora. Estos insights brindan una base sólida para la toma de decisiones estratégicas, la optimización de recursos y el fortalecimiento del rendimiento comercial de la empresa.
