# TrajGen_GAIL

### Introduction
Generative model for urban vehicle trajectories based on Deep Learning 
This repository include implementations of :
 - RNN based trajectory generator (Choi et al. 2018) [not yet]
 - MaxEnt inverse reinforcement learning (Ziebart et al. 2008)
 - Generative Adversarial Imitation Learning (Ho et al. 2016)
 - ShortestPath World (MDP for routing imitations)
 
### Data availability
Due to the public availability issue of taxi data of Gangnam District, it is not possible to upload the taxi data. 

The available data is a virtual vehicle trajectory data generated by AIMSUN shortest path routing engine.

Below figure shows the network configuration
<img src="./img/network.jpg" width="400" height="400">


### Requirements
python>3.7

required python packages in requirement.txt

<Bash terminal>
 
```bash
pip install -r requirement.txt
```


### How to Run

<Bash terminal>

```bash
python scripts/
```

