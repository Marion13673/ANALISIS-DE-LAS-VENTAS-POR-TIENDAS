**INTRODUCCIÓN** 🚀

El proyecto consiste en ayudar al Sr.Juan a decidir qué tienda de su cadena Alura Store debe vender para iniciar un nuevo emprendimiento. Para ello, se analiza datos de ventas, rendimiento y 
reseñas de las 4 tiendas de Alura Store. El objetivo es identificar la tienda menos eficiente y presentar una recomendación final basada en los datos.

**Características** ✨

Manipular datos CSV con la biblioteca Pandas.

**_Estructura de datos:_** 📑

El conjunto de datos incluye la siguiente información:

* Producto y Categoría: Artículos vendidos y sus calificaciones.
* Precio y Envío: Valores de venta y costos asociados.
* Fecha y ubicación de compra: Información temporal y geográfica.
* Evaluación de compra: Comentarios de clientes.
* Tipo de Pago y Cuotas: Métodos utilizados por los clientes.
* Coordenadas Geográficas: Ubicación de las transacciones.

Crear visualizaciones de datos con la biblioteca Matplotlib.
Analizar métricas como ingresos, reseñas y rendimiento de ventas. resultado del sorteo en la pantalla.

**Requisitos** 🛠️

**__Analizar datos de la tienda:_**
* Evaluando la información como los ingresos, las categorías más vendidas, las reseñas de los clientes, los productos más vendidos y el envío promedio.

**__Crear gráficos para visualización:_**
* Decidir qué tipos de gráficos utilizar para presentar los resultados de forma clara y visual.
* Mínimo de 3 gráficos diferentes, que pueden incluir gráficos de barras, circulares, de dispersión y otros.
  
**_Enviar una recomendación:_**

* Después del análisis, escribir un texto explicando a qué tienda debería vender el Sr. Juán y por qué, basándose en los datos presentados.

**_DESCRIPCIÓN_** 🖌️

**Ventas por categoría**
Se ha calculado la cantidad de productos vendidos por categoría en cada tienda. La idea es agrupar los datos por categoría y contar el número de ventas de cada tipo,
mostrando las categorías más populares de cada tienda.

**_Valoración media por tienda__**
En este paso, se calcula las calificaciones promedio de los clientes para cada tienda. El objetivo es conocer la satisfacción del cliente con los productos vendidos.

**_Productos más vendidos y menos vendidos_**
En este paso, se identifica qué productos fueron los más vendidos y los menos vendidos en cada tienda. Visualizando los resultados para que quede claro qué productos 
destacaron en ventas en cada tienda.

**_Valor del envío promedio por tienda_**
calcular el costo de envío promedio para cada tienda. El objetivo es comprender cuánto se gasta, en promedio, en el envío de cada tienda.

**_Análisis del desempeño geográfico_**
Se utiliza los datos de latitud (lat) y longitud (lon) para mapear las ventas de cada tienda y analizar la distribución geográfica de los productos vendidos.

**_Generando gráfico_**
Se generarón tres gráficos:
1.- Gráfico de torta que visualiza la distribución de los ingresos por ventas en cada tienda.
2.- Gráfico de línea de tiempo "Tendencia de las categoría de los ingresos por venta y año" y " Tendencia de las cantidades vendidas por categorías y año".
3.- Gráfico de heatmaps que visualiza los ingresos por entas por zona geográfico limitada por año.

**CONCLUSIÓN** 💿  
Análisis detallado basádose en los resultados obtenidos en las 4 tiendas en los ingresos por ventas, cantidades vendidas, costos incurridos en el envío de los productos 
a los clientes, calificación promedio de satisfacción que los clientes tienen acerca de cada tienda y producto vendido, como un mapeo acercá de la zona geográfica a la
cual venden más y obtienen mayores ingresos. De tal foma de entregar una conclusión consistente a qué tienda se debe cerrar de acuerdo a los resultados obtenidos. 


**Archivos del Proyecto** 📂
index.html: Estructura del proyecto.
style.css: Estilos del proyecto.
app.js: Lógica de JavaScript para agregar nombres y realizar el sorteo.

**Instrucciones para Ejecutar** 🚀
Clona este repositorio en tu máquina local.
git clone https://github.com/Marion13673/ANALISIS-DE-LAS-VENTAS-POR-TIENDAS.git
Abre el archivo index.html en tu navegador para ver y usar la aplicación.

**Contribuciones** 🤝
💡 ¡Las contribuciones son bienvenidas! Si deseas contribuir a este proyecto, por favor sigue estos pasos:

**Haz un fork del repositorio.**
Crea una rama con tu nueva característica (git checkout -b feature/nueva-caracteristica).
Realiza tus cambios y haz un commit (git commit -m 'Añadir nueva característica').
Envía tu rama (git push origin feature/nueva-caracteristica).
Abre una Pull Request.

**Licencia** 📜
📄 Este proyecto está licenciado bajo la Licencia MIT. Consulta el archivo LICENSE para más información.
