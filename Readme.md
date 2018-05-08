<section class="cover">

# Amor por el código

![Logo Amor por el código](images/logo_amor.png)

</section>
<section>

# Bienvenido

Amor por el código es una actividad que nace desde las mentes creativas y vanguardistas de academia desafío.

El objetivo, ~~es enamorarse~~ es utilizar esta tarde, para conocer gente nueva, divertirnos y aprender a hacer una página web.

Todos los pasos importantes que necesitas realizar se encuentran en esta guía, la revisaremos en conjunto y  realizaremos las actividades. de esta forma aprenderemos de forma práctica a construir páginas web.

Si no tienes ningún conocimiento previo, no los necesitas, te guiaremos en el proceso.

Trataremos de ir explicando cada término utilizado para que tengas un contexto de lo que estamos haciendo, y a tu disposición estarán los mentores y guías para ayudarte cuando lo necesites.


## ¿Qué se necesita para este taller?

Para el evento solo necesitas que tu computador tenga instalado, un navegador y un editor de texto y de tu parte muchas ganas de participar y aprender.

Como navegador puedes ocupar alguno de los siguiente:

- Firefox
- Safari
- Chrome
- Opera
- Edge

Como editor de texto te recomendamos:

- [Atom](https://atom.io/).
- [Sublime](https://www.sublimetext.com/).


***Con el editor de texto instalado pasemos a la siguiente sección***

![](https://media.giphy.com/media/fJKG1UTK7k64w/giphy.gif)


## ¿Qué es una página web?

Si buscamos en google, posiblemente encontremos desde respuestas muy complejas a que la respuesta esta en nuestro corazón, así que definiremos de forma muy simple algunos términos.


***WebPage (página web):*** Es un documento que puede ser visto en la pantalla a través de un navegador como Firefox, Google Chrome, Internet Explorer. Solo es un documento.

***Website (sitio Web):*** Es una colección de páginas(documentos), agrupadas y conectadas, generalmente de un mismo tema o tópico.

***Web Server (servidor Web):*** Es un computador que guarda los archivos de los sitios web.

***CSS(Cascading Stylesheets):*** Significa hojas de estilo en cascada y es un lenguaje para definir estilos a las etiquetas HTML. CSS también puede definir como los elementos pueden ser mostrados.

***JS (JavaScript):***  es un lenguaje de programación que permite modificar dinámicamente elementos de HTMLL y CSS y de esta forma agregar componentes y comportamientos nuevos a la página web así como agregar diversos tipos de animaciones e interactuar con información de otros sitios web.

![](https://media.giphy.com/media/ZEobigiRBFc7S/giphy.gif)

## Creando nuestra primera página web:


Vamos a crear un proyecto totalmente desde cero, sigue los pasos y si tienes dudas, acércate a algún mentor, guía de la actividad, ~~o aquella persona que te llamo la atención~~, estamos acá para ayudarte.


### Primer paso :

Vamos a crear una carpeta nueva en el escritorio. Le puedes llamar como tu quieras, como ejemplo "proyecto web".

### Segundo paso:

Luego abrimos la carpeta "proyecto web" en Atom (tú editor de texto).

- Puede ser arrastrando la carpeta hacia el editor de texto
- O abriéndola desde el editor de texto.

### Tercer paso:

Ahora crearemos un archivo nuevo llamado index.html  ( debemos presionar sobre la carpeta del proyecto el botón secundario y utilizar la opción "New File".

![new file con Atom](images/New_file_atom.png)

Luego:

Llamaremos a nuestro primer archivo

~~~
index.html
~~~


![imagen de Atom con index.html](images/Nuevo_archivo_Atom.png)

Presionamos enter y el archivo quedó guardado como index.html

### Cuarto Paso:

Ahora escribiremos, en nuestro archivo:

~~~html
Feliz día del amor !!!
~~~

Luego guardamos el archivo, para hacerlo puedes ir a la opción File / save, pero te recomiendo que utilizes el atajo del teclado.

***Ctrl + s (Windows, Linux) o  cmd + s (mac).***

### Quinto paso

Ahora podemos abrir este archivo con nuestro navegador, para lograrlo iremos a la carpeta donde está guardado y podemos arrastrarlo con el mouse dentro del navegador.

Al abrirlo en el navegador te debería aparecer algo como esto:

![imagen feliz día del](images/FirstPage.png)

***Felicidades!!	Ya estás escribiendo tú primera página web!!!***


### Recapitulemos

Fueron solo 5 pasos, mucho mas fácil que hacer una piscola, ¿cierto?.

Respondamos algunas preguntas.

***¿Por qué llamar al archivo de inicio como index?***

Porque es una convención, se subentiende que es el archivo índice que inicia una página web.

***¿Por qué la extension del archivo es .html?***

El que sea .html dice que es un archivo que se interpretará como HTML, es decir el navegador abrirá y leerá su contenido, En la siguiente sección aprenderemos mas sobre HTML.

Ahora podemos crear una página web para declarar nuestro amor.

## ¿Qué es HTML?

HTML significa "HyperText Markup Language" - en español, **Lenguaje de Marcas** de HyperTexto.

**HyperText** significa que es un tipo de texto que soporta hipervínculos entre páginas.

**Marcado** significa que hemos tomado un documento y lo marca con código para decirte cómo interpretar la página (en este caso, un navegador).

HTML es un lenguaje de **marcas**, cada una comenzando con `<` y terminando con `>`. Estas etiquetas definen **propiedades**, la **importancia** y el **significado semántico** del contenido que envuelven.

![imagen html lenguaje de marcas](images/html_marcas.png)

Entonces una página web es un archivo que contiene un conjunto de marcas ó etiquetas y el navegador lee (interpreta) estas marcas y con esa información  muestra las páginas web.

# ~~Conozcamonos~~ Trabajemos.

Reunanse en parejas, si, no sean timid@, estamos acá para conocer gente y aprender.

Una vez reunidos, vamos a construir  un sitio con el  perfil de tu compañer@. Vamos a añadir alguna foto, por lo cual cada uno deberá facilitar sacarse una o bajarla de la red social.

Si viniste con tu pareja y todos estos datos ya son conocidos, Celebremos el amor y creemos una oda a la persona que tenemos a nuestro lado, Una página con su descripciones y gustos, o simplemente porque la aman tanto,  o sus mas oscuros deseos etc... seamos creativos.

Si por algún motivo no alcanzamos a tener compañer@, no te preocupes, crea tu propio perfil, demostrando que eres mas cool y que amas el código y a ti,  mas que el whiskey al hielo.

## Primera parte

### Estructura de HTML

Un archivo HTML para poder ser interpretado correctamente deber tener una estructura. Esta estructura básica consiste en una **cabeza** (*head*) y un **cuerpo** (*body*), la cabeza contiene toda la información que es para el **navegador**, el cuerpo de la página contiene toda la información que es para el **usuario**. Dentro de las etiquetas HTML se encuentra todo el contenido de la página, y dentro de ellas están los dos bloques previamente mencionados.

La estructura de una página en HTML es la siguiente:

~~~html
<!DOCTYPE html>
<html>
<head>
	<title></title>
</head>
<body>
    <!-- Aquí va el contenido de la página web -->
</body>
</html>
~~~

El `doctype` (o tipo de documento) es la primera etiqueta que leeremos y le indica al navegador como debe interpretar el resto del documento. En el ejemplo veremos que el doctype especificado es de HTML5, el cuál es el estándar de actual.

La etiqueta `<html>` especifica que desde ese punto en adelante todo lo que venga deberá ser interpretado como HTML.

En HTML la etiqueta `<head>` Contendrá información variada, desde dónde encontrar las hojas de estilo o los iconos, hasta cuál es el título del sitio o sencillamente cómo debe manejar la página en el caso de que tenga que adaptarse a distintos tamaños de pantalla.


### Actividad 01.

1-	Borra el mensaje del index.html que creamos, y escribe en la primera linea

~~~html
html
~~~

Gracias a las cualidades de nuestro editor de texto, si presionamos enter luego de escribirlo, nos dará la posibilidad de autocompletar la estructura base del html.

![html](images/html_estructura.png)

De esta forma podemos tener la estructura de nuestra página.

![html-Autocompletado](images/html_estructura01.png)



No olvides guardar la página en este punto  Ctrl + s(windows, linux)  o cmd + s(mac) , Atom borrará el punto azul en el nombre de nuestro archivo cuando esta guardado.


### El título

Muestra en el navegador el título de la página, se escribe entre las marcas `<title>` y `</title>` y tiene la función de ser una guía visual del contenido de la ventana o del tab del navegador.

~~~html
<!DOCTYPE html>
<html>
<head>
	<title> Gal Gadot </title>
</head>
<body>
    <!-- Aquí va todo lo que quieras agregar -->
</body>
</html>
~~~

![imagen del titulo](images/title_gal.png)

>Cabe destacar que Los bookmarks ocupan el título de la página al guardarla.
>El título tiene mucho valor en el SEO(search engine optimization) de un sitio web.


### Actividad 02

Ponle título a tu página , ingresando el nombre de tú compañer@, o lo que necesites ingresar. No olvides guardar.


## Atributos y valores

En la etiqueta `<meta charset="utf-8">` vemos que hay algo nuevo que no habíamos visto en otras etiquetas, en primer lugar la marca no se cierra, y la regla es simple, si la etiqueta no tiene contenido no se cierra, y para pasarle valores adicionales se ocupan **atributos** y **valores**, donde `charset` sería el *atributo* y `utf-8` el *valor*.

## Etiquetas Básicas:

Todo lo que veremos desde ahora se debe escribir dentro de **body** *(hasta que se indique lo contrario), por ende dentro de las etiquetas* `<body>` `</body>`

### Párrafos:

Si escribes en el archivo index.html :

~~~html
<!DOCTYPE html>
<html>
	<head>
    <meta charset="utf-8">
    <title>Gal Gadot</title>
  	</head>
  	<body>
    hola a todos !!!
    hola hola hola
    hola !!!
  	</body>
 </html>

~~~

Al refrescar el navegador, éste se leerá de la siguiente forma:

![imagen de no párrafos](images/noparrafos.png)

Si observas, el navegador no respeta la sintaxis de párrafos y se lee como si estuviera todo escrito en una misma línea.

Lo que pasa es que HTML es un lenguaje de marcas y para separar cada línea del texto y se pueda leer todo en varias líneas, deben de existir etiquetas de por medio.
Vamos a aprender la primera etiqueta y la más sencilla de todas: `p`.

Se abre con `<p>` y debido a que contiene información se debe cerrar con `</p>`.

Todo el contenido que se encuentre dentro de estas marcas pasa a tener la **propiedad de párrafo**.
Por ejemplo, escribamos esto en nuestro archivo index.html:

~~~html
    hola a todos !!!
    hola hola hola
    hola !!!
    <p>Gal es mi novia</p>
    <p>Es una mujer maravillosa</p>
~~~

*No olvidar que esto se escribe dentro de body.*

Refrescamos el navegador y quedaría algo así:

![imagen de párrafos](images/Parrafosnew02.png)

Gracias a la etiqueta `<p>` Ahora **si** respeta que sea un párrafo!!!

Puedes agregar la cantidad y largo de contenido que quieras.

En Atom si se escribe "p" (o cualquier marca) y luego tab, se autocompleta la etiqueta por si sola. Para que este truco funcione es necesario que el editor tenga identificado el tipo de archivo(html), por defecto lo detecta por la extensión original, pero se puede cambiar en la parte inferior izquierda.


### Actividad 03

Añade 3 párrafos a tu página web:

-	El primero debe describir brevemente a tu compañer@.
-  El segundo debe indicar la edad de tú compañer@ y cuando esta de cumpleaños.
-  El tercero debe indicar cual era la expectativa de participar hoy en este evento.

No olvides guardar tu archivo y revisa tu progreso en tu navegador.


### Títulos y Subtítulos:

Una página web también tiene títulos y subtítulos, al igual que un periódico!

La marca para los titulares es `<h>` **más** un número del `1` al `6`. Siendo `<h1>` para el titular principal o con mayor importancia y `<h6>` para el subtítulo del subtítulo del subtítulo del subtítulo del subtítulo del título!

Por ejemplo escribamos en nuestro archivo index.html:

~~~html
hola a todos !!!
    hola hola hola
    hola !!!
    <h1> Titulo 1 </h1>
    <p>Gal es mi novia</p>
    <p>Me encanta su personalidad</p>
    <p>Le cargaría la bip</p>
	<h6> Sub sub sub sub sub titulo </h6>

~~~

Refrescamos el navegador y se debería ver algo como esto:

![imagen de titulares](images/Titulos01.png)

Se puede ver que el titular `<h6>` es muy pequeño, incluso menor que los párrafos.


### Actividad 04

- Añade un título a tu página, indicando el nombre de tu compañer@.
- Añade un subtítulo a tu página , indicando una frase que la identifique.
- Estos títulos deben ir antes de los párrafos.


### Imágenes:

Hasta el momento solo hemos utilizado texto, así que pondremos algunas imágenes. La etiqueta para agregar imágenes es

~~~html
<img src=" " alt=" ">
~~~

Donde `src` es *source* , que en español es fuente y que es un **atributo** de la etiqueta de imagen. `alt` es otro **atributo** de la etiqueta `img`, que te permite describir(brevemente) la imagen en caso de que no se pueda cargar por escasez de internet, o en navegadores de solo texto.

Esta etiqueta no necesita cerrarse como lo hacen las anteriores.

Para agregar imágenes utilizando esa etiqueta puedes hacerlo de dos maneras:

-Directo de una URL de internet.
-Desde una imagen desde tu proyecto (desde tu computador).

### Imágenes Desde internet:

Buscas en el google la imagen que quieras, y luego haciendo click en "ver imagen" , ésta te llevará a una url terminada en .jpg o .png

![imagen universo](images/GalGadot03.png)

Esa url debes copiarla y pegarla dentro de los `" "` del source

~~~html
<img src="https://images-na.ssl-images-amazon.com/images/M/MV5BMjUzZTJmZDItODRjYS00ZGRhLTg2NWQtOGE0YjJhNWVlMjNjXkEyXkFqcGdeQXVyMTg4NDI0NDM@._V1_UY317_CR51,0,214,317_AL_.jpg" alt="Galgadotita">
~~~
Entonces si esto lo agregamos en nuestro archivo index.html:

~~~html
  hola a todos !!!
    hola hola hola
    hola !!!
    <h1> GAL GADOT </h1>
    <h2> Gal es una mujer empoderada y hermosa.</h2>
    <p>Gal es preciosa</p>
    <p>Me encanta su personalidad</p>
    <p>Le cargaría la bip</p>
    <h6> Sub sub sub sub sub titulo </h6>
    <img src="https://images-na.ssl-images-amazon.com/images/M/MV5BMjUzZTJmZDItODRjYS00ZGRhLTg2NWQtOGE0YjJhNWVlMjNjXkEyXkFqcGdeQXVyMTg4NDI0NDM@._V1_UY317_CR51,0,214,317_AL_.jpg"
     alt="GalGadotita">
~~~

Refrescamos el navegador:

![imagen index_img](images/GalGadot02.png)

##### Imágenes desde el computador:

Para esto debes crearte una carpeta **dentro** de tu proyecto llamada *images* y ahí ir integrando las imágenes que quieres en tu proyecto:

~~~
proyecto_web
└───index.html
	images
    └─── ejemplo.jpg
~~~

*Puede ser formato jpg, png, jpeg, ahí debes ver que formato es tu imagen. Importante que las imágenes estén en una carpeta que se llame images dentro de la carpeta de donde está tú proyecto*

En ese ejemplo yo estoy agregando una imagen a mi carpeta *images* con el nombre de *ejemplo* y de formato *.jpg*

Entonces para agregarla en mi web se copia la ruta de donde se encuentra mi imagen en el `src` de la siguiente manera:

~~~html
<img src="images/ejemplo.jpg" alt="ejemplo">
~~~

Donde *images* es el nombre de la carpeta donde se encuentra mi imagen + `/` + *ejemplo* (nombre de mi imagen) `.jpg`(formato)


### Actividad 05

-	Añade una foto de tu compañer@ puede ser a través de la red social o una que tomes en el momento. Recuerda que si el archivo es local, debes creas la carpeta images dentro de tu proyecto. (Solicita permiso a tu compañero antes de tomar la foto).
-	Añade la foto arriba del primer título.
-  Guarda tu archivo y comprueba tu progreso en el navegador.


### Links:

Los links se hacen con la etiqueta `<a>`:

~~~html
<a href=" "> </a>
~~~
Esta etiqueta tiene el atributo href que es hacia adonde apunta, y contenido que muestra el texto, ya que tiene contenido esta etiqueta **si** se cierra.

Veamos un ejemplo:

~~~html
<a href="https://www.facebook.com/events/1455951704527398/">Link al evento</a>

~~~
Aquí se está transformando a la frase *Link al evento* en un hipervínculos. Y al hacerle *click* en ella , te enviará al link escrito dentro de las `" "` del `href`

![imagen del link](images/link.png)

Por ende lo que hace esta etiqueta es darle la **propiedad de hipervínculos** al contenido de ésta, apuntándolo al link que se encuentra en `href`

Si pongo link sin `href`, no me llevará a ninguna parte. Y si al link no le pongo texto(contenido) ,pero si `href`, no se podrá ver el link por ninguna parte y por ende no se podrá hacer nada.

Si yo quisiera que el link me abriera en una página nueva, hay que agregarle a la etiqueta el **atributo** `target="_blank"`, quedando de esta forma:

~~~html
<a href="https://www.facebook.com/events/2162321913993416/" target="_blank" > Link al evento </a>
~~~

*Importante resaltar que todos los* **atributos** (`href` , `target`, etc...) *se escriben dentro de la etiqueta `< ... >` no fuera, ya que pasaría a ser texto.*


### Actividad 06


- Añade un párrafo y en su interior agrega el enlace a alguna red social de tu compañer@. Si no tiene red social, utiliza cualquier página que le guste mucho, pone una descripción al enlace.


- Añade una nueva foto de algunos de sus pasatiempos e intenta convertirla en un hipervínculo, el link a donde nos redirige debe ser alguna página acorde a la imagen.

>Si necesitas ayuda, no dudes en preguntar a tu mentor.



***

## Recapitulemos

Hagamos un pequeño resumen de lo que hemos aprendido:
Si todo salió bien, Nuestro código debería verse así.

~~~html
<!DOCTYPE html>
<html>
<head>
  <title>Pizza de Pepperoni</title>
  <meta charset="utf-8">
</head>
<body>
    <img src="http://littlecaesars.com.mx/portals/7/Images/			HSMenu_HNR_Clasica_Pep_Hisp.png" 			alt="DeliciosaPizza">
    <h1> Pizza De Peperoni </h1>
    <h2>Hermosa y Deliciosa pizza, rapida y concisa.</h3>
    <p> Lorem ipsum dolor sit amet, consectetur adipisicing 		  elit.
      Ipsam consequuntur omnis minima dolorem adipisci officiis 		enim
      optio tenetur quos aliquid, saepe, corporis dignissimos?
      Harum debitis veritatis voluptas, illum iste deserunt.
      Lorem ipsum dolor sit amet, consectetur adipisicing elit.
      Quo dolorem dignissimos expedita repellendus ducimus 		natus
      possimus, molestiae architecto, aperiam officiis, amet 		consequatur,
      	nisi. Est accusamus eum quos natus architecto modi.</p>
    <p> Facebook de la Pizza <a href="https://www.facebook.com/			LittleCaesarsPIzzaSanJoaquin/" target="_blank" >aquí 	</a></p>
    <a href="https://littlecaesars.com/en-us/"> <img 	src="images/pizzaLittle.jpg" alt="DeliciosaPizza"> </a>
  </body>
</html>

~~~

Esto se vería así:

![imagen resumen](images/recapitulacion01.png)


- Primero se está llamando una imagen desde el internet.
- Luego se pone un título `<h1>`(Titular principal).
- Luego un sub sub título `<h2>`.
- Luego viene un párrafo con bastante texto.
- Luego un párrafo que a su vez con tiene un link (`<a>`).
- luego dentro de un link se llama a una imagen que se encuentra dentro de la carpeta *images* y que se llama *pizzaLittle.jpg*. Convirtiendo la imagen en un hipervínculo.



***Revisa si tienes algo parecido a esto,   Felicidades¡ haz avanzado mucho , recuerda que si tienes dudas pide ayuda a los mentores.***


# Ordenando nuestra página.

### Listas ordenadas:
Para definir una lista de elementos ordenados ocuparemos la etiqueta `<ol>`, pero dentro de esta lista debemos definir elementos, eso lo haremos con la etiqueta `<li>`

Las listas ordenadas tienen un número o letra, esto lo modificaremos más adelante con CSS.

~~~html
<h3> Esta es una lista ordenada </h3>
<ol>
	<li> Lista 1 </li>
	<li> Lista 2 </li>
</ol>

~~~
![imagen lista ordenada](images/listaordenada.png)

### Listas desordenadas:

Las listas desordenadas tienen bullets, esto también es modificable con CSS.
Para definir una lista de elementos desordenados ocuparemos la etiqueta `<ul>`, y dentro de esta lista debemos definir elementos, eso lo haremos con la etiqueta `<li>`

~~~html
<h3> Esta es una lista desordenada </h3>
<ul>
  <li> Lista 1 </li>
  <li> Lista 2 </li>
</ul>
~~~

![imagen lista ordenada](images/listadesordenada.png)
### Tablas

Es posible agregar tablas con datos ocupando la etiqueta `<table>`, dentro de una tabla debemos especificar las filas y las celdas dentro de las filas utilizando `<tr>` y `<td>` cada etiqueta tr especifica una nueva fila, y cada etiqueta td una celda.

~~~html
<table>
<tr>
<td> Celda 1</td>
<td> Celda 2</td>
</tr>

<tr>
<td> Celda 3</td>
<td> Celda 4</td>
</tr>

</table>
~~~

<table>
<tr>
<td> Celda 1</td>
<td> Celda 2</td>
</tr>

<tr>
<td> Celda 3</td>
<td> Celda 4</td>
</tr>

</table>

### Divs:
Los divs son etiquetas que permiten anidar a otras etiqueta y le damos estilo propio a la agrupación (esto lo haremos más adelante con CSS).
Envuelve varias etiquetas, y todas las etiquetas envueltas por él, están bajo la influencia del div.

~~~html
<div class="">
	<h1> Titular 1 </h1>
	<h2> Titular 2 </h2>
	<p> Párrafo 1 </p>
</div>
~~~

Cada div puede indicar una clase especifica, esto servirá mas adelante para identificar el contenido de ese div y aplicarle estilo con CSS.


### Span:

La etiqueta span es similar a los divs pero sirve para etiquetar texto, una parte de una palabra, una palabra o más. (luego con CSS, hace más sentido, por ahora es bueno que la conozcas)

~~~html
<p> Lorem <span> Ipsum </span> </p>
~~~


### Actividad 07

Vamos a continuar nuestra página dandole un poco de orden.

- Añade un nuevo div, y en su interior añade una lista ordenada con los sitios favoritos de tu compañer@.

- Añade un otro div y  agrega una tabla a tu página resaltando cualidades de tu compañer@.

**Por defecto al autocompletar un div aparece la etiqueta class="", por el momento la dejaremos vacía. Recuerda pedir ayuda a los mentores si tienes dudas.**




### Etiquetas semánticas:

HTML5 introduce  etiquetas semánticas, que no aportan ningún comportamiento visual adicional, pero que nos permiten por un lado definir de forma semántica el significado de su contenido, lo que será muy útil para el SEO (la optimización de contenidos para buscadores)

![imagen de etiquetas semánticas](images/semanticas.png)

Si quieres aprender más [aquí](http://www.tutorialmonsters.com/web-semantica-con-html5/)

### Resumen de etiquetas
Resumen de las etiquetas [aquí](resumen/resumen_de_marcas.md)



## El inspector de elementos
El inspector de elementos, es una herramienta que podemos abrirla haciendo click derecho sobre la página y luego inspect nos muestra el código completo de la página y nos permite modificarlo. Con esta herramienta pueden ver el código de cualquier página web.

Puedes aprender más sobre él [aquí](https://developer.mozilla.org/es/docs/Tools/Page_Inspector)

![inspector de elementos](images/inspect.png)

>Juega un rato con él, inspecciona lo que llevas de tu página,


## Encontrando errores en una página web
Una buena herramienta para detectar errores en tu página es w3c validator. Tiene diversas formas de validar, nosotros ocuparemos **Validate by direct input**, ahí podemos copiar el contenido de nuestra página y ver si hay errores de algún tipo.

![W3C Validator](images/w3cvalidator.png)






# Capítulo 2.

Ahora vamos a saltar al diseño de nuestra página web. Porque un HTML no es nadie sin su CSS.


![imagen de html css y js](images/htmlcssjs.png)

Hemos aprendido algunas cosas esenciales de HTML, lo  que vendría siendo el esqueleto de nuestro sitio web, ahora le añadiremos la "piel", el diseño, y eso lo hacemos con CSS.



# ¿Qué es CSS?

CSS es acrónimo de Cascading Style Sheet, o sea hojas de estilo que se pueden incorporar dentro de HTML para darle forma y color a nuestra voluntad.

Hay tres formas de incorporar CSS dentro de una página web.

- La primera es con un conjunto de atributos y valores dentro de la etiqueta del mismo HTML.

- La segunda consiste en agregar el CSS dentro del head del mismo documento HTML.

- La tercera forma consiste en utilizar un archivo externo.

La **forma recomendada de trabajar es la 3º**, pero para explicar como funciona CSS ejemplificaremos sobre la primera y se dará una breve explicación de la segunda.

## Sintaxis y primera forma
Todas las instrucciones en CSS se escriben en pares propiedad: valor, para agregar CSS sobre una etiqueta HTML (Primera forma) debes agregar a la etiqueta syle="propiedad: valor"

## Un ejemplo: color para un párrafo

~~~html
<p style="color: red"> </p>
~~~

## Agregando CSS en el head

La segunda forma de agregar CSS consiste en agregar las propiedades y valores de CSS dentro de una etiqueta style en el head de la página

~~~html
<head>
  <style>
    p {
    	color: red
   	}
  </style>
</head>
~~~



### Sintaxis:
La sintaxis de CSS tiene la siguiente estructura:

~~~css
etiqueta {
	propiedad: valor;
}
~~~


# Cargando un CSS externo:

La tercera forma para incluir CSS en una página web consiste en agregar un link a un CSS externo, con externo se refiere a fuera de la página, pero puede estar dentro del mismo servidor, o se puede cargar desde otro sitio.

Primero creamos un archivo nuevo, dentro de la carpeta de nuestro proyecto, llamado miestilo.css

~~~
proyecto_web
└───miestilo.css
	index.html
	images
    └─── ejemplo.jpg
~~~
El nombre no importa, lo importante es que sea `.css` para que sepa que estamos escribiendo CSS.

Para agregar un link a un archivo CSS ocuparemos la etiqueta link dentro del `<head>`.

~~~html
<link rel="stylesheet" type="text/css" href="miestilo.css">
~~~

>En Atom si se escribe link y luego se autocompleta con
>tab, la línea para agregar un CSS externo se escribe sola.

Quedando de esta manera:

~~~html
<!DOCTYPE html>
<html>
<head>
	<title> Pizza de Pepperoni </title>
   <meta charset="utf-8">
   <link rel="stylesheet" type="text/css" href="miestilo.css">
</head></head>
<body>
.
.
.
</body>
</html>
~~~

Con esto estamos agregando el CSS del archivo miestilo.css a nuestra página web.

###  Actividad 01

-	Añade y referencia un archivo .css en tu proyecto.


#### Color:

Vamos a cambiarle el color a la letra de nuestro título h1 y h2.

Tomando lo anterior y teniendo ya añadido nuestra hoja de estilo en head.

~~~html
<!DOCTYPE html>
<html>
<head>
  <title> Pizza de Pepperoni </title>
  <meta charset="utf-8">
  <link rel="stylesheet" type="text/css" href="miestilo.css">
</head>
<body>

  <img src="http://littlecaesars.com.mx/portals/7/Images/HSMenu_HNR_Clasica_Pep_Hisp.png" alt="Deliciosa Pizza">
  <h1> Pizza De Peperoni </h1>

  ..........

</body>
</html>

~~~

Utilizando la misma sintaxis:

~~~css
etiqueta {
	propiedad: valor;
}
~~~

Entonces para cambiarle el color a todo el contenido del título `<h1>` y `<h2>`

en nuestro archivo `miestilo.css`, añadimos:

~~~css
h1 {
	color: red;
}

h2 {
	color: blue;
}
~~~

Debería verse así.

![imagen de estilo](images/colortitulos.png)



Lo que hace el código anterior es tomar todas las etiquetas tipo `h1` y `h2` y les asigna el color. Siempre debes escribir los colores en inglés.

****
Qué pasa si quiero que toda mi página tenga un color de fondo?
Bueno sabemos que todo el código de nuestra página de encuentra dentro de las etiquetas de `<body>` verdad?

Pues entonces pongámosle un color de fondo:

~~~css
body {
	background-color: #F5DA81;
}
~~~

Quedando así:

![imagen de pag con fondo](images/backgroundcolor.png)


Vemos que ahora tenemos toda la página con un color distinto al por defecto que es blanco.

Nótese también que ahora no se utilizó darle el color nombrándolo, sino que se utilizó el sistema hexadecimal.

Más sobre colores en CSS [aquí](http://htmlcolorcodes.com/es/tutoriales/conceptos-basicos-de-color-css/).

Elige el color que quieras para el fondo de tu página, puedes ayudarte con el siguiente selector de colores.

[Color Picker](https://html-color-codes.info/codigos-de-colores-hexadecimales/)


### Tamaño de la fuente :
Ademas de darle color a la letra también podemos cambiar el tamaño.
Eso se hace utilizando la propiedad `font-size`

~~~css
p {
	color: green;
	font-size: 20px;
}
~~~

Aquí se puede ver que además de decirle a los párrafos que sean de color rojo, tenga el tamaño de 40 pixeles (`px`). Puedo agregar cuantas propiedades quiera sobre una etiqueta.

Pero esto hará que **todos** los párrafos se comporten de esa manera (que tengan el texto verde y tamaño de letra de 20px).

**¿Cómo hago para personalizar el cambio de una etiqueta específica?**

Ahora lo sabrás:

## ID y Clases

Los **ID** son identificadores **únicos** para cada etiqueta, es como un nombre que se le da a la etiqueta para hacerla única.

Por ejemplo se le asignará el id "parrafo1" al primer párrafo:

~~~html
<p id="parrafo1" > Lorem ipsum dolor sit amet, consectetur adipisicing elit.
Ipsam consequuntur omnis minima dolorem adipisci officiis enim
optio tenetur quos aliquid, saepe, corporis dignissimos?
Harum debitis veritatis voluptas, illum iste deserunt.
Lorem ipsum dolor sit amet, consectetur adipisicing elit.
Quo dolorem dignissimos expedita repellendus ducimus natus
possimus, molestiae architecto, aperiam officiis, amet consequatur,
 nisi. Est accusamus eum quos natus architecto modi </p>

~~~

De esta manera yo le puedo dar estilo específico a ese párrafo y no a todos.

Ahora le asigno el estilo en mi archivo miestilo.css

~~~css
#parrafo1 {
	color: blue;
	font-size: 10px;
}

~~~
Ahora solo mi párrafo con id "parrafo1" tendrá el texto azul y tamaño de fuente de 10px, y los demás serán verdes y con tamaño de 20px.

Se escribe `#` para referirse a una id , y más el nombre para saber a cuál id me estoy refiriendo.

Pero como se mencionaba anteriormente el id es único! Pero qué pasa si se quiere asignar esa propiedad a varias etiquetas distintas?

Para eso existen las **clases**. Las clases son parecidos a un identificador pero **no** son únicas. Eto quiere decir que varios elementos pueden tener la misma clase.

~~~html
<h1 class="violeta"> Pizza De Pepperoni </h1>
<h2 class=" violeta">Hermosa y Deliciosa pizza, rápida y concisa.</h2>
~~~

Aquí se le está asignando la misma clase a 2 etiquetas distintas (`<h1>`y `<h2>`).

Luego en el archivo CSS

~~~css
.violeta {
	color: violet;
}
~~~

Para referirse a las clases se se escribe un `. ` y luego el nombre que le diste a la clase en este caso `.violeta`

Con esto hago que dos etiquetas distintas (o cuantas yo quiera), tengan el contenido de color violeta.


## Actividad 02


-	Añade una clase específica para los títulos de tu página y dale un color que prefieras.
-  Añade una id especifica al párrafo y cambia el tamaño de la letra a 30px
-  Añade clases o ID y personaliza los elementos de tu página.




### Cambiando las tipografías
Para cambiar la tipografía de una marca debemos ocupar la propiedad font-family

~~~css
body{ font-family: "Times New Roman", Georgia, Serif; }
~~~

font family acepta diversas tipografías simultáneamente a modo de fallback, o sea si una tipografía falla en cargar se cargará la siguiente, si una de los nombres de la tipografía tiene espacios entre medio hay que agregarla entre comillas `" "`

### Googlefonts

[https://www.google.com/fonts
](https://fonts.google.com/)
Es una página web que permite cargar de forma sencilla diversas tipografías no tan comunes dentro de tu sitio,

![imagen google font](images/google_font.png)

Para utilizarla debes hacer click en la opción `select this font` de la fuente respectiva, luego seleccionar los pesos de la fuente.

Importar la fuente dentro del HTML o dentro del CSS, por ejemplo si quisiéramos importar open sans dentro del HTML sería:

~~~html
<link href="https://fonts.googleapis.com/css?family=Open+Sans" rel="stylesheet">
~~~

y finalmente utilizarla en nuestro archivo miestilo.css

~~~css
body {font-family: 'Open Sans', sans-serif;}
~~~




###  Actividad 03

-	Añade la letra que mas te guste para tu pagina desde Googlefonts y usala en tu pagina.




Hay muchas propiedades en CSS, [aquí](http://www.mclibre.org/consultar/htmlcss/css/css_propiedades.html) un listado de algunas. Dado el tiempo de esta actividad, solo repasaremos las vistas hasta ahora.

### Recapitulemos


Si has ido siguiendo las instrucciones, tu página ya debería verse mucho mejor desde cuando comenzamos, ademas, ya conocemos mucho mejor a nuestro compañer@.

Nos hemos ~~enamorado~~ divertido y hemos compartido con gente cool.

![](https://media.giphy.com/media/3o6UBhjHobLFgEmrJu/giphy-downsized.gif)


********


Nuestro código HTML y CSS debería verse algo así:


~~~html
<!DOCTYPE html>
<html>
<head>
  <title> Pizza de Pepperoni </title>
  <meta charset="utf-8">
  <link rel="stylesheet" type="text/css" href="miestilo.css">
  <link href="https://fonts.googleapis.com/css?family=Montserrat" rel="stylesheet">
</head>
<body>
  <div class="banner">
    <img class="img" src="http://littlecaesars.com.mx/portals/7/Images/HSMenu_HNR_Clasica_Pep_Hisp.png" alt="Deliciosa Pizza">
  </div>
  <div class="titles">
    <h1 class="violeta"> Pizza De Pepperoni </h1>
    <h2 class=" violeta">Hermosa y Deliciosa pizza, rapida y concisa.</h2>
  </div>

  <div class="parrafos">
    <p id="parrafo1"> Lorem ipsum dolor sit amet, consectetur adipisicing elit.
      Ipsam consequuntur omnis minima dolorem adipisci officiis enim
      optio tenetur quos aliquid, saepe, corporis dignissimos?
      Harum debitis veritatis voluptas, illum iste deserunt.
      Lorem ipsum dolor sit amet, consectetur adipisicing elit.
      Quo dolorem dignissimos expedita repellendus ducimus natus
      possimus, molestiae architecto, aperiam officiis, amet consequatur,
      nisi. Est accusamus eum quos natus architecto modi.</p>
      <p class="link"> Facebook de la Pizza <a href="https://www.facebook.com/LittleCaesarsPIzzaSanJoaquin/" target="_blank" >aquí </a></p>
      <a href="https://littlecaesars.com/en-us/"> <img src="images/pizzaLittle.jpg" alt="DeliciosaPizza"> </a>
    </div>

    <h3 class="violeta">Lugares favoritos</h3>
    <div class="ul">
      <ul>
        <li> La mesa del comedor</li>
        <li> La mesa de la terraza </li>
        <li> La mesa de la cocina </li>
      </ul>
    </div>

    <h3 class="violeta"> Ventajas y desventajas</h3>
    <div class="table">
      <table>
        <tr>
          <td> Ventajas</td>
          <td> Desventajas</td>
        </tr>
        <tr>
          <td> Es muy rica</td>
          <td> Engorda un poquito</td>
        </tr>
      </table>
    </div>
  </body>
  </html>
~~~


![](images/finalhtmlcss.png)


***No te preocupes si no tienes lo mismo, lo importante es que tu código pase por la validación de w3c  [validator](https://validator.w3.org/nu/#textarea) y que la página se vea como tú quieras.***


# Capítulo 3

## Desafío Amor Avanzado

Hasta el momento hemos aprendido muchas cosas acerca de las páginas web, pero nuestro viaje recién comienza, Ahora te enseñaremos acerca de un Framework llamado Bootstrap. Con el podremos hacer muchas mejoras a nuestros sitios webs.

Primero te explicaremos sus funcionalidades básicas y luego te desafiaremos a crear un Landing page desde una estructura de ejemplo.

Te invitamos a este desafío, por supuesto, los mentores estarán contigo para responder todas tus dudas.


# ¿Qué es Bootstrap?

Bootstrap es el framework más popular para el desarrollo de sitios responsive en la web, su código es compatible con SaSS y LESS por lo que podemos trabajar en nuestro preprocesador favorito sin problemas, además existen cientos de herramientas y plantillas que podemos integrar directamente con Bootstrap.

***Framework:*** Es un entorno o marco de desarrollo que estandariza herramientas para resolver problemas de índole similar.

**Responsive:** Se refiere a la facultad de que tu página se vea bien en cualquier dispositivo ( escritorio, tablets, teléfono).

***Sass:*** Syntactically Awesome Style Sheets, Facilita diversos aspectos de la creación de CSS al añadir mejoras de pre-procesamiento.

**Less** Leaner Style Sheets, Cumple la misma función que SaSS son herramientas que compiten entre ellas y sus funciones son muy similares pero la sintaxis cambia.

### Desventajas de Bootstrap

Utilizar Bootstrap completamente por defecto y no personalizarlo da un toque genérico a la página, hay muchos sitios construidos con este framework por lo que si no lo personalizamos se ve igual a los otros.

### Utilizando Bootstrap

>Observación: En esta guía se estará utilizando la versión **v4.0** de Bootstrap

Para integrar Boostrap a nuestro proyecto, hay dos formas, la primera es el utilizar un [CDN](https://www.bootstrapcdn.com/), la segunda descargando los archivos.

El CDN consiste simplemente en 2 archivos CSS y un archivo JS de bootstrap y Jquery, estos deben ser linkeados en la página HTML donde se utilizaran.

La descarga en cambio se divide en dos tipos, el precompilado donde vienen los CSS y JS directamente a utilizar y el source que viene con todo lo necesario para modificar el código fuente en LESS o SaSS dependiendo de la versión descargada.

Ejemplo de la estructura de directorio del código en LESS.

<pre>
bootstrap/
├── less/
├── js/
├── fonts/
├── dist/
│   ├── css/
│   ├── js/
│   └── fonts/
└── docs/
    └── examples/
</pre>

>Un CDN es una especie de página web para descargar contenido,
>pero está optimizada para la descarga rápida de assets, además
>que los CDN tienen servidores en diversas partes del mundo
>disminuyendo el impacto en la velocidad por distancia.


# Nuestro primer template con Bootstrap

Para facilitar la actividad, te entregamos un template HTMl donde se esta utilizando los archivos necesarios de Bootstrap a través de CDN.

~~~html
<!doctype html>
  <head>
    <!-- Required meta tags -->
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
    <!-- Bootstrap CSS -->
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/css/bootstrap.min.css" integrity="sha384-Gn5384xqQ1aoWXA+058RXPxPg6fy4IWvTNh0E263XmFcJlSAwiGgFAW/dAiS6JXm" crossorigin="anonymous">
    <title>Feliz día del Amor y la Amistad!</title>
  </head>
  <body>
    <h1>Gracias por venir a nuestra actividad!</h1>

    <!-- Optional JavaScript -->
    <!-- jQuery first, then Popper.js, then Bootstrap JS -->
    <script src="https://code.jquery.com/jquery-3.2.1.slim.min.js" integrity="sha384-KJ3o2DKtIkvYIK3UENzmM7KCkRr/rE9/Qpg6aAZGJwFDMVNA/GpGFF93hXpG5KkN" crossorigin="anonymous"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.12.9/umd/popper.min.js" integrity="sha384-ApNbgh9B+Y1QKtv3Rn7W3mgPxhU9K/ScQsAP7hUibX39j7fakFPskvXusvfa0b4Q" crossorigin="anonymous"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0/js/bootstrap.min.js" integrity="sha384-JZR6Spejh4U02d8jOt6vLEHfe/JQGiRRSQQxSfFWpi1MquVdAyjUar5+76PVCmYl" crossorigin="anonymous"></script>
  </body>
</html>
~~~

Para comprobar que Bootstrap funciona correctamente, debemos tener cuidado de que los archivos CSS y JS necesarios se encuentren donde se especifica. En nuestro template algunos se solicitan en el header y otros al final de body.

Para detectar si hay conflictos con las rutas que pusimos para los assets de Bootstrap podemos utilizar el inspector de elementos en el tab network, ahí podemos ademas escoger un sub tab como CSS, en caso de que un archivo no lo encuentre se mostrará en rojo, esto normalmente indica que la dirección apuntada es incorrecta.

![](images/inspector.png)

>Abrir el tab no es suficiente, hay que recargar la página con
>el tab network abierto para obtener la información.

Un error típico que podemos detectar de esta forma es la no inclusión (o la inclusión posterior) de Jquery, el javascript de Bootstrap depende de Jquery para su funcionamiento, por lo que no incluirlo o hacerlo después mostrará un error y no funcionará correctamente la capa de javascript de bootstrap.

En nuestro template ya esta incluido Jquery donde corresponde, antes de bootstrap. Por lo tanto puedes continuar.


# Comenzando con bootstrap

Hemos hecho una recopilación de los componentes básicos de Bootstrap, de todas formas te puedes guiar por su documentación oficial.
[Documentación](https://getbootstrap.com/docs/4.0/getting-started/introduction/)

## Jumbotron

Es una componente lightweight y flexible que permite mostrar texto o imágenes de forma resaltada en el sitio, ideal para la propuesta de valor del landing page

Ejemplo de básico de uso:

~~~html
<div class="jumbotron">
<h1> Yo estoy resaltado </h1>
</div>
~~~

![](images/jumbotron.png)


***Tips: observa la documentación de Bootstrap v4 para mas detalles.***

## Page Header
El page-header es otro componente liviano que sirve para títulos de secciones, además puede acompañarse con otro texto de clase small para acompañar el contenido.

![](images/page-header.png)

~~~html
<div class="page-header">
	<h1> Yo estoy resaltado <small> Yo no !! </small> </h1>
</div>
~~~


## Buttons

Si te diriges a la [documentación](https://getbootstrap.com/docs/4.0/components/buttons/) de Bootstrap,  te encontrarás con ejemplos de diferentes botones.

![imagen de botones](images/botones.png)

La documentación de Bootstrap es muy amigable como ves, te muestra el código y el ejemplo de cómo quedará.

Por ejemplo quiero ese botón verde (Succes), simplemente copiamos el código respectivo y pegamos en nuestro archivo HTML donde se quiera que aparezca.

~~~html
<button type="button" class="btn btn-success">Success</button>
~~~
Entonces que pasa aquí, se utiliza la etiqueta button (para que sepa que es un botón) se le dice que es de tipo botón y se le **agrega la clase** `btn` **y además la clase** `btn-success` para darle las propiedades de CSS que lo dejan como muestra la imagen.

Esta es una de las maravillas de Bootstrap! Puedes asignarle diseño, propiedades y más por medio de clases predeterminadas por Bootstrap.


## Container

Es un contenedor que da margen de los bordes del sitio, bastante útil a la hora de mostrar texto.

![](images/container.png)

En la imagen vemos dos párrafos uno con container y el otro sin,  el que tiene container tiene margen respecto a los bordes de la página.

~~~html
 <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
 	tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
 	quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
 	consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse
 	cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non
 	proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
</p>
<div class="container">
	<p>Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
	tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
	quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
	consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse
	cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non
	proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
	</p>
</div>
~~~



## Jumbotron y Containers

Un jumbotron puede ir dentro de un container y un container puede ir dentro de un jumbotron **No es lo mismo un container dentro de un jumbotron que un jumbotron dentro de un container**, esto es lo que estudiaremos a continuación.

![](images/jumbo-cont.png)

Al ponerle un container el texto se alínea mejor, y aunque esté dentro de un jumbotron un container, y otro container esté fuera sin jumbotron, veremos que ambos textos quedan bien alineados.

![](images/jumbo-cont2.png)

~~~html
	<div class="jumbotron">
		<div class="container">
			<h1> Yo soy un título dentro de un jumbotron y dentro de un container </h1>
		</div>
	</div>

	<div class="container">
	Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
	tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
	quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
	consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse
	cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non
	proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
	</div>
~~~

Algo muy distinto sucede cuando ponemos el jumbotron dentro de un container.

![](images/cont-jumbotron.png)

Como vemos en la imagen nos damos cuenta que ahora el jumbotron no está pegado al borde de la página, y además ahora es el borde del jumbotron el que está alineado con el texto de los otros containers.

> ##### **¿Cuál método utilizar?** <br>
> Depende de lo que se quiera hacer, todos los métodos previos son correctos


## Imágenes responsive

Con Bootstrap v4 podemos convertir una imagen responsive solo con agregar la clase img-fluid.

~~~html
<img src="..." class="img-fluid" alt="Responsive image">

~~~

`img-fluid` hace que la imagen tenga un **max-width** del 100%, recordemos que la diferencia entre width y max-width es que width altera el tamaño de todos los elementos mientras que **max-width** como dice su nombre afecta solo a los elementos que tienen un tamaño mayor que el espacio que tienen disponible.

![](images/img-responsive.png)

Además hay clases que pueden ayudarnos a darle formas a las imágenes.

~~~html
<img src="..." alt="..." class="rounded">
<img src="..." alt="..." class="rounded-circle">
~~~

>##### **width vs max-widht** <br>
> Debemos tener cuidado con la propiedad max-width porque esta
> no cambiará el tamaño de las fotos que son menores al espacio
> disponible.

## Thumbnails

Los thumbnails permiten agregar estilos y bordes de forma sencilla a las imágenes.

~~~html
<div class="thumbnail" style="width:300px">
		<img src="assets/desafiolatam.jpg" class="img-responsive img-rounded">

		<p>
		Lorem ipsum dolor sit amet, consectetur adipisicing elit, sed do eiusmod
		tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam,
		quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo
		consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse
		cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non
		proident, sunt in culpa qui officia deserunt mollit anim id est laborum.
		</p>
		<button type="" class="btn btn-primary"> Comprar</button>

	</div>
~~~

![](images/thumbnail.png)

> ##### **To thumbnail or not to thumbnail**
> La clase thumbnail puede aplicarse directamente a la imagen
> a un div superior, en caso de aplicarse a la imagen
> perderemos otras propiedades como el redondeado y no podremos
> poner otro contenido dentro del thumbnail.

## NavBar

En la [documentación](http://getbootstrap.com/) de Bootstrap , te diriges a `Components` , y ahí encontrarás varios componentes entre ellos ejemplos de  barra de navegación. (En menú derecho `Navbar`)

![nav](images/navbar.png)

~~~html
<nav class="navbar navbar-expand-lg navbar-light bg-light">
  <a class="navbar-brand" href="#">Navbar</a>
  <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
    <span class="navbar-toggler-icon"></span>
  </button>

  <div class="collapse navbar-collapse" id="navbarSupportedContent">
    <ul class="navbar-nav mr-auto">
      <li class="nav-item active">
        <a class="nav-link" href="#">Home <span class="sr-only">(current)</span></a>
      </li>
      <li class="nav-item">
        <a class="nav-link" href="#">Link</a>
      </li>
      <li class="nav-item dropdown">
        <a class="nav-link dropdown-toggle" href="#" id="navbarDropdown" role="button" data-toggle="dropdown" aria-haspopup="true" aria-expanded="false">
          Dropdown
        </a>
        <div class="dropdown-menu" aria-labelledby="navbarDropdown">
          <a class="dropdown-item" href="#">Action</a>
          <a class="dropdown-item" href="#">Another action</a>
          <div class="dropdown-divider"></div>
          <a class="dropdown-item" href="#">Something else here</a>
        </div>
      </li>
      <li class="nav-item">
        <a class="nav-link disabled" href="#">Disabled</a>
      </li>
    </ul>
    <form class="form-inline my-2 my-lg-0">
      <input class="form-control mr-sm-2" type="search" placeholder="Search" aria-label="Search">
      <button class="btn btn-outline-success my-2 my-sm-0" type="submit">Search</button>
    </form>
  </div>
</nav>
~~~

*Este código es la barra de navegación de la imagen*

Al ser barra de navegación, pego el código al inicio de nuestro código, luego de empezado el `<body>`


## La Grilla

Bootstrap contiene una grilla que permite crear layouts de forma muy sencilla.

Para utilizar una grilla lo primero que debemos crear es un row (fila)


~~~html
<div class="row">
</div>
~~~

Dentro de este row dispondremos de 12 columnas virtuales que podemos agrupar a nuestro antojo para poner contenido.

![imagen de grillas](images/grillas.png)


~~~html
<div class="row">
  <div class="col-md-1">.col-md-1</div>
  <div class="col-md-1">.col-md-1</div>
  <div class="col-md-1">.col-md-1</div>
  <div class="col-md-1">.col-md-1</div>
  <div class="col-md-1">.col-md-1</div>
  <div class="col-md-1">.col-md-1</div>
  <div class="col-md-1">.col-md-1</div>
  <div class="col-md-1">.col-md-1</div>
  <div class="col-md-1">.col-md-1</div>
  <div class="col-md-1">.col-md-1</div>
  <div class="col-md-1">.col-md-1</div>
  <div class="col-md-1">.col-md-1</div>
</div>
<div class="row">
  <div class="col-md-8">.col-md-8</div>
  <div class="col-md-4">.col-md-4</div>
</div>
<div class="row">
  <div class="col-md-4">.col-md-4</div>
  <div class="col-md-4">.col-md-4</div>
  <div class="col-md-4">.col-md-4</div>
</div>
<div class="row">
  <div class="col-md-6">.col-md-6</div>
  <div class="col-md-6">.col-md-6</div>
</div>


~~~

Dentro de cada una estas columnas podemos agregar todo el contenido que queramos y este contenido se adaptará dentro de las columnas.

Si vamos agregar texto o imágenes sería bueno envolver las columnas en un container. (para agregarles márgenes)

~~~html
<section class="container">
	<div class="row">
		<div class="col-md-6">
		</div>
		<div class="col-md-6">
		</div>
	</div>
</section>
~~~

![](images/columns.png)

Entonces resumiendo: Se empieza por añadiendo la clase `.row`, esto creará un bloque horizontal el cual va a contener 12 columnas.

### Utilizando columnas para dispositivos específicos

Es bueno analizar de que palabras vienen los nombres de reglas de estilo que provee Bootstrap:


<table>
<tr>
<td> col-xs-*</td>
<td> e(x)tra (s)mall</td>
<td> dispositivos con pantalla pequeña, móviles</td>
</tr>

<tr>
<td> col-sm-* </td>
<td> (sm)all</td>
<td> dispositivos con resolución mayor o igual 768px, tablets</td>
</tr>

<tr>
<td> col-md-*</td>
<td> (m)e(d)ium</td>
<td> dispositivos con resolución mayor o igual a 992px, notebooks  </td>
</tr>

<tr>
<td> col-lg-*</td>
<td> (l)ar(g)e </td>
<td> resolución mayor o igual a 1200px , computador de escritorio </td>
</tr>

</table>

*Donde* ` * ` es el número de columnas.


### Mobile First

Bootstrap  está construido sobre el concepto de mobile first, esto quiere decir que el primer principio es que la página debe adaptarse al contenido, para eso lo que hace bootstrap es utilizar media queries y desarmar la grilla disponiendo de todo el ancho de la página para presentar su contenido.

A menos que especifiquemos lo contrario.

¿En que repercute esto?

Al disminuir el ancho de la página (o al verla desde un teléfono) veremos que la grilla se rompe.

<img src="images/9 mobile-first.png">

### Media queries

La grilla contiene las siguientes media queries que debemos considerar:

~~~css
/* Extra small devices (phones, less than 768px) */
/* No media query since this is the default in Bootstrap */

/* Small devices (tablets, 768px and up) */
@media (min-width: @screen-sm-min) { }

/* Medium devices (desktops, 992px and up) */
@media (min-width: @screen-md-min) { }

/* Large devices (large desktops, 1200px and up) */
@media (min-width: @screen-lg-min) { }
~~~

***
***
***



### ¿Mucha información?, ¡vamos tú puedes¡. Si llegaste hasta acá ya eres genial, Ahora vamos plantearte un Desafío.

### Desafio Landing en Bootstrap.

-	Crea una nueva página y copia el template de bootstrap que te facilitamos.
-	Añade un Jumbotron a tu nueva página con un título con una frase acerca de aprender a hacer una web o cuanto te gusto tu compañer@.
- Añade un container con un título, subtítulo con los mensajes que quieras.
-	Añade tres parrafos abajo del Jumbotron cada uno en un container diferente.
-	Añade 3 images sobre cada párrafo, haz se sean responsive. Puedes usar thumb-nails si prefieres.
- Añade un button a cada container.
- Añade un Navbar a tu página.
- Has que tu página sea responsive utilizando las grillas de bootstrap
- Desarrolla todo tu potencial, recuerda que puedes añadir un archivo de CSS aparte para personalizar aun mas tu pagina. No te limites.


Si lograste seguir todos los pasos tú pagina web debería ser como esta.

[Ejemplo](https://himuravidal.github.io/LandingLoveExample/)


***¡ Mucho Éxito !***


## Si terminaste, Apoya a tus compañeros para que puedan aprender y mejorar sus páginas.

### ~~No olvides pedir su número.~~

![](https://media1.tenor.com/images/4f586b8d5cdc536ada9889b58e6d91e8/tenor.gif?itemid=5131908)
##!Gracias por participar¡.
