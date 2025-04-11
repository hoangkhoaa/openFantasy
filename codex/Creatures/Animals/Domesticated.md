# Welcome to the OpenFantasy system!

This is a basic introduction to how OpenFantasy is structured.

## Core Concepts

OpenFantasy is built around a few core concepts:

*   **Races**: Each character belongs to a race, which grants them certain benefits and limitations. For example, Elves (Elfen) are naturally good at magic, but weak in physical combat.
*   **Classes**: A character's class determines their role in the game. Warriors (Krieger) are good at fighting, Mages (Magier) are good at magic, and Thieves (Diebe) are good at sneaking around.
*   **Skills**: Skills are abilities that characters can use to perform actions. These can be combat skills, magic skills, or social skills.
*   **Stats**: Stats are numerical representations of a character's abilities. Strength (Stärke) determines how much damage they can do in combat, Intelligence (Intelligenz) determines how well they can cast spells, and so on.

## Character Creation

To create a character, you need to choose a race, a class, and then allocate points to your stats. You can also choose some skills.

Here's a simple example:

| Race (Rasse)   | Class (Klasse) | Strength (Stärke) | Intelligence (Intelligenz) | Skills (Fertigkeiten)     |
| -------------- | ------------- | ---------------- | ---------------------- | ------------------------- |
| Human (Mensch) | Warrior (Krieger)  | 15               | 8                     | Sword Fighting (Schwertkampf) |
| Elf (Elfe)     | Mage (Magier)     | 8                | 15                    | Fireball (Feuerball)      |

## Game Mechanics

The game is turn-based. Each turn, each character can perform one action. Actions can be attacking, casting a spell, using a skill, or moving.

### Combat

Combat is resolved by comparing the attacker's Strength (Stärke) to the defender's Defense (Verteidigung). If the attacker's Strength (Stärke) is higher, the attack hits. The amount of damage done is determined by the attacker's weapon and Strength (Stärke).

### Magic

Magic is resolved by comparing the caster's Intelligence (Intelligenz) to the target's Magic Resistance (Magieresistenz). If the caster's Intelligence (Intelligenz) is higher, the spell succeeds. The effect of the spell depends on the spell itself.

## Example Code (Python)

Here's a simple example of how OpenFantasy might represent a character in Python:

```python
class Character:
    def __init__(self, name, race, class_type, strength, intelligence):
        self.name = name
        self.race = race
        self.class_type = class_type
        self.strength = strength
        self.intelligence = intelligence

    def attack(self, target):
        damage = self.strength
        target.health -= damage
        print(f"{self.name} attacks {target.name} for {damage} damage!")

# Example usage
hero = Character("Aragorn", "Human", "Warrior", 15, 8)
monster = Character("Orc", "Orc", "Warrior", 12, 6)

hero.attack(monster)
```

This is just a very basic example. OpenFantasy can be much more complex.


---
_Note: This content was automatically translated by Google Gemini. Please refer to the original English version for accuracy._