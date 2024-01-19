---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Tomato VIGS Protocol"
subtitle: "The Whole process of tomato VIGS experiment from primer design to phenotype."
summary: ""
authors: 
  - admin
tags:
  - VIGS
  - Tomato
categories: Method
date: 2024-01-15T15:34:40+08:00
lastmod: 2024-01-15T15:34:40+08:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: "VIGS plants from Yule Liu et al."
  focal_point: "Smart"
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---

## VIGS tools
番茄VIGS片段选择网站，[VIGS tools](https://vigs.solgenomics.net)。
![Alt text](image.png)

填入目的基因CDS序列，然后默认参数，选择物种数据库，点击Run。
![Alt text](image-1.png)

输出结果黄色区域为特异性片段，用于VIGS。
![Alt text](image-2.png)

设计引物扩增片段，并构建至pTRV2载体。

---
# <font color=green>Part I Cotyledon infiltration</font>

---

## Plant material
Tomato (Solanum lycopersicum) 生长约7-9天，两片子叶完全展开，真叶还未出现。
{{% callout note %}}
苗期非常关键，要时刻注意苗的生长状态，否则会降低VIGS的效率。
{{% /callout %}}
![Alt text](tomatoseedling.png)

## VIGS
### DAY1
GV3101 harboring pTRV1, pTRV2, pTRV2-PDS, pTRV2-target gene are grown on LB agar plates containing 50 µg/mL of Kan and 25 µg/mL of rifampicin. Incubate at 28°C for 2 days.

### DAY3
Inoculate a 2-3 mL liquid culture of LB with the above mentioned antibiotics for each  of the strains. Shake at 28°C for 16-18 h.

### DAY4

Inoculate a 1:25 (2 ml strains: 50 ml IM)dilution of the primary culture into a secondary liquid Induction Media (IM) IM culture with kan, rif and 200 µM acetosyringone.

{{% callout note %}}
The acetosyringone is used as an inducer of the vir genes of Agrobacterium which are required for T-DNA transfer into the plant while the IM mimics the environment this pathogen encounters in the host apoplast. Incubate by shaking at 28 °C for 20-24 h.
{{% /callout %}}

### DAY5
1. Harvest the cells, at 3000 g for 10 min. Resuspend in the same volume that the original culture had with resuspend buffer (10 mM MgCl2, 10 mM MES pH 5.5).

2. Centrifugue for 10 min at 3000 g. Resuspend cells in 10 ml resuspend buffer, then adjust OD600=1.0. 

3. Add acetosyringone to a final concentration of 400 µM to the pTRV1 culture.

4. The different pTRV2 constructs are mixed into 50 mL conical tubes with an equal volume of pTRV1 suspension, resulting in a final acetosyringone concentration of 200 μM.

5. Individual seedlings were inoculated through the **abaxial side** of the **cotyledon**. Plants were incubated at 21-22 °C and covered to avoid light for 24 hours and returned to 16/8 h day-night cycles at the same temperature (21-22°C). Approximately 3 weeks later, the 4th true leaf of VIGS-PDS plant was observed for bleaching phenotype or sampled for qPCR assay.

## Reagents
### Prepara of Induction Medium (IM)
| V or W | Reagents                                    |
| ------ | ------------------------------------------- |
| 400 mL | ddH2O                                       |
| 4.88 g | MES (2-(4 morpholino)-ethane sulfonic acid) |
| 2.5 g  | Glucose                                     |
| 0.12 g | NaH2PO4                                     |

Note: Bring to a final volume of 475 mL with dH2O and adjust the pH to 5.6. Autoclave. After the medium has cooled down, add **25 mL** of 20X **AB salts**.

### Preparation of AB salts
| W      | Reagents   |
| ------ | ---------- |
| 20 g   | NH4Cl      |
| 6 g    | MgSO4·7H2O |
| 3 g    | KCl        |
| 0.2 g  | CaCl2      |
| 0.05 g | FeSO4·7H2O |

Bring to a final volume of 1 liter with distilled water. Autoclave. Be aware that AB salts precipitate as an orange powder. Just mix them well by swirling before their use.

### Preparation of 200 mM Acetosyringone. Please note that acetosyringone should be prepared the day it will be used
| W       | Reagents                                                 |
| ------- | -------------------------------------------------------- |
| 19.6 mg | Acetosyringone (3’, 5’-Dimethoxy-4’-hydroxyacetophenone) |
| 500 µL  | DMSO (Dimethyl sulfoxide)                                |

## References
André C. Velásquez, Suma Chakravarthy, Gregory B. Martin. Virus-induced Gene Silencing (VIGS) in *Nicotiana benthamiana* and Tomato. Journal of Visualized Experiments. 2009. 1292 doi:10.3791/1292 

---
# <font color=tomato>Part II Sprout vacuum-infiltration</font>

---
## Plant material
Tomato sprouts come from seeds. Sprouts are easy to obtain about 2days.


## VIGS

### DAY1
GV3101 harboring pTRV1, pTRV2, pTRV2-PDS, pTRV2-target gene are grown on LB agar plates containing 50 µg/mL of Kan and 25 µg/mL of rifampicin. Incubate at 28°C for 2 days.

### DAY3
A single colony was picked and inoculated in 2 mL LB with appropriate antibiotics（50 µg/mL of Kan and 25 µg/mL of Rifampicin）. Shaking at 200 rpm at 28°C for 10 h (Overnight)
{{% callout note %}}
与此同时，可以将种子浸泡于水中，开始28°C摇床200rpm摇2天。
{{% /callout %}}

### DAY4
500 µl of above culture was inoculated into a 2-3 mL LB containing antibiotics, 10 mM MES and 20 µM acetosyringone. Shaking at 200 rpm at 28°C for 10 h. Each *Agrobacterium* strain containing TRV1 and TRV2 vectors were mixed in 1:1 ratio.

Harvest and resuspend into infiltration buffer with 10 mM MgCl2, 10 mM MES and 200 µM Acetosyringone, pH 5.6, adjust to an OD of 1.0 and left at RT for 3-4 h.

Silwet L77 was added to cell solution (0.05%, v/v, 1 µL:2 mL) and mixed well immediately.

{{% callout note %}}
种子大概0.5-1.0 cm，可进行抽真空（Yan et al.2012.）。
![Alt text](image-3.png)
{{% /callout %}}

30 seeds each group were placed in 6 ml mixture strains, and then Vacuum-infiltration. **Vacuum 5 times for 30 seconds each time.**

<font color=red>Sow shallowly, sprinkle a shallow layer of soil over the surface of the seed.</font> In about 4-5 days, the seeds can break out of the soil and the shoot begin to grow.

## Reference
Yan et al. Plant Cell Reports. 2012. 31: 1713–1722 


