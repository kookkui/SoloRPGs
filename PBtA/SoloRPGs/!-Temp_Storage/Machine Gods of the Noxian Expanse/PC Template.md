---
Art: "![[MachineGods_Pink.webp]]"
STR: 16
CONST: 15
DEX: 16
INT: 17
WIL: 16
PRE: 9
xp: 95
Level: 1
aramax: 20
axp: 
coins: 0
skill1: Athlete
skill1desc: You have +2 Mastery on all checks involving athleticism (swimming, running, retc.).
skill2: 
skill2desc: 
skill3: 
skill3desc: 
skill4: 
skill4desc: 
skill5: Poison Resistance
skill5desc: Gain +2 Mastery on checks against poison.
feat1: 
feat1desc: 
feat2: 
feat2desc: 
Weapon1: Battle Axe
Weapon1dmg: (D8+3)+2
Weapon1notes: Slashing, Versatile (D10)
Weapon2: 
Weapon2dmg: 
Weapon2notes: 
Weapon3: 
Weapon3dmg: 
Weapon3notes: 
Armor1: Hide Armor
Armor1DL: 13
Armor1notes: Medium
Armor2: 
Armor2rate: 0
Armor2notes: 
Stance: Offensive (+1 Weshan Control)
Stanceskill: "The character receives +1 INT **Light Cascade: ** The character keeps cycling Light Ara through their body, permanently increasing their attack damage of any type by +1 per Spirit Stage."
Spell1: Sudden Dawn ↯
Spell1cost: 4 Ara
Spell1range: 30 feet
Spell1time: 1 Action
Spell1descript: A sudden burst of pure Light Ara blinds every character within range for 1 turn. Blinded characters have Disadvantage with all their actions.
Spell1AFF: Light
Spell2: 
Spell2cost: 
Spell2range: 
Spell2time: 
Spell2descript: 
Spell2AFF: 
Anlach1: 
Anlach1essence: 
Anlach1uses: 
Anlach1Cost: 
Anlach1DC: 
Anlach1descript: 
title1: ""
title2: ""
title3: ""
title4: ""
title5: ""
title6: ""
title26: ""
title7: ""
title27: ""
title8: ""
title9: ""
torch1: D12
Lampoil: None
SpiritPath: Path of Celestial Fury
Spell1Spirit: Wood
checkbox1: false
---
>[!dice] %%FAKE TITLE HERE%%
>> [!dice] %%FAKE TITLE HERE%%
>> # `=this.file.name`
>> `=this.Art`
>> ###### Attributes 
>>|     |     |
>> |------ | :---: |
>>|**Level**|  `=this.Level`   |
>>| **Development Points** | `0` |
>> |**Cultivating**| `0` |
>>|**HP** | **Current:** `20` **Max:** `=this.CONST*2`|
>>---
>>
>> ###### Stats
>>|     |     |
>> |--- | --- |
>> |**Initiative** | +`=floor((this.DEX - 10)/3)` |
>> |**Carrying Capacity**| `=this.STR` |
>> |**XP** | `VIEW[{xp}][text]`|
>>|**XP Needed** | `=100+(this.level*2)`
>>|**ADD XP**| `INPUT[number:axp]` `BUTTON[exp]`|
>>
>>&nbsp;
>>
>> ###### Weapons
>>| **Weapons** | **Damage** | **Notes** |
>>| ---------------------- | --------------- | ------------- |
>>| `=this.Weapon1` | `=this.Weapon1dmg` | `=this.Weapon1notes` |
>>| `=this.Weapon2` | `=this.Weapon2dmg` | `=this.Weapon2notes` |
>>| `=this.Weapon3` | `=this.Weapon3dmg` | `=this.Weapon3notes` |
>>| | | |
>>| | | |
>>
>>&nbsp;
>>
>>###### Combo Abilities
>> |**Name**| **Description**|
>>|:-:| :---: |
>>| `=this.combo1` | `=this.combo1desc` |
>>| `=this.combo2` | `=this.combo2desc` |
>>| `=this.combo3` | `=this.combo3desc` |
>>| `=this.combo4` | `=this.combo4desc` |
>>| `=this.combo5` | `=this.combo5desc` |
>>| | |
>>
>>&nbsp;
>>
>> ###### Armor
>>| **Armor** | **Defense Level** | **Notes** |
>>| ---------------------- | --------------- | ------------- |
>>| `=this.Armor1` | `=this.Armor1DL` | `=this.Armor1notes` |
>>| `=this.Armor2` | `=this.Armor2DL` | `=this.Armor2notes` |
>>| **Total DL**|`=(this.Armor1DL)+(floor((this.DEX - 10)/2.5))`||
>>
>>&nbsp;
>>
>> ###### Supplies
>>  | | |
>>---|---|---|
>>**Coins (₵)**|`=this.coins` ||
>>**Rations**|`7` ||
>>**Torches**| `INPUT[inlineSelect(option(D12), option(D10), option(D8), option(D6), option(D4), option(None)):torch1]` ||
>>**Lamp Oil**|`INPUT[inlineSelect(option(D12), option(D10), option(D8), option(D6), option(D4), option(None)):Lampoil]` ||

