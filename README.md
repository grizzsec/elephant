# elephant

'''
           __..--''``---....___   _..._    __
 /// //_.-'    .-/";  `        ``<._  ``.''_ `. / // /
///_.-' _..--.'_    \                    `( ) ) // //
/ (_..-' // (< _     ;_..__               ; `' / ///
 / // // //  `-._,_)' // / ``--...____..-' /// / //
'''


Herramienta con un programa interactivo realizada con Python, similar a Unicorn pero más avanzada y adaptada.

¿Qué hace? 

Generar payload: Esta opción genera un payload, que es una secuencia de bytes utilizada en exploits o técnicas de hacking. En este caso, se ha utilizado un payload de ejemplo con bytes \x90\x90\x90\x90, pero puedes personalizar la lógica en la función generar_payload() para generar un payload según tus necesidades.

Emular código: Esta opción te permite emular el código proporcionado utilizando la biblioteca Unicorn. Puedes ingresar el payload en formato hexadecimal y la herramienta lo emulará utilizando la arquitectura x86 y el modo 32 bits. Si el formato hexadecimal no es válido, se mostrará un mensaje de error.

Ejecutar comando del sistema: Esta opción te permite ejecutar comandos en el sistema operativo. Puedes ingresar un comando válido y la herramienta lo ejecutará utilizando la función ejecutar_comando(). Ten en cuenta que esta función puede variar según el sistema operativo y los permisos del usuario.

Cargar archivo: Esta opción te permite cargar el contenido de un archivo. Puedes ingresar la ruta del archivo y la herramienta leerá su contenido utilizando la función cargar_archivo(). Si el archivo no existe, se mostrará un mensaje de error.

Guardar archivo: Esta opción te permite guardar contenido en un archivo. Puedes ingresar la ruta del archivo y el contenido que deseas guardar, y la herramienta utilizará la función guardar_archivo() para escribir el contenido en el archivo. En caso de errores, se mostrará un mensaje correspondiente.

Salir: Esta opción finaliza la ejecución del programa.
