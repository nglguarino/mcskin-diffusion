# Minecraft Skin Generator

[WIP] Simple diffusion model for generating Minecraft skins. It's built using PyTorch and is trained on a large dataset of 900k+ Minecraft skins.

First run:
trained for 50 epochs on 10k images.

![Skin generated from the first training](assets/diffuser.png)

## Problem Diagnosis
The symptoms (gradients and random pixels) suggest the model is undertrained.

Fixes to try:
* Experiment with training settings 
* Increase subset size
* Increase the model's capacity
* Add self-supervised context