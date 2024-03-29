# Multi-Agent Reinforcement Learning for UAV Fleet Management
The code for this project isn't made public yet as the project is still in progress.

# Abstarct:
The usage of UAVs has increased dramatically in the past few years due to the technological
advancements that made them cheaper and more affordable. These UAVs are put to use in
almost all domains be it engineering, military, or civilian surveys because of their
capabilities and ease of usage. Most of the applications out in the real world require multiple
drones to be used and this led to an increase in the need of efficient and robust systems to
control and coordinate a multitude of UAVs at the same time.

This project proposes a novel Multi-agent Reinforcement Learning system to control and
coordinate a fleet of UAVs to survey a region of interest optimally by avoiding the inter-
section between the Field of Views of the UAVs and maximizing the coverage. The model
takes input the present coordinates of the drones present in the environment and outputs
the next state coordinates in order to achieve the maximum coverage of the field of interest.
A centralized learning and decentralized implementation strategy is followed in order to make
use of all the available data during training. The system is trained on the AirSim simulator.



![FOV of Drones](Images/FOV_OF_ALL_DRONES.png)




