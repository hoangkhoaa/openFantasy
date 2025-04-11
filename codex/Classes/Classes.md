# Clases de Personaje en OpenFantasy

> *"En el mundo de OpenFantasy, las clases representan los diversos caminos de poder y especialización que los individuos pueden seguir."*

## Referencia Rápida

- [Estructura de Clase](#estructura-de-clase)
- [Clases Principales](#clases-principales)
- [Progresión de Clase](#progresion-de-clase)
- [Multiclase](#multiclase)
- [Interacciones Clase-Especie](#interacciones-clase-especie)

## Resumen

Cada clase en OpenFantasy representa una armonía única de [**Exanthis**](/codex/Basic/Exanthis.md), [**Almas**](/codex/Basic/Soul.md), y **Capacidad de Maná**, creando una sinfonía de habilidades que define su rol en el mundo.

## Estructura de Clase

Las clases están organizadas en categorías principales, cada una con numerosas subclases o caminos de carrera que se ramifican de la clase central. Estas subclases representan aplicaciones especializadas de las habilidades fundamentales de la clase, como variaciones sobre un tema musical.

## Clases Principales

### [**Guerrero**](/codex/Classes/Warrior/Warrior.md)

| Aspecto | Detalles |
|--------|---------|
| **Enfoque** | Combate físico y destreza marcial |
| **Elemento Primario** | [**Exanthis**](/codex/Basic/Exanthis.md) |
| **Metáfora** | Un poderoso tambor que impulsa el ritmo de la batalla |

**Subclases:**
- [**Guardián**](/codex/Classes/Warrior/Guardian.md) - Especialistas defensivos que sobresalen en proteger a otros
- [**Berserker**](/codex/Classes/Warrior/Berserker.md) - Especialistas ofensivos que entran en un furor de batalla
- [**Duelista**](/codex/Classes/Warrior/Duelist.md) - Luchadores de precisión que sobresalen en el combate uno contra uno
- [**Comandante**](/codex/Classes/Warrior/Commander.md) - Líderes tácticos que coordinan los esfuerzos grupales
- [**Maestro de Armas**](/codex/Classes/Warrior/Weaponmaster.md) - Maestros de múltiples armas y estilos de combate

### [**Mago**](/codex/Classes/Mage/Mage.md)

| Aspecto | Detalles |
|--------|---------|
| **Enfoque** | Habilidades mágicas y lanzamiento de hechizos |
| **Elemento Primario** | **Capacidad de Maná** |
| **Metáfora** | Un director que orquesta los elementos |

**Subclases:**
- [**Elementalista**](/codex/Classes/Mage/Elementalist.md) - Maestros de la magia elemental (fuego, agua, tierra, aire)
- [**Nigromante**](/codex/Classes/Mage/Necromancer.md) - Practicantes de la magia de la muerte y el alma
- [**Ilusionista**](/codex/Classes/Mage/Illusionist.md) - Creadores de efectos mágicos engañosos
- [**Adivino**](/codex/Classes/Mage/Diviner.md) - Buscadores de conocimiento a través de medios mágicos
- [**Brujo**](/codex/Classes/Mage/Warlock.md) - Negociadores con entidades de otro mundo por poder

### [**Pícaro**](/codex/Classes/Rogue/Rogue.md)

| Aspecto | Detalles |
|--------|---------|
| **Enfoque** | Sigilo, precisión y astucia |
| **Elemento Primario** | [**Alma**](/codex/Basic/Soul.md) |
| **Metáfora** | Una flauta sutil que se mueve sin ser vista |

**Subclases:**
- [**Asesino**](/codex/Classes/Rogue/Assassin.md) - Asesinos silenciosos que eliminan objetivos sin ser detectados
- [**Explorador**](/codex/Classes/Rogue/Scout.md) - Exploradores que sobresalen en la recopilación de información
- [**Embaucador**](/codex/Classes/Rogue/Trickster.md) - Engañadores que usan la tergiversación y la ilusión
- [**Hoja de Sombra**](/codex/Classes/Rogue/Shadowblade.md) - Luchadores sigilosos que combinan el combate con el subterfugio
- [**Espía**](/codex/Classes/Rogue/Spy.md) - Infiltrados que recopilan inteligencia desde dentro de las filas enemigas

### [**Clérigo**](/codex/Classes/Cleric/Cleric.md)

| Aspecto | Detalles |
|--------|---------|
| **Enfoque** | Magia divina y curación |
| **Elementos Primarios** | [**Alma**](/codex/Basic/Soul.md) y **Capacidad de Maná** |
| **Metáfora** | Un coro que une lo mortal y lo divino |

**Subclases:**
- [**Sanador**](/codex/Classes/Cleric/Healer.md) - Especialistas en magia restaurativa y curación
- [**Paladín**](/codex/Classes/Cleric/Paladin.md) - Guerreros sagrados que combinan la magia divina con el combate
- [**Oráculo**](/codex/Classes/Cleric/Oracle.md) - Receptores de visiones y profecías divinas
- [**Inquisidor**](/codex/Classes/Cleric/Inquisitor.md) - Cazadores de herejes y amenazas sobrenaturales
- [**Chamán**](/codex/Classes/Cleric/Shaman.md) - Comunicadores con espíritus de la naturaleza y ancestros

### [**Guardabosques**](/codex/Classes/Ranger/Ranger.md)

| Aspecto | Detalles |
|--------|---------|
| **Enfoque** | Supervivencia y combate en la naturaleza |
| **Elementos Primarios** | [**Exanthis**](/codex/Basic/Exanthis.md) y [**Alma**](/codex/Basic/Soul.md) |
| **Metáfora** | Un instrumento de viento madera que hace eco de los sonidos del bosque |

**Subclases:**
- [**Amo de las Bestias**](/codex/Classes/Ranger/Beastmaster.md) - Compañeros de animales que luchan a su lado
- [**Cazador**](/codex/Classes/Ranger/Hunter.md) - Rastreadores que sobresalen en encontrar y eliminar objetivos
- [**Guardián**](/codex/Classes/Ranger/Warden.md) - Protectores de lugares naturales y sus habitantes
- [**Explorador**](/codex/Classes/Ranger/Scout.md) - Exploradores que sobresalen en la navegación por territorios desconocidos
- [**Superviviente**](/codex/Classes/Ranger/Survivalist.md) - Maestros de la supervivencia en la naturaleza y el ingenio

### [**Artífice**](/codex/Classes/Artificer/Artificer.md)

| Aspecto | Detalles |
|--------|---------|
| **Enfoque** | Creación de objetos y dispositivos mágicos |
| **Elemento Primario** | **Capacidad de Maná** |
| **Metáfora** | Un artesano que crea instrumentos de poder |

**Subclases:**
- [**Encantador**](/codex/Classes/Artificer/Enchanter.md) - Creadores de mejoras mágicas para objetos
- [**Alquimista**](/codex/Classes/Artificer/Alchemist.md) - Elaboradores de pociones y sustancias mágicas
- [**Ingeniero**](/codex/Classes/Artificer/Engineer.md) - Constructores de dispositivos mecánicos con componentes mágicos
- [**Maestro de Runas**](/codex/Classes/Artificer/Runemaster.md) - Creadores de símbolos e inscripciones mágicas
- [**Manitas**](/codex/Classes/Artificer/Tinkerer.md) - Inventores de pequeños aparatos y herramientas mágicas

### [**Bardo**](/codex/Classes/Bard/Bard.md)

| Aspecto | Detalles |
|--------|---------|
| **Enfoque** | Interpretación e inspiración |
| **Elementos Primarios** | [**Alma**](/codex/Basic/Soul.md) y **Capacidad de Maná** |
| **Metáfora** | Músicos que tejen magia a través de sus actuaciones |

**Subclases:**
- [**Colegio de Elocuencia**](/codex/Classes/Bard/Colleges/Eloquence.md) - Maestros de la persuasión verbal y la oratoria perfecta
- [**Colegio del Glamour**](/codex/Classes/Bard/Colleges/Glamour.md) - Artistas que canalizan la magia de encantamiento fey
- [**Colegio del Saber**](/codex/Classes/Bard/Colleges/Lore.md) - Coleccionistas de conocimiento y secretos
- [**Colegio de los Espíritus**](/codex/Classes/Bard/Colleges/Spirits.md) - Narradores que canalizan entidades sobrenaturales
- [**Colegio de las Espadas**](/codex/Classes/Bard/Colleges/Swords.md) - Bailarines de espada que combinan el combate con la interpretación
- [**Colegio del Valor**](/codex/Classes/Bard/Colleges/Valor.md) - Intérpretes de batalla que inspiran coraje y heroísmo
- [**Colegio de los Susurros**](/codex/Classes/Bard/Colleges/Whispers.md) - Manipuladores del miedo y los secretos
- [**Colegio de la Creación**](/codex/Classes/Bard/Colleges/Creation.md) - Artistas que crean objetos físicos a través de la interpretación

### [**Druida**](/codex/Classes/Druid/Druid.md)

| Aspecto | Detalles |
|--------|---------|
| **Enfoque** | Magia de la naturaleza y cambio de forma |
| **Elementos Primarios** | [**Alma**](/codex/Basic/Soul.md) y **Capacidad de Maná** |
| **Metáfora** | Un camaleón que se adapta a su entorno |

**Subclases:**
- [**Círculo de la Tierra**](/codex/Classes/Druid/Land.md) - Guardianes de territorios naturales
- [**Círculo de la Luna**](/codex/Classes/Druid/Moon.md) - Maestros del cambio de forma salvaje
- [**Círculo de los Sueños**](/codex/Classes/Druid/Dreams.md) - Conectores a los reinos fey de la naturaleza
- [**Círculo del Pastor**](/codex/Classes/Druid/Shepherd.md) - Protectores de animales e invocadores de espíritus de la naturaleza
- [**Círculo de las Esporas**](/codex/Classes/Druid/Spores.md) - Controladores del ciclo de la vida y la muerte

### [**Monje**](/codex/Classes/Monk/Monk.md)

| Aspecto | Detalles |
|--------|---------|
| **Enfoque** | Fuerza interior y disciplina |
| **Elementos Primarios** | [**Exanthis**](/codex/Basic/Exanthis.md) y [**Alma**](/codex/Basic/Soul.md) |
| **Metáfora** | Un artista marcial que ha dominado el flujo de energía |

**Subclases:**
- [**Sendero de la Mano Abierta**](/codex/Classes/Monk/OpenHand.md) - Maestros de las técnicas de combate sin armas
- [**Sendero de la Sombra**](/codex/Classes/Monk/Shadow.md) - Guerreros sigilosos que manipulan la oscuridad
- [**Sendero de los Cuatro Elementos**](/codex/Classes/Monk/FourElements.md) - Controladores de la energía elemental
- [**Sendero del Kensei**](/codex/Classes/Monk/Kensei.md) - Maestros de armas que extienden su espíritu a sus armamentos
- [**Sendero de la Tranquilidad**](/codex/Classes/Monk/Tranquility.md) - Mediadores pacíficos que sanan y protegen

### [**Brujo**](/codex/Classes/Warlock/Warlock.md)

| Aspecto | Detalles |
|--------|---------|
| **Enfoque** | Pactos con entidades sobrenaturales |
| **Elementos Primarios** | [**Alma**](/codex/Basic/Soul.md) y **Capacidad de Maná** |
| **Metáfora** | Un músico que ha vendido su alma por talento |

**Subclases:**
- [**El Infernal**](/codex/Classes/Warlock/Fiend.md) - Pacto con entidades demoníacas
- [**El Archifey**](/codex/Classes/Warlock/Archfey.md) - Pacto con poderosas criaturas fey
- [**El Gran Antiguo**](/codex/Classes/Warlock/GreatOldOne.md) - Pacto con antiguas entidades cósmicas
- [**El Celestial**](/codex/Classes/Warlock/Celestial.md) - Pacto con seres divinos
- [**La Hoja Maldita**](/codex/Classes/Warlock/Hexblade.md) - Pacto con un arma sintiente o entidad de sombra

## Progresión de Clase

Las clases en OpenFantasy siguen un sistema de progresión que permite a los individuos desarrollar sus habilidades con el tiempo. Esta progresión está representada por niveles, cada uno otorgando acceso a nuevas habilidades y poderes, como un músico que aprende piezas cada vez más complejas.

### Niveles de Nivel

| Nivel | Niveles | Descripción |
|------|--------|-------------|
| **Novicio** | 1-5 | Principiantes que aprenden fundamentos |
| **Adepto** | 6-10 | Maestros de los conceptos básicos que desarrollan la especialización |
| **Experto** | 11-15 | Especialistas con habilidades altamente perfeccionadas |
| **Maestro** | 16-20 | Aquellos que han alcanzado la verdadera maestría |
| **Legendario** | 21+ | Individuos que trascienden las limitaciones normales |

## Multiclase

Algunos individuos eligen seguir múltiples clases, combinando habilidades de diferentes caminos para crear combinaciones únicas. Esta práctica, conocida como multiclase, permite una mayor versatilidad pero puede limitar la profundidad de la especialización en cualquier clase individual, como un músico que toca varios instrumentos pero puede no dominar ninguno solo.

## Interacciones Clase-Especie

Diferentes especies tienen afinidades naturales por ciertas clases basadas en su composición elemental:

| Especie | Afinidades Naturales de Clase |
|---------|--------------------------|
| **Humanos** | Afinidad equilibrada para todas las clases |
| **Elfos** | Fuerte afinidad por las clases de Mago, Guardabosques y Bardo |
| **Elfos Oscuros** | Fuerte afinidad por las clases de Mago, Pícaro y Brujo |
| **Enanos** | Fuerte afinidad por las clases de Guerrero, Artífice y Clérigo |
| **Hombres Bestia** | Fuerte afinidad por las clases de Guardabosques, Druida y Guerrero |
| **Dracónidos** | Fuerte afinidad por las clases de Guerrero, Mago y Brujo |
| **Fae** | Fuerte afinidad por las clases de Bardo, Druida y Mago |
| **Golems** | Fuerte afinidad por las clases de Artífice y Guerrero |
| **Sirenas** | Fuerte afinidad por las clases de Bardo y Mago |
| **Gente de las Sombras** | Fuerte afinidad por las clases de Pícaro, Brujo y Mago |
| **Gigantes** | Fuerte afinidad por las clases de Guerrero y Druida |

---

> Comprender la naturaleza de las clases proporciona información sobre los diversos caminos del poder en el mundo de **OpenFantasy**, como escuchar las diferentes melodías que componen la gran sinfonía de la existencia.


---
_Note: This content was automatically translated by Google Gemini. Please refer to the original English version for accuracy._