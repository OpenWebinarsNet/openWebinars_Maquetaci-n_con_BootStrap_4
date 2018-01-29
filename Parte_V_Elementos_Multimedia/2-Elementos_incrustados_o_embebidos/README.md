
# Elementos incrustados o embebidos

Los elementos embebidos son algo común en todas las webs , vídeos de youtube, reproductores de canciones de spotify, presentaciones de slideshare están embebidas o incrustadas por todos los sitios.

Desde el punto de vista más técnico nos estamos refiriendo a las etiquetas ***iframe***,***embed***,***video*** y ***object***

Para hacer estas etiquetas responsivas debemos añadir la clase ***embed-responsive*** a un elemento que la contenga y la clase ***embed-responsive-item*** a la etiqueta en cuestión. Algo así:

```html

  <div class="embed-responsive">
      <iframe src="..." class="embed-responsive-item"></iframe>
  </div>
```

Adicionalmente podemos modificar las proporciones elementos (su *aspect ratio*) añadiendo al elemento padre clases que lo modificarán:

* ***embed-responsive-21by9 :*** *Aspect Ratio 21x9*
* ***embed-responsive-16by9 :*** *Aspect Ratio 16x9*
* ***embed-responsive-4by3 :*** *Aspect Ratio 4x3*
* ***embed-responsive-1by1 :*** *Aspect Ratio 1x1*
