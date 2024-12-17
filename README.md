# Non-myopic-multi-sensor-multi-Bernoulli-GOSPA-driven-sensor-management
Sensor management code for non-myopic, multi-sensor, multi-Bernoulli GOSPA driven sensor management. Utilising Monte Carlo Tree Search adapted to sensor management and utilising an upper bound on the mean square generalised optimal sub pattern assignment (GOSPA) error to drive the decision making.

This code base is for the centralised approachg to multi-sensor sensor management for multi-Bernoulli (MB) filtering.

The cost function used to drive the decision making is an upper bound on the mean square generalised optimal sub pattern assignment (GOSPA) error and the implementation is based on a Monte Carlo Tree Search (MCTS), adapted for the partiallyobservable nature of sensor management.

Each sensor (S1, S2) has the ability to conduct its own decision making, independent of the other andthe ability to share information to a centralised decision making module which jointly optimises the actionstaken by the sensors.

The filtering is centralised, and all sensors operate on shared information from a centralised, multi-Bernoullifiltering loop, with a sequential update step, to avoid unnecessary information loss about the origin ofthe measurements recieved by either sensor.

The codebase is a PMB implementation with the Poisson elements intensity set to zero meaning that it is MB.

This is the code base used for the research and results used in the paper: *Add paper link here if it gets accepted and published.*





The predecessor papers to this codebase are: 

ISIF Fusion 2023 - https://ieeexplore.ieee.org/abstract/document/10224220

IEEE TAES 2024 - https://ieeexplore.ieee.org/abstract/document/10571358 or https://arxiv.org/abs/2405.05815

MFI 2024 - https://ieeexplore.ieee.org/abstract/document/10705781

Google Scholar:  https://scholar.google.com/citations?user=hgzQhO8AAAAJ&hl=en
