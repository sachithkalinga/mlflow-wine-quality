# 🍷 MLflow Setup Guide for Wine Quality Prediction

This guide walks you through setting up your environment to use [MLflow](https://mlflow.org/) for tracking machine learning experiments — specifically for predicting wine quality.

---

## ✅ Minimum Requirements

| Component         | Recommended Version |
|------------------|---------------------|
| **Python**        | 3.7 – 3.11 *(3.12 not fully supported yet)* |
| **pip**           | ≥ 20.0 *(Upgrade with `pip install --upgrade pip`)* |
| **OS**            | Windows / Linux / macOS |

-------------------------------
## 🔧 Create and Activate a Virtual Environment

### 📁 Step 1: Create Virtual Environment
```
python -m venv mlflow_env
```
This creates a folder named `mlflow_env` containing the Python interpreter, pip, and base packages.

### ⚙️ Step 2: Activate Environment

Windows
```
mlflow_env\Scripts\activate
```
macOS/Linux
```
source mlflow_env/bin/activate
```
This creates a folder named mlflow_env containing the Python interpreter, pip, and base packages.

-----------------------
## 📦 Install Dependencies

```
pip install mlflow scikit-learn pandas seaborn jupyter
```
### 🔍 Installed Packages:

*   **MLflow** → Experiment tracking
    
*   **Scikit-learn** → Modeling
    
*   **Pandas & Seaborn** → Data handling & visualization
    
*   **Jupyter** → Interactive coding notebooks
    
-------------------------------
## 🚀 Launching MLflow Tracking UI


### ▶️ Command:

```
mlflow ui
```
### 🌐 Access the UI:

*   [http://127.0.0.1:5000](http://127.0.0.1:5000)
    
*   [http://localhost:5000](http://localhost:5000)
    

* Leave the terminal **open and running** while using the UI.
-------------------------------
## 🌈 Use a Custom Port (Optional)


If port 5000 is already in use, specify another port:

```
mlflow ui --port 8989 
```
Then access via: [http://localhost:8989](http://localhost:8989)

Happy Experiment Tracking! 🎯
