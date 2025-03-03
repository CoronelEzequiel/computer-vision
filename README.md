# 🚀 Proyecto de Visión Computacional - "Trayectoria del Robot"

## Descripción del Proyecto


Este proyecto de visión computacional se enfoca en desarrollar un sistema que simule el movimiento de un robot siguiendo un camino predefinido. Utilizando técnicas de procesamiento de imágenes y OpenCV, el robot es capaz de detectar un punto de inicio, identificar el camino más largo entre varios candidatos y seguirlo correctamente.

El propósito principal de este proyecto es demostrar la capacidad de utilizar algoritmos de computer vision para resolver problemas de navegación autónoma, aplicando reglas heurísticas para la toma de decisiones a lo largo del trayecto.

## Funcionalidades Principales

- **Detección del punto de inicio**: El robot detecta automáticamente el punto de inicio del trayecto.
- **Elección de la mejor ruta**: Se evalúan diferentes direcciones posibles, y el robot selecciona la dirección con el trayecto más largo.
- **Simulación del movimiento**: Se genera una simulación visual donde el robot sigue el camino detectado.
- **Generación de video**: El proyecto crea un video que muestra el movimiento del robot a lo largo del camino.
- **Manejo de intersecciones**: El sistema es capaz de manejar intersecciones y seguir el camino adecuado.

## Tecnologías Utilizadas

- **Python**: Lenguaje principal utilizado en el desarrollo del proyecto.
- **OpenCV**: Librería de procesamiento de imágenes utilizada para la detección del camino y la simulación del movimiento del robot.
- **Matplotlib**: Para la visualización del camino seguido por el robot.
- **Jupyter Notebooks**: Herramienta utilizada para el desarrollo iterativo y la experimentación.

## Aprendizajes Clave

1. **Detección y procesamiento de trayectorias**: Aprendimos cómo utilizar OpenCV para binarizar imágenes, identificar caminos y realizar seguimiento de posiciones clave en tiempo real.
   
2. **Algoritmos de toma de decisiones**: El proyecto implementa una lógica que permite al robot elegir la dirección correcta en intersecciones, lo cual es aplicable en escenarios de navegación autónoma.

3. **Generación de video con OpenCV**: Se utilizó OpenCV para crear videos que visualizan el recorrido del robot en cada iteración, aprendiendo sobre la manipulación de cuadros de video en el proceso.

4. **Manejo de errores y depuración**: Durante el desarrollo, se abordaron varios desafíos, como la identificación correcta del punto de inicio, la toma de decisiones basadas en caminos posibles y la depuración de errores en el movimiento.

## Requisitos del Proyecto

Para ejecutar este proyecto en tu entorno local, necesitarás tener instaladas las siguientes dependencias:

```bash
pip install opencv-python
pip install matplotlib

