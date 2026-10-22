# Política de privacidad de sCollectPlay y sCollectPlay Lite

Actualizado: 2026-10-22

## En resumen

sCollectPlay y sCollectPlay Lite **no** recopilan, almacenan ni transmiten datos
personales. Las apps trabajan exclusivamente en tu Mac o tu PC con Windows. No hay cuentas, ni conexión a la
nube, ni servicios de analítica, ni publicidad.

## Qué datos procesa la app

La app lee los archivos de medios en las carpetas que le has entregado expresamente,
eligiéndolas en el diálogo de apertura: una carpeta para escanear, un XML de iTunes o de
Apple Music, o una biblioteca de sCollect. Se leen el nombre del archivo, su tamaño, su
fecha y sus metadatos, y en un XML o una biblioteca, además, los datos de su catálogo.

Sin tu selección, la app no accede a ningún archivo. macOS lo impone mediante la
sandbox de apps.

## Qué deja la app en tu Mac

- **Los ajustes y las posiciones de las ventanas** en la carpeta protegida de la app.
- **El permiso de macOS para volver a abrir tus carpetas en el siguiente inicio.** Se
  guardan rutas de carpetas, no contenidos de archivos. Solo así la app no tiene que
  preguntar de nuevo en cada inicio.
- **En sCollectPlay, además:** la lista de las carpetas, los archivos XML y las
  bibliotecas usados últimamente, tus propias listas de reproducción, el orden y el estado
  del explorador de columnas — también en la carpeta protegida de la app.

Todo ello desaparece cuando borras la app.

## Dos permisos que pueden plantear dudas

**Acceso a la red.** La app lo solicita porque, sin ese permiso, macOS muestra vacía la
ventana de ayuda integrada: la ayuda la presenta un componente del sistema que lo
necesita, aunque solo cargue archivos del propio programa. La app **no llama por sí
misma a ninguna dirección de internet**, no descarga nada y no informa de nada.

Las carpetas en volúmenes de red (SMB, NFS) las alcanza la app a través del sistema
de archivos de tu Mac, no mediante una conexión propia.

**Control de Apple Music.** Cuando envías una selección a Apple Music como lista de
reproducción, la app abre Apple Music con una lista de reproducción generada y, si lo
deseas, sustituye otra del mismo nombre que ya exista allí. macOS pide tu consentimiento
para ello, y se te solicita la primera vez. La app no controla ningún otro programa.

## Tus archivos

La app no escribe etiquetas ni cambia los metadatos de tus archivos.

Solo cuando borras un archivo expresamente, la app lo lleva a la papelera de macOS y lo
quita de la lista; si procede de una biblioteca de sCollect, su catálogo se ajusta en
consecuencia. En unidades sin papelera, la app pregunta antes si el archivo debe
borrarse definitivamente.

## En Windows

Los apartados anteriores describen el Mac. En Windows, sCollectPlay y sCollectPlay Lite guardan lo siguiente
exclusivamente de forma local, en la carpeta de datos de la app (`%LOCALAPPDATA%\Packages\<paquete>\LocalState` y `Settings`):

- **Los ajustes y la posición de la ventana.**
- **La última fuente elegida** — carpetas escaneadas, un archivo XML de iTunes o una biblioteca de sCollect — y el
  resultado del último escaneo.
- **La correspondencia entre las carpetas Mac de una biblioteca y carpetas de tu PC** (solo rutas de carpetas).
- **En sCollectPlay, además:** tus propias listas de reproducción, la lista de las carpetas, los archivos XML y
  las bibliotecas usados recientemente, la ordenación y el estado del navegador de columnas.
- **Un registro de errores** (`fehler.log`), que se queda en tu PC.

Todo ello se elimina cuando desinstalas la app.

La app solo lee archivos de medios y archivos XML allí donde tú los seleccionas; una biblioteca de sCollect solo se lee.
No establece conexiones de red propias, no usa servicios de analítica y no muestra publicidad. Los archivos que Windows
no reproduce por sí mismo se pasan al programa predeterminado para ese tipo de archivo, que eliges en Windows.

Si en sCollectPlay exportas una lista de reproducción para VLC o un dispositivo, la app copia sus archivos en la
carpeta que elijas. En Windows no elimina archivos de medios.

## Microsoft Store

En Windows, la compra (sCollectPlay), la descarga y las actualizaciones se gestionan a través de Microsoft Store; para
ello se aplica la declaración de privacidad de Microsoft. sCollectPlay Lite es gratuita y menciona la versión completa.

## Sin cesión de datos, sin analítica

No hay publicidad, ni servicios de analítica, ni informes de fallos a terceros, ni
cuentas.

## Contacto

Andreas Heiligtag · SwiftAppsBavaria@gmx.net
