---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "GeneiousLocalBlast"
subtitle: ""
summary: "Establishment of local blast databases for each species for rapid CDS, protein or genomic blasts"
authors: 
  - admin
tags: 
  - Blast
  - Geneious
categories: Method
date: 2023-12-05T19:37:29+08:00
lastmod: 2023-12-05T19:37:29+08:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: "From Geneious homepage"
  focal_point: "Smart"
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---
# <font color=green>安装ncbi-blast本地blast软件</font>

- 按步骤1-2-3打开界面
  ![2022-08-05-3HpSMr](https://raw.githubusercontent.com/Lxmic/Picture-bed/master/uPic/2022-08-05-3HpSMr.png)
  <br>
- 点击OK，然后geneious会自行检测安装ncbi-blast
  ![2022-08-05-1VlJOD](https://raw.githubusercontent.com/Lxmic/Picture-bed/master/uPic/2022-08-05-1VlJOD.png)
- 显示正在安装
  ![2022-08-05-JzYvPw](https://raw.githubusercontent.com/Lxmic/Picture-bed/master/uPic/2022-08-05-JzYvPw.png)

# <font color=green>本地Blast数据库构建</font>

- 例如可以讲物种基因组或者所有编码蛋白进行格式化，可以用于blast。
  ![2022-08-05-T5v64m](https://raw.githubusercontent.com/Lxmic/Picture-bed/master/uPic/2022-08-05-T5v64m.png)
- 可以选择从已经下载好的数据导入，最后点击OK，就完成本地blast数据库的构建。
  ![2022-08-05-fcbXgl](https://raw.githubusercontent.com/Lxmic/Picture-bed/master/uPic/2022-08-05-fcbXgl.png)

# <font color=green>选择目标基因进行数据库blast</font>

一个物种的基因去比对另一个物种的基因组或者蛋白数据，得到相关的同源蛋白。
![2022-08-05-xh6Dga](https://raw.githubusercontent.com/Lxmic/Picture-bed/master/uPic/2022-08-05-xh6Dga.png)

{{% callout note %}}
参考内容：[Geneious官方文档](https://assets.geneious.com/manual/2022.1/index.html)。
{{% /callout %}}
