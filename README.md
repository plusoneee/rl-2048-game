# RL: 2048-game

This game's environment is from [gym-2048](https://pypi.org/project/gym-2048/) which implements the classic grid game 2048 for OpenAI gym environment.

## Getting Started
* The project use `PyTorch` to implement, make sure `torch` is installed.

### Requirements
* Install `Python3` & `pip` first. 
* Then, run:
```
pip install -r requirements.txt
```

## Source Code Structure

* `experience_replay` implements the Replay Memory.
* `dueling_dqn` defines the Dueling DQN architecture and its parameters.
* `agent` implements the what the agent could do (like get action, compute loss, save or load model.)
* `main` glues everything together to implement the Deep Q-Learning algorithm.

## Run Training

**(Optional) set various parameters.**
* For example, you can change the `MAX_EPISIDOSE`, `MAMORY_SIZE` or `BATCH_SIZE` in `main.py`.

```
python main.py
```
