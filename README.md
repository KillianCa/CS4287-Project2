# Mountain Car – Deep Q-Network (DQN)

This project implements a **Deep Q-Network (DQN)** to solve the classic **MountainCar-v0** problem from OpenAI Gym.  
The task is to train an AI agent to push a car up a steep hill to a goal state, using reinforcement learning.

---

##  Project Overview
- Implemented a custom **DQN agent** in Python with TensorFlow/Keras.  
- Balanced **exploration vs. exploitation** using an epsilon-greedy strategy.  
- Applied **experience replay** to improve training stability and prevent catastrophic forgetting.  
- Customised the reward function to encourage the agent to move closer to the goal.  
- Achieved a successful solution after ~100 episodes, demonstrating convergence.  

---

##  Technologies & Libraries
- **Python**  
- **TensorFlow/Keras**  
- **OpenAI Gym** 
- **NumPy**   
- **Matplotlib**  

---

## Results
- Agent successfully learned to reach the goal within ~100 training episodes.  
- Training performance graph shows average rewards increasing over time. 
