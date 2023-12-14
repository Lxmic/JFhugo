---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "H7650 Transmission Electron Microscope Simple Operation Guide"
subtitle: ""
summary: "TEM tutorial"
authors: []
tags:
  - TEM
categories: Method
date: 2023-12-12T15:10:39+08:00
lastmod: 2023-12-12T15:10:39+08:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: "TEM H7650"
  focal_point: "Smart"
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---
{{< toc >}}

## 操作前步骤
1. 在每次操作的开始阶段，老师首先会教使用者设置照片的存盘路径（首次教学后，以后自己设置）。
2. 然后，老师将样品装进电镜并点亮灯丝（始终老师操作）。

## 基本的按钮和电脑界面
### <font color=orange>电镜操作所涉及的5个按钮（只有5个哦）</font>
- 电镜左边面板有如下3按钮：
  - <font color=red>1-MAG</font>——用于调整放大倍数；
  - <font color=red>2-BRIGHT</font>——用于调整亮度；
  - <font color=red>3-STAGE X</font>——用于水平方向移动切片
![三个按钮](<图片 1.jpg>)

- 电镜右边面板有如下2个按钮：
  - <font color=red>4-STAGE Y</font>——用于垂直方向移动切片；
  - <font color=red>5-FOUS</font>——用于调焦，使图像清晰；

![2个按钮](<图片 2.jpg>)

### <font color=orange>操作台右边的电脑是电镜的电脑，仅有两处跟使用者相关</font>
- 显示样品放大倍数，下图中<font color=red>7.0k</font>表示放大7000倍，使用`1-MAG`键调节。
![倍数](image.png)
- 该电镜的样品杆可以一次性放进去3个样品，在“<font color=red>Stage control</font>”这个窗口的“<font color=red>Holder</font>”菜单下面的“<font color=red>Specimen No</font>.”里面可以选择要观察的样品。
{{% callout warning %}}
在放样品时，一定要跟老师确认好样品的位置（1,2,3各自是什么样品），确保得到的图片与自己样品名是对应的。
{{% /callout %}}
![样品名字](image-1.png)

### 操作台左边的电脑是CCD（数码相机）的电脑，可以实时成像、拍照以及保存照片。
- 锤子和扳手图标，可以设置保存的相关参数。
![保存参数](image-2.png)

- 点击上面图标，显示如下<font color=tomato>Global Info</font>界面。在“**Global Info**”下面的“<font color=red>Save Numbered</font>”里面可以看到保存照片路径。
![设置界面](image-3.png)

