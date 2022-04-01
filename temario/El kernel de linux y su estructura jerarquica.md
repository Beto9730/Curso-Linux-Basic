### El kernel de linux y su estructura jerarquica

- El kernel se encuentra en el centro del sistema operativo y controla todas las funciones importantes del hardware, 
ya sea un sistema Linux macOS o Windows, un smartphone, un servidor, una virtualización como KVM o cualquier otro tipo de ordenador.
```
/bin (binarios): Es un directorio estático donde se almacenan todos los binarios ejecutables de usuario. Cualquier usuario puede ejecutarlos.
cat: Concatenar varios archivos para posteriormente desplegarlos en pantalla.
cp: Para copiar ficheros ficheros.
echo: Repite o despliega la salida estándar cualquier argumento que se le indique para posteriormente saltar una línea.
ls: Para listar directorio.
grep: filtrar las lineas que tienen un patron o una expresion regular 
/boot (arranque): Es un directorio estático que contiene todos los ejecutables y archivos necesarios para el arranque del sistema. Por ejemplo, la imagen del kernel Linux en /boot/vmlinuz. También, podemos encontrar en /boot el gestor de arranque GRUB.En algunas distribuciones, este directorio se almacena en su propia partición separada del resto.
/dev (dispositivos): Contiene a los dispositivos conectados al sistema como usb, disco duro, cdrom, etc. La ruta en la que se encuentra cualquier volumen (partición o dispositivo externo) conectado al sistema empieza por /dev.
/etc (etcétera): Aquí se guardan los ficheros de configuración de los programas instalados así como ciertos scripts que se ejecutan en el inicio del sistema.
/home (hogar): Es el directorio donde se encuentran los directorios personales de cada usuario con su nombre de usuario respectivo. Cada uno de estos contiene los directorios: /Documentos, /Imágenes, /Música, /Plantillas y /Videos
/lib (bibliotecas): Contiene las bibliotecas del sistema
```
- ¿Cuales son las 4 libertades esenciales del software Libre?

Poder usar el programa con cualquier propósito.
Poder estudiar cómo funciona el programa y poder modificarlo.
Poder copias del programa.
Poder mejorar el programa y poder compartir dichas mejoras para beneficio de todos.

- ¿Cuáles son las principales diferencias entre el movimiento del software libre y el movimiento Open Sources (código abierto)?
Las diferencias entre el software libre y el software de código abierto es que el software libre va dirigido o enfocado 
a las libertades filosóficas que tienen los usuarios a la hora de hacer uso de ello y el software de código abierto va dirigido a las ventajas a la hora de utilizarlo