
# Contenedores en BootStrap


### ¿Qué es un contenedor?

Un contenedor es el "padre" de todos los elementos de nuestra página web. Es una etiqueta que. como regla general, va a contener todas las otras etiquetas del contenido de nuestra página.

### ¿Qué tipos de contenedores nos ofrece BootStrap?

BootStrap 4 nos ofrece dos tipos de contenedores:

* **container** : Ocupará diferentes anchos dependiendo del tamaño de la pantalla. Puede ocupar todas la pantalla o dejar unos márgenes a izquierda a derecha aunque, en este caso, siempre estará centrado.

```html
<body>

<div class="container">

</div>

</body>
```

* **container-fluid**: Ocupará todo el ancho (100%) de lo que podemos ver en el navegador.

```html
<body>

  <div class="container-fluid">

  </div>

</body>
```

**IMPORTANTE:** Aunque los contenedores se pueden anidar unos dentro de otros son pocas las páginas que son tan complejas para necesitar contenedores anidados.
