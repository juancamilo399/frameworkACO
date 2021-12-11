# Algoritmo colonia de hormigas (ACO)

## Genetic Algorithm Class

A continuación se detalla la definición de la clase ACO. Esta clase tiene como atributos otros objetos de otras clases que representan los distintos componentes del modelo.

````
 ACO(environment,colonyPheromone,deseabilityHeuristic)
````

### Arguments

- environment: Objeto de tipo Environment que define el ambiente del modelo.
- colonyPheromone: Objeto de tipo ColonyPheromone que define el comportamiento de las feromonas del modelo.
- deseabilityHeuristic: Objeto de tipo DeseabilityHeuristic que define la heuristica de deseabilidad del modelo.

## Run Method

Metodo encargado de iniciar el algoritmo.
    
````
 ACO.run(agents,iterations,transitions,decay,alpha,beta)
````

### Arguments

- agents: Número de agentes (hormigas).
- iterations: Número de iteraciones.
- transitions: Número de movimientos que se realizarán en el grafo.
- decay: tasa de evaporación de las feromonas:
- alpha: hiperparametro de explotación(feromonas)
- beta: hiperparametro de exploración(heuristica deseabilidad)