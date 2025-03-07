# Deep Reinforcement Learning with Gym 🚀  

This repository contains implementations and experiments on various **Deep Reinforcement Learning (DeepRL)** algorithms using **OpenAI Gym** environments. The project explores **Deep Q-Networks (DQN)** and its improvements, investigates different neural architectures, and compares policy-based methods such as **PPO** and **A2C**.

---

## 📌 Project Overview  
This project is structured as follows:  

1. **Environment Selection** 🏋️  
   - Chosen one Gym environment and analyzed its **action space, observation shape, and reward signals**.  

2. **DQN Implementation** 🤖  
   - Implemented **Deep Q-Network (DQN)** using PyTorch.  
   - Trained the agent and **plotted rewards per epoch**.  

3. **Sensitivity Study** 📊  
   - Conducted analysis on **4 key implementation parameters** to study their impact.  
   - Presented results in a **one-page PDF report**.  

4. **Advanced DQN Enhancements** 🚀  
   - Implemented an **improved DQN variant** using one of the following:  
     - ✅ **Prioritized Experience Replay**  
     - ✅ **Dueling DQN**  
     - ✅ **Double DQN**  
     - ✅ **Noisy Networks for Exploration**  
   - Retrained the model and **compared performance**.  

5. **Alternative Neural Network Structures** 🧠  
   - Re-implemented DQN using **one of these advanced architectures**:  
     - ✅ **LSTM**  
     - ✅ **GRU**  
     - ✅ **Transformer**  
   - Analyzed how different architectures affect learning.  

6. **Comparing PPO & A2C** ⚖️  
   - Used **Stable-Baselines3 / Tianshou** to train **PPO** and **A2C**.  
   - Evaluated performance and presented findings in a **report**.  

---

## 📦 Installation  

1️⃣ Clone the repository:  
```bash
git clone https://github.com/Kallistina/dqn-gym-experiments.git
cd DQN-and-DeepRL-Gym
