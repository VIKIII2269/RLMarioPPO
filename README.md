
![NarrowUnselfishAmbushbug](https://user-images.githubusercontent.com/85488433/227931428-1c1724e5-2e41-49d8-bd6a-b11beb879d8a.gif)


# RLMarioPPO

RLMarioPPO stands for "Reinforcement Learning Mario Proximal Policy Optimization." This is a reinforcement learning algorithm used to train artificial intelligence agents to play Super Mario Bros games automatically.

## Overview

RLMarioPPO utilizes the Proximal Policy Optimization (PPO) algorithm, a policy optimization technique in the context of reinforcement learning. The goal is to maximize the rewards obtained by intelligent agents in a given environment or task. In the context of RLMarioPPO, this algorithm optimizes the playing strategies of Super Mario Bros. agents to achieve higher scores or specific objectives within the game.

## Features

- **Reinforcement Learning**: Implements PPO for policy optimization.
- **Game Automation**: Trains agents to play Super Mario Bros games automatically.
- **Reward Maximization**: Aims to maximize in-game rewards and achieve specific goals.

## Installation

To get started with RLMarioPPO, follow these steps:

1. Clone the repository:
    ```sh
    git clone https://github.com/VIKKIII2269/RLMarioPPO.git
    cd RLMarioPPO
    ```

2. Create and activate a virtual environment:
    ```sh
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. Install the required dependencies:
    ```sh
    pip install -r requirements.txt
    ```

## Usage

To train the RLMarioPPO agent, run:
```sh
python train.py
```

To evaluate the trained agent, run:
```sh
python run.py
```

## File Structure

- `train.py`: Script to train the RLMarioPPO agent.
- `run.py`: Script to evaluate the trained agent.
- `ppo.py`: Contains the implementation of the PPO algorithm.
- `environment.py`: Sets up the Super Mario Bros game environment.
- `models/`: Directory to save and load trained models.
- `utils/`: Utility functions and helper scripts.

## Requirements

- Python 3.7+
- NumPy
- TensorFlow / PyTorch
- OpenAI Gym
- gym-super-mario-bros

Install the dependencies using:
```sh
pip install numpy tensorflow gym gym-super-mario-bros
```

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements

- OpenAI for the PPO algorithm.
- The gym-super-mario-bros library for the game environment.

