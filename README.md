# Reinforcement Learning Lab 1

This repository contains **Lab 1: Bandits and Contextual Bandits** from the course **Reinforcement Learning** at *Stockholm University*.

---

## Overview

In this lab, the goal is to simulate and analyze **news recommendation systems** using **multi-armed bandits** and **contextual bandits**.  
You act as a data scientist for *NewsNet*, where the system learns which articles to recommend based on user behavior and contextual information.

The lab explores how to balance **exploration** (trying new options) and **exploitation** (using what seems best).

---

## Contents

### **Part 1 — Multi-Armed Bandits**
- Implemented algorithms:
  - Epsilon-Greedy
  - Upper Confidence Bound (UCB)
- Evaluation metrics:
  - Average reward
  - Cumulative regret
  - Action selection counts

### **Part 2 — Contextual Bandits**
- Environment models user features such as:
  - Political interest, sports preference, tech-savviness, reading time, and age  
- Algorithms:
  - Contextual Epsilon-Greedy
  - Linear UCB (LinUCB)
- Compared against a random policy

---

##  Key Results
- **Epsilon-Greedy** explores randomly and balances exploration with ε.
- **UCB** explores optimistically based on uncertainty, leading to faster convergence.
- **Contextual Bandits** adapt article recommendations to user profiles, outperforming static bandits.

---

##  File Description
| File | Description |
|------|--------------|
| `rl_lab_1.py` | Complete Python implementation of Lab 1 including MAB, Contextual Bandits, and visualizations. |

---

##  Author
**Negin Ebrahimi**  
 *Master’s Student, Stockholm University*  
 [Contact via GitHub](https://github.com/ebrahiminegin67)

---

## 🌟 Acknowledgements
Based on the *Reinforcement Learning* course labs by **Sindri Magnússon**, Stockholm University.
