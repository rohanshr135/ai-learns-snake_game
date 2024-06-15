Description
This project focuses on training an AI agent to play the classic Snake game using reinforcement learning. The agent learns to navigate the game board, collect food, and avoid collisions. Here’s how you can set up the environment and install the required packages:
## Setup Instructions

1. **Clone the repository:**

    ```sh
    git clone https://github.com/rohanshr135/Recommender-system.git
    cd Recommender-system
    ```

2. **Create and activate a virtual environment:**

    - For Windows:
      ```sh
      conda create -n pygame_env
      conda activate pygame_env
      ```
   

3. **Install the required packages:**

    ```sh
    pip install -r requirements.txt
    ```
4. ** or use this commands
   ```sh
    pip install pygame
    pip3 install torch torchvision --index-url https://download.pytorch.org/whl/cpu
    pip install matplotlib ipython
    ```
5. **Run the game and allow it to train for some time:**

    ```sh
    python agent.py
    ```

## Notes

- Ensure you have Python installed on your system. You can download it from [python.org](https://www.python.org/).
