# 🐦 Flappy Bird Game with Deep Q-Learning (DQN)

This project is a **Flappy Bird game environment** built using Gymnasium and Pygame, with support for **Deep Reinforcement Learning (DQN)**.
It allows both **manual gameplay** and training an **AI agent** to play the game automatically.

---

## 🚀 Features

* 🎮 Play Flappy Bird manually using keyboard
* 🤖 Train an AI agent using Deep Q-Learning (DQN)
* 🧠 Uses Experience Replay & Target Network
* 🖥️ Real-time rendering using Pygame
* ⚡ Beginner-friendly implementation

---

## 🛠️ Tech Stack

* Python 3.11
* Gymnasium
* Pygame
* flappy-bird-gymnasium
* PyTorch

---

## 📦 Installation

Clone the repository:

```bash
git clone https://github.com/Samiksha28-k/flappy-bird-game.git
cd flappy-bird-game
```

Install dependencies:

```bash
pip install gymnasium pygame flappy-bird-gymnasium torch torchvision
```

---

## ▶️ How to Run

### 🔹 1. Play Manually

```bash
python game_flappy_bird.py
```

Controls:

* **SPACE** → Flap
* Close window → Exit

---

### 🔹 2. Train AI Agent (DQN)

```bash
python agent.py
```

---

## 🧠 Deep Q-Learning (DQN)

This project implements **Deep Q-Learning**, a Reinforcement Learning algorithm.

### 🔹 Key Concepts:

* **Q-Network** → Neural network to estimate Q-values
* **Experience Replay** → Stores past experiences and samples randomly
* **Target Network** → Stabilizes training

### 🔹 Update Equation:

[
Q(s,a) = r + \gamma \max Q(s',a')
]

---

## 📂 Project Structure

```
flappy-bird-game/
│
├── game_flappy_bird.py   # Manual gameplay
├── agent.py              # DQN training
├── dqn.py                # Neural network model
├── README.md
```

---

## 📊 Future Improvements

* 📈 Plot training rewards graph
* 🎥 Save gameplay videos
* 🤖 Improve AI performance
* 🌐 Deploy as web app

---

## 🙌 Acknowledgements

* Gymnasium
* flappy-bird-gymnasium
* PyTorch

---

## 👩‍💻 Author

**Samiksha Sengar**
GitHub: https://github.com/Samiksha28-k

---

## ⭐ Support

If you like this project, please ⭐ the repository!
