---
Art: "![[CutieGoblinNerd.webp|center]]"
Level: 1
STR: 16
INT: 14
WIS: 14
DEX: 15
CON: 15
CHA: 11
BodySav: "`=floor((this.STR - 10)/3) + floor((this.CON - 10)/3)`"
MindSav: "`=floor((this.INT - 10)/3) + floor((this.CHA - 10)/3)`"
ReflexSav: "`=floor((this.DEX - 10)/3) + floor((this.WIS - 10)/3)`"
AtkBonus: 0
SavBonus: 0
xp: 3
LevelXP: "`=(this.Level*10)`"
MaxHP: 7
Fatigue: "`=this.CON`"
axp: 
background: Beast Hunter
Weapon1: Shortsword
Weapon1dmg: D6+2
Weapon1notes: Piercing / Slashing
Weapon2: 
Weapon2dmg: 
Weapon2notes: 
Armor1: Leather Armor
Armor1Bod: 1
Armor1Ref: 0
Armor1notes: 
Armor2: 
Armor2rate: 0
Armor2notes: 
torch1: D8
Lampoil: None
CurrentFatigue: 0
CurrentHP: 6
Ability1: "[[Witchcraft]]"
Ability2: Diabolic Language
Spell1: "[[Rebuke Sorcery]]"
Spell2: "[[Scorn the Unwelcome]]"
Spell3: "[[Rebuke the Undead]]"
title1: Torch
title2: Bandages x2
title3: Bedroll (Recover Fatigue in the wilds)
title4: "Thieves Tools, Simple "
title5: "Travel Rations "
title6: "Travel Rations "
title7: Gem (400sp)
title8: Bandage (Halts Bleeding and heals 1d4 HP on successful +INT  check. +1 Fatigue.)
title9: Gems (100 sp) x2
title10: Religious Trappings (300 sp)
title11: Alcohol (250 sp)
title12: Gem (50 sp)
lightitem1: ""
---

>[!dice] %%FAKE TITLE HERE%%
>> [!dice] %%FAKE TITLE HERE%%
>> ## `=this.file.name`
>> `=this.Art`
>>```meta-bind
>>INPUT[progressBar(class(green-progress-bar), maxValue(7), title(HP)):CurrentHP]
>>```
>>```meta-bind
>>INPUT[progressBar(class(pink-progress-bar), maxValue(15), title(Fatigue)):CurrentFatigue]
>>```
>> ##### Stats 
>>|     |     |
>> |:---: | :---: |
>>|**Level**|`=this.Level`|
>>|**Max HP:** |`=this.MaxHP`|
>> |**Max Fatigue:** |`=this.Fatigue`|
>> |**Max Inv Slots:** |`=this.STR`|
>> |**XP** | `VIEW[{xp}][text]`|
>> |**XP Needed:** | `=this.LevelXP`|
>>|**ADD XP**| `INPUT[number:axp]` `BUTTON[exp]`|
>>&nbsp;
>>
>> ##### Attribute Scores 
>>| Attribute | Score | Mod |
>>| :---: | :---: | :---: |
>>| **Strength** | `=this.STR` | +`=floor((this.STR - 10)/3)`| 
>>| **Intelligence** | `=this.INT` | +`=floor((this.INT - 10)/3)`|
>>| **Wisdom** | `=this.WIS` | +`=floor((this.WIS - 10)/3)`
>>| **Dexterity** | `=this.DEX` | +`=floor((this.DEX - 10)/3)`
>>| **Constitution** | `=this.CON` |+`=floor((this.CON - 10)/3)`| 
>>| **Charisma** | `=this.CHA` | +`=floor((this.CHA - 10)/3)`| 
>>
>>&nbsp;
>>
>> ##### Saves vs Target 16
>>|    |  Save | Save Bonus |
>> |:---: | :---: | :---: |
>> |**Body Save**| `=this.BodySav` |+`=this.SavBonus`| 
>> |**Mind Save**| `=this.MindSav` |+`=this.SavBonus`|
>> |**Reflex Save**| `=this.ReflexSav` |+`=this.SavBonus`|
>>
>>
>>&nbsp;
>>
>> ##### Damage Mods
>>|     | Attribute Bonus | Atk Bonus |
>> |:---: | :---: | :---: |
>>|**Melee**|+`=floor((this.STR - 10)/3)`| +`=this.AtkBonus`|
>>|**Ranged**|+`=floor((this.DEX - 10)/3)`|+`=this.AtkBonus`|
>> || |

