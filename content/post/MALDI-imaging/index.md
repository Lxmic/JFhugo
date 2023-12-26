---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "MALDI Imaging"
subtitle: ""
summary: "How to use MALDI-TOF Imaging equipment **rapifleX MALDI Tissuetyper** from BRUKER company."
authors: 
  - admin
tags: MALDI
categories: Method
date: 2023-12-26T19:47:53+08:00
lastmod: 2023-12-26T19:47:53+08:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: "rapifleX"
  focal_point: "Smart"
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---
## MALDI开始前工作
在样品ITO玻璃板上未喷基质处点标准品（1 ul 多肽标准品和1 ul HCCA matrix混合），通风橱晾干后会自然结晶。用于调教系统及方法。
![Standard](image.png)

## 找到校正方法文件并复制到自己的实验文件夹
每次实验不改原始方法文件，复制到自己文件夹再进行修改。选择`D/Methods/flexControlMethods/RP_600-3200_Da.par`, 复制到自己的新建实验文件夹。

## 切换到上述方法
- 打开flexControl软件，然后file——select Method，选择方法par文件，一般采集方法需要和相应的标准品相匹配。
- 等待有下角的状态由黄变为绿，说明方法载入成功。
![Alt text](image-1.png)
![Alt text](image-4.png)

## 校正仪器，确保测量精度
选择Calibration——Peptidecalibstandard mono（适合m/z 700-4000之间），然后标准品会出现在`Ref.Mass/Da`列里面。
![Alt text](image-3.png)

## 采集标准品的质谱图
- 视野中找到Standard样品，点状白色的结晶就是标准品和matrix的混合物。
![Alt text](image-5.png)
- 十字中心点调至白色样品处，点击`Start`开始开始采集标准品质谱图。瞬间旁边会出现质谱图。
![Alt text](image-6.png)
- 点击`Automatic assign`,自动对齐标准品和list理论值的峰图，只要Err在正负10之间就说明仪器正常。
![Alt text](image-7.png)
## 保存校正后的方法
- 点击`Apply`
- File——Save method

## 然后选择图像采集方法
- 复制图像采集方法`Imaging_Lipid_20µm.par`到自己文件夹
- 载入该图像采集方法
![Alt text](image-8.png)
![Alt text](image-9.png)
- 找到样品，先采集一针，根据丰度，可以调整激光强度。10^5左右的intensity就差不多。
![Alt text](image-10.png)
- 然后保存方法。

## 设置采集分辨率
- 一般根据你的需要进行调整，分辨率越高，采集时间越久。也就是两次激光距离越短，激光次数越多。
![Alt text](image-11.png)
- 再次保存方法。

## 然后打开图像采集软件——fleximaging
- 打开软件，按右边的步骤一步步进行下去
![Alt text](image-12.png)
![Alt text](image-16.png)
- 选择new imaging run，点击ok
![Alt text](image-13.png)

![Alt text](image-14.png)
- 命名和选择结果保存文件夹
![Alt text](image-15.png)
- 设置分辨率，和优化过的方法文件
![Alt text](image-17.png)

- 选择baseline
![Alt text](image-18.png)

- 将之前扫描的样品位置照片放置此次实验文件夹下面，这样才能在这一步识别。否则不会出现。
![Alt text](image-19.png)
这样是出现正常的
![Alt text](image-20.png)

- 需要对齐flexControl和flexImaging，使得两边的位置一致，这样才能采集到正确的图。一般需要对应3-4个点。
![Alt text](image-21.png)
MTP板子放入机器前，需要在盖子上做好标记，这样能和flexcontrol软件的384个圆点进行对应，根据点击圆点坐标（C9，定位到相应的位置），较为快速的定位样品所在位置。
![Alt text](image-22.png)
![Alt text](image-23.png)

- 用矩形工具或者无规则工具将需要采集的样品框起来。需要采集几个就框几个。
![Alt text](image-24.png)

- 然后开始run，点击确定就可以，此时可能会卡顿，耐心等待。
![Alt text](image-25.png)

- 可以看到采集所需要的时间。分辨率高，且样品数多，就会需要几个小时，甚至几天的时间。
![Alt text](image-27.png)

- 可以停止，进行调整，然后再次run
![Alt text](image-28.png)

## 数据分析
- 使用SCiLS Lab软件进行数据分析，首先打开软件。
![Alt text](image-29.png)

- 选择new，然后选择TOF,然后next
![Alt text](image-30.png)

- 添加flexImaging采集的`.mis`数据文件。
![Alt text](image-31.png)

- 数据转换
![Alt text](image-32.png)
出现样品的轮廓图
![Alt text](image-33.png)
- Next后，会出现总的图谱
![Alt text](image-34.png)

- 然后`Import`，选择文件夹存放，然后开始走进度条。
![Alt text](image-36.png)

![Alt text](image-35.png)

- 进度条结束后，就会出现这样的界面。可以选择你感兴趣的m/z。
![Alt text](image-37.png)

![Alt text](image-38.png)