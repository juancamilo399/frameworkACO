# ColonyPheromone Class

Esta clase define las feromonas y su comportamiento en el modelo. Esta clase tiene como objetivo definir la forma en la que se inicializan las feromonas y la determinar la cantidad de feromonas que un agente deposita(función delta).


la definición genérica de esta clase se presenta a continuación: 

````
 ColonyPheromone(environment)
````
### Arguments

- environment: Objeto de tipo ambiente sobre el cual se trabaja.

## generate_pheromones Method

Metodo abstracto que inicializa las feromonas.

## delta_pheromone Method

Metodo abstracto que determina la cantidad de feromonas a depositar sobre un arco.

````
 delta_pheromone(edge)
````
### Arguments

- edge: Arco del grafo.


Esta clase al ser abstracta debe ser extendida por otra donde se implementen los metodos anteriores, de esta manera se crea una clase que defina este comportamiento según el problema que se quiere resolver.
