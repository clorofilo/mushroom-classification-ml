# Clasificación de Setas Venenosas con Machine Learning

## 📌 Descripción
Este proyecto utiliza algoritmos de Machine Learning para clasificar setas en comestibles o venenosas basándose en sus características. Se trabaja con un conjunto de datos de setas que contiene diversas características como color, tamaño y forma.

## 🛠️ Tecnologías y Herramientas
- Python
- Jupyter Notebook
- Pandas
- NumPy
- Scikit-learn
- Matplotlib / Seaborn
- Graphviz
- Pickle
  
## 📂 Contenido del Repositorio

- `Clasificación_Setas.ipynb`: Notebook con el código para la carga de datos, preprocesamiento, entrenamiento del modelo y evaluación.
- `README.md`: Documento con información sobre el proyecto.
- `requirements.txt`: Lista de dependencias necesarias para ejecutar el proyecto.
- `knn_model.pkl`: Modelo entrenado utilizando el algoritmo K-Nearest Neighbors.
- `svm_model.pkl`: Modelo entrenado con Support Vector Machine (SVM).
- `random_forest_model.pkl`: Modelo entrenado con Random Forest.

### Estructura del repositorio
```
mushroom-classification-ml/
│── models/                        # Modelos entrenados
│   ├── knn_model.pkl
│   ├── svm_model.pkl
│   ├── random_forest_model.pkl
│
│── notebooks/                     # Jupyter Notebooks
│   ├── Clasificación_Setas.ipynb  # Notebook principal con el código
│
│── requirements.txt               # Dependencias del proyecto
│── README.md                      # Documentación del proyecto
```

## Instalación y Uso

1. Clona el repositorio:
   ```bash
   git clone https://github.com/tu_usuario/nombre_del_repositorio.git
   cd nombre_del_repositorio
   ```

2. Instala las dependencias necesarias:
   ```bash
   pip install -r requirements.txt
   ```

3. Ejecuta el notebook `Clasificación_Setas.ipynb` en Jupyter Notebook o Jupyter Lab.

## 📊 Dataset

El dataset utilizado en este proyecto proviene de [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/mushroom). Contiene características de setas, como:

- Color de la gorra
- Forma del pie
- Superficie de la gorra
- Olor
- Entre otras...

El objetivo es predecir si una seta es comestible (`e`) o venenosa (`p`).

## 🔎 Modelos Utilizados

Se han probado diversos modelos de clasificación, entre ellos:

- Árboles de decisión
- Random Forest
- SVM
- Naive Bayes
- KNN
- Regresión Logística

El mejor modelo se selecciona en función de métricas como la precisión y la matriz de confusión.

## 📈 Resultados

El mejor modelo obtenido fue un **SVM**  (kernel = RBF, C = 10), logrando los siguientes resultados:

- **Precisión (Precision)**: 1.00 (para clase "e"), 0.99 (para clase "p")
- **Recall**: 0.99 (para clase "e"), 1.00 (para clase "p")
- **F1-score**: 1.00 (para ambas clases)
- **Accuracy**: 99.74%

Estos resultados muestran una alta precisión en la clasificación de setas, lo que indica que el modelo es confiable para la tarea.

## 📜 Licencia
Este proyecto está bajo la licencia MIT.

## Contribución

Si deseas contribuir a este proyecto, puedes hacer un fork y enviar un pull request con mejoras o nuevas funcionalidades.



