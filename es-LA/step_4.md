## Seguimiento de fallas

Agreguemos un código para realizar un seguimiento de los errores.

+ Vas a agregar un 1 a tu variable ` fallas` cada vez que se realiza una conexión en Pin0. Para hacer esto, arrastre ` al pin P0 presionado` desde 'Entrada'.

![captura de pantalla](images/frustration-pressPin0.png)

+ Luego, agregue 2 bloques para mostrar una cruz durante 1 segundo cuando se presiona Pin0.

![captura de pantalla](images/frustration-pin0-x.png)

+ Luego deberá agregar 1 a su variable ` fallas`. Para hacer esto, haga clic en arrastar un `cambiar objeto por 1` de Variables y cambia `elemento` a `falla`. 

![captura de pantalla](images/frustration-pin0-fails.png)

+ Finalmente, puede agregar un código para mostrar el número actualizado de fallas. Así es como debería verse su código.

![captura de pantalla](images/frustration-pin0-code.png)

+ Prueba tu código presionando el botón A en el emulador para comenzar tu juego. Cada vez que presione Pin0 debería ver un aumento de su variable `fallas` en 1.

![captura de pantalla](images/frustration-pin0-test.png)

+ Haga clic en 'Descargar' y transfiera su secuencia de comandos a su micro: bit. Puede presionar Pin0 completando un circuito. Para hacer esto, coloque el pulgar derecho en el pin de tierra (GND) y luego toque Pin0 con el pulgar izquierdo.

![captura de pantalla](images/frustration-pin0-compile.png)