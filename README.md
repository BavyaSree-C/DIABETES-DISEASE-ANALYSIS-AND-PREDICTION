# 🌟 **Diabetes Analysis and Prediction** 🌟

## 📂 Dataset: **PIMA Indian Diabetes Dataset**
The **PIMA Indian Diabetes Dataset** contains medical and demographic data to predict diabetes outcomes.

### 🔑 **Attributes:**
- **`Pregnancies`**: Number of times pregnant.
- **`Glucose`**: Plasma glucose concentration.
- **`BloodPressure`**: Diastolic blood pressure (mm Hg).
- **`SkinThickness`**: Triceps skin fold thickness (mm).
- **`Insulin`**: 2-Hour serum insulin (mu U/ml).
- **`BMI`**: Body mass index (weight in kg/(height in m)^2).
- **`DiabetesPedigreeFunction`**: Diabetes pedigree function (a measure of genetic influence).
- **`Age`**: Age in years.
- **`Outcome`**: 
  - `1` indicates diabetes.
  - `0` indicates no diabetes.

---

## 🛠 **Workflow**

### 1️⃣ **Data Preprocessing**
- ✅ Handled missing or zero values for attributes like **Glucose**, **BloodPressure**, **SkinThickness**, **Insulin**, and **BMI**.
- ✅ Applied **data normalization and scaling** for consistent input to machine learning models.
- ✅ Checked for **class imbalance** in the `Outcome` variable and applied techniques to address it.

---

### 2️⃣ **Exploratory Data Analysis (EDA)**
- 📊 Visualized feature distributions using **histograms** and **boxplots** to detect outliers.
- 🔍 Explored feature relationships with **heatmaps**, **scatter plots**, and **pair plots**.
- 🔗 Investigated **correlations** between features to identify potential redundancies.

---

### 3️⃣ **Modeling**
- 📂 **Split** the data into **training and testing sets** (e.g., 80/20 split).
- 🧠 Trained various machine learning models:
  - 🤖 **Logistic Regression**
  - 🌲 **Random Forest Classifier**
  - 💻 **Support Vector Machine (SVM)**
  - 👥 **K-Nearest Neighbors (KNN)**
  - 🌳 **Decision Tree**

---

### 4️⃣ **Evaluation**
- 📈 Models were evaluated using metrics like:
  - **Accuracy**
- 🧮 Generated **confusion matrices** for detailed performance analysis.

---

## 🏆 **Results**
- **Best Performing Model**:  
  🌟 **Random Forest Classifier** achieved the highest accuracy of **100%** .  

### 💡 **Insights:**
- 🩺 **Glucose** and **BMI** are the most significant predictors of diabetes.


---

## 📖 **Conclusion**
This project demonstrates a complete workflow for **predicting diabetes** using machine learning, from preprocessing and visualization to model training and evaluation.  

### 🚀 **Future Scope:**
- Experiment with **deep learning models** for enhanced accuracy.
- Explore additional features or datasets for better prediction capabilities.

---
