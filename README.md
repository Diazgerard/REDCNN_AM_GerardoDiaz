# REDCNN_AM_GerardoDiaz

# 🍎 Clasificador de Frutas con CNN (Fruits 360)

Este proyecto utiliza una red neuronal convolucional (CNN) para clasificar imágenes de frutas usando el dataset Fruits 360. El modelo fue entrenado en Google Colab y puede identificar más de 130 tipos diferentes de frutas.

---

## 📚 Contenido

- [🔍 Descripción](#-descripción)
- [📁 Dataset](#-dataset)
- [🧠 Modelo CNN](#-modelo-cnn)
- [🚀 Instrucciones para ejecución](#-instrucciones-para-ejecución)
- [📈 Resultados](#-resultados)
- [📷 Predicciones](#-predicciones)
- [📎 Créditos](#-créditos)

---

## 🔍 Descripción

Este proyecto aplica una arquitectura CNN inspirada en VGG para resolver un problema de clasificación multiclase de imágenes. Se incluyen pasos desde la descarga del dataset hasta la evaluación con el conjunto de prueba y predicciones individuales.

---

## 📁 Dataset

Usamos el dataset [Fruits 360](https://www.kaggle.com/datasets/moltean/fruits), que contiene:

- Imágenes en `Training/` y `Test/`
- Más de 130 clases de frutas
- Imágenes de 100x100 píxeles

---

## 🧠 Modelo CNN

- 2 bloques de convolución + max pooling
- Capas `Dropout` para evitar overfitting
- Capa `Dense` final con softmax para clasificación multiclase
- Optimización con Adam

---

## 🚀 Instrucciones para ejecución

### 1. Abrir en Google Colab

Abre el archivo `fruits_classifier.ipynb` en [Google Colab](https://colab.research.google.com/).

### 2. Subir tu archivo `kaggle.json`

Obténlo en [kaggle.com/settings](https://www.kaggle.com/settings) y súbelo para descargar el dataset automáticamente.

### 3. Ejecutar las celdas paso a paso

El notebook está organizado en:

- Paso 1: Preparar entorno y dataset
- Paso 2: Preprocesamiento con `ImageDataGenerator`
- Paso 3: Definir la red CNN
- Paso 4: Entrenar el modelo
- Paso 5: Visualizar resultados
- Paso 6: Evaluar con datos de prueba
- Paso 7: Hacer predicciones individuales

---
