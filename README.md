# 📊 Análisis de Desempeño de Tiendas - Alura Store
## 🧾 Descripción General ##
Durante este desafío, ayudamos al Sr. Juan a decidir qué tienda de su cadena Alura Store debe vender para iniciar un nuevo emprendimiento.
Para ello, se analizaron datos de ventas, rendimiento, reseñas y distribución geográfica de las 4 tiendas con el objetivo de identificar
la tienda menos eficiente y presentar una recomendación final basada en evidencia.

## 📌 Objetivos del Proyecto
Analizar el rendimiento de cada tienda en términos de ventas, ingresos y reseñas.

Evaluar productos y categorías más y menos vendidos.

Calcular métricas clave como facturación total, calificación promedio y costo de envío promedio.

Explorar el comportamiento de ventas en función de la ubicación geográfica.

Determinar si existe superposición de cobertura geográfica entre tiendas.

## 🧠 Análisis Realizado
### 1. Carga y unificación de datos
Se cargaron los archivos CSV de las 4 tiendas, se etiquetaron con su nombre correspondiente y se combinaron en un solo DataFrame global (df_global) para facilitar el análisis comparativo.

### 2. Análisis de rendimiento por tienda
Se calcularon las siguientes métricas para cada tienda:

- Facturación total

- Calificación promedio de los clientes

- Costo de envío promedio

- Producto más vendido y menos vendido

- Categorías con mayor y menor número de ventas

Estos datos se presentaron en tablas resumen y gráficos comparativos.

### 3. Visualización de ventas por categoría
Se utilizaron gráficos de barras para comparar la cantidad de ventas por categoría en cada tienda, revelando preferencias de los clientes y la eficacia de cada tienda en distintas líneas de productos.

### 4. Visualización geográfica
Se analizaron las coordenadas geográficas (lat, lon) de las ventas:

- Se crearon mapas de dispersión y mapas de calor (Heatmaps) para cada tienda con Folium y Geopandas.

- Se analizó la concentración geográfica de ventas y se observaron zonas de mayor actividad.

- Se generó un mapa combinado para visualizar la superposición geográfica entre tiendas mediante capas de calor y círculos de cobertura estimada.

## 🧩 Análisis Geográfico
Se identificaron zonas con mayor volumen de ventas, especialmente en zonas urbanas.

Algunas tiendas muestran superposición de cobertura, lo cual podría indicar redundancia geográfica.

Se observaron tiendas con mayor presencia en regiones específicas, lo cual puede ser clave para la toma de decisiones estratégicas.

## ✅ Conclusión
Aunque todas las tiendas presentan un rendimiento competitivo, se recomienda al Sr. Juan vender la Tienda 4 por las siguientes razones:

- Tiene la menor facturación total.

- Presenta la calificación promedio más baja (junto con Tienda 1).

- Su costo de envío promedio es el más bajo, pero esto no compensa sus desventajas.

- Su distribución geográfica de ventas se superpone con otras tiendas, lo que reduce su valor estratégico.

- Los productos menos vendidos indican posible falta de alineación con la demanda regional.
