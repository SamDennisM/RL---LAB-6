<p align="center">
  <img src="https://img.icons8.com/external-flatart-icons-outline-flatarticons/100/000000/artificial-intelligence.png" width="110"/>
</p>

<h1 align="center">🧠 RL Lab 6 — Bootstrapping Techniques</h1>

<p align="center">  
  <b>TD(0) • SARSA • Q-Learning • SARSA(λ) • Function Approximation</b><br>
  <i>A complete, visual, step-by-step implementation for Reinforcement Learning bootstrapping methods.</i>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10-blue?logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter"/>
  <img src="https://img.shields.io/badge/NumPy-0175C2?logo=numpy&logoColor=white"/>
  <img src="https://img.shields.io/badge/Matplotlib-ffffff?logo=matplotlib"/>
  <img src="https://img.shields.io/badge/Reinforcement%20Learning-Bootstrapping-green"/>
</p>

---

## 🎯 **Objective**

Implement, visualize, and compare **bootstrapping-based Reinforcement Learning techniques** using a custom **GridWorld** environment.

---

## 📘 **Algorithms Implemented**

### 🔵 Prediction
- **TD(0)** → bootstrapped state-value prediction  
- **Monte Carlo (First-Visit)** → non-bootstrapped baseline  

### 🔴 Control
- **SARSA** (On-policy)  
- **Q-Learning** (Off-policy)  

### 🟢 Additional Complexity
- **SARSA(λ)** with Eligibility Traces  
- **TD(0) + Linear Function Approximation**  

---

## 🗺️ **Environment: Custom GridWorld**

<p align="center">
  <img src="https://img.icons8.com/external-flatart-icons-outline-flatarticons/512/external-map-ux-and-ui-flatart-icons-outline-flatarticons.png" width="130"/>
</p>

- Grid size: **5×5**  
- Actions: **↑ ↓ ← →**  
- Reward:
  - Step = **–1**
  - Goal = **0**
- Start = bottom-left  
- Goal = top-right  
- Deterministic transitions  
- Heatmaps used for value/policy visualization  

---

## 📁 **Project Structure**

