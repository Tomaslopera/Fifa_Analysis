# Fifa Data Analysis

Este proyecto tiene como objetivo realizar un análisis comparativo de datos de FIFA de los años 2021, 2023 y 2024, enfocado en tres categorías clave: **jugadores**, **equipos** y **técnicos**. Utilizando herramientas de análisis de datos y visualización, buscamos explorar las tendencias, comparativas y estadísticas más relevantes entre estos años.

## Estructura del Proyecto

La carpeta `Datasets/` contiene los archivos CSV utilizados para el análisis. El proyecto está organizado por año, con subcarpetas para cada uno:

- `2021`: Datos sin procesar. Es necesario realizar una limpieza previa antes de cualquier análisis.
- `2023`: Datos parcialmente organizados.
- `2024`: Datos estructurados y listos para análisis y visualización.

> **Git Large File Storage (LFS)** ha sido implementado para gestionar los archivos CSV de gran tamaño. Asegúrate de tener Git LFS instalado para clonar correctamente este repositorio.

## Tecnologías y Herramientas

- Python (pandas, matplotlib, seaborn, etc.)
- Git & Git LFS
- Jupyter Notebooks (para análisis exploratorio)

## Enfoque Inicial

- Análisis descriptivo y visual de los datos del 2024, por ser los más organizados.
- Limpieza y preparación de los datos del 2021 y 2023 para análisis posterior.
- Comparativas entre años sobre rendimiento de jugadores, distribución por nacionalidad, media de atributos, técnicos más representativos, entre otros.

## Notas

- Algunos archivos superan los 100MB, por lo que GitHub requiere el uso de Git LFS.
- Si estás clonando este proyecto por primera vez, asegúrate de ejecutar:

```bash
git lfs install
git clone https://github.com/Tomaslopera/Fifa_Analysis.git
```

