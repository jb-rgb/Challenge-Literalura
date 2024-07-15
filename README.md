# LiterALura 📚

## Comenzando 🚀

El propósito de este desafío es desarrollar un Catálogo de Libros que permita la interacción textual (vía consola) con los usuarios, ofreciendo al menos 5 opciones de interacción. Los libros se buscarán a través de una API específica.

La API utilizada en este proyecto es **GUTENDEX**.

## Pasos para lograr el CHALLENGE 🔧

1. **Configuración del Entorno Java**: La configuración del proyecto comenzó utilizando [Spring Initializr](https://start.spring.io/) y el entorno de desarrollo IntelliJ IDEA.
2. **Creación del Proyecto**: Se creó el repositorio en GitHub y las clases necesarias para el desafío.
3. **Consumo de la API**: Se realizó el consumo de la API GUTENDEX.
4. **Análisis de la Respuesta JSON**: Mediante POSTMAN y pruebas se verificó la respuesta de la API.
5. **Inserción y Consulta en la Base de Datos**: Se utilizó una base de datos relacional SQL, PostgreSQL, y con la ayuda de pgAdmin se gestionó la aplicación.
6. **Presentación de Resultados a los Usuarios**: Se implementó un menú en consola que muestra las opciones disponibles para el usuario.

## Configuración del archivo `application.properties` 🛠️

En el archivo `application.properties`, se utilizaron variables de entorno para la configuración de la base de datos:

```properties
spring.datasource.url = jdbc:postgresql://${DB_HOST}/${DB_NAME}
spring.datasource.username=${DB_USER}
spring.datasource.password=${DB_PASSWORD}
```

- `DB_HOST`: es el host de la base de datos.
- `DB_NAME`: es el nombre de la base de datos.
- `DB_USER`: es el usuario para ingresar a la base de datos.
- `DB_PASSWORD`: es la contraseña para poder ingresar a la base de datos.

## Construido con las siguientes herramientas 🛠️

- **Spring** - Framework de aplicaciones
- **PostgreSQL** - Sistema de gestión de bases de datos
- **IntelliJ IDEA** - IDE (Entorno de desarrollo integrado)

## Autor ✒️

- **Jorge Arturo Barahona de la Cruz** - [jb-rgb](https://github.com/jb-rgb)
