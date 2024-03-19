# DescentRTL
Traducción de campañas Embers of Dread y Trials of Frostgraven

![IMG_20230701_102630](https://github.com/kelmys/DescentRTL/assets/3743722/4fcb5c76-41ee-485a-9044-68985237ee4d)


Tenemos 2 archivos binarios según la version de la aplicación que se utilice:

_data_windows para Windows
_data_android para Android 

a) Instrucciones de instalación para la versión de Windows

Acceder al siguiente directorio:

![IMG_20230629_224754_178](https://github.com/kelmys/DescentRTL/assets/3743722/336cf994-48d3-4a91-b65c-ab1d34a21685)

En lugar de la carpeta "kelmy", tiene que ser el de vuestro usuario de windows con el que os habéis logado, en esa carpeta, vereis esos archivos.

Pegais el archivo descargado del repositorio "_data_windows"

Renombrais el _data a _data_bck (para tener copia de seguridad).

Y renombrais el _data_windows a _data

Recientemente se ha detectado que la cache se borra, para poder evitar eso, acceder al directorio 

C:\Users\\<vuestro usuario>\AppData\LocalLow\Unity\WebPlayer\Cache

Y en las propiedades de la carpeta "com_fantasyflightgames_Road To Legend" ponerla en modo lectura, así evitaremos que al iniciar Steam borre la carpeta de cache y por consiguiente el fichero que anteriormente hemos copiado.

Con eso ya está instalado.

b) Instrucciones de instalación para la versión* de Android:

Acceder al siguiente directorio:

![IMG_20230630_222355_115](https://github.com/kelmys/DescentRTL/assets/3743722/6d156c02-5890-46fb-be4f-29e720857e43)

Pegais el archivo descargado del repositorio "_data_android"

Renombrais el _data a _data_bck (para tener copia de seguridad).

Y renombrais el _data_android a _data

Con eso ya está instalado.

*Según la versión de Android que se disponga hay que hacer un paso previo, porque antes de Android 10 se podia acceder directamente al directorio en el que se debe instalar el archivo.

Pero a partir de Android 10, el acceso al directorio /Android/data no es directo, aunque se puede hacer sin hacer root ni modificación, simplemente instalar cualquier app de exploración de archivos. 

Buscar en youtube "android acceso directorio data" y encontraréis muchos tutoriales.

Agradecimientos a Vidimus y Familialara, por la ayuda en la revisión de la traducción.
