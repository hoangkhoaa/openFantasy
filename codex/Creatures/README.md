# OpenFantasy 生物图鉴

> *"世界吟唱着无数生物的声音，它们在存在的宏伟交响曲中扮演着各自的角色。"*

## 概述

欢迎来到 OpenFantasy 生物文档。 此存储库包含有关居住在 OpenFantasy 世界中的各种生物的全面信息，包括有知觉的物种、动物、怪物、植物和其他实体。

## 目录结构

```
/Creatures
├── README.md                # 此概述文档
├── Creatures.md             # 核心原则和元素组成
├── template_species.md      # 用于创建新物种条目的模板
├── /Sentient                # 智能、形成文明的物种
│   ├── README.md            # 有知觉物种的概述
│   ├── Humans.md (人类)
│   ├── Elves.md (精灵)
│   ├── DarkElves.md (黑暗精灵)
│   ├── Dwarves.md (矮人)
│   └── ...
├── /Magical                 # 主要由魔法或妖精组成的生物
│   ├── README.md            # 魔法生物的概述
│   ├── Fae.md (妖精)
│   ├── Golems.md (魔像)
│   ├── Elementals.md (元素)
│   └── ...
├── /Animals                 # 无知觉的自然动物
│   ├── README.md            # 动物的概述
│   ├── Domesticated.md (驯养)
│   ├── Wild.md (野生)
│   ├── Aquatic.md (水生)
│   └── ...
├── /Monsters                # 危险或不自然的生物
│   ├── README.md            # 怪物的概述
│   ├── Aberrations.md (畸变)
│   ├── Undead.md (不死)
│   ├── Corrupted.md (堕落)
│   └── ...
├── /Plants                  # 具有独特属性的植物
│   ├── README.md            # 魔法和普通植物的概述
│   ├── Magical.md (魔法)
│   ├── Medicinal.md (药用)
│   ├── Poisonous.md (有毒)
│   └── ...
└── /Hybrid                  # 跨类别生物
    ├── README.md            # 混合生物的概述
    ├── Centaurs.md (半人马)
    ├── Merfolk.md (美人鱼)
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

| Component (成分) | Function (功能) | Influence (影响) |
|-----------|----------|-----------|
| **Exanthis** | 物理基础 | 力量、耐力、耐久性 |
| **Soul** (灵魂) | 意识和身份 | 意志力、创造力、感知力 |
| **Mana Capacity** (法力容量) | 魔法潜力 | 法术能力、魔法抗性、法力净化 |

有关这些原则的详细信息，请参阅[生物概述](/codex/Creatures/Creatures.md)。

## 有知觉的物种

能够形成文明、创造文化并通过有意识的努力运用魔法的智能生物：

| Species (物种) | Overview (概述) | Elemental Balance (元素平衡) |
|---------|----------|-------------------|
| [Humans](/codex/Creatures/Sentient/Humans.md) (人类) | 适应性强，具有创新性，成分均衡 | E: 20-55%, S: 15-45%, M: 15-60% |
| [Elves](/codex/Creatures/Sentient/Elves.md) (精灵) | 长寿的魔法专家，具有高法力亲和力 | E: 5-25%, S: 5-15%, M: 50-80% |
| [Dark Elves](/codex/Creatures/Sentient/DarkElves.md) (黑暗精灵) | 与阴影协调的精灵变体，具有独特的能力 | E: 5-25%, S: 10-20%, M: 50-80% |
| [Dwarves](/codex/Creatures/Sentient/Dwarves.md) (矮人) | 坚固的工匠，具有高 Exanthis 浓度 | E: 50-70%, S: 20-35%, M: 5-25% |
| [Beastfolk](/codex/Creatures/Sentient/Beastfolk.md) (兽人) | 具有动物属性的各种生物 | E: 35-70%, S: 15-35%, M: 15-40% |
| [Gnomes](/codex/Creatures/Sentient/Gnomes.md) (侏儒) | 具有技术才能的小型、有创造力的生物 | E: 30-50%, S: 30-50%, M: 15-30% |

## 魔法生物

主要由魔法能量组成或通过魔法过程创造的生物：

| Being (生物) | Overview (概述) | Elemental Balance (元素平衡) |
|-------|----------|-------------------|
| [Fae](/codex/Creatures/Magical/Fae.md) (妖精) | 几乎纯粹的魔法的空灵生物 | E: 2-10%, S: 15-35%, M: 50-80% |
| [Golems](/codex/Creatures/Magical/Golems.md) (魔像) | 具有人造灵魂的构造生物 | E: 70-90%, S: 5-15%, M: 5-15% |
| [Shadowfolk](/codex/Creatures/Magical/Shadowfolk.md) (暗影族) | 由阴影诞生的生物，具有黑暗操纵能力 | E: 10-30%, S: 20-40%, M: 40-70% |
| [Elementals](/codex/Creatures/Magical/Elementals.md) (元素) | 元素力量的纯粹体现 | E: 15-30%, S: 5-15%, M: 60-85% |
| [Dragonkin](/codex/Creatures/Magical/Dragonkin.md) (龙人) | 龙的后裔，具有天然的魔法亲和力 | E: 55-75%, S: 5-15%, M: 20-35% |

## 动物

非知觉的动物群，具有不同程度的智力和魔法亲和力：

| Category (类别) | Description (描述) | Examples (例子) |
|----------|-------------|----------|
| [Domesticated](/codex/Creatures/Animals/Domesticated.md) (驯养) | 为人类使用而繁殖的动物 | 马、牛、狗、猫、家禽 |
| [Wild](/codex/Creatures/Animals/Wild.md) (野生) | 各种生物群落的自然动物群 | 狼、熊、鹰、鹿 |
| [Aquatic](/codex/Creatures/Animals/Aquatic.md) (水生) | 海洋和淡水生物 | 鱼、鲸鱼、章鱼、河流生物 |
| [Magical](/codex/Creatures/Animals/Magical.md) (魔法) | 具有先天魔法属性的动物 | 凤凰、狮鹫、独角兽 |

## 怪物

对文明地区构成威胁的危险或不自然的生物：

| Category (类别) | Description (描述) | Examples (例子) |
|----------|-------------|----------|
| [Aberrations](/codex/Creatures/Monsters/Aberrations.md) (畸变) | 具有奇异解剖结构的不自然生物 | 模仿怪、眼魔、夺心魔 |
| [Undead](/codex/Creatures/Monsters/Undead.md) (不死) | 曾经是活着的生物，被黑暗力量赋予生命 | 僵尸、骷髅、幽灵 |
| [Corrupted](/codex/Creatures/Monsters/Corrupted.md) (堕落) | 被魔法腐化扭曲的生物 | 受损的动物、受污染的元素 |
| [Giants](/codex/Creatures/Monsters/Giants.md) (巨人) | 具有非凡力量的巨大生物 | 石巨人、冰霜巨人、食人魔 |

## 植物

具有独特属性的植物，包括魔法的和普通的：

| Category (类别) | Description (描述) | Examples (例子) |
|----------|-------------|----------|
| [Magical](/codex/Creatures/Plants/Magical.md) (魔法) | 具有内在魔法属性的植物 | 发光根、梦叶、奥术真菌 |
| [Medicinal](/codex/Creatures/Plants/Medicinal.md) (药用) | 具有治疗特性的植物 | 治疗师的草药、止血苔藓、活力花 |
| [Poisonous](/codex/Creatures/Plants/Poisonous.md) (有毒) | 具有毒性的植物 | 颠茄、死亡帽、毒液藤 |
| [Sentient](/codex/Creatures/Plants/Sentient.md) (有知觉) | 具有意识的植物 | 树人、低语柳树、心灵苔藓 |

## 混合生物

通过独特的生理学跨越多个类别的生物：

| Being (生物) | Overview (概述) | Elemental Balance (元素平衡) |
|-------|----------|-------------------|
| [Centaurs](/codex/Creatures/Hybrid/Centaurs.md) (半人马) | 具有自然智慧的马-类人杂交生物 | E: 50-70%, S: 20-40%, M: 10-25% |
| [Merfolk](/codex/Creatures/Hybrid/Merfolk.md) (美人鱼) | 具有水亲和力的水生类人动物 | E: 30-50%, S: 15-35%, M: 25-45% |
| [Sirens](/codex/Creatures/Hybrid/Sirens.md) (海妖) | 具有基于声音的魔法的声乐女巫 | E: 15-30%, S: 30-45%, M: 40-60% |

## 贡献

要向图鉴添加新生物：

1. 确定生物的适当类别
2. 使用该类别的相关模板
3. 与现有的元素组成原则保持一致
4. 在适用情况下包括文化、历史和生态背景

---

> *"了解我们世界的生物就是了解世界本身，因为它们是其多样化能量的生动体现。"* — 大贤者 Lyria Thornheart


---
_Note: This content was automatically translated by Google Gemini. Please refer to the original English version for accuracy._