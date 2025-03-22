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
Armor1: Light Armor
Armor1rate: 2
Armor1notes: Armor (2)
Armor2: 
Armor2rate: 0
Armor2notes: 
Shield: 
Shieldrate: 
Shieldnotes: 
merc: ".6"
provisions: 10
flaws: 
Head: 
passive0: 
passive1: 
passive2: 
---
>[!dice] %%FAKE TITLE HERE%%
>> [!dice] %%FAKE TITLE HERE%%
>> # `=this.file.name`
>> `=this.Art`
>> ###### Character Core
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
>>| **Armor** | **Armor Rating** | **Notes** |
>>| ---------------------- | --------------- | ------------- |
>>| `=this.Armor1` | `=this.Armor1rate` | `=this.Armor1notes` |
>>| `=this.Armor2` | `=this.Armor2rate` | `=this.Armor2notes` |
>>| **Total Armor**|`=(this.Armor1rate)+(this.Armor2rate)`||
>>|**Shield** | **Parry**| **Notes**|
>>|`=this.Shield`|`=this.Shieldrate`| `=this.Shieldnotes`|
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
>> ### Attributes 
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
>>### Heart Abilities
>>
>>| **Ability Name** | Life Bolt | **Type** | Holy, Attack, Support |
>>|:-:|:----------:|:-----:|:---------------------:|
>>| **Rank** | Novice | **XP** | |
>>| **Cost** | 2 MP | **Heart** | Talent, Restoration |
>>| **Actions** | 1 Required | **Range** | 30 m        |  
>>&nbsp;
>> 
>>
>>Target is healed for D6+DM Health. If the target is undead, it deals damage instead.
>>
>>&nbsp;
>>**Apprentice Rank:** Amount increased to 2D6+DM 
>>**Veteran Rank:** Amount increased to 3D6+DM 
>>**Master Rank:** Amount increased to 4D6+DM
>>&nbsp;
>>*You gather divine energy in your hand, shooting off a beam of bright light.*
>>
>>&nbsp
>>
>>---
>>|     |     |
>> |--- | --- |
>>|**Name** | `=this.Spell1`|
>>|**CL** |  `=this.Spell1cl`|
>> | **Description**     | `=this.Spell1des` | 
>> |||
>>|**Name** | `=this.Spell2`|
>>|**CL** |  `=this.Spell2cl`|
>> | **Description**     | `=this.Spell2des` | 
>> |||
>>|**Name** | `=this.Spell3`|
>>|**CL** |  `=this.Spell3cl`|
>> | **Description**     | `=this.Spell3des` | 
>> |||
>>|**Name** | `=this.Spell4`|
>>|**CL** |  `=this.Spell4cl`|
>> | **Description**    | `=this.Spell4des` | 

>[!success] %%FAKE TITLE HERE%%
>>[!success] %%FAKE TITLE HERE%%
>> ##### Character Traits
>>|     |     |
>> |--- | --- |
>>| **Home Region**   |  `=this.hregion`   |
>>|**Formative Event** | `=this.Fevent`|
>> |**Significant Event** |`=this.Sevent` |
>>| **Character Flaws**   |  `=this.flaws`   |
>>| **Parents Occupation**   |  `=this.poccupation`   |
>>
>
>>[!travel] %%FAKE TITLE HERE%%
>> ### Alchemy Journal
>>|Plant/Herb|Commonly Found In|Potential Effect|Combined With|Produces|
>>|---|---|---|---|---|
>>|`=this.plant69`|`=this.found69`|`=this.effect69`|`=this.combined69`|`=this.produces69`|
>>|`=this.plant1`|`=this.found1`|`=this.effect1`|`=this.combined1`|`=this.produces1`|
>>|`=this.plant2`|`=this.found2`|`=this.effect2`|`=this.combined2`|`=this.produces2`|
>>|`=this.plant3`|`=this.found3`|`=this.effect3`|`=this.combined3`|`=this.produces3`|
>>|`=this.plant4`|`=this.found4`|`=this.effect4`|`=this.combined4`|`=this.produces4`|
>>|`=this.plant5`|`=this.found5`|`=this.effect5`|`=this.combined5`|`=this.produces5`|
>>|`=this.plant6`|`=this.found6`|`=this.effect6`|`=this.combined6`|`=this.produces6`|
>>|`=this.plant7`|`=this.found7`|`=this.effect7`|`=this.combined7`|`=this.produces7`|
>>|`=this.plant8`|`=this.found8`|`=this.effect8`|`=this.combined8`|`=this.produces8`|
>>|`=this.plant9`|`=this.found9`|`=this.effect9`|`=this.combined9`|`=this.produces9`|
>>|`=this.plant10`|`=this.found10`|`=this.effect10`|`=this.combined10`|`=this.produces10`|
>>|`=this.plant11`|`=this.found11`|`=this.effect11`|`=this.combined11`|`=this.produces11`|
>>|`=this.plant12`|`=this.found12`|`=this.effect12`|`=this.combined12`|`=this.produces12`|
>>|`=this.plant13`|`=this.found13`|`=this.effect13`|`=this.combined13`|`=this.produces13`|
>>|`=this.plant14`|`=this.found14`|`=this.effect14`|`=this.combined14`|`=this.produces14`|
>>|`=this.plant1416`|`=this.found1416`|`=this.effect1416`|`=this.combined1416`|`=this.produces1416`|
>>|`=this.plant1417`|`=this.found1417`|`=this.effect1417`|`=this.combined1417`|`=this.produces1417`|
>>|`=this.plant1418`|`=this.found1418`|`=this.effect1418`|`=this.combined1418`|`=this.produces1418`|


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







