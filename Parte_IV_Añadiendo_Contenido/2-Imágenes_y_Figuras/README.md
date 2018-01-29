# Imágenes y Figuras

Para aquellos que no tengan claro la diferencia entre imágenes y figuras podemos resumirlo de la siguiente manera:

* Una **imagen** es únicamente el elemento gráfico el cual hemos añadido mediante las etiquetas ***img*** o ***picture***.

```html

  <img src="ejemplo.png">

```
* Una **figura** (etiqueta ***figure***) es un conjunto compuesto de una imagen (etiqueta ***img***) y de un texto descriptivo sobre la imagen (etiqueta ***caption***). Esta etiqueta es una de las novedades en HTML5.Tradicionalmente es lo que se usa en *libros* para hacer posteriormente un índice de figuras.

```html

  <figure>
    <img src="ejemplo.png">
    <figcaption>Texto descriptivo de la imagen</figcation>
  </figure>

```

BootStrap 4, por supuesto, nos proporciona una serie de clases para tratar y dar estilos a este tipo de contenidos.

### Imágenes

En relación a las imágenes las clases de interés son:

* **img-fluid :** Que nos permite convertir una imagen en responsiva. Al añadir esa clase a una imagen ésta ocupará toda la anchura de su elemento padre manteniendo sus proporciones (aspect ratio).Si hemos utilizado la etiqueta *picture* debemos añadir esta clase a la *img* que contiene y no a *picture*.
* **img-thumbnail :** Para añadir un marco redondeado a la imagen. Para esto podríamos también usar las clases relativas a bordes que veremos posteriormente en el capítulo sobre utilidades.
* **rounded .** Si queremos que las esquinas sean redondeadas.

**IMPORTANTE :** En IE10 si la imagen es una imagen SVG no se respeta el aspect ratio.

### Figuras

En relación a las figuras las clases de interés para dar estilos con BootStrap 4 son:

* **figure :** Clase a añadir a la etiqueta *figure*.
* **figure-img :** Clase a añadir a la etiqueta *img* que contiene la figura.
* **figure-caption :** Clase añadir a la etiqueta *figcation* que contiene la figura. El texto se podrá adicionalmente alinear de distintas maneras usando *text-justify*, *text-left*, *text-right* o *text-center*.

**IMPORTANTE :** Si queremos que esto siga siendo responsivo debemos añadir *.img-fluid* a la imagen de la figura.
