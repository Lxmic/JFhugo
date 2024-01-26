---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Adobe illustrator制作和排版矢量色谱图"
subtitle: ""
summary: "从MassHunter软件导出色谱图，导入Adobe Illustrator中并进行整理排版。"
authors: 
  - admin
tags: 
  - Adobe Illustrator
  - Chromatogram
categories: Methods
date: 2024-01-24T18:15:24+08:00
lastmod: 2024-01-24T18:15:24+08:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: "Final Picture"
  focal_point: "Smart"
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---
# 导出需要的TIC
点击选中——右键——导出。
![Alt text](image.png)
选择`emf`文件格式，可选择高亮或者所有色谱图。
![Alt text](image-1.png)

# 用Adobe Illustrator (Ai)打开文件
整个图像是一个group，可以看到y轴数字显示有点问题。
![Alt text](image-2.png)
右边图层点开，Group下面还有Clip Group，path，以及x轴title。ClipGroup就是剪切组合，它含有蒙版和对象。
![Alt text](image-3.png)
Clipgroup下面还包含剪切路径以及很多对象
![Alt text](image-4.png)

# 开始处理图片
## Step1 去除所有剪切蒙版和取消组合
选中图片——file——scripts——`RemoveClippingMasks`
![Alt text](image-5.png)
弹出确认对话框，所有clippingmask都删除了。
![Alt text](image-6.png)
此时，右侧图层中，所有的Clip字样消失了，只有Group。
![Alt text](image-7.png)

{{% callout note %}}
[RemoveClippingMasks](https://github.com/nvkelso/illustrator-scripts/blob/master/import/RemoveClippingMasks.jsx)是一个自动化脚本或者称它为插件，可以一键除去所有clippingmask，便于后续操作。它是github上一个作者写的，可以将文件下载并导入到Ai中使用。
{{% /callout %}}

## Step2 ungroup第一层次的group，释放图片的各个部分
选中图片——ungroup，可以看到第一层的group不见了，剩下几个小group。
![Alt text](image-8.png)
![Alt text](image-9.png)
删除几个空白路径和第一个Group，一个一个删除，前提不影响图片。
![Alt text](image-10.png)
至此就剩下图片主题部分，然后根据图片修改相应部分。
![Alt text](image-11.png)

## Step3 XY轴调整
将文字和路径各自组合成一个Group
![Alt text](image-12.png)
锁定其他几个含有文字的图层，然后Select——All object——All text object，这样就选中了所有Y轴的文字，然后group，这样可以整体调整Y轴文字。
![Alt text](image-13.png)
然后调整Y轴，包括tick加粗
![Alt text](image-14.png)
同样的方法调整X轴
![Alt text](image-15.png)
## Step4 删除图片黑框,修改文字
![Alt text](image-16.png)


