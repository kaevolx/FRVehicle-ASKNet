# FRVehicle
## FRVehicle dataset
[BaiduYun](https://pan.baidu.com/s/1KBf6baQoI_1zSOzNkEcEJQ)
code:g7wn
# ASKNet
![main](https://github.com/user-attachments/assets/018d7819-ad64-45e6-8851-ce2b1cba65c5)

## Installation
[MMRotate](https://github.com/open-mmlab/mmrotate) depends on [PyTorch](https://pytorch.org/), [MMCV](https://github.com/open-mmlab/mmcv) and [MMDetection](https://github.com/open-mmlab/mmdetection). Please refer to [Install Guide](https://mmrotate.readthedocs.io/en/latest/install.html) for more detailed instruction. Below are quick steps for installation.

```python
conda create --name openmmlab python=3.8 -y
conda activate openmmlab
conda install pytorch==1.8.0 torchvision==0.9.0 cudatoolkit=10.2 -c pytorch
pip install -U openmim
mim install mmcv-full
mim install mmdet
git clone https://github.com/zcablii/Large-Selective-Kernel-Network.git
git clone https://github.com/kaevolx/FRVehicle-ASKNet.git
cd FRVehicle-ASKNet
cp -r /asknet/ /Large-Selective-Kernel-Network/lsknet/configs
cp -r /mmrotate/ /Large-Selective-Kernel-Network/lsknet/
cd Large-Selective-Kernel-Network
pip install -v -e .
```
## BibTeX
```python
@Article{rs17030407,
AUTHOR = {Wang, Zhenyu and Xiong, Lu and Yu, Zhuoping},
TITLE = {An Asymmetric Selective Kernel Network for Drone-Based Vehicle Detection to Build a High-Accuracy Vehicle Trajectory Dataset},
JOURNAL = {Remote Sensing},
VOLUME = {17},
YEAR = {2025},
NUMBER = {3},
ARTICLE-NUMBER = {407},
URL = {https://www.mdpi.com/2072-4292/17/3/407},
ISSN = {2072-4292},
DOI = {10.3390/rs17030407}
}
```

## Acknowladgement
Please also support the representation learning work on which this work is based:

LSKNet：[LSKNet: A Foundation Lightweight Backbone for Remote Sensing](https://doi.org/10.1007/s11263-024-02247-9)  
        &emsp;&emsp;&emsp;&emsp;[Large Selective Kernel Network for Remote Sensing Object Detection](https://openaccess.thecvf.com/content/ICCV2023/papers/Li_Large_Selective_Kernel_Network_for_Remote_Sensing_Object_Detection_ICCV_2023_paper.pdf)  
        &emsp;&emsp;&emsp;&emsp;[code](https://github.com/zcablii/LSKNet)
