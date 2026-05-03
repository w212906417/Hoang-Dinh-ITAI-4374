# 🧠 Lab 07: Anomaly Detection with HTM

## 📌 Overview

This lab explores how intelligent systems can detect unusual or unexpected patterns using **Anomaly Detection**, based on Hierarchical Temporal Memory (HTM).

The focus is on identifying when incoming data deviates from learned patterns. By leveraging Temporal Memory, the system compares predictions with actual inputs to determine whether something is normal or anomalous.

---

## 🎯 Objectives

The main goals of this lab were:

- Understand how anomaly detection works in sequence-based systems  
- Use prediction errors to identify unusual patterns  
- Implement an anomaly score based on model performance  
- Analyze how the system reacts to unexpected inputs  

---

## ⚙️ Approach & Implementation

The lab builds on Temporal Memory concepts to evaluate how well predictions match actual observations.

### 1. Sequence Learning
- Trained the model on normal sequences of data  
- Allowed the system to learn expected patterns over time  

### 2. Prediction vs Actual Comparison
- Compared predicted inputs with actual inputs  
- Measured how closely they matched  

### 3. Anomaly Score Calculation
- Calculated an anomaly score based on prediction error  
- High error → high anomaly score  

### 4. Detection of Unexpected Events
- Introduced deviations or new patterns  
- Observed how the anomaly score responded  

### 5. Continuous Monitoring
- The system continuously updates predictions  
- Anomaly detection happens in real time  

---

## 🧪 Key Concepts Demonstrated

- **Anomaly Detection**: Identifying unexpected or rare events  
- **Prediction Error**: Difference between expected and actual input  
- **Temporal Context**: Uses sequence history to detect anomalies  
- **Real-Time Analysis**: Continuously evaluates incoming data  

---

## 📊 Results & Observations

- The system successfully detected deviations from learned sequences  
- Anomaly scores increased significantly when unexpected inputs appeared  
- Stable patterns produced consistently low anomaly scores  
- Detection performance depended on how well the system learned normal behavior  

---

## 📚 What I Learned

- How anomaly detection can be based on prediction accuracy  
- The importance of learning “normal” patterns before detecting anomalies  
- How sequence models can be applied to real-time monitoring  
- How biological inspiration can improve detection systems  

---

## ⚠️ Challenges Faced

- Interpreting anomaly scores and determining meaningful thresholds  
- Handling noisy data that may resemble anomalies  
- Ensuring the system learns patterns effectively before evaluation  
- Visualizing when and why anomalies occur  

---

## ▶️ How to Run

1. Open the Jupyter Notebook:
