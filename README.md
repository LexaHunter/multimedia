
# Contenido multimedia

En esta práctima hemos aplicado modificaciones sobre contenido multimedia: imágenes, audio y vídeo. Además de trabajar para crear un banner publicitario, e integrar todo esto en el escaparate virtual creado anteriormente.


## Secciones y modificaciones

### 1. Audio
Modificaciones con WavePad al clip [Tomorrow](https://www.bensound.com/royalty-free-music/track/tomorrow)
. Lo primero en los efectos ha sido extreaer un minuto del audio, y pasarle un fundido de entrada y de salida para que comience y finalie de forma suave. Desde la pestaña de "Efectos" -> "FX especiales" he aplicado:
+ **Wah-Wah**: resonancia 80%, profundidad 100%, Frecuencia central 500Hz, Frecuencia Wah 5.000Hz
+ **Telefono**
+ **Cambio de velocidad y altura de sonido**: Duracion resultante 60 seg, Semitonos -3.206, Velocidad-altura 83%.

### 2. Video
La edición de vídeo está realizada con Windows Movie Maker. La primera modificación ha sido aumentar la velocidad del vídeo (Edit - speed: 2x), para hacer un corte de 10 segundos que abarcase una escena completa de la tierra de polo norte a polo sur. Después de esto, he cortado los 10 segundos que más me gustaban, y he aplicado los filtros **Hue - cycle entire color spectrum** y **Fade out black** para que el vídeo termine más suavemente. Además, he incluido una imágen de la tierra al inicio con efecto **Crossfade**, y un efecto de transición entre imágen y vídeo **Pixelado**.

### 3. Imágenes
En todas las imágenes expuestas, al hacer click en la miniatura, te dirige a una página nueva con la imagen en tamaño original. Además, todas llevan la marca de agua abajo a la derecha, generada coon una capa de texto blanca o negra y un 60% de transparencia. Los retoques están realizados con photoshop.

+ **Desierto y Desierto1**: imagen en la que se borra a una persona del centro de la foto. Realizado con el tampón de clonar.

+ **Sequía1 y Sequía1_2**: imágenes de un puente. A la primera se le ha aplicad un efecto de color en el cual, con manejo de capas, ciertas zonas se han dejado en blanco y negro y las zonas de vegetación en colores otoñales. En la segunda he elegido crear un reflejo de agua: a una capa copiada, dada la vuelta y un poco aplanada se le aplica un filtro de agua, un desenfoque gaussiano muy suave y un degradado que aclare la parte más "cercana" a la cámara, dando el efecto de profundidad.

+ **Sequía 2 y Sequía2_2**: a la primera imágen se le aplican dos retoques de color, la parte del cielo más azulada y la del suelo más verde y con un aspecto más de primavera (de nuevo, trabajo por capas). Sobre esta imágen he aplicado un segundo retoque, desaturando las nubes y aplicando un filtro de lluvia: sobre una capa nueva con fondo negro se apica un filtro "ruido" y después un desenfoque de movimiento en oblicuo, simulando la lluvia. Esta capa se pone en modo trama, y jugando con el brillo y el contraste, y poniendo un poco de claridad cercana al suelo, se genera el efecto lluvia.

### 4. Banner
Banner creado usando la herramienta Google Web Designer y con la ayuda de varios [tutoriales](https://www.youtube.com/results?search_query=google+web+designer+banner). 
La idea ha sido, a partir de un gif con un dibujo de la tierra goteando, dejar caer una gota con el texto "Save the Water" dentro. La imagen de esta gota empieza fuera del panel y desciente a los 5 segundos. Al texto se le añade un componente de interacción "área de pulsación", para agregar un evento. Por otra parte, en una página nueva añado la imagen de una hucha y el texto "Dona!, con la intención de que esta redirija a la página de donación de nuestra web.
Desde la priera página, para añadir un **evento**, vamos al panel derecho -> Eventos -> + -> Objetivo : página de origen -> Evento : área de pulsación : toque o click -> Acción : cubierta de página : ir a la página -> Receptor : pagedeck -> Identificador de página : nombre de la página de destino. Esto nos llevará a la segunda página.
La intención inicial sobre la segunda página era llevarla a un enlace de la web, pero al no conseguirlo he añadido un evento de la misma forma descrita anteriormente, para que al clickear vuelva a la primera página del banner.

Al integrar el banner me he encontrado con ciertos problemas, así que la funcionalidad completa puedes verla aquí: [Banner](https://lexahunter.github.io/multimedia/banner/banner/banner.html) (recordemos antes desabilitar cualquier extensi´n u opción de bloqueo cono AddBlock).

En cuanto a la **integración**, la primera opción era posicionar el banner en la parte inferior izquiera de la ventana, y que se fuese moviendo al hacer scroll quedándose siempre pegada al bottom. Después de varios intentos y búsquedas, aunque había conseguido que quedara pegado y moviéndose con a la vez que subimos o bajamos, invadía demasiado la página y no he averiguado cómo insetar una pestaña de cierre que quedase bien integrada y con el banner completo (se me cortaba). Así que, como segunda opción, he insertado el banner en un pop up que se muestra al abrir la página a partir de este [tutorial](http://soyfrontend.com/crear-ventana-modal-con-solo-css/). Con esto, al entrar en la página, se muestra el banner con la opción de cierre, pero con esta técnica no interactúan la primera y la segunda página del banner. 

### 5. Modificaciones
En cuanto a las modificaiones de la interfaz, ya que el escape virtual de la práctica anterior estaba basado en venta de pinturas y fotografía, las nuevas especificaciones se adaptaban muy bien. En el header, he modificado el logo, los enlaces, y el icono que antes correspondía a carrito ahora es una hucha en la que se podrán hacer donaciones. Por otra parte, lo que anteriormente era el carrusel ahora es el vídeo y el sonido, y la parte de fotografía y pintura que incluía cuatro imágenes por cada división ahora son las imágenes que nos pide la práctica: priemero la original, y después una o dos retocadas. Debajo de éstas están las opciones de abrir la imágen en los distintos formados pedidos, al igual que si se hace click en la miniatura de la imágen ésta se abrirá (se abrirán siempre en una nueva pestaña). Por último, he cambiado algunos de los enlaces del footer y puesto una imágen de fondo acorde con el tema de la página.


#### Autora

* **Paz Rubio Rubio** - [Github](https://github.com/LexaHunter)

[Readme - markdown](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