>[!thing] %%FAKE TITLE HERE%%
>>[!thing] %%FAKE TITLE HERE%%
>> ### Abilities 
>>| Stat | Sore | Mod |Save|
>>| :---: | :---: | :---: | :---: |
>>| **Strength** | `=this.STR` | +`=floor((this.STR - 10)/2.5)`| `=floor((this.STR - 10)/2.5)`|
>>| **Constitution** | `=this.CONST` |+`=floor((this.CONST - 10)/2.5)`| `=floor((this.CONST - 10)/2.5)`|
>>| **Dexterity** | `=this.DEX` | +`=floor((this.DEX - 10)/2.5)`|`=floor((this.DEX - 10)/2.5)`|
>>| **Intelligence** | `=this.INT` | +`=floor((this.INT - 10)/2.5)`| `=floor((this.INT - 10)/2.5)`|
>>| **Willpower** | `=this.WIL` | +`=floor((this.WIL - 10)/2.5)`|`=floor((this.WIL - 10)/2.5)`|
>>| **Presence** | `=this.PRE` | +`=floor((this.PRE - 10)/2.5)`| `=floor((this.PRE - 10)/2.5)`|
>>---
>
>>[!travel] %%FAKE TITLE HERE%%
>>##### Skills
>> |**Name**| **Description**|
>>|:-:| :---: |
>>| `=this.skill1` | `=this.skill1desc` |
>>| `=this.skill2` | `=this.skill2desc` |
>>| `=this.skill3` | `=this.skill3desc` |
>>| `=this.skill4` | `=this.skill4desc` |
>>| `=this.skill5` | `=this.skill5desc` |
>>---
>
>>[!travel] %%FAKE TITLE HERE%%
>>##### Feats
>> |**Name**| **Description**|
>>|:-:| :---: |
>>| `=this.feat1` | `=this.feat1desc` |
>>| `=this.feat2` | `=this.feat2desc` |
>>| `=this.feat3` | `=this.feat3desc` |
>>| `=this.feat4` | `=this.feat4desc` |
>>| `=this.feat5` | `=this.feat5desc` |
>>| `=this.feat6` | `=this.feat6desc` |
>>---
>
>>[!travel] %%FAKE TITLE HERE%%
>>##### Proficiencies
>> |**Weapons** |**Armor** |
>>|:-:| :---: |
>>| `=this.proficiencyweapon1` | `=this.proficiencyarmor1` |
>>| `=this.proficiencyweapon2` | `=this.proficiencyarmor2` |
>>| `=this.proficiencyweapon3` | `=this.proficiencyarmor3` |
>>| `=this.proficiencyweapon4` | `=this.proficiencyarmor4` |
>>| `=this.proficiencyweapon5` | `=this.proficiencyarmor5` |
>>| `=this.proficiencyweapon6` | `=this.proficiencyarmor6` |

