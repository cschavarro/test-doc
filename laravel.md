# DOCUMENTACIÓN DE LARAVEL

+ [Concepto Básico](#concepto)
+ [¿Quien disfrutara de Laravel?](#quien)
+ [¿Que hace diferente a Laravel?](#diferente)
+ [La Estructura de Aplicación ](#estruct)
+ [La Comunidad Laravel](#comunidad)
+ [Información sobre la Licencia ](#licencia)

<h2 id = 'concepto'>Concepto Básico</h2>

Bienvenido a la documentación de Laravel. Esta secciones fueron diseñadas con el objetivo de servir como guía de inicio a Laravel al igual que un artículo de referencia. Aunque se puede saltar a cualquier sección que necesite y empezar a aprender, te recomendamos que leas la documentación en orden, así nos permitirá establecer conceptos que serán utilizados en secciones posteriores.

<h2 id = 'quien'>¿Quien disfrutará de Laravel?</h2>

Laravel es un poderoso framework que enfatiza en la flexibilidad y expresividad. Los usuarios nuevos en Laravel van a disfrutar de la misma facilidad para desarrollar, la cual se tiene con los frameworks PHP mas populares y livianos. Los usuarios con mas experiencia apreciarán la oportunidad de modular su código en formas que no permiten otros frameworks. La flexibilidad de Laravel permitirá a su organización actualizar y moldear las aplicaciones en cualquier momento en cuanto sea necesario, de la misma manera la expresividad le permitirá a usted y su equipo crear un código que al mismo tiempo sea conciso y fácil de leer.

<h2 id = 'diferente'>¿Que hace diferente a Laravel?</h2>

Existen varias formas en las que Laravel se diferencia de otros Frameworks. Aquí unos pequeños puntos que hacen ejemplo de esto:

+ __Bundles__ son el sistema modular de empaquetado que usa Laravel. [El Repositorio de Bundles de Laravel](http://bundles.laravel.com/) hasta la fecha contiene una extensa cantidad de características que se pueden agregar fácilmente a su aplicación. Estas se pueden descargar ya sea del repositorio a tu carpeta de repositorios (Carpeta Bundles) o puedes usar la herramienta de linea de comandos "Artisian" e instalarlos automáticamente.

+ __El Eloquent ORM__ es la implementación disponible mas avanzada del PHP ActiveRecorded. Con la capacidad de fácilmente aplicar restricciones a relaciones y a eager-loading anidadas tendrá total control sobre sus datos con toda la conveniencia del ActiveRecord. Eloquent soporta de forma nativa todos los métodos de Fluent, el constructor de consultas de Laravel.

+ __Lógica de Aplicación__ puede ser implementada dentro de la aplicación ya sea usando controladores (con lo cual muchos desarrolladores web ya están familiarizados) o directamente con declaraciones de Routes (rutas) con sintaxis similar a del Framework Sinatra. Laravel esta diseñado con la filosofía de ofrecer al diseñador la flexibilidad que necesita para crear todo, desde sitios pequeños hasta grandes aplicaciones empresariales.

+ __Direccionamiento Invertido__ permite crear enlaces a rutas nombradas. Al crear enlaces solo se tiene que usar el nombre de la Ruta y Laravel automáticamente insertara la URI correcta. Esto permite cambiar las rutas después de un tiempo y Laravel actualizará todos los enlaces relevantes en todo el sito web.

+ __Controladores Restful__ son la forma opcional para separar la lógica de las peticiones GET y POST. En un ejemplo de inicio de sesión la acción get\_login() de su controlador cargará el formulario, y la acción post\_login() aceptará el formulario enviado,  lo validara y ya sea redirigir al formulario de inicio de sesión con un mensaje de error o redirigir al usuario a su pagina de inicio.

+ __Clase de Auto-carga__ abstiene de mantener una configuración de carga automática, al igual que tener que cargar componentes innecesarios que no va a ser utilizados. ¿Quieres utilizar un modelo o una librería? No te molestes en cargarla, solo úsala. Laravel hará es resto del trabajo.

+ __Compositores de Vistas__son bloques de código que se pueden ejecutar cuando se carga una vista. Un buen ejemplo de esto sería la vista del panel de navegación lateral de un blog que contiene una lista de entradas aleatorias. Tu compositor contendrá la lógica para cargar todas las entradas, para que así solo tengas que cargar la vista y todo quede listo para usarlo. Esto le evita tener que asegurarse de que sus controladores carguen el un montón de datos de los modelos para las vistas que no están relacionadas con el contenido la pagina de ese método.

+ __El contenedor IoC (Inversión del Control o Inversion of Control)__ ofrece un método para generar nuevos objetos y, opcionalmente, crear instancias y referencias a un objeto unitario. IoC implica	 que raramente se tendrá que adicionar librerías externas al arranque. También implica que usted puede acceder a estos objetos desde cualquier lugar en el código sin tener que lidiar con una estructura monolítica inflexible.

+ __Migraciones__ sirven como control de versiones a los esquemas de la base de datos y están directamente integradas en Laravel. Puede generar al igual que ejecutar las migraciones usando la herramienta de linea de comandos "Artisan". En el momento que otro miembro realice cambios a los esquemas usted puede actualizar su copia desde el repositorio y ejecutar las migraciones. Y ahora también tu estas actualizado!.

+ __Unidad de Pruebas__ es una parte importante de Laravel. El propio Laravel ejecuta cientos de pruebas con el objetivo de procurar que nuevos cambios (actualizaciones)  no rompan algo de manera inesperada. Esta es una de las razones por la que ampliamente se considera a Laravel por tener uno de los versiones mas estables de la industria. Laravel también te permite hacer fácilmente unidades d prueba para tu propio código. Puedes ejecutar pruebas utilizando la herramienta de linea de comandos "Artisan".

+ __Paginado Automático__ previene que la lógica de su aplicación se sature de una gran cantidad de configuraciones de paginado. En vez de obtener la pagina actual,  tener que contar en número de registros obtenidos de la BD,  y seleccionar la información usando un LIMIT/OFFSET, puede invocar a "paginate" y decirle a Laravel donde se deben colocar los enlaces de paginado en la vista. Laravel automáticamente hará el resto. El sistema de paginado de Laravel fue diseñado para ser fácil de implementar y modificar.  También es importante tener en cuenta que aunque Laravel maneja el paginado de forma automática no implica que no se pueda invocar o configurar estos sistemas de forma manual, esto es si usted lo prefiere.

Estos son solo algunos puntos que demuestra como Laravel se diferencia de otros Frameworks PHP. Todas estas características  y muchas otras mas se irán explicando a medida que se avance en la documentación.

<h2 id = 'estruct'>La Estructura de Aplicación</h2>

