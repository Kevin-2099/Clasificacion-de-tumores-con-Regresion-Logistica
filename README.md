# Clasificacion-de-tumores-con-Regresion-Logistica
Este proyecto aplica un modelo de Regresión Logística para predecir si un tumor es maligno o benigno utilizando el conocido Breast Cancer Wisconsin Dataset.

## 📊 Descripción del Problema
El diagnóstico temprano de tumores es fundamental en la lucha contra el cáncer. En este proyecto, se utiliza un conjunto de datos real con características extraídas de imágenes de núcleos celulares para entrenar un modelo que clasifique los tumores en:

0 → Tumor Maligno

1 → Tumor Benigno

## 🗃 Dataset
Dataset: Breast Cancer Wisconsin

Fuente: Incluido directamente en scikit-learn

Tamaño: 569 muestras, 30 características numéricas

Clases:

212 malignos

357 benignos

## 🛠 Tecnologías Utilizadas
Python 3

Pandas

NumPy

Scikit-learn

Matplotlib

Seaborn

## ⚙️ Pasos del Proyecto
Carga y exploración de datos

División en conjuntos de entrenamiento y prueba

Estandarización de características

Entrenamiento del modelo de Regresión Logística

Evaluación mediante precisión, matriz de confusión y reporte de clasificación

Visualización de resultados

## 📈 Resultados
Precisión obtenida: alrededor de 95%, dependiendo de la semilla aleatoria.

Buen equilibrio entre precisión, recall y F1-score, lo que indica un modelo fiable para clasificación binaria en este caso.

Ejemplo de matriz de confusión:
Predicho Maligno	Predicho Benigno
Real Maligno	40	3
Real Benigno	2	69

## 🚀 Ejecución
Puedes ejecutar el proyecto fácilmente en Google Colab o localmente en Jupyter Notebook. Solo necesitas tener instaladas las librerías mencionadas.
