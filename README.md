# DOCKER-COMPOSE RAILS 5

No mueran en su miserable intento de trabajar con una versión estable de rails 5 con docker y que despliegue en Heroku sin problemas, yo ya morí por ustedes. Clonen este repositorio y ajá!

![Image](https://phrase.com/blog/wp-content/uploads/2017/09/Ruby_on_Rails-Docker_Compose-768x512.jpg)

* Ruby versión

`ruby '2.5.7'`

* Rails versión

`'rails', '~> 5.2.0'`

----
## Instrucciones para dummies y mancos ...

----
### Clonar el repositorio

`git clone https://github.com/nildiert/rails5-docker.git && cd rails5-docker`

----
### Crear la base de datos

`docker-compose run --rm web rails db:create`

----
### Correr el contenedor
`docker-compose up`

----
### Ejecutar comandos de rails

`docker-compose run --rm web rails generate model User name:string status:boolean`

`docker-compose run --rm web rails db:migrate`

----
## Changelog
* 14-Dec-2019 Creación


----
## Agradecimientos
* [Agradecimientos especiales](https://lmgtfy.com/?q=A+t%C3%AD+cosita!!)
* 


----
## Correcciones, fallos y sugerencias (DM)
[![Twitter](https://img.icons8.com/clouds/2x/twitter.png)](https://twitter.com/nildiert)
