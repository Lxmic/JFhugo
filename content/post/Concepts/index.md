---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Concepts in science"
subtitle: ""
summary: "Understand the concepts, understand the science."
authors: 
    - admin
tags: Cuticle
categories: Concepts
date: 2023-10-23T15:15:51+08:00
lastmod: 2023-10-23T15:15:51+08:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: "Smart"
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---
## Plant Cuticle
<font color=amber>Cuticle</font>: a hydrophobic boundary layer that coats the outer face of the epidermis of aerial plant organs.

<font color=tomato>Suberin</font>: a hydrophobic polyester deposited in the apoplast of endodermal and peridermal cells, abscission zones, scar tissues, and seed coats.

<font color=chocolate>Cutin</font>: a polyester network of predominantly fatty acids that constitutes a major component of the plant cuticle.

<font color=red>Cross-link</font>: a lateral covalent linkage between two polymer chains.

<font color=seagreen>Long-chain fatty acid</font>: a fatty acid that is 16 or 18 carbons in length.

<font color=red>Depolymerization</font>: the breakdown of a polymer into its constituent monomers.

<font color=green>Gas chromatography</font>: an analytical technique to separate and quantify the abundance of compounds that are volatile in a gaseous phase.

<font color=royalblue>Apoplast</font>: the continuous region throughout the plant that is external to the plasma membranes.

<font color=royalblue>Dendrimer</font>: a branching, tree-like structure with a single origin and many termini.


<font color=chocolate>Monoacylglycerol</font>: a molecule consisting of glycerol ester-linked to a single acyl chain.

<font color=yellowgreen>Magic-angle spinning nuclear magnetic resonance (MAS NMR)</font>: a method of solid-state NMR spectroscopy that gives improved peak resolution.

<font color=chocolate>Long-chain acyl-CoA synthetase (LACS) proteins</font>: enzymes that conjugate a molecule of coenzyme A to the carboxyl end of a fatty acid.

<font color=purple>Cytochrome P450</font>: a large family of enzymes that typically perform oxidation reactions.

<font color=green>Cutinase</font>: an enzyme that hydrolyzes polymeric cutin polymers, breaking the ester linkages.

<font color=purple>Epidermal-growth-control theory</font>: the thory that turgor-driven organ growth is constrained by the rigid epidermal layer.

## Mass spectrometry or chromatography

<font color=amber>原子量Atomic mass:</font> Relative atomic mass, 原子量的单位为道尔顿Da。而1道尔顿的定义为C12原子静止质量的1/12. 原子核的质子和中子几乎占原子总质量的全部。
![Atom](fced5432747de71dceb1acb9f05b64ad-350x350.png)

<font color=orange>同位素isotope</font>：含有相同的质子数不同中子数的原子。包括放射性同位素和稳定同位素。比如C13 和O18就属于稳定同位素。
![同位素](<Hydrogen isotopes.jpg>)

<font color=royalblue>同位素丰度isotope abundance/Natural abundance</font>：自然界中存在的某一元素的各种同位素的相对含量，比例是固定的。比如在地球上，氧的同位素丰度：16O=99.76%，17O=0.04%，18O=0.20% 
![丰度](image.png)
> [同位素丰度表](https://www.chem.ualberta.ca/~massspec/atomic_mass_abund.pdf)

<font color=blue>平均质量（average mass ）</font>：计算时候，每个同位素质量都要乘以丰度，然后加和。比如氧气（O2）的平均分子量： 2\*（15.994915\*99.76%+16.999131\*0.038%+17.999159\*0.2%）这里需要说明，大家日常所叫的分子量（molecular weight），大多数时候便是平均质量。

<font color=seagreen>精确质量 （Exact mass）</font>：是以丰度最高的同位素质量进行直接进行加和得到。
{{% callout note %}}
使用高分辨质谱进行分析的时，可看到每个同位素峰（isotope peak）.
![同位素峰](image-1.png)
{{% /callout %}}

<font color=green>质谱正负离子模式的选择</font>：<font color=red>物质需要离子化后也就是需要带电才能被质谱检测。</font>主要根据化合物的性质，也就是看结构的不同，有些物质在电离时容易带正电荷，有些容易带负电荷。
1. 正离子模式：适合碱性样品，如还有赖氨酸、精氨酸和组氨酸等肽类。可用乙酸（pH=3-4）或者甲酸（pH=2-3）对样品进行酸化。**如果样品pK值已知，则pH至少要低于pK值2个单位。** 碱性化合物容易加合质子，**带正电荷，形成[M+H]+,m/z会多H的分子量**。此外，还有其他带正电的加合物，<font color=brown>[M+Na]+，[M+K]+，[M+NH4]+</font>。
2. 负离子模式：适合酸性样品，如含有谷氨酸和天冬氨酸的肽类，可用氨水或三乙胺对样品碱化。pH至少高于pK值2个单位。酸性化合物很容易丢失质子，带负电荷，形成[M-H]-，m/z就是分子量要减去H。此外，还会形成<font color=blue>[M+Cl]-，[M+HCOO]-，[M+CH3COO]-</font>

当样本浓度特别高的时候，还会产生二聚离子，如[2M+H]+，[2M+Na]+，此时整个化合物的**m/z就会增加**；有时候还会形成多电荷离子，如[M+nH]n+，[M-nH]n-，这时候**m/z就会减小**。