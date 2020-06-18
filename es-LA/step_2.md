## Fallo en el almacenamiento

Comencemos creando un lugar para almacenar el número de fallas.

+ Vaya a <a href="https://rpf.io/microbit-new" target="_blank"> rpf.io/microbit-new </a> para comenzar un nuevo proyecto en el editor MakeCode (PXT). Llame a su nuevo proyecto 'Frustración'.

+ Eliminar los bloques `para siempre` y `comenzar` arrastrándolos a la paleta:

![captura de pantalla](images/frustration-bin.png)

+ Un nuevo juego debe comenzar cuando el jugador ó la jugadora presiona el botón A. Haga clic en 'Entrada' y luego ` en el botón A presionado `.

![captura de pantalla](images/frustration-onPressA.png)

+ Ahora necesitas una variable para almacenar la cantidad de veces que fallas en el juego tocando el cable con la varita. Haga clic en 'Variables' y luego en 'Crear una nueva variable'. Nombre la variable `fallas`.

![captura de pantalla](images/frustration-variable.png)

+ Arrastre un bloque `conjunto` desde 'Variables' y seleccione `fallas`:

![captura de pantalla](images/frustration-fails.png)

Esto establecerá el número de fallas a cero cuando presionar el botón A.

+ Finalmente, puede mostrar el número de `fallas` en tu micro:bit. Para hacer esto, primero arrastre un bloque `mostrar número` desde 'Básico' hasta el final de su secuencia de comandos.

![captura de pantalla](images/frustration-show.png)

+ Luego arrastre `fallas` desde 'Variables' a su `bloque de conjunto`.

![captura de pantalla](images/frustration-show-fails.png)

+ Click 'run' to test your script. Al hacer clic en el botón A debería aparecer el número de fallas, que se ha establecido en `0`.

![captura de pantalla](images/frustration-fails-test.png)