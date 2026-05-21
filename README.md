# 🚗 Vehicle Insurance MLOps Project

<div align="center">

![Python](https://img.shields.io/badge/Python-3.10-blue?style=for-the-badge&logo=python)
![FastAPI](https://img.shields.io/badge/FastAPI-Production-green?style=for-the-badge&logo=fastapi)
![Docker](https://img.shields.io/badge/Docker-Containerized-blue?style=for-the-badge&logo=docker)
![AWS](https://img.shields.io/badge/AWS-Cloud-orange?style=for-the-badge&logo=amazonaws)
![MongoDB](https://img.shields.io/badge/MongoDB-Atlas-green?style=for-the-badge&logo=mongodb)
![CI/CD](https://img.shields.io/badge/CI/CD-GitHub%20Actions-black?style=for-the-badge&logo=githubactions)

### 🚀 End-to-End Production Grade MLOps Pipeline for Vehicle Insurance Prediction

</div>

---

# 📌 Project Overview

This project demonstrates a complete **Machine Learning Operations (MLOps)** workflow for predicting vehicle insurance outcomes using a scalable and production-ready architecture.

The project covers:

✅ Data Ingestion from MongoDB Atlas  
✅ Data Validation & Transformation  
✅ Model Training & Evaluation  
✅ AWS S3 Model Registry  
✅ CI/CD Automation using GitHub Actions  
✅ Dockerized Deployment  
✅ FastAPI Web Application  
✅ AWS EC2 Deployment  
✅ End-to-End Production Pipeline  

---

# ✨ Features

- 🔥 Modular End-to-End MLOps Pipeline
- ☁️ AWS Cloud Deployment
- 🐳 Docker Containerization
- ⚡ FastAPI Prediction API
- 📦 AWS ECR Integration
- 📊 Automated Model Training
- 📈 Data Validation & Transformation
- 🧠 Machine Learning Model Pipeline
- 🔄 CI/CD using GitHub Actions
- 🗄️ MongoDB Atlas Integration
- 🛠️ Logging & Exception Handling
- 🚀 Production Ready Architecture

---

# 🛠️ Tech Stack

## 👨‍💻 Programming & Frameworks

- Python 3.10
- FastAPI
- Scikit-Learn
- Pandas
- NumPy

---

## ☁️ Cloud & DevOps

- AWS EC2
- AWS ECR
- AWS S3
- GitHub Actions
- Docker

---

## 🗄️ Database

- MongoDB Atlas

---

## 📊 Machine Learning

- Data Ingestion
- Data Validation
- Feature Engineering
- Model Training
- Model Evaluation
- Prediction Pipeline

---

# 🏗️ Project Architecture

```text
MongoDB Atlas
      ↓
Data Ingestion
      ↓
Data Validation
      ↓
Data Transformation
      ↓
Model Trainer
      ↓
Model Evaluation
      ↓
AWS S3 Model Registry
      ↓
Prediction Pipeline
      ↓
FastAPI Application
      ↓
Docker Container
      ↓
AWS EC2 Deployment
```

---

# 📂 Project Structure

```bash
├── artifact/
├── config/
├── notebook/
├── src/
│   ├── components/
│   ├── configuration/
│   ├── cloud_storage/
│   ├── data_access/
│   ├── entity/
│   ├── exception/
│   ├── logger/
│   ├── pipeline/
│   └── utils/
│
├── static/
├── templates/
├── app.py
├── requirements.txt
├── Dockerfile
├── setup.py
├── pyproject.toml
└── .github/workflows/aws.yaml
```

---

# ⚙️ Installation & Setup

## 1️⃣ Clone Repository

```bash
git clone https://github.com/moteprem4-web/MLOPS_VEHICLE_INSURANCE.git
cd MLOPS_VEHICLE_INSURANCE
```

---

## 2️⃣ Create Virtual Environment

```bash
conda create -n vehicle python=3.10 -y
conda activate vehicle
```

---

## 3️⃣ Install Requirements

```bash
pip install -r requirements.txt
```

---

# 🍃 MongoDB Atlas Setup

## Steps

- Create MongoDB Atlas Account
- Create New Project
- Create M0 Free Cluster
- Create Database User
- Add Network Access:

```text
0.0.0.0/0
```

- Copy MongoDB Connection String

---

## Set Environment Variable

### Bash

```bash
export MONGODB_URL="your_mongodb_url"
```

### PowerShell

```powershell
$env:MONGODB_URL="your_mongodb_url"
```

---

# 📈 ML Pipeline Workflow

## 🔹 Data Ingestion

- Connects with MongoDB Atlas
- Fetches Dataset
- Converts Data into DataFrame
- Saves Artifacts

---

## 🔹 Data Validation

- Schema Validation
- Missing Value Handling
- Data Drift Detection

---

## 🔹 Data Transformation

- Feature Engineering
- Encoding & Scaling
- Data Cleaning

---

## 🔹 Model Trainer

- Train ML Models
- Hyperparameter Tuning
- Model Selection

---

## 🔹 Model Evaluation

- Compare Existing vs New Model
- Threshold-Based Validation

---

## 🔹 Model Pusher

- Upload Best Model to AWS S3
- Maintain Model Registry

---

# ☁️ AWS Services Used

| AWS Service | Purpose |
|---|---|
| EC2 | Deployment |
| ECR | Docker Image Registry |
| S3 | Model Storage |
| IAM | Authentication & Access |

---

# 🐳 Docker Setup

## Build Docker Image

```bash
docker build -t vehicleproj .
```

---

## Run Docker Container

```bash
docker run -p 5000:5000 vehicleproj
```

---

# 🔄 CI/CD Pipeline

## GitHub Actions Workflow

The CI/CD pipeline automatically performs:

✅ Build Docker Image  
✅ Push Image to AWS ECR  
✅ Deploy Application on EC2  
✅ Continuous Integration  
✅ Continuous Deployment  

---

# 🚀 Deployment Architecture

```text
GitHub Push
    ↓
GitHub Actions
    ↓
Docker Build
    ↓
AWS ECR
    ↓
AWS EC2 Deployment
    ↓
FastAPI Application
```

---

# 🖥️ Run Application

## Run with Python

```bash
python app.py
```

---

## Run with Uvicorn

```bash
uvicorn app:app --host 0.0.0.0 --port 5000
```

---

# 🌐 Application Routes

| Route | Description |
|---|---|
| `/` | Home Page |
| `/predict` | Prediction Endpoint |
| `/training` | Trigger Model Training |

---

# 📊 Logging & Exception Handling

- Centralized Logging System
- Custom Exception Handling
- Production Grade Error Tracking

---

# 🔐 Environment Variables

```env
MONGODB_URL=your_mongodb_url
AWS_ACCESS_KEY_ID=your_key
AWS_SECRET_ACCESS_KEY=your_secret
AWS_DEFAULT_REGION=us-east-1
```

---

# 📸 Recruiter Highlights

✅ Production Grade MLOps Architecture  
✅ AWS Cloud Deployment Experience  
✅ CI/CD Automation  
✅ Docker & Containerization  
✅ End-to-End ML Pipeline  
✅ FastAPI Backend Development  
✅ Real World Deployment Workflow  
✅ Industry-Level Project Structure  

---

# 📚 Learning Outcomes

Through this project, I gained hands-on experience in:

- MLOps Engineering
- AWS Cloud Services
- Docker & CI/CD
- Model Registry
- FastAPI Backend
- Production ML Systems
- Cloud Deployment
- Data Engineering

---

# 👨‍💻 Author

## Prem Mote

### 🔗 GitHub Profile

https://github.com/moteprem4-web

### 🚀 Project Repository

https://github.com/moteprem4-web/MLOPS_VEHICLE_INSURANCE

---

# ⭐ Support

If you like this project, give it a ⭐ on GitHub!

---

<div align="center">

## 🚀 Thank You For Visiting

</div>
