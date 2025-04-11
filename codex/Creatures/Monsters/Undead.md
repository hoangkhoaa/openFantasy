¡Hola! Welcome to the world of OpenFantasy! This document will guide you through the basics of creating your own OpenFantasy module.

## What is OpenFantasy?

OpenFantasy is a free and open-source fantasy role-playing game engine. It allows you to create your own worlds, rules, and adventures. Think of it as a toolkit for building your own custom RPG (juego de rol).

## Getting Started

To start creating your own OpenFantasy module, you'll need the following:

*   A text editor (un editor de texto)
*   A basic understanding of YAML (una comprensión básica de YAML)
*   The OpenFantasy engine (el motor OpenFantasy)

You can download the OpenFantasy engine from [here](https://www.example.com).

## Creating Your First Module

Let's create a simple module that defines a new race, the Elfkin.

1.  Create a new file named `elfkin.yaml`. (Crea un nuevo archivo llamado `elfkin.yaml`.)

2.  Add the following content to the file:

```yaml
name: Elfkin (Duendecitos)
description: A race of small, nimble humanoids with pointy ears. (Una raza de humanoides pequeños y ágiles con orejas puntiagudas.)
attributes:
  strength: -1 (fuerza: -1)
  dexterity: 2 (destreza: 2)
  constitution: 0 (constitución: 0)
  intelligence: 1 (inteligencia: 1)
  wisdom: 0 (sabiduría: 0)
  charisma: 1 (carisma: 1)
```

3.  Save the file. (Guarda el archivo.)

## Loading Your Module

To load your module into OpenFantasy, you'll need to place the `elfkin.yaml` file in the modules directory. (Para cargar tu módulo en OpenFantasy, necesitarás colocar el archivo `elfkin.yaml` en el directorio de módulos.) The location of this directory depends on your OpenFantasy installation. (La ubicación de este directorio depende de tu instalación de OpenFantasy.) Consult the OpenFantasy documentation for more details. (Consulta la documentación de OpenFantasy para obtener más detalles.)

## Example Table

This table shows the base stats for different Races.

| Race (Raza) | Strength (Fuerza) | Dexterity (Destreza) | Constitution (Constitución) | Intelligence (Inteligencia) | Wisdom (Sabiduría) | Charisma (Carisma) |
|---|---|---|---|---|---|---|
| Humans (Humanos) | 0 | 0 | 0 | 0 | 0 | 0 |
| Elves (Elfos) | -1 | 2 | -1 | 1 | 0 | 1 |
| Dwarves (Enanos) | 2 | -1 | 2 | 0 | 1 | -1 |
| Gnomes (Gnomos) | -2 | 1 | 0 | 2 | 1 | 0 |
| Orcs (Orcos) | 3 | 0 | 2 | -2 | -1 | -2 |

## Next Steps

This is just a simple example. (Esto es solo un ejemplo simple.) You can extend your modules with more complex rules, items, monsters, and adventures. (Puedes extender tus módulos con reglas, objetos, monstruos y aventuras más complejas.) Refer to the OpenFantasy documentation for more information. (Consulta la documentación de OpenFantasy para obtener más información.)

Happy modding! (¡Feliz modding!)


---
_Note: This content was automatically translated by Google Gemini. Please refer to the original English version for accuracy._