# OpenFantasy 生物图鉴

> *"世界以无数生灵的声音歌唱，每个生灵都在存在的宏伟交响曲中扮演着自己的角色。"*

## 概述

欢迎来到 OpenFantasy 生物文档。本仓库包含关于居住在 OpenFantasy 世界中的各种生物的综合信息，包括有知觉的物种、动物、怪物、植物和其他实体。

## 目录结构

```
/Creatures
├── README.md                # 本概述文档
├── Creatures.md             # 核心原则和元素构成
├── template_species.md      # 用于创建新物种条目的模板
├── /Sentient                # 智能的、形成文明的物种
│   ├── README.md            # 有知觉物种的概述
│   ├── Humans.md
│   ├── Elves.md
│   ├── DarkElves.md
│   ├── Dwarves.md
│   └── ...
├── /Magical                 # 主要是魔法或妖精生物
│   ├── README.md            # 魔法生物的概述
│   ├── Fae.md
│   ├── Golems.md
│   ├── Elementals.md
│   └── ...
├── /Animals                 # 无知觉的自然动物
│   ├── README.md            # 动物的概述
│   ├── Domesticated.md
│   ├── Wild.md
│   ├── Aquatic.md
│   └── ...
├── /Monsters                # 危险或不自然的生物
│   ├── README.md            # 怪物的概述
│   ├── Aberrations.md
│   ├── Undead.md
│   ├── Corrupted.md
│   └── ...
├── /Plants                  # 具有独特属性的植物
│   ├── README.md            # 魔法和凡人植物的概述
│   ├── Magical.md
│   ├── Medicinal.md
│   ├── Poisonous.md
│   └── ...
└── /Hybrid                  # 跨类别生物
    ├── README.md            # 混合生物的概述
    ├── Centaurs.md
    ├── Merfolk.md
    └── ...
```

## 快速导航

