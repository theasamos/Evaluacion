# Evaluacion
Evaluacion de programacion Web
Pasos para ejecutar el aplicativo

Descargar el aplicativo.

Descomprimir el archivo zipeado. Copiar y pegar el aplicativo a un servidor local (PC) o subirlo a un hosting

Subir el archivo sql datos.sql al phpMyAdmin.

Modificar el archivo "conexion.php" de la carpeta includes:

define("SERVIDOR","nombre del servidor"); // nombre del servidor (por defecto es localhost)
define("USUARIO","usuario"); // El usuario de la base de datos MySQL
define("CLAVE","tu clave"); // La clave de la bd MySQL. Si tienes instado xampp, dejarlo en blanco
define("BASE_DATOS","tu base de datos"); //El nombre de la base de datos que has creado.
Ejecutar la aplicación y listo.
