# Sentiment Analysis with BERT Transformers 🗣️

Este repositorio contiene dos etapas del proyecto: Entrenamiento del modelo y Pruebas de Inferencia.

| Notebook | Visualizar en Colab (Recomendado) |
|----------|-----------------------------------|
| **1. Entrenamiento (Training)** | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/BGIA1/sentiment-analysis-bert-transformers/blob/main/bert_model_training.ipynb) |
| **2. Inferencia (Inference)** | [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/BGIA1/sentiment-analysis-bert-transformers/blob/main/sentiment_classification_inference.ipynb) |

---

## 📋 Descripción del Proyecto

Clasificación semántica de reseñas de películas (IMDB) utilizando el estado del arte en Procesamiento de Lenguaje Natural (NLP). Este proyecto implementa **Deep Learning** y **Transfer Learning** mediante el modelo **BERT** para entender el contexto y matices del lenguaje humano mejor que los modelos tradicionales.

## 🛠️ Tecnologías Clave

* **Deep Learning:** PyTorch / TensorFlow, Transformers (Hugging Face).
* **NLP:** Tokenization (BERT Base Uncased), Word Embeddings.
* **Hardware:** Aceleración por GPU.

## ⚙️ Metodología

1. **Tokenización:** Procesamiento de texto crudo para adaptarlo a la entrada de BERT (CLS/SEP tokens, padding).
2. **Embeddings:** Extracción de representaciones vectoriales densas utilizando un modelo BERT pre-entrenado.
3. **Entrenamiento:** Clasificador (Regresión Logística/NN) entrenado sobre los embeddings para distinguir entre reseñas positivas y negativas.
4. **Inferencia:** Pruebas con textos inéditos para validar la generalización.

## 📊 Resultados

El uso de BERT permitió capturar sarcasmo y dobles negaciones, superando significativamente a los enfoques basados en frecuencia de palabras (TF-IDF).

## 📁 Disponibilidad de los Datos

Este proyecto utiliza un subconjunto del dataset público **IMDB Movie Review Dataset**.

> 💡 **Nota de Visualización:** GitHub a menudo tiene problemas renderizando notebooks complejos. Por favor, usa los botones de **"Open in Colab"** de la tabla superior para ver el código y las gráficas correctamente.
