# Heart Disease Classification using Machine Learning

##  Project Overview
This project predicts the presence of **heart disease** in patients using machine learning techniques. It involves **data preprocessing, feature engineering, model training, and evaluation** to classify whether a patient is at risk of heart disease or not.

 using-Decision Tree,
       Random Forest,
       AdaBoost
       
##  Objective
The main goal of this project is to:
- Analyze a heart disease dataset.
- Apply classification algorithms to predict heart disease.
- Evaluate model performance using appropriate metrics.

---

##  Dataset
- **Source**: [UCI Heart Disease Dataset](https://www.kaggle.com/datasets/johnsmith88/heart-disease-dataset)
- **Description**: The dataset contains patient medical details like age, gender, blood pressure, cholesterol level, and more.

### **Features**
- `age`: Age of the patient
- `sex`: Gender (1 = male, 0 = female)
- `cp`: Chest pain type (0-3)
- `trestbps`: Resting blood pressure
- `chol`: Serum cholesterol (mg/dl)
- `fbs`: Fasting blood sugar > 120 mg/dl (1 = true, 0 = false)
- `restecg`: Resting electrocardiographic results (0-2)
- `thalach`: Maximum heart rate achieved
- `exang`: Exercise-induced angina (1 = yes, 0 = no)
- `oldpeak`: ST depression induced by exercise relative to rest
- `slope`: Slope of the peak exercise ST segment
- `ca`: Number of major vessels (0-3) colored by fluoroscopy
- `thal`: Thalassemia (3 = normal, 6 = fixed defect, 7 = reversible defect)

### **Target**
- `target`: Presence of heart disease (1 = disease, 0 = no disease)

---

##  Tools & Libraries
- **Python**: 3.x
- **Libraries**:
  - `numpy`, `pandas` (Data manipulation)
  - `matplotlib`, `seaborn` (Visualization)
  - `scikit-learn` (ML models and metrics)

---

##  Project Workflow
1. **Data Loading & Exploration**:
   - Load dataset and check for missing values.
   - Perform statistical analysis and visualize feature distributions.
   
2. **Data Preprocessing**:
   - Handle missing values.
   - Encode categorical variables.
   - Normalize/standardize numerical features.

3. **Model Building**:
   - Train multiple models such as:
     - Decision Tree
     - Random Forest
     - AdaBoost
   - Compare performance using metrics.

4. **Model Evaluation**:
   - Accuracy
   - Confusion Matrix
   - Precision, Recall, F1-score

---

##  Results
- Best model achieved an **accuracy of 100%**.
- DecisionTree
- Random Forest

---

## How to Run
 Clone the repository:
   ```bash
   git clone https://github.com/Nirmalan8/Heart-Disease-Classification.git
   cd Heart-Disease-Classification
---
Run the notebook:
jupyter notebook Heart-Disease-Classification-using-ML.ipynb

---
Future Improvements

- Implement advanced models (XGBoost, LightGBM).

- Hyperparameter tuning for better accuracy.

- Deploy model using Streamlit or Flask.
---
