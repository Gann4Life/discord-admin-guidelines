# Administración general de servidores en discord
Administrar servidores es una tarea que debe ser llevada a cabo con estrategia y la mayor optimización posible. Deben saber como ahorrarse trabajo haciendo las cosas de la forma más óptima posible para prevenir confusiones y estancamientos.

# Introducción
* Es importante interpretar y entender cómo van a ingresar los usuarios y qué es lo primero que van a ver.
* No queremos estresarlos (a los usuarios) mostrándoles tanta información visual de golpe, tengan en cuenta que esto es como si manejaran su propia red social.
* De ser posible, guiar a los usuarios por un "camino" o con algo que les ayude a entender como funciona todo. Canales o foros que contengan información, consultas y respuestas sirven, incluso para mantener información o cambios actualizados.

# Canales
* Ningún canal debe tener asignado roles específicos. Siempre sincronizar con las categorías para facilitar la administración.
* Cada categoría debe tener un propósito al igual que cada canal de texto, asegurarse de que no hayan canales con conceptos duplicados antes de hacer canales nuevos.
* Todos (@everyone) deben tener la posibilidad de interactuar con lo básico (enviar mensajes y ver canales)
* Los canales deben estar organizados por prioridad de actividad, aquellos que más actividad tengan o más importantes sean, deben estar más arriba para facilitar el uso a los miembros del servidor.
* En caso de querer implementar un sistema de verificación, implementar un rol específico que se agregue a los usuarios cuando entren para evitar que vean canales, en lugar de usar a @everyone para ello. Modificar los permisos base de @everyone causará problemas y conflictos entre roles, por lo que dificulta la administración de los mismos.
* Existen tres categorías importantes que se muestran en la gran mayoría de servidores.
	* **Staff:** Los canales de staff deben estar arriba de todo para facilitar la comunicación y que estén a mano, ya que los usuarios que no son administradores no lo ven, no interfiere en su experiencia.
	* **Información:** Es el lugar donde se mostrarán canales de sólo lectura, por lo tanto la categoría debe tener los permisos asignados para que @everyone no envíe mensajes.
	* **General:** Una categoría de interacción general, el nombre de la categoría puede tener un título temático o diferente de simplemente "general". Se puede incluir un chat de voz para quienes deseen simplemente estar en llamada y hablar de cualquier cosa, o lo que la temática propone.
	* **Otro:** `pensando...`

# Roles
* Todos (@everyone) deben tener la posibilidad de interactuar con lo básico (enviar mensajes y ver canales)
* Todo rol estético o de etiqueta, *nunca* debe modificar permisos si no es necesario. Esto debe mantenerse así para que los roles que **si** requieran modificar permisos, puedan hacerlo sin chocar con los permisos de otros roles. 
	* Ejemplos de roles que modifican permisos: **Moderador**, **Administrador**, **No verificado**.
	* Ejemplos de roles estéticos: **Rojo**, **Azul**, **Violeta**, **Rosa**, **Naranja**.
	* Ejemplos de roles de etiqueta: **Gamer,** **Artista**, **Streamer**, **Lolero**.
* Para evitar que los nuevos usuarios vean canales, implementar un rol de tipo `@NoVerificado` que no tenga permisos de ver canales. Estos permisos deben ser asignados en cada categoría. **Recordatorio**: no en cada *canal*, en cada *categoría*. Los canales deben sincronizarse con la categoría *siempre*. Pueden haber excepciones si es para sólo un canal o dos, mientras no complique la administración o mantenimiento futuro.
* Los administradores generalmente tienen permisos de todo tipo y se encargan de la estructura del servidor y elementos más técnicos por así decirlo.
* Los moderardores generalmente se encargan de anunciar o ayudar con la administración, verificando que todo esté correcto a la par de los administradores, pero sin necesariamente trabajar en lo mismo. La idea es esa, dividirse tareas. No deben tener permisos de administrador, en su lugar, asignar permisos específicos. Por ejemplo: Puede kickear, usar algún que otro comando de bot, o mover canales.
* Existen otros roles de moderación que pueden ser agregados pero que no siempre son necesarios.
* Todos deben ser de confianza, y no en el sentido amistoso; es necesario que los miembros del staff tengan un mínimo de sentido común para evitar que sus cuentas sean robadas y se utilicen con intenciones maliciosas. Algunas acciones comunes que se realizan tras robar o hackear una cuenta de discord son: Enviar enlaces falsos de nitro gratuito a todos los contactos, servidores y en todos los canales, borrar canales, banear o kickear a todos los miembros, bloquear todos los canales, y demás. Una buena forma de prevenir es evitar descargas de fuentes desconocidas, software crackeado, revisar bien las URL de las páginas a las que acceden y evitar caer en técnicas como phishing a través de los correos. Quienes tengan curiosidad, pueden revisar si alguna de sus cuentas está comprometida con la siguiente página: [Have I Been Pwned: Check if your email has been compromised in a data breach](https://haveibeenpwned.com/).

# Bots
* Cada bot debe tener su propósito definido. Muchos bots tienen funcionalidades iguales o similares y lleva a confusiones para ambas partes: administradores y usuarios.
* Deben haber la menor cantidad de bots posibles, es muy común tener a todos los bots con permisos de administrador pero si uno de ellos resulta vulnerado (hackeado o robado), que no les sorprenda entrar un día al servidor y verlo vacío. (¿Qué pasó? Uno de los santos bots eliminó todos los canales.)
* Con respecto al punto anterior, deben asegurarse que los bots que inviten estén verifiados y sean de confianza, o que no hayan tenido algún historial de actividad extraño.
* Al momento de invitar a un bot, saquenle todos los permisos que pida para evitar que genere un rol extra, un rol basura que ocupa espacio y no se puede borrar. Así una vez lo invitan, le asignan el rol que deseen. (Por lo general, un simple @Bot basta.)

# Estética
* Mientras la estética sea uniforme en todo el servidor, casi cualquier cosa es válido.
* Es necesario que todos los canales sean fáciles de leer y con la menor cantidad de carácteres posibles.
* Recordar que discord es multiplataforma, por lo que debe ser legible para todos los dispositivos.
* Evitar nombres largos a tal punto de... (Que queden sin poder terminar de leer)
 <img src="img/Pasted image 20230624135626.png">

* Algunos ejemplos de estética uniforme:
	* <img src="img/Pasted image 20230624140936.png">
	* <img src="img/Pasted image 20230624140946.png">
	* <img src="img/Pasted image 20230624141016.png">
	* <img src="img/Pasted image 20230624141059.png">
	* <img src="img/Pasted image 20230624141105.png">
	* <img src="img/Pasted image 20230624141222.png">
