# Diabetes Prediction using Support Vector Machine (SVM)

## 📌 Project Overview
This project implements a **Diabetes Prediction Model** using **Support Vector Machine (SVM)**. The model classifies whether a person is diabetic or not based on medical data. The dataset used is the **Pima Indians Diabetes Dataset**, which contains diagnostic measurements.

## 📂 Dataset
- **Source**: Pima Indians Diabetes Dataset
- **Features**:
  - Pregnancies
  - Glucose Level
  - Blood Pressure
  - Skin Thickness
  - Insulin Level
  - BMI (Body Mass Index)
  - Diabetes Pedigree Function
  - Age
- **Target**: Diabetic (1) or Non-Diabetic (0)

## 🛠️ Technologies Used
- **Programming Language**: Python
- **Libraries**:
  - `numpy` (Numerical computations)
  - `pandas` (Data manipulation)
  - `matplotlib` & `seaborn` (Data visualization)
  - `scikit-learn` (Machine Learning algorithms)

## 🔥 Implementation Steps
1. **Load Dataset**: Read the dataset using Pandas.
2. **Data Preprocessing**:
   - Handle missing values (if any).
   - Standardize numerical features.
3. **Train-Test Split**: Divide data into training and testing sets.
4. **Apply SVM Model**: Train the **Support Vector Machine (SVM)** model.
5. **Evaluation**:
   - Accuracy Score
   - Confusion Matrix
   - Classification Report
   - ROC Curve
6. **Prediction**: Test the model on new input values.

## 📊 Results & Visualization
- **Confusion Matrix**: To visualize classification performance.
- **Accuracy Score**: Model's performance percentage.
- **ROC Curve**: Model's ability to distinguish between diabetic and non-diabetic.

## 🛡️ Model Performance
- **Accuracy**: 79% (Varies based on dataset split)
- **Precision & Recall**: Evaluated using classification report.
- **AUC-ROC Score**: Measures the model's ability to separate classes.

## 📌 Future Improvements
- **Hyperparameter Tuning**: Optimize the SVM kernel and parameters.
- **Feature Engineering**: Identify important features for better predictions.
- **Deep Learning Approach**: Use Neural Networks for enhanced accuracy.

## Dataset
The dataset used for this project can be found [here](https://colab.research.google.com/drive/1azJjE2Zzi10Wuu8mavmxh9LFQiAuxjH2?usp=sharing).
