# pruebaendeavor
Sitio wordpress
- Descarga los archivos "prueba_endeavor.rar" y "prueba_endeavor.sql".
- Crea la carpeta de destino (public_html/nombre_sitio) en el nuevo servidor.
- Sube el archivo "prueba_endeavor.rar" y descomprímelo.
- Quedarán todos los archivos y carpetas del sitio web. 
- Crea una base de datos (MySQL) en el nuevo servidor.
- Después, crea un usuario y asócialo a la base de datos que se creó, dándole todos los permisos posibles.
- Entra a phpMyAdmin en el hosting de destino y pulsa en el nombre de la BD recién creada. 
- Luego, importa el archivo "prueba_endeavor.sql".
- Configura el archivo "wp-config.php" modificando las siguientes lineas:
  • define(‘DB_NAME’, ‘new_db’);
  • define(‘DB_USER’, ‘new_db_username’);
  • define(‘DB_PASSWORD’, ‘new_db_password’);
  • define(‘DB_HOST’, ‘localhost’);
