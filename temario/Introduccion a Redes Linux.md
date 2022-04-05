### Introduccion a Redes Linux

- LINUX es un sistema operativo, compatible Unix. Dos características muy peculiares lo diferencian del resto de los sistemas que podemos encontrar en el mercado, la primera, es que es libre, esto significa que no tenemos que pagar ningún tipo de licencia a ninguna casa desarrolladora de software por el uso del mismo, la segunda, es que el sistema viene acompañado del código fuente. El sistema lo forman el núcleo del sistema (kernel) mas un gran numero de programas librerías que hacen posible su utilización.

- Las variantes de estos sistemas se denominan distribuciones y su objetivo es ofrecer una edición que cumpla con las necesidades de determinado grupo de usuarios. Algunas son gratuitas y otras de pago, algunas insertan software no libre y otras contienen solo software libre. Existen numerosos grupos de usuarios de Linux en casi todos los países del mundo.

- El comando hostname se usa para mostrar o configurar el nombre de host y el nombre de
dominio de una computadora. Es una de las utilidades administrativas de red más básicas y se obtener la dirección IP de las conexiones de red activas.

hostname -I

- En Linux, Ping es una herramienta comúnmente usada para solucionar problemas de accesibilidad de hosts en una red. Nos ayuda a entender la razón por la cual un sitio web podría no estar cargando.

Más allá de esto, es necesario saber la causa raíz del problema. Puede ser cualquier cosa, desde la conectividad a Internet, la pérdida de la red o el sitio web que ya no está disponible. Ping es el comando que nos ayuda a determinar la accesibilidad de un dispositivo de red.

Siendo rápidos y directos, muchos usuarios están optando por usar el comando ping para solucionar problemas. Y, con este tutorial, ¡esperamos que ahora también puedes usarlo tú!

   
VPS
Dic 07, 2020

Deyimar A.

4min de lectura

Cómo usar el comando Ping de Linux
El comando PING, o Packet Internet Groper, de Linux es una herramienta muy querida por los desarrolladores. Su objetivo principal es administrar el estado de conectividad de red entre una fuente y un dispositivo, con la ayuda de una red IP. En este tutorial sobre Ping de Linux, aprenderás cómo puede ayudar a tu proyecto y cómo comenzar a usarlo.

Y si tienes en mente conseguir un servidor para Linux simple y rápido, estás en el lugar indicado. Aprovecha los descuentos de hasta un 70% en Hostinger.

Conseguir descuento

Tabla de Contenidos	
¿Qué es el comando Ping de Linux?
Cómo instalar el comando Ping en Linux
¿Cómo usar el comando Ping de Linux?
1. Comprobando la conectividad
2. Especificando el número ECHO_REQUEST
3. Con ping audible
4. Estableciendo intervalos
5. Recibiendo solo el resumen del comando Ping de Linux
6. Inundando la red con el comando Ping
Resumen
¿Qué es el comando Ping de Linux?
Con el comando ping, también puedes saber el tiempo que toma enviar y recibir respuestas de una red. Funciona enviando una serie de mensajes del Protocolo de mensajes de control de Internet (ICMP, por sus siglas en inglés) al host de destino y esperando un mensaje ICMP en forma de eco desde y hacia el host y el Dispositivo. Esto te brindará información sobre el tiempo de ejecución de la red.

Básicamente, al usar el comando estarás enviando el mensaje ECHO_REQUEST y esperando ECHO_RESPONSE. Si el mensaje de respuesta muestra «ping rápido de baja latencia» (en inglés sería “fast ping low latency”), significa que la conexión es rápida. Se mide en milisegundos.

Hoy en día, todas las computadoras modernas, VPS o dispositivos tienen PING preinstalado, debido a sus múltiples usos. Se trata de una forma rápida y directa de verificar el rendimiento entre el dispositivo y el host.

Ya sea una red de área local (LAN) o una red de área amplia (WAN), el comando ping proporciona detalles precisos sobre conectividad. También te permite obtener resúmenes estadísticos de la prueba, que incluyen las rondas mínima y máxima, el número de paquetes transmitidos y recibidos, el porcentaje de paquetes perdidos y la desviación estándar de la media. También permite al usuario verificar la calidad de la conexión de red entre dos dispositivos. Hasta ahora suena bastante bien, ¿verdad?

La prueba de Ping entre tu computadora y el host de destino te permitirá determinar:

Estado del host de destino: si es accesible.
Medición del tiempo que le toma a un mensaje ir y venir (Host-Computadora-Host)
Porcentaje de paquetes perdidos.
Cómo instalar el comando Ping en Linux
Recuerda, primero tendrás que acceder a tu VPS usando SSH. ¡Puedes consultar nuestro tutorial PuTTY si tienes problemas con esto!

La mayoría de las versiones de Linux tienen la herramienta ping instalada de manera predeterminada. Puedes verificar si lo está, ejecutando el siguiente comando:

ping -V
Si en Linux ping no está instalado, una actualización rápida del sistema debería resolver el problema:

apt-get update && apt-get install -y iputils-ping
¿Cómo usar el comando Ping de Linux?
Hay varias opciones en Linux que permiten al usuario probar la conectividad entre dos redes:

- Comprobando la conectividad
Puedes ejecutar un comando simple y rápido en tu sistema para verificar el estado del host y el del servidor o computadora de destino.

Como ejemplo, podemos verificar la conectividad de la red con www.google.com: