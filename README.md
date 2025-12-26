# ❤️ Heart Disease Prediction – Exploratory Data Analysis & Modeling

This project focuses on **exploratory data analysis (EDA)** and **machine learning–based prediction of heart disease** using the UCI Heart Disease dataset.
The goal is to understand key medical features, visualize their distributions, and build a foundation for predictive modeling.

---

## 📁 Project Structure

```
├── heart_disease_uci.csv              # Dataset used for analysis
├── HeartDiseasePrediction_Technohacks.ipynb   # Jupyter notebook with EDA & modeling
├── featuresplot.png                   # Feature distribution visualizations
└── README.md                          # Project documentation
```

---

## 📊 Dataset Description

The dataset contains **clinical and demographic attributes** collected from patients to assess the presence of heart disease.

### Key Features Visualized

* **age** – Age of the patient (years)
* **trestbps** – Resting blood pressure (mm Hg)
* **chol** – Serum cholesterol (mg/dl)
* **thalch** – Maximum heart rate achieved
* **oldpeak** – ST depression induced by exercise relative to rest
* **ca** – Number of major vessels colored by fluoroscopy
* **num** – Target variable

  * `0` → No heart disease
  * `1` → Presence of heart disease

---

## 📈 Exploratory Data Analysis (EDA)

The `featuresplot.png` file shows histograms of key numerical features:

### Observations

* **Age** is concentrated between **40–65 years**, indicating a middle-aged to older population.
* **Resting blood pressure (trestbps)** clusters around **110–140 mm Hg**, with some high outliers.
* **Cholesterol (chol)** shows a **right-skewed distribution**, suggesting presence of extreme values.
* **Maximum heart rate (thalch)** peaks around **140–170 bpm**.
* **Oldpeak** is heavily skewed toward **lower values**, meaning most patients have minimal ST depression.
* **ca** is discrete and imbalanced, with most patients having **0 affected vessels**.
* **Target variable (num)** is relatively balanced, making it suitable for classification tasks.

---

## 🧠 Modeling Approach

The notebook includes:

* Data cleaning and preprocessing
* Feature selection and transformation
* Train-test splitting
* Machine learning models for heart disease prediction
* Model evaluation using accuracy and related metrics

*(Exact models and performance details can be found inside the notebook.)*

---

## 🛠️ Technologies Used

* **Python**
* **Pandas & NumPy** – Data manipulation
* **Matplotlib & Seaborn** – Data visualization
* **Scikit-learn** – Machine learning models and evaluation
* **Jupyter Notebook**

---

## 🚀 How to Run the Project

1. Clone the repository:

   ```bash
   git clone <repository-url>
   ```
2. Open the notebook:

   ```bash
   jupyter notebook HeartDiseasePrediction_Technohacks.ipynb
   ```
3. Run all cells to reproduce the analysis and results.

---

## 📌 Conclusion

This project demonstrates how **EDA and feature analysis** help uncover meaningful patterns in medical data and support effective **heart disease prediction models**.
It can be extended further by:

* Hyperparameter tuning
* Feature engineering
* Trying advanced models (XGBoost, Random Forests, etc.)

---
