# What's new in LGA PipeSync

## v1.030 (2026-11-17)

- **New:** Tools users: en LGA Updates del tab TOOLS aparece LGA GateBouncer, el firewall de LGA para Windows: lo instalás y lo actualizás desde ahí. (Studio, Windows only)
- **New:** Tools users: en LGA Updates del tab TOOLS aparece LGA GateBouncer, el firewall de LGA para Windows: lo instalás y lo actualizás desde ahí. (Client, Windows only)
- **New:** Reviewers, coordinators, producers and admins: en los proyectos que tienen Shot Docs, la tarjeta de cada shot suma un botón que abre su escena en Shot Docs (en la app de Shot Docs si la tenés instalada en la Mac), y el menú del click derecho de PROD e INBOX trae Show scene in Shot Docs y Copy Shot Docs link. (Studio only)
- **New:** Admins: en el tab PROJECTS, la columna Shot Docs prende el link de cada proyecto y guarda cómo se llama allá. (Studio only)
- **New:** Production editors: en el tab PROD podés deshacer y rehacer los últimos tres cambios de la tabla con Ctrl+Z y Ctrl+Shift+Z (Cmd en la Mac) o con los dos botones nuevos del toolbar; si alguien cambió ese mismo valor después, esa fila no se toca y te avisa cuál. (Studio only)
- **New:** Production editors: en el tab PROD podés deshacer y rehacer los últimos tres cambios de la tabla con Ctrl+Z y Ctrl+Shift+Z (Cmd en la Mac) o con los dos botones nuevos del toolbar; si alguien cambió ese mismo valor después, esa fila no se toca y te avisa cuál. (Client only)
- **New:** Production managers: en el tab PROD, Ctrl+Z también deshace Create task, Delete task y Delete shot: lo que borraste vuelve con sus versiones, notas y horas, y una task recién creada se retira. (Studio only)
- **New:** Production managers: en el tab PROD, Ctrl+Z también deshace Create task y Delete task: lo que borraste vuelve con sus versiones, notas y horas, y una task recién creada se retira. (Client only)
- **New:** Shots users: en las tarjetas de shots, cada botón de descarga o subida muestra su avance mientras trabaja, en vez de llevarte al tab QUEUE, y los que usarían la misma carpeta quedan apagados hasta que termina; al pasar el mouse te dicen qué se está haciendo y desde dónde. (Studio only)
- **New:** Shots users: en las tarjetas de shots, cada botón de descarga o subida muestra su avance mientras trabaja, en vez de llevarte al tab QUEUE, y los que usarían la misma carpeta quedan apagados hasta que termina; al pasar el mouse te dicen qué se está haciendo y desde dónde. (Client only)
- **Improved:** Slate users: Slate MXF suma un selector Status al lado de Project: además de las tasks en Review Dir podés listar las de cualquier otro status y armarles el slate sin cambiarlas de status, y lo que dejás tildado queda en la lista al cambiar de status o de proyecto, así un envío junta shots de varios status. (Studio, Windows only)
- **Improved:** el DMG viene firmado y verificado por Apple: la app se abre sin pasar por la Terminal. Por el cambio de firma, macOS te va a volver a pedir una sola vez los permisos que ya le habías dado (carpetas, Finder, notificaciones). (macOS only)
- **Improved:** Tools users: LGA GateBouncer y LGA Mighty Tools, que tienen la interfaz en inglés y en castellano, se instalan desde LGA Updates ya en castellano, y Mighty Tools pasa a castellano la próxima vez que la actualizás desde ahí; el idioma se sigue cambiando en cada app. (Studio only)
- **Improved:** Tools users: LGA GateBouncer y LGA Mighty Tools, que tienen la interfaz en inglés y en castellano, se instalan desde LGA Updates ya en castellano, y Mighty Tools pasa a castellano la próxima vez que la actualizás desde ahí; el idioma se sigue cambiando en cada app. (Client only)
- **Improved:** cuando cambiás el estado de una task con los botones de Push en Nuke Studio, PipeSync abierto lo muestra al instante en SHOTS, REVIEW, PROD y GANTT, sin esperar al próximo sync.
- **Improved:** Ctrl+F (Cmd+F en la Mac) te lleva al buscador del tab que estás viendo; Esc borra la búsqueda y sale del buscador, y Enter sale y la deja aplicada. En GANTT, Ctrl+F abre Search Task.
- **Improved:** Shots users: las versiones de la tarjeta de un shot se actualizan solas cuando termina cualquier descarga o subida de ese shot, aunque falle o se cancele, también lo que bajás o subís con el FileManager dentro del shot. (Studio only)
- **Improved:** Shots users: las versiones de la tarjeta de un shot se actualizan solas cuando termina cualquier descarga o subida de ese shot, aunque falle o se cancele, también lo que bajás o subís con el FileManager dentro del shot. (Client only)
- **Improved:** si otra transferencia está usando la carpeta de un shot, la descarga automática lo deja para la vuelta siguiente, y las descargas de Flow y la subida del MOV a Flow te avisan en vez de pisar archivos a medio escribir.
- **Improved:** Shots users: el FileManager y el Retry del tab QUEUE ya no largan una descarga, subida, copia, movida o borrado sobre un archivo que otra transferencia está usando: te avisan cuál es y qué lo está usando. Lo demás de esa misma carpeta se sigue encolando, así que podés ir subiendo archivos de a uno mientras sube el resto. (Studio only)
- **Improved:** Shots users: el FileManager y el Retry del tab QUEUE ya no largan una descarga, subida, copia, movida o borrado sobre un archivo que otra transferencia está usando: te avisan cuál es y qué lo está usando. Lo demás de esa misma carpeta se sigue encolando, así que podés ir subiendo archivos de a uno mientras sube el resto. (Client only)
- **Improved:** si la conexión falla al buscar o bajar una actualización, PipeSync espera y vuelve a probar solo hasta tres veces.
- **Fixed:** en la tarjeta del shot, una versión v000 local o en Wasabi ahora sale en rojo cuando Flow ya tiene una versión más alta, y la de Flow en verde.
- **Fixed:** si a esta Mac le falta la carpeta local de proyectos, Download Versions from Flow te dice que la configures en SETTINGS en vez de fallar con un error sin ruta, y en cuanto la ponés ya podés bajar sin reiniciar PipeSync. (macOS only)
- **Fixed:** Admins and producers: cerrar el aviso de cambios en las playlists con Dismiss o con la cruz ya no trae PipeSync al frente: seguís en la app en la que estabas. (Studio, macOS only)
- **Fixed:** Admins and producers: cerrar el aviso de cambios en las playlists con Dismiss o con la cruz ya no trae PipeSync al frente: seguís en la app en la que estabas. (Client, macOS only)
- **Fixed:** Shots users: en el tab QUEUE, un path largo ya no se escribe encima de las columnas Size y Progress: si no entra, se abrevia por el medio y deja a la vista el shot y el número de cuadro, y al pasar el mouse ves el path completo. (Studio only)
- **Fixed:** Shots users: en el tab QUEUE, un path largo ya no se escribe encima de las columnas Size y Progress: si no entra, se abrevia por el medio y deja a la vista el shot y el número de cuadro, y al pasar el mouse ves el path completo. (Client only)
- **Fixed:** Auto downloaders: las descargas automáticas ya no abren el cartel «Wasabi access denied» por proyectos en los que no trabajás: los NKS y los assets se bajan solo de tus proyectos, y lo que Wasabi no deja bajar se ve arriba de Auto Download & Upload en SETTINGS, con Details para ver el error. (Studio only)
- **Fixed:** Auto downloaders: las descargas automáticas ya no abren el cartel «Wasabi access denied» por proyectos en los que no trabajás: los NKS y los assets se bajan solo de tus proyectos, y lo que Wasabi no deja bajar se ve arriba de Auto Download & Upload en SETTINGS, con Details para ver el error. (Client only)
- **Fixed:** Shots users: cancelar una subida o una descarga en el tab QUEUE ahora la frena de verdad, y una subida ya no borra de Wasabi los archivos que ya estaban aunque la hayas lanzado con Overwrite existing. (Studio only)
- **Fixed:** Shots users: cancelar una subida o una descarga en el tab QUEUE ahora la frena de verdad, y una subida ya no borra de Wasabi los archivos que ya estaban aunque la hayas lanzado con Overwrite existing. (Client only)
- **Fixed:** Shots users: la pausa del tab QUEUE ahora frena también las descargas de archivos chicos, que antes seguían bajando aunque la cola dijera Paused. (Studio only)
- **Fixed:** Shots users: la pausa del tab QUEUE ahora frena también las descargas de archivos chicos, que antes seguían bajando aunque la cola dijera Paused. (Client only)
- **Fixed:** Shots users: la tarjeta de un shot ya no muestra como local una versión cuya carpeta está vacía, como la que queda si cancelás una descarga antes de que baje el primer archivo. (Studio only)
- **Fixed:** Shots users: la tarjeta de un shot ya no muestra como local una versión cuya carpeta está vacía, como la que queda si cancelás una descarga antes de que baje el primer archivo. (Client only)
- **Fixed:** las personas con tilde o eñe en el nombre reciben el acceso a sus shots cuando se les asigna una task desde una Mac; antes les aparecía «Wasabi access denied» al abrirlos. (macOS only)

