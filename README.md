# Proyectos de RStudio y RMarkdown
 
Este repositorio contiene una serie de proyectos simples para la práctica de R y RMarkdown. Para generar el código se ha utilizado RStudio.

## Contenido

### Análisis y visualización de datos con R 🔍📊

Se exploran los conceptos básicos de manipulación y visualización de datos utilizando R. Se incluyen ejemplos de cómo cargar datos, realizar operaciones básicas, crear gráficos simples y más.

Algunas de las librerías utilizadas son:
- summarytools
- ggplot2
- tidyverse
- carData
- readr

### Creación de Informes con RMarkdown 📝📈

Los archivos se centran en la creación de informes dinámicos utilizando RMarkdown. RMarkdown es un formato de archivo que combina texto escrito en Markdown con bloques de código R. Estos documentos pueden ser ejecutados y convertidos en varios formatos de salida, como HTML, PDF y Word, utilizando la función ``knit`` en RStudio.

## Estructura del Repositorio 

- ``dataset_salaries.Rmd``: Archivo Rmarkdown que contiene el código para el análisis del set de datos **Salaries** del paquete **carData** de R, con la información del salario de profesores de una institución de enseñanza superior en EEUU. 
- ``dataset_titanic.Rmd``: Archivo Rmarkdown que contiene el código para el análisis del set de datos **TitanicSurvival** del paquete **carData** de R. Incluye el preprocesamiento de los datos y su visualización.
- ``dataset_gapminder.Rmd``: Archivo Rmarkdown que contiene el código para el análisis de los archivos .csv **gapminder_1800.csv** y **hiv.csv**, con información de métricas socioeconómicas de países de todo el mundo y de prevalencia del VIH, respectivamente. Incluye el preprocesamiento de los datos y su visualización.
- /Data: Carpeta de datos que incluye los archivos .csv ``gapminder_1800.csv`` y ``hiv.csv``.
- /pdf: Carpeta que incluye los reportes en .pdf generados mediante los ficheros Rmarkdown.
