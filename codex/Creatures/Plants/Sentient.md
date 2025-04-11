## OpenFantasy Item Creation Guide

This guide will walk you through the process of creating items in OpenFantasy. Items are fundamental to gameplay, and can range from simple swords to powerful artifacts.

### Item Structure

An item in OpenFantasy is defined by a JSON file with the following structure:

```json
{
  "id": "unique_item_id",
  "name": "Sword of Power",
  "description": "A powerful sword imbued with ancient magic.",
  "type": "weapon",
  "subtype": "sword",
  "properties": {
    "attack": 15,
    "defense": 5,
    "magic": 10
  },
  "rarity": "rare",
  "value": 500
}
```

*   `id`: A unique identifier for the item. This should be a string.
*   `name`: The name of the item.
*   `description`: A description of the item.
*   `type`: The general type of the item (e.g., "weapon", "armor", "potion").
*   `subtype`: A more specific subtype of the item (e.g., "sword", "helmet", "healing").
*   `properties`: A dictionary of properties that define the item's attributes.
*   `rarity`: The rarity of the item (e.g., "common", "uncommon", "rare", "epic", "legendary").
*   `value`: The monetary value of the item.

### Creating a New Item

1.  **Create a JSON file:** Create a new JSON file (e.g., `my_sword.json`) to define your item.
2.  **Define the item's properties:** Populate the JSON file with the item's properties, as described above.
3.  **Choose a unique ID:** Make sure the `id` is unique within your OpenFantasy game. A good practice is to use a prefix based on your name or project. For example, `myname_sword_of_awesome`.
4.  **Save the file:** Save the JSON file in the appropriate directory for your OpenFantasy game (typically a directory named "items").

### Example Item: Healing Potion

Here's an example of a `healing_potion.json` file:

```json
{
  "id": "default_healing_potion",
  "name": "Healing Potion",
  "description": "A potion that restores a small amount of health.",
  "type": "potion",
  "subtype": "healing",
  "properties": {
    "health_restore": 25
  },
  "rarity": "common",
  "value": 50
}
```

### Advanced Item Properties

You can add custom properties to your items to create unique effects. For example:

```json
{
  "id": "unique_fire_sword",
  "name": "Fire Sword",
  "description": "A sword that deals fire damage.",
  "type": "weapon",
  "subtype": "sword",
  "properties": {
    "attack": 10,
    "fire_damage": 5
  },
  "rarity": "uncommon",
  "value": 200
}
```

These custom properties can be used in OpenFantasy's game logic to create special effects when the item is used.

### Using Items in OpenFantasy

Once you have created your item, you can use it in your OpenFantasy game by referencing its `id` in your game scripts and configurations. Refer to the OpenFantasy documentation for details on how to integrate items into your game world.


---
_Note: This content was automatically translated by Google Gemini. Please refer to the original English version for accuracy._