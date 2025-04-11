# OpenFantasy World Codex

> *"魔法と驚異の世界が待っている。すべての魂が、存在の壮大な交響曲に貢献する場所"*

## 概要

OpenFantasy World Codexへようこそ。これはOpenFantasyユニバースに関する知識の包括的なリポジトリです。このコーデックスには、世界の基本原則、住人、魔法システム、場所、アイテムなどに関する詳細な情報が含まれています。

## クイックナビゲーション

- [世界の基礎](#world-fundamentals)
- [クリーチャーと種族](#creatures-and-species)
- [魔法システム](#magic-system)
- [キャラクタークラス](#character-classes)
- [世界の地理](#world-geography)
- [アイテムとアーティファクト](#items-and-artifacts)
- [リポジトリ構造](#repository-structure)

## 世界の基礎

OpenFantasyは、世界がどのように機能するかを支配するコア原則に基づいて構築されています。

| ディレクトリ | コンテンツ | 説明 |
|---|---|---|
| [Basic/](Basic/) | 基本的な概念 | OpenFantasyにおける現実の構成要素 |

主な概念は次のとおりです。

- **Exanthis**: 構造と形態を提供する物理的な基盤
- **Soul**: 意志とアイデンティティを提供する意識の火花
- **Mana**: すべてのものを通して流れる魔法のエネルギー
- **Elemental Balance**: 基本的な力同士の相互作用

## クリーチャーと種族

世界には、ユニークな特性を持つ多様な種族が生息しています。

| ディレクトリ | コンテンツ | 説明 |
|---|---|---|
| [Creatures/](Creatures/) | 種族のドキュメント | 世界に生息するさまざまな存在に関する情報 |

主な種族カテゴリは次のとおりです。

- **Primary Species**: ヒューマン、エルフ、ドワーフ、ビーストフォークなど
- **Magical Species**: フェイ、ゴーレム、セイレーン、シャドウフォークなど
- **Other Notable Species**: ダークエルフ、ケンタウロス、ノーム、マーフォークなど

→ 詳細については、[Creatures README](Creatures/README.md)を参照してください。

## 魔法システム

OpenFantasyの魔法は、体系的なルールと原則に従います。

| ディレクトリ | コンテンツ | 説明 |
|---|---|---|
| [Magics/](Magics/) | 魔法システム、呪文 | 魔法エネルギーのルールと具現化 |

主な魔法の概念は次のとおりです。

- **Elemental Magic**: 8つの主要な要素の操作
- **Mana Purity**: 魔法のエネルギーの洗練
- **Spell Structure**: 魔法の効果を形作るパターン
- **Enhancement Buffs**: 能力を強化する魔法の効果

→ 詳細については、[Magics README](Magics/README.md)を参照してください。

## キャラクタークラス

OpenFantasyのキャラクターは、特別な開発の道に従います。

| ディレクトリ | コンテンツ | 説明 |
|---|---|---|
| [Classes/](Classes/) | クラス情報、専門分野 | 力と専門分野のさまざまな道 |

主なクラスカテゴリは次のとおりです。

- **Martial Classes**: ウォーリアー、モンク、レンジャー
- **Magical Classes**: メイジ、ウォーロック、ドルイド
- **Hybrid Classes**: クレリック、バード、アーティフィサー
- **Specialized Classes**: ローグとサブクラス

→ 詳細については、[Classes README](Classes/README.md)を参照してください。

## 世界の地理

OpenFantasyの世界には、多様な地域と場所が含まれています。

| ディレクトリ | コンテンツ | 説明 |
|---|---|---|
| [World/](World/) | 場所、地理、歴史 | 世界の物理的および文化的景観 |

注目すべき地域は次のとおりです。

- **Eastern Veldrassil**: 魔法の森と学術センター
- **Western Veldrassil**: 山脈と採掘作業
- **Central Plains**: 農業の中心地と主要都市
- **Northern Reaches**: 凍てつく荒地と古代遺跡
- **Southern Isles**: 熱帯の群島と海洋文化

## アイテムとアーティファクト

世界には、力と重要性を持つ多数のオブジェクトが含まれています。

| ディレクトリ | コンテンツ | 説明 |
|---|---|---|
| [Items/](Items/) | 装備、アーティファクト、材料 | 力と有用性を持つオブジェクト |

アイテムカテゴリは次のとおりです。

- **Magical Equipment**: 魔法の特性を持つ武器、鎧、アクセサリー
- **Alchemical Substances**: ポーション、エリクサー、魔法の試薬
- **Artifacts**: 重要な力を持つ古代のオブジェクト
- **Everyday Items**: 文化的な重要性を持つ平凡なオブジェクト

## リポジトリ構造

OpenFantasy Codexは、一貫した構造で編成されています。

```
codex/
├── README.md                # この概要ドキュメント
├── Basic/                   # 基本的な概念
├── Creatures/               # 種族のドキュメント
│   ├── README.md            # クリーチャーの概要
│   ├── Creatures.md         # 一般的な種族情報
│   ├── Human.md             # 個々の種族ドキュメント
│   └── ...                  # その他の種族ドキュメント
├── Magics/                  # 魔法システム
│   ├── README.md            # 魔法の概要
│   ├── Spells/              # 呪文のドキュメント
│   └── ...                  # 魔法システムのドキュメント
├── Classes/                 # キャラクタークラス
│   ├── README.md            # クラスの概要
│   ├── Warrior/             # クラス固有のディレクトリ
│   └── ...                  # その他のクラスディレクトリ
├── World/                   # 地理と場所
│   ├── README.md            # 世界の概要
│   └── ...                  # 地域と場所のドキュメント
└── Items/                   # 装備とアーティファクト
    ├── README.md            # アイテムの概要
    └── ...                  # アイテムカテゴリのドキュメント
```

### ドキュメントの標準

このリポジトリのすべてのドキュメントは、一貫した形式に従います。

- **README.md ファイル**は、概要とナビゲーションを提供します
- ドキュメントの上部にある**クイックリファレンスセクション**
- 比較情報のための**テーブル**
- ドキュメント全体で同様の情報に対する**一貫したヘッダー**
- 関連コンテンツへの**相互参照**
- より良い表示体験のための**Git最適化されたマークダウン**

---

> **注**: このコーデックスは、時間の経過とともに拡張および改良される可能性のある生きたドキュメントです。すべてのコンテンツは、OpenFantasyの世界を定義する音楽のメタファーに従います。


---
_Note: This content was automatically translated by Google Gemini. Please refer to the original English version for accuracy._