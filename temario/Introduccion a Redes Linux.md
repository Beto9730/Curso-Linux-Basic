### Introduccion a Redes Linux

- LINUX es un sistema operativo, compatible Unix. Dos características muy peculiares lo diferencian del resto de los sistemas que podemos encontrar en el mercado, la primera, es que es libre, esto significa que no tenemos que pagar ningún tipo de licencia a ninguna casa desarrolladora de software por el uso del mismo, la segunda, es que el sistema viene acompañado del código fuente. El sistema lo forman el núcleo del sistema (kernel) mas un gran numero de programas librerías que hacen posible su utilización.

- Las variantes de estos sistemas se denominan distribuciones y su objetivo es ofrecer una edición que cumpla con las necesidades de determinado grupo de usuarios. Algunas son gratuitas y otras de pago, algunas insertan software no libre y otras contienen solo software libre. Existen numerosos grupos de usuarios de Linux en casi todos los países del mundo.

- Servicios de Red

Cliente-Servidor: un cliente pide un servicio a un servidor 
ftp: acepta conexiones ftp 
dns: peticiones de consultas de nombres de dominio
login: conexiones al servidor o un equipo

- Herramientas de Red mas utilizadas

ping ._ nos permite verificar la conexion de un servidor con otros equipo en la red mediante el uso de paquetes
```
ping google.com.pe
```
traceroute ._ nos sirve que rutas siguen los paquetes que se envian a otro equipo conectado a la red y con una direccion ip valdia
```
traceroute google.com.pe
```
telnet ._ para la conexiones en servidores unix , solaris. Permite establecer conexion con otro servidor que tenga el servidor unix. Verificar la conexion de los puertos

ssh ._ nos permite conectarnos entre equipos dentro de Linux 
```
ssh alberto@10.0.0.12
```
netstat ._ verificar el estado de nuestra red o si estamos conectado a una red 
```
netstat -rn
```
ifconfig._ permite conocer bastantes aspectos de la configuracion de la red por ejemplo: ip del equipo, puertas de enlace ,dns, etc. esta siendo sustitudio por ip a es mas moderna y completa
```
ifconfig
```
- Ficheros de configuracion de red

hostname._ nos sirve para cambiar o mostrar el nombre de nuestro servidor 
```
cat /etc/hostname
```