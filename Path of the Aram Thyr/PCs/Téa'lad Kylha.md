---
Art: "![[Téa'lad KylhaPro.webp|600]]"
STR: 16
INT: 17
WIS: 16
DEX: 14
CONST: 15
CHA: 9
xp: 95
spiritstage: 
SpiritStage: Wood
spiritdomain: Light
kingift: "Lifetap: You can tap into your Life Ara and sacrifice your own vitality to regain some Ara. For each 1 HP you spend you gain 2 Ara. This counts as an action."
healingrate: D8
MaxHP: 18
aramax: 20
typeaffinity: Caster
axp: 
spcoin: 3
bpcoin: 0
ipcoin: 0
proficiencyweapon1: Battle Axe
proficiencyarmor1: Hide Armor
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
title1: Hide Armor
title2: Battle Axe
title3: Backpack
title4: Torch Ud12
title5: Bandage Ud12
title6: Antidote x1
title26: ""
title7: Thieves' Tools
title27: ""
title8: Coins
title9: Rations x8
torch1: D12
Lampoil: None
SpiritPath: Path of Celestial Fury
Spell1Spirit: Wood
---
>[!dice] %%FAKE TITLE HERE%%
>> [!dice] %%FAKE TITLE HERE%%
>> # `=this.file.name`
>> `=this.Art`
>> ###### Attributes 
>>|     |     |
>> |------ | :---: |
>>|**Spirit Stage**|  `INPUT[inlineSelect(option(Wood), option(Bronze), option(Iron), option(Silver), option(Gold), option(Platinum), option(Diamond)):SpiritStage]`   |
>>| **Path** |  `INPUT[inlineSelect(option(Path of Celestial Fury), option(Path of Endless Blade), option(Path of the Everlasting Shadows), option(Path of Flaming Truth), option(Path of the Thousand Mirrors), option(Path of Invincible Blood), option(Path of the Rolling Boulder), option(Path of the Rushing Water), option(Path of Seething Fangs), option(Path of the Slicing Wind)):SpiritPath]`   |
>>| **Domain** |  `INPUT[inlineSelect(option(Light), option(Blades), option(Darkness), option(Fire), option(Dream), option(Blood), option(Earth), option(Water), option(Poison), option(Wind)):spiritdomain]`   |
>> |**Reputation**| `30` |
>>|**HP** | **Current:** `20` **Max:** `=this.MaxHP`|
>> |**Ara Pool** | **Current:** `20`  **Max:** `=this.aramax`   |
>>| **Kin Gift** |  `=this.kingift`   |
>>
>>&nbsp;
>>
>> ###### Stats
>>|     |     |
>> |--- | --- |
>> |**Initiative** | +`=floor((this.DEX - 10)/3)` |
>> |**Healing Rate**| `=this.healingrate` |
>> |**Passive Perception**| `=10+(floor((this.WIS - 10)/2.5))` |
>> |**Tenacity**| `=(this.WIS)+10` |
>> |**Technique Type Affinity**| `=this.typeaffinity` |
>> |**XP** | `VIEW[{xp}][text]`|
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
>>  | ||
>>---|---|---|
>>**Silver Pieces (sp)**|`=this.spcoin` |
>>**Bronze Pieces (bp)**|`=this.bpcoin` | **=** `=floor((this.bpcoin)/10)` ***sp***
>>**Iron Pieces (ip)**|`=this.ipcoin` |**=** `=floor((this.ipcoin)/10)` ***bp***
>>**Rations**|`7` |
>>**Torches**| `INPUT[inlineSelect(option(D12), option(D10), option(D8), option(D6), option(D4), option(None)):torch1]` |
>>**Lamp Oil**|`INPUT[inlineSelect(option(D12), option(D10), option(D8), option(D6), option(D4), option(None)):Lampoil]` |

>[!thing] %%FAKE TITLE HERE%%
>>[!thing] %%FAKE TITLE HERE%%
>> ### Abilities 
>>| Stat | Sore | Mod |Save|
>>| :---: | :---: | :---: | :---: |
>>| **Strength** | `=this.STR` | +`=floor((this.STR - 10)/2.5)`| `=floor((this.STR - 10)/2.5)`|
>>| **Intelligence** | `=this.INT` | +`=floor((this.INT - 10)/2.5)`| `=floor((this.INT - 10)/2.5)`|
>>| **Wisdom** | `=this.WIS` | +`=floor((this.WIS - 10)/2.5)`|`=floor((this.WIS - 10)/2.5)`|
>>| **Dexterity** | `=this.DEX` | +`=floor((this.DEX - 10)/2.5)`|`=floor((this.DEX - 10)/2.5)`|
>>| **Constitution** | `=this.CONST` |+`=floor((this.CONST - 10)/2.5)`| `=floor((this.CONST - 10)/2.5)`|
>>| **Charisma** | `=this.CHA` | +`=floor((this.CHA - 10)/2.5)`| `=floor((this.CHA - 10)/2.5)`|
>>| **Max Gear Slots** | *`=(this.STR)+10`* | ||
>>---
>>&nbsp;
>> ### Skill Checks
>>| **Skill Name** | **Skill Level** | **Skill Name** | **Skill Level** |
>>| :-----: | :-: |:------: | :-: |
>>|**Acrobatics** (DEX +`=floor((this.DEX - 10)/2.5)`)|`1`| **Nature** (INT +`=floor((this.INT - 10)/2.5)`) | `2` |
>>| **Animal Handling** (WIS +`=floor((this.WIS - 10)/2.5)`) | `2` | **Perception** (WIS +`=floor((this.WIS - 10)/2.5)`) | `3`|
>>|**Athletics** (STR +`=floor((this.STR - 10)/2.5)`)| `2` | **Performance** (CHA +`=floor((this.CHA - 10)/2.5)`) | `-1` |
>>| **Culture** (INT +`=floor((this.INT - 10)/2.5)`) | `2` | **Sacred Scripture** (INT +`=floor((this.INT - 10)/2.5)`) | `2` |
>>| **Deception** (CHA +`=floor((this.CHA - 10)/2.5)`) | `-1` |**Sleight of Hand** (DEX +`=floor((this.DEX - 10)/2.5)`) | `2` |
>>|**Insight** (WIS +`=floor((this.WIS - 10)/2.5)`)|`2` |**Spiritual Lore** (WIS +`=floor((this.WIS - 10)/2.5)`)| `2`|
>>| **Investigation** (INT +`=floor((this.INT - 10)/2.5)`) | `2` | **Stealth** (DEX +`=floor((this.DEX - 10)/2.5)`)|`1`|
>>|**Manipulation** (CHA +`=floor((this.CHA - 10)/2.5)`)| `-1` | **Survival** (WIS +`=floor((this.WIS - 10)/2.5)`) | `2` |
>>| **Medicine** (WIS +`=floor((this.WIS - 10)/2.5)`) | `2` | **Weshan Control** (INT +`=floor((this.INT - 10)/2.5)`) | `4` |
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


