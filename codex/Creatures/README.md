# OpenFantasy 생물 도감

> *"세계는 무수한 존재들의 목소리로 노래하며, 각자는 웅장한 존재의 교향곡에서 자신의 역할을 수행합니다."*

## 개요

OpenFantasy 생물 문서에 오신 것을 환영합니다. 이 저장소는 지각 있는 종, 동물, 괴물, 식물 및 기타 개체를 포함하여 OpenFantasy 세계에 서식하는 다양한 존재에 대한 포괄적인 정보를 담고 있습니다.

## 디렉토리 구조

```
/Creatures
├── README.md                # 이 개요 문서
├── Creatures.md             # 핵심 원칙 및 원소 구성
├── template_species.md      # 새로운 종 항목 생성을 위한 템플릿
├── /Sentient                # 지능이 있고, 문명을 형성하는 종
│   ├── README.md            # 지각 있는 종 개요
│   ├── Humans.md (인간)
│   ├── Elves.md (엘프)
│   ├── DarkElves.md (다크 엘프)
│   ├── Dwarves.md (드워프)
│   └── ...
├── /Magical                 # 주로 마법적이거나 요정인 존재
│   ├── README.md            # 마법적 존재 개요
│   ├── Fae.md (페이)
│   ├── Golems.md (골렘)
│   ├── Elementals.md (엘리멘탈)
│   └── ...
├── /Animals                 # 지각이 없는 자연 동물군
│   ├── README.md            # 동물 개요
│   ├── Domesticated.md (길들여진 동물)
│   ├── Wild.md (야생 동물)
│   ├── Aquatic.md (수생 동물)
│   └── ...
├── /Monsters                # 위험하거나 부자연스러운 생물
│   ├── README.md            # 괴물 개요
│   ├── Aberrations.md (이형)
│   ├── Undead.md (언데드)
│   ├── Corrupted.md (타락한 존재)
│   └── ...
├── /Plants                  # 독특한 속성을 가진 식물
│   ├── README.md            # 마법 및 일반 식물 개요
│   ├── Magical.md (마법 식물)
│   ├── Medicinal.md (약용 식물)
│   ├── Poisonous.md (독성 식물)
│   └── ...
└── /Hybrid                  # 범주를 넘나드는 존재
    ├── README.md            # 혼종 생물 개요
    ├── Centaurs.md (켄타우로스)
    ├── Merfolk.md (인어)
    └── ...
```

## 빠른 탐색

