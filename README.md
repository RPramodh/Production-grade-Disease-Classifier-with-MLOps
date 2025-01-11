# Production-Grade-Disease-Classifier-with-MLOps


This project leverages machine learning to classify kidney disease efficiently, incorporating advanced tools like MLflow for experiment tracking and DVC for lightweight orchestration and pipeline management. Designed for seamless deployment and scalability, this system ensures an efficient and secure environment for data scientists and healthcare professionals.

---

# 📋 <a name="table">Table of Contents</a>

1. 🚀 [Introduction](#introduction)
2. ⚙️ [Tech Stack](#tech-stack)
3. 🎨 [Features](#features)
4. 🖥️ [Quick Start](#quick-start)
5. 📜 [About MLflow & DVC](#mlflow-dvc)

---

## <a name="tech-stack">⚙️ Tech Stack</a>

- **Python 3.8**: Core language for development and machine learning.
- **TensorFlow/PyTorch**: Frameworks for model development and training.
- **MLflow**: Production-grade experiment tracking and model logging.
- **DVC**: Lightweight experiment tracker and pipeline orchestrator.
- **Dagshub**: Simplified ML experiment tracking and collaboration platform.
- **Docker**: Containerization for deployment.
- **AWS (ECR & EC2)**: Cloud-based infrastructure for scalable model deployment.

---

## <a name="features">🎨 Features</a>

🕀 **Experiment Tracking**: Manage and track all experiments with MLflow and DVC.  

🕀 **Pipeline Management**: Lightweight orchestration with `dvc.yaml` for modular and reproducible workflows.

🕀 **Secure Cloud Deployment**: Integration with AWS services like EC2 and ECR for reliable deployment.

🕀 **Data Version Control**: Maintain reproducibility with DVC for datasets and experiments.

🕀 **Dockerized Deployment**: Ensure portability with Docker containers.

🕀 **User-Friendly Environment**: Simplified setup and configuration for seamless adoption.

---

## <a name="quick-start">🖥️ Quick Start</a>

### **Prerequisites**

Ensure the following are installed on your system:

- [Git](https://git-scm.com/)
- [Conda](https://docs.conda.io/projects/conda/en/latest/index.html)
- [Python 3.8](https://www.python.org/downloads/)
- [MLflow](https://mlflow.org/)
- [DVC](https://dvc.org/)
- [Docker](https://www.docker.com/)

### **Installation**

#### Step 1: Clone the Repository
```bash
git clone https://github.com/krishnaik06/Kidney-Disease-Classification-Deep-Learning-Project
```

#### Step 2: Create a Conda Environment
````bash
conda create -n cnncls python=3.8 -y
conda activate cnncls
````

#### Step 3: Install Requirements
````bash
pip install -r requirements.txt
````

#### Step 4: Create a .env file in the root directory and add:
````bash
# MLflow Configuration
MLFLOW_TRACKING_URI=
MLFLOW_TRACKING_USERNAME=
MLFLOW_TRACKING_PASSWORD=

# AWS Configuration
AWS_ACCESS_KEY_ID=
AWS_SECRET_ACCESS_KEY=
AWS_REGION=us-east-1
AWS_ECR_LOGIN_URI=
ECR_REPOSITORY_NAME=
````

#### Step 5: Run the Application
````bash
python app.py
````
