# 🫀 Heart Disease Prediction using Machine Learning

This project is a solution for a **Kaggle Machine Learning Competition** focused on predicting heart disease using patient health data.

*📌 Competition: Playground Series S6E2
*📌 Platform: Kaggle
*📌 Problem Type: Binary Classification
*📌 Evaluation Metric: ROC-AUC Score

The objective is to build machine learning models that predict whether a patient has heart disease based on medical and demographic features.

---

# 🧠 Competition Objective

The goal of this Kaggle competition is to:

* Predict the probability of heart disease in patients
* Train and compare machine learning models
* Optimize performance using ROC-AUC score
* Generate a submission file for Kaggle evaluation

---

# ⚙️ Machine Learning Models Used

This project implements and compares two powerful ML models:

## 1. Random Forest Classifier

* Ensemble learning algorithm
* Strong baseline model
* Handles non-linear relationships well

## 2. LightGBM Classifier

* Gradient Boosting framework
* Faster and more efficient
* Higher accuracy on structured datasets
* Selected as best model based on ROC-AUC score

---

# 📊 Dataset Description

The dataset contains medical attributes such as:

| Feature        | Description              |
| -------------- | ------------------------ |
| Age            | Age of patient           |
| Sex            | Gender                   |
| ChestPainType  | Chest pain category      |
| RestingBP      | Resting blood pressure   |
| Cholesterol    | Cholesterol level        |
| FastingBS      | Fasting blood sugar      |
| RestingECG     | ECG results              |
| MaxHR          | Maximum heart rate       |
| ExerciseAngina | Exercise-induced angina  |
| Oldpeak        | ST depression            |
| ST_Slope       | ST segment slope         |
| HeartDisease   | Target variable (0 or 1) |

---

# 🔄 Project Workflow

## 1. Load Data

* Load train.csv and test.csv using Pandas

## 2. Data Preprocessing

* Separate features and target
* Handle categorical variables

## 3. Feature Encoding

* Apply one-hot encoding

## 4. Train-Test Split

* Split data into training and validation sets

## 5. Train Models

* Train Random Forest model
* Train LightGBM model

## 6. Model Evaluation

* Evaluate using ROC-AUC score
* Compare both models

## 7. Best Model Selection

* Automatically select best-performing model

## 8. Final Training

* Train best model on full dataset

## 9. Prediction

* Generate predictions on test dataset

## 10. Submission File Creation

* Create submission.csv file for Kaggle submission

---

# 📈 Evaluation Metric

Competition Metric: **ROC-AUC Score**

| Score Range | Performance     |
| ----------- | --------------- |
| 0.50        | Random guessing |
| 0.70–0.85   | Good            |
| 0.85–0.92   | Very Good       |
| 0.92–0.95   | Excellent       |

Expected Results:

| Model         | ROC-AUC     |
| ------------- | ----------- |
| Random Forest | 0.88 – 0.91 |
| LightGBM      | 0.91 – 0.95 |

---

# 🛠 Installation

Clone repository:

```bash
git clone https://github.com/yourusername/heart-disease-prediction.git
cd heart-disease-prediction
```

Install dependencies:

```bash
pip install pandas numpy scikit-learn lightgbm
```

---

# ▶️ Usage

Run the training script:

```bash
python train.py
```

Output:

* Model comparison results
* Best model selection
* submission.csv file ready for Kaggle upload

---

# 📁 Project Structure

```
heart-disease-prediction/
│
├── train.csv
├── test.csv
├── sample_submission.csv
│
├── train.py
├── submission.csv
├── README.md
│
└── requirements.txt
```

---

# 📤 Kaggle Submission

After running the script, upload the generated:

```
submission.csv
```

to the Kaggle competition page for scoring.

---

# 🚀 Features

✔ Kaggle competition solution
✔ LightGBM implementation
✔ Random Forest implementation
✔ Automatic best model selection
✔ ROC-AUC evaluation
✔ Submission file generation
✔ Clean and production-ready code

---

# 🔮 Future Improvements

* Cross-validation
* Hyperparameter tuning
* Feature engineering
* Model ensembling
* Feature importance visualization

---

# 👨‍💻 Author

Your Name
Final Year Engineering Student
Data Science and Machine Learning Enthusiast

---

# ⭐ If you found this useful, please star the repository!
