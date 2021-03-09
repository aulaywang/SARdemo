# SARdemo
只是一个用来记录实验的帖子～
## 研究COCO数据集转化为YOLOv3可以处理的格式（2021.3.7）
用到的程序有：coco2voc.py、xml2txtall.py、txtall2txt.py
## 复现FasterRCNN训练的过程（2021.3.9）  
主要还是基于[AI2SARShip](https://github.com/aulaywang/AI2SARShip)的相关内容，有一些改动。  
**复现版本：Ubuntu16.04 + Cuda10.0 + cuDNN7.6.3 + PyTorch1.7.1 + python3.8**  
查阅过的帖子：  
[解决ImportError: cannot import name 'imread' from 'scipy.misc'](https://www.cnblogs.com/gkm0120/p/12925130.html)  
本来想试一下COCO数据集的，不过看了[jwyang](https://github.com/jwyang/faster-rcnn.pytorch/tree/pytorch-1.0)的介绍，耗时是VOC的十倍，而且需要8块GPU，遂放弃。  
