
# Observaciones

Cami, felicitaciones por tu trabajo. Tu portfolio se ve muy lindo; me alegra ver que en general seguiste las pautas del diseño solicitado pero a la vez le diste tu toque personal. Me gustan muchisimo las imagenes e iconos elegidos, la eleccion de colores y muy especialmente los efectos en el foco y el hover. Se nota, y aprecia, que hubo mucho trabajo para lograr una web que te represente y que sea amable con el usuario.

Me da la impresión de que te enfocaste en que la web se viera lo mejor posible, y en el camino descuidaste un poco el lado del código. Tu HTML, tu css, tu estructura del proyecto, están muy desprolijos. Me parece bien, ante la falta de tiempo, privilegiar lo que finalmente verá el usuario, pero nunca olvidemos que como desarrolladoras, nuestro código es una parte importante y por más bien que se vea una página, nuestro código también debe tener estándares altos. Queremos que sea tan fácil para nuestros colegas entender nuestro código como para los usuarios entender nuestra web. Creo que ese es el mayor factor que te juega en contra en este TP, y el principal aspecto que te voy a pedir que mejores en futuros trabajos. 

Te dejo varios comentarios para mencionar cositas puntuales. Como comentamos en clase, este trabajo no se hace para que constates conocimientos, sino para que aprendas: en ese sentido, mi intencion es que estos comentarios te sirvan para aprender, mejorar tu codigo a futuro e ir apreciando mejor qué se espera de nosotras como desarrolladoras front end.

## Estructura correcta de documento HTML

Cumplido, tu HTML esta bien, formas correctamente las etiquetas y la estructura esta correcta. Ocasionalmente usas mal las mayúsculas, por ejemplo escribís `<P>` en lugar de `<p>`. No usamos mayúsculas en HTML, ya que distintos navegadores las leen de maneras diferentes y puede ocasionar errores. A veces te olvidas las comillas en la clase, como aqui: `<div class=tercerparte>`. 

No importas todas las tipografias que utilizas, por lo que yo en mi computadora veo por ejemplo muchas de tus letras como Times New Roman. Eso afea un poco tu web, y es una lástima porque no se puede apreciar del todo tu hermoso diseño. No podes asumir que todos los usuarios tienen las tipografias que queres que vean: toda tipografia que uses debe estar importada en HTML. 

## Respeta la consigna 

- El portfolio cuenta con las secciones solicitadas 

Cumplido. 

- Al clickear en los links de navegación, debe llevar a la sección correspondiente

Cumplido. 

- Al clickear en los links de contacto, debe llevar a la página externa correspondiente 

No cumplido. No es necesario que agregues tus propias redes si es algo que preferís no hacer, pero
cualquier link a una web externa hubiera servido para cumplir la consigna.

- El portfolio debe tener un diseño responsivo y verse correctamente en distintos dispositivos 

Cumplido, con la excepcion de un scroll horizontal muy molesto en movil. Quiza ni lo hayas notado, pero eso ocurre cuando hay un elemento que esta rebalsando el ancho del body. En este caso, se trata del div "dos" de tu formulario, que mide 420px, un tamaño mas grande que el de los celulares mas pequeños. 

- El portfolio debe estar deployado y ser accesible desde una URL 

Cumplido. 

- El repositorio en GitHub debe tener un readme adecuado 

No cumplido. El readme es muy importante para tus lectores! 

### Respeta el diseño dado 

Cumplido, es muy destacable la atención al detalle que demostrás acá. 

### Buena estructura de proyecto 

Usás muchas imágenes en tu proyecto, y viéndolo a primera vista en github no es tan fácil ver cuáles son los archivos principales. Siempre que uses imágenes locales, como en este caso, agregalas a una carpeta que se llame por ejemplo "imgs", "imagenes" o "assets". De esta manera solo los archivos principales - html, readme y css - son los que están en la carpeta principal. La excepción a esta regla es el favicon, que siempre debería ir en la carpeta principal. 

### Código bien indentado 

No cumplido. Sé que es difícil entender la importancia a esta altura, pero la indentación adecuada es realmente importantísima para poder leer tu código. Muchas veces se hace absolutamente imposible saber qué está adentro de cada cosa, y leer tu HTML en particular es muy, muy difícil. Recordá que haciendo click derecho + "formatear documento" podés corregir rápidamente el tabulado, y esto también te va a ayudar a encontrar rápidamente errores como etiquetas mal cerradas. 

