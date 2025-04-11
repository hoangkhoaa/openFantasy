# OpenFantasy 생물 도감

> *“세계는 수많은 존재들의 목소리로 노래하며, 각자 존재의 웅대한 교향곡에서 자신의 역할을 수행합니다.”*

## 개요

OpenFantasy 생물 문서에 오신 것을 환영합니다. 이 저장소는 지성 있는 종족, 동물, 몬스터, 식물 및 기타 개체를 포함하여 OpenFantasy 세계에 서식하는 다양한 존재에 대한 포괄적인 정보를 담고 있습니다.

## 디렉토리 구조

```
/Creatures
├── README.md                # 이 개요 문서
├── Creatures.md             # 핵심 원칙 및 원소 구성
├── template_species.md      # 새로운 종 항목 생성을 위한 템플릿
├── /Sentient                # 지능이 있고 문명을 형성하는 종족
│   ├── README.md            # 지성 있는 종족 개요
│   ├── Humans.md
│   ├── Elves.md
│   ├── DarkElves.md
│   ├── Dwarves.md
│   └── ...
├── /Magical                 # 주로 마법적이거나 요정인 존재
│   ├── README.md            # 마법적인 존재 개요
│   ├── Fae.md
│   ├── Golems.md
│   ├── Elementals.md
│   └── ...
├── /Animals                 # 지능이 없는 자연 동물군
│   ├── README.md            # 동물 개요
│   ├── Domesticated.md
│   ├── Wild.md
│   ├── Aquatic.md
│   └── ...
├── /Monsters                # 위험하거나 부자연스러운 생물
│   ├── README.md            # 몬스터 개요
│   ├── Aberrations.md
│   ├── Undead.md
│   ├── Corrupted.md
│   └── ...
├── /Plants                  # 독특한 속성을 가진 식물
│   ├── README.md            # 마법 및 평범한 식물 개요
│   ├── Magical.md
│   ├── Medicinal.md
│   ├── Poisonous.md
│   └── ...
└── /Hybrid                  # 교차 범주 존재
    ├── README.md            # 혼종 생물 개요
    ├── Centaurs.md
    ├── Merfolk.md
    └── ...
```

## 빠른 탐색

