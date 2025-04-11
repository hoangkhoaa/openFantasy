## OpenFantasy Character Sheet Generator

This document describes the data format used by the OpenFantasy character sheet generator.

### Character Data

The character data is a JSON object with the following properties:

*   `name`: The character's name.
*   `race`: The character's race.
*   `class`: The character's class.
*   `level`: The character's level.
*   `attributes`: An object containing the character's attributes.
*   `skills`: An object containing the character's skills.
*   `inventory`: An array of items the character possesses.

Example:

```json
{
  "name": "Aella",
  "race": "Elf",
  "class": "Rogue",
  "level": 3,
  "attributes": {
    "strength": 10,
    "dexterity": 16,
    "constitution": 12,
    "intelligence": 14,
    "wisdom": 8,
    "charisma": 15
  },
  "skills": {
    "acrobatics": 6,
    "stealth": 8,
    "perception": 1,
    "persuasion": 2
  },
  "inventory": [
    "Shortsword",
    "Leather Armor",
    "Potion of Healing"
  ]
}
```

### Attributes

Attributes are key-value pairs where the key is the attribute name and the value is the attribute score. Common attributes include:

*   `strength`: Measures physical power.
*   `dexterity`: Measures agility and reflexes.
*   `constitution`: Measures health and stamina.
*   `intelligence`: Measures reasoning and memory.
*   `wisdom`: Measures perception and insight.
*   `charisma`: Measures force of personality.

### Skills

Skills are key-value pairs where the key is the skill name and the value is the skill bonus.

### Items

Items are simple strings representing the name of the item.

### Table Example

| Header 1 | Header 2 | Header 3 |
|---|---|---|
| Item A | Value 1 | Value 2 |
| Item B | Value 3 | Value 4 |

### Detailed Table Example

| Race (Chủng tộc) | Strength (Sức mạnh) | Dexterity (Sự khéo léo) | Constitution (Thể chất) | Intelligence (Trí thông minh) | Wisdom (Sự thông thái) | Charisma (Sức quyến rũ) |
|---|---|---|---|---|---|---|
| Humans (Con người) | +1 | +1 | +1 | +1 | +1 | +1 |
| Elves (Tiên tộc) | -1 | +2 | -1 | +2 | 0 | 0 |
| Dwarves (Người lùn) | +2 | -1 | +2 | 0 | -1 | 0 |

This is a simple overview. More details to follow.


---
_Note: This content was automatically translated by Google Gemini. Please refer to the original English version for accuracy._