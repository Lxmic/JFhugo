---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "XCMS online tool used for analyzing non-targeted metabolomics data"
subtitle: ""
summary: "Rapidly screen and identify significantly changing metabolites from metabolomics data."
authors: 
  - admin
tags: 
  - XCMS
  - LC/MS
categories: Method
date: 2023-12-28T21:14:49+08:00
lastmod: 2023-12-28T21:14:49+08:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: "XCMS"
  focal_point: "Smart"
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---
## 注册XCMS网站
网址：[https://xcmsonline.scripps.edu/landing_page.php?pgcontent=mainPage](https://xcmsonline.scripps.edu/landing_page.php?pgcontent=mainPage)
{{% callout note %}}
最好使用edu的邮箱，否则不好注册。
{{% /callout %}}
![sign-up](image.png)
![email](image-1.png)

## 新建任务
![newjob](image-2.png)
- 查看可之间上传的文件格式
![file format](image-4.png)

## 可上传的数据格式
若不满足以下数据格式，可使用[ProteoWizard](http://proteowizard.sourceforge.net/downloads.shtml)进行转换。
![vendor](image-3.png)
Ailgent的数据格式`.d`需要进行转换，通常可以将其转换为`.mzxml`。否则是无法整个上传，会将文件夹中的所有文件分开上传。转换后数据如下：
![mzxml](image-6.png)
{{% callout note %}}
转换方法详情见文章[MSconvert](https://lxmic.netlify.app/post/msconvert/)
{{% /callout %}}
## 上传需要比较的文件
### <font color=orange>先上传对照组，生物学重复一起上传</font>

![Alt text](image1.png)

![Alt text](image2.png)
上传了数据集1共4个文件,点击next
