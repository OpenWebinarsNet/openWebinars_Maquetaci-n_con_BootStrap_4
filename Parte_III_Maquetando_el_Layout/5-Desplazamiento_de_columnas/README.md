
# Desplazamiento de columnas

Tal y como hemos visto en apartados anteriores podemos dar diferentes tamaños a los distintos componentes o columnas de una *row* o fila.

Adicionalmente podemos establecer no sólo el tamaño de la columna si no también la posición a partir de la cuál se va a posicionar.

Para conseguir eso debemos añadir la clase *offset-X* donde X es el número de columnas a la izquierda que desplazaremos el elemento que queremos posicionar.

Este desplazamiento puede ser también establecido de manera diferente para cada tamaño de pantalla:

* **offset-sm-X :** Para desplazamientos para pantallas entre 576px y 768px.
* **offset-md-X :** Para desplazamientos para pantallas entre 768px y 992px.
* **offset-lg-X :** Para desplazamientos para pantallas entre 992 y 1200px.
* **offset-xl-X :** Para desplazamientos para pantallas mayores de 1200px.

Por ejemplo:

```html

<div class="container-fluid">
  <div class="row">
    <div class="col-sm-4 offset-md-1 red"></div>
    <div class="col-sm-4 offset-sm-4 offset-md-2 blue"></div>
  </div>
</div>

```
En este ejemplo para pantallas mayores de 768px el primer div está desplazado una columna a la izquierda y ambos bloques se separan dos columnas mediante el uso de un desplazamiento de dos columnas en el segundo bloque.

Además para pantallas entre 576px y 768px no hay desplazamiento para el primer bloque y hay un desplazamiento de 4 columnas para el segundo bloque consiguiendo, de esta forma que ese bloque quede totalmente pegado a la derecha.

**IMPORTANTE:** En esta nueva versión de BooStrap 4 hay un cambio importante en el nombre de las clases para desplazar los elementos de la fila. En versiones anteriores esas clases de denominaban *col-yy-offset-X* donde yy son las siglas del tamaño de la pantalla.
