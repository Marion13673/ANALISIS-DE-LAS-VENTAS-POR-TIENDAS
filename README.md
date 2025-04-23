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

Visualizaciones de datos con la biblioteca Matplotlib.
Análisis métricas como ingresos, reseñas y rendimiento de ventas. 

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
3.- Gráfico de heatmaps que visualiza los ingresos por ventas por zona geográfica limitada por año.

**CONCLUSIÓN** 💿  
Análisis detallado basádose en los resultados obtenidos en las 4 tiendas en los ingresos por ventas, cantidades vendidas, costos incurridos en el envío de los productos 
a los clientes, calificación promedio de satisfacción que los clientes tienen acerca de cada tienda y producto vendido, como un mapeo acercá de la zona geográfica a la
cual venden más y obtienen mayores ingresos. De tal foma de entregar una conclusión consistente a qué tienda se debe cerrar de acuerdo a los resultados obtenidos. 

**Archivos del Proyecto** 📂
- **CSV**: Archivos que contienen las bases de datos de cada tienda, utilizados para el análisis.
- **Jupyter Notebook**: Proyecto desarrollado en Google Colaboratory, utilizando Python y bibliotecas como Pandas para realizar el análisis de datos.

**Lenguaje y Bibliotecas Utilizadas** 💻
- **Lenguaje**:
  * **Python**
- **Bibliotecas Principales**:
  * **Pandas**: Manipulación y análisis de datos estructurados.
  * **NumPy**: Trabajo con arrays multidimensionales y cálculos matemáticos.
  * **Matplotlib**: Creación de gráficos y visualizaciones de datos.

**Instalación** 💽
Ejecuta el siguiente comando para instalar las bibliotecas necesarias:
```bash
pip install pandas numpy matplotlib

**Instrucciones para Ejecutar** 🚀
Clona este repositorio en tu máquina local: ´´´bash
git clone https://github.com/Marion13673/Analisis-ventas-por-tienda.git
Abre el archivo index.html en tu navegador para ver y usar la aplicación.

**Contribuciones** 🤝
💡 ¡Las contribuciones son bienvenidas! Si deseas contribuir a este proyecto, por favor sigue estos pasos:

**Haz un fork del repositorio.**
Crea una rama con tu nueva característica (git checkout -b feature/nueva-caracteristica).
Realiza tus cambios y haz un commit (git commit -m 'Añadir nueva característica').
Envía tu rama al repositorio remoto (git push origin feature/nueva-caracteristica).
Abre una Pull Request.

**Licencia** 📜
📄 Este proyecto está licenciado bajo la Licencia MIT. Consulta el archivo LICENSE para más información.
