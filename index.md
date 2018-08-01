Enfermera Joy es un bot de Telegram especializado en gestionar grupos de Pokémon GO en Telegram.

Puedes pedir ayuda en el grupo [@enfermerajoyayuda](https://t.me/enfermerajoyayuda) y estar informado de las novedades en el canal [@enfermerajoynoticias](https://t.me/enfermerajoynoticias).

1. [Ayuda para entrenadores](#ayuda-para-entrenadores)
   1. [Registrarse en el bot](#registrarse-en-el-bot)
   2. [Código de Entrenador](#friend-id)
   3. [Registrarse en el bot](#tablas)   
   3. [Más ayuda](#más-ayuda)
2. [Ayuda para administradores](#ayuda-para-administradores)
   1. [Añadir el bot a un grupo o canal](#añadir-el-bot-a-un-grupo-o-canal)
   2. [Configuración](#configuración)
   3. [Modo niñero](#modo-niñero)
   4. [Zona horaria](#zona-horaria)
   5. [Otros comandos exclusivos para administradores](#otros-comandos-exclusivos-para-administradores)
3. [Reglamento General de Uso del Bot](#reglamento-general-de-uso-del-bot)

## Ayuda para entrenadores ##

### Registrarse en el bot ###

El registro es obligatorio en algunos grupos (a discreción de los administradores), pero sea obligatorio o no, te permite disfrutar de todas las funcionalidades del bot, como por ejemplo preguntar por otros usuarios, solicitar información de los Pokémones y muchas más funcionalidades que llegarán en un futuro.

Para registrarte tienes dos opciones:

1. En un privado con [@NurseJoyBot](https://t.me/NurseJoyBot), escribe el comando `/register` y comenzarás el proceso de registro y validación. El proceso es automatizado y te pedirá que hagas una captura de pantalla del juego con unas condiciones.

2. Si estás registrado y validado con [@detectivepikachubot](https://t.me/detectivepikachubot), puedes escribir el comando `/profile` y reenviar la respuesta a [@NurseJoyBot](https://t.me/NurseJoyBot).

### Más ayuda ###

Si necesitas ayuda que no se encuentre en este manual, puedes preguntar en [@enfermerajoyayuda](https://t.me/enfermerajoyayuda). Si estás administrando un grupo o un canal, mira más abajo para ver la ayuda para administradores.

## Ayuda para administradores ##

### Grupos y canales ###

El bot se puede añadir a grupos y a canales, pero funciona de manera ligeramente distinta en ambos casos, en parte por el propio funcionamiento de Telegram.

En **grupos** el bot ya se puede utilizar tan pronto entra al grupo y envía un saludo. Conviene configurarlo, no obstante. Ten cuidado porque, si una vez añadas el bot conviertes el grupo a supergrupo, tendrás que volver a configurarlo. Un supergrupo es la mejor opción en la mayoría de los casos.

En **canales** el bot no saluda al entrar y necesita configurarse con `/settings` antes de poder utilizarse. También funciona algo más lento y hay algunas diferencias más. En un canal, no mostrará el creador de la incursión porque la incursión siempre la crea el canal, no un usuario. Además, algunas de las opciones no tienen sentido para canales. Usar un canal es una opción sencilla si se quiere integrar con otros bots, ya que un bot no puede leer el mensaje de otro bot en un grupo.

### Añadir el bot a un grupo o canal ###

Para **añadir el bot a un grupo** tienes tres alternativas:

1. Vete al perfil de [@detectivepikachubot](https://t.me/detectivepikachubot). En el menú, selecciona la opción *Añadir a un grupo* y escoge el grupo de la lista.

2. Pulsa en [este enlace](https://telegram.me/detectivepikachubot?startgroup=true) en un dispositivo donde tengas Telegram instalado.

3. Puedes intentar añadirlo como un contacto más desde el grupo con su alias `@detectivepikachubot`, pero en versiones recientes de Telegram hay problemas usando este método.

Para **añadir el bot a un canal** las opciones son más limitadas. Tienes que ir a la gestión de administradores y **añadirlo directamente como administrador**, buscándolo como un contacto más con su alias `@detectivepikachubot`.

Con versiones recientes de Telegram no se pueden añadir bots de esta forma. Si es tu caso, descarga la beta para Android desde [el canal Beta de Telegram](http://t.me/tgrambeta) buscando el archivo `tgrambeta.apk` más reciente. Telegram Beta se instala como una aplicación aparte y, una vez añadas el bot, puedes desinstalarla.

### Configuración ###


Para hacer la configuración básica del bot utiliza el comando `/settings`. La configuración está dividida en varios submenús:

#### Funcionamiento del grupo/canal ####

1. **Ubicaciones**. Activa o desactiva la integración de las ubicaciones. Para poder utilizar esta opción, debes [configurar las ubicaciones](#ubicaciones). Si no vas a hacerlo, es mejor que la desactives. Opción activada por defecto.

2. **Permitir configurar alertas**. Requiere la opción *Ubicaciones* (se marca automáticamente si es necesario). Permite o no que los usuarios encuentren los gimnasios configurados en este grupo/canal a la hora de configurarse alertas por privado. Opción activada por defecto.

3. **Modo niñero**. Borra todos los mensajes excepto los mensajes de creación de incursiones y los comandos permitidos. Mira el  [apartado del modo niñero](#modo-niñero) para más información. Opción desactivada por defecto.

4. **Validación obligatoria**. Si está activada, obliga a todos los usuarios a validarse en el bot antes de poder participar en incursiones o crearlas. Opción desactivada por defecto.

5. **Reflotar automático**. Si está activada, esta opción hace que el bot reflote todas las incursiones activas cada 5, 10, 15 o 30 minutos. Las incursiones se consideran activas si falta **menos de una hora y media para que comiencen** o si acaban de comenzar (una vez comenzadas, se reflotarán una única vez). Opción desactivada por defecto.


### Modo niñero ###

El modo niñero evita que la gente hable en un grupo, borrando todos los mensajes que pongan los usuarios (no los administradores).

El comando `/settalkgroup` permite definir un grupo para hablar. Si está el modo niñero activado, el bot recordará el enlace al grupo para hablar cada vez que hable alguien. Por ejemplo:

    /settalkgroup @PGSDC
    /settalkgroup https://t.me/joinchat/XXs3XkzYsXXxnvbtxxe11x

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

En caso de formar parte de un grupo en el cual se encuentre [@NurseJoyBot](https://t.me/NurseJoyBot) y tener a un usuario que no cumple cualquiera de las normas, se deberá comunicar Cualquier sancion aplicada será debatida entre los administradores del bot, apelable en la siguiente dirección de E-mail: [apelaciones@qwert1.es](mailto:apelaciones@qwert1.es).

### Normas de Enfermera Joy ### 

- 🔞 Está totalmente prohibido enviar material sensible.
- 😈 Nunca difames, abuses, hostigues, dañes, acoses, amenaces o violes de cualquier manera los derechos legales (incluidos los derechos de privacidad y publicidad) de los demás.
- 👺 Se ruega evitar generar discusiones o debates *interminables*, o que no aporten información útil al grupo, incluyendo temas de hacks, trampas, emuladores o similares.
- 😊 Ante todo, ¡fomenta el buen rollo! El grupo no es restrictivo, no tengas miedo de preguntar o conversar sobre el juego. Pero ten cuidado con las cosas o "bromas" que digas, puedes ofender a alguien.
- 📩 Se considera **flood** el hecho de repetir contínuamente palabras, hacer *cadenas* de contenido multimedia o comandos (enviar muchas fotos o stickers seguidos), provocando molestias al grupo con contenido innecesario. 
- 🌍 Normalmente el usuario estará unido en los grupos cercanos a su ubicación, o que suela frecuentar. Si un usuario es avistado en varios grupos de diferentes ubicaciones a la vez, podría ser expulsado de todos ellos por sospechas de posibles trampas. Se entiende que si un usuario se va de vacaciones a otro lugar, no es necesario abandonar los grupos de su ubicación, y se valorará este motivo.
- 🤐 Está **COMPLETAMENTE PROHIBIDO** solicitar y/o aportar información relativa a otro jugador en cualquiera de los grupos oficiales del bot o bien por privado a cualquier miembro del staff. En caso de producirse esta situacion, los administradores se reservan el derecho de banear **definitivamente** la cuenta del entrenador.


## Normas del Entrenador

Es **obligatorio** que todos los usuarios que están en el grupo, cumplan las [Normas del Entrenador](https://support.pokemongo.nianticlabs.com/hc/es/articles/221993967) de Niantic.

Obviando la parte de comportamiento ético como personas, se detalla que jugar de las siguientes formas (pero no únicamente éstas) se considera **trampa**, llevando a la expulsión del grupo:
- Usar software modificado o no oficial
- Jugar con múltiples cuentas (una cuenta por persona, por favor)
- Compartir cuentas, jugar con cuentas de otros jugadores en un mismo móvil
- Usar herramientas o técnicas para alterar o falsificar la ubicación
- Vender y comerciar con las cuentas
