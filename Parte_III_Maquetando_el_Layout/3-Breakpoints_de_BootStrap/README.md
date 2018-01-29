# BreakPoints en Bootstrap 4

### ¿Qué es un breakpoint?

En el mundo del diseño responsivo un ** breakpoint ** es un tamaño de pantalla (en pixels) donde se produce un cambio en la disposición de los elementos que conforman nuestra página web.

Existen multitud de tipos de dispositivos, multitud de pantallas, pantallas que giran etc. Por lo tanto la elección de los distintos breakpoints no es algo trivial. Sin embargo, tenemos la suerte de que los muchachos de [Twitter](http://www.twiiter.com), usando su experiencia y los datos que sus millones de usuarios les proporcionan, has decidido que la elección más adecuada son 4 breakpoints:

* En ** 576px **
* En ** 768px **
* En ** 992px **
* En ** 1200px **

Teniendo en cuenta estos 4 breakpoints podemos diferenciar entre 5 tipos de pantallas

* ** Pantallas extra pequeñas: ** Entre 0 y 576px
* ** Pantallas pequeñas: ** Entre 576px y 768px
* ** Pantallas medianas: ** Entre 768px y 992px
* ** Pantallas grandes: ** Entre 993px y 1200px
* ** Pantallas extra-grandes: ** A partir de 1200px


Juntando todo nos queda la siguiente tabla:

|                        | Extra pequeñas | Pequeñas | Medianas | Grandes | Extra Grandes |
| ---------------------- | :------------: | :------: | -------- | ------- | ------------- |
| Anchura máxima         |                |          |          |         |               |
| Prefijo de la clase    | .col-          | .col-sm- | .col-md- | .col-lg-| .col-xl-      |
| Número de columnas     | 12                                                             |
| Anchura del Gutter     | 30px (1px a cada lado de cada columna)                         |
| Anidar                 | Sí                                                             |
| Reordenar columnas     | Sí                                                             |  

De ** especial importancia ** son los prefijos CSS de las clases ** .col-* ** que son los que nos van a permitir establecer la anchura de los diferentes elementos que compongan nuestro layout. En definitiva son esas clases las que me proporciona BootStrap 4 para poder maquetar.


En el próximo apartado veremos cómo hacerlo.
