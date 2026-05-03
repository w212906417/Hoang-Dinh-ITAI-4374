# 🧠 Lab 05: Temporal Memory and Sequence Learning

## 📌 Overview

This lab explores how the brain learns and predicts sequences over time using the concept of **Temporal Memory**, a core component of Hierarchical Temporal Memory (HTM).

The goal is to simulate how neurons can learn patterns in sequences and make predictions about future inputs based on past observations. This allows systems to move beyond static pattern recognition and handle time-based data.

---

## 🎯 Objectives

The main goals of this lab were:

- Understand how Temporal Memory models sequence learning  
- Simulate how neurons activate based on previous context  
- Implement prediction mechanisms for sequential data  
- Analyze how the system learns transitions between patterns  

---

## ⚙️ Approach & Implementation

The lab focused on modeling how cells within columns respond differently depending on context.

### 1. Input Sequences
- Defined sequences of patterns (e.g., A → B → C)  
- Represented time-dependent data  

### 2. Active and Predictive States
- Cells can be in active, inactive, or predictive states  
- Predictive cells anticipate the next input  

### 3. Learning Transitions
- Connections are strengthened between sequential patterns  
- The system learns which patterns follow others  

### 4. Sequence Disambiguation
- Same input can lead to different outputs depending on context  
- System uses history to determine correct prediction  

### 5. Prediction Mechanism
- Based on learned sequences, the model predicts the next step  
- Correct predictions reinforce learning  

---

## 🧪 Key Concepts Demonstrated

- **Sequence Learning**: Ability to learn patterns over time  
- **Context Awareness**: Same input can have different meanings  
- **Prediction**: System anticipates future inputs  
- **Memory Formation**: Connections store temporal relationships  

---

## 📊 Results & Observations

- The system successfully learned simple sequences  
- Predictions improved as more sequences were observed  
- Incorrect predictions occurred when sequences were ambiguous  
- Context played a critical role in accurate prediction  

---

## 📚 What I Learned

- How temporal data differs from static data in machine learning  
- The importance of context in sequence prediction  
- How memory and prediction are tightly connected  
- How biological inspiration can guide sequence modeling  

---

## ⚠️ Challenges Faced

- Understanding how multiple states (active vs predictive) interact  
- Managing ambiguity in overlapping sequences  
- Visualizing how the model transitions between states  
- Ensuring stable learning across multiple iterations  

---

## ▶️ How to Run

1. Open the Jupyter Notebook:
