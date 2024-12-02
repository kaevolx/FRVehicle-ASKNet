# FRVehicle-ASKNet
## FRVehicle dataset
[BaiduYun](https://pan.baidu.com/s/1KBf6baQoI_1zSOzNkEcEJQ)
code:g7wn
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
cd Large-Selective-Kernel-Network
pip install -v -e .
git clone https://github.com/yuhongtian17/Spatial-Transform-Decoupling.git
cp -r Spatial-Transform-Decoupling/mmrotate-main/* mmrotate/
```

## Acknowladgement
Please also support the representation learning work on which this work is based:

LSKNet：[LSKNet: A Foundation Lightweight Backbone for Remote Sensing](https://doi.org/10.1007/s11263-024-02247-9)  
        &emsp;&emsp;&emsp;&emsp;[LSKNet: A Foundation Lightweight Backbone for Remote Sensing](https://openaccess.thecvf.com/content/ICCV2023/papers/Li_Large_Selective_Kernel_Network_for_Remote_Sensing_Object_Detection_ICCV_2023_paper.pdf)  
        &emsp;&emsp;&emsp;&emsp;[code](https://github.com/zcablii/LSKNet)
