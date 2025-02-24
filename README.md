# Análisis de Sentimientos en Español

Este repositorio contiene un cuaderno de Jupyter (`analisis_sentimientos.ipynb`) que implementa un análisis de sentimientos en español utilizando un modelo preentrenado basado en Naive Bayes y TF-IDF. El modelo es proporcionado por la librería `sentiment-analysis-spanish`, creada por Elliot Hofman.

## Descripción

El análisis de sentimientos es una técnica de procesamiento de lenguaje natural (NLP) que permite determinar la polaridad (positiva, negativa o neutral) de un texto. En este caso, el modelo está entrenado específicamente para textos en español.

El cuaderno incluye:
1. Instalación de las dependencias necesarias.
2. Uso de la librería `sentiment-analysis-spanish` para analizar el sentimiento de frases en español.
3. Ejemplos prácticos de análisis de sentimientos con frases positivas, negativas y neutrales.

## Requisitos

Para ejecutar el cuaderno, necesitas tener instalado:

- Python 3.x
- Jupyter Notebook o Google Colab
- Las siguientes librerías de Python:
  - `sentiment-analysis-spanish`
  - `scikit-learn`
  - `keras`
  - `tensorflow`

Puedes instalar las dependencias ejecutando los siguientes comandos en tu entorno:

```bash
pip install sentiment-analysis-spanish scikit-learn keras tensorflow
