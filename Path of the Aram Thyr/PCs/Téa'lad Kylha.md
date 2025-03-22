---
Art: "![[Hema.webp|600]]"
HP: 0
STR: 16
DEX: 18
CONST: 10
WIS: 11
INT: 13
CHA: 17
xp: 10
spiritstage: Wood
spiritpath: Path of Celestial Fury
spiritdomain: PH
aramax: 20
typeaffinity: Caster
axp: 
spcoin: 10
bpcoin: 30
ipcoin: 40
Weapon1: 
Weapon1dmg: 
Weapon1notes: 
Weapon2: 
Weapon2dmg: 
Weapon2notes: 
Weapon3: 
Weapon3dmg: 
Weapon3notes: 
Armor1: Padded Leather
Armor1DL: 12
Armor1notes: Light
Armor2: 
Armor2rate: 0
Armor2notes: 
Shield: 
Shieldrate: 
Shieldnotes: 
Spell1: Night Vision
Spell1cost: 10 Ara
Spell1range: Self
Spell1time: 1 Action
Spell1descript: The character can see in absolute darkness (natural or otherwise) as if in broad daylight for 1 hour.
Spell1AFF: Darkness, Light, Fire, Dream
Spell2: Freedom
Spell2cost: 10 Ara
Spell2range: Self
Spell2time: 1 Action
Spell2descript: The character frees themself from any effect that holds or slows them.
Spell2AFF: All
Anlach1: Domain Ward
Anlach1essence: Two of the desired Domain
Anlach1uses: Until destroyed
Anlach1Cost: 
Anlach1DC: "14"
Anlach1descript: When creating this anlach, the character chooses one Domain. The anlach must be placed at the threshold of any sort of entrance, and any creature of the chosen Domain must make a WIL saving throw in order to be able to cross through. The character can set a password for the anlach.
---
>[!dice] %%FAKE TITLE HERE%%
>> [!dice] %%FAKE TITLE HERE%%
>> # `=this.file.name`
>> `=this.Art`
>> ###### Attributes 
>>|     |     |
>> |--- | --- |
>>| **Spirit Stage** |  `=this.spiritstage`   |
>>| **Path** |  `=this.spiritpath`   |
>>| **Domain** |  `=this.spiritdomain`   |
>>|**HP** | **Current:** `30` **Max:** `=this.CONST*3`|
>> |**Ara Pool** | **Current:** `30`  **Max:** `=this.aramax`   |
>>
>>&nbsp;
>>
>> ###### Stats
>>|     |     |
>> |--- | --- |
>> |**Initiative** | +`=floor((this.DEX - 10)/3)` |
>> |**Healing Rate**| `=this.healingrate` |
>> |**Reputation**| `30` |
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
>>**Bronze Pieces (bp)**|`=this.bpcoin` | **bp:** `=floor((this.bpcoin)/10)` *sp*
>>**Iron Pieces (ip)**|`=this.ipcoin` |**ip:** `=floor((this.ipcoin)/10)` *bp*
>>**Rations**|`0` |
>>**Torches**|`0` |
>>**Lamp Oil**|`0` |

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
>>| **Max Gear Slots** | `=(this.STR)+10` | ||
>>---
>>&nbsp;
>> ### Skill Checks
>>| **Skill Name** | **Skill Level** | **Skill Name** | **Skill Level** |
>>| :-----: | :-: |:------: | :-: |
>>|**Acrobatics** (DEX +`=floor((this.DEX - 10)/2.5)`)|`0`| **Nature** (INT +`=floor((this.INT - 10)/2.5)`) | `0` |
>>| **Animal Handling** (WIS +`=floor((this.WIS - 10)/2.5)`) | `0` | **Perception** (WIS +`=floor((this.WIS - 10)/2.5)`) | `0`|
>>|**Athletics** (STR +`=floor((this.STR - 10)/2.5)`)| `0` | **Performance** (CHA +`=floor((this.CHA - 10)/2.5)`) | `0` |
>>| **Culture** (INT +`=floor((this.INT - 10)/2.5)`) | `0` | **Sacred Scripture** (INT +`=floor((this.INT - 10)/2.5)`) | `0` |
>>| **Deception** (CHA +`=floor((this.CHA - 10)/2.5)`) | `0` |**Sleight of Hand** (DEX +`=floor((this.DEX - 10)/2.5)`) | `0` |
>>|**Insight** (WIS +`=floor((this.WIS - 10)/2.5)`)|`0` |**Spiritual Lore** (WIS +`=floor((this.WIS - 10)/2.5)`)| `0`|
>>| **Investigation** (INT +`=floor((this.INT - 10)/2.5)`) | `0` | **Stealth** (DEX +`=floor((this.DEX - 10)/2.5)`)|`0`|
>>|**Manipulation** (CHA +`=floor((this.CHA - 10)/2.5)`)| `0` | **Survival** (WIS +`=floor((this.WIS - 10)/2.5)`) | `0` |
>>| **Medicine** (WIS +`=floor((this.WIS - 10)/2.5)`) | `0` | **Weshan Control** (INT +`=floor((this.INT - 10)/2.5)`) | `0` |
>
>>[!travel] %%FAKE TITLE HERE%%
>>##### Proficiencies
>> | | |
>>|:-:| :---: |
>>| `=this.proficiency1` | `=this.proficiency2` |
>>| `=this.proficiency3` | `=this.proficiency4` |
>>| `=this.proficiency5` | `=this.proficiency6` |
>>| `=this.proficiency7` | `=this.proficiency8` |
>>| `=this.proficiency9` | `=this.proficiency10` |
>>| `=this.proficiency11` | `=this.proficiency12` |

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
>>### Known Weshan
>>
>>&nbsp
>>
>>| | | | |
>>|:-:|:----------:|:-----:|:---------------------:|
>>| **Weshan Name** | `=this.Spell1` | **Cost** | `=this.Spell1cost` |
>>| **Range** |  `=this.Spell1range`  | **Execution Time** |`=this.Spell1time` |
>>
>>&nbsp;
>> 
>>
>>`=this.Spell1descript`
>>
>>&nbsp;
>>**Domain Affinities:** `=this.Spell1AFF`
>>
>>&nbsp
>>
>>---
>>
>>&nbsp
>>
>>| | | | |
>>|:-:|:----------:|:-----:|:---------------------:|
>>| **Weshan Name** | `=this.Spell2` | **Cost** | `=this.Spell2cost` |
>>| **Range** |  `=this.Spell2range`  | **Execution Time** |`=this.Spell2time` |
>>
>>&nbsp;
>> 
>>
>>`=this.Spell2descript`
>>
>>&nbsp;
>>**Domain Affinities:** `=this.Spell2AFF`
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