## v1.029

- **New:** En las tarjetas de shots, un click en la descripción de una task la abre completa en una ventana aparte que podés mover, leer mientras trabajás y copiar.
- **New:** Reviewers: en el tab REVIEW, cada task tiene un botón de descarga junto a EXR Publish (o Publish): un click baja la última versión publicada a la carpeta de la task, y Shift+Click abre la lista de versiones para elegir cuáles bajar. (Studio only)
- **Improved:** El recorrido guiado para artistas muestra dónde está la descripción de la task y cómo abrirla completa con un click. (Studio only)
- **Improved:** el recorrido guiado para artistas explica cómo cargar en Mis horas lo que no es de un shot, como la reunión de inducción o instalar tus herramientas el primer día. (Studio only)
- **Improved:** Team time users: en el Registro del equipo, Enter cierra la ventana; para ir a Stats está el botón Abrir Stats. (Studio only)
- **Improved:** Team time users: al agrandar la ventana del Registro del equipo, el espacio extra muestra más personas de la tabla en vez de separar los textos. (Studio only)
- **Improved:** 3D reviewers: en las tasks de 3D, Shift+Click en el botón de descarga de Publish abre la lista de versiones para elegir cuáles bajar; antes servía para elegir otra carpeta. (Studio only)
- **Improved:** Admins, producers and 3d reviewers: el botón de descarga junto a MOV Review baja la última versión de Flow con un click; para elegir entre todas las versiones, Shift+Click. (Studio only)
- **Improved:** Admins and producers: el botón de descarga junto a MOV Review baja la última versión de Flow con un click; para elegir entre todas las versiones, Shift+Click. (Client only)
- **Improved:** Assignee editors: en el editor de Assignees podés dejar una task solo con Watchers, sin ningún Assignee, por ejemplo para que la sigan mientras se decide a quién dársela. (Studio only)
- **Improved:** Assignee editors: en el editor de Assignees podés dejar una task solo con Watchers, sin ningún Assignee, por ejemplo para que la sigan mientras se decide a quién dársela. (Client only)
- **Improved:** Reviewers: si sos Watcher de una task, el shot te aparece en REVIEW y no en SHOTS, salvo que tengas otra task asignada en ese shot. (Studio only)
- **Improved:** Reviewers: si sos Watcher de una task, el shot te aparece en REVIEW y no en SHOTS, salvo que tengas otra task asignada en ese shot. (Client only)
- **Fixed:** Admins and producers: el aviso de cambios en las playlists aparece encima sin traer PipeSync al frente, así que no te interrumpe lo que estás haciendo en otra app. (Studio, macOS only)
- **Fixed:** Admins and producers: el aviso de cambios en las playlists aparece encima sin traer PipeSync al frente, así que no te interrumpe lo que estás haciendo en otra app. (Client, macOS only)
- **Fixed:** Assignee editors: al asignar a alguien desde un shot, el acceso al material en Wasabi se le da aunque cierres el editor enseguida; antes podía quedar asignado sin poder bajar nada. (Studio only)
- **Fixed:** Production managers: Rename shot ya no se traba cuando el material del shot ya se había subido con el nombre nuevo: si la carpeta con el nombre viejo está vacía, el shot pasa a usar la que ya tiene el nombre correcto, sin mover nada. (Studio only)

