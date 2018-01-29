
# Gutter

Por defecto BootStrap 4 introduce separación entre el contenido de las columnas mediante *paddings* y márgenes a derecha e izquierda. Es lo que se denomina *gutter*

Si ése no es el efecto que queremos en nuestra maquetación podemos evitarlo añadiendo al elemento que tenga la clase *row* la clase *no-gutters*.

Así de esta manera las columnas o elementos de la fila no tendrán ese padding con la posibilidad de que el contenido de la misma queden pegados.

Un ejemplo sería:

```html

<div class="container">
  <div class="row">
    <div class="col-md-6"><h3>Elemento con Gutter</h3></div>
    <div class="col-md-6"><h3>Elemento con Gutter</h3></div>
  </div>

  <div class="row no-gutters">
    <div class="col-md-6"><h3>Elemento sin gutter</h3></div>
    <div class="col-md-6"><h3>Segundo Elemento</h3></div>
  </div>

</div>


```