- [核心概念](#core-concepts)
- [有知觉的物种](#sentient-species)
- [魔法生物](#magical-beings)
- [动物](#animals)
- [怪物](#monsters)
- [植物](#plants)
- [混合生物](#hybrid-beings)

## 核心概念

OpenFantasy 中的所有生物都由三个基本元素组成，这些元素决定了它们的本质和能力：

| 组件 | 功能 | 影响 |
|---|---|---|
| **Exanthis** | 物理基础 | 力量、耐力、耐久性 |
| **Soul** | 意识和身份 | 意志力、创造力、感知力 |
| **Mana Capacity** | 魔法潜力 | 法术能力、魔法抗性、法力净化 |

有关这些原则的详细信息，请参阅[生物概述](/codex/Creatures/Creatures.md)。

## 有知觉的物种

有智能的生物，能够形成文明、创造文化并通过有意识的努力运用魔法：

| 物种 | 概述 | 元素平衡 |
|---|---|---|
| [人类](/codex/Creatures/Sentient/Humans.md) | 适应性强，具有创新性，成分均衡 | E: 20-55%, S: 15-45%, M: 15-60% |
| [精灵](/codex/Creatures/Sentient/Elves.md) | 长寿的魔法专家，具有很高的法力协调性 | E: 5-25%, S: 5-15%, M: 50-80% |
| [黑暗精灵](/codex/Creatures/Sentient/DarkElves.md) | 具有独特能力的阴影协调精灵变体 | E: 5-25%, S: 10-20%, M: 50-80% |
| [矮人](/codex/Creatures/Sentient/Dwarves.md) | 坚固的工匠，具有高 Exanthis 浓度 | E: 50-70%, S: 20-35%, M: 5-25% |
| [兽人](/codex/Creatures/Sentient/Beastfolk.md) | 具有动物属性的多样化生物 | E: 35-70%, S: 15-35%, M: 15-40% |
| [侏儒](/codex/Creatures/Sentient/Gnomes.md) | 小而有创造力，具有技术能力 | E: 30-50%, S: 30-50%, M: 15-30% |

## 魔法生物

主要由魔法能量组成或通过魔法过程创造的生物：

| 生物 | 概述 | 元素平衡 |
|---|---|---|
| [妖精](/codex/Creatures/Magical/Fae.md) | 几乎纯粹魔法的空灵生物 | E: 2-10%, S: 15-35%, M: 50-80% |
| [魔像](/codex/Creatures/Magical/Golems.md) | 具有人造灵魂的构造生物 | E: 70-90%, S: 5-15%, M: 5-15% |
| [暗影族](/codex/Creatures/Magical/Shadowfolk.md) | 诞生于阴影并能操纵黑暗的生物 | E: 10-30%, S: 20-40%, M: 40-70% |
| [元素生物](/codex/Creatures/Magical/Elementals.md) | 元素力量的纯粹化身 | E: 15-30%, S: 5-15%, M: 60-85% |
| [龙裔](/codex/Creatures/Magical/Dragonkin.md) | 具有天然魔法亲和力的龙的后裔 | E: 55-75%, S: 5-15%, M: 20-35% |

## 动物

具有不同程度的智力和魔法亲和力的无知觉动物：

| 类别 | 描述 | 例子 |
|---|---|---|
| [驯养的](/codex/Creatures/Animals/Domesticated.md) | 为人类使用而繁殖的动物 | 马、牛、狗、猫、家禽 |
| [野生的](/codex/Creatures/Animals/Wild.md) | 各种生物群落的自然动物 | 狼、熊、鹰、鹿 |
| [水生的](/codex/Creatures/Animals/Aquatic.md) | 海洋和淡水生物 | 鱼、鲸鱼、章鱼、河流生物 |
| [魔法的](/codex/Creatures/Animals/Magical.md) | 具有先天魔法属性的动物 | 凤凰、狮鹫、独角兽 |

## 怪物

对文明地区构成威胁的危险或不自然的生物：

| 类别 | 描述 | 例子 |
|---|---|---|
| [畸变体](/codex/Creatures/Monsters/Aberrations.md) | 具有奇异解剖结构的不自然生物 | 模仿怪、眼魔、夺心魔 |
| [不死生物](/codex/Creatures/Monsters/Undead.md) | 由黑暗力量赋予生命的先前生物 | 僵尸、骷髅、幽灵 |
| [堕落的](/codex/Creatures/Monsters/Corrupted.md) | 被魔法腐蚀扭曲的生物 | 被污染的动物、受污染的元素生物 |
| [巨人](/codex/Creatures/Monsters/Giants.md) | 具有非凡力量的大型生物 | 石巨人、霜巨人、食人魔 |

## 植物

具有独特属性的植物，包括魔法和凡人：

| 类别 | 描述 | 例子 |
|---|---|---|
| [魔法的](/codex/Creatures/Plants/Magical.md) | 具有内在魔法属性的植物 | 发光根、梦叶、奥术真菌 |
| [药用的](/codex/Creatures/Plants/Medicinal.md) | 具有治疗特性的植物 | 治疗师草药、止血苔藓、活力花 |
| [有毒的](/codex/Creatures/Plants/Poisonous.md) | 具有毒性特性的植物 | 茄属植物、死亡帽、毒液藤蔓 |
| [有知觉的](/codex/Creatures/Plants/Sentient.md) | 具有意识的植物 | 树人、低语柳树、心灵苔藓 |

## 混合生物

通过独特的生理机能桥接多个类别的生物：

| 生物 | 概述 | 元素平衡 |
|---|---|---|
| [半人马](/codex/Creatures/Hybrid/Centaurs.md) | 马与类人生物的混合体，具有天然智慧 | E: 50-70%, S: 20-40%, M: 10-25% |
| [美人鱼](/codex/Creatures/Hybrid/Merfolk.md) | 具有水属性的水生类人生物 | E: 30-50%, S: 15-35%, M: 25-45% |
| [塞壬](/codex/Creatures/Hybrid/Sirens.md) | 基于声音魔法的人声女巫 | E: 15-30%, S: 30-45%, M: 40-60% |

## 贡献

要向图鉴添加新生物：

1. 确定生物的适当类别
2. 使用该类别的相关模板
3. 保持与现有元素构成原则的一致性
4. 在适用的情况下包括文化、历史和生态背景

---

> *"了解我们世界的生物就是了解世界本身，因为它们是其多样化能量的活生生的体现。"* —— 大贤者莱瑞亚·索恩哈特

---
_Note: This content was automatically translated by Google Gemini. Please refer to the original English version for accuracy._