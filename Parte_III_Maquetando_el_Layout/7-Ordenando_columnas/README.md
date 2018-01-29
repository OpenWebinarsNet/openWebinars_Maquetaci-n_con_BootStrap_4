
# Reordenando los elementos de una fila

Por defecto,los elementos de una *row* se sitúan según el orden que hemos establecido al escribir la estructura de nuestro archivo HTML.

Sin embargo, mediante clases de BootStrap podemos cambiar el orden en que dichos elementos van a aparecer en nuestra pantalla.

Para ello utilizaremos la clase *.order-X* siendo X el orden en el que queremos situar dicho elemento dentro de nuestra fila.

Así por ejemplo:

```html

  <div class="row">

    <div class="col-md-4 order-3">
      Primer elemento. Posición Tercera
    </div>
    <div class="col-md-4 order-1">
      Segundo elemento. Posición Primera
    </div>
    <div class="col-md-4 order-2">
      Primer elemento. Posición Segunda
    </div>
  <div>

```
**Importante:** Debemos poner *order-X* a todos los elementos de la columna. Si no lo hacemos, aquellos que no lo tengan serán mostrados los primeros y en el orden establecido por defecto.

De igual manera, nos puede interesar únicamente reordenar a partir de cierto tipo de pantallas.Para eso tendremos en cuenta los breakpoints explicados en capítulos anteriores  y usaremos:

* order-sm-X
* order-md-X
* order-lg-X
* order-xl-X
