# OpenFantasy キャラクタークラス

> *"全ての魂は、力のシンフォニーの中で独自の旋律を見つける。"*

## 概要

OpenFantasy キャラクタークラスのドキュメントへようこそ。このリポジトリには、OpenFantasy の世界でキャラクターが利用できる、様々な力と専門分野の道に関する包括的な情報が含まれています。

## クイックナビゲーション

- [クラスの基礎](#class-fundamentals)
- [プライマリークラス](#primary-classes)
- [キャラクターの成長](#character-progression)
- [マルチクラス](#multiclassing)
- [種族の親和性](#species-affinities)
- [ドキュメントの構成](#documentation-structure)

## クラスの基礎

OpenFantasy のクラスは、キャラクターの生来の能力を活用し、発展させる専門的な道を表現します。

| 概念 | 説明 |
|---------|-------------|
| **クラス構造** | 能力と専門分野の組織 |
| **元素構成** | Exanthis、Soul、および Mana Capacity のバランス |
| **サブクラス** | 各コアクラスの特殊な分派 |
| **クラスの成長** | クラス能力の発展パス |
| **装備** | クラスの能力を強化するツールとアイテム |

## プライマリークラス

OpenFantasy には 10 個のプライマリークラスがあり、それぞれに独自の専門分野があります。

| クラス | コアフォーカス | 主要な属性 | クラスディレクトリ |
|-------|------------|-------------------|----------------|
| **Warrior** | 物理戦闘 | Exanthis | [Warrior/](Warrior/) |
| **Mage** | 秘術的な呪文詠唱 | Mana Capacity | [Mage/](Mage/) |
| **Rogue** | 隠密と精密さ | Soul | [Rogue/](Rogue/) |
| **Cleric** | 神聖魔法 | Soul/Mana | [Cleric/](Cleric/) |
| **Ranger** | 荒野と追跡 | Exanthis/Soul | [Ranger/](Ranger/) |
| **Artificer** | 魔法創造 | Mana Capacity | [Artificer/](Artificer/) |
| **Bard** | パフォーマンス魔法 | Soul/Mana | [Bard/](Bard/) |
| **Druid** | 自然魔法 | Soul/Mana | [Druid/](Druid/) |
| **Monk** | 内なるエネルギー | Exanthis/Soul | [Monk/](Monk/) |
| **Warlock** | 契約魔法 | Soul/Mana | [Warlock/](Warlock/) |

→ 各クラスの詳細については、[クラスの概要](Classes.md)を参照してください。

## キャラクターの成長

キャラクターの成長は、階層化された成長システムに従います。

### レベル層

| 層 | レベル | 説明 |
|------|--------|-------------|
| **Novice** | 1-5 | クラスの基礎を学ぶ |
| **Adept** | 6-10 | 基本を習得し、専門分野を開発する |
| **Expert** | 11-15 | 能力を高度に磨く |
| **Master** | 16-20 | 選択した道の習得を達成する |
| **Legendary** | 21+ | 通常の制限を超える |

## マルチクラス

キャラクターは複数のクラスパスを同時に追求し、能力のユニークな組み合わせを作成できます。この汎用性は、単一の分野における専門的な習得を犠牲にします。

### 一般的なマルチクラスの組み合わせ

| 組み合わせ | シナジー |
|-------------|---------|
| Warrior/Mage | 魔法能力で強化された物理戦闘 |
| Cleric/Warrior | 武道の腕前を備えた神聖魔法 |
| Rogue/Ranger | 荒野の専門知識と組み合わせた隠密 |
| Bard/Warlock | 契約能力で強化されたパフォーマンス魔法 |
| Druid/Monk | 物理的な鍛錬と組み合わせた自然魔法 |

## 種族の親和性

種族によって、その元素構成に基づいて特定のクラスに対する自然な親和性があります。

| 種族 | 自然なクラスの親和性 |
|---------|--------------------------|
| **Humans** | すべてのクラスに対するバランスの取れた親和性 |
| **Elves** | Mage, Ranger, Bard |
| **Dark Elves** | Mage, Rogue, Warlock |
| **Dwarves** | Warrior, Artificer, Cleric |
| **Beastfolk** | Ranger, Druid, Warrior |
| **Dragonkin** | Warrior, Mage, Warlock |
| **Fae** | Bard, Druid, Mage |
| **Golems** | Artificer, Warrior |
| **Sirens** | Bard, Mage |
| **Shadowfolk** | Rogue, Warlock, Mage |
| **Giants** | Warrior, Druid |

## 元素構成

各クラスは、その能力を形作る特徴的な元素構成を備えています。

| クラス | Exanthis | Soul | Mana Capacity | 主要な魔法の親和性 |
|-------|----------|------|---------------|--------------------------|
| **Warrior** | 50-70% | 20-35% | 10-20% | Terramana (安定性), Base Mana (力) |
| **Mage** | 10-25% | 15-35% | 50-70% | 専門分野によって異なる |
| **Rogue** | 30-45% | 40-60% | 10-25% | Umbramana (隠蔽), Aeromana (機動性) |
| **Cleric** | 20-35% | 30-50% | 25-45% | Luxmana (光), Vitamana (癒し) |
| **Ranger** | 35-55% | 30-45% | 15-30% | Vitamana (自然), Aeromana (移動) |
| **Artificer** | 25-40% | 20-35% | 35-55% | Crystallmana (構造), Terramana (堅牢性) |
| **Bard** | 15-30% | 35-55% | 25-45% | Fulgumana (音), Aeromana (コミュニケーション) |
| **Druid** | 20-35% | 30-45% | 30-50% | Vitamana (成長), Terramana (大地) |
| **Monk** | 40-55% | 30-50% | 10-25% | Base Mana (内部エネルギー), Aeromana (移動) |
| **Warlock** | 15-30% | 25-40% | 40-60% | Aetheramana (虚無), 契約によって異なる |

この元素のバランスは、特定の専門的な魔法の形態に対するクラスの自然な親和性と、全体的な魔法能力に直接影響を与えます。

- **専門分野の効率**: Mana Capacity が高いクラスは、通常、より優れた元素専門分野の割合を達成します
- **マナの浄化**: Soul から Mana Capacity への比率は、Wild Mana を Base Mana に浄化するクラスの能力に影響を与えます
- **魔法のスタミナ**: Exanthis が高いほど、物理的な耐久性が向上しますが、通常は魔法の効率が低下します
- **ハイブリッドの可能性**: よりバランスの取れた構成を持つクラスは、多くの場合、異なる元素タイプを組み合わせるのに優れています

## ドキュメントの構成

Classes ディレクトリは次のように構成されています。

```
codex/Classes/
├── README.md                # この概要ドキュメント
├── Classes.md               # 詳細な説明を含むメインクラスドキュメント
├── template_README.md       # クラスディレクトリの README ファイルを作成するためのテンプレート
├── Warrior/                 # クラスディレクトリの例
│   ├── README.md            # クラス固有の概要
│   ├── Warrior.md           # 詳細なクラス情報
│   ├── Guardian.md          # サブクラスのドキュメント
│   ├── Berserker.md         # サブクラスのドキュメント
│   └── ...                  # その他のサブクラスドキュメント
└── ...                      # その他のクラスディレクトリ
```

### テンプレートの使用

新しいクラス README を作成するには、[template_README.md](template_README.md) ファイルをコピーし、プレースホルダーの値をクラス固有の情報に置き換えます。

1. `[CLASS_NAME]` をクラスの名前に置き換えます
2. 構成範囲と説明を入力します
3. フォーカスエリアと専門分野を持つサブクラスをリストします
4. コア能力、装備、および種族の親和性を文書化します
5. クラスの強みと課題を説明します

---

> **リポジトリの構造**: このドキュメントでは、Git プラットフォームでの表示に最適化された Markdown 形式を使用しています。


---
_Note: This content was automatically translated by Google Gemini. Please refer to the original English version for accuracy._