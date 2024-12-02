# Introducción
Este repositorio contiene el código y los materiales correspondientes al proyecto de Análisis de Datos y Predicción de Precios de Airbnb, realizado como parte de la asignatura Ciencia de Datos en la carrera de Ingeniería Industrial. El objetivo de este proyecto fue analizar datos de Airbnb de anuncios en Estados Unidos y desarrollar modelos para predecir el precio.

## Autores

* Juan Ignacio Gaitez Obando
* Martina Maggi

# Descripción del Dataset
El conjunto de datos utilizado se compone de 19,309 publicaciones y 29 variables, que describen características de las propiedades, como el tipo de propiedad, el tipo de habitación disponible, el barrio donde se encuentran ubicadas, la cantidad de habitaciones, el tipo de cama, y la información sobre el alquiler como la política de cancelación, las opiniones de los huéspedes, la fecha desde que el anfitrión está en Airbnb, entre otras.

A continuación, se puede observar la distribución de la variable objetivo, que en este caso es el precio de las propiedades.

# Análisis exploratorio de datos (EDA)
Durante el análisis exploratorio del conjunto de datos, se observó que las variables numéricas no eran predominantes, por lo que fue necesario realizar la conversión adecuada de las categorías en los features correspondientes. Las conversiones fueron las siguientes:

first_review, host_since, last_review → tipo fecha.
cleaning_fee, instant_bookable, host_identity_verified, host_has_profile_pic → tipo booleano.
host_response_rate → tipo float.
Además, eliminamos las columnas name y thumbnail_url ya que no eran relevantes para el análisis.

En cuanto a los tipos de propiedad, el conjunto de datos contiene 27 categorías de propiedades, como: "House", "Apartment", "Loft", "Condominium", entre otras.
