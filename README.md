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

# Perform experiments on cifar100 dataset
| method | T1 | Pretrained Model
| ---- | ---- | ----
| +pnMixESKD+shakedrop | 13.08 | [baidu cloud](链接：https://pan.baidu.com/s/1sxE9uc4xCzkYEhiAuUZijA?pwd=4trp  提取码：4trp)

# Perform experiments of object detection on VOC
| method | mAP | Pretrained Model
| ---- | ---- | ----
| +pnMixESKD | 83.60 | [baidu cloud](链接：https://pan.baidu.com/s/1wdEf6hvzn9_exC8nk8z7vg?pwd=wcqx  提取码：wcqx)

# Perform experiments of object detection on COCO
| method | mAP | Pretrained Model
| ---- | ---- | ----
| +pnMixESKD | 41.81 | [baidu cloud](链接：https://pan.baidu.com/s/1aWjLAd6Z2ZAb_pS125w7qA?pwd=wdwx  提取码：wdwx)


# Perform experiments of semantic segmentation on voc
Except for pnMixESKD, all the imagenet pre-trained models we used for training were the official open-source models of the relevant data augmentation methods. We would like to express our gratitude to the authors for their open-source contributions. Perhaps due to the difference in the number of GPUs used, our image segmentation test results on the VOC dataset differ significantly from those of other papers, but the trends of the different methods are consistent. Therefore, we provide our trained image segmentation models for all relevant methods.
| method | mIoU | Pretrained Model
| ---- | ---- | ----
| resnet50 | 75.62 | [baidu cloud](链接：https://pan.baidu.com/s/13a81BTeKpz5tPIxFPjpnqA?pwd=5w2x  提取码：5w2x)
| +mixup | 73.26 | [baidu cloud](链接：https://pan.baidu.com/s/1VHzczq32BEPmOusZcKoW-A?pwd=bl1x  提取码：bl1x)
| +manifoldMixup | 73.48 | [baidu cloud](链接：https://pan.baidu.com/s/1lQyUaZtmpEgMMWhTNNfiMQ?pwd=7qny  提取码：7qny)
| +cutmix | 73.31 | [baidu cloud](链接：https://pan.baidu.com/s/1ygMMzlWt30Gy9d4PVTIpOg?pwd=9m2y  提取码：9m2y)
| +cutmix+moex | 72.90 | [baidu cloud](链接：https://pan.baidu.com/s/1IMP6gVMjbb0k_8MTDQBLmQ?pwd=e84g  提取码：e84g)
| +cutout | 73.17 | [baidu cloud](链接：https://pan.baidu.com/s/1kihOQW2MikI6anGy2z4eNQ?pwd=0b0n  提取码：0b0n)
| +mixSKD | 77.70 | [baidu cloud](链接：https://pan.baidu.com/s/1U6uOPChihhpi9ebNaYoVVQ?pwd=1h00  提取码：1h00)
| +pnMixESKD | 77.72 | [baidu cloud](链接：https://pan.baidu.com/s/1DXovTanTMDOq8UwQRmidNQ?pwd=whle  提取码：whle)
