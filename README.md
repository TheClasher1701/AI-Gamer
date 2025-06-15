# **Project Overview**  

This project aims to develop an AI model that learns to play a **customized 2D game** through reinforcement learning. The AI model will be trained to navigate the game environment, learn from its interactions, and improve its performance over time.  

---

## **Game Details**  

- A **2D game** built using **Pygame**.  
- The environment is designed to challenge the AI player as it learns to complete objectives.  
- The AI will interact with the game world, analyze the environment, and improve its skills through repeated gameplay.  

---

## **AI Model**  

- The AI is based on **Deep Q-Networks (DQN)**.  
- It uses the **Gym library** to simulate and train in the game environment.  
- The model continuously learns from rewards and penalties to optimize gameplay strategies.  

---

## **Project Goals**  

- Implement **reinforcement learning** to train an AI agent.  
- Allow the AI to **self-learn** by interacting with the game environment.  
- Improve AI performance over time using **trial-and-error learning**.  

---

## **Improvements**  

- There are two ways to implement reinforcement learning:
  1. **First Approach** – The player should reach the goal as soon as possible (**Completed**).
  2. **Second Approach** – The player should collect all gold coins before reaching the goal (**Yet to be done**).

- Further improvements can be made by implementing AI for enemies instead of relying on random movements.

---

## **Work Completed**  

- Developed a fully functional **2D platformer game**.  
- Structured the game environment to be compatible with the **Gym library**.  
- Trained two models for the first approach, and they are working successfully.  

---

## Clone the Repository

First, clone the repository using HTTPS:

```bash
git clone https://github.com/PiyushGhegade/my-platformer-ai.git
cd my-platformer-ai
```

## Setup Instructions

1. **Create a virtual environment** using conda:

    ```bash
    conda create -n myenv python=3.10
    ```

2. **Activate the virtual environment**:

   ```
   conda activate myenv
   ```

4. **Install the dependencies** from `requirements.txt`:

    ```bash
    pip install -r requirements.txt
    ```

5. **Navigate to the code directory**:

    ```bash
    cd code
    ```

## Running the Game
  #### 🔧 Configuration

To play the game manually, make following changes in `settings.py`:
  
  ```python
  control_ai = None
  ```


- **To run the game manually**:

    ```bash
    python run.py manual
    ```

- **To let an AI model play the game**:

    ```bash
    python run.py ai <model_name>
    ```

    Replace `<model_name>` with the name of your trained model file.

  Example:
    ```bash
    python run.py ai ppo_platformwer
    ```

---


