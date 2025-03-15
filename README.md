# 8470: Introduction to Information Retrieval 
# Project: Diffusion Models for Hairstyle Recommendation

This code is originally from the paper "Diffusion Models for Generative Outfit Recommendation" at SIGIR 2024:
> [Diffusion Models for Generative Outfit Recommendation](https://arxiv.org/abs/2402.17279)
> 
> Yiyan Xu, Wenjie Wang, Fuli Feng, Yunshan Ma, Jizhi Zhang, Xiangnan He

## Environment
- Anaconda 3
- python 3.8.13
- torch 2.0.1
- torchvision 0.15.2
- Pillow 9.0.1
- numpy 1.24.4
- transformers 4.32.1
- open-clip-torch 2.20.0
- accelerate 0.20.3
- diffusers 0.18.2
- xformers 0.0.22
- pytorch-fid 0.3.0
- lpips 0.1.4

## Run code
Download the Figaro-1k dataset from [here](https://www.dropbox.com/scl/fi/bkzbwgobxayoaeqohgvrp/Figaro-1k.zip?dl=0&e=7&file_subpath=%2FFigaro-1k%2FOriginal%2FTesting&rlkey=qahueoko45prpzmsadzmus5ga)

## Generated images from Diffusion Denoising Probability Model (DDPM) 
Images are generated from DDPM from this github code: https://github.com/Draw1n/DDPM-Street-Scene-Repaint 

## Model
Use the file "difashion.py"

## Training
Use the file "train.py" for training


