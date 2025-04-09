# OpenFantasy Character Classes

> *"Every soul finds its own melody in the symphony of power."*

## Overview

Welcome to the OpenFantasy Character Classes documentation. This repository contains comprehensive information about the various paths of power and specialization available to characters in the OpenFantasy world.

## Quick Navigation

- [Class Fundamentals](#class-fundamentals)
- [Primary Classes](#primary-classes)
- [Character Progression](#character-progression)
- [Multiclassing](#multiclassing)
- [Species Affinities](#species-affinities)
- [Documentation Structure](#documentation-structure)

## Class Fundamentals

Classes in OpenFantasy represent specialized paths that harness and develop a character's innate abilities:

| Concept | Description |
|---------|-------------|
| **Class Structure** | The organization of abilities and specializations |
| **Elemental Composition** | The balance of Exanthis, Soul, and Mana Capacity |
| **Subclasses** | Specialized branches of each core class |
| **Class Progression** | The development path for class abilities |
| **Equipment** | Tools and items that enhance class capabilities |

## Primary Classes

OpenFantasy features ten primary classes, each with their own specializations:

| Class | Core Focus | Primary Attribute | Class Directory |
|-------|------------|-------------------|----------------|
| **Warrior** | Physical combat | Exanthis | [Warrior/](Warrior/) |
| **Mage** | Arcane spellcasting | Mana Capacity | [Mage/](Mage/) |
| **Rogue** | Stealth and precision | Soul | [Rogue/](Rogue/) |
| **Cleric** | Divine magic | Soul/Mana | [Cleric/](Cleric/) |
| **Ranger** | Wilderness and tracking | Exanthis/Soul | [Ranger/](Ranger/) |
| **Artificer** | Magical creation | Mana Capacity | [Artificer/](Artificer/) |
| **Bard** | Performance magic | Soul/Mana | [Bard/](Bard/) |
| **Druid** | Nature magic | Soul/Mana | [Druid/](Druid/) |
| **Monk** | Internal energy | Exanthis/Soul | [Monk/](Monk/) |
| **Warlock** | Pact magic | Soul/Mana | [Warlock/](Warlock/) |

→ See the [Classes overview](Classes.md) for detailed information about each class.

## Character Progression

Character advancement follows a tiered progression system:

### Level Tiers

| Tier | Levels | Description |
|------|--------|-------------|
| **Novice** | 1-5 | Learning fundamentals of the class |
| **Adept** | 6-10 | Mastering basics and developing specialization |
| **Expert** | 11-15 | Honing abilities to a high degree |
| **Master** | 16-20 | Achieving mastery of chosen path |
| **Legendary** | 21+ | Transcending normal limitations |

## Multiclassing

Characters may pursue multiple class paths simultaneously, creating unique combinations of abilities. This versatility comes at the cost of specialized mastery in any single discipline.

### Common Multiclass Combinations

| Combination | Synergy |
|-------------|---------|
| Warrior/Mage | Physical combat enhanced with magical abilities |
| Cleric/Warrior | Divine magic with martial prowess |
| Rogue/Ranger | Stealth combined with wilderness expertise |
| Bard/Warlock | Performance magic enhanced with pact abilities |
| Druid/Monk | Nature magic combined with physical discipline |

## Species Affinities

Different species have natural affinities for certain classes based on their elemental composition:

| Species | Natural Class Affinities |
|---------|--------------------------|
| **Humans** | Balanced affinity for all classes |
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

## Elemental Composition

Each class features a characteristic elemental composition that shapes their abilities:

| Class | Exanthis | Soul | Mana Capacity | Primary Magical Affinity |
|-------|----------|------|---------------|--------------------------|
| **Warrior** | 50-70% | 20-35% | 10-20% | Terramana (Stability), Base Mana (Force) |
| **Mage** | 10-25% | 15-35% | 50-70% | Varies by specialization |
| **Rogue** | 30-45% | 40-60% | 10-25% | Umbramana (Concealment), Aeromana (Mobility) |
| **Cleric** | 20-35% | 30-50% | 25-45% | Luxmana (Light), Vitamana (Healing) |
| **Ranger** | 35-55% | 30-45% | 15-30% | Vitamana (Nature), Aeromana (Movement) |
| **Artificer** | 25-40% | 20-35% | 35-55% | Crystallmana (Structure), Terramana (Solidity) |
| **Bard** | 15-30% | 35-55% | 25-45% | Fulgumana (Sound), Aeromana (Communication) |
| **Druid** | 20-35% | 30-45% | 30-50% | Vitamana (Growth), Terramana (Earth) |
| **Monk** | 40-55% | 30-50% | 10-25% | Base Mana (Internal Energy), Aeromana (Movement) |
| **Warlock** | 15-30% | 25-40% | 40-60% | Aetheramana (Void), Varies by pact |

This elemental balance directly influences a class's natural affinity for certain specialized forms of magic and their overall magical capabilities:

- **Specialization Efficiency**: Classes with higher Mana Capacity typically achieve better elemental specialization rates
- **Mana Purification**: The ratio of Soul to Mana Capacity affects a class's ability to purify Wild Mana into Base Mana
- **Magical Stamina**: Higher Exanthis provides better physical endurance but typically reduces magical efficiency
- **Hybrid Potential**: Classes with more balanced compositions often excel at combining different elemental types

## Documentation Structure

The Classes directory is organized as follows:

```
codex/Classes/
├── README.md                # This overview document
├── Classes.md               # Main classes document with detailed descriptions
├── template_README.md       # Template for creating class directory README files
├── Warrior/                 # Example class directory
│   ├── README.md            # Class-specific overview
│   ├── Warrior.md           # Detailed class information
│   ├── Guardian.md          # Subclass documentation
│   ├── Berserker.md         # Subclass documentation
│   └── ...                  # Other subclass documents
└── ...                      # Other class directories
```

### Using the Template

To create a new class README, copy the [template_README.md](template_README.md) file and replace the placeholder values with class-specific information:

1. Replace `[CLASS_NAME]` with the name of the class
2. Fill in composition ranges and descriptions
3. List subclasses with their focus areas and specialties
4. Document core abilities, equipment, and species affinities
5. Describe class strengths and challenges

---

> **Repository Structure**: This documentation uses Markdown formatting optimized for viewing on Git platforms. 