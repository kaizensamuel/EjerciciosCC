# Buscar una aplicación de ejemplo, preferiblemente propia, y deducir qué patrón es el que usa. ¿Qué habría que hacer para evolucionar a un patrón tipo microservicios?

La aplicacion elegida es mi TFG, este proyecto consistia en hacer un juego escape room utilizando posicionamiento en interiores utilizando una plataforma hardware POZYX con arduino, para la comunicacion entre servidor y android para mostrar las dinamicas de juego. La arquitectura es la siguiente:

![Arquitectura](https://github.com/kaizensamuel/EjerciciosCC/blob/main/Tema%201/imagenes/Arquitectura.png) 

Para mejorar este sistema y utilizar microservicios en la nube se podria dividir en tres plataforma un servidor de bd, que almacene jugadores y coordenadas , Un servidor que procese los datos enviados desde arduino y los envie tanto a cada jugador como al almacenaje de bd. 
