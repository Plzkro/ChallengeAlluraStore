# Desafío Alura Store: Análisis de Rendimiento de Tiendas

## Propósito del Análisis

Este proyecto tiene como objetivo principal ayudar al Sr. Juan, propietario de la cadena "Alura Store", a identificar la tienda con el menor desempeño entre sus cuatro sucursales. El análisis se realiza para que el Sr. Juan pueda tomar una decisión informada sobre qué tienda vender y así liberar capital para invertir en un nuevo emprendimiento, optimizando sus recursos.

El análisis se centra en métricas clave de ventas, finanzas y satisfacción del cliente para proporcionar una recomendación basada en datos.

## Estructura del Proyecto y Organización de Archivos

Este repositorio contiene los siguientes archivos:

* `AluraStoreLatam.ipynb`: Este es el cuaderno principal de Jupyter (Google Colab) donde se realizó todo el análisis de datos, las visualizaciones y se formuló la recomendación final.
* `tienda_1.csv`, `tienda_2.csv`, `tienda_3.csv`, `tienda_4.csv`: Son los archivos CSV de las bases de datos de cada una de las cuatro tiendas, utilizados como fuente de datos para el análisis. (Estos archivos se acceden directamente desde la URL de GitHub proporcionada en el notebook base).

El flujo de trabajo dentro del `AluraStoreLatam.ipynb` está organizado en secciones claras para facilitar la comprensión:
1.  **Importación y Preparación de Datos:** Carga de los CSV y combinación en un solo DataFrame.
2.  **Análisis de Facturación:** Cálculo y visualización de ingresos totales por tienda.
3.  **Ventas por Categoría:** Desglose y visualización de la facturación por categorías de productos.
4.  **Calificación Promedio de la Tienda:** Análisis y visualización de la satisfacción del cliente.
5.  **Productos Más y Menos Vendidos:** Identificación de los productos con mayor y menor frecuencia de transacciones.
6.  **Conclusión y Recomendación Final:** Resumen de los hallazgos y la recomendación al Sr. Juan.

## Ejemplos de Gráficos e Insights Obtenidos

Durante el análisis, se generaron diversas visualizaciones para entender mejor el rendimiento de cada tienda. A continuación, se describen algunos ejemplos de gráficos y los insights clave:

* **Gráfico de Barras de Facturación Total por Tienda:** Este gráfico muestra claramente la contribución de cada tienda a los ingresos generales. Se observó que la **Tienda 4** consistentemente presentaba la facturación más baja entre las cuatro.
    * *Insight:* La Tienda 4 es la que menos ingresos genera, lo que la posiciona como la principal candidata para una posible venta.

* **Gráficos de Pastel (Pie Charts) de Facturación por Categoría por Tienda:** Estos gráficos desglosaron la composición de la facturación de cada tienda por categorías de productos.
    * *Insight:* Se identificó que, si bien 'Electrónicos' y 'Electrodomésticos' son categorías de alto valor en todas las tiendas, la Tienda 4 mostró una facturación proporcionalmente menor en estas categorías clave en comparación con las otras tiendas.

* **Gráfico de Barras de Calificación Promedio de Clientes:** Visualización de la satisfacción del cliente por tienda.
    * *Insight:* La Tienda 1 obtuvo la calificación promedio más baja, mientras que la Tienda 3 tuvo la más alta. La Tienda 4 se ubicó en un punto intermedio, no siendo la mejor ni la peor en este aspecto.

* **Gráfico de Barras Horizontal de Top 10 Productos Más Vendidos (Global):** Se mostró qué productos son los más populares en general, considerando todas las tiendas.
    * *Insight:* Permitió identificar patrones de consumo y entender qué productos tienen mayor demanda a nivel de cadena.


¡Espero que este análisis sea de gran utilidad para el Sr. Juan en su toma de decisiones!
