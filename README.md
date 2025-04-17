# Fifa Data Analysis

Este proyecto tiene como objetivo realizar un análisis comparativo de datos de FIFA de los años 2021, 2023 y 2024, enfocado en tres categorías clave: **jugadores**, **equipos** y **técnicos**. Utilizando herramientas de análisis de datos y visualización, busco explorar las tendencias, comparativas y estadísticas más relevantes entre estos años.

## Estructura del Proyecto

La carpeta `Datasets/` contiene los archivos CSV utilizados para el análisis. El proyecto está organizado por año, con subcarpetas para cada uno:

- `2021`: Datos sin procesar. Se realizó un preprocesamiento de datos aplicando técnicas como cambio de formatos, eliminación de columnas, renombramiento de columnas, modificación de strings e identificación de nulos. Posteriormente se realizó un análisis mediante gráficas enfocado mayormente a Valores, Altura y Peso con los datos ya limpios. 
- `2023`: Datos parcialmente organizados. Se realizó preprocesamiento de datoa aplicando técnicas como cambio de formatos, elimincación de columnas, renombramiento de columnas, agrupación por tipos de datos, modificación de strings e identificación de nulos. Posteriormente se realizó un análisis mediante gráficas diferenciado de Coaches y Teams, con sus respectivos análisis posibles. 
- `2024`: Datos estructurados y listos para análisis y visualización. Se realizó un análisis descriptivo y visual de los datos para obtener variantes con respecto a los 30 mejores jugadores en cada posición (delanteros, mediocampistas, defensas y arqueros). Se analizaron sus habilidades por individual para poder resaltar cuales son los mejores futbolistas no solo a partir de su Overall, sino de sus atributos y lograr identificar en que destaca cada uno de ellos para que un jugador pueda determinar a partir de sus necesidades cual es el mejor futbolista.

> **Git Large File Storage (LFS)** ha sido implementado para gestionar los archivos CSV de gran tamaño. Asegúrate de tener Git LFS instalado para clonar correctamente este repositorio.

## Tecnologías y Herramientas

- Python (pandas, matplotlib, seaborn, etc.)
- Git & Git LFS
- Jupyter Notebooks (para análisis exploratorio)

## Notas

- Algunos archivos superan los 100MB, por lo que GitHub requiere el uso de Git LFS.
- Si estás clonando este proyecto por primera vez, asegúrate de ejecutar:

```bash
git lfs install
git clone https://github.com/Tomaslopera/Fifa_Analysis.git
```

