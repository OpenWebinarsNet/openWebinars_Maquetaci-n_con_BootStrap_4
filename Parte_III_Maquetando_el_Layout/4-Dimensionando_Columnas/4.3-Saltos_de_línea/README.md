
#Saltos de línea

Si mientras estamos construyendo nuestro grid y queremos que haya un salto de línea podemos forzarlo de la siguiente manera:

```html

  <div class="w-100"></div>

```

Con esa estructura aunque no hayamos ocupado las 12 columnas de nuestro grid podremos pasar a la siguiente fila. De esta manera:

```html

<div class="row">

  <!-- Ocupamos 5/12 de la fila -->
  <div class="col-md-3"></div>
  <div class="col-md-2"></div>

  <!-- Forzamos el salto de línea -->
  <div class="w-100"></div>

  <!-- Ocupamos otra vez 5/12 pero en una nueva línea -->
  <div class="col-md-3"></div>
  <div class="col-md-2"></div>


</div>

```

Si nos damos cuenta esto mismo se podría haber conseguido utilizando varias *rows* (filas). De esta manera

```html

<div class="row">

  <!-- Ocupamos 5/12 de la fila -->
  <div class="col-md-3"></div>
  <div class="col-md-2"></div>

</div>

<div class="row">

</div>

<div class="row">

  <!-- Ocupamos otra vez 5/12 pero en una nueva línea -->
  <div class="col-md-3"></div>
  <div class="col-md-2"></div>

</div>

```
De manera selectiva podemos establecer que ese cambio de línea se produzca en un determinado breakpoint de los establecidos por BootStrap 4.

Así por ejemplo:

```html


```
Para más información podemos ver [BootStrap4 Display Utilities](https://getbootstrap.com/docs/4.0/utilities/display/)