Cada vez que una etiqueta esta adentro de otra, debemos dejar dos o cuatro espacios (eso va a preferencia de cada una). Visual Studio Code va a tratar de ayudarte en eso. Por favor, prestale atención para la próxima vez. 

### Comentarios que permiten mejorar la legibilidad del código 

No cumplido, no hay ninguno en HTML y muy poquitos en CSS. Tu código es muy difícil de seguir a veces. 

### Uso correcto de etiquetas semánticas 

En general usas bien las etiquetas semánticas. Me llama la atención que hayas usado `div` para tus tarjetas: deberían ser todas `article`. El "header" no es un header: es el nav. El header es la seccion que sigue, en donde saludas a tus usuarios. 

### Buenos nombres de clases 

No está cumplido. Luego del tabulado, es el factor que más atenta contra la calidad de tu código. Es muy dificil entender tu CSS porque no hay manera de saber a que se refiere cada cosa: hay que estar chequeando a cada rato el HTML para poder entenderlo. 

Cuando decimos que un nombre de clase debe ser descriptivo, lo decimos en un sentido funcional: qué rol cumple este elemento en el código. Los colores de los elementos, su forma, su estilo, su posición, todas esas cosas pueden cambiar y efectivamente cambian todo el tiempo en las webs que hacemos. El botón que hoy es violeta mañana será azul; la sección que estaba primera mañana estará tercera. Por lo tanto esos factores sos no son buenos descriptores, y no deberían ser parte de nuestros nombres de clases.
Otros nombres de clases que usas directamente no tienen sentido. Entiendo que es dificil pensar buenos nombres, y es algo con lo que todos renegamos alguna vez, pero es importante que te vayas acostumbrando a darle más atención a eso. "Divname" no me dice nada. "Contenedor", tampoco. "Uno", "Dos", es imposible saber qué son. Son tarjetas de proyectos, son secciones en el form. Clases como "footerredes" y "footerredes2" casi que garantizan una confusión, para vos como desarrolladora y para cualquier lector que quiera saber como hiciste tu código. 

Usás mayúsculas en tus nombres de clases, lo que no es buena práctica dado que distintos navegadores leen distinto las mayúsculas, y no separas las distintas palabras con guion. Una clase debería tener el formato "contenedor-tarjeta" o "tarjeta-proyectos". 

### Código CSS bien estructurado 

Cumplido a nivel formal. Noto muchos estilos innecesarios o confusos, que te voy indicando en tu archivo de css. 

### Reutilización de estilos 

En general está cumplido, se nota el esfuerzo por usar clases reutilizables. 

### Cumple con criterios básicos de accesibilidad 

- Los colores tienen un contraste adecuado 

No cumplido en varios casos, por ejemplo con el color de fondo #4c9791 y el texto de color negro. Siempre chequeá el contraste con herramientas como https://webaim.org/resources/contrastchecker/

- Las imágenes tiene el atributo `alt` que corresponde 

Algunas de tus imagenes no tienen alts, como las de Mis Proyectos. Los alts que si tenes lamentablemente no sirven, ya que son textos que un lector de pantalla debe leer y poder pronunciar. Imaginate que va a entender el usuario si el lector de pantalla trata de leer "imagencss" (va a leerlo como imagenks, no como imagen ce ese ese). Aunque el lector pudiera leerlo correctamente, el usuario no vidente no va a poder entender qué es eso. No es necesario decirle que es una imagen, eso ya se lo dice el lector de pantalla, es necesario describirla adecuadamente. "Icono de la tecnologia CSS". 

- Los íconos y elementos que no presentan texto agregan la información correspondiente por otros medios (etiquetas aria, texto oculto) 

No cumplido, por ejemplo en los links a redes sociales de tu footer. Necesitan un aria. 

- Los íconos y elementos que no necesitan ser anunciados por un lector de pantalla tienen la etiqueta aria
correspondiente 

No cumplido. 

- Commits con mensajes adecuados 

No cumplido, aunque entiendo que tuviste problemas ahi, por lo que no lo considero para la nota final. 

- Cuenta con un favicon

No cumplido

### Nota: 8
