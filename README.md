# CNN-VGG16---Tomatoes-Dataset
listo aqui esta ahora mi tercer proyecto aqui te dejo mi realme # CNN-VGG16---Tomatoes-Dataset
# 🍅 Clasificación de Tomates mediante CNN (VGG16)

Este proyecto implementa una Red Neuronal Convolucional (CNN) basada en la arquitectura **VGG16** para clasificar imágenes de tomates en distintas categorías. Se utiliza **Transfer Learning** (aprendizaje por transferencia) con pesos preentrenados en ImageNet, adaptando y entrenando una nueva cabeza clasificadora para este conjunto de datos.

---

## 📌 Características Principales

* **Transfer Learning:** Uso del modelo base VGG16 preentrenado para aprovechar la extracción de características complejas.
* **Procesamiento de Imágenes:** Reescalado, normalización y preparación de imágenes de entrada.
* **Evaluación del Modelo:** Generación de métricas de precisión, matriz de confusión y curvas de entrenamiento/pérdida.
* **Entorno Cloud:** Implementado y optimizado para ejecutarse en la nube utilizando aceleración por GPU.

---

## 🛠️ Tecnologías y Herramientas

* **Entorno de Desarrollo:** Google Colab
* **Lenguaje:** Python
* **Framework de Deep Learning:** TensorFlow / Keras
* **Manipulación de Datos:** NumPy, Pandas
* **Visualización:** Matplotlib, Seaborn
* **Métricas y Evaluación:** Scikit-learn

---

## 📊 Dataset

El proyecto utiliza el **Tomatoes Dataset** alojado en Kaggle:

* **Fuente:** [Tomatoes Dataset - Kaggle](https://www.kaggle.com/?utm_source=gemini)
* **Contenido:** Imágenes clasificadas de tomates en diferentes estados/categorías.

---

## 📁 Estructura del Repositorio

```text
Clasificacion-Tomates-VGG16/
├── Clasificacion_de_tomates_VGG16.ipynb  # Notebook ejecutable de Google Colab
└── README.md                              # Documentación del proyecto

```

---

## 🚀 ¿Cómo ejecutar este proyecto?

### Opción 1: Directo en Google Colab (Recomendado)

1. Abre el archivo `.ipynb` de este repositorio.
2. Haz clic en el botón de **Open in Colab** (o súbelo manualmente a tu Google Drive).
3. Asegúrate de activar la GPU: `Entorno de ejecución` ➔ `Cambiar tipo de entorno de ejecución` ➔ seleccionar `GPU`.
4. Descarga el dataset desde Kaggle o conéctalo directamente a través de la API de Kaggle en la celda correspondiente.
5. Ejecuta todas las celdas secuencialmente.

### Opción 2: Localmente con Jupyter Notebook

1. **Clonar el repositorio:**
```bash
git clone https://github.com/tu-usuario/Clasificacion-Tomates-VGG16.git
cd Clasificacion-Tomates-VGG16

```


2. **Instalar dependencias necesarias:**
```bash
pip install tensorflow numpy matplotlib seaborn scikit-learn pandas

```


3. **Iniciar Jupyter Lab / Notebook:**
```bash
jupyter notebook

```
