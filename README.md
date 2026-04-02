# 🧠 MLOps Pipeline with Weights & Biases and MLP

This project implements a complete **Machine Learning pipeline** following **MLOps best practices**, using **Weights & Biases (W&B)** for experiment tracking and artifact versioning.

The goal is to build a **reproducible, monitored, and scalable workflow**, covering everything from raw data ingestion to training a **Multi-Layer Perceptron (MLP)** using PyTorch.

---

## 🚀 Features

- 📦 **Artifact Versioning** with Weights & Biases  
  Track datasets, processed data, splits, and trained models

- 🧪 **Data Validation Tests**  
  Automated checks to ensure data consistency and quality

- 🔀 **Train/Test Split with Statistical Validation**  
  Reliable dataset splitting to avoid bias and leakage

- 🧠 **MLP Model (PyTorch)**  
  Implementation of a Multi-Layer Perceptron for supervised learning tasks

- 📊 **Experiment Tracking**  
  Logging of metrics such as loss and performance in real-time using W&B

- ⏹️ **Early Stopping**  
  Prevent overfitting by stopping training when performance stops improving

- 🏆 **Best Model Registration**  
  Automatic saving and versioning of the best-performing model

---

## 🏗️ Pipeline Overview

The pipeline follows a structured MLOps workflow:

1. **Data Ingestion**
   - Load raw dataset
   - Log raw data as an artifact

2. **Data Cleaning & Validation**
   - Handle missing values and inconsistencies
   - Run validation tests

3. **Data Splitting**
   - Train/Test split with statistical checks

4. **Model Training**
   - Train MLP using PyTorch
   - Track metrics with W&B

5. **Model Evaluation**
   - Evaluate performance on test data

6. **Model Registration**
   - Save and version the best model as an artifact

---

## 🛠️ Technologies Used

- Python
- PyTorch
- Weights & Biases (W&B)
- NumPy
- Pandas
- Scikit-learn

---

## 📂 Project Structure

.
├── data/ # Raw and processed datasets
├── notebooks/ # Jupyter notebooks
├── src/ # Source code (pipeline, models, utils)
├── tests/ # Data validation tests
├── README.md

