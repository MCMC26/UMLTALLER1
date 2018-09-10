# UMLTALLER1

![uml_taller1 - pagina 2](https://user-images.githubusercontent.com/42015388/45259922-27477800-b39e-11e8-989e-4f30f7467b4b.jpeg)

## MAIN
Esta clase llama la clase ejecutable logica, aqui se define el la resolucion y los metodos prinplales de 
PApplet (API de processing)
#### METODOS
* settings:void

* setup:void</p>

* draw:void</p>

* mousePressed:void</p>

* mouseReleassed:void</p>

* mouseDragged:void</p>

##### ATRIBUTOS
- log:Logica </p>
Esta variable se utiliza para llamar las diferentes interacciones de la clase logica y los diferentes objetos que se involucran </p>


## LOGICA

#### METODOS
* pintar:void</p>

* teclado:void</p>

* mouse:void</p>

##### ATRIBUTOS
- app:PApplet </p>
Este atributo es para instanciar la libreria de processing a la clase logica, y asi poder usarla en todas las demas clases </p>
- palabras:Arraylist<Strings> </p>
Este atributo se utilizara para crear la lista de palabras, letras y las diferentes interacciones que habran dentro de estas


### CENTRO
Esta clase padre es la estructura de las dos posibles composiciones, ya se la luna o el sol con sus diferentes interacciones </p>
#### METODOS
* pintar:void </sp>
Este metodo se encargara de pintar las dos posibles opciones , luna o sol con sus diferentes interacciones </p>

##### ATRIBUTOS
- s:Sol </p>
- l:luna </p>
estos dos atributos estan para conectar las interacciones de las dos clases hijas , luna y sol </p>
- isL:boolean </p>
este atributo sera para indicar en que caso esta la hija luna o la hija sol, y asi cuando se den unas interacciones de una clase no se daran las de la otra </p>

#### LUNA
Esta clase hija esta constituida por una ellipse  grande y mas pequeñas que representan la luna, la cual se modificara o no de acuerdo a si tienen interaccion con otra clase llamada meteoro </p>
##### METODOS
* pintar:void
Este metodo sirve para pintarla  la ellipse grande y las pequeñas que desapareceran al interactuar con el meteoro</p>
###### ATRIBUTOS
-posX:int </p>
-posY:int </p>
Ambas variables son las coordenadas son para dibujar la luna que esta compuesta por una ellipse  grande y otras pequeñas dentro del area de la ellipse </p>

#### SOL
Esta clase hija esta constituida por una ellipse que representa el sol  y unos aros alrededor de este con los cuales se podra interactuar
##### METODOS
* pintar:void </p>
Este metodo sirve para pintarla ellipse y los aros a su alrededor segun la interaccion dada </p>
###### ATRIBUTOS
-posX:int </p>
-posY:int </p>
Ambas variables son las coordenadas son para dibujar el sol y sus respectivos aros</p>
-tam:int </p>
-color:int </p>
Ambas variables son las propiedades para darle el tamaño y el color a los diferentes aros que se pintaran de acuerdo a cada letra </p>



### METEORO
Esta clase se encargara de crear la composicion mas compleja de un meteoro apartir de figuras simples que tendra como interaccion volar en diagonal para chocar contra la luna </p>
#### METODOS
* pintar:void </p>
En este metodo el objetivo es pintar el meteoro construido en la misma clase y asi poder interactuar con él con las coordenadas del mouse</p>
* mover:void </p>
En este metodo el objetivo es poder interactuar con el meteoro, en donde se modificaran las posiciones en el eje "x" y "y" para poder desplazar lo de manera diagonal y poder chocar la luna </p>
* chocar():boolean </p>
En este metodo se validara si el meteoro choco con la luna y asi desaareceran los puntos y se convertira en sol </p>

##### ATRIBUTOS
- posX:int </p>
- posY:int </p>
Ambas variables son las coordenadas tanto para dibujar como para desplazar el meteoro de manera diagonal </p>




### CONSTELACION
Esta clase se encargara de crear la composicion mas compleja de una constelacion  con las debidas estrellas, en donde tendran que ser puestas en determinadas zonas para poder armarla,despues estas mismas se engrandeceran y se convertiran en planetas, a los cuales se les aplicara gravedad </p>
#### METODO
* pintar:void </p>
En este metodo el objetivo es pintar la constelacion construido en la misma clase y asi poder interactuar con ella y sus estrellas, que despues de cierta condicion , ser convertiran en planetas </p>
* mover:void </p>
En este metodo el objetivo es poder interactuar con las estrellas tanto para darles la nueva posicion, como para aplicarles gravedad </p>
* agregar ():boolean </p>
En este metodo se validara si la estrella ha sido puesta en el punto de ancla para formar la constelacion y asi podran volverse planetas. </p>
##### ATRIBUTOS
-posX:int </p>
-posY:int </p>
Ambas variables son las coordenadas tanto para dibujar como para desplazar el las estrellas , que despues seran planetas</p>
-tam:int </p>
-color:int </p>
Ambas variables son las propiedades para modificar el tamaño y el color en las estrellas y asi volverlas planetas </p>



### ELEFANTE
Esta clase se encargara de crear la composicion mas compleja de un elefante comido por una boa como en la historia del principito apartir de figuras simples que tendra como interaccion desplazarse en el eje "x" y capturar los planetas </p>
#### METODOS
* pintar:void </p>
En este metodo el objetivo es pintar el cohete construido en la misma clase y asi poder interactuar con él </p>
* mover:void </p>
En este metodo el objetivo es poder interactuar con el elefante, en donde se modificaran las posiciones en el eje x para poder moverlo y poder atrapar los planetas </p>
* Atrapo():boolean </p>
En este metodo se validara si el elefante toco o no el planeta y  si es asi lo desaparecera. </p>

##### ATRIBUTOS
- posX:int </p>
- posY:int </p>
Ambas variables son las coordenadas tanto para dibujar como para desplazar el elefante </p>



### CUHETE </p>
Esta clase se encargara de crear la composicion mas compleja de un cohete apartir de figuras simples que tendra como interaccion volar </p>
#### METODOS </p>
* pintar:void </p>
En este metodo el objetivo es pintar el cohete construido en la misma clase y asi poder interactuar con él </p>
* mover:void </p>
En este metodo el objetivo es poder interactuar con el cohete, en donde se modificaran las posiciones en el eje y para poder moverlo</p>
##### ATRIBUTOS
- posX:int </p>
- posY:int </p>
Ambas variables son las coordenadas tanto para dibujar como para desplazar el cohete </p>

