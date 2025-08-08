# intrusion-detection
# Intrusion Detection System (IDS)

## Overview
The **Intrusion Detection System (IDS)** project analyzes network traffic data to identify malicious activities and security threats.  
It leverages **machine learning** techniques to distinguish between normal and suspicious network behavior, aiming to enhance cybersecurity through automated threat detection.

This project includes **data preprocessing**, **exploratory data analysis (EDA)**, **model building**, and **evaluation**, with results documented in an interactive Jupyter Notebook.

---

## Features
- 📊 **Exploratory Data Analysis (EDA)**: Identifies trends, anomalies, and relationships in the dataset.
- 🧹 **Data Preprocessing**: Handles missing values, normalizes/encodes features, and prepares data for modeling.
- 🤖 **Machine Learning Models**: Trains classifiers to detect intrusions.
- 📈 **Model Evaluation**: Compares models using accuracy, precision, recall, and F1-score.
- 📂 **Network Log Analysis**: Provides additional insights from raw network logs.

---

## Dataset
- **Train_data.csv**: Main dataset used for training and testing models.
- **network_log.txt**: Sample log file containing raw network activity data.

**Sample Features** (update according to your dataset):
- `Duration` – Length of the connection/session
- `Protocol` – Type of protocol used (TCP, UDP, ICMP, etc.)
- `Service` – Network service accessed
- `Src_bytes` – Bytes sent from source
- `Dst_bytes` – Bytes sent to destination
- `Flag` – Connection status
- `Label` – Classification (Normal / Intrusion)

---

## Project Structure
