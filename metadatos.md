---
title: "metadatos"
output: html_document
---

# *Seleccionar un dataset de metabolómica*

En mi caso, he seleccionado y descargado el dataset Cachexia procedente de https://github.com/nutrimetabolomics/metaboData/. Para trabajar con estos datos en R, cargamos el archivo "human_cachexia.csv" que tiene los datos con los que trabajaremos.

```{r}
# Indicar la ruta del archivo
ruta_archivo <- "D:/Máster bioinformática/Análisis de datos ómicos/PEC1/human_cachexia.csv"

# Cargar el archivo
cachexia <- read.csv(ruta_archivo)

```