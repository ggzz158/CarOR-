# CarOR-
车牌号识别，基于深度学习的车牌号识别系统，License plate number recognition

[![](https://img.shields.io/badge/Video-%E6%BC%94%E7%A4%BA-yellow)](https://www.bilibili.com/video/BV1Yq4y1V758/)
[![](https://img.shields.io/badge/author-GXW-green)]()

## 详细代码及论文请联系q:844970924
<figure class="half">
    <img src="https://img-blog.csdnimg.cn/dcd87cc31eba4c259f2b058d313007f4.jpg" width="20%" >
</figure>

## 系统介绍
随着21世纪经济全球化的到来，高速度、高效率的生活节奏，使车辆普及成为必然的趋势，交通管理自动化越来越成为亟待解决的问题。车牌是一辆汽车独一无二的信息，因此，对车辆牌照的识别可以作为辨识一辆车最为有效的方法。现代智能交通系统中，车辆牌照识别技术是计算机视觉与模式识别技术在交通领域应用的重要研究课题之一，是实现交通管理能够智能化的重要环节，其任务是分析、处理汽车图像，自动识别汽车牌号。LPR系统中的两个关键子系统是车牌定位系统和车牌字符识别系统。整个处理过程分为预处理、边缘提取、车牌定位、字符分割、字符识别五大模块，其中字符识别过程主要由以下3个部分组成：
(1)正确地分割文字图像区域；
(2)正确的分离单个文字；
(3)正确识别单个字符。
现代化交通系统不断提高的快节奏，将对车牌定位的准确率和实时性提出更高的要求，因而进一步加深车牌定位的研究是非常有必要的。
## 本系统采用方法
本系统首先采用opencv和矩形特征对车牌的位置进行确定，之后对于车牌上的汉字、字母及数字进行分割，将分割后的图像，利用实现训练好的字符模型，确定具体的车牌号。
## 数据集介绍
本系统所用数据集为网络公开的车牌号字符数据集
[车牌号数据集CCPD](https://blog.csdn.net/qq_31261509/article/details/95509572)
## 系统展示
### 1、首页![系统首页](https://img-blog.csdnimg.cn/e9c12d940e7140bdb38e765fa0743369.png?x-oss-process=image/watermark,type_ZHJvaWRzYW5zZmFsbGJhY2s,shadow_50,text_Q1NETiBA6L-Z5Liq5ZCN5a2X5aW96K6w,size_20,color_FFFFFF,t_70,g_se,x_16)
### 2、读取图片
![读取图片](https://img-blog.csdnimg.cn/4123524d76954240a78ddabf132f04e8.png?x-oss-process=image/watermark,type_ZHJvaWRzYW5zZmFsbGJhY2s,shadow_50,text_Q1NETiBA6L-Z5Liq5ZCN5a2X5aW96K6w,size_20,color_FFFFFF,t_70,g_se,x_16)
### 3、车牌边界检测
![车牌边界检测](https://img-blog.csdnimg.cn/c58216a76102474289da2cbc1ad5c391.png?x-oss-process=image/watermark,type_ZHJvaWRzYW5zZmFsbGJhY2s,shadow_50,text_Q1NETiBA6L-Z5Liq5ZCN5a2X5aW96K6w,size_20,color_FFFFFF,t_70,g_se,x_16)
### 4、车牌图像分割
![车牌图像分割](https://img-blog.csdnimg.cn/4d610a0fb39140a48781b6d9f3b5c1b6.png?x-oss-process=image/watermark,type_ZHJvaWRzYW5zZmFsbGJhY2s,shadow_50,text_Q1NETiBA6L-Z5Liq5ZCN5a2X5aW96K6w,size_20,color_FFFFFF,t_70,g_se,x_16)
### 5、车牌号识别
![车牌号识别](https://img-blog.csdnimg.cn/e5f452afc6714f5cbeb7b1d1844732b8.png?x-oss-process=image/watermark,type_ZHJvaWRzYW5zZmFsbGJhY2s,shadow_50,text_Q1NETiBA6L-Z5Liq5ZCN5a2X5aW96K6w,size_20,color_FFFFFF,t_70,g_se,x_16)
