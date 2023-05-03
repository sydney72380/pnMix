# pnMix

The official PyTorch implementation of the paper XXXXXXXXXXXXXXXXXX.

# Overview
This repo contains the PyTorch implementation of pnMix, described in the paper XXXXXXXXXXXXXX.  
Due to the paper has not been accepted by any journal yet, we are not able to release the related source code for now, but only the pretrained models. We will continue to release the related source code after the paper has been accepted by a journal.

# Installation
Ubuntu 20.04 LTS  
Python 3.8 (Anaconda is recommended)  
CUDA 12  
PyTorch 1.13  

# Perform experiments on ImageNet dataset
| method | T1 | Pretrained Model
| ---- | ---- | ----
| +pnMixESKD | 79.19 | [baidu cloud](链接：https://pan.baidu.com/s/1GHcRJO4ebPu21vop3vrBXw?pwd=a3m1 提取码：a3m1)

# Perform experiments of object detection on VOC
| method | map | Pretrained Model
| ---- | ---- | ----
| +pnMixESKD | 83.66 | [baidu cloud](链接：链接：https://pan.baidu.com/s/1w5WVHUw8U9t5AtGPNN48EQ?pwd=9xsz  提取码：9xsz)

# Perform experiments of object detection on COCO
| method | map | Pretrained Model
| ---- | ---- | ----
| +pnMixESKD | 41.81 | [baidu cloud](链接：链接：https://pan.baidu.com/s/1w5WVHUw8U9t5AtGPNN48EQ?pwd=9xsz  提取码：9xsz)


# Perform experiments of semantic segmentation on voc
Except for pnMixESKD, all the imagenet pre-trained models we used for training were the official open-source models of the relevant data augmentation methods. We would like to express our gratitude to the authors for their open-source contributions. Perhaps due to the difference in the number of GPUs used, our image segmentation test results on the VOC dataset differ significantly from those of other papers, but the trends of the different methods are consistent. Therefore, we provide our trained image segmentation models for all relevant methods.
| method | mIou | Pretrained Model
| ---- | ---- | ----
| resnet50 | 75.62 | [baidu cloud](链接：链接：https://pan.baidu.com/s/1w5WVHUw8U9t5AtGPNN48EQ?pwd=9xsz  提取码：9xsz)
| +mixup | 73.26 | [baidu cloud](链接：链接：https://pan.baidu.com/s/1w5WVHUw8U9t5AtGPNN48EQ?pwd=9xsz  提取码：9xsz)
| +manifoldMixup | 73.48 | [baidu cloud](链接：链接：https://pan.baidu.com/s/1w5WVHUw8U9t5AtGPNN48EQ?pwd=9xsz  提取码：9xsz)
| +cutmix | 73.31 | [baidu cloud](链接：链接：https://pan.baidu.com/s/1w5WVHUw8U9t5AtGPNN48EQ?pwd=9xsz  提取码：9xsz)
| +cutmix+moex | 72.90 | [baidu cloud](链接：链接：https://pan.baidu.com/s/1w5WVHUw8U9t5AtGPNN48EQ?pwd=9xsz  提取码：9xsz)
| +cutout | 73.17 | [baidu cloud](链接：链接：https://pan.baidu.com/s/1w5WVHUw8U9t5AtGPNN48EQ?pwd=9xsz  提取码：9xsz)
| +mixSKD | 77.70 | [baidu cloud](链接：链接：https://pan.baidu.com/s/1w5WVHUw8U9t5AtGPNN48EQ?pwd=9xsz  提取码：9xsz)
| +pnMixESKD | 77.72 | [baidu cloud](链接：链接：https://pan.baidu.com/s/1w5WVHUw8U9t5AtGPNN48EQ?pwd=9xsz  提取码：9xsz)
