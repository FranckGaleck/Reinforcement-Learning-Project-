# 👾 Reinforcement Learning – Pacman & Multi-Armed Bandit

This repository presents a structured collection of Reinforcement Learning (RL) experiments.  
It explores several fundamental RL approaches including **multi-armed bandits**, **tabular Q-learning**, and **deep Q-learning**, applied to both simulations and a custom Pacman environment.

---

## 🧠 Project Highlights

### 🎰 1. Multi-Armed Bandit (Exploration vs Exploitation)
- Implemented $\epsilon$-greedy strategy to study reward optimization in bandit problems
- Compared different epsilon values and analyzed exploration/exploitation tradeoffs
- Visualized performance using reward and regret plots

### 🟨 2. Tabular Q-Learning on Pacman Grid
- Developed a custom Pacman environment using an OpenAI Gym-like API (`pacman_gym.py`)
- Applied Q-Learning algorithm with discrete state-action space
- Reward structure: +10 (dot), -10 (ghost), -1 (wall), 0 (neutral move)
- Agent behavior visualized through grid rendering

### 🧠 3. Deep Q-Learning (DQN)
- Built a Deep Q-Network with PyTorch to approximate Q-values
- Included experience replay and $\epsilon$-decay schedule
- Trained on the same environment to benchmark performance vs. Q-table
- Showed smoother learning and generalization capabilities

---

## 🛠️ Technologies Used

- **Python**
- **NumPy / Matplotlib**
- **PyTorch**
- **Custom OpenAI Gym-compatible Environment**

---
