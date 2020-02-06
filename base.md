# 864 System
The 864 is a simplified tabletop role-playing system uses the d8, d6, and d4 dice for its mechanics. It uses dice elimination and simple modifiers to set up roll targets and determine success.

## Entities
An entity is defined as a player character, non-player character, monster, creature, or any other sentient or semi-sentient inhabitant of the adventure world, basically anything that can be considered alive (or pseudo-alive, like undead creatures).

### Abilities
Abilities define global characteristics of any sentient or semi-sentient entity. These are defined by how many dice are rolled when using them, and have three levels for measuring how capable the entity is in that area.

| Rating  | Dice         | 
|---------|--------------|
| High    | d8 + d6 + d4 |
| Average | d8 + d6      |
| Low     | d8           |

Since there are only three levels per each ability, the initial recommendation is to have multiple abilities used in the entity definition so that a lot of ground can be covered and compensate for the somwhat simple ability measurement system. These are some proposed abilities:

#### Acumen (ACU)
Measures the ability for reasoning and understanding, and for things such as investigation and research. This determines how many skills an entity can know.

#### Agility (AGI)
Measures physical nimbleness. This helps to avoid being hit by physical attacks, in conjunction with Awareness. It is used when the entity is trying to perform complex physical moves like parkour.

#### Awareness (AWA)
Determines how "in-tune" the entity is to their surroundings. This, with Agility, determines how hard it is to hit the entity.

#### Dexterity (DEX)
Measures hand-to-eye coordination and precise handiwork. Use this ability as the base for missile attacks.

#### Endurance (END)
Measures toughness and resistance to damage. This directly determines how much damage an entity can take.

#### Strength (STR)
Measures raw physical strength and power. Melee attacks would use this stat as their base.

#### Tenacity (TEN)
Measures the entity's mental strength and resilience, and also sets how much mental damage the entity can take.

### Additional stats
There are other stats that are needed to round out the basic description for an entity.

#### Mental attack target (MAT)
Determines how easy or difficult it is to hit the entity with a mental/psych attack. To determine this stat, consult the Acument and Tenacity scores. Add them up using the following reference values:

| Rating  | Modifier | 
|---------|----------|
| High    | +2       |
| Average | 0        |
| Low     | -2       |

Take 8 and add the values of both abilities. The result is the base number someone needs to roll (or higher) to affect the entity via a mental or psych attack. For example, a player character with low awareness and average acumen would have -2 + 0 + 8 = 6 or more to be affected.

#### Mental damage resistance (MDR)
Determines how much physical damage the entity can take. This is defined as follows, based on the Tenacity ability:

| Rating  | Score | 
|---------|-------|
| High    | 6     |
| Average | 4     |
| Low     | 2     |

#### Physical attack target (PAT)
Determines how easy or difficult it is to hit the entity with a physical attack. To determine this stat, consult the Agility and Awareness scores. Add them up using the following reference values:

| Rating  | Modifier | 
|---------|----------|
| High    | +2       |
| Average | 0        |
| Low     | -2       |

Take 8 and add the values of both abilities. The result is the base number someone needs to roll (or higher) to hit the entity with a physical attack. For example, a player character with high agility and average awareness would have 2 + 0 + 8 = 10 or more to be hit.

#### Physical damage resistance (PDR)
Determines how much physical damage the entity can take. This is defined as follows, based on the Endurance ability:

| Rating  | Score | 
|---------|-------|
| High    | 6     |
| Average | 4     |
| Low     | 2     |

## Creating a player character

### Abilities
There are different systems for generating a player character's abilities.

#### Direct assignment
Each player character will have two high, three average, and two low abilities. The player gets to assign these scores to their character abilities as desired.

#### Random assignment
The player rolls d864 for each ability, and then consults the table below:

| Roll  | Rating  | 
|-------|---------|
| 3-6   | Low     |
| 7-12  | Average |
| 13-18 | High    |

To make it even more random, after rolling an ability rating, the player can roll 1d8 to determine the ability to be set, based on this table:

| Roll | Ability       | 
|------|---------------|
| 1    | Acumen        |
| 2    | Agility       |
| 3    | Awareness     |
| 4    | Dexterity     |
| 5    | Endurance     |
| 6    | Strength      |
| 7    | Tenacity      |
| 8    | Player choice |

### Creating a player character

Let's create a player character using the random process. First, we will roll the ability ratings by rolling d864 7 times.

* 10 - Average
* 14 - High
* 8 - Average
* 8 - Average
* 11 - Average
* 10 - Average
* 5 - Low

Now we roll 1d8 to assign the ability ratings, starting from the first one:

* Tenacity - Average
* Dexterity - High
* Agility - Average
* Strength - Average
* Awareness - Average
* Endurance - Average
* Acumen - Low

## Base mechanics
All attempts at performing an action will be performed against a target number from 1 to 20. The player performing the action rolls the dice depending on the rating their ability or skill has.

| Rating  | Dice         | 
|---------|--------------|
| High    | d8 + d6 + d4 |
| Average | d8 + d6      |
| Low     | d8           |

Regarding the target score, the higher the number, the more difficult the action is. An easy way to set action target number is with the following table.

| Difficulty | Target | 
|------------|--------|
| Easy       | 4      |
| Normal     | 8      |
| Hard       | 14     |
| Impossible | 18     |

However, the game master is free to set the difficulty number as they wish, using any number between the ones presented here. An entity with a low rating on a skill or score will barely be able to perform an action that goes beyond normal. Similarly, an entity with an ability or skill at the average rating will rarely be able to perform anything of a hard difficulty. Impossible difficulty is only attainable by those with high ratings.
