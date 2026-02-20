
# Proyecto Bases de Datos
## Descripción General
El conjunto de datos consta de 45,466 películas estrenadas hasta julio de 2017. Fue recolectado por Rounak Banik utilizando la API de TMDB y datos de GroupLens. Su propósito inicial era una base para poder narrar la historia del cine y facilitar el desarrollo de sistemas de recomendación. No se ha actualizado desde el día de su publicación.

Origen: Kaggle (https://www.kaggle.com/datasets/rounakbanik/the-movies-dataset)

## Estructura de los Datos
El archivo principal consta de 45,466 tuplas y 24 atributos.

### Clasificación de Atributos:
***Numéricos***: 'budget' (presupuesto), revenue (ingresos), runtime (duración), popularity, vote_average y vote_count.

***Categóricos***: adult (clasificación), original_language, status (estado de producción), genres (géneros en JSON) y production_companies.

***Texto***: title, overview (sinopsis), tagline (eslogan) y imdb_id.

***Temporales***: release_date (fecha de estreno).

## Objetivo del Proyecto
El equipo utilizará este set para identificar patrones de éxito comercial. El fin último es entrenar un modelo que prediga la rentabilidad y calificación de una película basándose en variables de producción (reparto, género y presupuesto) antes de su lanzamiento.

## Consideraciones Éticas
El análisis se rige bajo los siguientes principios:

Sesgo Cultural: Los datos reflejan mayoritariamente la industria de Hollywood; los resultados podrían no ser aplicables al cine independiente o internacional.

Privacidad: Se garantiza el anonimato de los usuarios en los archivos de calificaciones (IDs anonimizados).

Diversidad: El equipo se compromete a señalar si los algoritmos de recomendación resultantes tienden a invisibilizar géneros o minorías debido a sesgos históricos en los datos.

Veracidad: Se reconoce que, al ser datos de crowdsourcing, pueden existir imprecisiones en las cifras de presupuesto o ingresos.

## Integrantes
Alejandro Ozymandias Cepeda Beltran, CU:219451  
Renata Pasalagua Payá, CU:218650  
Mariana Rendón Monroy, CU:217225  
Nicolás Burgueño Rodríguez, CU:218065  
Gerardo Villanueva Vargas, CU:219890  
Paula Fernández Gregorio, CU:218821  