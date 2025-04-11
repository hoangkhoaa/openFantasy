# Classes de Personnage d'OpenFantasy

> *"Dans le monde d'OpenFantasy, les classes représentent les différents chemins de pouvoir et de spécialisation que les individus peuvent suivre."*

## Référence rapide

- [Structure des classes](#class-structure)
- [Classes principales](#main-classes)
- [Progression des classes](#class-progression)
- [Multiclassage](#multiclassing)
- [Interactions Classes-Espèces](#class-species-interactions)

## Aperçu

Chaque classe dans OpenFantasy représente une harmonie unique d'[**Exanthis**](/codex/Basic/Exanthis.md), d'[**Âmes**](/codex/Basic/Soul.md) et de **Capacité de Mana**, créant une symphonie de compétences qui définit son rôle dans le monde.

## Structure des classes

Les classes sont organisées en catégories principales, chacune ayant de nombreuses sous-classes ou parcours de carrière qui découlent de la classe de base. Ces sous-classes représentent des applications spécialisées des compétences fondamentales de la classe, comme des variations sur un thème musical.

## Classes principales

### [**Guerrier**](/codex/Classes/Warrior/Warrior.md)

| Aspect (Aspect) | Details (Détails) |
|--------|---------|
| **Focus** | Combat physique et prouesses martiales |
| **Primary Element** (Élément principal) | [**Exanthis**](/codex/Basic/Exanthis.md) |
| **Metaphor** (Métaphore) | Un tambour puissant qui rythme la bataille |

**Subclasses:** (Sous-classes :)
- [**Gardien**](/codex/Classes/Warrior/Guardian.md) - Des spécialistes de la défense qui excellent dans la protection des autres
- [**Berserker**](/codex/Classes/Warrior/Berserker.md) - Des spécialistes de l'offensive qui entrent dans une rage de combat
- [**Duelist**](/codex/Classes/Warrior/Duelist.md) - Des combattants de précision qui excellent dans le combat en tête-à-tête
- [**Commander**](/codex/Classes/Warrior/Commander.md) - Des chefs tactiques qui coordonnent les efforts de groupe
- [**Weaponmaster**](/codex/Classes/Warrior/Weaponmaster.md) - Des maîtres de plusieurs armes et styles de combat

### [**Mage**](/codex/Classes/Mage/Mage.md)

| Aspect (Aspect) | Details (Détails) |
|--------|---------|
| **Focus** | Capacités magiques et lancement de sorts |
| **Primary Element** (Élément principal) | **Mana Capacity** |
| **Metaphor** (Métaphore) | Un chef d'orchestre dirigeant les éléments |

**Subclasses:** (Sous-classes :)
- [**Elementalist**](/codex/Classes/Mage/Elementalist.md) - Maîtres de la magie élémentaire (feu, eau, terre, air)
- [**Necromancer**](/codex/Classes/Mage/Necromancer.md) - Praticiens de la magie de la mort et de l'âme
- [**Illusionist**](/codex/Classes/Mage/Illusionist.md) - Créateurs d'effets magiques trompeurs
- [**Diviner**](/codex/Classes/Mage/Diviner.md) - Chercheurs de connaissances par des moyens magiques
- [**Warlock**](/codex/Classes/Mage/Warlock.md) - Traiteurs avec des entités d'un autre monde pour le pouvoir

### [**Voleur**](/codex/Classes/Rogue/Rogue.md)

| Aspect (Aspect) | Details (Détails) |
|--------|---------|
| **Focus** | Discrétion, précision et ruse |
| **Primary Element** (Élément principal) | [**Âme**](/codex/Basic/Soul.md) |
| **Metaphor** (Métaphore) | Une flûte subtile qui se déplace invisible |

**Subclasses:** (Sous-classes :)
- [**Assassin**](/codex/Classes/Rogue/Assassin.md) - Tueurs silencieux qui éliminent les cibles sans être détectés
- [**Scout**](/codex/Classes/Rogue/Scout.md) - Explorateurs qui excellent dans la collecte d'informations
- [**Trickster**](/codex/Classes/Rogue/Trickster.md) - Trompeurs qui utilisent la désorientation et l'illusion
- [**Shadowblade**](/codex/Classes/Rogue/Shadowblade.md) - Combattants furtifs qui mélangent le combat avec la subterfuge
- [**Spy**](/codex/Classes/Rogue/Spy.md) - Infiltreurs qui recueillent des renseignements au sein des rangs ennemis

### [**Clerc**](/codex/Classes/Cleric/Cleric.md)

| Aspect (Aspect) | Details (Détails) |
|--------|---------|
| **Focus** | Magie divine et guérison |
| **Primary Elements** (Éléments principaux) | [**Âme**](/codex/Basic/Soul.md) et **Mana Capacity** |
| **Metaphor** (Métaphore) | Une chorale qui relie le mortel et le divin |

**Subclasses:** (Sous-classes :)
- [**Healer**](/codex/Classes/Cleric/Healer.md) - Spécialistes de la magie réparatrice et de la guérison
- [**Paladin**](/codex/Classes/Cleric/Paladin.md) - Saints guerriers qui combinent la magie divine avec le combat
- [**Oracle**](/codex/Classes/Cleric/Oracle.md) - Récepteurs de visions divines et de prophéties
- [**Inquisitor**](/codex/Classes/Cleric/Inquisitor.md) - Chasseurs d'hérétiques et de menaces surnaturelles
- [**Shaman**](/codex/Classes/Cleric/Shaman.md) - Communicateurs avec les esprits de la nature et les ancêtres

### [**Ranger**](/codex/Classes/Ranger/Ranger.md)

| Aspect (Aspect) | Details (Détails) |
|--------|---------|
| **Focus** | Survie en milieu sauvage et combat |
| **Primary Elements** (Éléments principaux) | [**Exanthis**](/codex/Basic/Exanthis.md) et [**Âme**](/codex/Basic/Soul.md) |
| **Metaphor** (Métaphore) | Un instrument à vent qui fait écho aux sons de la forêt |

**Subclasses:** (Sous-classes :)
- [**Beastmaster**](/codex/Classes/Ranger/Beastmaster.md) - Compagnons d'animaux qui se battent à leurs côtés
- [**Hunter**](/codex/Classes/Ranger/Hunter.md) - Traqueurs qui excellent dans la recherche et l'élimination de cibles
- [**Warden**](/codex/Classes/Ranger/Warden.md) - Protecteurs des lieux naturels et de leurs habitants
- [**Scout**](/codex/Classes/Ranger/Scout.md) - Explorateurs qui excellent dans la navigation de territoires inconnus
- [**Survivalist**](/codex/Classes/Ranger/Survivalist.md) - Maîtres de la survie en milieu sauvage et de la débrouillardise

### [**Artificier**](/codex/Classes/Artificer/Artificer.md)

| Aspect (Aspect) | Details (Détails) |
|--------|---------|
| **Focus** | Création d'objets et d'appareils magiques |
| **Primary Element** (Élément principal) | **Mana Capacity** |
| **Metaphor** (Métaphore) | Un artisan qui crée des instruments de pouvoir |

**Subclasses:** (Sous-classes :)
- [**Enchanter**](/codex/Classes/Artificer/Enchanter.md) - Créateurs d'améliorations magiques pour les objets
- [**Alchemist**](/codex/Classes/Artificer/Alchemist.md) - Brasseurs de potions et de substances magiques
- [**Engineer**](/codex/Classes/Artificer/Engineer.md) - Constructeurs d'appareils mécaniques avec des composants magiques
- [**Runemaster**](/codex/Classes/Artificer/Runemaster.md) - Artisans de symboles et d'inscriptions magiques
- [**Tinkerer**](/codex/Classes/Artificer/Tinkerer.md) - Inventeurs de petits gadgets et outils magiques

### [**Barde**](/codex/Classes/Bard/Bard.md)

| Aspect (Aspect) | Details (Détails) |
|--------|---------|
| **Focus** | Performance et inspiration |
| **Primary Elements** (Éléments principaux) | [**Âme**](/codex/Basic/Soul.md) et **Mana Capacity** |
| **Metaphor** (Métaphore) | Musiciens qui tissent la magie à travers leurs performances |

**Subclasses:** (Sous-classes :)
- [**College of Eloquence**](/codex/Classes/Bard/Colleges/Eloquence.md) - Maîtres de la persuasion verbale et de l'art oratoire parfait
- [**College of Glamour**](/codex/Classes/Bard/Colleges/Glamour.md) - Artistes qui canalisent la magie d'enchantement féérique
- [**College of Lore**](/codex/Classes/Bard/Colleges/Lore.md) - Collectionneurs de connaissances et de secrets
- [**College of Spirits**](/codex/Classes/Bard/Colleges/Spirits.md) - Conteurs qui canalisent des entités surnaturelles
- [**College of Swords**](/codex/Classes/Bard/Colleges/Swords.md) - Danseurs de lames qui combinent le combat avec la performance
- [**College of Valor**](/codex/Classes/Bard/Colleges/Valor.md) - Artistes de combat qui inspirent le courage et l'héroïsme
- [**College of Whispers**](/codex/Classes/Bard/Colleges/Whispers.md) - Manipulateurs de la peur et des secrets
- [**College of Creation**](/codex/Classes/Bard/Colleges/Creation.md) - Artistes qui créent des objets physiques à travers la performance

### [**Druide**](/codex/Classes/Druid/Druid.md)

| Aspect (Aspect) | Details (Détails) |
|--------|---------|
| **Focus** | Magie de la nature et métamorphose |
| **Primary Elements** (Éléments principaux) | [**Âme**](/codex/Basic/Soul.md) et **Mana Capacity** |
| **Metaphor** (Métaphore) | Un caméléon qui s'adapte à son environnement |

**Subclasses:** (Sous-classes :)
- [**Circle of the Land**](/codex/Classes/Druid/Land.md) - Gardiens des territoires naturels
- [**Circle of the Moon**](/codex/Classes/Druid/Moon.md) - Maîtres de la métamorphose sauvage
- [**Circle of Dreams**](/codex/Classes/Druid/Dreams.md) - Connecteurs aux royaumes féériques de la nature
- [**Circle of the Shepherd**](/codex/Classes/Druid/Shepherd.md) - Protecteurs des animaux et invocateurs des esprits de la nature
- [**Circle of Spores**](/codex/Classes/Druid/Spores.md) - Contrôleurs du cycle de la vie et de la mort

### [**Moine**](/codex/Classes/Monk/Monk.md)

| Aspect (Aspect) | Details (Détails) |
|--------|---------|
| **Focus** | Force intérieure et discipline |
| **Primary Elements** (Éléments principaux) | [**Exanthis**](/codex/Basic/Exanthis.md) et [**Âme**](/codex/Basic/Soul.md) |
| **Metaphor** (Métaphore) | Un artiste martial qui a maîtrisé le flux d'énergie |

**Subclasses:** (Sous-classes :)
- [**Way of the Open Hand**](/codex/Classes/Monk/OpenHand.md) - Maîtres des techniques de combat à mains nues
- [**Way of Shadow**](/codex/Classes/Monk/Shadow.md) - Guerriers furtifs qui manipulent les ténèbres
- [**Way of the Four Elements**](/codex/Classes/Monk/FourElements.md) - Contrôleurs de l'énergie élémentaire
- [**Way of the Kensei**](/codex/Classes/Monk/Kensei.md) - Maîtres d'armes qui étendent leur esprit dans leurs armements
- [**Way of Tranquility**](/codex/Classes/Monk/Tranquility.md) - Médiateurs pacifiques qui guérissent et protègent

### [**Sorcier**](/codex/Classes/Warlock/Warlock.md)

| Aspect (Aspect) | Details (Détails) |
|--------|---------|
| **Focus** | Pactes avec des entités surnaturelles |
| **Primary Elements** (Éléments principaux) | [**Âme**](/codex/Basic/Soul.md) et **Mana Capacity** |
| **Metaphor** (Métaphore) | Un musicien qui a vendu son âme pour le talent |

**Subclasses:** (Sous-classes :)
- [**The Fiend**](/codex/Classes/Warlock/Fiend.md) - Pacte avec des entités démoniaques
- [**The Archfey**](/codex/Classes/Warlock/Archfey.md) - Pacte avec de puissantes créatures féériques
- [**The Great Old One**](/codex/Classes/Warlock/GreatOldOne.md) - Pacte avec d'anciennes entités cosmiques
- [**The Celestial**](/codex/Classes/Warlock/Celestial.md) - Pacte avec des êtres divins
- [**The Hexblade**](/codex/Classes/Warlock/Hexblade.md) - Pacte avec une arme sensible ou une entité d'ombre

## Progression des classes

Les classes dans OpenFantasy suivent un système de progression qui permet aux individus de développer leurs capacités au fil du temps. Cette progression est représentée par des niveaux, chacun donnant accès à de nouvelles capacités et pouvoirs, comme un musicien qui apprend des morceaux de plus en plus complexes.

### Niveaux

| Tier (Palier) | Levels (Niveaux) | Description (Description) |
|------|--------|-------------|
| **Novice** | 1-5 | Débutants apprenant les principes fondamentaux |
| **Adept** | 6-10 | Maîtres des bases développant la spécialisation |
| **Expert** | 11-15 | Spécialistes avec des capacités très affûtées |
| **Master** | 16-20 | Ceux qui ont atteint une véritable maîtrise |
| **Legendary** | 21+ | Individus transcendant les limitations normales |

## Multiclassage

Certaines personnes choisissent de suivre plusieurs classes, combinant les capacités de différents chemins pour créer des combinaisons uniques. Cette pratique, connue sous le nom de multiclassage, permet une plus grande polyvalence, mais peut limiter la profondeur de la spécialisation dans une seule classe, comme un musicien qui joue de plusieurs instruments mais peut ne maîtriser aucun d'entre eux.

## Interactions Classes-Espèces

Différentes espèces ont des affinités naturelles pour certaines classes en fonction de leur composition élémentaire :

| Species (Espèce) | Natural Class Affinities (Affinités de Classe Naturelles) |
|---------|--------------------------|
| **Humans** (Humains) | Affinité équilibrée pour toutes les classes |
| **Elves** (Elfes) | Forte affinité pour les classes de Mage, Ranger et Barde |
| **Dark Elves** (Elfes Noirs) | Forte affinité pour les classes de Mage, Voleur et Sorcier |
| **Dwarves** (Nains) | Forte affinité pour les classes de Guerrier, Artificier et Clerc |
| **Beastfolk** (Hommes-bêtes) | Forte affinité pour les classes de Ranger, Druide et Guerrier |
| **Dragonkin** (Draconiens) | Forte affinité pour les classes de Guerrier, Mage et Sorcier |
| **Fae** (Fées) | Forte affinité pour les classes de Barde, Druide et Mage |
| **Golems** (Golems) | Forte affinité pour les classes d'Artificier et de Guerrier |
| **Sirens** (Sirènes) | Forte affinité pour les classes de Barde et de Mage |
| **Shadowfolk** (Peuple de l'Ombre) | Forte affinité pour les classes de Voleur, Sorcier et Mage |
| **Giants** (Géants) | Forte affinité pour les classes de Guerrier et de Druide |

---

> Comprendre la nature des classes donne un aperçu des divers chemins de pouvoir dans le monde d'**OpenFantasy**, comme écouter les différentes mélodies qui composent la grande symphonie de l'existence.


---
_Note: This content was automatically translated by Google Gemini. Please refer to the original English version for accuracy._