---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Zotero CSL style file modification"
subtitle: ""
summary: "Modify the existing CSL style file for meeting your needs in journal citation "
authors: 
  - admin
tags: 
  - Zotero
  - CSL
categories: Trifles
date: 2023-12-12T13:12:46+08:00
lastmod: 2023-12-12T13:12:46+08:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: "CSLeditor"
  focal_point: "Smart"
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---
## 修改现有样式——创建适合PPT文献引用格式
1. [open CSL editor site](https://editor.citationstyles.org/about/)，可再搜索框搜索需要修改的期刊文献引用格式。
![search](image.png)

2. 例如Nature，点击Edit进行修改。
![edit](image-1.png)

3. 进入visual editor界面。
![visual editor](image-2.png)

4. 点击Example citations,将例子选择成我们熟悉的<font color=royalblue>**journal article**</font>，否则修改的内容可能让你有点晕。
![journal article](image-3.png)

5. INLINE CITATIONS可以将其删除，PPT引用不需要。删除后，显示[NO_PRINTED_FORM]。
{{% callout warning %}}
需要注意的是，这里的Layout和Sort内容不能删除，只能删除他们包含的内容（就是下拉菜单内容）。
{{% /callout %}}
![删除位置](image-4.png)
![Alt text](image-5.png)

6. 删除number以及title，基本上不太需要这两个内容。
![删除多余的](image-6.png)

7. 此时已经是比较短的引用了，你可以再稍做调整，可以将名字显示更短，或者将年份去掉括号，调整至volume前面，可以取消volume的加粗，可以将期刊名显示完整，或者改变分割符号。
 ![短引用](image-7.png)
8. 我自己引用的样式如下，可以进行一步步调整，达到这个效果。
![最终效果](image-8.png)
9. 比如我要修改名字的长短，点击名字，会出现可以编辑的位置，其中Name部分有**form**，选择short，就会缩短名字。其他部分内容也是一样的修改，具体的参数可以自己研究一下。
![修改相应内容](image-9.png)
10. 最后修改CSL的名字，自己像个名字填入title，并删除ISSN号。
点击**ADVANCED**-info，在title部分填入自己想要的名字，再点击Delete删除ISSN号，至此全部修改完成。
![修改csltitle](image-12.png)
## 保存修改后的CSL文件，导入Zotero中使用
- 点击左上角的Style，点击Save style
![点击save](image-10.png)
- 点击download style
![下载保存](image-11.png)
- 根据Zotero这部分说明，将CSL文件导入zotero，然后选择该引用方式。
![导入zotero使用](image-13.png)
## 参考内容
1. [知乎@兰斯《Zotero + CSL编辑器，自定义文献引用格式，创建PPT中的短文献引用》](https://zhuanlan.zhihu.com/p/185026280)
2. [Visual CSL Editor: A guide to modifying and creating citation styles in Mendeley and Zotero](https://www.researchgate.net/publication/359256507_Visual_CSL_Editor_A_guide_to_modifying_and_creating_citation_styles_in_Mendeley_and_Zotero)
<center><embed src="VisualCSLEditorGuide.pdf" width="700" height="650"></center>s