
# Instalación de BootStrap 4

Para instalar BootStrap 4 podemos optar por dos opciones:

* Usar el los enlaces que nos proporcionan en la documentación:

El primero de ellos es el CSS de la librería

```html

<!-- Bootstrap CSS -->
<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0-beta.2/css/bootstrap.min.css" integrity="sha384-PsH8R72JQ3SOdhVi3uxftmaW6Vc51MKb0q5P2rRUpPvrszuE4W1povHYgTpBfshb" crossorigin="anonymous">

```

Y posteriormente si vamos a usar componentes, muchos de los cuáles no son elementos estáticos y van a requerir scripts para definir su comportamiento

```html

<!-- Optional JavaScript -->
<!-- jQuery first, then Popper.js, then Bootstrap JS -->

<script src="https://code.jquery.com/jquery-3.2.1.slim.min.js" integrity="sha384-KJ3o2DKtIkvYIK3UENzmM7KCkRr/rE9/Qpg6aAZGJwFDMVNA/GpGFF93hXpG5KkN" crossorigin="anonymous"></script>

<script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.12.3/umd/popper.min.js" integrity="sha384-vFJXuSJphROIrBnz7yo7oB41mKfc8JzQZiCq4NCceLEaO4IHwicKwpJf9c9IpFgh" crossorigin="anonymous"></script>

<script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0-beta.2/js/bootstrap.min.js" integrity="sha384-alpBpkh1PFOepccYVYDB4do5UnbKysX5WZXm3XxPqe5iKTfUKjNkCk9SaVuEZflJ" crossorigin="anonymous"></script>

```

Los dos primeros scripts son para referenciar las librerías [jQuery](https://jquery.com/) y [Popper](https://popper.js.org/) de las que depende BootStrap.

* Descargar los ficheros necesarios para no tener que pedirlos cada vez que se muestre nuestra página.

Esos ficheros podemos descargarlos de [aquí](https://github.com/twbs/bootstrap/releases/download/v4.0.0-beta.2/bootstrap-4.0.0-beta.2-dist.zip) y en vez de usar URLs podremos referenciar los ficheros localmente.


En cualquier caso para este curso se proporciona un fichero base HTML (template.html) con todo lo necesario para poder practicar.


**IMPORTANTE:** Para la realización de este curso se ha usado la versión beta de BootStrap 4. Conforme los desarrolladores vayan publicando nuevas versiones habría que actualizar los enlaces.
