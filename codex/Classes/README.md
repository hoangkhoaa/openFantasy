# OpenFantasy 캐릭터 클래스

> *"모든 영혼은 힘의 교향곡에서 자신만의 멜로디를 찾습니다."*

## 개요

OpenFantasy 캐릭터 클래스 문서에 오신 것을 환영합니다. 이 저장소는 OpenFantasy 세계에서 캐릭터가 사용할 수 있는 다양한 힘과 전문화의 길에 대한 포괄적인 정보를 담고 있습니다.

## 빠른 탐색

- [클래스 기본 사항](#클래스-기본-사항)
- [기본 클래스](#기본-클래스)
- [캐릭터 성장](#캐릭터-성장)
- [멀티클래싱](#멀티클래싱)
- [종족 친화도](#종족-친화도)
- [문서 구조](#문서-구조)

## 클래스 기본 사항

OpenFantasy의 클래스는 캐릭터의 타고난 능력을 활용하고 개발하는 특화된 경로를 나타냅니다.

| 개념 | 설명 |
|---------|-------------|
| **클래스 구조** | 능력 및 전문화의 구성 |
| **원소 구성** | Exanthis, Soul 및 Mana Capacity의 균형 |
| **서브클래스** | 각 핵심 클래스의 전문화된 분기 |
| **클래스 성장** | 클래스 능력의 개발 경로 |
| **장비** | 클래스 능력을 향상시키는 도구 및 아이템 |

## 기본 클래스

OpenFantasy는 각각 고유한 전문 분야를 가진 10개의 기본 클래스를 제공합니다.

| 클래스 | 핵심 집중 | 주요 속성 | 클래스 디렉토리 |
|-------|------------|-------------------|----------------|
| **Warrior** | 물리 전투 | Exanthis | [Warrior/](Warrior/) |
| **Mage** | 신비로운 주문 시전 | Mana Capacity | [Mage/](Mage/) |
| **Rogue** | 은신 및 정밀성 | Soul | [Rogue/](Rogue/) |
| **Cleric** | 신성 마법 | Soul/Mana | [Cleric/](Cleric/) |
| **Ranger** | 황무지 및 추적 | Exanthis/Soul | [Ranger/](Ranger/) |
| **Artificer** | 마법 창조 | Mana Capacity | [Artificer/](Artificer/) |
| **Bard** | 공연 마법 | Soul/Mana | [Bard/](Bard/) |
| **Druid** | 자연 마법 | Soul/Mana | [Druid/](Druid/) |
| **Monk** | 내부 에너지 | Exanthis/Soul | [Monk/](Monk/) |
| **Warlock** | 계약 마법 | Soul/Mana | [Warlock/](Warlock/) |

→ 각 클래스에 대한 자세한 내용은 [클래스 개요](Classes.md)를 참조하십시오.

## 캐릭터 성장

캐릭터 발전은 계층화된 성장 시스템을 따릅니다.

### 레벨 계층

| 계층 | 레벨 | 설명 |
|------|--------|-------------|
| **Novice** | 1-5 | 클래스의 기본 사항 학습 |
| **Adept** | 6-10 | 기본 사항 숙달 및 전문화 개발 |
| **Expert** | 11-15 | 능력을 높은 수준으로 연마 |
| **Master** | 16-20 | 선택한 경로의 숙달 달성 |
| **Legendary** | 21+ | 정상적인 한계 초월 |

## 멀티클래싱

캐릭터는 여러 클래스 경로를 동시에 추구하여 능력의 고유한 조합을 만들 수 있습니다. 이러한 다재다능함은 단일 분야의 전문적인 숙달을 희생하는 대신 얻을 수 있습니다.

### 일반적인 멀티클래스 조합

| 조합 | 시너지 |
|-------------|---------|
| Warrior/Mage | 마법 능력으로 강화된 물리 전투 |
| Cleric/Warrior | 무술 기량과 신성 마법 |
| Rogue/Ranger | 황무지 전문 지식과 결합된 은신 |
| Bard/Warlock | 계약 능력으로 강화된 공연 마법 |
| Druid/Monk | 물리적 단련과 결합된 자연 마법 |

## 종족 친화도

다른 종족은 원소 구성에 따라 특정 클래스에 대한 자연적인 친화력을 가지고 있습니다.

| 종족 | 자연 클래스 친화도 |
|---------|--------------------------|
| **Humans** | 모든 클래스에 대한 균형 잡힌 친화도 |
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

## 원소 구성

각 클래스는 능력의 형태를 결정하는 특징적인 원소 구성을 특징으로 합니다.

| 클래스 | Exanthis | Soul | Mana Capacity | 주요 마법 친화도 |
|-------|----------|------|---------------|--------------------------|
| **Warrior** | 50-70% | 20-35% | 10-20% | Terramana (안정성), Base Mana (힘) |
| **Mage** | 10-25% | 15-35% | 50-70% | 전문 분야에 따라 다름 |
| **Rogue** | 30-45% | 40-60% | 10-25% | Umbramana (은폐), Aeromana (기동성) |
| **Cleric** | 20-35% | 30-50% | 25-45% | Luxmana (빛), Vitamana (치유) |
| **Ranger** | 35-55% | 30-45% | 15-30% | Vitamana (자연), Aeromana (움직임) |
| **Artificer** | 25-40% | 20-35% | 35-55% | Crystallmana (구조), Terramana (견고성) |
| **Bard** | 15-30% | 35-55% | 25-45% | Fulgumana (소리), Aeromana (커뮤니케이션) |
| **Druid** | 20-35% | 30-45% | 30-50% | Vitamana (성장), Terramana (땅) |
| **Monk** | 40-55% | 30-50% | 10-25% | Base Mana (내부 에너지), Aeromana (움직임) |
| **Warlock** | 15-30% | 25-40% | 40-60% | Aetheramana (공허), 계약에 따라 다름 |

이러한 원소 균형은 특정 전문 마법 형태 및 전반적인 마법 능력에 대한 클래스의 자연적인 친화도에 직접적인 영향을 미칩니다.

- **전문화 효율성**: Mana Capacity가 높은 클래스는 일반적으로 더 나은 원소 전문화 비율을 달성합니다.
- **Mana 정화**: Soul과 Mana Capacity의 비율은 클래스가 Wild Mana를 Base Mana로 정화하는 능력에 영향을 미칩니다.
- **마법 스태미나**: Exanthis가 높을수록 더 나은 물리적 지구력을 제공하지만 일반적으로 마법 효율성이 떨어집니다.
- **하이브리드 잠재력**: 더 균형 잡힌 구성을 가진 클래스는 종종 다양한 원소 유형을 결합하는 데 탁월합니다.

## 문서 구조

Classes 디렉토리는 다음과 같이 구성됩니다.

```
codex/Classes/
├── README.md                # 이 개요 문서
├── Classes.md               # 자세한 설명이 포함된 주요 클래스 문서
├── template_README.md       # 클래스 디렉토리 README 파일 생성 템플릿
├── Warrior/                 # 예제 클래스 디렉토리
│   ├── README.md            # 클래스별 개요
│   ├── Warrior.md           # 자세한 클래스 정보
│   ├── Guardian.md          # 서브클래스 문서
│   ├── Berserker.md         # 서브클래스 문서
│   └── ...                  # 기타 서브클래스 문서
└── ...                      # 기타 클래스 디렉토리
```

### 템플릿 사용

새로운 클래스 README를 생성하려면 [template_README.md](template_README.md) 파일을 복사하고 자리 표시자 값을 클래스별 정보로 바꿉니다.

1. `[CLASS_NAME]`을 클래스 이름으로 바꿉니다.
2. 구성 범위 및 설명을 채웁니다.
3. 집중 영역 및 전문 분야와 함께 서브클래스를 나열합니다.
4. 핵심 능력, 장비 및 종족 친화도를 문서화합니다.
5. 클래스의 강점과 과제를 설명합니다.

---

> **저장소 구조**: 이 문서는 Git 플랫폼에서 보기에 최적화된 Markdown 형식을 사용합니다.


---
_Note: This content was automatically translated by Google Gemini. Please refer to the original English version for accuracy._