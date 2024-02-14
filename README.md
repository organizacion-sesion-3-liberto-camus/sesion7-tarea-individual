# sesion7-tarea-individual
Tarea 7 del curso Gestión de la tarea docente con Github

# Enunciado de la práctica: Menús parte I
Crea un script llamado gestion_usuarios.sh que limpie la pantalla y muestre un menú como el que sigue:

```
MENU
----
1. Crear usuario
2. Eliminar usuario
3. Mostrar la información del usuario
4. Salir

Elige una opción del menú:
```

Si el usuario no ha indicado ninguna opción o una opción que no está en el menú deberá mostrar un mensaje de error indicándolo y terminar la ejecución del programa.

Si el usuario ha introducido una opción válida realizará una acción distinta dependiendo de la opción seleccionada. Deberás utilizar para ello la estructura ```if```:

* Si el usuario ha pulsado 1 (Crear usuario), le pedirá un nombre de usuario y después lo creará.
* Si el usuario ha pulsado 2 (Eliminar usuario), le pedirá un nombre de usuario y después lo eliminará.
* Si el usuario ha pulsado 3 (Mostrar información del usuario), le pedirá un nombre de usuario y mostrará su información.
* Si el usuario ha pulsado 4 (Salir) mostrará un mensaje indicando “Programa finalizado”.

Por lo tanto, el menú se ejecutará una única vez.
