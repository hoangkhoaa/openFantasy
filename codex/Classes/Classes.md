# OpenFantasy 캐릭터 클래스

> *"OpenFantasy 세계에서 클래스는 개인이 추구할 수 있는 다양한 힘과 전문화의 길을 나타냅니다."*

## 빠른 참조

- [클래스 구조](#클래스-구조)
- [주요 클래스](#주요-클래스)
- [클래스 진행](#클래스-진행)
- [멀티클래싱](#멀티클래싱)
- [클래스-종족 상호작용](#클래스-종족-상호작용)

## 개요

OpenFantasy의 각 클래스는 [**Exanthis**](/codex/Basic/Exanthis.md), [**Souls**](/codex/Basic/Soul.md), 그리고 **마나 용량**의 독특한 조화를 나타내며, 세상에서 자신의 역할을 정의하는 능력의 교향곡을 만듭니다.

## 클래스 구조

클래스는 주요 범주로 구성되며, 각 범주에는 핵심 클래스에서 분기되는 수많은 서브클래스 또는 경력 경로가 있습니다. 이러한 서브클래스는 클래스의 기본 능력의 특수화된 적용을 나타냅니다. 마치 음악적 주제의 변주와 같습니다.

## 주요 클래스

### [**전사**](/codex/Classes/Warrior/Warrior.md)

| 측면 | 세부 정보 |
|--------|---------|
| **집중** | 물리적 전투 및 무술 기량 |
| **주요 원소** | [**Exanthis**](/codex/Basic/Exanthis.md) |
| **비유** | 전투의 리듬을 주도하는 강력한 드럼 |

**서브클래스:**
- [**수호자**](/codex/Classes/Warrior/Guardian.md) - 다른 사람을 보호하는 데 뛰어난 방어 전문가
- [**광전사**](/codex/Classes/Warrior/Berserker.md) - 전투에 광분 상태로 들어가는 공격 전문가
- [**결투가**](/codex/Classes/Warrior/Duelist.md) - 일대일 전투에 뛰어난 정밀 전투가
- [**지휘관**](/codex/Classes/Warrior/Commander.md) - 그룹 노력을 조정하는 전술 지도자
- [**무기 달인**](/codex/Classes/Warrior/Weaponmaster.md) - 다양한 무기 및 전투 스타일의 달인

### [**마법사**](/codex/Classes/Mage/Mage.md)

| 측면 | 세부 정보 |
|--------|---------|
| **집중** | 마법 능력 및 주문 시전 |
| **주요 원소** | **마나 용량** |
| **비유** | 원소를 조율하는 지휘자 |

**서브클래스:**
- [**정령술사**](/codex/Classes/Mage/Elementalist.md) - 정령 마법 (불, 물, 흙, 공기)의 달인
- [**강령술사**](/codex/Classes/Mage/Necromancer.md) - 죽음과 영혼 마법 시전자
- [**환술사**](/codex/Classes/Mage/Illusionist.md) - 기만적인 마법 효과 창조자
- [**점술가**](/codex/Classes/Mage/Diviner.md) - 마법 수단을 통해 지식을 추구하는 자
- [**흑마법사**](/codex/Classes/Mage/Warlock.md) - 힘을 위해 다른 세계의 존재와 거래하는 자

### [**도적**](/codex/Classes/Rogue/Rogue.md)

| 측면 | 세부 정보 |
|--------|---------|
| **집중** | 은신, 정확성, 그리고 교활함 |
| **주요 원소** | [**Soul**](/codex/Basic/Soul.md) |
| **비유** | 보이지 않게 움직이는 미묘한 플루트 |

**서브클래스:**
- [**암살자**](/codex/Classes/Rogue/Assassin.md) - 탐지 없이 대상을 제거하는 조용한 살인자
- [**정찰병**](/codex/Classes/Rogue/Scout.md) - 정보 수집에 뛰어난 탐험가
- [**사기꾼**](/codex/Classes/Rogue/Trickster.md) - 오도와 환상을 사용하는 기만자
- [**그림자 칼날**](/codex/Classes/Rogue/Shadowblade.md) - 전투와 은신을 혼합하는 은밀한 전투가
- [**스파이**](/codex/Classes/Rogue/Spy.md) - 적의 진영 내에서 정보를 수집하는 침투가

### [**클레릭**](/codex/Classes/Cleric/Cleric.md)

| 측면 | 세부 정보 |
|--------|---------|
| **집중** | 신성 마법과 치유 |
| **주요 원소** | [**Soul**](/codex/Basic/Soul.md) 그리고 **마나 용량** |
| **비유** | 필멸자와 신성을 연결하는 합창단 |

**서브클래스:**
- [**치유사**](/codex/Classes/Cleric/Healer.md) - 회복 마법과 치유 전문가
- [**성기사**](/codex/Classes/Cleric/Paladin.md) - 신성 마법과 전투를 결합한 신성한 전사
- [**오라클**](/codex/Classes/Cleric/Oracle.md) - 신성한 비전과 예언의 수신자
- [**심문관**](/codex/Classes/Cleric/Inquisitor.md) - 이단과 초자연적 위협의 사냥꾼
- [**샤먼**](/codex/Classes/Cleric/Shaman.md) - 자연 영혼 및 조상과의 소통자

### [**레인저**](/codex/Classes/Ranger/Ranger.md)

| 측면 | 세부 정보 |
|--------|---------|
| **집중** | 야생 생존 및 전투 |
| **주요 원소** | [**Exanthis**](/codex/Basic/Exanthis.md) 그리고 [**Soul**](/codex/Basic/Soul.md) |
| **비유** | 숲의 소리를 반영하는 목관 악기 |

**서브클래스:**
- [**야수 조련사**](/codex/Classes/Ranger/Beastmaster.md) - 동물과 함께 싸우는 동반자
- [**사냥꾼**](/codex/Classes/Ranger/Hunter.md) - 대상을 찾고 제거하는 데 뛰어난 추적자
- [**수호자**](/codex/Classes/Ranger/Warden.md) - 자연 장소와 그 거주자 보호자
- [**정찰병**](/codex/Classes/Ranger/Scout.md) - 미지의 영역을 탐색하는 데 뛰어난 탐험가
- [**생존 전문가**](/codex/Classes/Ranger/Survivalist.md) - 야생 생존 및 자원 활용의 달인

### [**아티피서**](/codex/Classes/Artificer/Artificer.md)

| 측면 | 세부 정보 |
|--------|---------|
| **집중** | 마법 아이템 및 장치 제작 |
| **주요 원소** | **마나 용량** |
| **비유** | 힘의 악기를 만드는 장인 |

**서브클래스:**
- [**마법부여자**](/codex/Classes/Artificer/Enchanter.md) - 아이템에 대한 마법적 향상 창조자
- [**연금술사**](/codex/Classes/Artificer/Alchemist.md) - 포션 및 마법 물질 양조자
- [**엔지니어**](/codex/Classes/Artificer/Engineer.md) - 마법 부품이 있는 기계 장치 건설자
- [**룬 마스터**](/codex/Classes/Artificer/Runemaster.md) - 마법 상징 및 비문 제작자
- [**땜장이**](/codex/Classes/Artificer/Tinkerer.md) - 작은 마법 도구 및 장치 발명가

### [**바드**](/codex/Classes/Bard/Bard.md)

| 측면 | 세부 정보 |
|--------|---------|
| **집중** | 공연과 영감 |
| **주요 원소** | [**Soul**](/codex/Basic/Soul.md) 그리고 **마나 용량** |
| **비유** | 공연을 통해 마법을 엮는 음악가 |

**서브클래스:**
- [**웅변 대학**](/codex/Classes/Bard/Colleges/Eloquence.md) - 구두 설득과 완벽한 연설의 달인
- [**화려함 대학**](/codex/Classes/Bard/Colleges/Glamour.md) - 요정 마법을 사용하는 공연가
- [**지식 대학**](/codex/Classes/Bard/Colleges/Lore.md) - 지식과 비밀 수집가
- [**영혼 대학**](/codex/Classes/Bard/Colleges/Spirits.md) - 초자연적 존재를 사용하는 스토리텔러
- [**검 대학**](/codex/Classes/Bard/Colleges/Swords.md) - 전투와 공연을 결합한 검 무용가
- [**용기 대학**](/codex/Classes/Bard/Colleges/Valor.md) - 용기와 영웅심을 고취하는 전투 공연가
- [**속삭임 대학**](/codex/Classes/Bard/Colleges/Whispers.md) - 공포와 비밀 조작자
- [**창조 대학**](/codex/Classes/Bard/Colleges/Creation.md) - 공연을 통해 물리적 객체를 창조하는 예술가

### [**드루이드**](/codex/Classes/Druid/Druid.md)

| 측면 | 세부 정보 |
|--------|---------|
| **집중** | 자연 마법과 변신 |
| **주요 원소** | [**Soul**](/codex/Basic/Soul.md) 그리고 **마나 용량** |
| **비유** | 주변 환경에 적응하는 카멜레온 |

**서브클래스:**
- [**땅의 서클**](/codex/Classes/Druid/Land.md) - 자연 영역의 수호자
- [**달의 서클**](/codex/Classes/Druid/Moon.md) - 야생 변신의 달인
- [**꿈의 서클**](/codex/Classes/Druid/Dreams.md) - 자연의 요정 영역 연결자
- [**양치기의 서클**](/codex/Classes/Druid/Shepherd.md) - 동물 보호자 및 자연 영혼 소환자
- [**포자의 서클**](/codex/Classes/Druid/Spores.md) - 삶과 죽음의 순환 제어자

### [**몽크**](/codex/Classes/Monk/Monk.md)

| 측면 | 세부 정보 |
|--------|---------|
| **집중** | 내면의 힘과 규율 |
| **주요 원소** | [**Exanthis**](/codex/Basic/Exanthis.md) 그리고 [**Soul**](/codex/Basic/Soul.md) |
| **비유** | 에너지 흐름을 마스터한 무술가 |

**서브클래스:**
- [**개방된 손의 길**](/codex/Classes/Monk/OpenHand.md) - 맨손 전투 기술의 달인
- [**그림자의 길**](/codex/Classes/Monk/Shadow.md) - 어둠을 조작하는 은밀한 전사
- [**네 원소의 길**](/codex/Classes/Monk/FourElements.md) - 원소 에너지 제어자
- [**켄세이의 길**](/codex/Classes/Monk/Kensei.md) - 자신의 정신을 무기로 확장하는 무기 달인
- [**평온의 길**](/codex/Classes/Monk/Tranquility.md) - 치유하고 보호하는 평화로운 중재자

### [**워락**](/codex/Classes/Warlock/Warlock.md)

| 측면 | 세부 정보 |
|--------|---------|
| **집중** | 초자연적 존재와의 계약 |
| **주요 원소** | [**Soul**](/codex/Basic/Soul.md) 그리고 **마나 용량** |
| **비유** | 재능을 위해 영혼을 팔아넘긴 음악가 |

**서브클래스:**
- [**악마**](/codex/Classes/Warlock/Fiend.md) - 악마적인 존재와의 계약
- [**아치페이**](/codex/Classes/Warlock/Archfey.md) - 강력한 요정 생물과의 계약
- [**위대한 고대 존재**](/codex/Classes/Warlock/GreatOldOne.md) - 고대의 우주적 존재와의 계약
- [**천상계**](/codex/Classes/Warlock/Celestial.md) - 신성한 존재와의 계약
- [**헥스블레이드**](/codex/Classes/Warlock/Hexblade.md) - 지각이 있는 무기 또는 그림자 존재와의 계약

## 클래스 진행

OpenFantasy의 클래스는 개인이 시간이 지남에 따라 능력을 개발할 수 있게 해주는 진행 시스템을 따릅니다. 이 진행은 레벨로 표시되며, 각 레벨은 점점 더 복잡한 곡을 배우는 음악가와 같이 새로운 능력과 힘에 대한 접근 권한을 부여합니다.

### 레벨 티어

| 티어 | 레벨 | 설명 |
|------|--------|-------------|
| **초심자** | 1-5 | 기본을 배우는 초보자 |
| **능숙자** | 6-10 | 기본을 마스터하고 전문화를 개발하는 자 |
| **전문가** | 11-15 | 고도로 숙련된 능력을 가진 전문가 |
| **달인** | 16-20 | 진정한 숙달을 이룬 자 |
| **전설적** | 21+ | 일반적인 한계를 초월하는 개인 |

## 멀티클래싱

어떤 개인은 여러 클래스를 추구하여 다양한 경로의 능력을 결합하여 독특한 조합을 만듭니다. 멀티클래싱이라고 알려진 이 관행은 더 큰 다양성을 허용하지만, 여러 악기를 연주하지만 단일 악기를 마스터하지 못할 수 있는 음악가와 같이 단일 클래스의 전문화 깊이를 제한할 수 있습니다.

## 클래스-종족 상호작용

다른 종족은 원소 구성에 따라 특정 클래스에 대한 자연스러운 친화력을 가집니다:

| 종족 | 자연스러운 클래스 친화력 |
|---------|--------------------------|
| **인간** | 모든 클래스에 대한 균형 잡힌 친화력 |
| **엘프** | 마법사, 레인저, 바드 클래스에 대한 강한 친화력 |
| **다크 엘프** | 마법사, 도적, 워락 클래스에 대한 강한 친화력 |
| **드워프** | 전사, 아티피서, 클레릭 클래스에 대한 강한 친화력 |
| **비스트포크** | 레인저, 드루이드, 전사 클래스에 대한 강한 친화력 |
| **드래곤킨** | 전사, 마법사, 워락 클래스에 대한 강한 친화력 |
| **페이** | 바드, 드루이드, 마법사 클래스에 대한 강한 친화력 |
| **골렘** | 아티피서 및 전사 클래스에 대한 강한 친화력 |
| **세이렌** | 바드 및 마법사 클래스에 대한 강한 친화력 |
| **섀도우포크** | 도적, 워락, 마법사 클래스에 대한 강한 친화력 |
| **자이언트** | 전사 및 드루이드 클래스에 대한 강한 친화력 |

---

> 클래스의 본질을 이해하면 마치 웅장한 존재의 교향곡을 이루는 다양한 멜로디를 듣는 것처럼 **OpenFantasy** 세계에서 힘의 다양한 경로에 대한 통찰력을 얻을 수 있습니다.


---
_Note: This content was automatically translated by Google Gemini. Please refer to the original English version for accuracy._