### Weapons & Supplies
>[!rng] %%FAKE TITLE HERE%%
>> [!rng] %%FAKE TITLE HERE%%
>> ##### Weapons
>>| **Weapons** | **Damage** | **Quality** | **Notes** |
>>| --------- | :---: | :---: |-----|
>>| `=this.Weapon1` | `=this.Weapon1dmg` | `3` |`=this.Weapon1notes` |
>>| `=this.Weapon2` | `=this.Weapon2dmg` |`0`| `=this.Weapon2notes` |
>>
>>
>>&nbsp;
>>
>> ##### Armor
>>| **Armor** | **Body** | **Reflex** |**Quality** | **Notes**|
>>| ----------- | :---: | :---: | ------ |------ |
>>| `=this.Armor1` | `=this.Armor1Bod`|`=this.Armor1Ref` |`0` | `=this.Armor1notes` |
>>| `=this.Armor2` |  `=this.Armor1Bod`|`=this.Armor1Ref` |`0`| `=this.Armor2notes` |
>>
>>
>>&nbsp;
>>
>> ##### Supplies
>>  | |
>>---|---|
>>**Silver Pieces (sp)**|`80` |
>>**Gold Pieces (gp)**|`0` |
>>**Bronze Pieces (bp)**|`0` | 
>>**Rations**|`6` |
>>**Torches**| `INPUT[inlineSelect(option(D12), option(D10), option(D8), option(D6), option(D4), option(None)):torch1]` |
>>**Lamp Oil**|`INPUT[inlineSelect(option(D12), option(D10), option(D8), option(D6), option(D4), option(None)):Lampoil]` |


### Timers & Counters
>[!crafting] %%FAKE TITLE HERE%%
>> [!crafting] %%FAKE TITLE HERE%%
>> ##### Timers & Counters
>>  | |
>>---|---|
>>**Watches**| `clock,yellow: 0/4` |
>>**Encounter Penalties**|`circles,pink: 0/10`|
>>**Goal Timer**|`circles,yellow: 5/12`|
>>**Progress Track**|`circles,green: 0/10` | 
>>**Countdown Track**|`circles,red: 0/4` |

### Skills
>[!travel] %%FAKE TITLE HERE%%
>>[!thing] %%FAKE TITLE HERE%%
>> ### Skills
>>| **Skill Name** | **Skill Level** | **Skill Name** | **Skill Level** |
>>| :-----: | :-: |:------: | :-: |
>>|**Acrobatics**|`0`| **Sorcerous Lore** | `0` |
>>| **Acrobatics** | `0` | **Local Lore** | `0`|
>>|**Athletics** | `0` | **Medicine** | `0` |
>>| **Architecture**  | `0` | **Perform**  | `0` |
>>| **Awareness** | `0` |**Persuade** | `0` |
>>|**Beast Lore ** |`1` |**Ride** | `0`|
>>|**Bluff**|`0`| **Stealth** | `0` |
>>|**Bushcraft** | `0` | **Streetwise** | `0`|
>>|**Craft** | `0` | **Seamanship** | `0` |
>>|**Customs**  | `0` | **Spot Hidden**  | `0` |
>>|**Foraging** | `0` |**Swim** | `0` |
>>|**Hunt & Fish** |`1` |**Thievery** | `1`|
>>|**Insight**  | `0` | **Trade**  | `0` |
>>|**Languages** | `0` |**Witchery** | `0` |
>>|**Religious Lore** |`0` | **Background** |`=this.background` |
>>
>>&nbsp;
>>

### Abilities & Languages
>[!table_time] %%FAKE TITLE HERE%%
>>[!table_time] %%FAKE TITLE HERE%%
>>### Abilities & Languages
>> | | |
>>|:-:| --- |
>>| `=this.Ability1` | `=this.Ability2` |
>>| `=this.Ability3`| `=this.Ability4` |
>>| `=this.Ability5` | `=this.Ability6` |
>>| `=this.Ability7` | `=this.Ability8` |
>>

