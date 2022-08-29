# Example Filtering & Reward Weigthed Refinement implementation with [ReLAx](https://github.com/nslyubaykin/relax)

This repository contains an [implementation](https://github.com/nslyubaykin/relax_frwr_example/blob/master/frwr_tutorial.ipynb) of filtering & reward weigthed refinement (FRWR aka PDDM) with ReLAx.

FRWR actor was trained on HalfCheetah-v2 Mujoco Gym environment for 50k env-steps. 

The graph of average return vs training step is shown below (`batch_size=5000`):

![frwr_training](https://github.com/nslyubaykin/relax_frwr_example/blob/master/frwr_training.png)

The graph below shows actual rewards vs rewards fitted with environment model:

![frwr_model_rews](https://github.com/nslyubaykin/relax_frwr_example/blob/master/frwr_model_rews.png)

__Resulting Policy__:

https://user-images.githubusercontent.com/67604207/187187405-7d5626dc-f205-47fc-9204-a20887c51e7e.mp4
