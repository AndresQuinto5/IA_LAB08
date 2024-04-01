# Laboratorio 8 - Inteligencia Artificial
## CC3045 - Semestre I - 2024

### Descripción
Este laboratorio se enfoca en la implementación de tres algoritmos diferentes de satisfacción de restricciones (Constraint Satisfaction Problem, CSP) para resolver un problema de programación de exámenes para cuatro estudiantes que toman siete exámenes diferentes. El objetivo es calendarizar los exámenes respetando diversas limitaciones y preferencias.

### Tareas
- **Task 1 - Teoría:**
  - Investigar el algoritmo AC-3 y su relación con el algoritmo de backtracking search.
  - Definir en sus propias palabras el término "Arc Consistency".
  - Las respuestas pueden ser subidas en un PDF o dentro del mismo Jupyter Notebook.

- **Task 2 - CSP con Backtracking, Beam y Local Search:**
  - Implementar tres algoritmos diferentes de satisfacción de restricciones:
    1. Algoritmo de backtracking search
    2. Algoritmo de beam search
    3. Algoritmo de local search
  - Definir las variables y restricciones del problema de programación de exámenes.
  - Tomar el tiempo que le toma a cada algoritmo encontrar una solución.
  - Comparar el tiempo y la solución encontrada por cada algoritmo.
  - Escribir las conclusiones como parte de una celda "markdown" en el Jupyter Notebook.

### Entregables
1. Link al repositorio de los integrantes del grupo.
   - Subir también el código a Canvas por temas de Acreditación.

### Evaluación
- [1 pts.] Task 1 (0.5 pts cada pregunta)
- [3 pts.] Task 2 - Implementación de algoritmos (1pt cada algoritmo)
- [1 pts.] Task 2 - Conclusiones
Total: 5 pts.

## Requisitos Previos (Usamos CONDA !! :D)

- Miniconda instalado en su sistema. Si no tiene Miniconda, puede descargarlo desde [aquí](https://docs.conda.io/en/latest/miniconda.html).

## Configuración del Entorno

Siga estos pasos para configurar el entorno Conda necesario para ejecutar el notebook:

1. **Clonar el Repositorio**

Primero, clone el repositorio a su máquina local usando Git:

```bash
git clone https://github.com/AndresQuinto5/IA_LAB08.git
cd IA_LAB08
```

### Crear el Entorno Conda
Cree un entorno Conda utilizando el archivo environment.yml incluido en el repositorio. Esto instalará todas las dependencias necesarias.

```
conda env create -f environment.yml
```

### Activar el entorno

```
conda activate nombre_del_entorno
```

#### Ejecutar el Jupyter Notebook

Con el entorno activado, inicie Jupyter Notebook o JupyterLab:

```
jupyter notebook
# o
jupyter lab
```

### Autores
- [Andres Quinto - 18288](https://github.com/AndresQuinto5)
- [Marlon Hernández - 15177](https://github.com/ivanhez)