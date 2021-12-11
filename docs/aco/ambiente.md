# Environment Class

Esta clase define el ambiente del modelo, esta tiene como objetivo inicializar el grafo ponderado sobre el cual se va a realizar la busqueda de lasolución.

la definición genérica de esta clase se presenta a continuación: 

````
 Environment(graph)
````

### Arguments

- graph: Grafo ponderado correspondiente al problema.

## generate_graph Method

Metodo abstracto encargado de inicializar el grafo (graph)

## get_start_point Method

Metodo abstracto encargado de elegir el punto inicial de cada agente en el grafo (start_point)

# EnvironmentNodes Class

Esta clase extiende Environment añadiendo el atributo de correspondiente a los nodos, construyendo el grafo respecto a estos.

la definición de esta clase se presenta a continuación: 

````
 EnvironmentNodes(nodes)
````

### Arguments

- nodes: Nodos correspondientes al modelo sobre los cuales se construye el grafo.