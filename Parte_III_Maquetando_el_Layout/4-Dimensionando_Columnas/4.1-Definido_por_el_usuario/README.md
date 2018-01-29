
# Tamaño de las columnas establecido por el usuario


En apartados anteriores vimos cuál era la estructura general de una página con BootStrap 4,vimos también cuáles eran los breakpoint establecidos y que, en principio, cada *row* puede contener hasta 12 columnas.

En este apartado vamos a ver como nosotros podemos establecer el tamaño de cada uno de los componentes de dicha *row* o filas y que además, podemos establecer distintos tamaños dependiendo del tamaño de nuestra pantallas.

Si queremos dar tamaño a cada de los componentes usaremos las clases vistas previamente, de esta manera :

* **col-X**: hará que ese contendor X/12 columnas en pantallas extra pequeñas.

```html
  <!-- col-6 ocupará justo la mitad en pantallas extra pequeñas -->
  <div class="col-6">
  </div>
```
* **col-sm-X**: hará que ese contendor X/12 columnas en pantallas pequeñas.

```html
  <!-- col-sm-4 ocupará un tercio de la pantalla en pantallas pequeñas -->
  <div class="col-sm-4">
  </div>
```

Y así sucesivamente para *col-md-X* para pantallas medianas, *col-lg-X* para pantalla grandes y *col-xl-X* para pantallas extragrandes.

Una cosa importante que hay que tener en cuenta es que si establecemos un tamaño para un cierto tamaño de pantallas ese tamaño se va a mantener para pantallas de mayor tamaño pero para pantallas menores ese div ocupará toda la pantalla, es decir si tenemos:

```html

  <div class="col-md-6">
  </div>

```
Este div ocupará la mitad de la pantalla para pantallas de 768px (recordar los breakpoints) o superiores pero para tamaño menores ocupará todo el ancho de la fila que lo contiene.

Podemos también fijar a la vez anchos diferentes para distintos tipos de tamaños de pantallas. Para ello añadiremos varias clases a un mismo elemento, por ejemplo:

```html

  <div class="col-sm-6 col-md-4 col-xl-3">
  </div>

```
En este caso ese div:

* Ocupará toda la fila para pantallas extrapequeñas (<576px)
* Ocupará la mitad de la fila para pantallas en 576px y 768px
* Ocupará un tercio de la fila para pantallas entre 768px y 992px
* Ocupará un cuarto para pantallas mayores de 992px

También es importante recordar que si, en un *row* nos pasamos de 12 columnas ese elemento que provoca que nos pasemos de las 12 columnas *"pasará"* debajo de los elementos de la fila actual ocupando el tamaño establecido.

Así por ejemplo si tenemos la siguiente estructura:

```html
  <div class="row">
    <div class="col-md-6">
    </div>
    <div class="col-md-4">
    </div>
    <div class="col-md-4">
    </div>
  </div>
```

El tercer div irá abajo ya que 6+4+4 = 14 que es mayor que 12.
