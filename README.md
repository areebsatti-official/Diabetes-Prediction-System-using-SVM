# Diabetes Prediction System (Machine Learning)

A Machine Learning project that predicts whether a person is diabetic or not using medical attributes such as glucose level, BMI, blood pressure, and age.

The model is trained using **Support Vector Machine (SVM)** and the dataset is preprocessed using **StandardScaler** to improve prediction performance.

---

## Project Overview

Diabetes is one of the most common chronic diseases worldwide. Early prediction can help in prevention and better medical care.

This project builds a **binary classification model** that predicts:

- **0 → Non-Diabetic**
- **1 → Diabetic**

The model is trained using the **PIMA Indians Diabetes Dataset**.

---

## Project Structure

```
Diabetes-Prediction-System
│
├── dataset/
│   └── diabetes.csv
│
├── model/
│   └── diabetes_model.pkl
│
├── notebook/
│   └── diabetes_prediction.ipynb
│
├── src/
│   └── diabetes_prediction_system.py
│
└── README.md
```

### Folder Description

**dataset/**  
Contains the dataset used to train the machine learning model.

**model/**  
Contains the trained machine learning model saved using pickle.

**notebook/**  
Contains the Jupyter Notebook used for experimentation, data analysis, and model training.

**src/**  
Contains the Python source code used to build and run the prediction system.

---

## Technologies Used

- Python  
- NumPy  
- Pandas  
- Scikit-learn  
- Jupyter Notebook  
- Google Colab  

---

## Machine Learning Workflow

The following steps were used to build this project:

1. Import dependencies
2. Load the dataset
3. Perform data analysis
4. Separate features and labels
5. Standardize the data
6. Split dataset into training and testing sets
7. Train the model using **Support Vector Machine (SVM)**
8. Evaluate model accuracy
9. Build a predictive system

---

## Model Details

**Algorithm Used**

Support Vector Machine (SVM)

**Kernel Used**

```
linear
```

**Libraries used from Scikit-learn**

- `StandardScaler`
- `train_test_split`
- `svm.SVC`
- `accuracy_score`

---

## Dataset Features

| Feature | Description |
|--------|-------------|
| Pregnancies | Number of pregnancies |
| Glucose | Plasma glucose concentration |
| BloodPressure | Diastolic blood pressure |
| SkinThickness | Skin fold thickness |
| Insulin | Serum insulin level |
| BMI | Body mass index |
| DiabetesPedigreeFunction | Diabetes genetic score |
| Age | Age of the patient |

Target Column:

```
Outcome
```

- **0 = Non Diabetic**
- **1 = Diabetic**

---

## Model Accuracy

Training Accuracy

```
~78% - 80%
```

Testing Accuracy

```
~75% - 78%
```

*(Accuracy may vary depending on dataset split)*

---

## How to Run the Project

### 1 Install Required Libraries

```bash
pip install numpy pandas scikit-learn
```

### 2 Clone the Repository

```bash
git clone https://github.com/yourusername/diabetes-prediction-system.git
```

### 3 Navigate to Project Directory

```bash
cd diabetes-prediction-system
```

### 4 Run the Python Script

```bash
python src/diabetes_prediction_system.py
```

---

## Example Prediction

Example Input

```
(2,197,70,45,543,30.5,0.158,53)
```

Output

```
The Person has Diabetes
```

or

```
Non Diabetes
```

---

## Future Improvements

Possible improvements for this project:

- Build a **Web Application (Flask or Streamlit)**
- Add **multiple ML algorithms for comparison**
- Improve accuracy using **feature engineering**
- Add **data visualization**
- Deploy the model on **cloud platforms**

---

## Author

**Muhammad Areeb Satti**

Software Engineering Student  
Interested in Machine Learning, Cybersecurity, and Software Development

---

## License

This project is open-source and available under the **MIT License**.
