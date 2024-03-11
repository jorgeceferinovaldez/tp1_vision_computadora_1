# Especialización en Inteligencia Artificial

# Trabajo Práctico N° 1

# Visión por Computadora I
---

## Alumno: Jorge Ceferino Valdez


# Enunciado

- Parte 1 (imágenes en `/white_patch`  y `/coord_cromaticas`):
    1. Implementar el algoritmo de pasaje a coordenadas cromáticas para librarnos de las variaciones de contraste.
    2. Implementar el algoritmo White Patch para librarnos de las diferencias de color de iluminación.
    3. Mostrar los resultados obtenidos y analizar las posibles fallas (si es que las hay) en el caso de White patch.

- Parte 2:
    1. Para las imágenes img1_tp.png y img2_tp.png leerlas con OpenCV en escala de grisas y visualizarlas.
    2. Elija el numero de bins que crea conveniente y grafique su histograma, compare los histogramas entre si.
    Explicar lo que se observa, si tuviera que entrenar un modelo de clasificación/detección de imágenes, considera que puede ser de utilidad tomar como ‘features’ a los histogramas?
    3. Para la imagen segmentacion.png analice el histograma de los canales RGB. Segmente algunos de los elementos presentes en la imagen (agua, cielo, tierra) y muestre, aplicando mascaras, las regiones en imágenes separadas.

# Instalación

Luego de clonar el repositorio ejecutar desde el directorio raiz:

1.- Crear un entorno virtual con venv.

2.- Active el entorno creado

3.- Proceda a instalar los paquetes necesarios para el proyecto.

    $ make install

4.- Desinstalación del ambiente venv

    $ make clean

