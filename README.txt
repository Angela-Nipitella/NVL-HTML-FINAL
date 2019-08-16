PROYECTO FINAL. 

 Crear una pagina web donde la empresa fuese una tienda/hotel para mascotas, presentando la siguiente información; quiénes somos?,
 servicios que prestamos, tabla de precios y bonos de descuento, y un formulario para contactar luego al cliente.

 Se elaboro todo el contenido dentro de un archivo .html, utilizando la estructura básica

 el contenido de quiénes somos es lo primero que se puede ver, ubicado dentro del body, utilizando las etiquetas
 header y h1: para el encabezado principal (nombre de la empresa y eslogan) 
 h2: Para quienes somos?
 p: para desarrollar el contenido haciendo enfasis con 
 strong: cada vez que se menciona el nombre de la empresa

 h2: se utilizo tambien para el encabezado de los servicios
 img: para inserción de imagenes
 figcaption: para titulo de pie de fotos

 br: para hacer saltos de linea

 table: Para generar la tabla de servicios con sus precios y bonos 
 thead: para agrupar toda la primera fila que es la que contiene la información de encabezado, dentro de la misma se encuentra anidada
  tr: que es la que hace la fila para a su vez anidar cada una de las celdas siguientes
  th: crea las celdas con mas fuerza a nivel gráfico y de motor de busqueda

Luego el proceso se repite 5 veces pero esta vez cambiando <th> por <td> que presentan un nivel estandar a nivel gráfico.

Se presenta un breve formulario para que el cliente pueda rellenar en caso de que quiera ser contactado.
h3: para encabezado del formulario
form: Formulario usando de atributos method="post"(para indicar que recolectara la informacion) 
action="Miservidor.php"(a donde sera enviada la información).
div: todas las secciones de este formulario se agruparon dentro de un div y a su vez todos los div dentro de <Form>
dentro de cada div encontramos un label y un input
label: para decirle al servidor que información es y para mostrar en la pagina al usuario que debe rellenar en esa casilla. Usado el
atributo "for".
input: para ordenar la información que se le dice en label que recogerá, usando los atributos:
"id": se debe colocar el mismo que se coloco en label 
"type": indica el tipo de información. numerico, texto.
"name": se ultiza para introducir el nombre.

para concluir el boton que hara toda la magia y hara llegar la información al servidor en cuestión.
se utliza la etiqueta input pero con el atributo type="submit"(le indica lo que hara) y Value="enviar"(este es el que colocara 
el texto en el boton).

y por ultimo se cierra la etiqueta de body y luego el html.