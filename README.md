<h1 align="center"> FORO-HUB</h1>

## Tecnologias
## POST /topicos/login: 
Autenticación de usuarios con nombre de usuario y contraseña.
<img src="Imagenes\LOGIN.png"/>
## POST /topicos: 
Permite a los usuarios crear nuevos tópicos en el foro con su token generado.
<img src="Imagenes\Registro Topico.png"/>
## GET /topicos/listado: 
Muestra una lista de todos los tópicos disponibles.
<img src="Imagenes\LISTADO.png"/>
## PUT /topicos/{id}: 
Permite la actualización de la información de un tópico existente.
<img src="Imagenes\ACTUALIZAR TOPICO.png"/>
## DELETE /topicos/{id}: 
Elimina tópicos no deseados del foro.
<img src="Imagenes\DELETE.png"/>

## BASE DE DATOS
<img src="Imagenes\DB.png"/>

## Dependencias
* Spring Data JPA
* PostgreSQL Driver
* Jackson-databind
* Lombok
* Flyway
* MySql-connector
* JWT
* Spring (web,security,validation,JPA)
* Versión Java SpringBoot (Initializr) 17