{{% callout note %}}
老师会在观察开始前教你设置好存盘路径: 
1. 我们应该在`1111nongxueyuan\fangpengxiang\`文件夹下，新建自己的个人文件夹HQY。
2. 在自己文件夹下继续新建本次实验的文件夹，例如`20231213-MGfruit`
{{% /callout %}} 

  - 点击Browse, 选择本次实验的文件夹“<font color=red>20231213-MGfruit</font>”，之后的照片都会保存在这个文件夹。
![选择路径](image-4.png)

  - 此外，该页面还有一个<font color=red>Next Index</font>选项，它的作用是让你的照片可以待上序号。**例如，将其设置为1，照片名字后面会从1开始命名。**

  - 在Global Info页面的<font color=red>Session info</font>中，在General的Specimen中，需要填写你自己的样品名，当你在电镜的电脑里面换了样品以后，<font color=red>一定要记得在这里及时修改样品名称</font>，相当于告诉CCD的软件系统：我换了一个样品了。

{{% callout warning %}}
务必注意，样品杆1-2-3三个位置，如果你选择了1号样品，则一定要将Specimen改为对应的样品名字。例如有三个样品，在样品杆的位置：1——CK，2——ERF1，3——ERF9a。<font color=blue>如果目前你再看1号位置，则需要将Specimen改为CK</font>。
{{% /callout %}}

![修改Specimen](image-5.png)

  - 当我们拍好一张照片以后，要记得存盘哦，存盘方法很简单：点击下图红色箭头所指的<font color=red>磁盘123</font>即可。照片被存盘到指定的文件夹，而且照片文件名里面<font color=red>自动</font>带上了样品名称、放大倍数以及序号。
![保存](image-6.png)

- 电镜操作 👇
<iframe id="test" src="//player.bilibili.com/player.html?aid=664659916&bvid=BV16a4y197ue&cid=1364507660&p=1" scrolling="no" border="0" frameborder="no" framespacing="0" allowfullscreen="true" width=100%> </iframe>

<script type="text/javascript">
document.getElementById("test").style.height=document.getElementById("test").scrollWidth*0.76+"px";
</script>

- 样品杆装样 👇
<iframe id="sample" src="//player.bilibili.com/player.html?aid=664692234&bvid=BV1Sa4y197XJ&cid=1366928204&p=1" scrolling="no" border="0" frameborder="no" framespacing="0" allowfullscreen="true" width=100%> </iframe>

<script type="text/javascript">
document.getElementById("sample").style.height=document.getElementById("sample").scrollWidth*0.76+"px";
</script>

- 相机操作 👇
<iframe id="tem" src="//player.bilibili.com/player.html?aid=494699797&bvid=BV1QN411G7n5&cid=1364580181&p=1" scrolling="no" border="0" frameborder="no" framespacing="0" allowfullscreen="true" width=100%> </iframe>

<script type="text/javascript">
document.getElementById("tem").style.height=document.getElementById("tem").scrollWidth*0.76+"px";
</script>

- 目镜使用 👇
<iframe id="eye" src="//player.bilibili.com/player.html?aid=237208874&bvid=BV1me411y7AA&cid=1366942641&p=1" scrolling="no" border="0" frameborder="no" framespacing="0" allowfullscreen="true" width=100%> </iframe>

<script type="text/javascript">
document.getElementById("eye").style.height=document.getElementById("eye").scrollWidth*0.76+"px";
</script>

- 保存照片 👇
<iframe id="pic" src="//player.bilibili.com/player.html?aid=749687851&bvid=BV1dC4y1F7QP&cid=1366924726&p=1" scrolling="no" border="0" frameborder="no" framespacing="0" allowfullscreen="true" width=100%> </iframe>

<script type="text/javascript">
document.getElementById("pic").style.height=document.getElementById("pic").scrollWidth*0.76+"px";
</script>

## <font color=orange>操作电镜</font>

{{% callout note %}}
1. CCD作为高精密的仪器，价格昂贵（本机所配CCD，花了10万刀哦 ），而且还是易损件。所以要格外注意爱护。记住：CCD仅仅用于拍照，严禁用作浏览器！！！应在电镜里找好目标物，然后按照程序准备好以后，方能启动CCD。
2. 过高的亮度也会损伤CCD，导致其寿命缩短，所以，启动CCD之前，一定要降低亮度至昏暗的程度（但不要暗到看不到图像）。
3. 出于提高效率和保护仪器的考虑，规定生物切片样品的套餐价格里面包含观察时间半个小时以及最多10张照片。超出部分另行收费，标准为：每小时300元，每张照片10元。
{{% /callout %}} 

### <font color=orange>在电镜中，用低倍找到切片，然后提高放大倍数，通过移动找到自己感兴趣的地方</font>
注意：一张铜网上有超过3张的切片，都是当前这个样品的切片。使用者可以在一张切片上仔细搜寻，也可以在一张铜网上的不同切片里面搜寻，直到找到目标物。
### <font color=orange>拍照（重中之重）</font>
找到目标物以后，拍照之前的准备工作有4大步骤：
1. 将目标对象放置在电镜荧光屏的中心附近，即靠近“十”字附近；
2. 将放大倍数调整到位。注意：设定一套倍数以后，不要随意变动！
3. 使用“Focus”，把照片调清楚。
4. 上述准备工作完成以后，将电镜里的亮度调低，达到这样的程度：电镜里的光线比较昏暗，但仍能看到图像。特别提醒：过高的亮度会损伤CCD，缩短其寿命！！！但也不要全黑了。
5. 电镜方面的准备到位以后，就要使用CCD的软件来拍照。
   - 在下图的界面中点选“<font color=red>Camera Inserted</font>”，然后点击“<font color=red>Start View</font>”，就会在view的窗口中看到照片预览。
![view](image-7.png)

{{% callout note %}}
View窗口的作用有这样几个方面：
- 判断照片亮度是否合适（上图中的<font color=blue>Intensity</font>就是指示亮度，应使亮度条处于<font color=green>绿区范围内</font>，<font color=red>红区表明亮度过高！！！</font>）
- 判断一下所选目标物是否理想；如果目标物理想，放置是否合适（应将影响画面的因素尽量放到画面以外或放在照片的边角部位）；
- 照片是否清晰（如果不清晰，建议点击start view——再点击Camera Inserted，把CCD撤出来，在电镜里重新调焦，直至照片清晰再插入CCD）。
{{% /callout %}}

  - 一切都调好，觉得照片是需要的。上图中，点击“Start Acquire”开始拍照（照片生成需要一段时间，请耐心等待）。
![拍照保存](image-8.png)
  - 获得的照片一定要及时存盘，<font color=red>点击磁盘123</font>。
![点击磁盘保存](image-9.png)

## <font color=orange>参考内容说明</font>
{{% callout note %}}
以上内容根据ZJU农生环电镜中心的相关资料及教学视频进行稍加整理。
{{% /callout %}}
