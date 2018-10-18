Enfermera Joy es un bot especializado en gestionar grupos de Pokémon GO en Telegram.

Puedes pedir ayuda en el grupo [@enfermerajoyayuda](https://t.me/enfermerajoyayuda) y estar informado de las novedades en el canal [@enfermerajoynoticias](https://t.me/enfermerajoynoticias).

1. [Ayuda para entrenadores](#ayuda-para-entrenadores)
   1. [Registrarse en el bot](#registrarse-en-el-bot)
   2. [Profile](#profile)
   3. [Iconos en la Ficha de Entrenador](#iconos-en-la-ficha-de-entrenador)
   4. [Código de Entrenador](#código-de-entrenador)
   5. [Quién es](#quién-es)
   6. [Tablas](#tablas)  
   7. [Registrar nidos](#registrar-nidos)  
   8. [Glosario de comandos para entrenadores](#glosario-de-comandos-para-entrenadores)
   9. [Más ayuda](#más-ayuda)
2. [Ayuda para administradores](#ayuda-para-administradores)
   1. [Añadir el bot a un grupo o canal](#añadir-el-bot-a-un-grupo-o-canal)
   2. [Configuración básica](#configuración-básica)
      1. [Ajustes generales](#ajustes-generales)
      2. [Ajustes de entrada](#ajustes-de-entrada)
      3. [Configurar nidos](#configurar-nidos)
      4. [Noticias](#noticias)
      5. [Bienvenida](#bienvenida)
   3. [Configuración Admins](#configuración-admins)
   4. [Zona horaria](#zona-horaria)
   5. [Otros comandos exclusivos para administradores](#otros-comandos-exclusivos-para-administradores)
   6. [Glosario de comandos para administradores](#glosario-de-comandos-para-administradores)
3. [Reglamento General de Uso del Bot](#reglamento-general-de-uso-del-bot)
4. [Política de privacidad](#políica-de-privacidad)

## Ayuda para entrenadores ##

### Registrarse en el bot ###

El registro puede ser obligatorio en algunos grupos (todo depende de la configuración del grupo), pero para poder interactuar con el bot, es imprescindible el registro.

Registrarte te permite disfrutar de todas las funcionalidades del bot, como por ejemplo preguntar por otros usuarios, solicitar información de los Pokémon y muchas más funcionalidades que llegarán en un futuro.

Para registrarte tienes tres opciones:

1. La opción más rápida, si estás registrado con [@detectivepikachubot](https://t.me/detectivepikachubot), es decirle por privado a [@NurseJoyBot](https://t.me/NurseJoyBot) el comando `/register`, entonces te preguntará si quieres que le pregunte a Detective Pikachu tus datos. Si aceptas tendrás que abrir la conversación privada con Detective Pikachu que te preguntará lo mismo. Si aceptas en ambos entonces ya estarás registrado.

   Si antes de eso ya le habías dicho a Detective Pikachu que aceptas compartir los datos con Enfermera Joy, entonces al escribirle        `/register` preguntará automáticamente los datos a Detective Pikachu (sin que tu tengas que hacer nada) y ya estarás registrado.

2. Si al decirle `/register` en privado a [@NurseJoyBot](https://t.me/NurseJoyBot) no estás registrado con el bot [@detectivepikachubot](https://t.me/detectivepikachubot) o no has aceptado que Enfermera Joy pregunte los datos a Detective Pikachu, entonces iniciará automáticamente el proceso de registro en el cual te preguntará tu nick de entrenador y te pedirá que hagas una captura de pantalla del juego con unas condiciones.

3. También tienes la opción de que si estás registrado y validado con [@detectivepikachubot](https://t.me/detectivepikachubot), puedes escribir el comando `/profile` en el privado de Detective Pikachu y reenviar la respuesta a [@NurseJoyBot](https://t.me/NurseJoyBot). Este método, sirve tanto para registrarse como para subir de nivel.

#### Alias de Telegram ####

Para poder utilizar algunas de las funciones más básicas del bot es necesario tener definido un alias en Telegram. Puede hacerse desde: Opciones de Telegram -> Ajustes -> Alias.

#### Subida de nivel ####

Para indicar una subida de nivel una vez se esté validado, basta con enviar una captura de pantalla del perfil de entrenador de Pokémon Go por privado a [@NurseJoyBot](https://t.me/NurseJoyBot).

#### Cambio de nombre de entrenador ####

Si has cambiado tu nombre de entrenador en el juego, debes volver a hacer el proceso de registro. No hay ninguna restricción, aunque ya estuvieras validado anteriormente con otra cuenta.

Para ello puedes seguir cualquiera de los tres métodos que encontrarás en el apartado [Registrarse en el bot](#registrarse-en-el-bot).

#### Cambio de cuenta de Telegram ####


### Profile ###

El comando `/Profile` puede utilizarse en un grupo o en una conversación privada con el bot [@NurseJoyBot](https://t.me/NurseJoyBot), pero la resupesta de Enfermera Joy será enviada al privado. Este comando hará que el bot responda con la Ficha de Entrenador (Nick del juego, Equipo, Nivel y Estado de Validación) del jugador que la solicita.

Ejemplos de posibles respuestas del bot:

1. **Berny**, eres del equipo **Instinto** nivel **40** ✅
   
   Estás registrado correctamente.

2. *Desconocido*, es *Desconocido* nivel *Desconocido*.

   Esto quiere decir que el proceso de validación ha sido iniciado pero no finalizado, por lo tanto no estás registrado con el bot.

3. ❌ No tengo información sobre ti.
   
   No tiene ningún tipo de dato sobre ti.


### Iconos en la Ficha de Entrenador ###

En principio, el único icono que deberías de ver ya sea en tu Ficha de Entrenador o en la de tus companeros es el de Validado (✅), pero existen mucho otros.

Algunos de ellos son los siguientes:

| Icono           | Definición                       |
|:----------------|:---------------------------------|
|        .        | Baneado                          |
|        .        | Staff                            |


### Código de Entrenador ### 

Si quieres, puedes compartir tu código de entrenador con el bot para que cuando pregunten por ti con el comando `quién es` (para más información sobre este comando mira el apartado [Quién es](#quién-es)), aparezca junto al resto de información. Únicamente verán tu código aquellas personas que hayan compartido el suyo con el bot.

Para compartir tu código de entrenador, lo debes hacer con el siguiente comando por privado a [@NurseJoyBot](https://t.me/NurseJoyBot) (el número sin espacios y separado del comando):

    /set_friendid 

Una vez hecho esto, para ver los codigos de entrenador de los demás, tienes dos formas:

`(no disponible)` - Este comando es **exclusivo** para grupos. El bot te enviará un listado de todos los IDs conocidos del grupo por privado.

`(no disponible)` - Respondiendo a un mensaje de alguien, Joy te enviará por privado la información de ese usuario.


### Quién es ###

El comando `quién es` (también aceptado como `quien es` o `/whois`, sin interrogante) hace que el bot te responda la información de la Ficha de Entrenador (Nick del juego, Equipo, Nivel y Estado de Validación) del jugador solicitado.

Ejemplos de posibles respuestas de Joy:

1. **Berny**, es del equipo **Instinto** nivel **40** ✅

   El Entrenador utiliza el nick de Berny en el juego, es del equipo Instinto, nivel 40 y está validado. Aunque no es freqüente, la        Ficha de Entrenador puede tener otros iconos. Para más información leer el apartado [Iconos en la Ficha de Entrenador](#iconos-en-la-ficha-de-entrenador).

2. ❌ No tengo información sobre este entrenador.
   
   El Entrenador no está registrado.

3. *Desconocido*, es *Desconocido* nivel *Desconocido*.

   El Entrenador ha iniciado un proceso de registro, pero no se ha terminado correctamente.

El bot siempre enviará la información al privado, por ello es imprescindible tener abierta una conversación privada con [@NurseJoyBot](https://t.me/NurseJoyBot).

Se puede emplear el comando de dos formas:

1. Citando el mensaje del jugador por el grupo general y escribiendo el comando. El bot eliminará automáticamente el mensaje donde esté el comando y responderá con un mensaje que también será eliminado cuando hayan pasado unos segundos.

2. Citando el mensajde del jugador por privado. Este método evita escribir el mensaje por grupo, pero es algo más rebuscado. Primero de todo se debe reenviar un mensaje del jugador que se desea al privado del bot [@NurseJoyBot](https://t.me/NurseJoyBot), seguidamente, dentro del privado del bot, deberás citar el mensaje que acabas de reenviarle y escribir el comando.


### Tablas ###

El bot dispone de una gran cantidad de tablas de IV, de recompensas por amistad, Pokémon de los Community Day, Pokémon shiny, etc. Para solicitarlas se debe emplear el comando `/tabla` o `/table` seguido de un espacio y el nombre de la tabla que se desea. El mensaje solicitando la tabla será eliminado por el bot de forma automática.

Todas las tablas son mandadas al privado del bot, para ello es necesario tener abierta una conversación privada con [@NurseJoyBot](https://t.me/NurseJoyBot).

Estos son las tablas de las que se disponen actualmente:

- Absol
- Articuno
- Beldum (también la puedes solicitar como Community)
- Celebi
- Deoxys normal
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

- Raid (también se puede solicitar como: Raids, incursión, incursion, incursiones, jefe o jefes)
- Amistad
- Community

Todas las tablas se van modificando según los cambios que van surgiendo en Pokémon Go y se van añadiendo tablas nuevas necesarias, por lo tanto la lista de tablas es algo que irá cambiando.

### Registrar nidos ###

El bot dispone de registro de nidos, para ello debe de estar configurado el grupo para aceptar su registro. Esta configuración únicamente la puede realizar un administrador de dicho grupo. Si eres administrador de un grupo y quieres saber más información al respecto lee el apartado [Configurar nidos](#configurar-nidos).

Para registrar un nido se debe emplear el comando `Confirmo nido de {Pokémon} en {Lugar}` cambiando la variable {Pokémon} por el nombre del Pokémon del que sea el nido y {Lugar} por el nombre por el cual se reconozca ese espacio. 

Si el nido es erroneo y se quiere borrar antes de que Joy los reinicie entonces se deberá utilizar el comando `Borrar nido de {Pokémon} en {Lugar}`. Siendo, igual que al registrar el nido, las variables {Pokémon} y {Lugar} las únicas palabras que se modificarán del comando. Este comando es exclusivo para administradores.

Otros dos comandos relacionados con los nidos son:  `Nido en {Lugar}` y `Nido de {Pokémon}`.

`Nido en {Lugar}`, por ejemplo, "Nido en Parque Ilm".

Hace que el bot te responda si hay registrado algún nido en el lugar llamado "Parque Ilm" y, si lo hay, te diga de qué pokémon se trata.

`Nido de {Pokémon}`, por ejemplo, "Nido de Chansey".

Hace que el bot te responda si hay registrado algún nido de Chansey en tu grupo, si lo hay, te responderá con el nombre del lugar donde se ha registrado.

### Glosario de comandos para entrenadores ###

Comando | Descripción | Exclusivo administradores | Ámbito | Parámetros
--------|-------------|---------------------------|--------|-----------
`Confirmo nido de {Pokémon} en {Lugar}`| ? | ❌ | Grupo | `Pokémon Lugar`<sup>1</sup>
`Borrar nido de {Pokémon} en {Lugar}`| ? | ✅ | Grupo | `Pokémon Lugar`<sup>1</sup>
`Nido en {Lugar}`| ? | ❌ | Grupo | `Lugar`<sup>1</sup>
`Nido de {Pokémon}`| ? | ❌ | Grupo | `Lugar`<sup>1</sup>
`/start`| ? | ❌ | Todos | ❌
`/help`| ? | ❌ | Todos | ❌
`/register`| ? | ❌ | Privado | ❌
`/set_friendid`| ? | ❌ | Privado | `ID de Pokémon GO`
`Quién es`| ? | ❌ | Todos | ❌
`Quién es Entrenador`| ? | ❌ | Todos | `Nombre de entrenador`
`/profile`| ? | ❌ | Todos | ❌
`/tabla`| ? | ❌ | Todos | `Tabla disponible`
`/joyping`| ? | ❌ | Todos | ❌

1. Número máximo de caracteres: 50.

### Más ayuda ###

Si necesitas ayuda que no se encuentre en este manual, puedes preguntar en [@enfermerajoyayuda](https://t.me/enfermerajoyayuda). Si estás administrando un grupo o un canal, continua leyendo para ver la ayuda para administradores.

----
----


## Ayuda para administradores ##

De aquí en adelante, [@NurseJoyBot](https://t.me/NurseJoyBot) pasará a ser *el bot*.

### Grupos ###

El soporte del bot, por el momento, solo está probado en **grupos y supergrupos**. En un futuro, contará con soporte en canales.

En **grupos** el bot ya se puede utilizar tan pronto entra al grupo y envía un saludo. Conviene configurarlo, no obstante. Ten cuidado porque, si una vez añadas el bot conviertes el grupo a supergrupo, tendrás que volver a configurarlo. Un supergrupo es la mejor opción en la mayoría de los casos.

### Añadir el bot a un grupo o canal ###

Para **añadir el bot a un grupo** tienes tres alternativas:

1. Dirígete al perfil del bot. En el menú, selecciona la opción *Añadir a un grupo* y escoge el grupo de la lista.

2. Pulsa en [este enlace](https://telegram.me/NurseJoyBot?startgroup=true) en un dispositivo donde tengas Telegram instalado.

3. Puedes intentar añadirlo como un contacto más desde el grupo con su alias `@NurseJoyBot`, pero en versiones recientes de Telegram hay problemas usando este método.

### Configuración básica ###

Para hacer la **configuración básica** del bot utiliza el comando `/settings`. La configuración está dividida en varios apartados y subapartados:

1. [Ajustes generales](#ajustes-generales) (Configuraciones básicas de juegos y modo de administración.)
      1. [Chistes](#chistes) `Actualmente esta opción no está disponible.`
      2. [Juegos](#Juegos) `Actualmente esta opción no está disponible.`
      3. [Modo enfermera](#modo-enfermera)   
      4. [Tipo de expulsión por Warns](#tipo-de-expulsión-por-warns)
      5. [Cantidad de Warns](#cantidad-de-warns)      

2. [Ajustes de entrada](#ajustes-de-entrada) (Configuración de los tipos de grupo y los requisitos.)
      1. [Tipo de grupo](#tipo-de-grupo)
      2. [Requisito de nivel](#requisito-de-nivel)
      
3. [Configurar Nidos](#configurar-nidos) (Configuración de los nidos y requisitos para el registro) `Actualmente esta opción no está disponible.`
      1. [Nidos](#nidos) 
      2. [Requisito de cantidad de días](#requisito-de-cantidad-de-días)
      3. [Requisito de cantidad de mensajes](#requisito-de-cantidad-de-mensajes)
      
4. [Noticias](#noticias) `Actualmente esta opción no está disponible.`
      1. **@pokemongohonesto**
      2. **@enfermerajoynoticias**

5. [Bienvenida](#bienvenida)
      1. **Bienvenida**

#### Ajustes generales ####

##### Chistes #####   
`Actualmente esta opción no está disponible.`

Activa o desactiva los chistes, refranes y cualquier cosa que pueda hacer que el bot hable sin que nadie lo invoque. Opción desactivada por defecto. 

##### Juegos #####   
`Actualmente esta opción no está disponible.`

Activa o desactiva los juegos del bot. Por defecto esta opción está desactivada.

##### Modo enfermera #####

El modo enfermera evita que la gente hable en un grupo, borrando todos los mensajes que pongan los usuarios (no los mensajes de los administradores ni de los bots). Opción desactivada por defecto.

El comando `/settalkgroup` permite definir un grupo para hablar.  Por ejemplo:

    /settalkgroup @enfermerajoyayuda
    /settalkgroup https://t.me/joinchat/XXs3XkzYsXXxnvbtxxe11x

Si está el modo enfermera activado, el bot recordará el enlace al grupo para hablar cada vez que hable alguien.

##### Tipo de expulsión por Warns #####

Este botón puede estar activado como `Ban (Warns)` o como `Kick (Warns)` y determina el tipo de expulsión que recibirá el usuario al llegar al máximo de Warns determinado por el grupo.

##### Cantidad de Warns #####

Clicando sobre el botón determina la cantidad máxima de Warns que podrá tener un usuario antes de recibir la expulsión del grupo. La cantidad de Warns que se puede configurar es de: 3, 5, 10, 25, 50 o 100.

#### Ajustes de entrada ####

(Configuración de los tipos de grupo y los requisitos.)

##### Tipo de grupo #####

Por defecto al introducir el bot, se establece el grupo como *grupo sin requisitos*.

| Identificador   | Definición                       |
|:----------------|:---------------------------------|
|        ▪️        | Grupo sin requisitos             |
|       ✅        | Grupo con validación obligatoria |
|       ❤️        | Grupo exclusivo Rojo             |
|       💙        | Grupo exclusivo Azul             |
|       💛        | Grupo exclusivo Amarillo         |

En caso de que un usuario intente acceder a un grupo en el cual no cumpla las condiciones de entrada, si el bot cuenta con los privilegios pertinentes, expulsará al usuario.

##### Requisito de nivel #####

Determina un nivel mínimo como requisito para entrar al grupo. Esta opción viene activada por defecto como 0, eso queriere decir que no hay nivel mínimo requerido.

El nivel mínimo para entrar en el grupo se puede configurar, clicando en el botón hasta que salga la opción deseada, según: 0 (sin nivel requerido), 15, 20, 25, 30, 35 o 40.

#### Configurar Nidos ####

El bot dispone de la opción de registrar nidos, para ello es necesario configurar el apartado de Nidos y sus requisitos.

##### Nidos ##### 
`Actualmente esta opción no está disponible.`

Clicando sobre el botón `Nidos` podrás activar o desactivar esta opción para que no pueda entrar en conflicto con otros bots que puedan estar haciendo la misma función en el grupo.

| Identificador   | Definición                       |
|:----------------|:---------------------------------|
|    ▪️ Nidos      | Registro de nidos desactivado |
|    ✅ Nidos    | Registro de nidos activado |    

El registro de nidos viene desactivada por defecto.

##### Requisito de cantidad de días #####

Para determinar el número mínimo de días que un jugador ha de pertenecer al grupo para poder registrar un nido es necesario clicar sobre el botón hasta que aparezca la opción deseada. La cantidad de días que se pueden configurar son: 0 (sin requisito de días), 1, 3, 5, 7, 15 o 30.

Por defecto viene configurado el requisito como sin requisito, 0 días.

##### Requisito de cantidad de mensajes #####

Para determinar el número mínimo de mensajes que un jugador debe de hacer en un grupo para poder registrar un nido se debe de clicar sobre el botón hasta que aparezca la opción deseada. La cantidad de mensajes requeridos que se puede configurar son: 0 (sin requisitos), 1, 5, 10, 20, 50 o 100.

Por defecto, este requisito, viene configurado como sin requisitos, 0 mensajes.

#### Noticias ####

##### @pokemongohonesto #####

##### @enfermerajoynoticias #####

#### Bienvenida ####

El bot puede dar la bienvenida a los entrenadores que vayan entrando al grupo. Opción desactivada por defecto. 

Para activar la Bienvenida es necesario activarla en Settings y después es necesario utilizar el comando `/set_welcome` para definir el mensaje de bienvenida que dará el bot. Por ejemplo, si se quiere poner el mensaje "Bienvenidos al grupo", sería:

    /set_welcome Bienvenidos al grupo.

Además el bot dispone de tres strings que se pueden introducir en el texto de bienvenida para conocer más información del entrenador que acaba de entrar. Por ejemplo:

| Strings | Texto mostrado       | Definición                              |
|:--------|:---------------------|:----------------------------------------|
|  $pogo  | Berny **L40** 💛 ✅  | Nick +Nivel +Equipo +Proceso validación |
|$username| Berny                | Nick                                    |
| $title  | PoGo de tu ciudad    | Nombre del grupo                        | 

Para poner links en el mensaje de bienvenida lo puedes hacer mediante el siguiente string: `[NombreLink](Link)`.
Por ejemplo: `[superjoy](https://websuperenfermerajoy.com)`. Este link que veremos en el mensaje de bienvenida como `superjoy` al clickarlo nos mandará a la web `https://websuperenfermerajoy.com`.

Si se quiere eliminar el mensaje de bienvenida, para que el bot deje de saludar cuando entren entrenadores nuevos, entonces se debe escribir el comando `/set_welcome` sin ningún texto más.

### Configuración Admins ###

Para hacer la **configuración de administración** del bot utiliza el comando `/settings_adm`.

### Zona horaria ###

El bot reconoce la hora que escriben los usuarios y hace operaciones con ellas, por lo que es importante que la hora que utilice el bot se corresponda con la hora real de tu grupo.

Para establecer la zona horaria correcta se debe utilizar el comando `/settimezone` con la zona horaria correspondiente como parámetro siguiendo el formato del [listado de zonas horarias de la IANA](https://en.wikipedia.org/wiki/List_of_tz_database_time_zones). Por ejemplo:
    /settimezone Europe/Madrid
    /settimezone Atlantic/Canary

### Otros comandos exclusivos para administradores ###   
`En proceso de escritura`

Ban (los ban expulsan al entrenador del grupo y no permite que este vuelva a entrar)
`/ban`: Citando el mensaje y escribiendo el comando en la respuesta. Puede ir seguido del motivo del ban.
`/banuv`: Se puede hacer desde el grupo o desde el grupo de administración, si se hace desde el de administración se puede especificar el grupo al cual va dirigido el ban, sino baneará al entrenador de todos los grupos vinculados al grupo de administración.
`/banmsg`:`Grupo Nº Mensajes`<sup>1</sup> Grupo & Grupo administración
`/banold`:`Grupo Días`<sup>1</sup> Grupo & Grupo administración
`/banall`: únicamente se puede realizar desde el grupo de administración `UserID Motivo`<sup>2</sup>
`/banteam`:`Grupo Equipo`<sup>1< Grupo & Grupo administración


`/unban`: Desbanea a un usuario. También se puede desbanear en: Ajustes de Grupo -> Administrar grupo -> Suspendidos.


`/bangroup` Grupo & Grupo administración `UserID Grupo Motivo`<sup>2</sup>

Kick (los kick expulsan al entrenador del grupo, pero permite que este vuelva a entrar)

`/kick`   Grupo  `{Motivo}`
`/kickuv` Grupo & Grupo administración `Grupo`<sup>1</sup>
`/kickmsg` Grupo & Grupo administración `Grupo Nº Mensajes`<sup>1</sup>
`/kickold` Grupo & Grupo administración `Grupo Días`<sup>1</sup>
`/kickall` Grupo administración `UserID Motivo`<sup>2</sup>
`/kickteam` Grupo & Grupo administración `Grupo Equipo`<sup>1</sup>
`/kickgroup` Grupo & Grupo administración `UserID Grupo Motivo`<sup>2</sup>
`/kickeveryone` Grupo administración `GrupoEX`<sup>3</sup>

Warn (los warn son advertencias al jugador de la futura expulsión, por ban o kick, del grupo)
`/warn`   Grupo  `{Motivo}`
`/warnuv` Grupo & Grupo administración `Grupo`<sup>1</sup>
`/warnmsg` Grupo & Grupo administración `Grupo Nº Mensajes`<sup>1</sup>
`/warnold` Grupo & Grupo administración `Grupo Días`<sup>1</sup>
`/warnall` Grupo administración `UserID Motivo`<sup>2</sup>
`/warngroup` Grupo & Grupo administración `UserID Grupo Motivo`<sup>2</sup>

`/warn`: Advierte al usuario en el grupo actual. Al alcanzar el nº máximo de advertencias banea al usuario del grupo. Se utiliza respondiendo a un mensaje del usuario a advertir.

### Glosario de comandos para administradores ###

Comando | Descripción | Exclusivo administradores | Ámbito | Parámetros
--------|-------------|---------------------------|--------|-----------
`/ban`   | ? | ✅ | Grupo | `{Motivo}`
`/banuv`| ? | ✅ | Grupo & Grupo administración | `Grupo`<sup>1</sup>
`/banmsg`| ? | ✅ | Grupo & Grupo administración | `Grupo Nº Mensajes`<sup>1</sup>
`/banold`| ? | ✅ | Grupo & Grupo administración | `Grupo Días`<sup>1</sup>
`/banall`| ? | ✅ | Grupo administración | `UserID Motivo`<sup>2</sup>
`/banteam`| ? | ✅ | Grupo & Grupo administración | `Grupo Equipo`<sup>1</sup>
`/bangroup`| ? | ✅ | Grupo & Grupo administración | `UserID Grupo Motivo`<sup>2</sup>
`/unban`| ? | ✅ | Grupo & Grupo administración | ❌
`/kick`   | ? | ✅ | Grupo | `{Motivo}`
`/kickuv`| ? | ✅ | Grupo & Grupo administración | `Grupo`<sup>1</sup>
`/kickmsg`| ? | ✅ | Grupo & Grupo administración | `Grupo Nº Mensajes`<sup>1</sup>
`/kickold`| ? | ✅ | Grupo & Grupo administración | `Grupo Días`<sup>1</sup>
`/kickall`| ? | ✅ | Grupo administración | `UserID Motivo`<sup>2</sup>
`/kickteam`| ? | ✅ | Grupo & Grupo administración | `Grupo Equipo`<sup>1</sup>
`/kickgroup`| ? | ✅ | Grupo & Grupo administración | `UserID Grupo Motivo`<sup>2</sup>
`/kickeveryone`| ? | ✅ | Grupo administración | `GrupoEX`<sup>3</sup>
`/warn`   | ? | ✅ | Grupo | `{Motivo}`
`/warnuv`| ? | ✅ | Grupo & Grupo administración | `Grupo`<sup>1</sup>
`/warnmsg`| ? | ✅ | Grupo & Grupo administración | `Grupo Nº Mensajes`<sup>1</sup>
`/warnold`| ? | ✅ | Grupo & Grupo administración | `Grupo Días`<sup>1</sup>
`/warnall`| ? | ✅ | Grupo administración | `UserID Motivo`<sup>2</sup>
`/warngroup`| ? | ✅ | Grupo & Grupo administración | `UserID Grupo Motivo`<sup>2</sup>
`/settings_admin`| ? | ✅ | Grupo administración | ❌
`/settings`| ? | ✅ | Grupo & Grupo administración | `Grupo`<sup>1</sup>
`/set_welcome`| ? | ✅ | Grupo | `Mensaje de bienvenida`
`/set_zone`| ? | ✅ | Grupo & Grupo administración | `Zona horaria`
`/set_stops`| ? | ✅ | Grupo & Grupo administración | `Enlace hoja de calculo`
`/set_talkgroup`| ? | ✅ | Grupo & Grupo administración | `Alias o enlace de Telegram`
`/mk_admin`| ? | ✅ | Grupo administración | ❌
`/rm_admin`| ? | ✅ | Grupo administración | ❌
`/add_group`| ? | ✅ | Grupo | `AdminID Tipo Etiqueta`
`/add_link`| ? | ✅ | Grupo | `Alias o enlace de Telegram`
`/rm_group`| ? | ✅ | Grupo | ❌
`/request_verification`| ? | ✅ | Grupo | ❌
`/groups`| ? | ✅ | Grupo & Grupo administración<sup>4</sup> | ❌
`Borrar nido de {Pokémon} en {Lugar}`| ? | ✅ | Grupo | `Pokémon Lugar`<sup>1</sup>
`/joyping`| ? | ❌ | Todos | ❌

1. Argumento `Grupo` unicamente válido desde el grupo de administración.
2. Argumento `Motivo` opcional.
3. Solo disponible para grupos etiquetados como EX.
4. En el grupo de administración incluye los ID.


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

Ofrecer el servicio de gestión de grupos de Pokémon GO en Telegram.
La base legal para el tratamiento de datos mencionado en esta sección es la prestación del servicio que se solicita voluntariamente (artículo 6, párrafo 1 (b) del RGPD).

Como se explica en la Política de tramposos, se rastrearán los logs la actividad de forma automatizada en busca de sospechosa. La base legal para este tratamiento de datos es el artículo 6, párrafo 1 (f) del RGPD.

### Quién tiene acceso a la información ###

El alias público de Telegram y los datos relacionados con la cuenta de Pokémon GO podrán compartirse en grupos o canales en los que se mantenga actividad. Esta compartición puede ser pública, dependiendo de la configuración de cada grupo o canal.

El identificador numérico y alias público de Telegram y el nombre de entrenador de Pokémon GO podrán compartirse con los administradores de los grupos o canales en los que se realice alguna actividad.

La base legal para compartir los datos proporcionados es la prestación del servicio que se solicita voluntariamente (artículo 6, párrafo 1 (b) del RGPD).

### Duración del almacenamiento ###

La información se almacena durante el tiempo necesario para cumplir con los fines para los que se se recopila:

La información de la cuenta de Pokémon GO y alias de Telegram se eliminan al pasar seis meses desde la última participación en un grupo en el cual esté el bot.
Las interacciones en grupos y directas con el bot (logs) se eliminan pasados dos meses.

### Derechos contemplados en el RGPD ###

Se debe enviar un correo a [apelaciones@qwert1.es](mailto:apelaciones@qwert1.es) indicando que se desea ejercer alguno de los derechos contemplados: acceso, rectificación, supresión y limitación del tratamiento, portabilidad de datos.

En caso de ejercitar el derecho de supresión, el bot guardará el identificador numérico de Telegram junto con una marca que indica este deseo. En este caso, no será posible utilizar el bot y el estado de la cuenta aparecerá como baneada.
