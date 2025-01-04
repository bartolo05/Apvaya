---
Type: Player
Art: "![[../img/scoot.jpg]]"
Level: 3
AC: 17
Prof: 2
HP: 35
HitDice: d12
Speed: 30
STR: 16
DEX: 10
CONST: 16
INT: 10
WIS: 12
CHA: 11
Race: Tortle
Alignment: NONE
Gender: Male
Age: "0"
Location: NONE
Class: Barbarian
Subclass: Ancestral guardian
AssociatedGroup: NONE
Likes: NONE
Dislikes: NONE
Pronouns: NONE
PersonalityTrait:
  - NONE
SocialTrait:
  - NONE
MentalTrait:
  - NONE
Proficiencies:
  - NONE
Resistances:
  - NONE
Languages:
  - NONE
DmgTkn: 0
TempHP: 0
Copper: 0
Silver: 0
Electrum: 0
Gold: 10
Platinum:
---


>[!column|flex 2]
>> [!infobox]
>> # `=this.file.name`
>> ![](../img/scoot.jpg)
>> ###### Stats
>>  |
>> ---|---|
>> **Level** |`=this.level` |
>>  **Speed** |`=this.Speed` |
>> **Proficiency** | +`=this.Prof` |
>> **Initiative** | +`=(this.DEX - 10)/2` |
>> **AC** | `=this.AC`
>> **HP** | `=this.HP - this.DmgTkn + this.TempHP` |
>> **Hit Dice** | `=this.Level + this.HitDice`  |
>> **Passive Perception** |
>>  
>> ###### Bio
>>   |
>> ---|---|
>> **Race** | `=this.race` |
>> **Sex** | `=this.gender` |
>> **Age** | `=this.age` |
>> **Sexuality** | `=this.sexuality` |
>> **Alignment** | `=this.alignment` |
>> ###### Info
>>   |
>> ---|---|
>> **Class(s)** | `=this.Class` |
>> **Sub-Class(s)** | `=this.Subclass`
>> **Group(s)** | `=this.AssociatedGroup` |
>> **Religion(s)** | `=this.AssociatedReligion` |
>> **Current Location** | `=this.Location` |
>>  ### Currency
| Copper         | Silver         | Gold         | Platinum         |
| -------------- | -------------- | ------------ | ---------------- |
| `=this.Copper` | `=this.Silver` | `=this.Gold` | `=this.Platinum` |
>
>> [!infobox] Death Saves
>> ### Death Saves
| Success | <input type="checkbox" unchecked>  | <input type="checkbox" unchecked> | <input type="checkbox" unchecked> | 
| ------- | --- | --------------------------------- | --------------------------------- |
>>
| Fails | <input type="checkbox" unchecked>  | <input type="checkbox" unchecked> | <input type="checkbox" unchecked> | 
| ----- | --- | --------------------------------- | --------------------------------- |
>>
>> ### Skills
| Skill | Score       | Mod                     | Prof                              | ST                                  |
| ----- | ----------- | ----------------------- | --------------------------------- | ----------------------------------- |
| <font color="#ff0000">**STR**</font>   | `=this.STR` | +`=(this.STR - 10)/2`   | <input type="checkbox" checked> | +`=(this.STR - 10)/2 + this.prof`               |
| <font color="#ffff00">**DEX**</font>   | `=this.DEX`  | +`=(this.DEX - 10)/2`   | <input type="checkbox" unchecked> | +`=(this.DEX - 10)/2`               |
| <font color="#00b050">**CON**</font>   | `=this.CONST` | +`=(this.CONST - 10)/2` | <input type="checkbox" checked>   | +`=((this.CONST - 10)/2) + this.prof` |
| <font color="#7030a0">**INT**</font>   | `=this.INT`          | +`=(this.INT - 10)/2`   | <input type="checkbox" unchecked>   | +`=((this.INT - 10)/2)`   |
| <font color="#245bdb">**WIS**</font>   | `=this.WIS`          | +`=(this.WIS - 10)/2`   | <input type="checkbox" unchecked> | +`=(this.WIS - 10)/2`               |
| <font color="#de7802">**CHA**</font>   | `=this.CHA`          | +`=(this.CHA - 11)/2`   | <input type="checkbox" unchecked> | +`=(this.CHA - 11)/2`               |
>> ### Skill Checks
| Ability               |                                   | Mod |
| --------------------- | --------------------------------- | --- |
| Acrobatics (DEX)      | <input type="checkbox" unchecked> | +`=(this.DEX - 10)/2`   |
| Animal Handling (WIS) | <input type="checkbox" unchecked> | +`=(this.WIS - 10)/2`  |
| Arcana (INT)          | <input type="checkbox" unchecked> | +`=((this.INT - 10)/2)`  |
| Athletics (STR)       | <input type="checkbox" checked> | +`=((this.STR - 10)/2 + this.prof)`   |
| Deception (CHA)       | <input type="checkbox" unchecked> | +`=(this.CHA - 11)/2`  |
| History (INT)         | <input type="checkbox" unchecked> | +`=(this.INT - 10)/2`  |
| Insight (WIS)         | <input type="checkbox" unchecked>   | +`=((this.WIS - 10)/2)`  |
| Intimidation (CHA)    | <input type="checkbox" checked> | +`=(this.CHA - 11)/2`  |
| Investigation (INT)   | <input type="checkbox" unchecked>   | +`=((this.INT - 10)/2)`  |
| Medicine (WIS)        | <input type="checkbox" unchecked> | +`=(this.WIS - 10)/2`  |
| Nature (INT)          | <input type="checkbox" unchecked> | +`=(this.INT - 10)/2`  |
| Perception (WIS)      | <input type="checkbox" checked>   | +`=((this.WIS - 10)/2) + this.prof`  |
| Performance (CHA)     | <input type="checkbox" unchecked> | +`=(this.CHA - 11)/2`  |
| Persuasion (CHA)      | <input type="checkbox" unchecked> | +`=(this.CHA - 11)/2`  |
| Religion (INT)        | <input type="checkbox" unchecked> | +`=(this.INT - 10)/2`  |
| Sleight of Hand (DEX) | <input type="checkbox" unchecked> | +`=(this.DEX - 10)/2`   |
| Stealth (DEX)         | <input type="checkbox" checked> | +`=(this.DEX - 10)/2 + this.prof`   |
| Survival (WIS)        | <input type="checkbox" checked> | +`=(this.WIS - 10)/2 + this.prof`  |






![](../img/scoot.jpg)