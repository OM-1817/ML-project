# 🎓 Student Performance Prediction

An end-to-end Machine Learning web application that predicts a student's **Math Score** based on demographic, educational, and academic factors.

The project follows a complete ML lifecycle including data analysis, preprocessing, model training, hyperparameter tuning, model serialization, real-time inference, and cloud deployment.

---

## 🚀 Features

- Exploratory Data Analysis (EDA)
- Data Ingestion Pipeline
- Data Transformation Pipeline
- Hyperparameter Tuning using GridSearchCV
- Multiple Regression Model Evaluation
- Model Serialization using Pickle
- Custom Prediction Pipeline
- Flask Web Application
- Custom Logging & Exception Handling
- Dockerized Application
- AWS Deployment using ECR and EC2

---

## 🛠️ Tech Stack

### Machine Learning
- Python
- Pandas
- NumPy
- Scikit-Learn
- XGBoost
- CatBoost

### Backend
- Flask

### Deployment
- Docker
- AWS ECR (Elastic Container Registry)
- AWS EC2

---

## 📂 Project Structure

```text
├── artifacts/
│
├── notebook/
│   ├── 1. EDA STUDENT PERFORMANCE.ipynb
│   └── 2. MODEL TRAINING.ipynb
│
├── src/
│   ├── components/
│   │   ├── data_ingestion.py
│   │   ├── data_transformation.py
│   │   └── model_trainer.py
│   │
│   ├── pipeline/
│   │   └── predict_pipeline.py
│   │
│   ├── exception.py
│   ├── logger.py
│   └── utils.py
│
├── templates/
│
├── app.py
├── setup.py
├── requirements.txt
└── README.md
```

## 🔄 Machine Learning Workflow

```text
Dataset
   ↓
EDA
   ↓
Data Ingestion
   ↓
Data Transformation
   ↓
Model Training
   ↓
Hyperparameter Tuning
   ↓
Best Model Selection
   ↓
Model Serialization
   ↓
Prediction Pipeline
   ↓
Flask Application
```

---

## 🤖 Models Evaluated

- Linear Regression
- Decision Tree Regressor
- Random Forest Regressor
- Gradient Boosting Regressor
- AdaBoost Regressor
- XGBoost Regressor
- CatBoost Regressor

The best-performing model is automatically selected using **GridSearchCV** and saved for inference.

---

## 📊 Input Features

The model predicts **Math Score** using:

- Gender
- Race / Ethnicity
- Parental Level of Education
- Lunch Type
- Test Preparation Course
- Reading Score
- Writing Score

---

## 🌐 Web Application

The Flask application allows users to:

- Enter student details through a simple web interface
- Generate real-time predictions
- View predicted Math Scores instantly

---

## ☁️ Deployment

The application has been containerized using **Docker** and deployed on **AWS Cloud** using:

- Amazon Elastic Container Registry (ECR)
- Amazon EC2

This deployment approach ensures portability, scalability, and reproducibility of the machine learning application.

---

## 🔮 Future Improvements

- CI/CD with GitHub Actions
- Model Monitoring
- MLflow Integration
- Kubernetes Deployment
- Automated Model Retraining
- User Authentication
- Prediction History Tracking

---

## 👨‍💻 Author

**Om Vaghani**

Computer Science Engineering Student

AI | Machine Learning | Deep Learning | Natural Language Processing