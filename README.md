# pytorch-unet

#### 介绍
pytorch搭建自己的unet网络，训练自己的数据集，对焊缝进行识别。
#### 软件架构
pythorch

#### 使用说明

1.  数据集原图存放地址：data/JPEGImages   mask存放地址：data/SegmentationClass
2.  直接运行train.py,其中train_image文件夹存储的是训练过程中的效果图
3.  params文件夹保存权重
4.  测试test.py，用来测试图片，测试结果存储在result文件夹中
