# cGAN: From paper to Code

### This is an implementation of the original CycleGAN paper.
https://arxiv.org/abs/1703.10593

## Goals:
The main goal of this repository was to be able to create the GAN discribed in the paper using PyTorch.

The paper describes a cycle GAN which takes in unpaired images from one domain and applies a cross-domain mapping transforming one image into the other. The dataset used in this particular network contained images from zebras and horses where the zebra would be changed to a horse in its orginal image or vice versa. This unpaired mapping is significant because it learns the unlying distribution of the domain and does not require labeling which can be extremely expensive and time consuming.

The reasoning behind this project was for the purpose of practicing taking a research paper and producing actionable code.

## Results:
The Cycle GAN was created successfully with PyTorch. Training took several hours and produced visual results similar to the paper.
