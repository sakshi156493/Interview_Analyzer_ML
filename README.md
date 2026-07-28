# 🤖 AI Interview Analyzer

An AI-powered Interview Analyzer built using Machine Learning classification algorithms to predict interview outcomes based on candidate-related features. The project compares the performance of **Logistic Regression**, **Decision Tree**, and **Random Forest** models to identify the best-performing classifier.

---

## 📌 Project Overview

This project demonstrates an end-to-end Machine Learning workflow, including:

- Data preprocessing
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Model Training
- Model Evaluation
- Model Comparison
- Prediction on New Candidate Data

Three classification algorithms were implemented and evaluated:

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier

---

## 📂 Dataset

The project uses a CSV dataset containing candidate interview information.

The dataset includes features such as:

- Candidate Skills
- Experience
- Education
- Technical Knowledge
- Communication Score
- Aptitude Score
- Other Interview Parameters
- Final Interview Result (Target Variable)

---

## 🛠️ Technologies Used

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 📊 Machine Learning Workflow

1. Load Dataset
2. Data Cleaning
3. Handle Missing Values
4. Encode Categorical Features
5. Feature Selection
6. Train-Test Split
7. Train Multiple Models
8. Evaluate Performance
9. Compare Models
10. Predict Interview Outcome

---

# 📈 Model Performance

## Logistic Regression

Accuracy, Confusion Matrix, and Classification Report.

### Screenshot

![Logistic Regression](https://github.com/sakshi156493/Interview_Analyzer_ML/blob/main/Screenshot%202026-07-28%20103027.png)


---

## Decision Tree

Accuracy, Confusion Matrix, and Classification Report.

### Screenshot

![Decision Tree](https://github.com/sakshi156493/Interview_Analyzer_ML/blob/main/Screenshot%202026-07-28%20103101.png)

---

## Random Forest

Accuracy, Confusion Matrix, and Classification Report.

### Screenshot

![Random Forest](https://github.com/sakshi156493/Interview_Analyzer_ML/blob/main/Screenshot%202026-07-28%20103114.png)

---

# 🧪 Model Testing

Prediction using new candidate input.

### Screenshot

![Prediction](images/prediction.png)

---

# 📁 Project Structure

```
AI-Interview-Analyzer/
│
├── AI_Interview_Analyzer.ipynb
├── interview_dataset.csv
├── README.md
│
├── images/
│   ├── logistic_regression.png
│   ├── decision_tree.png
│   ├── random_forest.png
│   └── prediction.png
│
└── requirements.txt
```

---

# 🚀 How to Run

### 1. Clone Repository

```bash
git clone https://github.com/yourusername/AI-Interview-Analyzer.git
```

### 2. Open Project

```bash
cd AI-Interview-Analyzer
```

### 3. Install Dependencies

```bash
pip install -r requirements.txt
```

### 4. Run Notebook

Open:

```
AI_Interview_Analyzer.ipynb
```

using Jupyter Notebook.

---

# 📌 Results

- Compared three Machine Learning classification algorithms.
- Evaluated models using Accuracy, Precision, Recall, F1-Score, and Confusion Matrix.
- Random Forest achieved the highest overall performance on the dataset.
- Built a prediction system to classify interview outcomes for new candidate data.

---

# 🔮 Future Improvements

- Hyperparameter Tuning
- Cross Validation
- Feature Importance Analysis
- Deploy using Streamlit
- REST API Integration
- Real-time Prediction

---

# 👩‍💻 Author

**Sakshi More**

Computer Science and Engineering Graduate

Data Analyst | Machine Learning Enthusiast

---

⭐ If you found this project helpful, consider giving it a star!
