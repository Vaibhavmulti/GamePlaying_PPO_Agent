# Implementation of Proximal Policy Optimization(PPO)

## Get started

Prerequisites:
```
conda create --name ppo_env python=3.9 -y
conda activate ppo_env
```


Install dependencies:
pip 
```
pip install -r requirements.txt
```

Train agents:
```
python ppo.py
```

Train agents with experiment tracking:
```
python ppo.py --track --capture-video
```

### Atari
Train agents:
```
python ppo_atari.py
```
Train agents with experiment tracking:
```
python ppo_atari.py --track --capture-video
```
