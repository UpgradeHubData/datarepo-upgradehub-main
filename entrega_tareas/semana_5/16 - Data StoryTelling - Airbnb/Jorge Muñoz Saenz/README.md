# Airbnb_Rome

## Objetivo

Vamos a realizar un estudio de la situación de Airbnb en la ciudad de Roma. Primeramente realizaremos una limpieza de los datos, para posteriormente acometer un estudio de la situación y de la influencia de la normativa Italiana. 

## Introducción

Insideairbnb.com es un sitio web en el que se publican conjuntos de datos extraídos de la web de "instantáneas" de ciudades. Hemos descargado los archivos de Roma de la situación del 7 de junio de 2022 desde [este enlace](http://insideairbnb.com/get-the-data). Pensamos que es un conjunto de datos interesante para trabajar. Además de la disputa de datos básicos y las tramas, también hemos agregado mapas interactivos de Folium, gráficos interactivos de tramas y extracción de texto de los comentarios de revisión.

## Descripción

El conjunto de datos contiene un total de 7 archivos. El archivo de listados es un archivo de descripción general que las etiquetas internas de airbnb como "bueno para visualizaciones". El identificador único en el conjunto de datos es la identificación de "listings". Esta es básicamente la identificación del anuncio. En general, había 23911 listados de Airbnb en Roma el 7 de junio de 2022.


## Variables

- name : Nombre de listado.
- host_id : Id del propietario.
- host_name : Nombre del propietario.
- neighbourhood : Barrio.
- latitude : Latitud (Coordenadas).
- longitude : Longitud (Coordenadas).
- room_type : Tipo de alojamiento.
- price : Precio por noche.
- minimum_nights : Mínimo de noches de alquiler.
- number_of_reviews : Número de reseñas del anuncio.
- last_review : Última reseña del anuncio.
- reviews_per_month : Reseñas mensuales.
- calculated_host_listings_count : Cantidad de listados de cada propietario.
- availability_365 : Cantidad de dias disponible en el año.
- number_of_reviews_ltm : Número de reseñas en el último mes.
- property_type : Descripción del tipo de alojamiento.
- accommodates : Número de personas máximas para cada alojamiento.
- bedrooms : Cantidad de habitaciones disponibles en alojamiento.
- beds : Cantidad de camas disponibles en cada alojamiento.
- first_review : Fecha de primera reseña.
- review_scores_value : Valoración del alojamiento. Sobre 10.
- review_scores_cleanliness : Valoración de limpieza. Sobre 10.
- review_scores_location : Valoración de localización. Sobre 10.
- review_scores_accuracy : Valoracón de exactitud de las reseñas. Sobre 10.
- review_scores_communication : Valoración de comunicación/transporte. Sobre 10.
- review_scores_checkin : Valoración del checkin. Sobre 10.
- review_scores_rating : Valoración global de las reseñas. Sobre 10.
- maximum_nights : Máximo de noches de alquiler.
- listing_url : url del anuncion de Airbnb.
- host_is_superhost : Si el propietario es superhost o no (True/False)
- host_about : Descripción acerca del propietario.
- host_response_time : Tiempo que tarda en responder el propietario.
- host_response_rate : Porcentaje de respuesta del propietario.
