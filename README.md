# deeplearning-questions
主要针对面试中遇到的常见问题进行总结以及简略回答。

## 人脸检测
## 人脸识别
## 深度学习
## 手机端模型部署
## 服务端模型部署
## 模型优化
## 目标检测
### 1.anchor具体坐标方法，并简述它在faster-RCNN，V3，SSD有什么区别
### 1.深度学习检测小目标常用的方法
### two-stage training:
* 第一阶段：在coco数据集训练的checkpoints上加载darknet53——body部分的weights，训练yoloV3的head部分，使用较大的学习率比如0.001，直到损失降下来
* 第二阶段，加载第一阶段训练的模型，训练整个模型的参数，使用较小的学习率比如0.0001.。
### LOSS NAN ?
* 出现loss nan的情况尽量设置大一点的warm-up-epoch的值，或者小一点的学习率，多试几次。如果使用的是one-stage的训练过程，使用adam优化器可能会出现nan的问题，请选择momentum optimizer。
### yolo系列问题
## 数据挖掘以及机器学习方面
## 图像算法方面
### 1.简述三种图像插值方法

### 2.仿射变换有几个自由度，并简述

### 3.过拟合和欠拟合分别是什么，如何改善
### 4.1X1卷积和作用
### 5.梯度下降算法你知道哪些，并简述，并别代码。
### 6.常用的边缘提取方法
### 7.常用的插值方法
### 8.常用的图像分割算法

## python基础算法题
## 数据结构题
## leecode
