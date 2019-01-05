Enfermera Joy es un bot especializado en gestionar grupos de Pokémon GO en Telegram.

Puedes pedir ayuda en el grupo [@enfermerajoyayuda](https://t.me/enfermerajoyayuda) y estar informado de las novedades en el canal [@enfermerajoynoticias](https://t.me/enfermerajoynoticias).

1. [Ayuda para entrenadores](#ayuda-para-entrenadores)
   1. [Registrarse en el bot](#registrarse-en-el-bot)
      1. [Alias de Telegram](#alias-de-telegram)
      2. [Subida de nivel](#subida-de-nivel)
      3. [Cambio de nombre de entrenador](#cambio-de-nombre-de-entrenador)
      4. [Cambio de cuenta de Telegram](#cambio-de-cuenta-de-telegram)
   2. [Profile](#profile)
   3. [Iconos en la Ficha de Entrenador](#iconos-en-la-ficha-de-entrenador)
   4. [Código de Entrenador](#código-de-entrenador)
   5. [Quién es](#quién-es)
   6. [Tablas](#tablas)  
   7. [Registrar nidos](#registrar-nidos)  
   8. [Listado de comandos](#listado-de-comandos) 
   9. [Listas](#listas) 
   10. [Glosario de comandos para entrenadores](#glosario-de-comandos-para-entrenadores)
   11. [Más ayuda](#más-ayuda)
2. [Ayuda para administradores](#ayuda-para-administradores)
   1. [Añadir el bot a un grupo o canal](#añadir-el-bot-a-un-grupo-o-canal)
   2. [Configuración básica](#configuración-básica)
      1. [Ajustes generales](#ajustes-generales)
      2. [Ajustes de entrada](#ajustes-de-entrada)
      3. [Configurar nidos](#configurar-nidos)
      4. [Noticias](#noticias)
      5. [Bienvenida](#bienvenida)
   3. [Configuración Admins](#configuración-admins)
      1. [Ajustes del grupo de Admins](#ajustes-del-grupo-de-admins)
      2. [Vincular grupos al grupo de Admins](#vincular-grupos-al-grupo-de-admins)
   4. [Zona horaria](#zona-horaria)
   5. [Gestión de usuarios](#gestión-de-usuarios)
   6. [Comandos personalizados](#comandos-personalizados)
   7. [Otros comandos exclusivos para administradores](#otros-comandos-exclusivos-para-administradores)
      1. [Moderación de un usuario](#moderación-de-un-usuario)
      2. [Moderación de varios usuarios](#moderación-de-varios-usuarios)
   8. [Glosario de comandos para administradores](#glosario-de-comandos-para-administradores)
3. [Reglamento General de Uso del Bot](#reglamento-general-de-uso-del-bot)
4. [Política de privacidad](#Política-de-privacidad)


## Ayuda para entrenadores ##

### Registrarse en el bot ###

El registro puede ser obligatorio en algunos grupos (todo depende de la configuración del grupo), pero para poder interactuar con el bot, es imprescindible el registro.

Registrarte te permite disfrutar de todas las funcionalidades del bot, como por ejemplo preguntar por otros usuarios, solicitar información de los Pokémon y muchas más funcionalidades que llegarán en un futuro.

Para registrarte (es necesario tener un [Alias de Telegram](#alias-de-telegram)) tienes tres opciones:

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
|        ⛔        | Baneado                          |
|        👩‍⚕️        | Staff                            |

### Código de Entrenador ### 

Si quieres, puedes compartir tu código de entrenador con el bot para que cuando pregunten por ti con el comando `quién es` (para más información sobre este comando mira el apartado [Quién es](#quién-es)), aparezca junto al resto de información. Únicamente verán tu código aquellas personas que hayan compartido el suyo con el bot.

Para compartir tu código de entrenador, lo debes hacer con el siguiente comando por privado a [@NurseJoyBot](https://t.me/NurseJoyBot) (el número sin espacios y separado del comando). Por ejemplo:

    /set_friendid 123412341234
    
Una vez hecho esto, es necesario autorizar a la enfermera Joy para que vuestros códigos sean visibles, para ello deberás escribir el comando `/privacity` por el chat privado a [@NurseJoyBot](https://t.me/NurseJoyBot).

Al escribir el comando verás las opciones de privacidad del bot. Clica sobre "Friend Code" y una vez allí podrás activar (✅) o desactivar (❌) la autorización para que Joy comparta tu código con otros jugadores.

Si aceptas el resto de jugadores podrán ver tu cógido, pero tú podrás ver los suyos. Si no aceptas, el resto de jugadores no podrán ver tu cógido, pero tú tampoco podrás ver los suyos.

Si has autorizado a Joy que comparta tu código, tienes dos formas para ver el código de los demás entrenadores:

1) Escribiendo `/fc` o `/fclist` en un grupo. El bot te enviará un listado de todos los IDs conocidos del grupo por privado.

2) Escribiendo el comando `quien es`. Para saber más sobre este comando ver el apartado [Quién es](#quién-es).

En ambos casos, clicando sobre el número este será automáticamente copiado para que puedas ir al juego Pokémon Go y agregarlos sin dificultad.

Si intentas ver el código de entrenador de otro jugador y no has aceptado compartir el tuyo entonces el bot te enviará por privado un mensaje diciendo que no cumples los requisitos para solicitarlo.

Si quieres eliminar de tu Ficha de Entrenador la información del ID puedes hacerlo escribiendo: `/set_friendid -`. Recuerda que también puedes desactivar la autorización para que Joy comparta tu ID de entrenador y de esa forma el resto de jugadores no podrán acceder a esa información.

### Quién es ###

El comando `quién es` (también aceptado como `quien es` o `/whois`, sin interrogante) hace que el bot te responda la información de la Ficha de Entrenador (Nick del juego, Equipo, Nivel y Estado de Validación) del jugador solicitado.

Ejemplos de posibles respuestas de Joy:

1. **Berny**, es del equipo **Instinto** nivel **40** ✅

   El Entrenador utiliza el nick de Berny en el juego, es del equipo Instinto, nivel 40 y está validado. Aunque no es frecuente, la        Ficha de Entrenador puede tener otros iconos. Para más información leer el apartado [Iconos en la Ficha de Entrenador](#iconos-en-la-ficha-de-entrenador).

2. ❌ No tengo información sobre este entrenador.
   
   El Entrenador no está registrado.

3. *Desconocido*, es *Desconocido* nivel *Desconocido*.

   El Entrenador ha iniciado un proceso de registro, pero no se ha terminado correctamente.

El bot siempre enviará la información al privado, por ello es imprescindible tener abierta una conversación privada con [@NurseJoyBot](https://t.me/NurseJoyBot).

Se puede emplear el comando de varias formas:

1. Citando el mensaje del jugador por el grupo general y escribiendo el comando. 

2. Citando un mensaje reenviando del jugador y escribiendo el comando.

3. Escribiendo el comando y escribiendo el Nick del juego del entrenador del que quieres información. Por ejemplo: `/whois Berny`.

4. Escribiendo el comando y escribiendo el Alias de Telegram (sin la @). Por ejemplo: `/whois bernyelperro`.

**Cosas a tener en cuenta:**

Los cuatro métodos anteriores funcionan tanto por grupo como por privado.

Si el comando se realiza por un grupo y el bot tiene permisos para borrar mensajes entonces este eliminará automáticamente el mensaje donde esté el comando y responderá con un mensaje que también será eliminado cuando hayan pasado unos segundos.

Si el comando se realiza por privado al bot [@NurseJoyBot](https://t.me/NurseJoyBot), lógicamente, los mensajes no serán borrados.

### Tablas ###

El bot dispone de una gran cantidad de tablas de IV, de recompensas por amistad, Pokémon de los Community Day, Pokémon shiny, etc. Para solicitarlas se debe emplear el comando `/tabla` o `/table` seguido de un espacio y el nombre de la tabla que se desea. El mensaje solicitando la tabla será eliminado por el bot de forma automática.

Todas las tablas son mandadas al privado del bot, para ello es necesario tener abierta una conversación privada con [@NurseJoyBot](https://t.me/NurseJoyBot).

Estos son las tablas de IV las que se disponen actualmente:

- Absol
- Articuno
- Celebi
- DeoxysA (versión ataque, es la forma activa en el juego. También se puede solicitar como: Deoxys o aDeoxys)
- DeoxysACounters (mejores counters contra Deoxys versión ataque. También se puede solicitar como: CountersDeoxysA)
- DeoxysD (versión defensa)
- DeoxysN (versión normal)
- DeoxysV (versión velocidad)
- Entei
- Gengar
- Giratina (la forma activa en el juego)
- GiratinaO (versión Origen, también se puede solicitar como: OGiratina)
- GiratinaM (versión modificada, también se puede solicitar como: MGiratina)
- Golem
- Groudon
- Heatran
- Ho-oh
- Kyogre
- Lapras
- Latias
- Latios
- Lugia
- Machamp
- Magikarp
- Marowak (versión alola)
- Mawile
- Mew
- Mewtwo
- Moltres
- Raichu (versión alola)
- Raikou
- Rayquaza
- Regice
- Regirock
- Registeel
- Rhydon
- Shedinja
- Shinx
- Snorlax
- Spiritomb
- Suicune
- Tyranitar
- Zapdos

***

Tablas de Community Day:

- Beldum
- Cyndaquil
- Totodile (también se puede solicitar como: Community)

***

Otras tablas:

- Amistad
- Community
- Ditto (pokémon que pueden transformarse en Ditto)
- Evento (tabla con información del evento actual. También se puede solicitar como: eventos)
- Huevos (qué pokémon puede salir de cada huevo. También se puede solicitar como: huevo, eclosión o eclosiones)
- Jefes (también se puede solicitar como: raid, raids, incursión incursiones o jefe)
- Sellos (tabla con las recompensas que se puden obtener en las cajas del séptimo sello)
- Shiny (también se puede solicitar como: Shinys)
- Sinnoh (tabla con las evoluciones que se pueden hacer actualmente con la piedra Sinnoh. También se puede solicitar como: piedrasinnoh)

Todas las tablas se van modificando según los cambios que van surgiendo en Pokémon Go y se van añadiendo tablas nuevas necesarias, por lo tanto la lista de tablas es algo que irá cambiando.

### Registrar nidos ###

El bot dispone de registro de nidos, para ello debe de estar configurado el grupo para aceptar su registro. Esta configuración únicamente la puede realizar un administrador de dicho grupo. Si eres administrador de un grupo y quieres saber más información al respecto lee el apartado [Configurar nidos](#configurar-nidos).

Para registrar un nido se debe emplear el comando `Registrar nido de {Pokémon} en {Lugar}` cambiando la variable {Pokémon} por el nombre del Pokémon del que sea el nido y {Lugar} por el nombre por el cual se reconozca ese espacio. Por ejemplo:

`Registrar nido de Chansey en Parque Ilm`. En este caso, es *Chansey* la variable {Pokémon} y *Parque Ilm* la variable {Lugar}.

Antes de poner el nombre del lugar ten en cuanta que el número máximo de carácteres que registra es 50.

Este comando también lo puedes escribir como: :feet:

`Registro nido de {Pokémon} en {Lugar}`

`Registrar spawn de {Pokémon} en {Lugar}`

`Registro spawn de {Pokémon} en {Lugar}`

Para que el bot te mande una lista de todos los nidos o spawns que se haya registrado en tu grupo, debes utilizar el comando `Listado de nidos`. Este comando lo puedes escribir en el grupo y Joy responderá borrando el comando y avisando de que alguien ha solicitado la lista y ofreciendo mandarsela a quien la solicite pulsando en el botón de "Yo!". La lista será mandada al privado del bot.

Si el nido es erroneo y se quiere borrar antes de que Joy los reinicie entonces se deberá utilizar el comando `Eliminar nido número {Número del nido}`. Puedes encontrar la variable {Número del nido} al solicitar el *Listado de nidos*. También se puede borrar todos los nidos de golpe empleando el comando `Eliminar todos los nidos de este grupo`. Estos dos comandos (de borrar nidos) son exclusivos para administradores.

Otros dos comandos relacionados con los nidos son:  `Nido en {Lugar}` y `Nido de {Pokémon}`.

`Nido en {Lugar}`, por ejemplo, "Nido en Parque Ilm".

Según el ejemplo, el bot te buscará en sus datos si hay registrado algún nido en el lugar llamado *Parque Ilm* y, si lo hay, te dirá de qué pokémon se trata.

`Nido de {Pokémon}`, por ejemplo, "Nido de Chansey".

Siguiendo también el ejemplo, el bot mirará si hay registrado algún nido de *Chansey* en tu grupo, si lo hay, te responderá con el nombre del lugar donde se ha registrado.

### Listado de comandos ###

Los comandos personalizados pueden ser creados y eliminados únicamente por los administradores. Si eres administrador te recomiendo que leas el apartado [Comandos personalizados](#comandos-personalizados).

Como entrenador y miembro del grupo puedes emplear y hacer que el bot responda con los comandos personalizados que hayan creado los administradores de tu grupo.

Los comandos personalizados son una información própia de cada grupo, es por ello que los comandos cambiarán según en el grupo en el que te encuentres.

Para solicitar el listado de comandos personalizados de un grupo debes escribir en dicho grupo la frase: `Listado de comandos`. La lista de comandos será mandada al privado que tienes con del bot y podrás ver todos los comandos personalizados que tiene ese grupo en concreto. 

Por ejemplo, podría haber un comando personalizado que se llame **Dios bidoof** y que el bot responderá a este con un gif sobre bidoof.

Ten en cuenta que el bot responderá únicamente si la frase que se escribas es únicamente el comando personalizado, sin importar las mayúsculas o minúsculas, y borrará el comando personalizado dejando únicamente su respuesta.

Por ejemplo, si escribieses "dios bidoof" el bot te respondería con el gif, pero si escribieses "Dios bidoof." ya no sería aceptado y el bot no lo detectaría como el comando personalizado.

### Listas ###

Joy dispone de la opción para hacer listas. En estas listas únicamente se podrá decir si vas ("Me apunto!") o si al estar apuntado has decidido no ir ("Paso...").

Para crear una lista se debe emplear el comando `/list` y añadir el título que tendrá la lista. Por ejemplo:

`/list Esto es una lista con un mensaje.`

Los entrenadores que se apunten a dicha lista aparecerán junto a la siguiente información: Equipo, Nivel y Alias de Telegram.

Con el comando `/joyrefloat` puedes reflotar una lista si esta ha quedado hundida. Para ello será necesario citar la lista y escribir el comando.

Si se quiere borrar una lista bastará con eliminar el mensaje que sea la lista.

### Glosario de comandos para entrenadores ###

Comando | Descripción | Exclusivo administradores | Ámbito | Parámetros
--------|-------------|---------------------------|--------|-----------
`Registrar nido de {Pokémon} en {Lugar}`| ? | ❌ | Grupo | `Pokémon Lugar`<sup>1</sup>
`Listado de nidos`| ? | ❌ | Grupo | ❌
`Eliminar nido número {Número del nido}`| ? | ✅ | Grupo | `Número del nido`
`Eliminar todos los nidos de este grupo`| ? | ✅ | Grupo | ❌
`Nido en {Lugar}`| ? | ❌ | Grupo | `Lugar`<sup>1</sup>
`Nido de {Pokémon}`| ? | ❌ | Grupo | `Lugar`<sup>1</sup>
`Listado de comandos`| ? | ❌ | Grupo | ❌
`/list`| ? | ❌ | Todos | ❌
`/joyrefloat`| ? | ✅ | Todos | ❌
`/start`| ? | ❌ | Todos | ❌
`/help`| ? | ❌ | Todos | ❌
`/register`| ? | ❌ | Privado | ❌
`/set_friendid`| ? | ❌ | Privado | `ID de Pokémon GO`
`/privacity`| ? | ❌ | Privado | ❌
`/fc`| ? | ❌ | Grupo | ❌
`/fclist`| ? | ❌ | Grupo | ❌
`Quién es`| ? | ❌ | Todos | ❌
`Quién es ´{Entrenador}`| ? | ❌ | Todos | `Nombre de entrenador`
`/profile`| ? | ❌ | Todos | ❌
`/tabla {Pokémon}`| ? | ❌ | Todos | `Tabla disponible`
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

Para hacer la **configuración básica** del bot utiliza el comando `/settings`. Este comando se utiliza en el grupo que quieras configurar. La configuración está dividida en varios apartados y subapartados:

1. [Ajustes generales](#ajustes-generales) (Configuraciones básicas de juegos y modo de administración.)
      1. [Chistes](#chistes) `Actualmente esta opción no está disponible.`
      2. [Juegos](#Juegos) `Actualmente esta opción no está disponible.`
      3. [Modo enfermera](#modo-enfermera)   
      4. [Tipo de expulsión por Warns](#tipo-de-expulsión-por-warns)
      5. [Cantidad de Warns](#cantidad-de-warns)      

2. [Ajustes de entrada](#ajustes-de-entrada) (Configuración de los tipos de grupo y los requisitos.)
      1. [Tipo de grupo](#tipo-de-grupo)
      2. [Requisito de nivel](#requisito-de-nivel)
      
3. [Configurar Nidos](#configurar-nidos) (Configuración de los nidos y requisitos para el registro)
      1. [Nidos](#nidos) 
      2. [Requisito de cantidad de días](#requisito-de-cantidad-de-días)
      3. [Requisito de cantidad de mensajes](#requisito-de-cantidad-de-mensajes)
      
4. [Noticias](#noticias) 
      1. @pokemongohonesto
      2. @enfermerajoynoticias
      3. @detectivepikachunoticias
      4. @noticiasPoGo
      5. @teamRocketFake

5. [Bienvenida](#bienvenida)
      1. Bienvenida

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

Determina un nivel mínimo como requisito para entrar al grupo. Esta opción viene activada por defecto como 0, eso quiere decir que no hay nivel mínimo requerido.

El nivel mínimo para entrar en el grupo se puede configurar, clicando en el botón hasta que salga la opción deseada, según: 0 (sin nivel requerido), 15, 20, 25, 30, 35 o 40.

#### Configurar Nidos ####

El bot dispone de la opción de registrar nidos, para ello es necesario configurar el apartado de Nidos y sus requisitos.

##### Nidos ##### 

Clicando sobre el botón `Nidos` podrás activar o desactivar esta opción para que no pueda entrar en conflicto con otros bots que puedan estar haciendo la misma función en el grupo.

| Identificador   | Definición                       |
|:----------------|:---------------------------------|
|    ▪️ Nidos      | Registro de nidos desactivado |
|    ✅ Nidos    | Registro de nidos activado |    

El registro de nidos viene desactivado por defecto.

Para saber cómo registrar un nido o spawn, o para borrar los que haya registrados leer el apartado [Registrar nidos](#registrar-nidos).

##### Requisito de cantidad de días #####

Para determinar el número mínimo de días que un jugador ha de pertenecer al grupo para poder registrar un nido es necesario clicar sobre el botón hasta que aparezca la opción deseada. La cantidad de días que se pueden configurar son: 0 (sin requisito de días), 1, 3, 5, 7, 15 o 30.

Por defecto viene configurado el requisito como sin requisito, 0 días.

##### Requisito de cantidad de mensajes #####

Para determinar el número mínimo de mensajes que un jugador debe de hacer en un grupo para poder registrar un nido se debe de clicar sobre el botón hasta que aparezca la opción deseada. La cantidad de mensajes requeridos que se puede configurar son: 0 (sin requisitos), 1, 5, 10, 20, 50 o 100.

Por defecto, este requisito, viene configurado como sin requisitos, 0 mensajes.

#### Noticias ####

El bot dispone de la opción de *Noticias*: Eso quiere decir que puede reenviar automáticamente las publicaciones que salgan en distintos canales.

Para poder ver este apartado es necesario haber escrito el comando `/settings` y haber accedido al apartado `Noticias` haciendo click sobre el botón.

Los canales de los que se dipone actualmente son los siguientes:

- @pokemongohonesto (noticias sobre Pokémon Go)
- @enfermerajoynoticias (noticias sobre el bot @NurseJoyBot)
- @detectivepikachunoticias (noticias sobre el bot @detectivepikachu)
- @NoticiasPoGo (noticias sobre Pokémon Go)
- @teamRocketFake (noticias broma de sobre Pokémon Go)

Cada uno de los siguientes canales tienen sus própias características por los cuales son importantes y seguidos: algunos son de noticias sobre bots, noticias sobre el juego o noticias de broma.

Es decisión de cada grupo activar o no el reenvio de las noticias (y cuales) para mantenerse informados. Por defecto todas las noticias estarán desactivadas. Para activarlas se debe clickar encima del botón y cuando ponga delante el icono ✅, si pone el icono ▪️ quiere decir que esas noticias estarán desactivadas y no serán enviadas al grupo.

#### Bienvenida ####

El bot puede dar la bienvenida a los entrenadores que vayan entrando al grupo. Opción desactivada por defecto. 

Para activar la Bienvenida es necesario activarla en Settings y después es necesario utilizar el comando `/set_welcome` para definir el mensaje de bienvenida que dará el bot. Por ejemplo, si se quiere poner el mensaje "Bienvenidos al grupo", sería:

    /set_welcome Bienvenidos al grupo.

Además el bot dispone de tres strings que se pueden introducir en el texto de bienvenida para conocer más información del entrenador que acaba de entrar. Por ejemplo:

| Strings | Texto mostrado       | Definición                              |
|:--------|:---------------------|:----------------------------------------|
|  {pogo}  | Berny **L40** 💛 ✅  | Nick +Nivel +Equipo +Proceso validación |
|{usuario}| Berny                | Nick                                    |
| {title}  | PoGo de tu ciudad    | Nombre del grupo       | 
| {id}  | 123456789    | ID de Telegram                    | 
| {nombre}  | Perrito   | Nombre en Telegram              | 
| {apellido}  | Lindo   | Apellido en Telegram            | 
| {mention}  | @bernyelperro   | Alias de Telegram           | 
| {count}  | 35   | Contador de usuarios que entran al grupo           | 

Para poner links en el mensaje de bienvenida lo puedes hacer mediante el siguiente string: `[NombreLink](Link)`.
Por ejemplo: `[superjoy](https://websuperenfermerajoy.com)`. Este link que veremos en el mensaje de bienvenida como `superjoy` al clickarlo nos mandará a la web `https://websuperenfermerajoy.com`.

El bot también puede tener botones en el mensaje de bienvenida, para ello se debe escribir de la siguiente manera: `[Texto a mostrar en el botón](buttonurl://dirección.com)`. Se debe escribir todo junto, sin espacio, y cambiar el texto del botón y el enlace. Como ejemplo:

`[Enlace a google.es](buttonurl:Google.es)`

Para escribir más de un botón en una misma línea se ha de escribir `:same` al final de la dirección. En el siguiente ejemplo se verían 3 botones seguidos (Botón 1, 2 y 3) y en la siguiente línea dos botones (Botón 4 y 5).

`[Botón 1](buttonurl:Google.es)`
`[Botón 2](buttonurl:Google.es:same)`
`[Botón 3](buttonurl:Google.es:same)`
`[Botón 4](buttonurl:Google.es)`
`[Botón 5](buttonurl:Google.es:same)`

Para escribir texto en **negrita** dentro del mensaje de bienvenida se debe escribir con un * antes y después del texto, para escribir en *cursiva* se debe escribir, antes y después del texto, un _ .

Si se quiere eliminar el mensaje de bienvenida, para que el bot deje de saludar cuando entren entrenadores nuevos, entonces se debe escribir el comando `/set_welcome` sin ningún texto más.

### Configuración Admins ###

#### Ajustes del grupo de Admins ####

Escribe, en el grupo de administración (el grupo de admins) el comando `/settings_admin`. Este comando te permitirá activar distintas opciones de avisos que llegarán al grupo de Admins de los grupos que tenga vinculados (leer apartado [Vincular grupos al grupo de Admins](#vincular-grupos-al-grupo-de-admins)). No te preocupes mucho si no sabes bien bien qué activar, dispondrás siempre de este comando y podrás activar o desactivar las opciones siempre que lo necesites recurriendo a ese comando.

Opciones de las que dispones:

   - Aviso de la gente que entra al grupo o grupos vinculados.

   - Aviso de la gente que sale del grupo o grupos vinculados. (sólo avisará si son grupos de 50 usuarios o menos, o si ha salido del grupo por ban o kick)

   - Aviso cuando se escribe @admin en el grupo o grupos vinculados.

   - Aviso de expulsiones y baneos individuales en el grupo o grupos vinculados.

   - Aviso de los warn en el grupo o los grupos vinculados.

   - Aviso de la solicitud de nidos en el grupo o grupos vinculados.

#### Vincular grupos al grupo de Admins ####

Para crear un grupo de administración que tenga uno o diversos grupos vinculados se debe seguir los siguientes pasos:

1. Ejecutar el comando `/create_admin` en el grupo al cual quieres que vaya la información, el que será el grupo de Admins. Para configurar el grupo de Admins leer el apartado: [Ajustes del grupo de Admins](#ajustes-del-grupo-de-admins)

Es importante guardar el ID que te dará el bot, lo necesitarás más adelante.

`Como ejemplo, a nosotros nos daría: ID -123456.`

2. Seguidamente ve al grupo que quieres vincular y ejecuta en dicho grupo el comando `/create_link ID`.

`En nuestro caso de muestra sería: /create_link -123456.`

3. Vuelve al grupo de administradores e indica, en la botonera, de qué trata el grupo que acabas de vincular. Las opciones de las que dispones son las siguientes:

Icono | Nombre | Descripción 
--------|-------------|---------------------------
💥   | Raids | Grupo para incursiones (Raids)
:repeat:   | Intercambios | Grupo para intercambios de Pokémon
🗣   | Charla | Grupo de charla
👫   | Amigos | Grupo de amigos
🌟   | EX | Grupo para incursiones (Raids) EX
👀   | Alertas | Grupo para alertas
🔍   | Misiones | Grupo para misiones
👾   | Otros | Cuando ninguno de los otros define tu grupo, este es el indicado
❤️   | Valor | Grupo para miembros del equipo rojo (Valor)
💛   | Instinto | Grupo para miembros del equipo amarillo (Instinto)
💙   | Sabiduría | Grupo para miembros del equipo azul (Sabiduría)

4. Para vincular más de un grupo a un mismo grupo de administradores vuelve al paso número 3 (la ID será la misma del paso número 1).

Si quieres que el bot deje de considerar un grupo como grupo de administración puedes hacerlo escribiendo `/rm_admin` en dicho grupo. Con ese comando se desvincularán todos los grupos que tuvieses vinculados. Si sólo quieres desvincular un grupo entonces dirígete a ese grupo y ejecuta el comando `/rm_link`.

Para saber qué grupos están vinculados a un grupo de administración escribe el comando `/groups` y el bot te hará una lista de los grupos vinculados, excepto el de administración.

### Zona horaria ###

El bot reconoce la hora que escriben los usuarios y hace operaciones con ellas, por lo que es importante que la hora que utilice el bot se corresponda con la hora real de tu grupo.

Para establecer la zona horaria correcta se debe utilizar el comando `/settimezone` con la zona horaria correspondiente como parámetro siguiendo el formato del [listado de zonas horarias de la IANA](https://en.wikipedia.org/wiki/List_of_tz_database_time_zones). Por ejemplo:
    /settimezone Europe/Madrid
    /settimezone Atlantic/Canary

### Gestión de usuarios ###

Para saber la cantidad de entrenadores que de cada equipo que hay en un grupo y saber los entrenadores que no están validados, puedes emplear el comando ´/joyuv´ y el bot te mostrará un mensaje parecido a este:

💙 Azules: 10

💛 Amarillos: 3

❤️ Rojos: 8

(corazón negro) No Validados: 5

(?) Desconocidos: 12

Los nicks de los entrenadores de uno de los equipos se pueden ver mediante:

💙 Azules (equipo Sabiduría) -> `/joyuv B`

💛 Amarillos (equipo Instinto) -> `/joyuv Y`

❤️ Rojos (equipo Valor) -> `/joyuv R`

No Validados -> `/joyuv L`

El comando `/joykickuv` sirve para expulsar a todos aquellos No Validados en el bot. El bot no puede expulsar a los que no conoce, pero si a los que no están validados y conoce.
*AVISO:* antes de usar el comando `/joykickuv` ten en cuenta que los únicos bots validados con @nurseyjoybot son: @detectivepikachubot, @nidospokemonbot, @ProfesorOak_bot y el própio bot @nurseyjoybot.

### Comandos personalizados ###

Los comandos personalizados pueden ser creados y eliminados únicamente por los administradores. Estos comandos personalizados harán que el bot responda con una frase, imagen, link, fichero, video, audio, nota de voz o gif.

Pasos para crear comandos:
   1. Para crear un comando personalizado se debe escribir `nuevo comando`.
   2. Seguidamente el bot te preguntará qué nombre quieres ponerle a dicho comando a lo que deberás responder únicamente con el nombre        que quieras que tenga (máximo 30 carácteres). Ten en cuenta que cada vez que el bot lea ese comando responderá automáticamente con      la respuesta que le vas a dar. Una vez le digas el nombre del comando el bot te pedirá la respuesta que quieres que dé.
   3. Aquí es cuando puedes escribir una frase, poner un gif, un link, un audio, una nota de voz, un video, un fichero o una imagen.
   
Por ejemplo, podría haber un comando personalizado que se llame "Dios bidoof" y que el bot responderá a este con un gif sobre bidoof.

Además, el bot responderá únicamente si la frase que se escriba es únicamente el comando personalizado, sin importar las mayúsuculas o minúsuclas, y borrará el comando personalizado dejando únicamente su respuesta.

Para que el bot te diga todos los comandos registrados en un grupo se debe emplear la frase: `Listado de comandos`. La lista de comandos será mandada al privado del usuario que lo solicite sin importar si es administrador o no.

Si deseas borrar un comando puedes hacerlo con `eliminar comando {número del comando}`, substituyendo la variable {número del comando} por el número del comando personalizado que tenga en el "Listado de comandos". Por ejemplo:

`Borrar comando 55`

En este caso el comando que se borraría sería el comando que corresponda al número 55.

Si al intentar borrar un comando personalizado el bot te responde que este no existe te recomiendo que le solicites al bot la lista de comandos (está explicado más arriba, en este mismo apartado, cómo se hace) para que te asegures de qué comando quieres eliminar.

Para borrar todos los comandos personalizados de golpe se puede hacer mediante el comando `eliminar todos los comandos`, pero tener cuidado que si el bot tenía en uno de ellos alguna información que querías conservar esta se perderá.

Si en vez de borrar un comando lo que se quiere es únicamente modificar la respuesta del bot, entonces bastará con crear de nuevo un comando con el mismo nombre.

### Otros comandos exclusivos para administradores ###   
`En proceso de escritura`

Algunos de los comandos más importantes para un administrador son los de tipo "castigo". Estos comandos únicamente pueden ser utilizados por los administradores, y si algún usuario lo escribiese el bot respondería que dicho usuario no tiene permisos para ello.

#### Moderación de un usuario ####

La mayoría de bots disponen de tres "castigos" muy diferenciados: Warn, Kick y Ban.

   Warn - El Warn es un aviso (advertencia), que después de una determinada cantidad de avisos será una expulsión del grupo por kick o ban (dependiendo de cómo esté configurado). Para ver la configuración de los Warn leer el apartado [Tipo de expulsión por Warns](#tipo-de-expulsión-por-warns) y [Cantidad de Warns](#cantidad-de-warns).

   Kick - El Kick es la expulsión del grupo a un usuario, pero este podrá volver a entrar al momento.
   
   Ban - El Ban es la expulsión del grupo a un usuario, y este no podrá volver a entrar al grupo hasta que un administrador le quite el ban.

#### Moderación de varios usuarios ####

Como se ha dicho, la mayoría de bots disponen de estos tres, al menos de los dos últimos, pero `@NurseJoyBot` dispone, además, de muchos más que facilitarán la labor de los administradores.

Antes de empezar con el listado debes saber que todos los comandos de este apartado funcionan tanto con la ID de Telegram del usuario al que se quiere expulsar o avisar, como citando un mensaje de dicho usuario.

Este comando se puede emplear desde el grupo en el cual se quiere dar el aviso o desde el grupo de Admins especificando el grupo como variable.

Tipos de Warn:

`/warn` - Advierte al usuario. Este comando se puede emplear únicamente en el grupo en el cual se quiere advertir al entrenador. Se puede escribir también como `/warn {Motivo}`, siendo `{Motivo}` un texto de no más de 30 carácteres escrito por el administrador justificando la advertencia. Por ejemplo: `/warn lenguaje inapropiado`
   
`/warnuv` 

`/warnmsg {Nº Mensajes}` - Advierte a los usuarios que hayan enviado menos de X mensajes, siendo X el número de mensajes especificados en el parámetro. Por ejemplo: `/warnmsg 20`

`/warnold {Días}` - Advierte a los usuarios que no han hablado en los últimos X días, siendo X los días especificados en el parámetro. Por ejemplo: `/warnold 20`

`/warnall {ID usuario}` 

`/warngroup {ID usuario}` 

Tipos de Kick:

`/kick`   Grupo  `{Equipo}`

`/kickuv` 

`/kickmsg {Nº Mensajes}`  - Expulsa a los usuarios que hayan enviado menos de X mensajes, siendo X el número de mensajes especificados en el parámetro. Por ejemplo: `/kickmsg 20`

`/kickold {Días}` - Expulsa a los usuarios que no han hablado en los últimos X días, siendo X los días especificados en el parámetro. Por ejemplo: `/kickold 20`

`/kickall {ID usuario}`

`/kickteam {Equipo}` - Expulsa a todos los usuarios registrados del equipo TEAM (R para rojo, B para azul o Y para amarillo). Por ejemplo, /kickteam Y para expulsar a los del equipo amarillo.

`/kickgroup {ID usuario}`

`/kickeveryone`

Tipos de Ban:

`/ban`: Citando el mensaje y escribiendo el comando en la respuesta. Puede ir seguido del motivo del ban.

`/banuv`: Se puede hacer desde el grupo o desde el grupo de administración, si se hace desde el de administración se puede especificar el grupo al cual va dirigido el ban, sino baneará al entrenador de todos los grupos vinculados al grupo de administración.

`/banmsg {Nº Mensajes}` - Expulsa y no les permite volver a entrar a los usuarios que hayan enviado menos de X mensajes, siendo X el número de mensajes especificados en el parámetro. Por ejemplo: `/banmsg 30`

`/banold {Días}` - Expulsa y no les permite volver a entrar a los usuarios que no han hablado en los últimos X días, siendo X los días especificados en el parámetro. Por ejemplo: `/banold 30`

`/banall {ID usuario}`: únicamente se puede realizar desde el grupo de administración `UserID Motivo`<sup>2</sup>

`/banteam {Equipo}`

`/bangroup {ID usuario}` 

El comando para quitar el Ban a un usuario es:

`/unban` - Desbanea a un usuario. También se puede desbanear sin necesidad de comando en: Ajustes de Grupo -> Administrar grupo -> Suspendidos.

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
`nuevo comando`| ? | ✅ | Grupo | ❌
`eliminar comando {nombre del comando}`| ? | ✅ | Grupo | `{nombre del comando}`
`eliminar todos los comandos`| ? | ✅ | Grupo | ❌
`Listado de comandos`| ? | ❌ | Grupo| ❌
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

En caso de ejercitar el derecho de supresión, el bot guardará el identificador numérico de Telegram junto con una marca que indica este deseo. En este caso, no será posible utilizar el bot y el estado de la cuenta aparecerá como baneada y eliminada.

Para eliminar sus datos se requerirá de su Documento Nacional de Identidad con fines acreditativos y de defensa en futuras reclamaciones. [Fuente 1 - Página 21 Apartado 5.4](https://www.aepd.es/media/guias/guia-ciudadano.pdf) [Fuente 2](https://ayudaleyprotecciondatos.es/2016/06/18/los-derechos-arco-acceso-rectificacion-cancelacion-y-oposicion/) 


