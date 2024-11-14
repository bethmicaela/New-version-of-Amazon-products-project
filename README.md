# Análisis de Ventas en Amazon y Sistema de Recomendación

## Objetivos

El objetivo de este proyecto es analizar más de 1,000 productos de Amazon, utilizando datos de calificaciones, reseñas y descuentos para extraer información relevante sobre el comportamiento de los consumidores y la percepción de los productos. Con base en este análisis, se busca desarrollar un sistema de recomendación personalizado que sugiera productos a los usuarios según sus intereses y comportamientos de compra anteriores, mejorando así la experiencia de compra y facilitando la toma de decisiones informadas.

Los pasos para realizar el análisis son:

📊 Recopilación de datos: Utilizar el "Amazon Sales Dataset" disponible en Kaggle, que incluye información detallada sobre productos, calificaciones y reseñas de más de 1,000 productos.

🧹 Preparación de datos: Limpiar y pre procesar el conjunto de datos para asegurar su calidad y adecuación para el análisis posterior.

🕵️‍♂️ Análisis exploratorio de datos: Explorar los datos para comprender mejor la distribución de los productos por categorías, las calificaciones de los clientes y el contenido de las reseñas.

📈 Visualización de datos: Crear visualizaciones claras y efectivas para identificar tendencias y patrones en las ventas, las calificaciones y las opiniones de los usuarios.

💡 Desarrollo de un sistema de recomendación sencillo: Implementar un sistema de recomendación utilizando un algoritmo de filtrado colaborativo basado en KNN, con la similitud de Pearson. Este algoritmo compara a los usuarios en función de sus calificaciones a productos similares y luego sugiere productos que podrían interesarles.

## Datos
- product_id: ID del producto.
- product_name: Nombre del producto.
- category: Categoría del producto.
- discounted_price: Precio con descuento del producto.
- actual_price: Precio real del producto.
- discount_percentage: Porcentaje de descuento del producto.
- rating: Calificación del producto.
- rating_count: Número de personas que votaron por la calificación de Amazon.
- about_product: Descripción sobre el producto.
- user_id: ID del usuario que escribió la reseña del producto.
- user_name: Nombre del usuario que escribió la reseña del producto.
- review_id: ID de la reseña del usuario.
- review_title: Breve reseña.
- review_content: Revisión larga.
- img_link: Enlace de imagen del producto.
- product_link: Enlace al sitio web oficial del producto.

## Conclusión
![Dashboard de Tableau](https://github.com/bethmicaela/New-version-of-Amazon-products-project/blob/main/dashboard/Amazon-Product-Project.png?raw=true)
El dashboard de Tableau permite identificar las categorías más populares, las valoraciones promedio de los clientes y los patrones de descuento, lo cual facilita un análisis integral de la satisfacción y demanda de productos.

Uno de los hallazgos más destacados fue la popularidad de las categorías **Electronics**, **Computers & Accessories**, y **Home & Kitchen**, junto con una clara tendencia hacia valoraciones positivas en los rangos de **3-4** y **4-5** estrellas. Asimismo, se identificaron categorías mejor valoradas, como **Home Improvement**, **Office Products**, **Home & Kitchen** y **Toys & Games**, con puntuaciones superiores a **4.0**, lo cual indica un alto nivel de satisfacción de los clientes en estos segmentos.

Además, el análisis de descuentos reveló que **Toys & Games** tiene un descuento promedio del **0%**, lo cual sugiere que la demanda en esta categoría es alta, incluso sin incentivos de precio. Por el contrario, las categorías **Home Improvement (57.5%)**, **Computers & Accessories (53.9%)**, y **Electronics (50.8%)** presentan los mayores descuentos, indicando una sensibilidad al precio y la necesidad de estrategias competitivas para atraer clientes.

Estos resultados sugieren que la estrategia de ventas podría enfocarse en optimizar los inventarios de categorías populares, mientras que los descuentos podrían mantenerse o incrementarse en categorías más sensibles al precio. Como próximos pasos, se recomienda monitorear periódicamente las valoraciones y ajustar los descuentos según la demanda, además de considerar análisis adicionales sobre la relación entre valoraciones y descuentos para ajustar la estrategia de mercado de manera más precisa.

## Recursos
[ Amazon Sales Dataset](https://www.kaggle.com/datasets/karkavelrajaj/amazon-sales-dataset)

## Librerias
 - Pandas
 - Matplotlib
 - Seaborn
 - WordCloud
 - Surprise


