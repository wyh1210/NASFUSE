# Introduction
This is the implementation of the paper [SMoA: Searching a Modality-Oriented Architecture for Infrared and Visible Image Fusion](https://ieeexplore.ieee.org/abstract/document/9528046).
# Requirements
    python >= 3.6, pytorch == 1.7, torchvision == 0.8
# Datasets
You can download the datasets [here].
# Test
    python test.py
# Train from scratch
## step 1:
    python train_search.py
## step 2:
Find the string which descripting the searched architectures in the log file. Copy and paste it into the genotypes.py, the format should consist with the primary architesture string.
## step 3:
    python train.py
