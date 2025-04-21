> [!WARNING]
> under construction

## Party
a team/party consists of 5 [CHARACTERS](../characters)! you can change who is on your party (whenever outside combat? at a specific place?)
you will be using this team to deal with combat and exploring the overworld

each character is unique in how they contribute to the team so choose whichever team combinations fit you the most!

---
## kB and MB (mana and currency system)
every ability needs a certain amount of `kB` to be performed  
the `kB bar` starts out empty at the start of each battle and can be filled by attacking enemies, every character use the same `kB bar`

excess `kB` gets turned into `MB` at the end of each battle using this formula:
```
((% fullness of kB bar) × 0.5) rounded up = MB
if the kB bar is 100% full, 60 MB is recieved
```
`MB` is used as currency to buy and or upgrade items

---
## Stats
your STATS determine how strong you are, of course your STATS get stronger each time you level up.  some [ITEMS](./Items.md) can also boost certain stats when equiped

### Overview
**HP:** health points! hit 0 and that character dies(?)  
**ATK:** attack power! the standard STAT that determines how strong your attacks are  
**DEF:** defence! how do u explain defence help  
**SPD:** speed! characters with higher speed than others move first and have a chance of evading some attacks  

### Standard Base Stats
HP: 100-200  
ATK: 20-50  
DEF: 20-50  
SPD: 1-10  

---
## Battle
the system works similarly to traditional RPGs, each character can defend, use abilities, or use items in their turn  
the standard attack button is replaced with defend, which generates 10 kB and blocks incoming damage for 25%

---
## Effects
### Status Effects
|Name|Description|
|:---|:---|
|Art Block|Prevents character from using any moves requiring kB|
|Inspired|Raises the amount of kB gained when attacking or being attacked.  If the status goes for 5 or more turns, inflicts Burnout for 1 turn (+1 turn the longer the character gets inspired)|
|Burnout|Character skips the turn and their sprite turns into a 30 seconds challenge version of itself with fire in the background|
|Compressed|Compresses the character into a smaller canvas.  halved kB cost and their sprite gets compressed into pixels|
|Upscaled|Upscales the character into a bigger canvas. +50% kB cost but 50% more effective moves|
|Transparent|Character turns invinsible, enemy has a 50% chance of landing attacks.  goes away after an attack lands or if the user does a move directed at an ally or enemy.  if the move is an attack, defense of target is halved when calculating damage|
|Locked In|All moves are 50% more effective, this character cannot be healed|


### Field Effects
|Name|Description|
|:---|:---|
|???|...|
|???|...|
|???|...|

---
## General Skills
skills most characters can learn by buying or other methods
|Name|Description|Cost|How to Get|
|:---|:---|---|:---|
|Study|Skips one turn to gains a random move from an enemy that lasts until the battle ends|???kB|???|
|Lurk|Goes TRANSPARENT for 5 turns, as each turn progress, heals 5 HP to self.|???kB|???|
|Inspire|Makes a character INSPIRED for 5 turns|???kB|???|
|Calm Down|Heals self for 10 HP and 80% chance to remove all status effects|???kB|???|
|||???kB|???|
