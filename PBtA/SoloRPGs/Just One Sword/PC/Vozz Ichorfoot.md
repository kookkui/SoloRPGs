---
Art: "![[CutieGoblinNerd.webp|center]]"
Level: 3
STR: 16
INT: 14
WIS: 14
DEX: 16
CON: 15
CHA: 11
BodySav: "`=floor((this.STR - 10)/3) + floor((this.CON - 10)/3)`"
MindSav: "`=floor((this.INT - 10)/3) + floor((this.CHA - 10)/3)`"
ReflexSav: "`=floor((this.DEX - 10)/3) + floor((this.WIS - 10)/3)`"
AtkBonus: 1
SavBonus: 2
xp: 9
LevelXP: "`=(this.Level*10)`"
MaxHP: 18
Fatigue: "`=this.CON`"
axp: 
background: Beast Hunter
currency: 98
Weapon1: Silver Bastard Sword
Weapon1dmg: D8
Weapon1notes: Slashing
Weapon2: Hunting Bow
Weapon2dmg: D8
Weapon2notes: Piercing, Range 240'(D)
Armor1: Chain Mail
Armor1Bod: 2
Armor1Ref: -1
Armor1notes: -1 Sneak
Armor2: Shield
Armor2Bod: 1
Armor2Ref: 
Armor2notes: 
torch1: D8
Lampoil: D20
CurrentFatigue: 0
CurrentHP: 18
Ability1: "[[Witchcraft]]"
Spell1: "[[SoloRPGs/Just One Sword/Spells & Sorcery/Scorn the Mind.md|Scorn the Mind]]"
Spell2: "[[SoloRPGs/Just One Sword/Spells & Sorcery/Dull the Mind.md|Dull the Mind]]"
Spell3: "[[SoloRPGs/Just One Sword/Spells & Sorcery/Disperse the Sickness.md|Disperse the Sickness]]"
title1: Lantern
title2: Bandages x3
title3: Tent (Roll to MAKE CAMP with Advantage. Recover 2 Fatigue on a Full Success)
title4: Thieves Tools, Complex
title5: Travel Rations
title6: "Travel Rations "
title7: Arrows
title8: Silver Coins
title9: Arrows
title10: Repair Kit x 3
title11: Lantern Oil x 2
title12: Spyglass (Advantage on +WIS checks)
lightitem1: Arm band of Giant Strength (+1 Attribute Bonus to Strength)
Language1: Diabolic
asilver: 
lightitem2: ""
lightitem6: ""
lightitem7: ""
title13: ""
Pouch1: Harehune x 2
Pouch2: Harehune x 2
Pouch3: Banwyrt x 2
Pouch4: Banwyrt x 2
---
>[!dice] %%FAKE TITLE HERE%%
>> [!dice] %%FAKE TITLE HERE%%
>> ## `=this.file.name`
>> `=this.Art`
>>```meta-bind
>>INPUT[progressBar(class(green-progress-bar), maxValue(18), title(HP)):CurrentHP]
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
>> | **Background** |`=this.background` |
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
>>| **Weapons** | **Damage** | **Mod**| **Quality** | **Notes** |
>>| --------- | :-: | :-: |:-:|-----|
>>| `=this.Weapon1` | `=this.Weapon1dmg` |+`=floor((this.STR - 10)/3) + this.AtkBonus`| `3` |`=this.Weapon1notes` |
>>| `=this.Weapon2` | `=this.Weapon2dmg` |+`=floor((this.DEX - 10)/3) + this.AtkBonus`|`3`| `=this.Weapon2notes` |
>>
>>
>>&nbsp;
>>
>> ##### Armor
>>| **Armor** | **Body** | **Reflex** |**Quality** | **Notes**|
>>| ----------- | :---: | :---: | ------ |------ |
>>| `=this.Armor1` | `=this.Armor1Bod`|`=this.Armor1Ref` |`3` | `=this.Armor1notes` |
>>| `=this.Armor2` |  `=this.Armor2Bod`|`=this.Armor2Ref` |`3`| `=this.Armor2notes` |
>>
>>
>>&nbsp;
>>
>> ##### Supplies
>>  | |
>>---|---|
>>**Silver Pieces (sp)**|`=this.currency` |
>>**Gold Pieces (gp)**|`0` |
>>**Bronze Pieces (bp)**|`0` | 
>>**Arrows**|`46` |
>>**Rations**|`6` |
>>**Torches**| `INPUT[inlineSelect(option(D8), option(D6), option(D4), option(None)):torch1]` |
>>**Lamp Oil**|`INPUT[inlineSelect(option(D20), option(D12), option(D10), option(D8), option(D6), option(D4), option(None)):Lampoil]` |
>>**ADD SP**| `INPUT[number:asilver]` `BUTTON[psilver]`|


### Timers & Counters
>[!crafting] %%FAKE TITLE HERE%%
>> [!crafting] %%FAKE TITLE HERE%%
>> ##### Timers & Counters
>>  | |
>>---|---|
>>**Watches**| `clock,yellow: 1/4` |
>>**Encounter Penalties**|**`2`**|
>>**Goal Timer**|`0`|
>>**Progress Track**|`circles,green: 0/10` | 
>>**Countdown Track**|`circles,red: 0/4` |

### Skills
>[!travel] %%FAKE TITLE HERE%%
>>[!thing] %%FAKE TITLE HERE%%
>> ### Skills
>>| **Skill Name** | **Skill Level** | **Skill Name** | **Skill Level** |
>>| ----- | :-: |------ | :-: |
>>| [[Acrobatics]] | `0` | [[Sorcerous Lore]] | `0` |
>>|[[Athletics]] | `0` | [[Local Lore]] | `0`|
>>| [[Architecture]]  | `0` | [[Medicine]] | `1` |
>>| [[Awareness]] | `0` |[[Perform]]  | `0` |
>>|[[Beast Lore]]  |`0` |[[Persuade]] | `0` |
>>|[[Bluff]]|`0`| [[Ride]] | `0`|
>>|[[Bushcraft]] | `1` |[[Stealth]] | `0` |
>>|[[Craft]] | `0` |  [[Streetwise]] | `0`|
>>|[[Customs]]  | `0` | [[Seamanship]] | `0` |
>>|[[Foraging]] | `0` |[[Spot Hidden]]  | `1` |
>>|[[Hunt & Fish]] |`1` |[[Swim]] | `0` |
>>|[[Insight]]  | `0` |[[Thievery]] | `1`|
>>|[[Languages]] | `0` | [[Trade]]  | `0` |
>>|[[Leadership]] |`0` |[[Witchery]] | `0` |
>>|[[Religious Lore]] |`0`| |  |
>>
>>&nbsp;
>>

### Abilities & Languages
>[!table_time] %%FAKE TITLE HERE%%
>>[!table_time] %%FAKE TITLE HERE%%
>>### Abilities
>> | | |
>>|:-:| --- |
>>| `INPUT[suggester(optionQuery(#Category/Ability)):Ability1]` | `INPUT[suggester(optionQuery(#Category/Ability)):Ability2]` |
>>| `INPUT[suggester(optionQuery(#Category/Ability)):Ability3]`| `INPUT[suggester(optionQuery(#Category/Ability)):Ability4]` |
>>
>> &nbsp;
>>
>>### Languages
>> | | |
>>|:-:| --- |
>>| `INPUT[inlineSelect(option(Ancient),option(Beast), option(Diabolic), option(Draconic), option(Giant), option(Nathric), option(None)):Language1]` | `INPUT[inlineSelect(option(Ancient),option(Beast), option(Diabolic), option(Draconic), option(Giant), option(Nathric), option(None)):Language2]` |
>>| `INPUT[inlineSelect(option(Ancient),option(Beast), option(Diabolic), option(Draconic), option(Giant), option(Nathric), option(None)):Language3]`| `INPUT[inlineSelect(option(Ancient),option(Beast), option(Diabolic), option(Draconic), option(Giant), option(Nathric), option(None)):Language4]` |


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
>>| 1 | `INPUT[suggester(optionQuery(#Category/Spell)):Spell1]` |
>>| 2 | `INPUT[suggester(optionQuery(#Category/Spell)):Spell2]` |
>>| 3 | `INPUT[suggester(optionQuery(#Category/Spell)):Spell3]` |
>>| 4 | `INPUT[suggester(optionQuery(#Category/Spell)):Spell4]` |
>>| 5 | `INPUT[suggester(optionQuery(#Category/Spell)):Spell5]` |
>>| 6 | `INPUT[suggester(optionQuery(#Category/Spell)):Spell6]` |
>>| 7 | `INPUT[suggester(optionQuery(#Category/Spell)):Spell7]`|
>>| 8 | `INPUT[suggester(optionQuery(#Category/Spell)):Spell8]`|
>>| 9 | `INPUT[suggester(optionQuery(#Category/Spell)):Spell9]`|
>>| 10 |`INPUT[suggester(optionQuery(#Category/Spell)):Spell10]`|


