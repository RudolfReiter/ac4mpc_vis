# Welcome to the project page of "AC4MPC: Actor Critic Reinforcement Learning for Model Predictive Control"

This work is related to an IEEE journal submission by Rudolf Reiter, Andrea Ghezzi, Jasper Hoffmann, Katrin Baumgärtner, Robert McAllister and Moritz Diehl.

## Comparison of Control Algorithms
The following simulations show, how the AC4MPC-RTI outperforms an reinforcement learning (RL) algorithm and a standard nonlinear model predictive controller (NMPC) on an autonomous driving overtaking task. NMPC is prone to get stuck into local minima and the RL agent performs considerably suboptimal. The RL agent was trained by soft actor critic learning in 10 Million randomized simulations. The actor and the critic network are used within AC4MPC-RTI as initial guess and terminal value function. The NMPC and the AC4MPC-RTI have a horizon length of 30 and a discretization time of 0.1 seconds. The vehicle parameters are taken from the DevBot 2.0 (roborace.com). Further details can be found in the related submission. 
<br />

<iframe width="1560" height="519" src="https://www.youtube.com/embed/rKVXq3VkC9o?rel=0&modestbranding=1&autoplay=1&loop=1&controls=0" title="Autonomous Driving Simulation 1: Comparison of RL, MPC and AC4MPC" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
<br />

<iframe width="1560" height="519" src="https://www.youtube.com/embed/7_xTmU4gOKc?rel=0&modestbranding=1&autoplay=1&loop=1&controls=0" title="Autonomous Driving Simulation 2: Comparison of RL, MPC and AC4MPC" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
<br />

<iframe width="1560" height="519" src="https://www.youtube.com/embed/pwMVS6dlFMs?rel=0&modestbranding=1&autoplay=1&loop=1&controls=0" title="Autonomous Driving Simulation 3: Comparison of RL, MPC and AC4MPC" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
<br />

<iframe width="1560" height="519" src="https://www.youtube.com/embed/oTr-dbKaJ8s?rel=0&modestbranding=1&autoplay=1&loop=1&controls=0" title="Autonomous Driving Simulation 4: Comparison of RL, MPC and AC4MPC" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