- [핵심 개념](#core-concepts)
- [지각 있는 종](#sentient-species)
- [마법적 존재](#magical-beings)
- [동물](#animals)
- [괴물](#monsters)
- [식물](#plants)
- [혼종 존재](#hybrid-beings)

## 핵심 개념

OpenFantasy의 모든 생물은 그 본성과 능력을 결정하는 세 가지 근본적인 요소로 구성됩니다.

| Component (구성 요소) | Function (기능) | Influence (영향) |
|---|---|---|
| **Exanthis** | 물리적 기반 | 힘, 지구력, 내구성 |
| **Soul** | 의식 및 정체성 | 의지력, 창의력, 지각 |
| **Mana Capacity** | 마법 잠재력 | 주문 능력, 마법 저항, 마나 정화 |

이러한 원칙에 대한 자세한 내용은 [Creatures overview](/codex/Creatures/Creatures.md)를 참조하십시오.

## 지각 있는 종

문명을 형성하고 문화를 창조하며 의식적인 노력을 통해 마법을 휘두를 수 있는 지능적인 존재:

| Species (종) | Overview (개요) | Elemental Balance (원소 균형) |
|---|---|---|
| [Humans](/codex/Creatures/Sentient/Humans.md) | 균형 잡힌 구성으로 적응력이 뛰어나고 혁신적임 | E: 20-55%, S: 15-45%, M: 15-60% |
| [Elves](/codex/Creatures/Sentient/Elves.md) | 높은 마나 조율을 가진 장수하는 마법 전문가 | E: 5-25%, S: 5-15%, M: 50-80% |
| [Dark Elves](/codex/Creatures/Sentient/DarkElves.md) | 독특한 능력을 가진 그림자 조율 엘프 변종 | E: 5-25%, S: 10-20%, M: 50-80% |
| [Dwarves](/codex/Creatures/Sentient/Dwarves.md) | 높은 Exanthis 농도를 가진 튼튼한 장인 | E: 50-70%, S: 20-35%, M: 5-25% |
| [Beastfolk](/codex/Creatures/Sentient/Beastfolk.md) | 동물과 같은 속성을 가진 다양한 존재 | E: 35-70%, S: 15-35%, M: 15-40% |
| [Gnomes](/codex/Creatures/Sentient/Gnomes.md) | 기술적 재능을 가진 작고 독창적인 존재 | E: 30-50%, S: 30-50%, M: 15-30% |

## 마법적 존재

주로 마법 에너지로 구성되거나 마법적 과정을 통해 창조된 생물:

| Being (존재) | Overview (개요) | Elemental Balance (원소 균형) |
|---|---|---|
| [Fae](/codex/Creatures/Magical/Fae.md) | 거의 순수한 마법의 무형의 존재 | E: 2-10%, S: 15-35%, M: 50-80% |
| [Golems](/codex/Creatures/Magical/Golems.md) | 인공 영혼을 가진 구축된 존재 | E: 70-90%, S: 5-15%, M: 5-15% |
| [Shadowfolk](/codex/Creatures/Magical/Shadowfolk.md) | 어둠 조작을 가진 그림자에서 태어난 존재 | E: 10-30%, S: 20-40%, M: 40-70% |
| [Elementals](/codex/Creatures/Magical/Elementals.md) | 원소 힘의 순수한 구현 | E: 15-30%, S: 5-15%, M: 60-85% |
| [Dragonkin](/codex/Creatures/Magical/Dragonkin.md) | 타고난 마법 친화력을 가진 용의 후손 | E: 55-75%, S: 5-15%, M: 20-35% |

## 동물

다양한 수준의 지능과 마법적 친화력을 가진 지각이 없는 동물군:

| Category (분류) | Description (설명) | Examples (예시) |
|---|---|---|
| [Domesticated](/codex/Creatures/Animals/Domesticated.md) | 인간의 사용을 위해 사육된 동물 | 말, 소, 개, 고양이, 가금류 |
| [Wild](/codex/Creatures/Animals/Wild.md) | 다양한 생물 군계의 자연 동물군 | 늑대, 곰, 독수리, 사슴 |
| [Aquatic](/codex/Creatures/Animals/Aquatic.md) | 해양 및 담수 생물 | 물고기, 고래, 문어, 강 생물 |
| [Magical](/codex/Creatures/Animals/Magical.md) | 타고난 마법 속성을 가진 동물 | 불사조, 그리핀, 유니콘 |

## 괴물

문명 지역에 위협을 가하는 위험하거나 부자연스러운 생물:

| Category (분류) | Description (설명) | Examples (예시) |
|---|---|---|
| [Aberrations](/codex/Creatures/Monsters/Aberrations.md) | 기괴한 해부학을 가진 부자연스러운 생물 | 미믹, 베홀더, 마인드 플레이어 |
| [Undead](/codex/Creatures/Monsters/Undead.md) | 어두운 힘에 의해 움직이는 이전의 살아있는 존재 | 좀비, 해골, 유령 |
| [Corrupted](/codex/Creatures/Monsters/Corrupted.md) | 마법적 타락에 의해 뒤틀린 존재 | 오염된 동물, 변질된 엘리멘탈 |
| [Giants](/codex/Creatures/Monsters/Giants.md) | 엄청난 힘을 가진 거대한 존재 | 돌 거인, 서리 거인, 오우거 |

## 식물

마법적 속성과 평범한 속성을 모두 가진 독특한 속성의 식물군:

| Category (분류) | Description (설명) | Examples (예시) |
|---|---|---|
| [Magical](/codex/Creatures/Plants/Magical.md) | 고유한 마법적 속성을 가진 식물 | 글로우루트, 드림리프, 아케인 곰팡이 |
| [Medicinal](/codex/Creatures/Plants/Medicinal.md) | 치유 속성을 가진 식물 | 치료사의 허브, 지혈 이끼, 활력 꽃 |
| [Poisonous](/codex/Creatures/Plants/Poisonous.md) | 독성 속성을 가진 식물 | 벨라돈나, 독우산광대버섯, 독 덩굴 |
| [Sentient](/codex/Creatures/Plants/Sentient.md) | 의식을 가진 식물 | 트렌트, 속삭이는 버드나무, 마인드모스 |

## 혼종 존재

독특한 생리를 통해 여러 범주를 연결하는 생물:

| Being (존재) | Overview (개요) | Elemental Balance (원소 균형) |
|---|---|---|
| [Centaurs](/codex/Creatures/Hybrid/Centaurs.md) | 타고난 지혜를 가진 말-인간형 하이브리드 | E: 50-70%, S: 20-40%, M: 10-25% |
| [Merfolk](/codex/Creatures/Hybrid/Merfolk.md) | 물 친화력을 가진 수생 인간형 | E: 30-50%, S: 15-35%, M: 25-45% |
| [Sirens](/codex/Creatures/Hybrid/Sirens.md) | 소리 기반 마법을 사용하는 보컬 마법사 | E: 15-30%, S: 30-45%, M: 40-60% |

## 기여하기

도감에 새로운 생물을 추가하려면:

1. 생물에 적합한 범주를 식별합니다.
2. 해당 범주에 대한 관련 템플릿을 사용합니다.
3. 기존 원소 구성 원칙과의 일관성을 유지합니다.
4. 해당되는 경우 문화적, 역사적 및 생태적 맥락을 포함합니다.

---

> *"우리 세계의 생물을 이해하는 것은 세계 자체를 이해하는 것입니다. 왜냐하면 그들은 다양한 에너지의 살아있는 구현이기 때문입니다."* — 대현자 리리아 쏜하트


---
_Note: This content was automatically translated by Google Gemini. Please refer to the original English version for accuracy._