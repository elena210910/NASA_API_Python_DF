# NASA_API_Python_DF
# Análisis de asteroides utilizando la API de NASA

![](https://github.com/elena210910/NASA_API_Python_DF/blob/main/asteroid_image.jpg)

Este proyecto utiliza la API gratuita y abierta de NASA ([enlace a la API](https://api.nasa.gov/)) para obtener datos sobre asteroides.
Según la documentación, se pueden obtener datos solo por un período de 7 días. Elegí el tema de asteroides para este análisis.

La respuesta de la API llega en formato JSON, del cual seleccionamos las columnas que nos interesan. 
Los datos obtenidos se transforman en un DataFrame de Pandas para su  análisis.

### Bibliotecas utilizadas

- Python
- requests
- json
- pandas

### Análisis

Realizamos un análisis basado en los datos obtenidos, donde calculamos la cantidad de asteroides potencialmente peligrosos, 
el diámetro máximo y mínimo de los asteroides, así como la velocidad relativa promedio de los asteroides.
