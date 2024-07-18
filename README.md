# <p align="center">*Análisis de Cursos del Año 2022*</p>

## Resumen

Este proyecto se centra en el análisis de un dataset de cursos del año 2022, agrupados por semestre. El dataset original contenía 196,124 filas y 24 columnas, con un alto porcentaje de datos nulos en varias columnas. Se realizaron diversas etapas de limpieza de datos, análisis estadístico y aplicación de técnicas de machine learning para obtener insights valiosos sobre el rendimiento académico de los estudiantes. Además, se desarrollaron visualizaciones y un informe detallado con los hallazgos principales.

## Estructura del Proyecto

El proyecto está organizado en las siguientes carpetas y archivos:

### Carpetas

- **[Data](./Data/)**: Contiene todos los archivos CSV que se analizaron.
- **[images](./images/)**: Contiene las imágenes utilizadas para el informe redactado.

### Archivos

- **[Analisis_ML - muestras_extraidas.ipynb](./Analisis_ML%20-%20muestras_extraidas.ipynb)**: Contiene el análisis de la muestra extraída.
- **[ETL - EDA.ipynb](./ETL%20-%20EDA.ipynb)**: Contiene la limpieza del archivo original y el análisis estadístico principal.
- **[informe_EDA.md](./informe_EDA.md)**: Contiene un informe en formato plano con los principales hallazgos.

## Descripción de los Archivos

1. **[Data](./Data/)**:
   - Esta carpeta contiene todos los archivos CSV utilizados para el análisis.

2. **[images](./images/)**:
   - Esta carpeta contiene las imágenes generadas y utilizadas para el informe redactado.

3. **[Analisis_ML - muestras_extraidas.ipynb](./Analisis_ML%20-%20muestras_extraidas.ipynb)**:
   - Este archivo Jupyter Notebook contiene el análisis de la muestra extraída del dataset original. Incluye técnicas de machine learning aplicadas para obtener insights adicionales sobre los datos completos.

4. **[ETL - EDA.ipynb](./ETL%20-%20EDA.ipynb)**:
   - Este archivo Jupyter Notebook detalla el proceso de limpieza del dataset original y el análisis estadístico principal, incluyendo la identificación y corrección de errores en los datos.

5. **[informe_EDA.md](./informe_EDA.md)**:
   - Este archivo contiene un informe en formato plano que resume los principales hallazgos del análisis exploratorio de datos (EDA).

6. **[Dashboard.pbix](./Dashboard.pbix)**:
   - Tablero dinamico que presenta el rendimiento de los estudiantes, métricas y KPI importantes.


### Conclusiones

El análisis del dataset de cursos del año 2022 reveló varios puntos importantes:

1. **Datos Nulos y Eliminación de Columnas**: Un alto porcentaje de datos nulos en varias columnas llevó a la eliminación de estas para poder realizar un análisis más limpio y preciso.
2. **Duplicados y Repetición de Cursos**: No se encontraron duplicados exactos; en su lugar, se observó que algunos estudiantes cursaron el mismo curso más de una vez en el mismo semestre.
3. **Desbalance en los Semestres**: Existe un desbalance significativo en la cantidad de registros entre los dos semestres del año, afectando el análisis comparativo de las notas finales.
4. **Errores en Variables Categóricas**: Se detectaron y corrigieron errores en variables categóricas como `semestre_año`, `id_curso` e `id_usuario`.
5. **Impacto del Curso en el Rendimiento Académico**: Se encontró que el curso en el que un estudiante está matriculado tiene un impacto significativo en su rendimiento académico.
6. **Relación entre Notas y Tareas**: Se demostró una relación positiva moderada entre las notas finales de la materia y el puntaje en las tareas, así como un impacto significativo del tipo de tarea en las notas finales.

