# Productionization of ML Systems – Voyage Analytics Integrating MLOps in Travel

## About the Project

This repository contains the work completed as part of a Travel Analytics and MLOps project. The goal was to build machine learning solutions for different travel-related use cases and understand how models can be moved from development to production.

The project includes three machine learning applications:

- Hotel Recommendation System
- Gender Classification using BERT
- Flight Price Prediction

Along with model development, the project also explores MLOps concepts such as Docker, CI/CD, MLflow, Airflow, Kubernetes, and deployment workflows.

---

## Projects Included

### Hotel Recommendation System

A recommendation system that suggests hotels based on user booking history and hotel information.

**What was done**
- Cleaned and preprocessed hotel booking data
- Built a Collaborative Filtering model using KNN
- Built a Content-Based Filtering model using TF-IDF
- Combined both approaches into a Hybrid Recommendation System
- Developed a simple Streamlit interface for recommendations

---

### Gender Classification using BERT

A Natural Language Processing project that predicts gender based on a person's name.

**What was done**
- Cleaned and prepared the dataset
- Fine-tuned a BERT model for classification
- Built a Flask API for predictions
- Containerized the application using Docker
- Explored deployment and automation workflows

---

### Flight Price Prediction

A machine learning model that predicts flight ticket prices based on flight details.

**What was done**
- Performed data cleaning and feature engineering
- Trained an XGBoost regression model
- Evaluated model performance
- Built a prediction interface
- Documented the deployment process

---

## Technologies Used

**Programming & ML**
- Python
- Pandas
- NumPy
- Scikit-Learn
- XGBoost
- PyTorch
- BERT

**Deployment & MLOps**
- Flask
- Streamlit
- Docker
- Kubernetes
- Apache Airflow
- MLflow
- Jenkins
- GitHub

---

## Repository Structure

```text
├── data/
│   └── travel_capstone.zip
│
├── app.py
├── model.pkl
├── company_encoder.pkl
│
├── Hotel_Recommendation_System.ipynb
├── Gender_Classification_Model.ipynb
├── flight_price_prediction_part.ipynb
│
├── Dockerfile.txt
├── requirements.txt
│
├── MLOps_Workflow_Guide.docx
└── README.md
```

---

## MLOps Workflow

As part of this project, I explored the complete lifecycle of deploying machine learning models.

Topics covered include:

- REST API development
- Streamlit applications
- Docker containerization
- Kubernetes deployment
- Apache Airflow scheduling
- CI/CD pipelines
- MLflow experiment tracking

A detailed explanation of these concepts is available in the **MLOps_Workflow_Guide.docx** document included in this repository.

---

## How to Run

Clone the repository:

```bash
git clone https://github.com/ravindramore98/Productionization-of-ML-Systems---Voyage-Analytics-Integrating-MLOps-in-Travel.git
```

Install dependencies:

```bash
pip install -r requirements.txt
```

Run the application:

```bash
python app.py
```

---

## Key Learnings

Through this project, I gained hands-on experience with:

- Recommendation Systems
- NLP using BERT
- Regression Models
- Model Deployment
- Docker
- CI/CD Concepts
- MLflow
- Airflow
- Kubernetes Basics
- MLOps Practices

---

## Author

**Ravindra More**

GitHub: https://github.com/ravindramore98

LinkedIn: https://www.linkedin.com/in/ravindramore031
