# 🎓 Student Placement Prediction using Logistic Regression

## 📌 Overview

This project is an End-to-End Machine Learning Classification project that predicts whether a student is likely to get placed based on two important factors:

- CGPA
- IQ Score

The model is built using **Logistic Regression** and trained on a placement dataset using Python and Scikit-learn.

---

## 🚀 Features

- Data Loading using Pandas
- Data Preprocessing
- Exploratory Data Analysis (EDA)
- Feature Selection
- Logistic Regression Model Training
- Model Evaluation
- Model Serialization using Pickle
- Predict Placement Status (Placed / Not Placed)

---

## 🛠️ Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- Pickle
- Jupyter Notebook

---

## 📂 Project Structure

```
Placement-project-logistic-regression/
│
├── End to End_ml.ipynb        # Complete ML workflow
├── placement.csv              # Dataset
├── model.pkl                  # Trained Logistic Regression model
└── README.md
```

---

## 📊 Dataset Information

The dataset contains **100 student records** with the following features:

| Feature | Description |
|----------|-------------|
| CGPA | Student's CGPA |
| IQ | IQ Score |
| Placement | Target Variable (0 = Not Placed, 1 = Placed) |

Target Variable:

- **0 → Not Placed**
- **1 → Placed**

---

## 🤖 Machine Learning Workflow

1. Import Libraries
2. Load Dataset
3. Data Exploration
4. Data Cleaning
5. Feature Selection
6. Train-Test Split
7. Model Training
8. Model Evaluation
9. Save Model using Pickle

---

## 📈 Algorithm Used

**Logistic Regression**

Logistic Regression is a supervised machine learning algorithm used for binary classification problems. It predicts the probability of a student being placed based on the input features (CGPA and IQ).:contentReference[oaicite:1]{index=1}

---

## ▶️ How to Run the Project

### Clone the repository

```bash
git clone https://github.com/Himanshukrsahu/Placement-project-logistic--regression.git
```

### Navigate to the project

```bash
cd Placement-project-logistic--regression
```

### Install required libraries

```bash
pip install numpy pandas matplotlib scikit-learn
```

### Open Jupyter Notebook

```bash
jupyter notebook
```

Open:

```
End to End_ml.ipynb
```

Run all the cells sequentially.

---

## 📌 Model Output

The trained model predicts:

- **Placed**
- **Not Placed**

based on the student's:

- CGPA
- IQ Score

---

## 🔮 Future Improvements

- Build a Flask Web Application
- Deploy using Render or Railway
- Add HTML/CSS Frontend
- Add Streamlit Dashboard
- Improve model accuracy with additional features
- Compare Logistic Regression with other classification algorithms

---

## 📚 Learning Outcomes

Through this project, I learned:

- Data preprocessing
- Data visualization
- Binary classification
- Logistic Regression
- Model evaluation
- Model serialization using Pickle
- End-to-End Machine Learning workflow

---

## 👨‍💻 Author

**Himanshu Kumar**

- GitHub: https://github.com/Himanshukrsahu
- LinkedIn: https://www.linkedin.com/in/himanshu-kumar-bb7a3736a/

---

## ⭐ If you found this project helpful

Please consider giving it a ⭐ on GitHub.