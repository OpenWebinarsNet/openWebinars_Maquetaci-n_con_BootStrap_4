
# Márgenes y paddings en las columnas.

BootStrap 4 añade clases que nos van a permitir modificar los márgenes y los paddings de las columnas. Según la documentación oficial son las *Utilidades de espaciado*.


## Márgenes entre columnas

Para establecer los  márgenes entre las columnas usaremos la clas *m{lado}-{tamaño}* o si queremos distinguir según los distintos tamaños de pantalla:

* **m{lado}-sm-{tamaño}** Para pantallas entre 576px y 768px.
* **m{lado}-md-{tamaño}** Para pantallas entre 768px y 992px.
* **m{lado}-lg-{tamaño}** Para pantallas entre 992px y 1200px.
* **m{lado}-xl-{tamaño}** Para pantallas de más de 1200px.

Pudiendo ser lado:

* **t** para margen superior (top).
* **b** para margen inferior (bottom).
* **l** para margen izquierdo (left).
* **r** para margen derecho (right).
* **x** para los márgenes superior e inferior.
* **y** para los márgenes izquierdo y derecho.
* En blanco si es para todos los lados.

Y pudiendo ser tamaño de tamaño:

* **0 :** No hay margen
* **1 :** 0.25rem
* **2 :** 0.25rem
* **3 :** 1rem
* **4 :** 1.25rem
* **5 :** 3rem
* **auto :** Para clases que establecen una margen auto


## Centrado horizontal

Relacionado con el tema de los márgenes hay que destacar que BooStrap 4 introduce una nueva clase ***mx-auto*** que permite centrar horizontalmente un elemento dentro de su contenedor siempre que tenga una

## Paddings

La notación de las clases para establecer los paddings en las columnas es muy similar a la notación de las clases para establecer márgenes entre las columnas. Simplemente tenemos que cambiar la ***m*** por la ***p***
