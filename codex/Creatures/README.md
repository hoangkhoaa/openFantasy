# Códice de Criaturas de OpenFantasy

> *"El mundo canta con las voces de incontables seres, cada uno jugando su papel en la gran sinfonía de la existencia."*

## Resumen

Bienvenido a la documentación de Criaturas de OpenFantasy. Este repositorio contiene información exhaustiva sobre los diversos seres que habitan el mundo de OpenFantasy, incluyendo especies inteligentes, animales, monstruos, plantas y otras entidades.

## Estructura del Directorio

```
/Creatures
├── README.md                # Este documento de resumen
├── Creatures.md             # Principios básicos y composición elemental
├── template_species.md      # Plantilla para crear nuevas entradas de especies
├── /Sentient                # Especies inteligentes que forman civilizaciones
│   ├── README.md            # Resumen de las especies inteligentes
│   ├── Humans.md
│   ├── Elves.md
│   ├── DarkElves.md
│   ├── Dwarves.md
│   └── ...
├── /Magical                 # Seres principalmente mágicos o feéricos
│   ├── README.md            # Resumen de los seres mágicos
│   ├── Fae.md
│   ├── Golems.md
│   ├── Elementals.md
│   └── ...
├── /Animals                 # Fauna natural no inteligente
│   ├── README.md            # Resumen de los animales
│   ├── Domesticated.md
│   ├── Wild.md
│   ├── Aquatic.md
│   └── ...
├── /Monsters                # Criaturas peligrosas o antinaturales
│   ├── README.md            # Resumen de los monstruos
│   ├── Aberrations.md
│   ├── Undead.md
│   ├── Corrupted.md
│   └── ...
├── /Plants                  # Flora con propiedades únicas
│   ├── README.md            # Resumen de plantas mágicas y mundanas
│   ├── Magical.md
│   ├── Medicinal.md
│   ├── Poisonous.md
│   └── ...
└── /Hybrid                  # Seres de categorías cruzadas
    ├── README.md            # Resumen de las criaturas híbridas
    ├── Centaurs.md
    ├── Merfolk.md
    └── ...
```

## Navegación Rápida

