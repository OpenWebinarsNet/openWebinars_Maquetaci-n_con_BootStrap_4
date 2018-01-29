
# Alineación en las filas

Como ya hemos descrito en apartados anteriores, BootStrap 4 utiliza contenedores flex. Precisamente utilizando las propiedades de estos elementos podremos fijar la alineación de los componentes de las *rows* o filas.

Podremos establecer:

* La alineación vertical de los elementos de la fila.
* La alineación horizontal de los elementos de la fila.

Tanto para establecer la alineación horizontal como la vertical deberemos añadir una nueva clase al contenedor *row* o fila.

## Alineación vertical

Si queremos alinear los distintos elementos que componen una fila de manera vertical podremos hacerlo añadiendo a la *row* fila una de estas tres clases:

* **align-items-start :** Los elementos  de la fila se alinearán verticalemente con el borde superior de la fila.

```html

 <div class="row align-items-start">
</div>

```

* **align-items-center :** Los elementos de la fila se alinearán centrados verticalmente.

```html

 <div class="row align-items-center">
</div>

```


* **align-items-end :** Los elementos de la fila se alinearán verticalemtne con el borde inferior de la fila.

```html

 <div class="row align-items-end">
</div>

```

## Alineación horizontal

Para fijar la alineación horizontal de los elementos en la *row* (fila) dispondremos de las siguientes clases:

* **justify-content-start :** Los elementos empezarán en la parte izquierda y ocuparán el tamaño horizontal establecido. Es la opción por defecto.

```html

 <div class="row justify-content-start">
</div>

```

* **justify-content-center :** Los elementos de la fila se centrarán horizontalmente.
* **justify-content-end :** Los elementos de la fila se alinearán al final (la derecha normalmente) de la fila.
* **justify-content-around :** El espacio restante se distribuirá de manera equitativa alrededor de los elementos empezando y acabando con espacios libres.
* **justify-content-between :** El espacio restante se distribuirá de manera equitativa entre los distintos elementos estando uno de ellos totalmente a la derecha y otro totalmente a la izquierda.

Con todas estas posibilidades y lo visto anteriormente es más que suficiente para casi cualquier Layout pero existen más posibilidades que podremos descubrir en la documentación oficial.
