# OpenFantasy 월드 코덱스

> *"마법과 경이로 가득한 세계가 기다리고 있습니다. 모든 영혼이 웅장한 존재의 교향곡에 기여합니다."*

## 개요

OpenFantasy 월드 코덱스에 오신 것을 환영합니다. OpenFantasy 세계에 대한 포괄적인 지식 저장소입니다. 이 코덱은 세계의 기본 원리, 주민, 마법 시스템, 위치, 아이템 등에 대한 자세한 정보를 담고 있습니다.

## 빠른 탐색

- [세계 기본 요소](#world-fundamentals)
- [생물 및 종족](#creatures-and-species)
- [마법 시스템](#magic-system)
- [캐릭터 클래스](#character-classes)
- [세계 지리](#world-geography)
- [아이템 및 유물](#items-and-artifacts)
- [저장소 구조](#repository-structure)

## 세계 기본 요소

OpenFantasy는 세계 작동 방식을 규정하는 핵심 원칙을 기반으로 구축되었습니다.

| 디렉토리 | 내용 | 설명 |
|---|---|---|
| [Basic/](Basic/) | 기본 개념 | OpenFantasy의 현실을 구성하는 기본 요소 |

주요 개념은 다음과 같습니다.

- **Exanthis**: 구조와 형태를 제공하는 물리적 기반
- **Soul**: 의지와 정체성을 제공하는 의식의 불꽃
- **Mana**: 모든 것을 통해 흐르는 마법 에너지
- **Elemental Balance**: 기본 힘 사이의 상호 작용

## 생물 및 종족

세계에는 고유한 특징을 가진 다양한 종족이 살고 있습니다.

| 디렉토리 | 내용 | 설명 |
|---|---|---|
| [Creatures/](Creatures/) | 종족 문서 | 세계에 서식하는 다양한 존재에 대한 정보 |

주요 종족 범주는 다음과 같습니다.

- **Primary Species**: 인간, 엘프, 드워프, 비스트포크 등
- **Magical Species**: 페이, 골렘, 사이렌, 섀도우포크 등
- **Other Notable Species**: 다크 엘프, 켄타우로스, 노움, 머포크 등

→ 자세한 내용은 [Creatures README](Creatures/README.md)를 참조하십시오.

## 마법 시스템

OpenFantasy의 마법은 체계적인 규칙과 원칙을 따릅니다.

| 디렉토리 | 내용 | 설명 |
|---|---|---|
| [Magics/](Magics/) | 마법 시스템, 주문 | 마법 에너지의 규칙과 발현 |

주요 마법 개념은 다음과 같습니다.

- **Elemental Magic**: 8가지 주요 원소 조작
- **Mana Purity**: 마법 에너지의 정제
- **Spell Structure**: 마법 효과를 형성하는 패턴
- **Enhancement Buffs**: 능력을 향상시키는 마법 효과

→ 자세한 내용은 [Magics README](Magics/README.md)를 참조하십시오.

## 캐릭터 클래스

OpenFantasy의 캐릭터는 전문화된 개발 경로를 따릅니다.

| 디렉토리 | 내용 | 설명 |
|---|---|---|
| [Classes/](Classes/) | 클래스 정보, 전문화 | 힘과 전문화의 다양한 경로 |

주요 클래스 범주는 다음과 같습니다.

- **Martial Classes**: 워리어, 몽크, 레인저
- **Magical Classes**: 메이지, 워록, 드루이드
- **Hybrid Classes**: 클레릭, 바드, 아티피서
- **Specialized Classes**: 로그 및 서브클래스

→ 자세한 내용은 [Classes README](Classes/README.md)를 참조하십시오.

## 세계 지리

OpenFantasy의 세계에는 다양한 지역과 위치가 있습니다.

| 디렉토리 | 내용 | 설명 |
|---|---|---|
| [World/](World/) | 위치, 지리, 역사 | 세계의 물리적 및 문화적 풍경 |

주요 지역은 다음과 같습니다.

- **Eastern Veldrassil**: 마법의 숲과 학술 중심지
- **Western Veldrassil**: 산맥과 광업 작업
- **Central Plains**: 농업 중심지와 주요 도시
- **Northern Reaches**: 얼어붙은 황무지와 고대 유적
- **Southern Isles**: 열대 군도와 해양 문화

## 아이템 및 유물

세계에는 수많은 힘과 중요성을 지닌 물건이 있습니다.

| 디렉토리 | 내용 | 설명 |
|---|---|---|
| [Items/](Items/) | 장비, 유물, 재료 | 힘과 유용성의 물건 |

아이템 범주는 다음과 같습니다.

- **Magical Equipment**: 마법 속성이 있는 무기, 방어구 및 액세서리
- **Alchemical Substances**: 포션, 엘릭서 및 마법 시약
- **Artifacts**: 중요한 힘을 가진 고대 물건
- **Everyday Items**: 문화적 의미가 있는 평범한 물건

## 저장소 구조

OpenFantasy 코덱은 일관된 구조로 구성되어 있습니다.

```
codex/
├── README.md                # 이 개요 문서
├── Basic/                   # 기본 개념
├── Creatures/               # 종족 문서
│   ├── README.md            # 생물 개요
│   ├── Creatures.md         # 일반 종족 정보
│   ├── Human.md             # 개별 종족 문서
│   └── ...                  # 기타 종족 문서
├── Magics/                  # 마법 시스템
│   ├── README.md            # 마법 개요
│   ├── Spells/              # 주문 문서
│   └── ...                  # 마법 시스템 문서
├── Classes/                 # 캐릭터 클래스
│   ├── README.md            # 클래스 개요
│   ├── Warrior/             # 클래스별 디렉토리
│   └── ...                  # 기타 클래스 디렉토리
├── World/                   # 지리 및 위치
│   ├── README.md            # 세계 개요
│   └── ...                  # 지역 및 위치 문서
└── Items/                   # 장비 및 유물
    ├── README.md            # 아이템 개요
    └── ...                  # 아이템 범주 문서
```

### 문서 표준

이 저장소의 모든 문서는 일관된 형식을 따릅니다.

- **README.md 파일**은 개요 및 탐색을 제공합니다.
- 문서 상단의 **Quick Reference 섹션**
- 비교 정보를 위한 **테이블**
- 문서 전반에 걸쳐 유사한 정보를 위한 **일관된 헤더**
- 관련 콘텐츠에 대한 **상호 참조**
- 더 나은 보기 환경을 위한 **Git에 최적화된 마크다운**

---

> **참고**: 이 코덱은 시간이 지남에 따라 확장되고 개선될 수 있는 살아있는 문서입니다. 모든 콘텐츠는 OpenFantasy 세계를 정의하는 음악적 은유를 따릅니다.


---
_Note: This content was automatically translated by Google Gemini. Please refer to the original English version for accuracy._