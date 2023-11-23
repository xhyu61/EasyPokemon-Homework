# EasyPokemon-Homework
![](https://img.shields.io/badge/lang-C%2B%2B-red)

Harbin Engineering University object-oriented course homework

## Project info
The project is created on 2021.12.05, used to finish the homework of my object-oriented course in Harbin Engineering University.

(In fact, I didn't use so much object-oriented thing in this project)

### What is Pokémon?
https://en.wikipedia.org/wiki/Pokémon

You will be a trainer, and you'll have some pokemons to fight with other trainers. Each pokemon have levels, skills, ability values, attributes.

#### pokemon's level
Level is an integer. Every Pokemon will have the base level 1 when you get the pokemon.Higher level can make pokemon stronger. You can give your pokemon exp to upgrade them.

Win the fight can earn exp.Each levels have different requirement to exp.The maximum level is 100. When pokemon reach Lv.100, there is no more exp can be earned.

Different pokemons may have different upgrade types which have different exp upperbound in each level.

#### pokemon's skills
Each pokemon have 4 skills, different with the official pokemon game which can get new skills when upgrade, in this project, each pokemon only have 4 skills.

Skills have their own type, damage_value, PP. Damage_value is an important value which decides the final damage. PP is the times you can use this skill in one battle.

#### pokemon's ability values
Ability values includes pokemons base HP, base physical atk, base physical def, base special atk, base special def.

It can be increased by upgrading level. It is used to calculate the final damage.

#### pokemon's attribute
Every pokemon has 1 or 2 attributes in official games, but in this project, only 1 attribute is used.

There exists attribute restraint in battle. With the restraint, the damage of the skill will be times 0, 0.5, 1 or 2.  (In official, there is also 0.25 and 4)

### What is inside?
* **EasyPokemon.cpp**: The main code of the project. (Actually, it's better to code with many cpp files, but I don't have so much time to do it.)
* **ExpUpperBound.txt**: The txt file contains the upperbound of exp in each level for different upgrade types.
* **Ability_Change.txt**: Values that times the pokemon's base ability value when pokemon get buffs or debuffs. (-6 ~ +6)
* **B.txt**: Every Skill have a value which decides the probability that the skill can use successfully. (The judgement of successfully using the skill is quite different from the official game)
* **Pokemon_Information.txt**: Contains the pokemon's base information. The project only choose a small ammount of pokemons.
* **Skill_Information.txt**: Contains the skill's base information, such as name, PP, damage_value, attribute.
* **Skill_Detail.txt**: Contains the descriptions of each skills for players.
* **StatusName.txt**: Contains the name of each status.
* **TypeCross.txt**: Contains the coefficient of the attribute restraint.
* **TypeName.txt**: Contains the name of each attribute.
* **Save1.txt**: Used to save the information of save 1.
* **Save2.txt**: Used to save the information of save 2.
* **Save3.txt**: Used to save the information of save 3.
