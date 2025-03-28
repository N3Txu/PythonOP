# Optimización Lineal con SciPy

Este proyecto implementa un modelo de optimización lineal utilizando Python y la biblioteca SciPy. El objetivo es minimizar el costo de instalación de una red, considerando restricciones de cobertura y presupuesto.

## Descripción del Problema

Se busca minimizar la función objetivo:  
**Z = 5x + 200y**  
donde:

- `x` representa los metros de cable.
- `y` representa los puntos Wi-Fi.

### Restricciones:

1. **Cobertura mínima:** \( 10x + 100y \geq 2000 \)
2. **Presupuesto máximo:** \( 5x + 200y \leq 20000 \)
3. **No negatividad:** \( x \geq 0, y \geq 0 \)

## Solución

El problema se resuelve utilizando el método `highs` de SciPy, que implementa un enfoque mejorado del método simplex.

### Resultados esperados:

- Valores óptimos de \( x \) y \( y \).
- Costo mínimo \( Z \).

## Requisitos

- Python 3.12 o superior.
- Biblioteca SciPy instalada.

## Ejecución

1. Clona este repositorio.
2. Abre el archivo `mainOP.ipynb` en Jupyter Notebook o un entorno compatible.
3. Ejecuta las celdas para obtener la solución óptima.

## Autor

Este proyecto fue desarrollado como un ejercicio práctico de optimización lineal.
