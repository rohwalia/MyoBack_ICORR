# MyoBack model: Simulation of a neuromusculoskeletal model of the back with an exoskeleton

[Rohan Walia]()<sup>1</sup>,
[Morgane Billot]()<sup>1</sup>,
[Kevin Garzon-Aguirre]()<sup>1</sup>,
[Swathika Subramanian]()<sup>2</sup>,
[Huiyi Wang]()<sup>1</sup>
[Mohamed Irfan Refai]()<sup>2</sup>
[Guillaume Durandau]()<sup>1</sup>

<sup>1</sup>McGill University
<sup>2</sup>University of Twente

<img src="MyoBack_repo.png" alt="MyoBack" width="30%"/>

## Overview
MyoBack is a human back model part of the MyoSuite framework, derived from a physiologically accurate OpenSim model. MyoBack was validated empirically by integrating a passive back exoskeleton in simulation and comparing forces exerted on the back with values from experimental trials.

MyoBack model can be applied to a range of contexts, including both passive and active exoskeletons, or even to entirely different use cases. To give a basis, we have added an example where a RL agent is trained to control the muscles in the model to balance it and keep it from leaning forward.

The folder [rl_example](./rl_example) includes a sample training script and baseline with which the MyoBack model developed can be tested. Use the instructions below to set up and run the training scripts or load the baseline on your own machine.

## Installation
We recommend installing MyoConverter via conda / mamba if you're running Linux (tested on Ubuntu 20.04 & 22.04).