>[!crafting] %%FAKE TITLE HERE%%
>>[!npc] %%FAKE TITLE HERE%%
>>### Path Stance
>>
>>&nbsp
>>
>>| | | | |
>>|:-:|:----------:|
>>| <font color="#00b0f0">**Stance**</font> | `=this.Stance` |  
>>| <font color="#00b0f0">**Description**</font> |  `=this.Stanceskill`  | 
>>
>>&nbsp
>>
>>### Known Weshan
>>
>>&nbsp
>>
>>| | | | |
>>|:-:|:----------:|:-----:|:---------------------:|
>>| <font color="#00b0f0">**Weshan Name**</font> | `=this.Spell1` | <font color="#00b0f0">**Cost**</font> | `=this.Spell1cost` |
>>| <font color="#00b0f0">**Range**</font> |  `=this.Spell1range`  | <font color="#00b0f0">**Execution Time**</font> |`=this.Spell1time` |
>>| <font color="#00b0f0">**Domain Affinities:**</font> |  `=this.Spell1AFF`  | <font color="#00b0f0">**Spirit Stage**</font> |`INPUT[inlineSelect(option(Wood), option(Bronze), option(Iron), option(Silver), option(Gold), option(Platinum), option(Diamond)):Spell1Spirit]`|
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
>>| <font color="#00b0f0">**Weshan Name**</font> | `=this.Spell2` | <font color="#00b0f0">**Cost**</font> | `=this.Spell2cost` |
>>| <font color="#00b0f0">**Range**</font> |  `=this.Spell2range`  | <font color="#00b0f0">**Execution Time**</font> |`=this.Spell2time` |
>>| <font color="#00b0f0">**Domain Affinities:**</font> |  `=this.Spell2AFF`  | <font color="#00b0f0">**Spirit Stage**</font> |`INPUT[inlineSelect(option(Wood), option(Bronze), option(Iron), option(Silver), option(Gold), option(Platinum), option(Diamond)):Spell2Spirit]`|
>>
>>&nbsp;
>> 
>>
>>`=this.Spell2descript`
>>
>>
>>&nbsp
>>
>>---
>>---
>>
>>&nbsp
>>
>>| | | | |
>>|:-:|:----------:|:-----:|:---------------------:|
>>| <font color="#00b0f0">**Weshan Name**</font> | `=this.Spell3` | <font color="#00b0f0">**Cost**</font> | `=this.Spell3cost` |
>>| <font color="#00b0f0">**Range**</font> |  `=this.Spell3range`  | <font color="#00b0f0">**Execution Time**</font> |`=this.Spell3time` |
>>| <font color="#00b0f0">**Domain Affinities:**</font> |  `=this.Spell3AFF`  | <font color="#00b0f0">**Spirit Stage**</font> |`INPUT[inlineSelect(option(Wood), option(Bronze), option(Iron), option(Silver), option(Gold), option(Platinum), option(Diamond)):Spell3Spirit]`|
>>
>>&nbsp;
>> 
>>
>>`=this.Spell3descript`
>>
>>
>>&nbsp
>>
>>---

>[!success] %%FAKE TITLE HERE%%
>>[!travel] %%FAKE TITLE HERE%%
>>#### Anlach
>>
>>&nbsp
>>
>>| | | | |
>>|:-:|:----------:|:-----:|:---------------------:|
>>| **Anlach Name** | `=this.Anlach1` | | |
>>| **Spirit Essence** |  `=this.Anlach1essence`  | **Uses** |`=this.Anlach1uses` |
>>| **Reactivation Cost** |  `=this.Anlach1Cost`  | **DC** |`=this.Anlach1DC` |
>>
>>&nbsp;
>> 
>>
>>`=this.Anlach1descript`
>>
>>&nbsp
>>
>>---
>>
>>&nbsp
>>
>>| | | | |
>>|:-:|:----------:|:-----:|:---------------------:|
>>| **Anlach Name** | `=this.Anlach2` | | |
>>| **Spirit Essence** |  `=this.Anlach2essence`  | **Uses** |`=this.Anlach2uses` |
>>| **Reactivation Cost** |  `=this.Anlach2Cost`  | **DC** |`=this.Anlach2DC` |
>>
>>&nbsp;
>> 
>>
>>`=this.Anlach2descript`
>>
>>&nbsp
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