>[!gather] %%FAKE TITLE HERE%%
>>[!table] %%FAKE TITLE HERE%%
>> ### Inventory
>>| Slot | Item |Slot | Item|
>>| :-: | :---------------- |--------|--------|
>>|1|`INPUT[text:title1]` |21|`INPUT[text:title21]`|
>>|2|`INPUT[text:title2]`|22|`INPUT[text:title22]`|
>>|3|`INPUT[text:title3]`|23|`INPUT[text:title23]`|
>>|4|`INPUT[text:title4]`|24|`INPUT[text:title24]`|
>>|5|`INPUT[text:title5]`|25|`INPUT[text:title25]`|
>>|6|`INPUT[text:title6]`|26|`INPUT[text:title26]`|
>>|7|`INPUT[text:title7]`|27|`INPUT[text:title27]`|
>>|8|`INPUT[text:title8]`|28|`INPUT[text:title28]`|
>>|9|`INPUT[text:title9]`|29|`INPUT[text:title29]`|
>>|10|`INPUT[text:title10]`|30|`INPUT[text:title30]`|
>>|11|`INPUT[text:title11]`|31|`INPUT[text:title31]`|
>>|12|`INPUT[text:title12]`|32|`INPUT[text:title32]`|
>>|13|`INPUT[text:title13]`|33|`INPUT[text:title33]`|
>>|14|`INPUT[text:title14]`|34|`INPUT[text:title34]`|
>>|15|`INPUT[text:title15]`|35|`INPUT[text:title35]`|
>>|16|`INPUT[text:title16]`|36|`INPUT[text:title36]`|
>>|17|`INPUT[text:title17]`|37|`INPUT[text:title37]`|
>>|18|`INPUT[text:title18]`|38|`INPUT[text:title38]`|
>>|19|`INPUT[text:title19]`|39|`INPUT[text:title39]`|
>>|20|`INPUT[text:title20]`|40|`INPUT[text:title40]`|
>>
>>&nbsp;
>>
>>|||
>>|:-:| :---: |
>> |**Backpack +10 Item Slots** |`INPUT[toggle:checkbox1]` |
>>|**Backpack +10 Item Slots**| `INPUT[toggle:checkbox2]` |
>
>>[!dice] %%FAKE TITLE HERE%%
>> ### Non-Encumbering Items
>>| Slot | Item |  Slot | Item |
>>| :-: | :---------------- |--------|--------|
>>|1|`INPUT[text:lightitem1]` |11|`INPUT[text:lightitem11]`|
>>|2|`INPUT[text:lightitem2]`|12|`INPUT[text:lightitem12]`|
>>|3|`INPUT[text:lightitem3]`|13|`INPUT[text:lightitem13]`|
>>|4|`INPUT[text:lightitem4]`|14|`INPUT[text:lightitem14]`|
>>|5|`INPUT[text:lightitem5]`|15|`INPUT[text:lightitem15]`|
>>|6|`INPUT[text:lightitem6]`|16|`INPUT[text:lightitem16]`|
>>|7|`INPUT[text:lightitem7]`|17|`INPUT[text:lightitem17]`|
>>|8|`INPUT[text:lightitem8]`|18|`INPUT[text:lightitem18]`|
>>|9|`INPUT[text:lightitem9]`|19|`INPUT[text:lightitem19]`|
>>|10|`INPUT[text:lightitem10]`|20|`INPUT[text:lightitem20]`|


>[!hint] %%FAKE TITLE HERE%%
>>[!travel] %%FAKE TITLE HERE%%
>>### Resonance Cores
>> |<font color="#00CCFF">**Current UD**</font> |<font color="#00CCFF">**Max UD**</font> |
>>|:-:| :---: |
>>| `INPUT[inlineSelect(option(D12), option(D10), option(D8), option(D6), option(D4), option(None)):Core1Current]` | `INPUT[inlineSelect(option(D12), option(D10), option(D8), option(D6), option(D4), option(None)):Core2Max]` |
>>| `INPUT[inlineSelect(option(D12), option(D10), option(D8), option(D6), option(D4), option(None)):Core2Current]` | `INPUT[inlineSelect(option(D12), option(D10), option(D8), option(D6), option(D4), option(None)):Core2Max]` |
>>| `INPUT[inlineSelect(option(D12), option(D10), option(D8), option(D6), option(D4), option(None)):Core3Current]` | `INPUT[inlineSelect(option(D12), option(D10), option(D8), option(D6), option(D4), option(None)):Core3Max]` |
>>|||
>>
>>&nbsp;
>>
>>---
>>
>>### Spells
>>
>>&nbsp
>>
>>| | | | |
>>|:-:|:----------:|:-----:|:---------------------:|
>>| <font color="#00b0f0">**Spell**</font> | `=this.Spell1` | <font color="#00b0f0">**Relic**</font> | `=this.Spell1Relic` |
>>|<font color="#00b0f0">**Target Number**</font> |`=this.Spell1TN` | <font color="#00b0f0">**Range**</font> |  `=this.Spell1range`  | 
>>
>>&nbsp;
>> 
>>
>>`=this.Spell1descript`
>>
>>&nbsp;
>>
>>---
>>
>>&nbsp
>>
>>| | | | |
>>|:-:|:----------:|:-----:|:---------------------:|
>>| <font color="#00b0f0">**Spell**</font> | `=this.Spell2` | <font color="#00b0f0">**Relic**</font> | `=this.Spell2Relic` |
>>|<font color="#00b0f0">**Target Number**</font> |`=this.Spell2TN` | <font color="#00b0f0">**Range**</font> |  `=this.Spell2range`  | 
>>
>>&nbsp;
>> 
>>
>>`=this.Spell2descript`
>>
>>&nbsp;
>>
>>---
>>
>>&nbsp
>>
>>| | | | |
>>|:-:|:----------:|:-----:|:---------------------:|
>>| <font color="#00b0f0">**Spell**</font> | `=this.Spell2` | <font color="#00b0f0">**Relic**</font> | `=this.Spell2Relic` |
>>|<font color="#00b0f0">**Target Number**</font> |`=this.Spell2TN` | <font color="#00b0f0">**Range**</font> |  `=this.Spell2range`  | 
>>
>>&nbsp;
>> 
>>
>>`=this.Spell2descript`
>>
>>&nbsp;
>>
>>---

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







