# OpenFantasy 生物図鑑

> *"世界は無数の存在の声で歌い、それぞれが壮大な存在の交響曲の中で自分の役割を果たしている。"*

## 概要

OpenFantasy 生物ドキュメントへようこそ。このリポジトリには、OpenFantasy (OpenFantasy) の世界に生息するさまざまな存在（知的種族、動物、モンスター、植物、その他の存在）に関する包括的な情報が含まれています。

## ディレクトリ構造

```
/Creatures
├── README.md                # この概要ドキュメント
├── Creatures.md             # コアとなる原則と要素構成
├── template_species.md      # 新しい種族エントリを作成するためのテンプレート
├── /Sentient                # 知的で文明を形成する種族
│   ├── README.md            # 知的種族の概要
│   ├── Humans.md            # ヒューマン
│   ├── Elves.md             # エルフ
│   ├── DarkElves.md         # ダークエルフ
│   ├── Dwarves.md           # ドワーフ
│   └── ...
├── /Magical                 # 主に魔法または妖精の存在
│   ├── README.md            # 魔法の存在の概要
│   ├── Fae.md               # フェイ
│   ├── Golems.md            # ゴーレム
│   ├── Elementals.md        # エレメンタル
│   └── ...
├── /Animals                 # 知性を持たない自然の動物相
│   ├── README.md            # 動物の概要
│   ├── Domesticated.md      # 家畜化
│   ├── Wild.md              # 野生
│   ├── Aquatic.md           # 水生
│   └── ...
├── /Monsters                # 危険または不自然な生き物
│   ├── README.md            # モンスターの概要
│   ├── Aberrations.md      # アベレーション
│   ├── Undead.md            # アンデッド
│   ├── Corrupted.md         # 堕落
│   └── ...
├── /Plants                  # ユニークな特性を持つ植物相
│   ├── README.md            # 魔法と普通の植物の概要
│   ├── Magical.md           # 魔法
│   ├── Medicinal.md         # 薬用
│   ├── Poisonous.md         # 有毒
│   └── ...
└── /Hybrid                  # クロスカテゴリの存在
    ├── README.md            # ハイブリッド生物の概要
    ├── Centaurs.md          # ケンタウロス
    ├── Merfolk.md           # マーフォーク
    └── ...
```

## クイックナビゲーション