### Inventory
>[!table] %%FAKE TITLE HERE%%
>>[!table] %%FAKE TITLE HERE%%
>>#### Backpack
>>| Slot | Encumbering Items | Slot | Encumbering Items 
>>| :-: | ---------------- |:-:|--------|
>>|1|`INPUT[text:title1]` |11|`INPUT[text:title11]`|
>>|2|`INPUT[text:title2]`|12|`INPUT[text:title12]`|
>>|3|`INPUT[text:title3]`|13|`INPUT[text:title13]`|
>>|4|`INPUT[text:title4]`|14|`INPUT[text:title14]`|
>>|5|`INPUT[text:title5]`|15|`INPUT[text:title15]`|
>>|6|`INPUT[text:title6]`|16|`INPUT[text:title16]`|
>>|7|`INPUT[text:title7]`|17|`INPUT[text:title17]`|
>>|8|`INPUT[text:title8]`|18|`INPUT[text:title18]`|
>>|9|`INPUT[text:title9]`|19|`INPUT[text:title19]`|
>>|10|`INPUT[text:title10]`|20|`INPUT[text:title20]`|


>[!crafting] %%FAKE TITLE HERE%%
>>[!crafting] %%FAKE TITLE HERE%%
>> #### Free to Carry
>>| Slot | Item |  Slot | Item |
>>| :-: | :---------------- |--------|--------|
>>|1|`INPUT[text:lightitem1]` |6|`INPUT[text:lightitem6]`|
>>|2|`INPUT[text:lightitem2]`|7|`INPUT[text:lightitem7]`|
>>|3|`INPUT[text:lightitem3]`|8|`INPUT[text:lightitem8]`|
>>|4|`INPUT[text:lightitem4]`|9|`INPUT[text:lightitem9]`|
>>|5|`INPUT[text:lightitem5]`|10|`INPUT[text:lightitem10]`|
>>
>> &nbsp;
>>
>> #### Component Pouch & Sack
>>| Slot | Component Pouch | Slot| Sack
>>| :-: | ---------------- |:-: | ---------------- |
>>|1|`INPUT[text:Pouch1]` |1|`INPUT[text:Sack1]` | 
>>|2|`INPUT[text:Pouch2]` |2|`INPUT[text:Sack2]` | 
>>|3|`INPUT[text:Pouch3]` |3|`INPUT[text:Sack3]` | 
>>|4|`INPUT[text:Pouch4]` |4|`INPUT[text:Sack4]` | 
>>|5|`INPUT[text:Pouch5]` |5|`INPUT[text:Sack5]` |
>>|6|`INPUT[text:Pouch6]` |6|`INPUT[text:Sack6]` |

### Spells
>[!table_time] %%FAKE TITLE HERE%%
>>[!table_time] %%FAKE TITLE HERE%%
>>### Spells
>>| Slot | Spell |
>>| ---------- | -------- |
>>| 1 | `=this.Spell1` |
>>| 2 | `=this.Spell2` |
>>| 3 | `=this.Spell3` |
>>| 4 | `=this.Spell4` |
>>| 5 | `=this.Spell5` |
>>| 6 | `=this.Spell6` |
>>| 7 | `=this.Spell7`|
>>| 8 | `=this.Spell8`|
>>| 9 | `=this.Spell9`|
>>| 10 |`=this.Spell10`|



```meta-bind-button
label: Add
icon: ""
style: primary
class: ""
cssStyle: ""
backgroundImage: ""
tooltip: ""
id: exp
hidden: True
actions:
- type: updateMetadata
  bindTarget: xp
  evaluate: True
  value: getMetadata('xp') + getMetadata('axp')

```

```meta-bind-button
label: Add Jats
icon: ""
style: primary
class: ""
cssStyle: ""
backgroundImage: ""
tooltip: ""
id: pjats
hidden: True
actions:
- type: updateMetadata
  bindTarget: currency
  evaluate: True
  value: getMetadata('ajats') * '0.6' + getMetadata('currency')

```




