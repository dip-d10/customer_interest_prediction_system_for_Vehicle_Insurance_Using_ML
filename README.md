# Vehicle Insurance Interest Prediction 

This project is an **end-to-end Machine Learning pipeline** that predicts whether a customer is interested in purchasing vehicle insurance based on customer demographics and vehicle-related information.

The goal is to help insurance companies identify potential customers and improve cross-selling efficiency.

>  **Project Status:** Currently in development stage.  
> Deployment and production hosting are yet to be completed.

---

## Problem Statement

Insurance companies often contact a large number of customers for vehicle insurance offers.

This model predicts:

- **Interested** → Customer is likely to buy vehicle insurance  
- **Not Interested** → Customer is unlikely to buy vehicle insurance  

This helps reduce unnecessary outreach and improves business decision-making.

---

## Tech Stack

- Python  
- Pandas  
- NumPy  
- Scikit-learn  
- MongoDB Atlas  
- AWS S3  
- Docker  
- GitHub Actions  

---

## Project Workflow

```bash
Data Ingestion
→ Data Validation
→ Data Transformation
→ Model Training
→ Model Evaluation
→ Prediction Pipeline
```

---

## Features

- Data ingestion from MongoDB Atlas  
- Data validation using schema checks  
- Feature engineering and transformation  
- Model training and evaluation  
- Best model storage in AWS S3  
- Prediction pipeline for new user data  
- CI/CD setup using Docker and GitHub Actions *(in progress)*  

---

## Project Structure

```bash
vehicle-insurance/
│
├── notebook/
├── src/
├── config/
├── pipeline/
├── app.py
├── requirements.txt
├── Dockerfile
└── .github/workflows/
```

---

## How to Run

```bash
git clone <your-repo-link>
cd vehicle-insurance

pip install -r requirements.txt

python app.py
```

---

## Future Improvements

- Complete deployment on AWS EC2  
- Add MLflow experiment tracking  
- Improve hyperparameter tuning  
- Add monitoring and retraining pipeline  

---

## Author

**Sumanta Jyoti**  
