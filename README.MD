# API REST
Esta api fue creada con spring boot, haciendo uso del patron arquitectonico por capas
y haciendo uso de una base de datos en Postgress
## Contenido de la Aplicación 
La api cuenta con las siguientes caracteristicas:

* Entidades que se mapean con la base de datos:
    * Producto
    * Categoría
    * Cliente
    * Compra
    
 * Interfaces
 * Servicios
 * Controladores
 * Manejo de los datos a través de JSON
 * Conexión con la base de datos Postgress
 * CRUD Solo para producto
 * Codigo limpio y buenas prácticas
 * Patron de diseño en capas
____________________________________________
## Funcionamiento

El usuario podra consultar todos los productos de la base de datos, podra buscar uno por su respectivo ID, podra
agregar productos y tambien podra hacer uso del endpoint dedicado a la emiminación de los productos

## Tecnologías

* Lenguaje: Java 17
* Fremework: Spring Boot
* Building: Gradle 8.5
* Base de Datos: PostgreSQL 16
* IDEs: IntelliJ IDEA 2023.3.4
