# paw-tp3
Trabajo Practico N°3 de Programacion en Ambiente Web - UNLu

## Consignas
<p><b>1) ¿Qué significa que los estilos se apliquen en cascada? ¿cómo aplica la herencia de estilos?</b></p>
<p> El significado de la aplicación de estilos en cascada hace referencia a que seguirá un patrón a la hora de aplicar el estilo a los elementos de forma masiva, el cual tendrá en cuenta las relaciones de herencia entre unos y otros, yendo desde lo más general a lo más específico.</P>
<p>Esta herencia que determina CSS se basa en qué elementos del HTML cumplen con una determinada característica para aplicarles un estilo particular, y por ende tendrán ese estilo todos los elementos que se consideren dentro del grupo que cumple esas características. Así, para los  elementos que formen parte de varios estilos definidos, se tomara siempre la definición que haya sido mas especifica, y tambien se afectara de igual forma a los proximos elementos que esten dentro de estos antes mencionados.</p>  
<p>A la hora de aplicar los estilos a un grupo de elementos tiene en cuenta la importancia dentro del código (indicada por el programador), la especificidad (cuantas mas características tenga en cuenta, se aplicará mas particularmente en lugar de tener los estilos mas genericos) y el orden en el código.</p>
<br>
<p><b>2) ¿Por qué es necesario utilizar un CSS de Reset?</b></p>
<p> Los Reset son definiciones del CSS para propiedades problemáticas que los diseñadores necesitan unificar desde un principio.</p>
<p> Son necesarios para limpiar todas las propiedades de CSS que aplican por defecto los navegadores web y que son diferentes en cada uno de ellos. De esta manera, la hoja de estilo que definamos, será lo más homogénea posible en todos los navegadores web que existen, a pesar de sus diferencias. </p>
<br>
<p><b>3) ¿Qué es el CSS box model?</b></p>
<p> Es un estandar para el diseño de CSS en el cual se considera cada elemento que conforma el HTML como una caja rectangular, la cual posee 4 principales caracteristicas, que se pueden editar para variar el tamaño y forma del contenido):</p>
  <p> <b>Content:</b> limita el area del contenido, como texto, imagen, video, etc</p>
  <p> <b>Padding:</b> Extiende el área del contenido para incluir el relleno del elemento,>
  <p> <b>Border:</b> pertenece al elemento y sirve para extender el borde por sobre el padding.>
  <p> <b>Margin:</b> Distancia que guardará con respecto a los demás elementos</p>
<p>Vale aclarar que cuando se editan las propiedades Width y Height solo se estan refiriendo al contenido de la caja..</p>  
<br>
<p><b>4) ¿Cuál es el código que hay que insertar en una hoja de estilo para poder usar WebFonts?</b></p>
<p> La WebsFonts nos facilitan el diseño ya que en lugar de depender de las fuentes instaladas en el ordenador del usuario que visite la pagina, el S.O, o algun otro factor externo, las WebFonts se almacenan en un propio servidor (externo), se descargan junto con las imágenes y el resto de recursos, y son formateables. Las mas usadas en la actualidad son las fuentes libres de Google: Google Fonts </p>
<p>  Para poder insertar una fuente de este tipo en nuestra hoja de estilos debemos insertar el siguiente codigo:</p>
<p><cite>@import url("https://fonts.googleapis.com/css?family=Mystery+Quest");</cite></p>
<p> En donde el link citado de ejemplo corresponderá a la fuente desde donde queramos importar ese tipo de letra. Luego bastará con setear el valor de Font-Family de algun elemento del HTML con el nombre de la letra importada. Para este caso, quedaría asi:
<p> <cite> body{  font-family: "Mystery Quest";   } </cite></p> 
<br>
<p><b>5) ¿Qué son y para qué sirven los pseudoElementos?</b></p>
<p> RESPUESTA </p>
<br>
<p><b>6) ¿Cómo se calcula la prioridad de una regla CSS? Expresarlo como una fórmula matemática.</b></p>
<p> RESPUESTA </p>
<br>
<p><b>7) ¿Qué es el view port? ¿Cómo se configura? ¿qué problema soluciona?</b></p>
<p> RESPUESTA </p>
<br>
<p><b>8) ¿Qué son las media querys? Enumere los distintos tipos de medios y las principales
características de cada uno de ellos.</b></p>
<p> RESPUESTA </p>
<br>
<p><b>9) ¿En qué circunstancias se pueden utilizar las variables css? ¿Qué problemas pueden traer
aparejadas? ¿Cuándo consideras que sería bueno utilizarlas?</b></p>
<p> RESPUESTA </p>
<br>
<p><b>10) CSS Grid Layout ¿Qué es? Explicar las reglas que intervienen en el armado de una grilla.
¿Qué ventajas y desventajas tiene frente a otros Layouts?</b></p>
<p> RESPUESTA </p>
<br>
<p><b>11) ¿Qué puntos en común y en que se diferencian las Material Design Guidelines de Google y
las Human Interface Guidelines de Apple?</b></p>
<p> RESPUESTA </p>
<br>
