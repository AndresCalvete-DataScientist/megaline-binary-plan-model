## 📞 Modelo predictivo para recomendación de planes en Megaline

### 📌 Introducción

Este proyecto fue desarrollado para Megaline, una empresa de telecomunicaciones interesada en mejorar su sistema de recomendación de productos. Utilizando datos reales de clientes, el objetivo es construir un modelo predictivo que recomiende a cada cliente uno de los dos planes disponibles, basándose en su comportamiento y características personales.

### Objetivo

El objetivo es analizar los datos de clientes de Megaline y desarrollar un modelo que permita predecir con alta precisión cuál de los dos planes es más adecuado para cada usuario. Esto implica tareas de preprocesamiento, análisis exploratorio, ingeniería de características y evaluación de modelos de clasificación supervisada.

---

### 🧠 Habilidades técnicas demostradas

Este proyecto demuestra competencias clave en ciencia de datos orientadas al aprendizaje automático y toma de decisiones comerciales. Entre las habilidades desarrolladas se encuentran:

- **Análisis exploratorio de datos (EDA)**: visualización de patrones y comportamiento por grupos.
- **Ingeniería de características**: transformación y creación de variables para mejorar el entendimiento de los datos.
- **Segmentación de datos**: en grupos de entrenamiento, validación y prueba para el modelo.
- **Modelado predictivo**: entrenamiento y evaluación de modelos de clasificación como `DecisionTreeClassifier`, `RandomForestClassifier` y `LogisticRegression`.
- **Evaluación de modelos**: uso de métricas como accuracy.
- **Optimización de hiperparámetros**: aplicación de bucles para mejorar el rendimiento del modelo.

---

### 🛠️ Tecnologías y herramientas utilizadas

- **Python**: lenguaje principal del proyecto.
- **pandas**: manipulación y análisis de datos.
- **seaborn**: visualización de datos.
- **scikit-learn**: entrenamiento, validación y evaluación de modelos de machine learning.
- **Métodos clave**: `.train_test_split()`, `.RandomForestClassifier()`, `.fit()`, `.predict()`, `.score()`, `.accuracy_score()`.

---

### ✅ Resultados y conclusiones

- Se logró construir un modelo predictivo con una exactitud del 80%.
- El modelo `RandomForestClassifier` resultó ser el más efectivo, superando a otros modelos como `DecisionTreeClassifier` y `LogisticRegression`.
- No se evidenciaron problemas de sobreajuste en los modelos evaluados.

---

### 📈 Posibles mejoras futuras

- Incorporar más variables relacionadas con satisfacción del cliente.
- Evaluar si un balanceo de clases podría mejorar la precisión del modelo.
- Implementar técnicas de validación cruzada para una evaluación más robusta del modelo.

---

### 👨‍💻 Autor

**Andrés Calvete**  
Científico de Datos Junior  
[LinkedIn](https://www.linkedin.com/in/andrescalvete/)  
ascalvete@hotmail.com
