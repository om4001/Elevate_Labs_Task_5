# Elevate_Labs_Task_5

### 📄 `README.md`

````markdown
# 🫀 Heart Disease Classification with Decision Tree and Random Forest

This project applies supervised machine learning algorithms — **Decision Tree** and **Random Forest** — to classify the presence of heart disease based on patient health data.

## 📌 Dataset

The dataset used is `heart.csv`, which includes the following features:

- Age, Sex, Chest Pain type (cp)
- Resting blood pressure (trestbps)
- Serum cholesterol (chol)
- Fasting blood sugar (fbs), Resting ECG results (restecg)
- Max heart rate achieved (thalach), Exercise induced angina (exang)
- Oldpeak, slope, ca, thal

Target:
- `target`: 1 indicates heart disease, 0 indicates no disease.

## 🔍 Project Tasks

1. **Train a Decision Tree Classifier**
2. **Visualize the Decision Tree**
3. **Analyze overfitting and control tree depth**
4. **Train a Random Forest and compare accuracy**
5. **Interpret feature importances**
6. **Evaluate using cross-validation**

## 🚀 Getting Started

### Clone the Repository

```bash
git clone https://github.com/yourusername/heart-disease-classification.git
cd heart-disease-classification
````

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run the Project

```bash
python heart_classification.py
```

## 📊 Outputs

* A full visual plot of the Decision Tree
* Accuracy metrics for both Decision Tree and Random Forest models
* Comparison of overfitting (via limited tree depth)
* Feature importance plot from the Random Forest
* 5-fold Cross-Validation score for Random Forest

## 📈 Feature Importance Example

![Feature Importances](feature_importances.png) *(generate and save this plot if you wish to include it)*

## 🧠 Evaluation Metrics

* **Accuracy**
* **Cross-Validation Accuracy**
* **Feature Importance Rankings**

## 📂 Project Structure

```
.
├── heart_classification.py
├── heart.csv
├── requirements.txt
└── README.md
```

## 🧪 Requirements

Install using:

```bash
pip install -r requirements.txt
```

Contents of `requirements.txt`:

```
pandas
matplotlib
scikit-learn
```

## 📜 License

This project is open-source and available under the [MIT License](LICENSE).

---

👨‍💻 *Contributions, suggestions, and improvements are welcome!*

```
