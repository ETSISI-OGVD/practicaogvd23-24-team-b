# Apple Quality Classification in Azure

Autores:
- Eduardo Miguel Riederer
- Samuel Reyes Sanz

Dataset: [https://www.kaggle.com/datasets/nelgiriyewithana/apple-quality/data](https://www.kaggle.com/datasets/nelgiriyewithana/apple-quality/data)

EDA: [https://www.kaggle.com/code/bryamblasrimac/applequality-eda-classification-multiplemodels](https://www.kaggle.com/code/bryamblasrimac/applequality-eda-classification-multiplemodels)

## 1. Azure Synapse

## 2. Azure ML

El script [inference.ipynb](train_model.ipynb) contiene el código necesario para entrenar, hacer log de las métricas y guardar el modelo dentro del entorno de AzureML.

## 3. Model Inference

En esta sección, demostramos cómo el modelo realiza inferencias sobre nuevos datos. La inferencia se lleva a cabo a través de un endpoint creado en AzureML sobre el modelo previamente entrenado.

![Model Inference](assets/inference.gif)
