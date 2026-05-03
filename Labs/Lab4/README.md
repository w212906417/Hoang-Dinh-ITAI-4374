# 🧠 Lab 04: Spatial Pooling and Sparse Distributed Representations

## 📌 Overview

This lab explores how the brain encodes information efficiently using **Sparse Distributed Representations (SDRs)**, a key concept in Hierarchical Temporal Memory (HTM).

The focus is on implementing a simplified **Spatial Pooling** mechanism, which converts dense input data into sparse representations. This process helps improve noise tolerance, pattern recognition, and generalization in intelligent systems.

---

## 🎯 Objectives

The main goals of this lab were:

- Understand the concept of Sparse Distributed Representations (SDRs)  
- Implement a basic Spatial Pooling algorithm  
- Observe how input patterns are transformed into sparse outputs  
- Analyze how sparsity improves robustness and efficiency  

---

## ⚙️ Approach & Implementation

The lab was structured around simulating how neurons activate sparsely in response to input patterns.

### 1. Input Encoding
- Generated binary or numerical input vectors  
- Represented raw sensory data before processing  

### 2. Synapse Connections
- Each column connects to a subset of input features  
- Connections have weights (or permanence values)  

### 3. Overlap Calculation
- Measured how well each column matches the input  
- Higher overlap → stronger activation potential  

### 4. Inhibition (Competition)
- Columns compete with each other  
- Only a small percentage of columns become active  
- Enforces sparsity in the output  

### 5. Sparse Output Generation
- Selected top-performing columns  
- Produced a sparse representation of the input  

---

## 🧪 Key Concepts Demonstrated

- **Sparse Distributed Representations (SDRs)**: Only a small fraction of neurons are active at once  
- **Noise Resistance**: SDRs remain stable even with noisy inputs  
- **Efficiency**: Sparse encoding reduces computational complexity  
- **Competition Mechanism**: Inhibition ensures only the strongest signals survive  

---

## 📊 Results & Observations

- The system successfully produced sparse representations of input data  
- Similar inputs resulted in overlapping SDRs, showing pattern recognition ability  
- Noise in input had limited impact on the final output  
- Sparsity improved both stability and interpretability  

---

## 📚 What I Learned

- How SDRs are used to represent information efficiently in brain-inspired models  
- The role of competition and inhibition in neural systems  
- Why sparsity is important for robustness and scalability  
- How Spatial Pooling transforms raw data into meaningful patterns  

---

## ⚠️ Challenges Faced

- Understanding how inhibition affects final output selection  
- Tuning parameters (e.g., sparsity level, overlap threshold)  
- Visualizing how input maps to sparse output  
- Balancing model simplicity with realistic behavior  

---

## ▶️ How to Run

1. Open the Jupyter Notebook:
