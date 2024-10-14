# Una API sencilla
En el Capítulo 1, mostré un sitio web de microblogging muy sencillo ubicado en **http://www.youtypeitwepostit.com/**. Resulta que también diseñé una API programable para este sitio web. Puede verla en vivo en **http://www.youtypeitwepostit.com/api/**

La API ideal tendría las mismas características que hacen que la World Wide Web sea fácil de usar. Como desarrollador, usted podría descubrir cómo usarla, comenzando con nada más que una URL que vio en un cartel publicitario.

Desarrollemos esa fantasía para ver cómo funcionaría. Primero, haría que su cliente programable realice una solicitud GET para la URL del cartel publicitario, el equivalente a ingresar esa URL en la barra de direcciones de su navegador web. Su cliente tomaría el control a partir de allí, examinando la respuesta para ver cuáles son las opciones disponibles. Seguiría enlaces (no necesariamente enlaces HTML), llenaría formularios (no necesariamente formularios HTML) y, finalmente, realizaría la tarea que le propuso.

 Este libro no nos va a llevar hasta ese objetivo. Hay problemas que no puedo resolver con un libro: problemas relacionados con la ausencia de estándares, problemas con el nivel actual de soporte de herramientas y el hecho brutal de que las computadoras simplemente no son tan inteligentes como los seres humanos. Pero podemos avanzar mucho hacia ese objetivo, mucho más de lo que crees. 

Como dije, hay una API de microblogging real en **http://www.youtypeitwepostit.com/api/**. Si te sientes aventurero, sigue adelante y escribe algo de código para hacer algo con esa API. Mira cuánto puedes descifrar, sin saber nada más que esa URL. Ya has hecho esto antes con sitios web: todo lo que sabías era la URL de la página de inicio y la descifraste. ¿Hasta dónde puedes llegar con una API? 

Si no te sientes aventurero o no tienes mucha experiencia escribiendo clientes para API web (o estás leyendo este libro en un futuro lejano y ya no estoy alojando ese sitio web), lo repasaremos juntos.  El primer paso es obtener una representación de la página de inicio de la API.
