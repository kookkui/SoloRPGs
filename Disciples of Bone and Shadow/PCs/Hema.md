---
Art: "![[Hema.webp|600]]"
Level: 1
CurrentCorruption: 0
Corruption: 10
HP: 0
GeSl: 0
STR: 12
DEX: 12
CONST: 10
WIL: 18
INT: 18
CHA: 10
xp: 32
axp: 10
Weapon1: Bone Battleaxe
Weapon1dmg: 3D6
Weapon1notes: Parry, Two-handed
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
currency: 90
ajats: 
merc: ".6"
provisions: 10
hregion: Madari
poccupation: "**Mercenaries.** Your parents lived by the sword, killing for the best bidder and moving on when the jats dried up."
Fevent: Your hunger for forbidden magic caused a terrible tragedy in your past, forcing you to leave your home. Maybe you injured someone accidentally with a spell, or you killed someone in order to get your hands on a grimoire; the fact is, you let your ambition get the best of you. Do you repent, or will you continue down this path?
Sevent: You saved a group of people from certain death.
flaws: 
Head: 
Title69: 1x Healing Tincture
Title1: Rations
Pskills69: 
Pskills1: 
Title2: Torch x 10
Title3: Bandage x 5
Pskills2: "Inner Compass (1 EP): You may re-roll once any failed Orientation tests."
passive0: 
passive1: 
passive2: 
archetype0: "**Vitalist.** You’ve seen the world struggling to survive, and you’ve chosen compassion. You do your best to ameliorate the pain in others through whatever means, even if the price is your own sanity."
Title4: 10 Pale Ghar claws  (20 jats ea.)
Title5: One-Handed Sword
Title6: Wolf Pelt (100 jats)
Lightitem1: false
exampleProperty: false
title1: Bone Battleaxe
title2: Bone Battleaxe
title3: Light Armor
title4: Rations
title5: Lantern
title6: Lamp Oil x10
title7: Bandage x10
checkbox1: true
checkbox2: true
checkbox3: true
checkbox4: false
checkbox5: false
checkbox7: false
equipped6: true
equipped7: false
mod0: "**Camping Gear** +20 Outdoor Survival when setting camp"
mod1: "**Portable Alchemy Kit** Can be used in the field, -10 Alchemy"
mod2: 
mod3: 
mod4: 
Spell1: Cauterize (2 daily uses)
Spell1cl: "4"
Spell1des: Heal D10+L HP from one character.
Spell2: Shared Corruption
Spell2cl: 6
Spell2des: The caster may transfer into themselves D4 CP from another target.
Spell3: Shield of Iniquity
Spell3cl: "6"
Spell3des: +20 Parry, Until the end of combat
Spell4: Cleanse Poison
Spell4cl: 4
Spell4des: Remove the poisoned effect from one character.
quest1: Placeholder Quest
quest2: 
title8: "Healing Tincture x1 "
checkbox8: false
title9: Camping gear
checkbox9: false
title10: Camping gear
equipped10: true
title11: Portable Alchemy
equipped11: false
title12: Portable Alchemy
title13: Portable Alchemy
equipped12: false
equipped13: false
equipped5: true
equipped9: true
checkbox11: false
title14: ""
checkbox14: false
plant69: 
found69: 
effect69: 
combined69: 
produces69: 
title15: ""
checkbox15: false
title16: ""
title17: ""
title18: ""
equipped18: true
title19: ""
equipped19: true
title20: ""
title21: ""
checkbox21: false
Other: |-
  - Rumor has it that the individual that is the murderer was spotted hiding out in some ruins 3 days ride from the village.
  - 6 Hexes away
  - Ruins
  - Possibly The Veil Deathbinder
---
>[!dice] %%FAKE TITLE HERE%%
>> [!dice] %%FAKE TITLE HERE%%
>> # `=this.file.name`
>> `=this.Art`
>> ###### Stats
>>|     |     |
>> |--- | --- |
>>|   **Level**   |  `=this.level`   |
>>|**HP** | **Current:** `30` **Max:** `=this.CONST*3`|
>> |**Corruption** | **Current:** `=this.CurrentCorruption` **Max:** `=this.Corruption`   |
>> |**Taint Threshold** | `=this.CurrentCorruption*10` |
>> |**EP**| `0` |
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
>>  | 
>>---|---|
>>**Jats**|`=this.currency` |
>>**Sellsword Cut**| `VIEW[{ajats} * {merc}]`
>>**Provisions**|`10` |
>>**Torches**|`0` |
>>**Lamp Oil**|`4` |
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