- [コアコンセプト](#core-concepts)
- [知的種族](#sentient-species)
- [魔法の存在](#magical-beings)
- [動物](#animals)
- [モンスター](#monsters)
- [植物](#plants)
- [ハイブリッド生物](#hybrid-beings)

## コアコンセプト

OpenFantasy (OpenFantasy) のすべての生物は、その性質と能力を決定する3つの基本的な要素で構成されています。

| Component (構成要素) | Function (機能) | Influence (影響) |
|-----------|----------|-----------|
| **Exanthis** | 物理的な基盤 | 強さ、耐久力、持続力 |
| **Soul** (魂) | 意識とアイデンティティ | 意志力、創造性、知覚 |
| **Mana Capacity** (マナ容量) | 魔法の可能性 | 呪文能力、魔法耐性、マナ浄化 |

これらの原則の詳細については、[生物の概要](/codex/Creatures/Creatures.md)を参照してください。

## 知的種族

文明を形成し、文化を創造し、意識的な努力によって魔法を操ることができる知的な存在：

| Species (種族) | Overview (概要) | Elemental Balance (要素バランス) |
|---------|----------|-------------------|
| [Humans](/codex/Creatures/Sentient/Humans.md) (人間) | バランスの取れた構成で適応力と革新性がある | E: 20-55%, S: 15-45%, M: 15-60% |
| [Elves](/codex/Creatures/Sentient/Elves.md) (エルフ) | 高いマナ適性を持つ長命の魔法熟練者 | E: 5-25%, S: 5-15%, M: 50-80% |
| [Dark Elves](/codex/Creatures/Sentient/DarkElves.md) (ダークエルフ) | ユニークな能力を持つ影に調和したエルフの変種 | E: 5-25%, S: 10-20%, M: 50-80% |
| [Dwarves](/codex/Creatures/Sentient/Dwarves.md) (ドワーフ) | Exanthis (エクザンティス) 濃度が高い頑丈な職人 | E: 50-70%, S: 20-35%, M: 5-25% |
| [Beastfolk](/codex/Creatures/Sentient/Beastfolk.md) (獣人) | 動物のような属性を持つ多様な存在 | E: 35-70%, S: 15-35%, M: 15-40% |
| [Gnomes](/codex/Creatures/Sentient/Gnomes.md) (ノーム) | 技術的な適性を持つ小さく、発明好きな存在 | E: 30-50%, S: 30-50%, M: 15-30% |

## 魔法の存在

主に魔法のエネルギーで構成されているか、魔法のプロセスを通じて作成された生物：

| Being (存在) | Overview (概要) | Elemental Balance (要素バランス) |
|-------|----------|-------------------|
| [Fae](/codex/Creatures/Magical/Fae.md) (妖精) | ほぼ純粋な魔法の幽玄な存在 | E: 2-10%, S: 15-35%, M: 50-80% |
| [Golems](/codex/Creatures/Magical/Golems.md) (ゴーレム) | 人工の魂を持つ構築された存在 | E: 70-90%, S: 5-15%, M: 5-15% |
| [Shadowfolk](/codex/Creatures/Magical/Shadowfolk.md) (影人) | 闇を操る影から生まれた存在 | E: 10-30%, S: 20-40%, M: 40-70% |
| [Elementals](/codex/Creatures/Magical/Elementals.md) (精霊) | 元素の力の純粋な具現化 | E: 15-30%, S: 5-15%, M: 60-85% |
| [Dragonkin](/codex/Creatures/Magical/Dragonkin.md) (竜人) | 生まれつき魔法の親和性を持つドラゴンの子孫 | E: 55-75%, S: 5-15%, M: 20-35% |

## 動物

さまざまな程度の知性と魔法の親和性を持つ、知性を持たない動物相：

| Category (カテゴリー) | Description (説明) | Examples (例) |
|----------|-------------|----------|
| [Domesticated](/codex/Creatures/Animals/Domesticated.md) (家畜化) | 人間の使用のために飼育された動物 | 馬、牛、犬、猫、家禽 |
| [Wild](/codex/Creatures/Animals/Wild.md) (野生) | さまざまなバイオームの自然動物相 | オオカミ、クマ、ワシ、鹿 |
| [Aquatic](/codex/Creatures/Animals/Aquatic.md) (水生) | 海と淡水の生き物 | 魚、鯨、タコ、川の生き物 |
| [Magical](/codex/Creatures/Animals/Magical.md) (魔法) | 生まれつき魔法の特性を持つ動物 | 不死鳥、グリフォン、ユニコーン |

## モンスター

文明化された地域に脅威を与える危険または不自然な生き物：

| Category (カテゴリー) | Description (説明) | Examples (例) |
|----------|-------------|----------|
| [Aberrations](/codex/Creatures/Monsters/Aberrations.md) (アベレーション) | 奇妙な解剖学を持つ不自然な生き物 | ミミック、ビホルダー、マインドフレイヤー |
| [Undead](/codex/Creatures/Monsters/Undead.md) (アンデッド) | 闇の力によってアニメートされた、かつて生きていた存在 | ゾンビ、スケルトン、スペクター |
| [Corrupted](/codex/Creatures/Monsters/Corrupted.md) (堕落) | 魔法の堕落によってねじれた存在 | 荒廃した動物、汚染された精霊 |
| [Giants](/codex/Creatures/Monsters/Giants.md) (巨人) | 並外れた力を持つ巨大な存在 | 石の巨人、霜の巨人、オーガ |

## 植物

魔法と普通のユニークな特性を持つ植物相：

| Category (カテゴリー) | Description (説明) | Examples (例) |
|----------|-------------|----------|
| [Magical](/codex/Creatures/Plants/Magical.md) (魔法) | 固有の魔法の特性を持つ植物 | グロールート、ドリームリーフ、秘術の菌類 |
| [Medicinal](/codex/Creatures/Plants/Medicinal.md) (薬用) | 治癒特性を持つ植物 | ヒーラーのハーブ、血液停止苔、活力の花 |
| [Poisonous](/codex/Creatures/Plants/Poisonous.md) (有毒) | 有毒な特性を持つ植物 | ベラドンナ、ドクツルタケ、毒のつる |
| [Sentient](/codex/Creatures/Plants/Sentient.md) (知性) | 意識のある植物 | トレント、ささやくヤナギ、マインドモス |

## ハイブリッド生物

ユニークな生理学を通じて複数のカテゴリーを結び付ける生物：

| Being (存在) | Overview (概要) | Elemental Balance (要素バランス) |
|-------|----------|-------------------|
| [Centaurs](/codex/Creatures/Hybrid/Centaurs.md) (ケンタウロス) | 自然な知恵を持つ馬と人間のハイブリッド | E: 50-70%, S: 20-40%, M: 10-25% |
| [Merfolk](/codex/Creatures/Hybrid/Merfolk.md) (マーフォーク) | 水の親和性を持つ水生の人型 | E: 30-50%, S: 15-35%, M: 25-45% |
| [Sirens](/codex/Creatures/Hybrid/Sirens.md) (セイレーン) | 音ベースの魔法を持つボーカルエンチャントレス | E: 15-30%, S: 30-45%, M: 40-60% |

## 貢献

新しい生物を図鑑に追加するには：

1. 生物の適切なカテゴリを特定する
2. そのカテゴリの関連するテンプレートを使用する
3. 既存の要素構成の原則との一貫性を維持する
4. 該当する場合は、文化的、歴史的、生態学的コンテキストを含める

---

> *"私たちの世界の生き物を理解することは、世界そのものを理解することです。なぜなら、彼らはその多様なエネルギーの生きた具現化だからです。"* — 大賢者ライリア・ソーンハート


---
_Note: This content was automatically translated by Google Gemini. Please refer to the original English version for accuracy._