# 🧠 Assignment 04: Leaky Integrate-and-Fire (LIF) Neuron Modeling

## 📌 Overview

This assignment explores how neurons process and encode information using the **Leaky Integrate-and-Fire (LIF) model**, a simplified mathematical representation of biological neurons.

The project combines simulation, visualization, and experimentation to understand how neurons respond to input currents, generate spikes, and encode signals over time.

---

## 🎯 Problem Statement

The goal of this assignment was to:

- Implement the LIF neuron model using differential equations  
- Simulate neuron behavior under different input conditions  
- Analyze how parameters affect neuron firing patterns  
- Understand how neurons encode information through spike trains  

---

## ⚙️ Approach & Methods

### 1. LIF Equation Simulation
- Implemented the LIF differential equation using numerical methods  
- Modeled membrane potential over time  
- Included spike generation and reset behavior  

### 2. Input Current Modeling
- Used step input current (on/off over time)  
- Simulated neuron response to external stimuli  

### 3. Interactive Dashboard
- Built an interactive **Manipulate[] interface**  
- Adjusted parameters such as:
  - Threshold voltage  
  - Time constant (τ)  
  - Input current  
- Observed real-time changes in neuron behavior  

### 4. f–I Curve Analysis
- Generated firing rate vs. input current (f–I curve)  
- Analyzed how neuron firing rate changes with stimulus intensity  

### 5. Signal Encoding (Rate Coding)
- Used a sine-wave input signal  
- Observed how continuous signals are converted into discrete spikes  

---

## 🧪 Key Concepts Demonstrated

- **Leaky Integrate-and-Fire Model**: Simulates neuron membrane dynamics  
- **Threshold Behavior**: Neuron fires only when input exceeds a critical level  
- **Rheobase**: Minimum current required to trigger a spike  
- **f–I Curve**: Relationship between input strength and firing rate  
- **Rate Coding**: Encoding signal intensity through spike frequency  

---

## 📊 Results & Observations

- The neuron begins firing at approximately **15 nA (rheobase)**  
- Increasing input current leads to higher spike frequency  
- Membrane potential follows a **curved (exponential-like)** trajectory between spikes  
- Larger time constants produce fewer spikes and smoother curves  
- Smaller time constants produce faster and more frequent firing  

From the f–I curve:
- The relationship is **nonlinear**, not perfectly linear  
- Firing rate increases gradually after threshold is reached  

From signal encoding:
- Spike trains capture overall signal intensity  
- Fine details of the waveform are lost  

---

## 🔬 Experiments Summary

### Experiment 1: Threshold Sweep
- Increasing threshold → fewer spikes  
- At high thresholds, neuron stops firing completely  

### Experiment 2: Time Constant Comparison
- Smaller τ → faster response and more spikes  
- Larger τ → slower response and smoother behavior  

### Experiment 3: f–I Curve Comparison
- Smaller τ produces a steeper curve (more sensitive neuron)  
- Larger τ produces a flatter curve (less sensitive neuron)  

---

## 📚 What I Learned

- How neurons integrate input over time before firing  
- The importance of threshold-based decision-making in biological systems  
- How firing rate encodes stimulus intensity  
- How model parameters affect neuron behavior and sensitivity  
- The role of time constants in shaping neural dynamics  

---

## ⚠️ Challenges Faced

- Understanding and implementing differential equations  
- Interpreting how parameters affect dynamic behavior  
- Connecting mathematical results to biological meaning  
- Visualizing spike-based encoding vs continuous signals  

---

## ▶️ How to Run

1. Open the notebook:
