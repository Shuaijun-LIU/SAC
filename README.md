# RL_sb3based_SAC Project Structure

This repo is based on **Stable-Baselines3 (SB3)** and implements the **Soft Actor-Critic (SAC)** reinforcement learning algorithm. 

---

## Project Directory Structure

```plaintext
RL_sb3based_SAC/
│
├── sac/                       # Main SAC algorithm 
│   ├── __init__.py            
│   ├── policies.py            # Defines SAC policy networks
│   ├── sac.py                 # Core SAC training and inference logic
│
├── support/                   # Supporting modules for SAC training
│   ├── __init__.py            
│   ├── base_class.py          # Base class for SAC components
│   ├── buffers.py             # Experience replay buffer implementation
│   ├── callbacks.py           # Callback functions for monitoring training
│   ├── distributions.py       # Handles probability distributions for SAC policies
│   ├── logger.py              # Logging utilities for training progress
│   ├── noise.py               # Noise strategies for exploration
│   ├── off_policy_algorithm.py # Base class for off-policy RL algorithms (including SAC)
│   ├── policies.py            # Defines policies for SAC and other RL algorithms
│   ├── preprocessing.py       # Data preprocessing utilities
│   ├── save_util.py           # Utility functions for saving/loading models
│   ├── torch_layers.py        # Defines neural network layers used in SAC
│   ├── type_aliases.py        # Type aliases for better readability
│   ├── utils.py               # General utility functions
│
├── support/vec_env/           # Environment wrapper and utilities
```
