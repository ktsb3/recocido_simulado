# Recocido simulado para el problema del viajero
> El objetivo general de este algoritmo es encontrar una buena aproximación al recorrido optimo de un viajero que debe pasar por todas las ciudades indicadas sin recorrer dos veces la misma ciudad y en el menor costo posible


## Instalar

`pip install recocido_simulado`

## como usar

```
N, T, distances = inpt()
distances_complete = fillmatrix(distances, N)
best_sol, best_cost = recocido(N, T, distances_complete)

print(best_sol)
print(best_cost)
```
