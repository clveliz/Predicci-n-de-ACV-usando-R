# Predicción del riesgo de ACV con Machine Learning en R

Repositorio con un script en R para predecir el riesgo de accidente cerebrovascular (ACV) mediante análisis de datos y entrenamiento de un modelo de machine learning.

## Archivos
- `ACV-R.Rmd` — Código principal del proyecto (preprocesamiento, entrenamiento y evaluación).
- `healthcare-dataset-stroke-data.csv` — Dataset utilizado para el análisis y entrenamiento del modelo.
- `README.md` — Descripción del proyecto y guía rápida.

## Uso
1. Descargar o clonar el repositorio.
2. Abrir `Build-deploy-stroke-prediction-model-R.Rmd` en RStudio.
3. Instalar paquetes necesarios:
```r
install.packages(c("tidymodels","caret","randomForest", "xgboost", "shiny", "GGally"))