## v1.028

- **New:** 3D reviewers: en las tasks de 3D podés bajar lo último sin pasar por FileManager: el botón junto a Publish baja la última versión publicada a la carpeta de la task (Shift+Click para elegir otra carpeta), y en el tab REVIEW el botón de descarga junto a MOV Review baja versiones de Flow. (Studio only)
- **New:** Producers, coordinators and admins: podés asignarle tasks a alguien que todavía está desactivado en Flow, por ejemplo quien arranca en unos días: en PROJECTS > Users & Access, en su ficha, tildá Also while disabled in Flow y aparece en la lista de assignees sin ocupar un asiento. Los demás desactivados siguen sin aparecer. (Studio only)
- **New:** Admins and producers: cuando cambia una playlist (una playlist nueva, una versión subida, un comentario del cliente, una aprobación) aparece un aviso abajo a la derecha que queda fijo hasta que lo cerrás; los cambios siguientes se suman al mismo aviso, y un click en una playlist la abre. (Studio only)
- **New:** Admins and producers: cuando cambia una playlist (una playlist nueva, una versión subida, un comentario del cliente, una aprobación) aparece un aviso abajo a la derecha que queda fijo hasta que lo cerrás; los cambios siguientes se suman al mismo aviso, y un click en una playlist la abre. (Client only)
- **Improved:** los errores aparecen en una sola ventana con Show Details y Copy, que no traba el resto de la app y se cierra cuando quieras; si el sync falla en varias partes a la vez, todo queda en esa misma ventana.
- **Improved:** Producers, coordinators and admins: si Flow bloqueó la cuenta de alguien, guardar a esa persona activa en PROJECTS > Users & Access la desbloquea. (Studio only)
- **Fixed:** si Flow rechaza tu login (por ejemplo, porque tu cuenta todavía está deshabilitada), PipeSync deja de intentar solo y te explica qué pasa y a quién pedírselo; antes, abrir la app varias veces podía dejarte la cuenta de Flow bloqueada.
- **Fixed:** Producers, coordinators and admins: al crear una task de 3D (Match Move, Model, Lighting…) desde el tab PROD, o con Create folders in Wasabi, la carpeta en Wasabi vuelve a llamarse 3D con D mayúscula; antes se creaba 3d. Si el shot ya tiene una carpeta 3d, se sigue usando esa. (Studio only)

## v1.027

