# Ms. Pac-Man (Deep Convolutional Q-Learning)

This project implements a **Deep Convolutional Q-Network (DCQN)** agent to play the **Ms. Pac-Man** environment from [Gymnasium](https://gymnasium.farama.org/).  
The agent learns to navigate the maze, collect pellets, avoid ghosts, and maximize its score using Deep Reinforcement Learning techniques.

---

## Try it on Google Colab
Run the notebook directly in Google Colab:  
[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/Connor2452/ms-pacman-dcqn/blob/main/Deep_Convolutional_Q_Learning_for_Pac_Man.ipynb?copy=true)

---

## Project Overview
- **Environment:** MsPacmanNoFrameskip-v0 (Gymnasium)
- **Goal:** Maximize score by collecting pellets and avoiding ghosts
- **Approach:** Deep Convolutional Q-Network (DCQN) with experience replay and target networks
- **Tools:** Python, PyTorch, Gymnasium, NumPy, PIL, Torchvision, Matplotlib

---

## Results
After training, the DCQN agent is capable of playing Ms. Pac-Man with improved strategies, avoiding ghosts, and consistently achieving higher scores over time.  

![Ms. Pac-Man Demo](pacman.gif)

---

## Repository Structure
- Deep_Convolutional_Q_Learning_for_Pac_Man.ipynb # Main notebook file of the network
- README.md # Project description (this file)
- deep_convolutional_q_learning_for_pac_man.py # Same main file in .py format
- pacman.gif # GIF of the model playing pacman

---

## Notes
- Designed for Google Colab to avoid environment/setup issues on local machines.
- No additional setup needed; all dependencies are installed in the notebook.
- If trying to run outside of Google Colab, other packages may be required.
