# Instalación y Configuración

+ [Requerimientos](#reque)
+ [Instalación](#instala)
+ [Configuración del Servidor](#servidor)
+ [Configuración Básica](#basica)
+ [Ambientes](#ambientes)
+ [URL's Limpias](#url)

<h2 id = 'reque'>Requerimientos</h2>

+ Apache, nginx, cualquier navegador compatible.
+ Laravel toma ventaja de las poderosas características que tiene disponible PHP 5.3. Consecuente, PHP 5.3 es requerido.
+ Laravel utiliza la [librería FileInfo](http://www.php.net/manual/en/intro.fileinfo.php) para detectar los archivos tipo MIME(Internet Media Type). Esto viene ya viene incluido con PHP 5.3. Sin embargo, usuarios de windows tal vez necesiten agregar una linea al php.ini antes de que el Modulo FileInfo este activado. Para mas información por favor mirar los [detalles de instalación y configuración de PHP.net](http://php.net/manual/en/fileinfo.installation.php).
+ Laravel utiliza la [librería Mcrypt](http://php.net/manual/en/book.mcrypt.php) para encriptación y generador hash. Si no puede encontrar Mcrypt en el resultado de phpinfo(), entonces revisar el sitio del vendedor de su instalación LAMP o revisar los [detalles de la instalación y configuración de PHP.net](http://php.net/manual/en/book.mcrypt.php).

<h2 id = 'instala'>Instalación</h2>

1. [Descargar Laravel](http://laravel.com/download).
2. Extrae el contenido del archivo comprimido y cárgalos a tu servidor web.
3. Colocar un valor aleatorio de un carácter cadena de 32 bits a la opción **key** del **config/application.php**.
4. Verificar que el directorio `storage/views` sea modificable.
5. Navega a tu aplicación en un navegador web.

Si todo sale bien veras un hermosa imagen de inicio de Laravel. Prepárate, hay mas para aprender.

<h2 id = 'servidor'>Configuración del Servidor</h2>



<h2 id = 'basica'>Configuración Básica</h2>

<h2 id = 'ambientes'>Ambientes</h2>

<h2 id = 'url'>URL's Limpias</h2>