- [Conceptos Básicos](#core-concepts)
- [Especies Inteligentes](#sentient-species)
- [Seres Mágicos](#magical-beings)
- [Animales](#animals)
- [Monstruos](#monsters)
- [Plantas](#plants)
- [Seres Híbridos](#hybrid-beings)

## Conceptos Básicos

Todas las criaturas en OpenFantasy están compuestas por tres elementos fundamentales que determinan su naturaleza y habilidades:

| (Componente) Component | (Función) Function | (Influencia) Influence |
|-----------|----------|-----------|
| **Exanthis** | (Fundamento físico) Physical foundation | (Fuerza, resistencia, durabilidad) Strength, endurance, durability |
| **Soul** | (Conciencia e identidad) Consciousness and identity | (Fuerza de voluntad, creatividad, percepción) Willpower, creativity, perception |
| **Mana Capacity** | (Potencial mágico) Magical potential | (Capacidad de hechizos, resistencia mágica, purificación de maná) Spell capability, magical resistance, mana purification |

Para obtener información detallada sobre estos principios, consulte la [descripción general de Creatures](/codex/Creatures/Creatures.md).

## Especies Inteligentes

Seres inteligentes capaces de formar civilizaciones, crear cultura y ejercer magia mediante un esfuerzo consciente:

| (Especie) Species | (Resumen) Overview | (Equilibrio Elemental) Elemental Balance |
|---------|----------|-------------------|
| [Humans](/codex/Creatures/Sentient/Humans.md) | (Adaptables e innovadores con una composición equilibrada) Adaptable and innovative with balanced composition | E: 20-55%, S: 15-45%, M: 15-60% |
| [Elves](/codex/Creatures/Sentient/Elves.md) | (Adeptos mágicos de larga vida con alta afinidad de maná) Long-lived magical adepts with high mana attunement | E: 5-25%, S: 5-15%, M: 50-80% |
| [Dark Elves](/codex/Creatures/Sentient/DarkElves.md) | (Variante élfica afinada a las sombras con habilidades únicas) Shadow-attuned elven variant with unique abilities | E: 5-25%, S: 10-20%, M: 50-80% |
| [Dwarves](/codex/Creatures/Sentient/Dwarves.md) | (Artesanos robustos con alta concentración de Exanthis) Sturdy crafters with high Exanthis concentration | E: 50-70%, S: 20-35%, M: 5-25% |
| [Beastfolk](/codex/Creatures/Sentient/Beastfolk.md) | (Seres diversos con atributos similares a los animales) Diverse beings with animal-like attributes | E: 35-70%, S: 15-35%, M: 15-40% |
| [Gnomes](/codex/Creatures/Sentient/Gnomes.md) | (Seres pequeños e inventivos con aptitud técnica) Small, inventive beings with technical aptitude | E: 30-50%, S: 30-50%, M: 15-30% |

## Seres Mágicos

Criaturas compuestas principalmente de energía mágica o creadas mediante procesos mágicos:

| (Ser) Being | (Resumen) Overview | (Equilibrio Elemental) Elemental Balance |
|-------|----------|-------------------|
| [Fae](/codex/Creatures/Magical/Fae.md) | (Seres etéreos de magia casi pura) Ethereal beings of nearly pure magic | E: 2-10%, S: 15-35%, M: 50-80% |
| [Golems](/codex/Creatures/Magical/Golems.md) | (Seres construidos con almas artificiales) Constructed beings with artificial souls | E: 70-90%, S: 5-15%, M: 5-15% |
| [Shadowfolk](/codex/Creatures/Magical/Shadowfolk.md) | (Seres nacidos de la sombra con manipulación de la oscuridad) Beings born of shadow with darkness manipulation | E: 10-30%, S: 20-40%, M: 40-70% |
| [Elementals](/codex/Creatures/Magical/Elementals.md) | (Encarnaciones puras de fuerzas elementales) Pure embodiments of elemental forces | E: 15-30%, S: 5-15%, M: 60-85% |
| [Dragonkin](/codex/Creatures/Magical/Dragonkin.md) | (Descendientes de dragones con afinidad mágica natural) Descendants of dragons with natural magical affinity | E: 55-75%, S: 5-15%, M: 20-35% |

## Animales

Fauna no inteligente con diversos grados de inteligencia y afinidad mágica:

| (Categoría) Category | (Descripción) Description | (Ejemplos) Examples |
|----------|-------------|----------|
| [Domesticated](/codex/Creatures/Animals/Domesticated.md) | (Animales criados para uso humano) Animals bred for human use | (Caballos, ganado, perros, gatos, aves de corral) Horses, cattle, dogs, cats, poultry |
| [Wild](/codex/Creatures/Animals/Wild.md) | (Fauna natural de varios biomas) Natural fauna of various biomes | (Lobos, osos, águilas, ciervos) Wolves, bears, eagles, deer |
| [Aquatic](/codex/Creatures/Animals/Aquatic.md) | (Criaturas oceánicas y de agua dulce) Ocean and freshwater creatures | (Peces, ballenas, pulpos, criaturas de río) Fish, whales, octopi, river creatures |
| [Magical](/codex/Creatures/Animals/Magical.md) | (Animales con propiedades mágicas innatas) Animals with innate magical properties | (Fénix, grifos, unicornios) Phoenixes, griffins, unicorns |

## Monstruos

Criaturas peligrosas o antinaturales que representan amenazas para las áreas civilizadas:

| (Categoría) Category | (Descripción) Description | (Ejemplos) Examples |
|----------|-------------|----------|
| [Aberrations](/codex/Creatures/Monsters/Aberrations.md) | (Criaturas antinaturales con anatomías extrañas) Unnatural creatures with bizarre anatomies | Mimics, beholders, mind flayers |
| [Undead](/codex/Creatures/Monsters/Undead.md) | (Seres que antes estaban vivos animados por fuerzas oscuras) Formerly living beings animated by dark forces | (Zombis, esqueletos, espectros) Zombies, skeletons, spectres |
| [Corrupted](/codex/Creatures/Monsters/Corrupted.md) | (Seres distorsionados por la corrupción mágica) Beings twisted by magical corruption | (Animales contaminados, elementales corrompidos) Blighted animals, tainted elementals |
| [Giants](/codex/Creatures/Monsters/Giants.md) | (Seres masivos con una fuerza extraordinaria) Massive beings with extraordinary strength | (Gigantes de piedra, gigantes de hielo, ogros) Stone giants, frost giants, ogres |

## Plantas

Flora con propiedades únicas, tanto mágicas como mundanas:

| (Categoría) Category | (Descripción) Description | (Ejemplos) Examples |
|----------|-------------|----------|
| [Magical](/codex/Creatures/Plants/Magical.md) | (Plantas con propiedades mágicas inherentes) Plants with inherent magical properties | (Raíz brillante, hoja de ensueño, hongos arcanos) Glowroot, dreamleaf, arcane fungi |
| [Medicinal](/codex/Creatures/Plants/Medicinal.md) | (Plantas con propiedades curativas) Plants with healing properties | (Hierba del curandero, musgo para detener la sangre, flores de vitalidad) Healer's herb, bloodstop moss, vitality flowers |
| [Poisonous](/codex/Creatures/Plants/Poisonous.md) | (Plantas con propiedades tóxicas) Plants with toxic properties | (Belladona, hongo de la muerte, vid venenosa) Nightshade, death cap, venom vine |
| [Sentient](/codex/Creatures/Plants/Sentient.md) | (Plantas con consciencia) Plants with consciousness | (Treants, sauces susurrantes, musgo mental) Treants, whispering willows, mindmoss |

## Seres Híbridos

Criaturas que unen múltiples categorías a través de fisiologías únicas:

| (Ser) Being | (Resumen) Overview | (Equilibrio Elemental) Elemental Balance |
|-------|----------|-------------------|
| [Centaurs](/codex/Creatures/Hybrid/Centaurs.md) | (Híbridos caballo-humanoide con sabiduría natural) Horse-humanoid hybrids with natural wisdom | E: 50-70%, S: 20-40%, M: 10-25% |
| [Merfolk](/codex/Creatures/Hybrid/Merfolk.md) | (Humanoides acuáticos con afinidad por el agua) Aquatic humanoids with water affinity | E: 30-50%, S: 15-35%, M: 25-45% |
| [Sirens](/codex/Creatures/Hybrid/Sirens.md) | (Hechiceras vocales con magia basada en el sonido) Vocal enchantresses with sound-based magic | E: 15-30%, S: 30-45%, M: 40-60% |

## Contribución

Para agregar nuevas criaturas al códice:

1. (Identifique la categoría apropiada para la criatura) Identify the appropriate category for the creature
2. (Utilice la plantilla relevante para esa categoría) Use the relevant template for that category
3. (Mantenga la coherencia con los principios de composición elemental existentes) Maintain consistency with existing elemental composition principles
4. (Incluya el contexto cultural, histórico y ecológico donde sea aplicable) Include cultural, historical, and ecological context where applicable

---

> *"Comprender las criaturas de nuestro mundo es comprender el mundo mismo, ya que son la encarnación viviente de sus diversas energías."* — (Archimaga) Archsage Lyria Thornheart


---
_Note: This content was automatically translated by Google Gemini. Please refer to the original English version for accuracy._