# Tablas con BootStrap 4

Mediante el uso de clases BootStrap 4 podemos dar distintos estilos a las tablas y hacerlas responsivas.

Estas clases relacionadas con tablas son muchas y en este apartado únicamente vamos a ver las más destacadas. Para más información os invito a visitar la documentación

### Haciendo que la tabla sea tabla Bootstrap

Simplemente debemos añadir la clase ***table*** y adicionalmente la clase ***table-dark*** si queremos que se inviertan los colores de fondo y de letra.

```html

  <table class="table">
      .....      
  </table>

```

### Clases para la cabecera de las tablas

Para dar estilos a las cabecera de las tablas tenemos que las clases ***thead-light*** o ***thead-dark***  a la etiquetas de las filas (*tr*) o a las etiquetas (*thead*).

```html

  <thead class="thead-light">
      <tr>
        <th>...</th>
        ......
      </tr>
  </thead>
```

**IMPORTANTE :** Este estilo sólo se aplica a la etiqueta *th* (celdas de cabecera).

### Alternado colores

Si queremos que las filas de las tablas tengan colores alternativos para poder distinguirlas mejor debemos añadir la clase ***table-striped*** a la etiqueta *table*. Esto funcionará también para tablas oscuras (clase *table-dark*).

```html

  <table class="table table-striped">
      .....      
  </table>

```

### Destacar

Si queremos que conforme pase el puntero de ratón por encima de una fila (que no sea la cabecera) esa fila de destaque cambiando ligeramente de color debo añadir las clase ***table-hover*** a las etiqueta *table*.

```html

  <table class="table table-hover">
      .....      
  </table>

```

### Bordes de las tablas

Por defecto en BootStrap 4 las tablas únicamente  muestran unos ligeros bordes inferiores en las filas para separar estas. Si, por el contrario, queremos que todas las celdas muestren los 4 bordes (inferior,superior, derecha e izquierda) debemos añadir la clase ***table-bordered*** a la etiqueta *tabla*.


```html

  <table class="table table-bordered">
      .....      
  </table>

```

### Haciendo las tablas responsivas

Hasta ahora únicamente hemos visto como BootStrap 4 da estilos a las tablas pero, como ya habrá quedado patente durante todo lo que llevamos de curso, la verdadera potencia de esta librería reside en la facilidad que nos da para hacer las páginas responsivas.

Existen distintas técnicas para hacer las tablas responsivas pero los desarrolladores de BootStrap 4 han optado porque aparezca un scroll horizontal cuando sea necesario.

Para conseguir esto debemos insertar nuestra tabla dentro un div con las clase BootStrap ***table-responsive***

```html
  <div class="table-responsive">
    <table class="table table-bordered">
        .....      
    </table>
  </div>
```
También puedo fijar el breakpoint a partir de la cual quiero que la tabla sea responsiva. En esos casos usaré:

* ***table-responsive-sm***
* ***table-responsive-md***
* ***table-responsive-lg***
* ***table-responsive-xl***