- [핵심 개념](#핵심-개념)
- [지성 있는 종족](#지성-있는-종족)
- [마법적인 존재](#마법적인-존재)
- [동물](#동물)
- [몬스터](#몬스터)
- [식물](#식물)
- [혼종 존재](#혼종-존재)

## 핵심 개념

OpenFantasy의 모든 생물은 세 가지 기본적인 요소로 구성되어 있으며, 이는 그들의 본성과 능력을 결정합니다.

| 구성 요소 | 기능 | 영향력 |
|-----------|----------|-----------|
| **엑산티스 (Exanthis)** | 물리적 기반 | 힘, 지구력, 내구성 |
| **영혼 (Soul)** | 의식 및 정체성 | 의지력, 창의력, 지각력 |
| **마나 용량 (Mana Capacity)** | 마법 잠재력 | 주문 능력, 마법 저항력, 마나 정화 |

이러한 원칙에 대한 자세한 내용은 [생물 개요](/codex/Creatures/Creatures.md)를 참조하십시오.

## 지성 있는 종족

문명을 형성하고, 문화를 창조하며, 의식적인 노력을 통해 마법을 휘두를 수 있는 지능적인 존재:

| 종족 | 개요 | 원소 균형 |
|---------|----------|-------------------|
| [인간](/codex/Creatures/Sentient/Humans.md) | 균형 잡힌 구성으로 적응력이 뛰어나고 혁신적임 | E: 20-55%, S: 15-45%, M: 15-60% |
| [엘프](/codex/Creatures/Sentient/Elves.md) | 높은 마나 조율을 가진 장수하는 마법 전문가 | E: 5-25%, S: 5-15%, M: 50-80% |
| [다크 엘프](/codex/Creatures/Sentient/DarkElves.md) | 독특한 능력을 가진 그림자에 조율된 엘프 변종 | E: 5-25%, S: 10-20%, M: 50-80% |
| [드워프](/codex/Creatures/Sentient/Dwarves.md) | 높은 엑산티스 집중을 가진 튼튼한 장인 | E: 50-70%, S: 20-35%, M: 5-25% |
| [수인](/codex/Creatures/Sentient/Beastfolk.md) | 동물과 같은 속성을 가진 다양한 존재 | E: 35-70%, S: 15-35%, M: 15-40% |
| [놈](/codex/Creatures/Sentient/Gnomes.md) | 기술적 재능을 가진 작고 독창적인 존재 | E: 30-50%, S: 30-50%, M: 15-30% |

## 마법적인 존재

주로 마법 에너지로 구성되거나 마법적 과정을 통해 창조된 생물:

| 존재 | 개요 | 원소 균형 |
|-------|----------|-------------------|
| [페이](/codex/Creatures/Magical/Fae.md) | 거의 순수한 마법의 미묘한 존재 | E: 2-10%, S: 15-35%, M: 50-80% |
| [골렘](/codex/Creatures/Magical/Golems.md) | 인공적인 영혼을 가진 구조된 존재 | E: 70-90%, S: 5-15%, M: 5-15% |
| [섀도우포크](/codex/Creatures/Magical/Shadowfolk.md) | 어둠 조작을 가진 그림자에서 태어난 존재 | E: 10-30%, S: 20-40%, M: 40-70% |
| [엘리멘탈](/codex/Creatures/Magical/Elementals.md) | 원소 힘의 순수한 구현체 | E: 15-30%, S: 5-15%, M: 60-85% |
| [드래곤킨](/codex/Creatures/Magical/Dragonkin.md) | 자연적인 마법 친화력을 가진 용의 후손 | E: 55-75%, S: 5-15%, M: 20-35% |

## 동물

다양한 정도의 지능과 마법 친화력을 가진 지능이 없는 동물군:

| 카테고리 | 설명 | 예시 |
|----------|-------------|----------|
| [가축](/codex/Creatures/Animals/Domesticated.md) | 인간의 사용을 위해 사육된 동물 | 말, 소, 개, 고양이, 가금류 |
| [야생](/codex/Creatures/Animals/Wild.md) | 다양한 생물 군계의 자연 동물군 | 늑대, 곰, 독수리, 사슴 |
| [수생](/codex/Creatures/Animals/Aquatic.md) | 바다 및 담수 생물 | 물고기, 고래, 문어, 강 생물 |
| [마법](/codex/Creatures/Animals/Magical.md) | 타고난 마법 속성을 가진 동물 | 불사조, 그리핀, 유니콘 |

## 몬스터

문명화된 지역에 위협을 가하는 위험하거나 부자연스러운 생물:

| 카테고리 | 설명 | 예시 |
|----------|-------------|----------|
| [기형](/codex/Creatures/Monsters/Aberrations.md) | 기괴한 해부학적 구조를 가진 부자연스러운 생물 | 미믹, 베홀더, 마인드 플레이어 |
| [언데드](/codex/Creatures/Monsters/Undead.md) | 어둠의 힘에 의해 움직이는 이전의 살아있는 존재 | 좀비, 해골, 스펙터 |
| [타락](/codex/Creatures/Monsters/Corrupted.md) | 마법적 타락에 의해 뒤틀린 존재 | 오염된 동물, 변질된 엘리멘탈 |
| [거인](/codex/Creatures/Monsters/Giants.md) | 비범한 힘을 가진 거대한 존재 | 돌 거인, 서리 거인, 오우거 |

## 식물

마법과 평범한 독특한 속성을 가진 식물군:

| 카테고리 | 설명 | 예시 |
|----------|-------------|----------|
| [마법](/codex/Creatures/Plants/Magical.md) | 고유한 마법적 속성을 가진 식물 | 글로우루트, 드림리프, 아케인 곰팡이 |
| [약용](/codex/Creatures/Plants/Medicinal.md) | 치유 속성을 가진 식물 | 치료사의 허브, 지혈 이끼, 활력 꽃 |
| [독성](/codex/Creatures/Plants/Poisonous.md) | 독성 속성을 가진 식물 | 벨라도나, 독우산버섯, 독 덩굴 |
| [지성](/codex/Creatures/Plants/Sentient.md) | 의식을 가진 식물 | 트렌트, 속삭이는 버드나무, 마인드모스 |

## 혼종 존재

독특한 생리를 통해 여러 카테고리를 연결하는 생물:

| 존재 | 개요 | 원소 균형 |
|-------|----------|-------------------|
| [켄타우로스](/codex/Creatures/Hybrid/Centaurs.md) | 자연적인 지혜를 가진 말-인간형 혼종 | E: 50-70%, S: 20-40%, M: 10-25% |
| [인어](/codex/Creatures/Hybrid/Merfolk.md) | 물 친화력을 가진 수생 인간형 | E: 30-50%, S: 15-35%, M: 25-45% |
| [사이렌](/codex/Creatures/Hybrid/Sirens.md) | 소리 기반 마법을 가진 보컬 인챈트리스 | E: 15-30%, S: 30-45%, M: 40-60% |

## 기여

새로운 생물을 도감에 추가하려면:

1. 생물에 적합한 카테고리를 식별하십시오.
2. 해당 카테고리에 대한 관련 템플릿을 사용하십시오.
3. 기존 원소 구성 원칙과의 일관성을 유지하십시오.
4. 가능한 경우 문화적, 역사적 및 생태적 맥락을 포함하십시오.

---

> *“우리 세계의 생물을 이해하는 것은 세상을 이해하는 것입니다. 왜냐하면 그들은 세상의 다양한 에너지의 살아있는 구현이기 때문입니다.”* — 대현자 리리아 쏜하트


---
_Note: This content was automatically translated by Google Gemini. Please refer to the original English version for accuracy._