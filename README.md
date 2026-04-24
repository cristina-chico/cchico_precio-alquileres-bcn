# Precio alquileres en Barcelona

# Descarga de la data

* Aclaraciones: Es un proyecto educacional.
  
El portal **Open Data BCN** ofrece conjuntos de datos de "Alto Valor" que son fundamentales para construir variables predictivas (features) precisas
.
De las categorías identificadas en las fuentes, las que más te sirven son:
Estadística: Es crucial para obtener datos sobre el contexto socioeconómico de los barrios, como niveles de renta, densidad de población o estadísticas históricas, que suelen correlacionar directamente con los precios de alquiler
.
Geoespacial: Permite trabajar con la delimitación de distritos y barrios
. En machine learning, la ubicación es una de las variables con mayor peso; estos datos te permiten asignar coordenadas precisas o etiquetas de zona a cada inmueble de tu dataset.
Mobilitat (Movilidad): La proximidad al transporte público (metro, bus, bicing) es un factor determinante en el valor de un alquiler
. Puedes usar estos datos para calcular distancias entre los pisos y los puntos de transporte más cercanos.
Observació de la Terra i medi ambient: Factores como la calidad del aire o niveles de ruido pueden ser variables interesantes para modelos más complejos que busquen explicar variaciones de precio basadas en la calidad de vida de la zona
.
Ventajas técnicas para tu proyecto:
Formatos reutilizables: Los datos están disponibles en formatos que puedes importar directamente a tus scripts de Python o R (como CSV o JSON), facilitando la etapa de preprocesamiento de datos
.
Actualización y oficialidad: Al ser el servicio oficial del Ayuntamiento, aseguras que la base estadística de tu modelo sea fiable
.
Como complemento a estos datos públicos, las fuentes sugieren que podrías cruzar esta información con datos de mercado provenientes de idealista/data, que ofrece tecnología específica para el análisis inmobiliario profesional

Jsons por poblacion: https://opendata-ajuntament.barcelona.cat/data/ca/dataset/pad_mdbas