>[!tldr] %%FAKE TITLE HERE%%
>>[!tldr] %%FAKE TITLE HERE%%
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
>>| **Alchemy** | `25` |
>>| **Animal Handling** (CHA `=this.CHA`) | `22` |
>>| **Command Skills** (CHA `=this.CHA`) | `10` |
>>| **Crafting** (DEX `=this.DEX`) | `22` |
>>| **Disguise** (DEX `=this.DEX`) | `12` |
>>| **Dodge** (DEX `=this.DEX` x 2 ) (`=(this.DEX)*2`) | `48` |
>>|**First Aid** (20) | `45` |
>>| **Forbidden Lore** | `10` |
>>| **Herb Lore** | `31` |
>>| **Literacy** (INT `=this.INT`) | `46` |
>>| **One-Handed Melee** (STR `=this.STR` + DEX `=this.DEX`) (`=(this.STR)+(this.DEX)`) | `44` |
>>| **Orientation** (20) | `41` |
>>|**Outdoor Survival** (INT `=this.INT` + DEX `=this.DEX`) (`=(this.INT)+(this.DEX)`)| `40` |
>>| **Parry** (STR `=this.STR` + DEX `=this.DEX`) (`=(this.STR)+(this.DEX)`) | `44` |
>>| **Perception** (20) | `35` |
>>| **Persuasion** (CHA `=this.CHA`) | `21` |
>>| **Pick Pockets** (DEX `=this.DEX`) | `12` |
>>| **Ranged Weapons** (DEX `=this.DEX` x 2) (`=(this.DEX)*2`) | `24` |
>>| **Sailing** (DEX `=this.DEX`) | `12` |
>>| **Sneaking** (DEX `=this.DEX` x 2 ) (`=(this.DEX)*2`) | `40` |
>>| **Throw** (STR `=this.STR` + DEX `=this.DEX`) (`=(this.STR)+(this.DEX)`) | `24` |
>>| **Tracking** (INT `=this.INT` ) | `40` |
>>| **Traditional Lore** (20) | `30` |
>>| **Two-Handed Melee** (STR `=this.STR` x 2) (`=(this.STR)*2`) | `41` |
>>| **Unarmed** (STR `=this.STR` + DEX `=this.DEX`) (`=(this.STR)+(this.DEX)`)| `24` |
>>
>
>>[!tldr] %%FAKE TITLE HERE%%
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
>>[!tldr] %%FAKE TITLE HERE%%
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

>[!table] %%FAKE TITLE HERE%%
>>[!table] %%FAKE TITLE HERE%%
>> ### Inventory
>>| Slot | Item |Equipped? |
>>| :-: | :----: |:----:|
>>|1|`INPUT[text:title1]`|`INPUT[toggle:checkbox1]`|
>>|2|`INPUT[text:title2]`|`INPUT[toggle:checkbox2]`|
>>|3|`INPUT[text:title3]`|`INPUT[toggle:checkbox3]`|
>>|4|`INPUT[text:title4]`|`INPUT[toggle:checkbox4]`|
>>|5|`INPUT[text:title5]`|`INPUT[toggle:checkbox5]`|
>>|6|`INPUT[text:title6]`|`INPUT[toggle:checkbox6]`|
>>|7|`INPUT[text:title7]`|`INPUT[toggle:checkbox7]`|
>>|8|`INPUT[text:title8]`|`INPUT[toggle:checkbox8]`|
>>|9|`INPUT[text:title9]`|`INPUT[toggle:checkbox9]`|
>>|10|`INPUT[text:title10]`|`INPUT[toggle:checkbox10]`|
>>|11|`INPUT[text:title11]`|`INPUT[toggle:checkbox11]`|
>>|12|`INPUT[text:title12]`|`INPUT[toggle:checkbox12]`|
>>|13|`INPUT[text:title13]`|`INPUT[toggle:checkbox13]`|
>>|14|`INPUT[text:title14]`|`INPUT[toggle:checkbox14]`|
>>|15|`INPUT[text:title15]`|`INPUT[toggle:checkbox15]`|
>>|16|`INPUT[text:title16]`|`INPUT[toggle:checkbox16]`|
>>|17|`INPUT[text:title17]`|`INPUT[toggle:checkbox17]`|
>>|18|`INPUT[text:title18]`|`INPUT[toggle:checkbox18]`|
>>|19|`INPUT[text:title19]`|`INPUT[toggle:checkbox19]`|
>>|20|`INPUT[text:title20]`|`INPUT[toggle:checkbox20]`|
>>|21|`INPUT[text:title21]`|`INPUT[toggle:checkbox21]`|
>>|22|`INPUT[text:title22]`|`INPUT[toggle:checkbox22]`|
>>|23|`INPUT[text:title23]`|`INPUT[toggle:checkbox23]`|
>>|24|`INPUT[text:title24]`|`INPUT[toggle:checkbox24]`|
>>|25|`INPUT[text:title25]`|`INPUT[toggle:checkbox25]`|
>>|26|`INPUT[text:title26]`|`INPUT[toggle:checkbox26]`|
>>|27|`INPUT[text:title27]`|`INPUT[toggle:checkbox27]`|
>>|28|`INPUT[text:title28]`|`INPUT[toggle:checkbox28]`|
>>|29|`INPUT[text:title29]`|`INPUT[toggle:checkbox29]`|
>>|30|`INPUT[text:title30]`|`INPUT[toggle:checkbox30]`|
>>|31|`INPUT[text:title31]`|`INPUT[toggle:checkbox31]`|
>>|32|`INPUT[text:title32]`|`INPUT[toggle:checkbox32]`|
>>|33|`INPUT[text:title33]`|`INPUT[toggle:checkbox33]`|
>>|34|`INPUT[text:title34]`|`INPUT[toggle:checkbox34]`|
>>|35|`INPUT[text:title35]`|`INPUT[toggle:checkbox35]`|
>>|36|`INPUT[text:title36]`|`INPUT[toggle:checkbox36]`|
>>|37|`INPUT[text:title37]`|`INPUT[toggle:checkbox37]`|
>>|38|`INPUT[text:title38]`|`INPUT[toggle:checkbox38]`|
>>|39|`INPUT[text:title39]`|`INPUT[toggle:checkbox39]`|
>>|40|`INPUT[text:title40]`|`INPUT[toggle:checkbox40]`|
>
>>[!table] %%FAKE TITLE HERE%%
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

>[!important] %%FAKE TITLE HERE%%
>>[!important] %%FAKE TITLE HERE%%
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
>>[!hint] %%FAKE TITLE HERE%%
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
>>|`=this.plant12`|`=this.found12`|`=this.effect1`|`=this.combined12`|`=this.produces12`|
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







