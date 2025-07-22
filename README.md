# Snake Game with Reinforcement Learning

This repository contains a classic Snake game implemented in Python using Pygame, with a focus on reinforcement learning integration for AI training and experimentation.

## Features
- Classic Snake gameplay with grid-based movement
- Apple generation and collision logic
- Score tracking and game over conditions
- Modular code structure for easy extension
- Ready for reinforcement learning experiments (see `snakeenv.py` and notebooks)

## File Structure
```
main.py                # Main game loop and logic using Pygame
snakeenv.py            # Snake environment for RL (OpenAI Gym style)
snake_rl.ipynb         # Jupyter notebook for RL training and experiments
Untitled.ipynb         # Additional notebook (possibly for prototyping)
Training/
  Saved_Models.zip     # Saved RL models
  Logs/                # Training logs (TensorBoard events)
```

### Prerequisites
- Python 3.8+

### Installation
1. Clone the repository:
   ```
   git clone https://github.com/subhradip32/Snake_RL_AI.git
   cd Snake_RL_AI
   ```
2. Install dependencies:
   ```
   pip install -r requirements.txt
   ```

### Running the Game
To play the classic Snake game:
```bash
python main.py
```

### Reinforcement Learning
- Use `snakeenv.py` and the provided notebooks to train and evaluate RL agents.
- Training logs and saved models are in the `Training/` directory.

## Requirements
See `requirements.txt` for the full list.


## License
This project is licensed under the MIT License.
