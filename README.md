# Practica_clase_2

# Ruta de evacuación: cuando el camino más corto no es el mejor

Prototipo que busca una ruta desde una zona afectada hasta un refugio en un terreno inundado. Compara estrategias de búsqueda y muestra que la ruta más corta no siempre es la más conveniente cuando se considera el riesgo de inundación.

**Equipo:** Morales Mendez Shryley Nicoles, Jimenez Andrade Monserrat, Tejero Hernandez Rubi, Sarao Morales Rubi
**Curso:** Fundamentos de la IA

## Contenido

- `Actividad_Ruta_Evacuacion.ipynb`: notebook principal con el modelo del terreno, los algoritmos, las visualizaciones, la comparación, las pruebas y la explicación de decisiones.

## Qué hace

- Representa el terreno como una cuadrícula con celdas libres, 4 niveles de inundación y celdas bloqueadas.
- Calcula el costo de cada celda como 1 + λ · riesgo, así que el riesgo influye en la decisión.
- Implementa BFS, Dijkstra, A* y búsqueda voraz, y los compara por costo de la ruta, pasos, nodos expandidos y generados, y tiempo.
- Valida cada ruta con un verificador independiente de los algoritmos.
- Incluye pruebas de los escenarios pedidos y una prueba adicional que detecta errores de la propia implementación.

## Uso de IA
La declaración de herramientas de IA y de cómo se verificó el código está en la sección 8 del notebook.