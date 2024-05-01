# Trabajo Práctico N1 - Redes Neuronales
Ines Quihillalt & Bruno Di Sanzo

## Clasificador de Texto Utilizando Base de Datos The 20 News Groups

Este proyecto se implementan modelos clasificadores de texto utilizando los algoritmos Multinomial Naive Bayes y de Regresion Logistica. Se utiliza Count Vectorizer y TF IDF para el procesamiento del lenguaje. 

### Descripción

El objetivo principal de este proyecto es desarrollar un clasificador de texto eficiente. 
Para esto se comparan diferentes modelos mediante la accuracy al clasificar un texto y se emplea Grid Search para encontrar los parámetros óptimos de alpha en NB, C en RL y max_df y min_df, los umbrales del máximo y el mínimo de veces que deben aparecer palabras en los documentos para ser consideradas en el CV y TF IDF.

### Tecnologías Utilizadas

- Python
- Scikit-learn

## RESULTADOS
### Multinomial NB con CountVectorizer
* Train: 88.27753839354767%
* Validation: 72.20503756076006%
* Test: 65.2283590015932%

### Regresion Lineal con CountVectorizer
* Train: 91.97878687437853% 
* Validation: 69.06760936809545%
* Test: 62.519915029208704% 

### Multinomial NB con TF IDF --> MEJOR MODELO
* Train: 94.49784554192907%
* Validation: 76.18205921343349%
* Test: **68.75995751460435% **

## Regresion Lineal con TF IDF
* Train: 96.35399403380842%
* Validation: 74.28192664604506%
* Test: 66.91449814126395%
