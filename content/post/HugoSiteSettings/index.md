---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "How to beautify your Hugo academic site?"
subtitle: ""
summary: "For recording some hugo blog website settings."
authors: 
  - admin
tags: 
  - Hugo
  - Academic
  - Blog
categories: Trifles
date: 2023-12-05T20:23:00+08:00
lastmod: 2023-12-05T20:23:00+08:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: "From unsplash author Rabie Madaci "
  focal_point: "Smart"
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---
# <font color=green>Code syntax highlighting</font>
According to [Hugo blox Docs site](https://docs.hugoblox.com/getting-started/customize/), you can set your code syntax highlight style.
![code1](image.png)
![code2](image-1.png)

There are many hugo chroma styles on [this site](https://xyproto.github.io/splash/docs/all.html).
![fruity](image-2.png)
![emacs](image-3.png)

You can download style by following code：
```shell
# Make directory named chroma for save sytle css files
mkdir -p assets/css/libs/chroma/
# Generate style css file, such as xcode highlight style. you can rename as xcode-light.css
hugo gen chromastyles --style=xcode > assets/css/libs/chroma/xcode-light.css
```