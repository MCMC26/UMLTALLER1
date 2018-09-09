# UMLTALLER1

![uml_taller1 - pagina 2](https://user-images.githubusercontent.com/42015388/45259922-27477800-b39e-11e8-989e-4f30f7467b4b.jpeg)

## MAIN
Esta clase llama la clase ejecutable logica, aqui se define el la resolucion y los metodos prinplales de 
PApplet (API de processing)
#### METODOS
* settings:void

* setup:void</p>
este meodo inicializa todo
* draw:void</p>

* mousePressed:void</p>

* mouseReleassed:void</p>

* mouseDragged:void</p>

##### ATRIBUTOS
- log:Logica


## LOGICA
Esta clase llama la clase ejecutable logica, aqui se define el la resolucion y los metodos prinplales de 
PApplet (API de processing)
#### METODOS
* pintar:void</p>

* teclado:void</p>

* mouse:void</p>

##### ATRIBUTOS
- app:PApplet
- palabras:Arraylist<Strings>


### CENTRO
Esta clase padre abstracta llama la clase ejecutable logica, aqui se define el la resolucion y los metodos prinplales de 
PApplet (API de processing)
#### METODOS
* pintar:void

##### ATRIBUTOS
- s:Sol
- l:luna
- isL:boolean 
#### LUNA
Esta clase padre abstracta llama la clase ejecutable logica, aqui se define el la resolucion y los metodos prinplales de 
PApplet (API de processing)
##### METODOS
* pintar:void

###### ATRIBUTOS
- s:Sol
- l:luna
- isL:boolean 
#### SOL
Esta clase padre abstracta llama la clase ejecutable logica, aqui se define el la resolucion y los metodos prinplales de 
PApplet (API de processing)
##### METODOS
* pintar:void

###### ATRIBUTOS
- s:Sol
- l:luna
- isL:boolean 



### METEORO
Esta clase padre abstracta llama la clase ejecutable logica, aqui se define el la resolucion y los metodos prinplales de 
PApplet (API de processing)
#### METODOS
* pintar:void

##### ATRIBUTOS
- s:Sol
- l:luna
- isL:boolean 



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
-tam:int
-color:int
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

