# Sustainable Approach to Surface Polishing of 3D Printed Components using Reinforcement Learning

Includes the python code to implement Advantage Actor-Critic algorithm for surface polishing experiment on Ti-6Al-4V metal sample.

## Description
With the aid of state-of-the-art reinforcement learning algorithms, this project aims at improving the decision making mechanism for surface polishing of 3D printed components. The model polishing environment is designed as an MDP to minimize the power consumption while reaching the desired surface roughness. The state variable is continuous and defined by the average roughness parameter, Sa; the action variables are discrete and are defined by the applied force (F) and Relative rotational speed (v) between the workpiece and the polishing pad; the reward is defined by the power consumed by the polishing machine. 
 

## Getting Started

### Dependencies

* The file is in IPYNB format created using Jupyter Notebook
* Required libraries are Torchvision, Scikit-learn


## Note
This repository also includes an Asynchronous advantage actor-critic implementation for the surface polishing environment. However, the results are sub-optimal and requires further tuning of the network architecture and hyperparameters.


## Authors

Lekhapriya Dheeraj Kashyap (lekha.dk@tamu.edu) 
Adithyaa Karthikeyan (adithyaa1996@tamu.edu)


## References
* Template code for A2C using pytorch: https://github.com/zzzxxxttt/pytorch_simple_RL/blob/master/a2c_mtcar.py
* Code for A3C mainly adopted from : https://github.com/philtabor/Youtube-Code-Repository/blob/master/ReinforcementLearning/PolicyGradient/A3C/pytorch/a3c.py
