# Glosario Comandos Vim

- Al entrar a Vim iniciamos en modo normal en donde solo podremos movernos entre el texto y relizar comandos, algunos comandos basicos:
    - **:q** Salir de Vim
    - **:w** Guardar archivo
    - **:wq** Guardar y salir
    - **:q!** salir sin realizar cambios
- Movimiento: 
    - Para navegar en el texto se utiliza **h j k l** que respectivamente es izquierda, abajo, arriba, derecha.
    - Para moverse entre paralabros se utliza **w** para moverse al inicio de la siguiente palabra, **e** para moverse al final de la palabra y **b** para moverse al inicio de la palabra actual y para moverse al inicio de la anterior.
    - Se pueden utilizar números en conjunto con los comandos ya establecidos, por ejemplo **5w** se movera al inicio de la 5ta siguiente palabra.

- Edición de texto
    - Los comandos basicos par edición son:  
    - **x**  borrar el caracter en donde está el cursor
    - **i** insertar texto
    - **A** insertar texto al final de la linea actual
    - **dw** borrar el resto de la palabra en donde se encuentra el cursor, 
    - **d$** borra el resto de la linea en donde se encuentra el cursor
    - **u** deshacer


- Buscar: se utliza el comando **f**