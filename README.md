# DOCKER-COMPOSE RAILS 5

No mueran en su miserable intento de trabajar con una versión estable de rails 5 con docker y que despliegue en Heroku sin problemas, yo ya morí por ustedes. Clonen este repositorio y ajá!

![Image](https://www.freecodecamp.org/news/content/images/2019/08/image-136-2.png)

* Ruby versión

`ruby '2.5.7'`

* Rails versión

`'rails', '~> 5.2.0'`

## Instrucciones para dummies y mancos ...

### Clonar el repositorio

`git clone https://github.com/nildiert/rails5-docker.git && cd rails5-docker`


### Cambiar propietario de usuario (Solo haganlo y ya)

`sudo chown $USER:$USER -R .`


### Crear la base de datos

`docker-compose run --rm web rails db:create`


### Correr el contenedor
`docker-compose up`

`docker-compose up -d`



### Ejecutar comandos de rails

`docker-compose run --rm web rails generate model User name:string status:boolean`

`docker-compose run --rm web rails db:migrate`



## Changelog
* 14-Dec-2019 Creación




## Agradecimientos
* [Agradecimientos especiales](https://lmgtfy.com/?q=A+t%C3%AD+cosita!!)




## Correcciones, fallos y sugerencias (DM)
[![Twitter](https://img.icons8.com/clouds/2x/twitter.png)](https://twitter.com/nildiert)
