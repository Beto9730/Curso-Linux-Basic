### Creacion de usuarios a traves de comandos 

Para crear usuarios en Linux se puede hacer de varios formas, con algún entrono gráfico, o a través de la linea de comandos. Con Ubuntu trae por defecto uno. Pero cuando se esta administrando un servidor lo normal es no tener la ayuda de ninguna de estos programas, para ello tendremos que tirar de comandos en la terminal.

- Creo el usuario
```
root@tserver:~# adduser eduardo
Añadiendo el usuario `eduardo' ...
Añadiendo el nuevo grupo `eduardo' (1001) ...
Añadiendo el nuevo usuario `eduardo' (1001) con grupo `juan' ...
Creando el directorio personal `/home/eduardo' ...
Copiando los ficheros desde `/etc/skel' ...
Introduzca la nueva contraseña de UNIX: # Escribir la contraseña
Vuelva a escribir la nueva contraseña de UNIX: # Confirmar
passwd: contraseña actualizada correctamente
Cambiando la información de usuario para juan
Introduzca el nuevo valor, o pulse INTRO para usar el valor predeterminado
      Nombre completo []: Juan # Completar datos (opcional)
      Número de habitación []: # [enter] para no completar datos
      Teléfono del trabajo []:
      Teléfono de casa []:
      Otro []:
¿Es correcta la información? [S/n] S # Confirmar información
```