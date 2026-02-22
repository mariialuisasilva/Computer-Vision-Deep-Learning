# Computer-Vision-Deep-Learning 👁️🤖

Este repositorio contiene una serie de proyectos desarrollados durante el **Máster en Ingeniería Informática (Universidad de Huelva)**, enfocados en la resolución de problemas de visión por computador mediante arquitecturas avanzadas de **Deep Learning**.

Se exploran desde redes neuronales densas hasta el uso de **Transfer Learning** con modelos pre-entrenados de última generación.

---

## Contenido del repositorio 📁

### 1. Clasificación de imágenes (Fashion-MNIST) - Redes densas
Comparativa de diferentes configuraciones de redes neuronales densamente conectadas (MLP).
* **Hito:** Evaluación del impacto del número de capas y neuronas en la convergencia del modelo.

### 2. Redes Neuronales Convolucionales (CNN) desde cero
Implementación de arquitecturas CNN personalizadas para mejorar la extracción de características espaciales.
* **Resultado:** Se logró romper la barrera del 90% de accuracy, superando ampliamente a las redes densas.
* **Modelos:** CNN Simple vs. CNN Profunda con múltiples bloques convolucionales.

### 3. Transfer Learning y Data Augmentation (reconocimiento facial)
Uso de modelos pre-entrenados para la clasificación de expresiones faciales (Dataset FER-2013).
* **Técnicas:** Fine-tuning y Extracción de Características utilizando **VGGFace**.
* **Optimización:** Implementación de `ImageDataGenerator` para aumentar la robustez del modelo frente a ruido y falta de datos.

---

## Comparativa de rendimiento 📊

| Modelo | Arquitectura | Accuracy (Test) | Nota Técnica |
| :--- | :--- | :--- | :--- |
| Red densa (MLP) | 512-256-128 | 89.34% | Límite de redes densas |
| **CNN profunda** | **3 bloques conv + 256N** | **92.87%** | **Mejor rendimiento propio** |
| Transfer Learning| VGGFace (Fine-tuning)| 62.26% | Éxito en dataset ruidoso (FER) |

---

## Tecnologías y librerías 🛠️

* **Python 3**
* **TensorFlow / Keras**
* **OpenCV:** Procesamiento de imagen.
* **Scikit-learn:** Métricas de evaluación (F1-Score, Confusion Matrix).
* **Matplotlib / Seaborn:** Visualización de resultados y curvas de aprendizaje.

---

## Estructura de archivos 📂

Cada proyecto incluye su correspondiente **notebook (.ipynb)** con el código de entrenamiento y una **memoria técnica (PDF)** con el análisis detallado de los experimentos y conclusiones.

---
*Proyectos realizados en la asignatura de Computación Inteligente - Máster en Ingeniería Informática (UHU).*