- **New:** Reviewers: en Mis horas, la sección de supervisión suma la opción R&D para cargar el tiempo de investigación y desarrollo aparte de la supervisión. (Studio only)
- **Improved:** Project managers: en Import BID podés sumar todas las columnas de descripción que necesites con «Agregar descripción»; antes eran tres como máximo. (Studio only)
- **Improved:** Project managers: en Import BID podés sumar todas las columnas de descripción que necesites con «Agregar descripción»; antes eran tres como máximo. (Client only)
- **Improved:** Assignee editors: en el editor de Assignees cada persona va como Assignee o como Watcher, nunca las dos: hay una columna para cada uno y marcar una casilla desmarca la otra. (Studio only)
- **Improved:** Producers and coordinators: en PROJECTS > Users & Access ya podés dar de alta una persona con Create user; antes lo podía hacer sólo un Master. La persona se crea desactivada y la activás desde su ficha. (Studio only)
- **Fixed:** Gantt planners: el asistente del Gantt ya puede mostrar el antes y después de un cambio de hasta 20 tasks de una vez, tengan fechas o no; antes fallaba con más de dos tasks sin fecha, y partir el cambio en tandas no servía. (Studio only)
- **Fixed:** Gantt planners: el asistente del Gantt ya puede mostrar el antes y después de un cambio de hasta 20 tasks de una vez, tengan fechas o no; antes fallaba con más de dos tasks sin fecha, y partir el cambio en tandas no servía. (Client only)
- **Fixed:** el recorrido guiado para artistas ya no se traba en el paso de instalar LGA Mighty Tools. (macOS only)
- **Fixed:** en el recorrido guiado para artistas, saltear un capítulo, volver a uno que ya hiciste o apretar de nuevo el botón de NukeX ya no traba el recorrido, y lo que explica cada subida espera a que lo leas en vez de pasar solo. (Studio only)
- **Fixed:** en QUEUE, el ETA ya no aparece cortado mientras se calcula: muestra --:-- hasta tener velocidad, y Stalled si la transferencia se frena.
- **Fixed:** Assignee editors: al guardar los asignados en PROD, la celda Assignees ya no muestra a los Watchers como si fueran asignados. (Studio only)

## v1.026

- **Improved:** al subir un MXF de ERSO a Flow, el chequeo de la especificación de entrega pide ahora DNxHR SQ, el codec nuevo del proyecto, en vez de DNxHD SQ. (Windows only)
- **Improved:** Slate users: Slate MXF puede agregar el slate a los MXF en DNxHR SQ, el codec nuevo de entrega de ERSO. (Studio, Windows only)
- **Fixed:** si en Flow se renombra un shot o se intercambian los nombres de dos shots, la card de cada uno ya no muestra las tasks, las versiones y la descripción del otro, y Shift+click en el nombre lleva al shot correcto; los que ya estaban cruzados se corrigen con Clean Local Cache o solos después de unas sincronizaciones.

## v1.025

- **New:** en HELP > Guided tours está «PipeSync para artistas»: un recorrido de unos 10 minutos sobre un proyecto de práctica que muestra cómo bajar un shot, abrirlo en Nuke, subir el trabajo, mandar el review a Flow y cargar las horas, sin tocar tus proyectos. (Studio only)
- **Fixed:** ya se puede asignar a una task a personas con tilde en el nombre (por ejemplo, Starópoli); antes fallaba con «no se encontraron estos usuarios». (macOS only)
- **Fixed:** el editor de Assignees muestra tildado a quien ya está asignado aunque todavía no figure como assignable, así que guardar ya no lo saca de la task sin querer.

## v1.024

- **New:** en el menú de click derecho del tab PROD, Show task in Explorer (Finder en Mac) abre la carpeta de esa task en tu computadora; si todavía no existe, te ofrece abrir la carpeta más cercana que sí está.
- **Improved:** en Mis horas, si Flow no te deja quitar o corregir un registro, el aviso dice que es por tu permiso y que lo pidas a producción, en vez de pedirte que revises si se guardó.
- **Improved:** el botón Download del Media Manager de Nuke pregunta si saltear o pisar los archivos que ya tenés en disco, en vez de pisarlos.
- **Fixed:** la sincronización con Flow ya no falla cuando alguien cambia Assigned To desde la web de Flow y deja como Watcher a una persona que ya no está asignada; si podés editar asignados, un aviso te explica qué pasó y te ofrece Fix in Flow para corregirlo.
- **Fixed:** Project managers: en Users & Access se vuelve a poder guardar a un freelancer activo con permiso Vendor (por ejemplo, para que aparezca en los assignees), sin que Flow pida un Vendor Group. (Studio only)
- **Fixed:** después de subir un review a Flow, la columna Local de la card ya no se queda en «...»: muestra las versiones sin tener que apretar Refresh.

## v1.023

- **New:** Gantt readers: en el tab GANTT podés guardar la combinación de filtros como un preset con nombre y volver a ella con un click; si después cambiás algún filtro, el control lo marca y te deja actualizar el preset o volver a como estaba. (Studio only)
- **New:** Gantt readers: en el tab GANTT podés guardar la combinación de filtros como un preset con nombre y volver a ella con un click; si después cambiás algún filtro, el control lo marca y te deja actualizar el preset o volver a como estaba. (Client only)
- **Improved:** Shots users: al subir una versión ya no hay que tildar nada para que cuenten las horas que cargaste hoy en esa task: la ventana te avisa cuántas son y se suman solas a la versión. (Studio only)
- **Improved:** el tab ACTIVITY ahora se llama QUEUE: es el mismo de siempre, con las subidas y descargas a Wasabi.
- **Improved:** los botones de arriba a la derecha cambian de orden: PROD va antes que PLAYLIST, STATS a la derecha de GANTT y TOOLS antes que PROJECTS; Ctrl+Alt+flechas los recorre en ese mismo orden.
- **Improved:** el tab PLAYLIST muestra su título arriba a la izquierda, como PROD.
- **Improved:** en GANTT, PROD, SHOTS, REVIEW, PLAYLIST y STATS, un combo de filtro que esconde algo (un solo proyecto, algunas secuencias, un assignee) se pinta de rojo para que se note, y sin filtro dice «All projects», «All sequences» o «All assignees».
- **Fixed:** en el tab GANTT, los filtros vuelven a ir alineados a la derecha de la barra en vez de quedar pegados a Today.

