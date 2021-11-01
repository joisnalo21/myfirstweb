# ¿Qué es JQuery?
JQuery es una librería de JavaScript (JavaScript es un lenguaje de
 programación muy usado en desarrollo web). Esta librería de código 
 abierto, simplifica la tarea de programar en JavaScript y permite 
 agregar interactividad a un sitio web sin tener conocimientos del 
 lenguaje.
 Basados en esta librería, **existe una infinita cantidad de plugins 
 (gratis y pagos) creados por desarrolladores de todo el mundo**. 
Estos plugins resuelven situaciones concretas dentro del maquetado 
de un sitio, por ejemplo: un menú responsive, una galería de fotos,
un carrousel de imágenes, un slide, un header que cambia de tamaño,
el deslizamiento del scroll al hacer clic en un botón (anclas HTML),
la transición entre páginas y miles de efectos más.

## ¿Cómo se instala un plugin?
Luego de realizar la búsqueda y comparar los diferentes demos, 
elegimos el plugin que queremos instalar en nuestro sitio y descargamos
 los archivos que lo componen. Dependiendo de la complejidad, algunos
plugins están compuestos por un sólo archivo .js como por ejemplo el
deslizamiento del scroll y otros se componen de un grupo de archivos
 relacionados entre sí: html, css, js e imágenes con es el caso de una 
 galería de fotos.
Cada plugin tiene sus instrucciones de instalación propias, escritas por 
su autor, pero vamos enumerar los puntos que hay que tener en cuenta 
durante el proceso:
## Librería JQuery
Todos los plugins de JQuery necesitan la librería de JQuery para funcionar. 
La librería es un archivo .js que se puede descargar desde el sitio oficial:
https://jquery.com/ colocar en una carpeta js y luego vincular con una etiqueta 
script, por ejemplo:

````
<html>	
    <script src="js/jquery-3.2.1.min.js"></script> 
</html>
````

Ese vínculo conviene colocarlo dentro del body y hacia el final del HTML para 
no demorar la carga de los contenidos. Si descargamos el archivo y lo vinculamos
 de esa manera, debemos subir el archivo a nuestro hosting.

Otra forma de vincular la librería es utilizando el servidor de Google. De esta 
manera no necesitamos descargarla ni subirla a nuestro servidor. En ese caso, el
 código es el mismo pero con ruta absoluta:

 ````
<html>	
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.2.1/jquery.min.js"></script>
</html>
````
La página donde Google ofrece los vínculos a diferentes recursos es la siguiente: https://developers.google.com/speed/libraries/#jquery

Los archivos .min son archivos que están optimizados (con el código comprimido)
 y no son editables, se usan en producción cuando se considera que no es 
 necesario hacerle modificaciones. La ventaja es que son más livianos y por lo
tanto cargan más rápido.