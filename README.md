# HybridAI-IDS: AI-Powered Intrusion Detection System

## Overview

HybridAI-IDS is a Hybrid Intrusion Detection System (IDS) that combines Machine Learning and Deep Learning techniques to detect network attacks and anomalous behavior in real-time.

The project integrates a complete cybersecurity pipeline for collecting, processing, analyzing, and visualizing network traffic. It uses AI models trained on the CICIDS2017 dataset and supports both attack classification and anomaly detection.

---

## Problem Statement

Traditional Intrusion Detection Systems face several limitations:

* Inability to detect unknown or zero-day attacks.
* Dependence on predefined signatures.
* High false positive rates.
* Difficulty handling large-scale network traffic.

This project addresses these challenges by leveraging AI-driven detection techniques to improve detection accuracy and reduce false alarms.

---

## Project Objectives

* Detect cyber attacks in real time.
* Classify multiple attack categories.
* Identify unknown attacks using anomaly detection.
* Reduce false positives.
* Provide live monitoring and visualization dashboards.
* Build a scalable and modular IDS architecture.

---

## System Architecture

The IDS pipeline consists of:

1. Network Traffic Collection
2. Apache Kafka for data streaming
3. Logstash for log processing and feature extraction
4. Elasticsearch for storage and indexing
5. Kibana for visualization
6. AI Models for attack detection
7. FastAPI backend for prediction services
8. Web Dashboard for monitoring and management

---

## Technologies Used

### Cybersecurity Stack

* Apache Kafka
* Logstash
* Elasticsearch
* Kibana
* Docker
* VMware

### Artificial Intelligence

* Python
* XGBoost
* CNN
* MLP
* Autoencoder
* Pandas
* NumPy
* Scikit-Learn
* TensorFlow / Keras

### Backend

* FastAPI
* Joblib

### Dataset

* CICIDS2017

---

## Machine Learning Models

### XGBoost

* Test Accuracy: 99%
* Macro F1-Score: 0.95

### CNN

* Test Accuracy: 99%
* Macro F1-Score: 0.90

### MLP

* Test Accuracy: 98%
* Macro F1-Score: 0.84

### Autoencoder

Used for anomaly detection and identifying previously unseen attacks.

---

## Data Preprocessing

The dataset underwent several preprocessing steps:

* Label normalization
* Missing value handling
* Duplicate removal
* Feature scaling
* Log transformation
* Data augmentation
* Feature selection using XGBoost

These steps improved model performance and generalization.

---

## Features

* Real-Time Attack Detection
* Multi-Class Attack Classification
* Anomaly Detection
* Live Traffic Monitoring
* Interactive Dashboard
* Alert Management
* User Management
* System Logs Monitoring
* AI Model Performance Tracking

---

## API Endpoints

### Authentication

* User Login

### Dashboard

* Get Dashboard Statistics

### Alerts

* Retrieve Security Alerts

### Logs

* Retrieve Network Logs

### Models

* Retrieve AI Models Information

### Prediction

* Predict Incoming Network Traffic

---

## Results

| Model   | Accuracy | Macro F1 |
| ------- | -------- | -------- |
| XGBoost | 99%      | 0.95     |
| CNN     | 99%      | 0.90     |
| MLP     | 98%      | 0.84     |

The XGBoost model achieved the best overall performance and was selected as the primary classification model.

---

## Challenges

* Class imbalance in cybersecurity datasets.
* Reducing false positives.
* Real-time traffic processing.
* Integration of multiple technologies.
* Detecting zero-day attacks.

---

## Future Work

* Zero-Day Attack Detection Enhancement.
* Online Learning for continuous model updates.
* Threat Intelligence Integration.
* Cloud Deployment.
* SIEM Integration.
* Advanced Explainable AI (XAI).

---

## Team Members

* Amir Akram Zakaria
* Amy Yousef Fawzy
* Shahd Ahmed Ragab
* Mariem Adel Kamal
* Wesal Shazly Abdelkarem
* Shahd Yahia Mohamed
* Peter Atef Hafez
* Gerges Nashaat Habeeb

---

## License

This project was developed as a Graduation Project at the Egyptian E-Learning University (EELU), Faculty of Computers and Information Technology.
