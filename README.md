## Machine-Learning
#Master Data Science CUNEF
Dentro de happy countries, tendréis la siguiente estructura:

README.md <- The top-level README for developers.

data

01_raw <- Immutable input data
02_intermediate<- Cleaned version of raw
03_processed <- Data used to develop models
04_models <- trained models
05_model_output<- model output
06_reporting <- Reports and input to frontend
docs <- Space for Sphinx documentation

notebooks <- Jupyter notebooks. Los notebooks se nombran como siguen (tomadlo como ejemplos, lo importante son los número de prefijo para saber en qué orden ejecutarlo): 00_Data_Processing, 01_EDA_Analysis...

references <- Data dictionaries, manuals, etc.

results <- Final analysis docs.

requirements.txt <- The requirements file for reproducing the analysis environment.

.gitignore <- Avoids uploading data, credentials, outputs, system files etc

src <- Source code for use in this project. Aquí solo los py si los hubiera, nunca notebooks
En este trabajo hemos realizado un análisis exploratorio de la siguiente base de datos: https://www.kaggle.com/unsdsn/world-happiness 
Hemos cogido la información correspondiente a 156 países a lo largo de 2019, analizando la felicidad de cada país con una puntuación basada en variables como el GDP per capita, la generosidad, la corrupción, la salud.....
He analizado cada variable, estudiado la correlacion entre ellas, detectado outliers, elaborado graficas....
