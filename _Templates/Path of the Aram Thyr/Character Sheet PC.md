---
Art: "![[Hema.webp|600]]"
HP: 0
STR: 12
DEX: 12
CONST: 10
WIL: 18
INT: 18
CHA: 10
xp: 10
spiritstage: Wood
axp: 
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
currency: 115
ajats: 
merc: ".6"
provisions: 10
flaws: 
Head: 
Pskills2: "Inner Compass (1 EP): You may re-roll once any failed Orientation tests."
passive0: 
passive1: 
passive2: 
---
>[!dice] %%FAKE TITLE HERE%%
>> [!dice] %%FAKE TITLE HERE%%
>> # `=this.file.name`
>> `=this.Art`
>> ###### Stats
>>|     |     |
>> |--- | --- |
>>|   **Spirit Stage**   |  `=this.spiritstage`   |
>>|**HP** | **Current:** `30` **Max:** `=this.CONST*3`|
>> |**Corruption** | **Current:** `=this.CurrentCorruption` **Max:** `=this.Corruption`   |
>> |**Taint Threshold** | `=this.CurrentCorruption*10` |
>> |**EP**| `0` |
>> |**XP** | `VIEW[{xp}][text]`|
>> |**XP Needed** | `=150-(this.xp)`|
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
>>  | 
>>---|---|
>>**Jats**|`=this.currency` |
>>**Sellsword Cut**| `VIEW[{ajats} * {merc}]`
>>**Provisions**|`23` |
>>**Torches**|`0` |
>>**Lamp Oil**|`18` |
>>**Sellsword jats**|  `INPUT[number:ajats]` `BUTTON[pjats]`|
>>
>>&nbsp;
>>
>>##### Quests
>>Description  | Milestones |
>>---|---|
>>`=this.quest1`|`0/6` |
>>`=this.quest2`| |
>>
>>
>>##### Notes
>>`INPUT[textArea:Other]`


>[!thing] %%FAKE TITLE HERE%%
>>[!thing] %%FAKE TITLE HERE%%
>> ### Stats
>>|        |         |   
>>| ---- | ---- |
>>| **Strength**   | `=this.STR`  |
>>| **Dexterity**    | `=this.DEX` | 
>>| **Constitution** | `=this.CONST` |
>>| **Will**         |  `=this.WIL` | 
>>| **Intelligence** |  `=this.INT` | 
>>| **Charisma**     | `=this.CHA` | 
>>| **Max Gear Slots**     | `=(this.STR)+10` | 
>>---
>>&nbsp;
>> ### Skill Checks
>>| <span style="color:rgb(129, 216, 208)">Skill Name</span>|<span style="color:rgb(129, 216, 208)"> Skill Level</span> |
>>| ------------ | ----------- |
>>| **Alchemy** | `31` |
>>| **Animal Handling** (CHA `=this.CHA`) | `22` |
>>| **Command Skills** (CHA `=this.CHA`) | `10` |
>>| **Crafting** (DEX `=this.DEX`) | `22` |
>>| **Disguise** (DEX `=this.DEX`) | `12` |
>>| **Dodge** (DEX `=this.DEX` x 2 ) (`=(this.DEX)*2`) | `48` |
>>|**First Aid** (20) | `45` |
>>| **Forbidden Lore** | `10` |
>>| **Herb Lore** | `47` |
>>| **Literacy** (INT `=this.INT`) | `46` |
>>| **One-Handed Melee** (STR `=this.STR` + DEX `=this.DEX`) (`=(this.STR)+(this.DEX)`) | `44` |
>>| **Orientation** (20) | `41` |
>>|**Outdoor Survival** (INT `=this.INT` + DEX `=this.DEX`) (`=(this.INT)+(this.DEX)`)| `40` |
>>| **Parry** (STR `=this.STR` + DEX `=this.DEX`) (`=(this.STR)+(this.DEX)`) | `56` |
>>| **Perception** (20) | `36` |
>>| **Persuasion** (CHA `=this.CHA`) | `21` |
>>| **Pick Pockets** (DEX `=this.DEX`) | `12` |
>>| **Ranged Weapons** (DEX `=this.DEX` x 2) (`=(this.DEX)*2`) | `25` |
>>| **Sailing** (DEX `=this.DEX`) | `12` |
>>| **Sneaking** (DEX `=this.DEX` x 2 ) (`=(this.DEX)*2`) | `35` |
>>| **Throw** (STR `=this.STR` + DEX `=this.DEX`) (`=(this.STR)+(this.DEX)`) | `24` |
>>| **Tracking** (INT `=this.INT` ) | `35` |
>>| **Traditional Lore** (20) | `30` |
>>| **Two-Handed Melee** (STR `=this.STR` x 2) (`=(this.STR)*2`) | `62` |
>>| **Unarmed** (STR `=this.STR` + DEX `=this.DEX`) (`=(this.STR)+(this.DEX)`)| `24` |
>>
>
>>[!seealso] %%FAKE TITLE HERE%%
>> ### Modifiers
>> |        |         |   
>>| :-: | :----- |
>>| 1 | `=this.mod0` |
>>| 2 | `=this.mod1` |
>>| 3 | `=this.mod2` |
>>| 4 | `=this.mod3` |
>>| 5 | `=this.mod4` |
>>| 6 |`=this.mod5` |
>>| 7 | `=this.mod6` |
>
>>[!travel] %%FAKE TITLE HERE%%
>> ### Passive Skills
>> |        |         |   
>>| :-: | :----------------------------------------- |
>>| 1 | `=this.passive0` |
>>| 2 | `=this.passive1` |
>>| 3 | `=this.passive2` |
>>| 4 | `=this.passive3` |
>>| 5 | `=this.passive4` |
>>| 6 |`=this.passive5` |
>>| 7 | `=this.passive6` |
>>| 8 | `=this.passive7` |
>>| 9 | `=this.passive8` |
>>| 10 | `=this.passive9` |
>>| 11 | `=this.passive10` |
>>| 12 | `=this.passive11` |
>>| 13 | `=this.passive12` |
>>| 14 | `=this.passive13` |
>>| 15 | `=this.passive14` |
>>| 16 | `=this.passive1416` |
>>| 17 | `=this.passive1417` |
>>| 18 | `=this.passive1418`
>
>>[!tldr] %%FAKE TITLE HERE%%
>>##### Archetypes
>> |        |         |   
>>| :-: | :----- |
>>| 1 | `=this.archetype0` |
>>| 2 | `=this.archetype1` |
>>| 3 | `=this.archetype2` |
>>| 4 | `=this.archetype3` |
>>| 5 | `=this.archetype4` |
>>| 6 |`=this.archetype5` |
>>| 7 | `=this.archetype6` |

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
>>### Magic
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







