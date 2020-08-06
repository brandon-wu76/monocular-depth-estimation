# Monocular Depth Estimation
![](https://github.com/brandon-wu76/monocular-depth-estimation/blob/master/demo_depth.gif?raw=true)
## Introduction
This is a custom implementation of a depth map generator using MobileNet, inspired by the paper [High Quality Monocular Depth Estimation via Transfer Learning (arXiv)](https://arxiv.org/abs/1812.11941). The model takes in 640x480 images and produces a corresponding depth map of the same resolution. The model was trained for two hours on a Nvidia Tesla P100 in Google Colab on the [DIML dataset](https://dimlrgbd.github.io/) with batch size 32.

## Pre-Trained Model
[You can find the demo_checkpoint.pth file here](https://drive.google.com/file/d/1rv4911vZFFTGitOQwwkE42tWVUr8YVpr/view?usp=sharing)

## Training
To get started, you'll need to download the DIML dataset from the link above and adjust the filepaths for the dataset and pretrained model within train_model.ipynb. This file contains the data processing and training code.
