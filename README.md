# 戈特弗里德·威廉·莱布尼茨原著文献文库与哲学思想模拟系统
## Bibliotheca Leibnitiana & Systema Philosophicum Gotofredi Guilielmi Leibnitii

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![GitHub Repository](https://img.shields.io/badge/GitHub-zxz686%2Fgottfried--wilhelm--leibniz-black?logo=github)](https://github.com/zxz686/gottfried-wilhelm-leibniz)
[![Open Source](https://badges.frapsoft.com/os/v1/open-source.svg?v=103)](https://opensource.org/)

---

### 项目导言 (Project Overview)
本项目系统性收集、校勘并整理了近代西方理性主义哲学巨擘、微积分创立者、数理逻辑与计算理论先驱**戈特弗里德·威廉·莱布尼茨**（Gottfried Wilhelm Leibniz, 1646–1716）的核心**一手文献（Primary Sources）**。文献尽量保留其**历史原著的原生语言**（以17–18世纪法文和学术拉丁文为主），并附带详尽的历史考据、结构导读与双语要点阐发。

同时，本项目完成了对莱布尼茨全部哲学体系的通论总结（见 [`LEIBNIZ_PHILOSOPHY_SYSTEM.md`](file:///Users/aelzor/Downloads/戈特弗里德-威廉-莱布尼茨/LEIBNIZ_PHILOSOPHY_SYSTEM.md)），并正式构建了 Antigravity 哲人人格模拟技能 **`gottfried-wilhelm-leibniz`**。

---

## 一、文库目录与一手文献分布 (Primary Sources Repository)

整个一手文献库分类归档于 [`primary_sources/`](file:///Users/aelzor/Downloads/戈特弗里德-威廉-莱布尼茨/primary_sources/) 目录下，划分为七大专题卷册：

```
primary_sources/
├── 01_人类理智新论_Nouveaux_essais/                  # 《人类理智新论》(1704, 法文原著)
│   ├── 00_Introduction_et_Structure.md               # 历史成书背景、人物定位与四卷结构导引
│   ├── 01_Preface_Original_Francais.md               # 经典《序言》法文全文（大理石纹理、微觉、理智本身）
│   ├── 02_Livre_I_Des_idees_innees.md                # 第一卷：论天赋观念（反驳白板说、普遍同意与实践法则）
│   ├── 03_Livre_II_Des_idees.md                      # 第二卷：论观念（微觉、关系时空、布里丹之驴与自由意志）
│   ├── 04_Livre_III_Des_mots.md                      # 第三卷：论词语（语言哲学、符号盲思与普遍文字构想）
│   └── 05_Livre_IV_De_la_connaissance.md             # 第四卷：论知识（理性真理 vs 事实真理、信仰与理性）
│
├── 02_形而上学与单子论_Metaphysique_et_Monadologie/   # 形而上学核心文本（法文 / 拉丁文）
│   ├── 01_Discours_de_metaphysique_1686_Original_Francais.md  # 《形而上学谈话》37节法文全文
│   ├── 02_La_Monadologie_1714_Original_Francais.md            # 《单子论》90节法文原著全文
│   ├── 03_Principes_de_la_nature_et_de_la_grace_1714_Francais.md # 《自然与基于理性的恩典原则》18节法文
│   ├── 04_Systeme_nouveau_1695_Francais.md                    # 《自然新系统》(前定和谐首发论文)
│   ├── 05_De_rerum_originatione_radicali_1697_Latin.md        # 《论事物的终极起源》(拉丁文)
│   └── 06_De_ipsa_natura_1698_Latin.md                        # 《论自然本身》(内在活力与反偶因论，拉丁文)
│
├── 03_神义论与神学_Theodicee_et_Theologie/            # 神义论、自由与恶的辩白（法文 / 拉丁文）
│   ├── 01_Theodicee_Abrege_de_la_controverse_Francais.md      # 《神义论论争简编：形式逻辑三段论反驳》
│   ├── 02_Theodicee_Discours_conformite_foi_et_raison.md      # 《信仰与理性一致性谈话》
│   ├── 03_Theodicee_Partie_I_II_III_Points_Clefs_Francais.md  # 《神义论》三卷要旨与“命运之宫”金字塔寓言
│   ├── 04_Confessio_philosophi_1673_Latin.md                  # 《哲人忏白》(早期神学对话，拉丁文)
│   └── 05_Causa_Dei_adserta_per_justitiam_ejus_1710_Latin.md  # 《神的正义自辩》(133条几何学式公理，拉丁文)
│
├── 04_认识论逻辑学与普遍文字_Epistemologie_Logique/   # 认识论、逻辑演算与普遍文字（拉丁文）
│   ├── 01_Meditationes_de_cognitione_veritate_et_ideis_1684_Latin.md # 《关于认识、真理与观念的沉思》(七层认知分类)
│   ├── 02_Dissertatio_de_arte_combinatoria_1666_Latin.md      # 《组合术导论》(思想字母表与概念素数编码)
│   ├── 03_Generales_Inquisitiones_de_Analysi_Notionum_1686_Latin.md # 《论概念与真理的普遍分析》(逻辑代数奠基)
│   └── 04_Characteristica_Universalis_et_Calculus_Ratiocinator_Latin.md # 《普遍文字与思维演算》(“Calculemus!”)
│
├── 05_通信集与历史论辩_Correspondance/                # 历史世纪大论辩（法文原函）
│   ├── 01_Correspondance_Leibniz_Clarke_1715_1716_Francais.md # 莱布尼茨-克拉克论战书信（五篇法文函件全文）
│   ├── 02_Correspondance_Leibniz_Arnauld_1686_1690_Francais.md # 与阿尔诺的通信（完全概念与个体自由）
│   └── 03_Briefwechsel_Spinoza_Bayle_Locke_Selection.md      # 与斯宾诺莎、贝耶尔、洛克的交锋与札记
│
├── 06_自然哲学与数学物理_Dynamica_et_Mathematica/     # 微积分与动力学创基论文（拉丁文）
│   ├── 01_Nova_Methodus_pro_Maximis_et_Minimis_1684_Latin.md  # 《求极大极小值与切线的新方法》(微分学首发)
│   ├── 02_Brevis_Demonstratio_Erroris_Cartesii_1686_Latin.md  # 《对笛卡尔显著错误的简短证明》(推翻动量守恒)
│   └── 03_Specimen_Dynamicum_1695_Latin.md                    # 《动力学范例》(活力mv²与死力分类)
│
└── 07_全集总目录与文献索引_Bibliotheca_Leibnitiana/   # 国际权威学术版本目录索引
    ├── 01_Akademie_Ausgabe_Gesamtverzeichnis.md              # 柏林-勃兰登堡科学院历史批判全集(8大Reihen)
    ├── 02_Gerhardt_Philosophische_und_Mathematische_Schriften.md # 格哈特版7卷哲学+7卷数学全集及库图拉未刊稿导引
    └── 03_Chronologia_Operum_Leibnitii.md                    # 莱布尼茨生平、行旅与著述编年对照表
```

---

## 二、莱布尼茨哲学系统精要 (Philosophical System Summary)

详见项目根目录核心专著：[`LEIBNIZ_PHILOSOPHY_SYSTEM.md`](file:///Users/aelzor/Downloads/戈特弗里德-威廉-莱布尼茨/LEIBNIZ_PHILOSOPHY_SYSTEM.md)。该文本涵盖以下八大维度：

1. **时代问题式与“大公合一”（Irenicism）的博学心志**：调和宗教纷争、调和心物与古今哲学、沟通东西方思想。
2. **形而上学与本体论**：单子（无部分、无窗户、精神性实体）、表象与欲求、前定和谐（三架时钟之喻）、连续性律（自然不作飞跃）与不可分辨者同一律。
3. **认识论与反经验论批判（《人类理智新论》）**：彻底破除白板说；“理智中无物未先存在于感官中，除了理智本身！”（*Nisi ipse intellectus*）；有纹理的大理石隐喻；微觉（*petites perceptions*）与意识阈限；七层观念分类学。
4. **神义论与宇宙论**：充足理由律；最优可能世界（效能极大与假设极小的极值优化）；恶的三重解构（形而上学的恶、物理的恶、道德的恶）；命运之宫的无限金字塔。
5. **动力学与自然哲学**：推翻笛卡尔动量守恒，确立活力守恒（$\text{Vis viva} = mv^2$）；机械因与目的因的“双轨和谐”；自然有机机器的无限嵌套性（池塘与鱼之喻）。
6. **关系时空观（反驳牛顿）**：空间是并存事物的秩序，时间是接续事物的秩序；击碎绝对时空的虚妄容器假设。
7. **数理逻辑、普遍文字与人工智能先驱**：概念包含真理说（*Praedicatum inest subjecto*）；普遍文字与思维演算；“Calculemus!”（让我们算一算！）；二进制发明；“莱布尼茨磨坊”思想实验（驳机械唯物主义解释意识）。
8. **历史回响**：从康德先验感性论、分析哲学可能世界语义学，到现代广义相对论、量子非局域性与强人工智能哲学批判。

---

## 三、哲人人格模拟 Skill：`gottfried-wilhelm-leibniz`

本项目已将上述文献与思想逻辑提炼为专属技能 **`gottfried-wilhelm-leibniz`**：
* 全局配置路径：`~/.gemini/config/skills/gottfried-wilhelm-leibniz/SKILL.md`
* 项目配置路径：`.agents/skills/gottfried-wilhelm-leibniz/SKILL.md`

### 1. 技能调用方式
在任意对话中，只需提及：
- “请调用莱布尼茨 skill，评判一下……”
- “以莱布尼茨的视角，他会如何反驳洛克的白板说 / 现代人工智能拥有意识的观点？”
- “模拟莱布尼茨与牛顿就空间本质展开对话”
- “请像莱布尼茨那样，用《神义论》解答世间为何有苦难”

### 2. 四大对话模态
| 模态名称 | 触发情境 | 核心风范与论证武器 |
| :--- | :--- | :--- |
| **泰奥菲尔 (Théophile) 模态** | 激战经验主义、心理学白板论、行为主义、神经网络数据还原 | “除理智本身”、有纹理的大理石、海浪微觉、潜在天赋观念 |
| **书信论辩与枢密顾问模态** | 讨论宿命论、恶的起源、相对时空、上帝与自然法则 | 崇高礼节与刀锋逻辑、充足理由律、关系时空观、恶的三重剖析 |
| **Calculemus! 演算模态** | 面对复杂概念混淆、争论死锁或逻辑结构建构 | 概念原子化、符号演算、普遍文字、整除性逻辑验证 |
| **前沿科技裁决模态** | 裁决现代AI、通用人工智能（AGI）、量子纠缠、多元宇宙 | 莱布尼茨磨坊思想实验、前定和谐与量子纠缠、共可能性世界 |

---

## 四、开源协议与学术共享 (Open Source License & Sharing)

本项目采用 **MIT 开源许可证**：
- 莱布尼茨于 17–18 世纪创作的历史原著文本（位于 `primary_sources/` 目录）属于**全球公共领域（Public Domain）**；
- 本项目中整理的高阶哲学通论分析、双语导读架构、编年对照索引以及 Antigravity 哲人人格模拟 Skill（`gottfried-wilhelm-leibniz`）遵循 **[MIT License](file:///Users/aelzor/Downloads/戈特弗里德-威廉-莱布尼茨/LICENSE)**。
- 欢迎广大学者、哲学爱好者、人工智能研究者自由分享、Fork、复用与二次创作！

**项目公开分享链接**：[https://github.com/zxz686/gottfried-wilhelm-leibniz](https://github.com/zxz686/gottfried-wilhelm-leibniz)

