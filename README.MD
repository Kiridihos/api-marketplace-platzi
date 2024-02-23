<h1>Sistema API RESTfull</h1>
<p>Sistema de prueba API RESTfull creado con en lenguaje de programación Java 17 y con el framework Spring Boot.</p>
<p>Servidor Tomcat embebido de Spring Boot y servidor de base de datos MySQL8.</p>
<h2>:white_check_mark: Contenido de la Aplicación</h2>
<p>La aplicación tiene las siguientes características:</p>
<ul>
  <li>
    <div>Entidades que se mapean con la base de datos:</div>
    <ul>
      <li>Usuario</li>
      <li>Rol</li>
      <li>Cliente</li>
      <li>Tipo de Documento</li>
      <li>Producto</li>
      <li>Categoría</li>
      <li>Sub Categoría</li>
      <li>Marca</li>
      <li>Venta</li>
      <li>Detalle de Venta</li>
    </ul>
  </li>
  <li>Interfaces</li>
  <li>Repositorios</li>
  <li>Servicios</li>
  <li>Controladores</li>
  <li>Manejo de los datos a través de JSON</li>
  <li>Conexión con la base de datos MySQL8</li>
  <li>CRUD para todas las entidades</li>
  <li>Autenticación y autorización con Spring Security</li>
  <li>Seguridad con JWT</li>
  <li>Codigo limpio y buenas prácticas</li>
  <li>Patrón de diseño facade</li>
</ul>
<hr>
<h2>:white_check_mark: Funcionamiento</h2>
<p>El usuario podrá registrar sus datos y luego se almacerán en la base de datos, pero antes de eso serán validados para no ingresar valores en blanco o valores nulos.</p> 
<p>Una vez que el usuario inicie sesión, la aplicación autenticará las credenciales como son su username, password y sus roles, luego generará un TOKEN con la tecnología JWT y así despues comprobará la autorización y la autenticidad del usuario ingresado y según sus roles tedrá acceso a ciertas funciones del programa.</p>
<p>La contraseña como es un dato sensible será encriptada antes de guardarse en la base de datos.</p>
<p>Cada usuario tiene su rol respectivo y cada función de la aplicación tendrá acceso un usuario según su rol indicado, los usuarios administradores podrán realizar todas las funciones mientras que los usuarios sin rol de administrador solo podrán buscar y obtener datos menos guardar o actualizar los datos.</p>
<hr>
<h2>:white_check_mark: Tecnologías</h2>
<ul>
  <li>Lenguaje: Java 17</li>
  <li>Fremework: Spring Boot 3.0.2</li>
  <li>Dependencias: Spring Web, Lombok, Spring Security 6, Spring Data JPA, Validation, JSON Web Tokens (JWT)</li>
  <li>Building: Maven 3.8.6</li>
  <li>Base de Datos: MySQL 8.0.31</li>
  <li>IDEs: IntelliJ IDEA 2022.3.2, Spring Tool Suite 4, NetBeans IDE 16</li>
</ul>
