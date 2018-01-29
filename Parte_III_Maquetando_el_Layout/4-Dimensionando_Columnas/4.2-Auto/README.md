
# Columnas con tamaño auto

Es una de las novedades de BootStrap 4 que deriva directamente del uso de contenedor flex.

Usando elementos en los que no especifiquemos el número de columnas, el espacio que haya en la fila se va a distribuir de manera uniforme.

* **col :** Para todo tipo de pantallas
* **col-sm :** De pantallas pequeñas en adelante (>=576px)
* **col-md :** De pantallas medianas en adelante (>=768px)
* **col-lg :** De pantallas grande en adelante (>=992px)
* **col-xl :** Para pantallas de 1200px en adelante


Veamos el primer ejemplo:

```html

<div class="row">
    <div class="col red">
    </div>
    <div class="col black">
    </div>
</div>

```

En este caso en cualquier tipo de pantallas esos dos elementos se repartirán a igual manera el ancho del contenedor principal.

Debemos de tener cuidado porque en caso de que lo que contengan esas partes ocupe más de la mitad no se respetará esa proporción. Veamos este caso con un ejemplo:


```html

<div class="row">
    <div class="col red">
      <h1>PRIMERA PARTE</h1>
    </div>
    <div class="col black">
      <h1>SEGUNDA PARTE</h1>           
    </div>
</div>

```

Si queremos que es reparto equitativo  suceda para determinado de pantallas:

```html

<div class="row">
    <div class="col-md yellow"></div>
    <div class="col-md pink"></div>
    <div class="col-md yellow"></div>
    <div class="col-md pink"></div>
    <div class="col-md yellow"></div>
</div>

```
En este caso todo se divide en 5 partes para pantallas menores de 768px pero en cuanto la pantalla es más pequeña que eso, todos los elementos pasarán a ocupar todo el centro de la pantalla.

Este funcionamiento abre la puerta a *rows* (filas) que tengan más de 12 columnas, por ejemplo una fila con 14 componentes:

```html

<div class="row">
  <div class="col-md blue"></div>
  <div class="col-md pink"></div>
  <div class="col-md blue"></div>
  <div class="col-md pink"></div>
  <div class="col-md blue"></div>
  <div class="col-md pink"></div>
  <div class="col-md blue"></div>
  <div class="col-md pink"></div>
  <div class="col-md blue"></div>
  <div class="col-md pink"></div>
  <div class="col-md blue"></div>
  <div class="col-md pink"></div>
  <div class="col-md blue"></div>
  <div class="col-md pink"></div>
</div>

```

BootStrap 4 nos permite también ajustar el tamaño de las columnas al contenido de las mismas usando *col-{breakpoint}-auto*. Así por ejemplo:

```html
  <div class="row">
    <div class="col-md-auto">Anchura ajustada</div>
    <div class="col-md-auto">Al contenido</div>
    <div class="col-md-auto">De las celdas que contiene la columna</div>
  </div>
``

**IMPORTANTE:** Debemos tener mucho cuidado cuando mezclemos tamaños automáticos junto tamaños, definidos por el usuario porque cuanto no quepan las columnas (y puede que no sumen 12) pasarán a la siguiente fila y se repartirán el espacio de la siguiente fila.
