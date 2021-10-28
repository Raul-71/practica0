Mi primer documento para github

clear

Limpia la ventana del terminal

Con el comando clear se borran todos los comandos de la sesión.



El usuario recibe un terminal vacío con el prompt a la espera de órdenes. Los comandos introducidos anteriormente se guardan en el scrollback buffer.

También se puede limpiar la ventana de la consola con el atajo de teclado [CTRL] + [L]

exit

Finaliza la sesión en el terminal

Con el programa exit finaliza la sesión actual y se cierra la consola.

También se puede utilizar el atajo de teclado [CTRL] + [D].

help

Muestra la lista de todos los comandos

El comando help se utiliza para mostrar una lista de todas las órdenes del sistema.

Si introduces help en combinación con un comando shell obtienes una breve descripción del comando en cuestión. 

history

Muestra las entradas del historial

En Bash, los últimos 500 comandos introducidos en el terminal se guardan en el historial. Esta función sirve de ayuda al introducir órdenes en la consola y permite ejecutar de nuevo un comando introducido con anterioridad seleccionándolo con ayuda de las flechas del teclado y confirmándolo con la tecla Enter.

También se puede examinar el historial en función de palabras clave con el atajo de teclado [CTRL] + [R]. Utilizando la orden sin opciones ni argumentos se obtiene la lista completa de comandos numerada.

Para filtrar la salida se combina history con el programa grep (ver opciones de búsqueda) y una palabra clave utilizando la barra vertical.
| grep PALABRA CLAVE

