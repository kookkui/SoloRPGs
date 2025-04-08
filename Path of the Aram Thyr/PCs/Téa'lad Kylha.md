---
Art: "![[Téa'lad KylhaPro.webp|600]]"
STR: 16
INT: 18
WIS: 16
DEX: 15
CONST: 15
CHA: 9
xp: 100
spiritstage: 
SpiritStage: Wood
spiritdomain: Light
kingift: "**Lifetap:** You can tap into your Life Ara and sacrifice your own vitality to regain some Ara. For each 1 HP you spend you gain 2 Ara. This counts as an action."
healingrate: D8
MaxHP: 18
aramax: 21
typeaffinity: Caster
axp: 
spcoin: 153
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
Spell2: Luminous Surge ↯
Spell2cost: 8 Ara
Spell2range: "Range: 10 feet cone"
Spell2time: 
Spell2descript: Pure Light Ara erupts from  the character’s hands, dealing D8 damage to all creatures in the area.
Spell2AFF: All
Anlach1: Snare
Anlach1essence: 1 Water, Earth or Dream
Anlach1uses: "1"
Anlach1Cost: 10 Ara
Anlach1DC: "12"
Anlach1descript: When a creature moves within 5 feet of the anlach, the snare triggers. The creature must succeed on a DEX saving throw or be pulled into the snare. The creature is restrained for 1 minute. A restrained creature can repeat the saving throw at the beginning of each of its turns, escaping the snare on a success. This anlach alerts its creator with a ping in their mind when the trap is triggered, if they are within 1 mile of the snare.
title1: "Weshan Scroll (Forger: Speed Burst)"
title2: Bandages x7
title3: Explosive Beads Ud4 (6d6)(TN 14)
title4: Antidote x1
title5: Thieves' Tools
title6: Coins
title26: ""
title7: Rations x6
title27: ""
title8: Small ivory statuette worth 300 sp
title9: Pendant worth 500 sp
torch1: D8
Lampoil: None
SpiritPath: Path of Celestial Fury
Spell1Spirit: Wood
ac: "14"
hp: 18
level: 1
modifier: 2
Spell1techtype: Caster
Spell2techtype: Caster
Spell2Spirit: Wood
lightitem1: Backpack
title10: "Enhancement Belt: +1 DEX"
title11: ""
lightitem2: Anlach - Domain Ward (2 Dark)
lightitem3: Anlach - Weaken (2 Blood)
lightitem4: Anlach - Confuse (2 Dream)
lightitem5: Anlach - Empower (3 Blade)
lightitem6: ""
lightitem11: ""
Tasktimer: D8
Other: "Enhancement Belt: +1 DEX"
---
>[!dice] %%FAKE TITLE HERE%%
>> [!dice] %%FAKE TITLE HERE%%
>> # `=this.file.name`
>> `=this.Art`
>> ###### Attributes 
>>|     |     |
>> |:---: | :---: |
>>|**Spirit Stage**|  `INPUT[inlineSelect(option(Wood), option(Bronze), option(Iron), option(Silver), option(Gold), option(Platinum), option(Diamond)):SpiritStage]`   |
>>| **Path** |  `INPUT[inlineSelect(option(Path of Celestial Fury), option(Path of Endless Blade), option(Path of the Everlasting Shadows), option(Path of Flaming Truth), option(Path of the Thousand Mirrors), option(Path of Invincible Blood), option(Path of the Rolling Boulder), option(Path of the Rushing Water), option(Path of Seething Fangs), option(Path of the Slicing Wind)):SpiritPath]`   |
>>| **Domain** |  `INPUT[inlineSelect(option(Light), option(Blades), option(Darkness), option(Fire), option(Dream), option(Blood), option(Earth), option(Water), option(Poison), option(Wind)):spiritdomain]`   |
>> |**Reputation**| `31` |
>>|**HP** | **Current:** `18` **Max:** `=this.MaxHP`|
>> |**Ara Pool** | **Current:** `17`  **Max:** `=this.aramax`   |
>>
>>&nbsp;
>>
>> ###### Stats
>>|     |     |
>> |--- | :---: |
>> |**Initiative** | +`=floor((this.DEX - 10)/3)` |
>> |**Healing Rate**| `=this.healingrate` |
>> |**Passive Perception**| `=10+(floor((this.WIS - 10)/2.5))` |
>> |**Tenacity**| `=(this.WIS)+10` |
>> |**Technique Type Affinity (+1)**| `=this.typeaffinity` |
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
>>**Rations**|`10` |
>>**Torches / Lamp Oil**| `INPUT[inlineSelect(option(D12), option(D10), option(D8), option(D6), option(D4), option(None)):torch1]` |
>>**Task Timer**|`INPUT[inlineSelect(option(D10), option(D8), option(D6), option(None)):Tasktimer]` |
>>
>>
>>###### Notes
>>`INPUT[textArea:Other]`

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
>>
>>&nbsp;
>>
>> ### Skills
>>| **Skill Name** | **Skill Level** | **Skill Name** | **Skill Level** |
>>| :-----: | :-: |:------: | :-: |
>>|**Acrobatics** (DEX +`=floor((this.DEX - 10)/2.5)`)|`2`| **Nature** (INT +`=floor((this.INT - 10)/2.5)`) | `3` |
>>| **Animal Handling** (WIS +`=floor((this.WIS - 10)/2.5)`) | `2` | **Perception** (WIS +`=floor((this.WIS - 10)/2.5)`) | `2`|
>>|**Athletics** (STR +`=floor((this.STR - 10)/2.5)`)| `2` | **Performance** (CHA +`=floor((this.CHA - 10)/2.5)`) | `-1` |
>>| **Culture** (INT +`=floor((this.INT - 10)/2.5)`) | `3` | **Sacred Scripture** (INT +`=floor((this.INT - 10)/2.5)`) | `3` |
>>| **Deception** (CHA +`=floor((this.CHA - 10)/2.5)`) | `-1` |**Sleight of Hand** (DEX +`=floor((this.DEX - 10)/2.5)`) | `2` |
>>|**Insight** (WIS +`=floor((this.WIS - 10)/2.5)`)|`2` |**Spiritual Lore** (WIS +`=floor((this.WIS - 10)/2.5)`)| `2`|
>>| **Investigation** (INT +`=floor((this.INT - 10)/2.5)`) | `3` | **Stealth** (DEX +`=floor((this.DEX - 10)/2.5)`)|`2`|
>>|**Manipulation** (CHA +`=floor((this.CHA - 10)/2.5)`)| `-1` | **Survival** (WIS +`=floor((this.WIS - 10)/2.5)`) | `3` |
>>| **Medicine** (WIS +`=floor((this.WIS - 10)/2.5)`) | `2` | **Weshan Control** (INT +`=floor((this.INT - 10)/2.5)`) | `5` |
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
>>
>>&nbsp;
>>
>>| | |
>>|---| -- |
>>| **Kin Gift** |  `=this.kingift`   |

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
>>
>> &nbsp;
>>
>> ##### Spirit Essences
>>| **Air**   | **Blades** | **Blood** | **Darkness** | **Dream**  | 
>>| :-: | :-: | :-: | :-: | :-: | 
>>| `0`   | `1`  | `0`  | `0`   | `0`   | 
>>| **Earth** | **Fire** | **Light** | **Poison** | **Water** | 
>| `0`   | `0`  | `0`  | `0`   | `0`   | 


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
>>| <font color="#00b0f0">**Range**</font> |  `=this.Spell1range`  | <font color="#00b0f0">**Technique Type**</font> |`INPUT[inlineSelect(option(Caster), option(Dominator), option(Forger), option(Shaper)):Spell1techtype]` |
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
>>| <font color="#00b0f0">**Range**</font> |  `=this.Spell2range`  |  <font color="#00b0f0">**Technique Type**</font> |`INPUT[inlineSelect(option(Caster), option(Dominator), option(Forger), option(Shaper)):Spell2techtype]` |
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
>>| <font color="#00b0f0">**Range**</font> |  `=this.Spell3range`  |  <font color="#00b0f0">**Technique Type**</font> |`INPUT[inlineSelect(option(Caster), option(Dominator), option(Forger), option(Shaper)):Spell3techtype]` |
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







