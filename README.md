# Code to follow with RL-Lecture-2022


# 1. Environment Setup

```
1. Install the conda by following the instructions:
https://docs.conda.io/projects/conda/en/latest/user-guide/install/

2. Setup the environment
This will be an isolated environment with compatible packages to work properly.

$conda create -n rlenv python=3.7

$conda activate rlenv

$pip install tensorflow==1.14.0

$pip install keras==2.2.0

$pip install keras-rl

$pip install jupyter

$pip install gym

$pip install h5py<3.0.0

```

# 2. Random actions on Cartpole
We will use the cartpole environment from OpenAI Gym to do random actions.


# Deleting the Environment
```
conda remove --name rlenv --all
```
