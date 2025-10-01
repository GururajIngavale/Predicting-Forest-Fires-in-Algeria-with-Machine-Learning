<h1 align="center">🔥 Algerian Forest Fire Prediction Using Machine Learning</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Machine%20Learning-Random%20Forest%20%7C%20Gradient%20Boosting-brightgreen?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Python-3.9-blue?style=for-the-badge&logo=python" />
  <img src="https://img.shields.io/badge/Scikit--Learn-ML%20Models-orange?style=for-the-badge&logo=scikit-learn" />
</p>

<p align="center">
  <img src="https://upload.wikimedia.org/wikipedia/commons/5/55/Fire-animation.gif" width="200px" alt="Fire Animation"/>
</p>

---

## 🌍 Overview  

Forest fires are one of the most devastating natural disasters, causing environmental destruction, loss of biodiversity, and economic damage.  
This project leverages **Machine Learning** to predict the likelihood of forest fires based on weather conditions in the **Bejaia** and **Sidi Bel-Abbès** regions of Algeria (June–September 2012).  

---

## 📊 Dataset  

- **Source:** Algerian Forest Fires Dataset  
- **Size:** 244 weather records  
- **Features:** 11 weather & fire indices (Temperature, Relative Humidity, Wind Speed, Rainfall, Fire Weather Index components, etc.)  
- **Target Variable:**  
  - 🔥 Fire (138 instances)  
  - 🌱 No Fire (106 instances)  

---

## 🎯 Objective  

Predict the **probability of a forest fire** using multiple machine learning algorithms and compare their performance.  

---

## ⚙️ Methodology  

### 🧹 Data Preprocessing  
✔️ Handled missing values  
✔️ Normalized numerical attributes  
✔️ Encoded categorical variables (dates)  
✔️ Conducted Exploratory Data Analysis (EDA)  

### 🤖 Models Implemented  
- Logistic Regression  
- Ridge & Lasso Regression  
- Decision Trees / Random Forests  
- Support Vector Machine (SVM)  
- Gradient Boosting  

### 🔧 Model Optimization  
- Hyperparameter tuning with **GridSearchCV**  
- Applied **Cross-Validation**  
- Compared metrics: Accuracy, Precision, Recall, F1-score, ROC-AUC  

---

## 📈 Results  

| Model                     | Accuracy  |
|---------------------------|-----------|
| Logistic Regression        | ~70%      |
| Ridge / Lasso Regression   | Improved  |
| Random Forest / Gradient Boosting | **85–90%** ✅ |

🔥 **Key Predictors:** Temperature, Relative Humidity, Wind Speed, and FWI indices  

---

## 🚀 Getting Started  

### 1️⃣ Clone the Repository  

```bash
git clone https://github.com/yourusername/algerian-forest-fire-prediction.git
cd algerian-forest-fire-prediction
