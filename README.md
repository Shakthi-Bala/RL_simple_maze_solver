# RL Maze Follower (Jupyter Notebook) 🧩🤖

This project demonstrates a **simple Reinforcement Learning (RL) agent** that learns to **navigate/follow a path in a maze** using trial-and-error.  
All implementation, training, and evaluation are provided in a single Jupyter Notebook.

---

## 📁 Project Files

```bash
.
├── ML_pro.ipynb        # Main notebook (training + evaluation + plots)
└── README.md
```
## 🎯 What This Notebook Does
1. Defines a maze/grid environment (states, actions, rewards)

2. Trains an RL agent to reach the goal by learning an optimal policy

3. Visualizes:
  - Training progress (rewards/steps)
  - Final learned path / policy behavior

4. Tests the trained agent on the maze

## 🧠 RL Method (High-Level)
Depending on the notebook configuration, the agent typically uses:

- Q-Learning / SARSA (tabular RL) OR a simple value/policy update approach
- Epsilon-greedy exploration to balance exploration vs exploitation
- Reward shaping to encourage reaching the goal efficiently

Open the notebook to see the exact algorithm and hyperparameters used.

## 🧰 Requirements
### Python
- Python 3.8+ recommended
### Common Libraries
Install the typical dependencies used in RL/grid-maze notebooks:
```bash
pip install numpy matplotlib
```
```bash
pip install pandas gym
```

## 🚀 How to Run
1. Clone the repository:
```bash
git clone <YOUR_REPO_URL>
cd <YOUR_REPO_FOLDER>
```
2. Start Jupyter:
```bash
jupyter notebook
```
3. Open and run:
```bash
ML_pro.ipynb
```
4. Run cells top → bottom:
- Environment setup
- Training loop
- Evaluation / visualization

## ✅ Expected Outputs
After running the notebook, you should see:

- Training curve(s): reward per episode / steps per episode
- A learned policy/path that successfully navigates the maze
- Optional prints/logs showing episode statistics

## 📌 Notes & Extensions

This project is intended as a **learning-focused Reinforcement Learning implementation**, designed to be **simple, interpretable, and easy to modify**.

### Possible Extensions
This framework serves as a strong foundation for experimenting with more advanced RL concepts, including:

- Larger and more complex maze environments  
- Stochastic state transitions  
- Multiple goal or reward configurations  
- Deep Q-Networks (DQN) and function approximation 

## 📜 License
For academic and educational use. Feel free to modify and extend.

## 👤 Author
Shakthi Bala
Reinforcement Learning | Robotics | Autonomous Navigation
