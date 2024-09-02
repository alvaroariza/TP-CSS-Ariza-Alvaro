# TP-CSS-Ariza-Alvaro
Pagina Web imitando pagina modelo usando HTML5 y CSS3

# Cabecera
En esta parte se hizo uso de la equeta header y se le aplico la clase header para editarla luego en CSS. En esta ultima parte se le agrego color de fondo, color de texto, alineacion del texto, configuracion de margenes entre otras cosas.

# Propiedades de Texto en CSS
Inicialmente comienza con un titulo en h4. A esta seccion y a las siguientes se les aplico la clase section para editarla con CSS. Las configuraciones dadas en este caso fueron el color del texto, el tamaño de letra y la alineacion. Ademas se uso la etiqueta <hr/ > para dar una linea de separacion.
Ademas se tiene una cita de autor gracias a la etiqueta blockquote con la clase cita en la que se le dieron ciertas configuraciones.

# Propiedades de Caja en CSS
A diferencia de la seccion anterior, aqui se colocan 2 cajas de texto con las clases box y box-highlight. En estas clases editamos aspectos como border, padding, margin y shadow para darle un aspecto mas agradable.

# Posicion Relativa y Absoluta en CSS
En esta seccion se tiene una caja  con posicion relativa y otra caja con posicion absoluta dentro de la caja relativa. Se les asignaron las clases relative-box y absolute-box respectivamente. Lo interesante es que en las configuraciones de absolute-box seteamos valores para que esta caja se situe en relacion a su caja padre. Para eso usamos variables como left, bottom y width.
Tambien se configuro que cuando la pantalla tenga un ancho maximo de 768px cambie el color del body, cambie el tamaño de texto del header y los margenes de las secciones se ajusten al 5% y el padding a 15px.
Y adicionalmente por temas de estetica se configuro que cuando la pantalla tenga menos de 1500px de ancho la caja absoluta baje aun mas para que esta no tape el texto de la caja con posicion relativa.

# Principios de Grid en CSS
En esta seccion se tienen 4 div con la clase grid-item dentro de un div con la clase grid-container.
En la clase grid-container se seteo el uso de grid, se hizo uso de la instruccion grid-template-columns para ordenar los elementos en columnas como deseemos, y tambien se añadio espaciado mediante gap.
En la clase grid-item se hizo la configuracion basica de una caja de texto.

# Principios de Animaciones en CSS
Aca se tienen 2 div con las clases animacion y mover.
En la clase animacion se define el tamaño del elemento, su color y cuanto duraria la transicion. En una clase animacion:hover se definio que pasaria cuando se hiciera hover sobre el elemento. En este caso cambia de color.
En la clase mover se define la instruccion animacion seguido del nombre de una funcion, su duracion y el formato (animation: mover 3s infinite;). Esta funcion tambien llamada mover se define con el uso de @keyframes. Dentro se especifica que acciones se deven seguir. En este caso son desplazamientos sobre el eje X.
