# CitiesWebsite
MOD05_LAK

En ésta aplicación vemos un ejemplo del uso de los siguientes tipos de vistas:

Vistas Razor
Vistas Componentes
Vistas Parciales e incrustarlas.
Html Helper --> nos pemite generar nuestro propio código HTML dentro de las vistas. 
                Esto simplifica enormemente el código que se genera en la vista porque evitamos tener que generar mucho código en cada llamada a las vistas.
Tag Helper --> para crear componentes reutilizables de generación de código de marcado desde el lado servidor

Comenzamos creando una web que muestra una lista de ciudades que al pulsar en cada una de ellas te lleva a una vista Razor.
Posteriormente se hace una vista parcial con el contenido de esta última vista de cada ciudad y se incrusta en la principal, 
de manera que en lugar de tener una lista de ciudades tenemos una lista de imagenes. Y cada imagen, te lleva a la página de la ciudad. 
La página de cada ciudad tiene un tag helper que nos lleva a la página inical
