# Waypoints

Para el desarrollo de esta práctica se han usado los standard assets de la unity store, en concreto los scripts WaypointCircuit.cs y WaypointProgressTracker.cs.

Creamos primero un circuito con un objeto vacio y dentro de este añadiremos una serie de objetos sobre un plano que haran de waypoints, dentro del inspector del WaypointCircuit pulsamos el botón "Assign using all child objects".

Crearemos despues un "centinela" (la esfera amarilla en el gif) a la que le añadiremos el script WaypointProgressTracker.cs y le especificamos el circuito creado y un Target ( Cápsula naranja en el gif ) para que huya recorriendo el circuito cuando el centinela se le acerque.

De esta forma hemos creado un circuito que el target (Esfera amarilla) recorrera para huir del centinela (Cápsula naranja).

![gif](./GIF/Waypoints.gif)
