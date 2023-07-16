## 关于本项目

个人学习用，容易上手，效果可能不是特别好。
项目来源：https://github.com/TCY07/YOLOv1

## 准备工作

### 下载数据集

http://host.robots.ox.ac.uk/pascal/VOC/voc2007/VOCtrainval_06-Nov-2007.tar
http://host.robots.ox.ac.uk/pascal/VOC/voc2007/VOCtest_06-Nov-2007.tar

### 下载预训练模型

下载resnet50的预训练模型：

https://download.pytorch.org/models/resnet50-19c8e357.pth

在train.py里面设置你的预训练模型路径

从预训练模型开始进行训练：

## 训练模型

>python train.py

继续训练已有的模型：

>python train.py --resume

## 进行预测
>python predict.py --image_name [filename]
>


