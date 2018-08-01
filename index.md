Enfermera Joy es un bot de Telegram especializado en gestionar grupos de Pokémon GO en Telegram.

Puedes pedir ayuda en el grupo [@enfermerajoyayuda](https://t.me/enfermerajoyayuda) y estar informado de las novedades en el canal [@enfermerajoynoticias](https://t.me/enfermerajoynoticias).

1. [Ayuda para entrenadores](#ayuda-para-entrenadores)
   1. [Registrarse en el bot](#registrarse-en-el-bot)
   2. [Código de Entrenador](#friend-id)
   3. [Registrarse en el bot](#tablas)   
   4. [Más ayuda](#más-ayuda)
2. [Ayuda para administradores](#ayuda-para-administradores)
   1. [Añadir el bot a un grupo o canal](#añadir-el-bot-a-un-grupo-o-canal)
   2. [Configuración](#configuración)
   3. [Modo niñero](#modo-niñero)
   4. [Zona horaria](#zona-horaria)
   5. [Otros comandos exclusivos para administradores](#otros-comandos-exclusivos-para-administradores)
3. [Reglamento General de Uso del Bot](#reglamento-general-de-uso-del-bot)

## Ayuda para entrenadores ##

### Registrarse en el bot ###

El registro puede ser obligatorio en algunos grupos (todo depende de la configuración del grupo), pero para poder interactuar con el bot, es imprescindible el registro.
Registrarte te permite disfrutar de todas las funcionalidades del bot, como por ejemplo preguntar por otros usuarios, solicitar información de los Pokémon y muchas más funcionalidades que llegarán en un futuro.

Para registrarte tienes dos opciones:

1. En un privado con [@NurseJoyBot](https://t.me/NurseJoyBot), escribe el comando `/register` y comenzarás el proceso de registro y validación. El proceso es automatizado y te pedirá que hagas una captura de pantalla del juego con unas condiciones.

2. Si estás registrado y validado con [@detectivepikachubot](https://t.me/detectivepikachubot), puedes escribir el comando `/profile` y reenviar la respuesta a [@NurseJoyBot](https://t.me/NurseJoyBot). Este método, sirve tanto para registrarse como para subir de nivel.

### Más ayuda ###

Si necesitas ayuda que no se encuentre en este manual, puedes preguntar en [@enfermerajoyayuda](https://t.me/enfermerajoyayuda). Si estás administrando un grupo o un canal, mira más abajo para ver la ayuda para administradores.


## Ayuda para administradores ##

De aquí en adelante, [@NurseJoyBot](https://t.me/NurseJoyBot) pasará a ser *el bot*.

### Grupos ###

El soporte de [@NurseJoyBot](https://t.me/NurseJoyBot) por el momento solo está probado en **grupos y supergrupos**. En un futuro, contará con soporte en canales.

En **grupos** el bot ya se puede utilizar tan pronto entra al grupo y envía un saludo. Conviene configurarlo, no obstante. Ten cuidado porque, si una vez añadas el bot conviertes el grupo a supergrupo, tendrás que volver a configurarlo. Un supergrupo es la mejor opción en la mayoría de los casos.

### Añadir el bot a un grupo ###

Para **añadir el bot a un grupo** tienes tres alternativas:

1. Vete al perfil de [@NurseJoyBot](https://t.me/NurseJoyBot). En el menú, selecciona la opción *Añadir a un grupo* y escoge el grupo de la lista.

2. Pulsa en [este enlace](https://telegram.me/NurseJoyBot?startgroup=true) en un dispositivo donde tengas Telegram instalado.

3. Puedes intentar añadirlo como un contacto más desde el grupo con su alias `@NurseJoyBot`, pero en versiones recientes de Telegram hay problemas usando este método.


### Configuración ###

Para hacer la configuración básica del bot utiliza el comando `/settings`. La configuración está dividida en varios apartados:

1. **Chistes**. Activa o desactiva los chistes, refranes y cualquier cosa que pueda hacer que el bot hable sin que nadie lo invoque. Opción desactivada por defecto.

2. **Juegos**. Permite o no que los usuarios ejecuten los comandos para jugar con el bot. Opción desactivada por defecto.

3. **Modo enfermera**. Borra todos los mensajes a excepción de los enviados por administradores. Mira el [apartado del modo enfermera](#modo-enfermera) para más información. Opción desactivada por defecto.

4. **Tipo de grupo**. Cuenta con cinco opciones. Mira el [apartado del tipo de grupo](#tipo-de-grupo) para más información. Opción desactivada por defecto.

5. **Configuración de los avisos**. Si está activada, esta opción hace que el bot reflote todas las incursiones activas cada 5, 10, 15 o 30 minutos. Las incursiones se consideran activas si falta **menos de una hora y media para que comiencen** o si acaban de comenzar (una vez comenzadas, se reflotarán una única vez). Opción desactivada por defecto.


### Modo enfermera ###

El modo enfermera evita que la gente hable en un grupo, borrando todos los mensajes que pongan los usuarios (no los administradores).

El comando `/settalkgroup` permite definir un grupo para hablar. Si está el modo niñero activado, el bot recordará el enlace al grupo para hablar cada vez que hable alguien. Por ejemplo:

    /settalkgroup @enfermerajoyayuda
    /settalkgroup https://t.me/joinchat/XXs3XkzYsXXxnvbtxxe11x

### Tipo de grupo ###

Por defecto, los grupos 

### Zona horaria ###

El bot reconoce la hora que escriben los usuarios y hace operaciones con ellas, por lo que es importante que la hora que utilice el bot se corresponda con la hora real de tu grupo.

Para establecer la zona horaria correcta se debe utilizar el comando `/settimezone` con la zona horaria correspondiente como parámetro siguiendo el formato del [listado de zonas horarias de la IANA](https://en.wikipedia.org/wiki/List_of_tz_database_time_zones). Por ejemplo:

    /settimezone Europe/Madrid
    /settimezone Atlantic/Canary

### Otros comandos exclusivos para administradores ###

Para revertir la cancelación de una incursión puedes usar el comando `/descancelar`. Se utiliza exactamente igual que el `/cancelar`, pero sobre incursiones canceladas.

Un administrador siempre puede cancelar incursiones con el comando `/cancelar`, aunque sean antiguas. Normalmente, un creador de incursión solo puede cancelar incursiones que no sean más antiguas de tres horas.

Para reflotar todas las incursiones activas una vez, sin necesidad de usar el reflotado automático, se puede usar el comando `/reflotaractivas`. También se pueden reflotar todas las incursiones, incluídas las EX que transcurrirán dentro de varias horas o días, con `/reflotartodas`.


## Reglamento General de Uso del Bot ##

El siguiente punto, detalla la normativa a cumplir en caso de registrarse en el bot. El desconocimiento de la misma no exime al usuario de su aplicación pues todas las normas aquí recogidas son de sentido común. 

Este bot no puede ser utilizado en grupos o canales que promueven el uso de trampas en el juego. Si bien no se puede evitar que sea utilizado casi por cualquiera, el bot implementa algunas medidas anti-trampas que detectan determinados comportamientos que pueden llevar a un baneo preventivo.

En caso de formar parte de un grupo en el cual se encuentre [@NurseJoyBot](https://t.me/NurseJoyBot) y conozcas a un usuario o administrador que no cumpla alguna de las normas, se deberá comunicar mediante correo electronico a la dirección [reportes@qwert1.es](mailto:reportes@qwert1.es). Cualquier sancion aplicada será debatida entre los miembros del staff del bot, apelable en la siguiente dirección de E-mail: [apelaciones@qwert1.es](mailto:apelaciones@qwert1.es).

### Normas de Enfermera Joy ### 

- 🔞 Está totalmente prohibido enviar material sensible.
- ⛔️ Está **COMPLETAMENTE PROHIBIDO** solicitar y/o aportar información relativa a otro jugador en cualquiera de los grupos oficiales del bot o bien por privado a cualquier miembro del staff. En caso de producirse esta situacion, los administradores se reservan el derecho de banear **definitivamente** la cuenta del entrenador.
- 😈 Nunca difames, abuses, hostigues, dañes, acoses, amenaces o violes de cualquier manera los derechos legales (incluidos los derechos de privacidad y publicidad) de los demás.
- 👺 Se ruega evitar generar discusiones o debates *interminables*, o que no aporten información útil al grupo, incluyendo temas de hacks, trampas, emuladores o similares.
- 😊 Ante todo, ¡fomenta el buen rollo! El grupo no es restrictivo, no tengas miedo de preguntar o conversar sobre el juego. Pero ten cuidado con las cosas o "bromas" que digas, puedes ofender a alguien.
- 📩 Se considera **flood** el hecho de repetir contínuamente palabras, hacer *cadenas* de contenido multimedia o comandos (enviar muchas fotos o stickers seguidos), provocando molestias al grupo con contenido innecesario. 
- 🌍 Normalmente el usuario estará unido en los grupos cercanos a su ubicación, o que suela frecuentar. Si un usuario es avistado en varios grupos de diferentes ubicaciones a la vez, podría ser expulsado de todos ellos por sospechas de posibles trampas. Se entiende que si un usuario se va de vacaciones a otro lugar, no es necesario abandonar los grupos de su ubicación, y se valorará este motivo.
- 🤐 Está **COMPLETAMENTE PROHIBIDO** solicitar y/o aportar información relativa a otro jugador en cualquiera de los grupos oficiales del bot o bien por privado a cualquier miembro del staff. En caso de producirse esta situacion, los administradores se reservan el derecho de banear **definitivamente** la cuenta del entrenador.


### Normas del Entrenador ###

Es **obligatorio** que todos los usuarios que están en el grupo, cumplan las [Normas del Entrenador](https://support.pokemongo.nianticlabs.com/hc/es/articles/221993967) de Niantic.

Obviando la parte de comportamiento ético como personas, se detalla que jugar de las siguientes formas (pero no únicamente éstas) se considera **trampa**, llevando a la expulsión del grupo:
- Usar software modificado o no oficial
- Compartir cuentas, jugar con cuentas de otros jugadores en un mismo móvil
- Usar herramientas o técnicas para alterar o falsificar la ubicación
- Vender y comerciar con las cuentas

Debido a la polémica generada con los usuarios que utilicen más de una cuenta o compartán la suya, a diferencia de lo que dicen las normas del entrenador, **NO** será sancionable a excepción de usuarios que abusen de estas o las utilicen con el fin de perjudicar a terceras personas.


## Política de privacidad ##

### Qué información recopilamos y sometemos a tratamiento ###

Este bot recoge la siguiente información sobre sus usuarios al interactuar con él en privado o a través de un grupo o canal de Telegram:

Identificador numérico de Telegram
Alias público de Telegram
Estado de la cuenta (validada, no validada o baneada)
Datos relacionados con la cuenta de Pokémon GO facilitados en el proceso de registro: equipo, nombre de entrenador y nivel
El bot también almacena unos ficheros no ordenados con las interacciones en grupos y directas (logs), con el objetivo de poder trazar problemas técnicos y atender a las apelaciones de baneo.

###Cómo se utiliza la información ###

La información almacenada se utiliza para los siguientes fines:

Ofrecer el servicio de organización de incursiones de Pokémon GO.
Ofrecer a cada usuario y grupo o canal estadísticas y rankings semanales y mensuales sobre el uso del bot.
La base legal para el tratamiento de datos mencionado en esta sección es la prestación del servicio que se solicita voluntariamente (artículo 6, párrafo 1 (b) del RGPD).

Como se explica en la Política de tramposos, se rastrearán los logs la actividad de forma automatizada en busca de sospechosa. La base legal para este tratamiento de datos es el artículo 6, párrafo 1 (f) del RGPD.

### Quién tiene acceso a la información ###

El alias público de Telegram y los datos relacionados con la cuenta de Pokémon GO podrán compartirse en grupos o canales en los que se mantenga actividad. Esta compartición puede ser pública, dependiendo de la configuración de cada grupo o canal.

El identificador numérico y alias público de Telegram y el nombre de entrenador de Pokémon GO podrán compartirse con los administradores de los grupos o canales en los que se realice alguna actividad.

La base legal para compartir los datos proporcionados es la prestación del servicio que se solicita voluntariamente (artículo 6, párrafo 1 (b) del RGPD).

### Duración del almacenamiento ###

La información se almacena durante el tiempo necesario para cumplir con los fines para los que se se recopila:

La información de la cuenta de Pokémon GO y alias de Telegram se eliminan al pasar seis meses desde la última participación en una incursión.
Las interacciones en grupos y directas con el bot (logs) se eliminan pasados dos meses.

### Derechos contemplados en el RGPD ###

Se debe enviar un correo a [apelaciones@qwert1.es](mailto:apelaciones@qwert1.es) indicando que se desea ejercer alguno de los derechos contemplados: acceso, rectificación, supresión y limitación del tratamiento, portabilidad de datos.

En caso de ejercitar el derecho de supresión, el bot guardará el identificador numérico de Telegram junto con una marca que indica este deseo. En este caso, no será posible utilizar el bot y el estado de la cuenta aparecerá como baneada.
