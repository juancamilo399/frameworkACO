# DeseabilityHeuristic Class

Esta clase define la función heuristica de deseabilidad. Esta clase tiene como objetivo definir heuristica de deseabilidad la cual evalua un arco del grafo y determina que tan buenos es este, determinando de esta manera que arco se añade a la solución según una regla que tambien tiene en cuenta el nivel de feromonas de dicho arco.


la definición genérica de esta clase se presenta a continuación: 

````
 DeseabilityHeuristic(environment)
````
### Arguments

- environment: Objeto de tipo ambiente sobre el cual se trabaja.

## get_deseability Method

Metodo abstracto que define la heuristica de deseabilidad y retorna dicho valor para los arcos conectados a un nodo.

````
 get_deseability(edges)
````
### Arguments

- edges: Arcos del grafo conectados al nodo actual.


Esta clase al ser abstracta debe ser extendida por otra donde se implemente el metodo anterior, de esta manera se crea una clase que defina este comportamiento según el problema que se quiere resolver.
