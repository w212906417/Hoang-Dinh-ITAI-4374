# 🧠 Lab 02: Cortical Column Voting Simulation

## 📌 Overview

This lab explores how the brain may form reliable perceptions from incomplete and noisy information using the concept of cortical columns, inspired by the Thousand Brains Theory.

In this simulation, multiple independent “columns” receive partial sensory input, form their own hypotheses, and collectively vote to reach a shared consensus. This demonstrates how distributed intelligence can emerge without a central controller.

---

## 🎯 Objectives

The main goals of this lab were:

- Simulate how multiple agents (cortical columns) process noisy input  
- Implement a voting-based consensus mechanism  
- Analyze how agreement is formed over time  
- Understand trade-offs between accuracy, noise, and system size  

---

## ⚙️ Approach & Implementation

The lab was divided into several key components:

### 1. Sensory Input Generation
- Created simulated input representing partial and noisy observations  
- Each “column” receives slightly different information  

### 2. Belief Initialization
- Each column starts with its own hypothesis about the object  
- These beliefs may differ due to noise and incomplete data  

### 3. Voting Mechanism
- Columns vote for their current hypothesis  
- Votes are aggregated to determine the most supported interpretation  

### 4. Consensus Process
- The system iterates until a majority agreement is reached  
- This models how perception stabilizes over time  

---

## 🧪 Key Concepts Demonstrated

- **Distributed Intelligence**: No single controller—decision emerges from collaboration  
- **Noise Robustness**: System can still reach correct conclusions despite imperfect input  
- **Consensus Formation**: Agreement builds gradually through repeated voting  
- **Scalability Trade-offs**: More columns can improve accuracy but may slow convergence  

---

## 📊 Results & Observations

- The system successfully reached consensus in most scenarios  
- Increasing noise made convergence slower and less stable  
- More columns improved robustness but required more iterations  
- Demonstrated the balance between speed vs. accuracy  

---

## 📚 What I Learned

- How biological inspiration (neuroscience) can inform AI system design  
- The importance of distributed decision-making in handling uncertainty  
- How consensus algorithms work in practice  
- How system parameters (noise, number of agents) impact performance  

---

## ⚠️ Challenges Faced

- Designing a voting mechanism that converges reliably  
- Handling noisy input without causing unstable results  
- Balancing simplicity of the model with meaningful behavior  
- Understanding how small parameter changes affect the system  

---

## ▶️ How to Run

1. Open the Jupyter Notebook:

L02_Hoang_Dinh_ITAI4374.ipynb

2. Run all cells in order  
3. Observe how the voting process evolves and reaches consensus  

---

## 💡 Final Thoughts

This lab provided a hands-on way to understand how intelligence can emerge from many simple components working together. While simplified, the model offers insight into both neuroscience and modern AI systems that rely on distributed processing and consensus.