## v1.022

- **New:** everyone now has the INBOX: your own to-do list, and the status changes of the tasks you are assigned to or watching. FOR YOU marks a task of yours that was sent to Corrections. (Studio only)
- **New:** everyone now has the INBOX: your own to-do list, and the status changes of every task in your projects. (Client only)
- **New:** Producers and admins: you can download a task's versions from Flow, or only the latest one, from the Prod tab's right-click menu. (Studio only)
- **New:** you can download a task's versions from Flow, or only the latest one, from the Prod tab's right-click menu. (Client only)
- **New:** Producers: you can download a shot's review versions from Flow from the Review tab, as admins already could. (Studio only)
- **New:** everyone can now download a shot's review versions from Flow, not only admins. (Client only)
- **New:** Gantt planners: the local planning assistant can work with several projects at once: review and capture an artist's schedule across two, three or all active projects, and prepare one proposal that moves tasks from different projects, shown together in your Gantt before you apply it. (Studio only)
- **New:** Gantt planners: the local planning assistant can work with several projects at once: review and capture an artist's schedule across two, three or all active projects, and prepare one proposal that moves tasks from different projects, shown together in your Gantt before you apply it. (Client only)
- **Improved:** the Prod tab's right-click menu uses color to show where each option takes you (Flow, NukeStudio, FileManagerS3) and which options mark or delete things.
- **Improved:** tasks are now assigned to the vendor's group instead of individual people, so anyone in that vendor can change their status in Flow. The assignee editors, Create task and the BID import offer the vendor's group. (Client only)
- **Improved:** Gantt planners: the Gantt shows one row per vendor, and dragging a task to a vendor's row assigns it to that vendor's group. (Client only)
- **Improved:** Project managers: Users & Access no longer saves an active vendor user without a Vendor Group, and the vendor audit lists the ones that have none. (Client only)

## v1.020

- **New:** Admins: you can download a shot's review versions from Flow straight from the Review tab. The window comes with only the latest version selected, Shift+Click downloads the latest version without opening it, and the row updates when the download ends. (Studio only)
- **New:** If Settings shows you NKS auto download but not NKS auto upload, you now also get an Upload Now button next to the NKS Download Now button, so you can send your NKS folders to Wasabi right away.
- **Improved:** In Log time, today now has two tabs: one to add time to your shots and general activities, and "Registrado hoy" to review and correct everything you already logged today in a full list. Clicking a shot's logged time takes you to its entries. (Studio only)
- **Improved:** Admins: Downloading versions from Flow now selects only the latest version, Shift+Click downloads it without opening the window, and the row updates when the download ends. (Client only)
- **Fixed:** The Log time window no longer appears inside a second dark panel; it opens as a single window. (Studio, macOS only)

## v1.019

- **New:** Log time supports repeated meetings and other activities with project selection and optional notes, plus supervision entries for reviewers; time fields accept combinations such as 8h 30m and 1d 4h. (Studio only)
- **New:** Shot assignee editors: Right-click an assignee in a Shot Card to edit the task's assignees and Watchers directly, using the same editor as PROD. (Studio only)
- **New:** Shot assignee editors: Right-click an assignee in a Shot Card to edit the task's assignees and Watchers directly, using the same editor as PROD. (Client only)
- **Improved:** Gantt planners: When some tasks changed in Flow after you moved them, Apply lists each one with what changed and lets you apply the rest, keeping those as temporary changes. (Studio only)
- **Improved:** Gantt planners: When some tasks changed in Flow after you moved them, Apply lists each one with what changed and lets you apply the rest, keeping those as temporary changes. (Client only)
- **Improved:** Log time now lists open shots with their current status for today's entries and lets you edit, move or remove earlier records before saving all changes together. (Studio only)
- **Improved:** Producers: The team hours summary compares this week and last week with explicit dates, logged and missing time, and daily details; totals over eight hours use workdays. (Studio only)
- **Improved:** Assignee editors: Viewer is now called Watcher. Removing an assignee also clears Watcher; assigning the person again keeps Watcher off until you explicitly select it. (Studio only)
- **Improved:** Assignee editors: Viewer is now called Watcher. Removing an assignee also clears Watcher; assigning the person again keeps Watcher off until you explicitly select it. (Client only)
- **Fixed:** Automatic updates install the new version again; before, PipeSync closed and reopened the version you already had. (macOS only)
- **Fixed:** Gantt planners: Apply no longer stops with an expected-values conflict when the batch moves tasks that are linked by dependencies in Flow. (Studio only)
- **Fixed:** Gantt planners: Apply no longer stops with an expected-values conflict when the batch moves tasks that are linked by dependencies in Flow. (Client only)
- **Fixed:** Gantt planners: After applying a planning proposal, the Gantt stays on the same dates instead of jumping elsewhere in the timeline. (Studio only)
- **Fixed:** Gantt planners: After applying a planning proposal, the Gantt stays on the same dates instead of jumping elsewhere in the timeline. (Client only)

## v1.018

- **New:** Assignee editors: Mark an assigned person as a Viewer to keep their access while identifying who is responsible for the task. (Studio only)
- **New:** Assignee editors: Mark an assigned person as a Viewer to keep their access while identifying who is responsible for the task. (Client only)
- **New:** Task information labels responsible people and Viewers separately, keeping access distinct from responsibility.
- **New:** Gantt planners: Compare each shot's recorded time with a selected quote and Flow's current estimate, keeping missing estimates and incomplete time records visible. (Studio only)
- **New:** Gantt planners: Compare each shot's recorded time with a selected quote and Flow's current estimate, keeping missing estimates and incomplete time records visible. (Client only)
- **New:** Cost analysts: Analyze declared internal rates, documented incurred costs and an internal budget with explicit sources, separately from client prices and assumptions. (Studio only)
- **New:** Cost analysts: Analyze declared internal rates, documented incurred costs and an internal budget with explicit sources, separately from client prices and assumptions. (Client only)
- **New:** Gantt planners: You can review overdue work and global artist queues, build a tentative Gantt with explicit capacity and effort assumptions, and share a planning context with a local assistant or through chat attachments. Gantt Exchange shows received changes and their exact approval before you apply them. (Studio only)
- **New:** Gantt planners: You can review overdue work and global artist queues, build a tentative Gantt with explicit capacity and effort assumptions, and share a planning context with a local assistant or through chat attachments. Gantt Exchange shows received changes and their exact approval before you apply them. (Client only)
- **New:** Gantt planners: Planning proposals appear as temporary drafts in your open Gantt, framed around the affected task and artist. You can refine them while keeping other manual changes. Only Apply All Changes in PipeSync confirms the current draft batch and sends it to Flow. (Studio only)
- **New:** Gantt planners: Planning proposals appear as temporary drafts in your open Gantt, framed around the affected task and artist. You can refine them while keeping other manual changes. Only Apply All Changes in PipeSync confirms the current draft batch and sends it to Flow. (Client only)
- **New:** Gantt planners: Save a planning proposal from the terminal and compare before/after images of the real Gantt. Drafts appear in violet, with shared assignees and optional dates preserved, before you apply them. (Studio only)
- **New:** Gantt planners: Save a planning proposal from the terminal and compare before/after images of the real Gantt. Drafts appear in violet, with shared assignees and optional dates preserved, before you apply them. (Client only)
- **New:** Gantt planners: You can capture the real Gantt from a terminal, framed by person, task or date, without opening a window. The image uses a copy of your planning database and Argentine holiday calendar. (Studio only)
- **New:** Gantt planners: You can capture the real Gantt from a terminal, framed by person, task or date, without opening a window. The image uses a copy of your planning database and Argentine holiday calendar. (Client only)
- **New:** Gantt planners: You can query the Gantt from a terminal without opening PipeSync: project and person status, task details, records to review and changes since a daily snapshot. Results are JSON with the evidence and missing data; the commands read copies of your local databases. (Studio only)
- **New:** Gantt planners: You can query the Gantt from a terminal without opening PipeSync: project and person status, task details, records to review and changes since a daily snapshot. Results are JSON with the evidence and missing data; the commands read copies of your local databases. (Client only)
- **New:** Reviewers: In the INBOX, right-click a status change to jump to that shot: Show shot in NukeStudio takes the open NukeStudio to it, and Show shot in FileManagerS3 opens the shot's folder in a FileManagerS3 tab. (Studio only)
- **New:** Reviewers: In the INBOX, right-click a status change to jump to that shot: Show shot in NukeStudio takes the open NukeStudio to it, and Show shot in FileManagerS3 opens the shot's folder in a FileManagerS3 tab. (Client only)
- **New:** Audit navigators: In the vendor audit, select a row and press Show in Prod tab to jump to that shot, already searched and selected. (Client only)
- **New:** Project managers: For a shot PipeSync has not synced because it has no tasks, the vendor audit's Show button turns green and opens it in Flow. (Client only)
- **New:** Admins: In the vendor audit, right-click > Delete shot lets you delete a shot that has no tasks. (Client only)
- **New:** Production managers: you can rename a shot from the PROD tab with right-click > Rename shot or F2: PipeSync renames it in Flow and moves its files in Wasabi and its folder on your computer to the new name. File names keep the old name, and other computers keep their old folder. (Studio only)
- **New:** Wasabi cleanup users: Wasabi Cleanup has a Next sequence button that scans the following sequence of the bucket without closing the window, and Rescan no longer resizes the window. (Studio only)
- **New:** Shots users: Log time: you can now log hours on your open tasks for any day of this week or last week without uploading a version, and log meetings separately, either for one project or as a General meeting. Open it by clicking the hours bar at the top of the Shots tab. (Studio only)
- **New:** Reviewers: Log time has a Supervision section to log the time you spend reviewing and supervising other people's work, for one project or as General. Its Completar button fills in the hours still missing to complete the day, without saving anything. (Studio only)
- **New:** If your time tracking is Required, PipeSync now reminds you half an hour before the end of the day if today's hours are not logged, and asks again the next morning if a day was left incomplete. Active people on the assignee list start at 8 hours a day with a 6 pm reminder. (Studio only)
- **New:** Team time users: Work Time in the Stats tab now lists the active team with logged versus expected hours per period, colored by status: green when complete, amber when hours are missing, red when nothing was logged or a period closed short. A summary on top filters the list, and each person's detail shows every day's status and the versions uploaded. Meetings and supervision hours are totaled for the team at the bottom. Eligible producers also get a short summary of who is behind each time you open PipeSync, with a checkbox to hide it until the next day. (Studio only)
- **New:** Team time users: In the Stats tab you can change who must log hours, their reminder time and time off without leaving Stats: use Edit in a person's Work Time detail. (Studio only)
- **New:** Project managers: Edit user has a Time tracking section to change who must log hours, their hours per day and reminder time, and to add time off, all in the same window. (Studio only)
- **New:** Keyshots now show a red diamond next to the shot name in the Shots, Review and PROD tabs. Hover it to see what it means.
- **New:** Production editors: In the PROD tab you can mark or unmark a shot as important from the right-click menu, the same flag as the Shot Priority button in HieroTools. Important shots now show their name in red in the PROD tab too, and with several rows selected the change applies to all their shots. (Studio only)
- **New:** Production editors: In the PROD tab you can mark or unmark a shot as important from the right-click menu. Important shots now show their name in red in the PROD tab too, and with several rows selected the change applies to all their shots. (Client only)
- **Improved:** After updating, release notes follow your current profile in Help and future update notices, so you see changes relevant to the features you can use.
- **Improved:** Gantt readers: Gantt Task Info keeps a fixed height while showing the shot image, colored task status, estimate and logged time together with each person's contribution; full notes and additional contributors open in a separate detail window. (Studio only)
- **Improved:** Gantt readers: Gantt Task Info keeps a fixed height while showing the shot image, colored task status, estimate and logged time together with each person's contribution; full notes and additional contributors open in a separate detail window. (Client only)
- **Improved:** Gantt readers: Viewers are excluded from current workload and Gantt assignment conflicts. (Studio only)
- **Improved:** Gantt readers: Viewers are excluded from current workload and Gantt assignment conflicts. (Client only)
- **Improved:** Gantt planners: Pending planning drafts detect responsibility changes before applying. (Studio only)
- **Improved:** Gantt planners: Pending planning drafts detect responsibility changes before applying. (Client only)
- **Improved:** Gantt readers: The Gantt shows the calendar interval as a faint band and recorded work on its actual dates, using eight-hour workdays. (Studio only)
- **Improved:** Gantt readers: The Gantt shows the calendar interval as a faint band and recorded work on its actual dates, using eight-hour workdays. (Client only)
- **Improved:** Gantt readers: The Gantt refreshes after Flow sync without interrupting your current view. (Studio only)
- **Improved:** Gantt readers: The Gantt refreshes after Flow sync without interrupting your current view. (Client only)
- **Improved:** Gantt planners: Your pending changes stay in place after Flow sync, without a prompt to decide what to do with drafts. Refresh DB still lets you keep or discard them manually. (Studio only)
- **Improved:** Gantt planners: Your pending changes stay in place after Flow sync, without a prompt to decide what to do with drafts. Refresh DB still lets you keep or discard them manually. (Client only)
- **Improved:** Gantt planners: Planning previews now show the selected task immediately, including tasks in Unassigned. Short visual transitions keep the full draft ready for review and stop when you edit, apply, reset, scroll or leave the Gantt; reduced motion shows the final state directly. (Studio only)
- **Improved:** Gantt planners: Planning previews now show the selected task immediately, including tasks in Unassigned. Short visual transitions keep the full draft ready for review and stop when you edit, apply, reset, scroll or leave the Gantt; reduced motion shows the final state directly. (Client only)
- **Improved:** Project managers: Re-importing a bid now assigns the existing vendor tasks that had no assignee to that vendor's users, and the preview shows it before you apply. (Client only)
- **Improved:** Project managers: Run audit in the Projects tab now opens a results window instead of a single line: a summary per vendor, every problem with the shots, tasks and people affected, and one-click fixes for shots missing their Vendor Group, vendor tasks without an assignee and vendor users without a Vendor Group. It also reports tasks left with disabled users, the versions and notes a vendor can no longer see, and who each shot without a vendor code belongs to. (Client only)
- **Improved:** Windows and dialogs no longer flash white for a moment when they open. (Windows only)
- **Improved:** The installer is much smaller (about 110 MB instead of 300 MB), so updates download faster, and PipeSync takes about 900 MB less disk space. (Windows only)
- **Improved:** Slate users: the Slate MXF tool in the Tools tab is now available to producers who also have access to Tools. (Studio, Windows only)
- **Improved:** Tools users: The Tools tab now adapts to the window width: in a narrower window the update cards and the Disk Cleanup actions rearrange instead of being cut off. (Studio only)
- **Improved:** Tools users: The Tools tab now adapts to the window width: in a narrower window the update cards and the Disk Cleanup actions rearrange instead of being cut off. (Client only)
- **Improved:** Project managers: The Projects tab now grows with the window, up to the same width as the Tools tab. You can drag any column border in its tables to resize it, and vendor codes and each user's projects rearrange to fit the width. (Studio only)
- **Improved:** Project managers: The Projects tab now grows with the window, up to the same width as the Tools tab. You can drag any column border in its tables to resize it, and vendor codes and each user's projects rearrange to fit the width. (Client only)
- **Improved:** Shots users: The hours bar in the Shots tab now shows today, your last working day and the week against your reference, and it no longer turns red first thing in the morning. (Studio only)
- **Improved:** Shots users: Uploading a version no longer forces you to enter time when you already logged the day; you can count those hours as the version's time instead. (Studio only)
- **Improved:** Project managers: Edit user is now a wide window organized in columns that fits on screen, and the assignee color is picked by clicking a single color dot. (Studio only)
- **Improved:** Tools users: The LGA Updates card in the Tools tab now offers LGA Mighty Tools in place of LGA OpenInNukeX, so you can install it from there and see when a new version is out. (Studio, macOS only)
- **Improved:** Tools users: The LGA Updates card in the Tools tab now offers LGA Mighty Tools in place of LGA OpenInNukeX, so you can install it from there and see when a new version is out. (Client, macOS only)
- **Improved:** PipeSync now checks for updates every few hours while it stays open, not only at startup. Remind me later waits one day instead of a week, and closing the update window won't ask again until you restart PipeSync.
- **Fixed:** Team time users: Availability in the Stats tab no longer shows negative available days when the deadline is in the past. (Studio only)
- **Fixed:** Project managers: Three tooltips in Edit user no longer show garbled characters. (Studio only)
- **Fixed:** Project managers: In Users & Access, a change saved right after another one is no longer lost silently: Edit user waits until the table is back in sync with Flow, and a save that Flow rejects now shows an error with its details. (Studio only)
- **Fixed:** Project managers: In Users & Access, a change saved right after another one is no longer lost silently: Edit user waits until the table is back in sync with Flow, and a save that Flow rejects now shows an error with its details. (Client only)
- **Fixed:** Stats no longer shows a task's logged hours as only its latest entry after a sync.
- **Fixed:** A task whose only time entry was deleted from another computer or from the Flow website no longer keeps showing that time after a sync.
- **Fixed:** Shots users: Uploading a version no longer counts its time as logged when Flow failed to register it; PipeSync now tells you so you can log it again. (Studio only)
- **Fixed:** Shots users: Uploading a version no longer counts its time as logged when Flow failed to register it; PipeSync now tells you so you can log it again. (Client only)
- **Fixed:** Assignee editors: Reassigning tasks to someone else no longer shows an "Assignees saved with warnings" message for every task. (Studio only)
- **Fixed:** Assignee editors: Reassigning tasks to someone else no longer shows an "Assignees saved with warnings" message for every task. (Client only)

