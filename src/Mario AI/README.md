## Build an Mario AI Model with Python

Link: https://www.youtube.com/watch?v=2eeYqJ0uBKE

Using PPO (Proximal Policy Optimization) to train a Mario AI model to play Super Mario Bros. 1-1.
https://stable-baselines3.readthedocs.io/en/master/modules/ppo.html



## Setup: Pre-requirements
### Gym-Super-Mario-Bros
Installing gym-super-mario-bros
https://pypi.org/project/gym-super-mario-bros/

pip install on command prompt using:
pip install gym-super-mario-bros

or you can install it on your juptyer notebook using:
!pip install gym_super_mario_bros==7.3.0 nes_py


### Nes-py
Installing nes-py 8.1.8
https://pypi.org/project/nes-py/

pip install on command prompt using:
pip install nes-py==8.1.8
or just (for latest version)
pip install nes-py

### GYM Open AI
Will also be using 
gym.openai.

### Installing Stable-baselines3
Reinformcement Learning Library
!pip install stable-baselines3[extra]

### PyTorch
https://pytorch.org/get-started/locally/
PyTorch Build: Stable (Latest Version)
Your OS: Windows
Package: Pip
Language: Python
Compute Platform: CUDA (GPU accelaration running) if you have cuda installed on your computer. If not, then CPU.

Run this Command: pip3 install torch torchvision torchaudio
or
pip install torch===1.7.1 torchvision===0.8.2 torchaudio===0.7.2 -f https://download.pytorch.org/whl/torch_stable.html

### To run the model
go to your command prompt on dir where the latest PPO is stored, then run the command:
tensorboard --logdir=.

then copy the link (ex: http://localhost:6006/) and paste it on your browser.

this allows you to view your training progress


## Comments
* Does not explain how PPO works
* Does not explain how to train the model
 * How the agent interact with the environment
 * How the agent learns from the environment
 * How the agent choose the best action
 * How it gains reward or looses reward


## Final Model
* It took a day to train on 200,000 steps
* The Model only reached the second or third pipe
* Either the model is not trained enough or the model is not good enough
