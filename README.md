# DDoS Attack Detection using Machine Learning in SDN

## Introduction
This document outlines the process of DDoS (Distributed Denial of Service) attack detection using Machine Learning (ML) techniques in Software-Defined Networking (SDN) environments. The goal is to develop models capable of distinguishing between benign and malicious network traffic to enhance network security.

## Data Analysis
### Dataset Overview
- The dataset contains information about network traffic, including features like packet count, byte count, protocol, duration, etc.
- The labels indicate whether the traffic is benign or malicious (0 for benign, 1 for malicious).

### Data Preprocessing
- Initial data analysis includes examining the distribution of labels, identifying null values, and visualizing features.
- Object columns such as source and destination IP addresses are explored to understand traffic patterns.

## Classical ML Models
### Model Implementation
- Implemented classical ML models including Logistic Regression, Support Vector Machine (SVM), Decision Tree, Random Forest, and k-Nearest Neighbors (KNN).
- Utilized feature scaling and preprocessing techniques for model training.
- Conducted hyperparameter tuning using GridSearchCV to optimize model performance.

### Results
- Logistic Regression, SVM, Decision Tree, Random Forest, and KNN models were trained and evaluated.
- Decision Tree and Random Forest exhibited promising performance in terms of accuracy and classification metrics.

## Prediction with Feature Selection
### Feature Selection
- Identified important features based on research findings and feature weights.
- Dropped redundant and highly correlated features to improve model efficiency.

### Model Evaluation
- Re-evaluated Logistic Regression, SVM, Random Forest, and Decision Tree models with the selected features.
- Observed improved performance in terms of accuracy and computational efficiency.

## Conclusion
- ML models show promise in detecting DDoS attacks in SDN environments.
- Feature selection and preprocessing techniques play a crucial role in enhancing model performance.
- Decision Tree and Random Forest models demonstrate effectiveness in distinguishing between benign and malicious network traffic.
- Continued research and development in ML-based DDoS detection can contribute to strengthening network security in SDN infrastructures.