## v1.016

- **Fixed:** When giving an artist Wasabi access failed halfway, the next task assignment or Wasabi policy sync now finishes it instead of leaving them without access to the shot. (Studio only)

## v1.015

- **New:** The update window now shows what's new before you install, and after an update you didn't see the app shows it once when it starts.
- **New:** In the Tools tab, each tool with an update in LGA Updates has a What's new button next to Update with its changes, Update All ends with a summary of what changed, and the startup notice about available updates says what's new in each tool.
- **New:** The Help tab has a What's new button with the release notes of every PipeSync version.
- **New:** The LGA Updates card in the Tools tab now lists LGA FrameRev, the screen capture and annotation app, so you can install it and see when a new version is out.
- **New:** Coordinators and reviewers: the Tools tab has a new Slate MXF tool that lists the tasks in Rev Dir, adds a slate frame in front of each delivery MXF and writes what you complete or correct back to Flow. (Studio, Windows only)
- **New:** Coordinators and admins: Shift+Click on the sync cloud opens a window to bring in projects that are not In Progress, such as Delivered ones, until you close the app. (Studio only)
- **New:** Admins: Shift+Click on the sync cloud opens a window to bring in projects that are not In Progress, such as Delivered ones, until you close the app. (Client only)
- **New:** Right-click a row in the PROD tab to open View notes and feedback for the task's versions, Show shot in NukeStudio to jump to it in the open NukeStudio, or Show shot in FileManagerS3 to open the shot's folder in a FileManagerS3 tab.
- **New:** Review Netflix and SL Approved task statuses are available after Review Dir in the status picker, the PROD table and the Gantt legend. (Client only)
- **Improved:** The LGA Updates card in the Tools tab shows each tool's summary from the LGA website in larger, easier to read text, with the full text in its info card.
- **Improved:** Coordinators and admins: Wasabi Cleanup reviews several shots at once, lets you pick any Wasabi bucket instead of a project, recognizes versions named with a space before the V and no longer keeps deleted versions on screen. (Studio only)
- **Improved:** Producers: you can now add comments to a version from its notes, as reviewers already could. (Studio only)
- **Improved:** Admins: you can now add comments to a version from its notes, as reviewers already could. (Client only)
- **Improved:** Admins: in Users & Access, choosing a Vendor Group also makes the person a member of that group in Flow, and changing it removes the old one. (Client only)
- **Improved:** The PROD tab's Task Name filter is now a dropdown like Assignees, Projects and Sequences, the PROD table's cursor no longer turns into a hand over editable cells, and the PLAYLIST tab opens with the most recently created playlist on top.
- **Fixed:** Tasks assigned to a whole Vendor Group now show that vendor's color in the PROD tab's Assignees column. (Client only)
- **Fixed:** The LGA Updates card in the Tools tab shows the version of LGA Shot Player that is actually installed, instead of an old one.
