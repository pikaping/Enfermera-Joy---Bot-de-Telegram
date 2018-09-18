Enfermera Joy es un bot especializado en gestionar grupos de Pokémon GO en Telegram.

Puedes pedir ayuda en el grupo [@enfermerajoyayuda](https://t.me/enfermerajoyayuda) y estar informado de las novedades en el canal [@enfermerajoynoticias](https://t.me/enfermerajoynoticias).

1. [Ayuda para entrenadores](#ayuda-para-entrenadores)
   1. [Registrarse en el bot](#registrarse-en-el-bot)
   2. [Código de Entrenador](#código-de-entrenador)
   3. [Tablas](#tablas)   
   4. [Más ayuda](#más-ayuda)
2. [Ayuda para administradores](#ayuda-para-administradores)
   1. [Añadir el bot a un grupo o canal](#añadir-el-bot-a-un-grupo-o-canal)
   2. [Configuración](#configuración)
   3. [Modo enfermera](#modo-enfermera)
   4. [Tipo de grupo](#tipo-de-grupo)
   5. [Zona horaria](#zona-horaria)
   6. [Otros comandos exclusivos para administradores](#otros-comandos-exclusivos-para-administradores)
3. [Reglamento General de Uso del Bot](#reglamento-general-de-uso-del-bot)
4. [Política de privacidad](#políica-de-privacidad)

## Ayuda para entrenadores ##

### Registrarse en el bot ###

El registro puede ser obligatorio en algunos grupos (todo depende de la configuración del grupo), pero para poder interactuar con el bot, es imprescindible el registro.
Registrarte te permite disfrutar de todas las funcionalidades del bot, como por ejemplo preguntar por otros usuarios, solicitar información de los Pokémon y muchas más funcionalidades que llegarán en un futuro.

Para registrarte tienes dos opciones:

1. En un privado con [@NurseJoyBot](https://t.me/NurseJoyBot), escribe el comando `/register` y comenzarás el proceso de registro y validación. El proceso es automatizado y te pedirá que hagas una captura de pantalla del juego con unas condiciones.

2. Si estás registrado y validado con [@detectivepikachubot](https://t.me/detectivepikachubot), puedes escribir el comando `/profile` y reenviar la respuesta a [@NurseJoyBot](https://t.me/NurseJoyBot). Este método, sirve tanto para registrarse como para subir de nivel.

### Código de Entrenador ###

Si quieres, puedes compartir tu código de entrenador con el bot para que cuando pregunten por ti, aparezca junto al resto de información. Únicamente verán tu código aquellas personas que hayan compartido el suyo con el bot.

Para compartir tu código de entrenador, lo debes hacer de la siguiente manera (el número sin espacios y separado del comando):

    /setfriendid 123456789123

Una vez hecho esto, para ver los codigos de entrenador de los demás, tienes dos formas:

`/idlist` - Este comando es **exclusivo** para grupos. El bot te enviará un listado de todos los IDs conocidos del grupo por privado.

`Joy, quien es` - Respondiendo a un mensaje de alguien, Joy te enviará por privado la información de ese usuario.

### Tablas ###

- Absol
- Articuno
- Celebi
- Entei
- Golem
- Groudon
- Ho-oh
- Kyogre
- Lapras
- Latias
- Latios
- Lugia
- Machamp
- Magikarp
- Marowak (alola)
- Mawile
- Mew
- Mewtwo
- Moltres
- Raichu (alola)
- Raikou
- Rayquaza
- Regice
- Regirock
- Registeel
- Rhydon
- Snorlax
- Suicune
- Tyranitar
- Zapdos

***

- Amistad
- Community


### Más ayuda ###

Si necesitas ayuda que no se encuentre en este manual, puedes preguntar en [@enfermerajoyayuda](https://t.me/enfermerajoyayuda). Si estás administrando un grupo o un canal, mira más abajo para ver la ayuda para administradores.


## Ayuda para administradores ##

De aquí en adelante, [@NurseJoyBot](https://t.me/NurseJoyBot) pasará a ser *el bot*.

### Grupos ###

El soporte de [@NurseJoyBot](https://t.me/NurseJoyBot), por el momento, solo está probado en **grupos y supergrupos**. En un futuro, contará con soporte en canales.

En **grupos** el bot ya se puede utilizar tan pronto entra al grupo y envía un saludo. Conviene configurarlo, no obstante. Ten cuidado porque, si una vez añadas el bot conviertes el grupo a supergrupo, tendrás que volver a configurarlo. Un supergrupo es la mejor opción en la mayoría de los casos.

### Añadir el bot a un grupo o canal ###

Para **añadir el bot a un grupo** tienes tres alternativas:

1. Dirígete al perfil de [@NurseJoyBot](https://t.me/NurseJoyBot). En el menú, selecciona la opción *Añadir a un grupo* y escoge el grupo de la lista.

2. Pulsa en [este enlace](https://telegram.me/NurseJoyBot?startgroup=true) en un dispositivo donde tengas Telegram instalado.

3. Puedes intentar añadirlo como un contacto más desde el grupo con su alias `@NurseJoyBot`, pero en versiones recientes de Telegram hay problemas usando este método.

### Configuración ###

Para hacer la configuración básica del bot utiliza el comando `/settings`. La configuración está dividida en varios apartados:

1. **Chistes**. Activa o desactiva los chistes, refranes y cualquier cosa que pueda hacer que el bot hable sin que nadie lo invoque. Opción desactivada por defecto.

2. **Juegos**. Permite o no que los usuarios ejecuten los comandos para jugar con el bot. Opción desactivada por defecto.

3. **Modo enfermera**. Borra todos los mensajes a excepción de los enviados por administradores. Mira el [apartado del modo enfermera](#modo-enfermera) para más información. Opción desactivada por defecto.

4. **Tipo de grupo**. Cuenta con cinco opciones. Mira el [apartado del tipo de grupo](#tipo-de-grupo) para más información. Opción desactivada por defecto.

5. **Configuración de los avisos**. Esta función sirve para determinar el número de avisos que recibirá un usuario antes de ser expulsado de un grupo. Las diferentes opciones son 5/10/25/50/100.

### Modo enfermera ###

El modo enfermera evita que la gente hable en un grupo, borrando todos los mensajes que pongan los usuarios (no los administradores).

El comando `/settalkgroup` permite definir un grupo para hablar.  Por ejemplo:

    /settalkgroup @enfermerajoyayuda
    /settalkgroup https://t.me/joinchat/XXs3XkzYsXXxnvbtxxe11x

Si está el modo niñero activado, el bot recordará el enlace al grupo para hablar cada vez que hable alguien.

### Tipo de grupo ###

Por defecto al introducir el bot, se establece el grupo como *grupo sin requisitos*

| Identificador   | Definición                       |
|:----------------|:---------------------------------|
|        ▪️        | Grupo sin requisitos             |
|       ✅       | Grupo con validación obligatoria |
|       ❤️       | Grupo exclusivo Rojo             |
|       💙       | Grupo exclusivo Azul             |
|       💛       | Grupo exclusivo Amarillo         |

En caso de que un usuario intente acceder a un grupo en el cual no cumpla las condiciones de entrada, si el bot cuenta con los privilegios pertinentes, expulsará al usuario.

### Zona horaria ###

El bot reconoce la hora que escriben los usuarios y hace operaciones con ellas, por lo que es importante que la hora que utilice el bot se corresponda con la hora real de tu grupo.

Para establecer la zona horaria correcta se debe utilizar el comando `/settimezone` con la zona horaria correspondiente como parámetro siguiendo el formato del [listado de zonas horarias de la IANA](https://en.wikipedia.org/wiki/List_of_tz_database_time_zones). Por ejemplo:

    /settimezone Europe/Madrid
    /settimezone Atlantic/Canary

### Otros comandos exclusivos para administradores ###

`/ban`: Expulsa y banea al usuario en el grupo actual. Se utiliza respondiendo a un mensaje del usuario a banear.

`/kick`:  Expulsa al usuario en el grupo actual. Se utiliza respondiendo a un mensaje del usuario a expulsar.

`/warn`: Advierte al usuario en el grupo actual. Al alcanzar el nº máximo de advertencias banea al usuario del grupo. Se utiliza respondiendo a un mensaje del usuario a advertir.

## Reglamento General de Uso del Bot ##

El siguiente punto, detalla la normativa a cumplir en caso de registrarse en el bot. El desconocimiento de la misma no exime al usuario de su aplicación pues todas las normas aquí recogidas son de sentido común. 

Este bot no puede ser utilizado en grupos o canales que promueven el uso de trampas en el juego. Si bien no se puede evitar que sea utilizado casi por cualquiera, el bot implementa algunas medidas anti-trampas que detectan determinados comportamientos que pueden llevar a un baneo preventivo.

En caso de formar parte de un grupo en el cual se encuentre [@NurseJoyBot](https://t.me/NurseJoyBot) y conozcas a un usuario o administrador que no cumpla alguna de las normas, se deberá comunicar mediante correo electrónico a la dirección [reportes@qwert1.es](mailto:reportes@qwert1.es). Cualquier sanción aplicada será debatida entre los miembros del staff del bot, apelable en la siguiente dirección de E-mail: [apelaciones@qwert1.es](mailto:apelaciones@qwert1.es).

### Normas de Enfermera Joy ### 

- 🔞 Está totalmente prohibido enviar material sensible.
- ⛔️ Está **COMPLETAMENTE PROHIBIDO** solicitar y/o aportar información relativa a otro jugador en cualquiera de los grupos oficiales del bot o bien por privado a cualquier miembro del staff. En caso de producirse esta situación, los administradores se reservan el derecho de banear **definitivamente** la cuenta del entrenador.
- 😈 Nunca difames, abuses, hostigues, dañes, acoses, amenaces o violes de cualquier manera los derechos legales (incluidos los derechos de privacidad y publicidad) de los demás.
- 👺 Se ruega evitar generar discusiones o debates *interminables*, o que no aporten información útil al grupo, incluyendo temas de hacks, trampas, emuladores o similares.
- 😊 Ante todo, ¡fomenta el buen rollo! El grupo no es restrictivo, no tengas miedo de preguntar o conversar sobre el juego. Pero ten cuidado con las cosas o "bromas" que digas, puedes ofender a alguien.
- 📩 Se considera **flood** el hecho de repetir continuamente palabras, hacer *cadenas* de contenido multimedia o comandos (enviar muchas fotos o stickers seguidos), provocando molestias al grupo con contenido innecesario. 
- 🌍 Normalmente el usuario estará unido en los grupos cercanos a su ubicación, o que suela frecuentar. Si un usuario es avistado en varios grupos de diferentes ubicaciones a la vez, podría ser expulsado de todos ellos por sospechas de posibles trampas. Se entiende que si un usuario se va de vacaciones a otro lugar, no es necesario abandonar los grupos de su ubicación, y se valorará este motivo.


### Normas del Entrenador ###

Es **obligatorio** que todos los usuarios que están en el grupo, cumplan las [Normas del Entrenador](https://support.pokemongo.nianticlabs.com/hc/es/articles/221993967) de Niantic.

Obviando la parte de comportamiento ético como personas, se detalla que jugar de las siguientes formas (pero no únicamente éstas) se considera **trampa**, llevando a la expulsión del grupo:
- Usar software modificado o no oficial
- Compartir cuentas, jugar con cuentas de otros jugadores en un mismo móvil
- Usar herramientas o técnicas para alterar o falsificar la ubicación
- Vender y comerciar con las cuentas

Debido a la polémica generada con los usuarios que utilicen más de una cuenta o compartan la suya, a diferencia de lo que dicen las normas del entrenador, **NO** será sancionable a excepción de usuarios que abusen de estas o las utilicen con el fin de perjudicar a terceras personas.


## Política de privacidad ##

### Qué información recopilamos y sometemos a tratamiento ###

Este bot recoge la siguiente información sobre sus usuarios al interactuar con él en privado o a través de un grupo o canal de Telegram:

- Identificador numérico de Telegram
- Alias público de Telegram
- Estado de la cuenta (validada, no validada o baneada)
- Datos relacionados con la cuenta de Pokémon GO facilitados en el proceso de registro: equipo, nombre de entrenador y nivel

El bot también almacena unos ficheros no ordenados con las interacciones en grupos y directas (logs), con el objetivo de poder trazar problemas técnicos y atender a las apelaciones de baneo.

### Cómo se utiliza la información ###

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
