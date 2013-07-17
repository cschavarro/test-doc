# DOCUMENTACIÓN DE LARAVEL

+ [Concepto Básico](#concepto)
+ [¿Quien disfrutara de Laravel?](#quien)
+ [¿Que hace diferente a Laravel?](#diferente)
+ [La Estructura de Aplicación (Application)](#estruct)
+ [La Comunidad Laravel](#comunidad)
+ [Información sobre la Licencia](#licencia)

<h2 id = 'concepto'>Concepto Básico</h2>

Bienvenido a la documentación de Laravel. Estas secciones fueron diseñadas con el objetivo de servir como una guía de inicio a Laravel y como artículos de referencia. Aunque puedes ir a cualquier sección que necesites y empezar a aprender, te recomendamos que leas la documentación en orden, así nos permitirá establecer conceptos que serán utilizados en secciones posteriores.

<h2 id = 'quien'>¿Quien disfrutará de Laravel?</h2>

Laravel es un poderoso framework que enfatiza en la flexibilidad y expresividad. Usuarios nuevos a Laravel disfrutaran de la misma facilidad al desarrollar la cual se puede encontrar en los mas populares y livianos frameworks PHP. Usuarios con mas experiencia apreciarán la oportunidad de modular su código en formas que otros frameworks no permiten. La flexibilidad de Laravel le permitirá a tu organización actualizar y moldear las aplicaciones en cualquier momento tanto sea necesario, y la expresividad le permitirá a usted y su equipo a crear código que al mismo tiempo sea conciso y fácil de leer.

<h2 id = 'diferente'>¿Que hace diferente a Laravel?</h2>

Existen varias maneras que hacen a Laravel diferenciarse de otros Frameworks. Aquí unos pequeños puntos que hacen ejemplo de esto:

+ __Bundles__ son el sistema modular de empaquetado que usa Laravel. [El Repositorio de Bundles de Laravel](http://bundles.laravel.com/) hasta ahora contiene un buen número de características que se pueden añadir fácilmente a tu aplicación. Puedes descargar ya sea el repositorio  a tu carpeta de repositorios (Bundles) o puedes usar la herramienta de linea de comandos "Artisian" e instalarlos automáticamente.

+ __El Eloquent ORM__ es la implementación mas avanzada de PHP ActiveRecorded disponible. Con la capacidad de fácilmente aplicar restricciones a las relaciones y a las eager-loading anidadas podras tener total control sobre tus datos con todas las conveniencias del ActiveRecord. Eloquent soporta de forma nativa todos los métodos de Fluent, el constructor de consulta de Laravel.

+ __Logica de Aplicación__ se puede implementar dentro de la aplicación ya sea usando controladores (los cuales muchos desarrolladores web ya están familiarizados) o directamente con declaraciones de Routes (rutas) usando sintaxis similar a del Framework Sinatra. Laravel es diseñado con la filosofía de ofrecerle al diseñador la flexibilidad que necesita para crear todo, desde sitios pequeños hasta grandes aplicaciones empresariales.

+ __Enrutamiento Invertido__ permite crear enlaces a rutas nombradas. Al crear un enlace solo tiene solamente una como nombre el mismo de la Ruta y Laravel automáticamente insertara la URI correcta. Esto te permite cambiar las rutas en un tiempo posterior y Laravel actualizará todos los enlaces relevantes en todo el sito web.

+ __Controladores Restful__ son una forma opcional par separar la lógica de peticiones GET y POST. En un ejemplo de inicio de sesión la acción get\_login() de su controlador presentará / cargará el formulario y la acción post\_login() aceptará el formulario enviado,  lo validara y ya sea redirigir al formulario de inicio de sesión con un mensaje de error o redirigir al usuario a su pagina de inicio.

+ __Clase de Auto-carga__ te abstiene de mantener una auto-cargador de configuración y de cargar componentes innecesarios que no se van a utilizar. ¿Quieres utilizar un modelo o una librería? No te molestes en cargarla, solo úsala. Laravel hará es resto del trabajo.

+ __Compositores de Vistas__son bloques de código que se pueden ejecutar cuando se carga una vista. Un buen ejemplo de esto sería la vista del panel de navegación lateral de un blog que contiene una lista de entradas aleatorias. Tu compositor contendrá la lógica para cargar todas las entradas, para que así solo tengas que cargar la vista y todo quede listo para usarlo. Esto le evita tener que asegurarse de que sus controladores carguen el un montón de datos de los modelos para las vistas que no están relacionadas con el contenido la pagina de ese método.

+ __El contenedor IoC (Inversión del Control o Inversion of Control)__ ofrece un método para generar nuevos objetos y, opcionalmente, crear instancias y referencias a un objeto unitario. IoC implica	 que raramente se tendrá que adicionar librerías externas al arranque. También implica que usted puede acceder a estos objetos desde cualquier lugar en el código sin tener que lidiar con una estructura monolítica inflexible.
+ __Migraciones__
+ __Unidad de Pruebas__
+ __Paginado Automático__