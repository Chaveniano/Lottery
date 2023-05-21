# Lottery
## Descripcion
Es una aplicación que permite obtener y analizar los resultados de diferentes loterías. Utiliza solicitudes HTTP para acceder a una API que proporciona los datos de los sorteos. A continuación, se resumen las principales funcionalidades del código:

El usuario puede especificar la cantidad de días de resultados que desea obtener y seleccionar la lotería de interés.
Se realiza una solicitud a la API para obtener los resultados más recientes de la lotería seleccionada.
Se procesan los datos obtenidos y se almacenan en un DataFrame para su posterior análisis.
Se itera sobre los resultados históricos de los sorteos para obtener información detallada.
Se generan estadísticas básicas sobre los números y series ganadoras.
Se generan propuestas de números y series que superen un umbral de frecuencia definido.
Se imprimen los resultados y propuestas generadas.
