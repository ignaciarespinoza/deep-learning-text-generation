# deep-learning-text-generation
Experimentos de generación de texto con redes recurrentes y Transformers usando Python, TensorFlow/Keras y procesamiento de lenguaje natural.


# Deep Learning para generación de texto

Este repositorio reúne dos notebooks desarrollados para una evaluación de Deep Learning enfocada en procesamiento de lenguaje natural.

## Contenido

### 01. Generación de texto con RNN/LSTM usando Don Quijote de la Mancha

Modelo de lenguaje a nivel de caracteres entrenado con *Don Quijote de la Mancha*. Se implementan y comparan modelos LSTM, GRU, LSTM apilada, embeddings, distintos valores de `SEQ_LENGTH`, generación con distintas temperaturas y un modelo secuencia a secuencia. También se incluye un experimento con textos teatrales de Calderón de la Barca.

### 02. Modelo Transformer Encoder-Decoder para generación de respuestas

Implementación de un modelo Transformer encoder-decoder para generación de respuestas en diálogos. El notebook incluye carga y preparación de datos, tokenización, entrenamiento y generación de respuestas.

## Tecnologías utilizadas

- Python
- TensorFlow / Keras
- NumPy
- Pandas
- Matplotlib
- Procesamiento de Lenguaje Natural
- Redes recurrentes
- Transformers

## Objetivo

El objetivo del repositorio es experimentar con distintas arquitecturas de Deep Learning aplicadas a generación de texto, comparando modelos recurrentes y modelos basados en atención.
