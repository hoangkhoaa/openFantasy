# Welcome to the OpenFantasy system!

This document provides an overview of the OpenFantasy system and how to get started.

## What is OpenFantasy?

OpenFantasy is a free and open-source system for creating and playing tabletop role-playing games. It is designed to be modular and extensible, allowing users to customize the system to fit their specific needs. OpenFantasy is built with flexibility in mind, and can be used for a wide variety of genres and settings.

## Key Features

*   **Open Source:** OpenFantasy is licensed under the MIT License, meaning it is free to use, modify, and distribute.
*   **Modular Design:** The system is built around modules, which can be enabled or disabled to customize the game.
*   **Extensible:** Users can create their own modules to add new features, rules, and content to the system.
*   **Cross-Platform:** OpenFantasy is written in Python and can be run on any platform that supports Python.
*   **Data-Driven:** The system uses JSON files to store data, making it easy to modify and extend the system.

## Getting Started

To get started with OpenFantasy, you will need to install Python. You can download Python from the official Python website: [https://www.python.org/downloads/](https://www.python.org/downloads/)

Once you have Python installed, you can clone the OpenFantasy repository from GitHub:

```bash
git clone https://github.com/your-username/OpenFantasy.git
```

Next, navigate to the OpenFantasy directory and install the required dependencies:

```bash
cd OpenFantasy
pip install -r requirements.txt
```

Finally, you can run the OpenFantasy server:

```bash
python server.py
```

This will start the OpenFantasy server on port 5000. You can then access the OpenFantasy web interface by opening your web browser and navigating to `http://localhost:5000`.

## Core Concepts

### Entities

Entities are the fundamental building blocks of the OpenFantasy system. Everything in the game world is an entity, including characters, items, locations, and events. Each entity has a set of properties that define its attributes and behavior.

### Components

Components are reusable pieces of data that can be attached to entities. Components define the specific attributes of an entity, such as its health, strength, or name.

### Systems

Systems are modules of code that operate on entities. Systems define the logic of the game, such as how characters move, how combat works, or how items are used.

## Example: Creating a Character

To create a character in OpenFantasy, you will need to create an entity and attach the appropriate components to it. For example, you might create a character entity with the following components:

*   `NameComponent`: Stores the character's name.
*   `HealthComponent`: Stores the character's health.
*   `StrengthComponent`: Stores the character's strength.

You can then use systems to modify these components, such as a `CombatSystem` that reduces the character's health when they are attacked.

## Contributing

OpenFantasy is an open-source project, and contributions are welcome. If you would like to contribute to OpenFantasy, please fork the repository on GitHub and submit a pull request.


---
_Note: This content was automatically translated by Google Gemini. Please refer to the original English version for accuracy._