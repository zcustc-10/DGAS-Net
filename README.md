# DGAS-Net
This is a Pytorch implementation of Dual Geometry Learning and Adaptive Sparse Attention for Point Cloud Analysis

## Environment Setup 
Python >= 3.7 

CUDA == 11.3 

PyTorch == 1.10.0 

## Install
```bash
source install.sh
```

## Train
```bash
CUDA_VISIBLE_DEVICES=0 python examples/segmentation/main.py --cfg cfgs/s3dis/DGAS-Net.yaml
```