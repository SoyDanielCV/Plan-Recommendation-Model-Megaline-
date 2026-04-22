## 🇺🇸 English

### 📌 Project Description

Megaline aims to migrate customers from legacy plans to new offerings (**Smart** and **Ultra**).
This project builds a Machine Learning model to analyze user behavior and recommend the most suitable plan.

---

### 🎯 Goal

Predict whether a customer should choose:

* **Smart (0)**
* **Ultra (1)**

based on their monthly usage behavior.

---

### 📊 Dataset

Each record includes:

* 📞 **Calls** — number of calls
* ⏱ **Minutes** — total call duration
* 💬 **Messages** — number of texts
* 🌐 **MB Used** — mobile data usage
* 🎯 **Target:** `is_ultra`

---

### ⚙️ Methodology

#### 🔹 1. Data Preparation

* Feature/target split
* Dataset split (60/20/20)
* Feature scaling (StandardScaler)

#### 🔹 2. Model Training

Models evaluated:

* Logistic Regression
* Decision Tree
* Random Forest

#### 🔹 3. Evaluation

* Metric: **Accuracy**

---

### 📈 Results

| Model               | Validation Accuracy |
| ------------------- | ------------------- |
| Logistic Regression | 0.745               |
| Decision Tree       | 0.790               |
| Random Forest       | 0.790               |

✅ Final Model: **Random Forest**

* 🎯 Test Accuracy: **0.812**
* 🎲 Random Baseline: **0.521**

---

### 💡 Key Insights

* Usage behavior is highly predictive
* Ensemble models improve performance
* Model significantly outperforms random baseline

---

### 🚀 Business Impact

* Enables personalized plan recommendations
* Supports customer migration strategies
* Improves revenue through data-driven upselling

---

### 🛠️ Tech Stack

* Python
* Pandas
* NumPy
* Scikit-learn

# 📱 Plan Recommendation Model (Megaline)

---

## 🇪🇸 Español

### 📌 Descripción del Proyecto

Megaline busca migrar a sus clientes desde planes heredados hacia nuevas opciones (**Smart** y **Ultra**).
Este proyecto desarrolla un modelo de Machine Learning capaz de analizar el comportamiento de los usuarios y recomendar el plan más adecuado.

---

### 🎯 Objetivo

Predecir si un cliente debería optar por el plan:

* **Smart (0)**
* **Ultra (1)**

basándose en su comportamiento mensual.

---

### 📊 Dataset

Cada registro contiene información de uso del cliente:

* 📞 **Calls** — número de llamadas
* ⏱ **Minutes** — duración total de llamadas
* 💬 **Messages** — número de SMS
* 🌐 **MB Used** — datos móviles consumidos
* 🎯 **Target:** `is_ultra` (1 = Ultra, 0 = Smart)

---

### ⚙️ Metodología

#### 🔹 1. Preparación de datos

* Separación de variables (X, y)
* División del dataset:

  * Entrenamiento (60%)
  * Validación (20%)
  * Prueba (20%)
* Escalado con `StandardScaler` (para modelos lineales)

#### 🔹 2. Entrenamiento de modelos

Se evaluaron distintos algoritmos:

* Logistic Regression
* Decision Tree (optimización de `max_depth`)
* Random Forest (optimización de `n_estimators` y `max_depth`)

#### 🔹 3. Evaluación

Métrica principal utilizada:

* **Accuracy**

---

### 📈 Resultados

| Modelo              | Accuracy (Validación) |
| ------------------- | --------------------- |
| Logistic Regression | 0.745                 |
| Decision Tree       | 0.790                 |
| Random Forest       | 0.790                 |

✅ **Modelo final seleccionado: Random Forest**

* 🎯 Accuracy en test: **0.812**
* 🎲 Baseline aleatorio: **0.521**

---

### 💡 Insights Clave

* El comportamiento de uso (llamadas, mensajes y datos) es altamente predictivo
* Los modelos ensemble como Random Forest mejoran la generalización
* El modelo supera significativamente un baseline aleatorio

---

### 🚀 Impacto de Negocio

Este modelo permite:

* 📊 Recomendar planes personalizados
* 🔄 Migrar clientes desde planes antiguos
* 💰 Incrementar ingresos mediante upselling
* 😊 Mejorar la experiencia del usuario

---

### 🛠️ Tech Stack

* Python
* Pandas
* NumPy
* Scikit-learn

---



