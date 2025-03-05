---
Art: "![[Character Image Placholder]]"
Level: 2
CurrentCorruption: 0
Corruption: 10
HP: 41
GeSl: 0
STR: 18
DEX: 17
CONST: 16
WIL: 15
INT: 14
CHA: 12
xp: 84
axp: 20
Weapon1: Longsword
Weapon1dmg: D8+1
Weapon1notes: Versatile (D10)
Weapon2: Greatsword
Weapon2dmg: 2D8
Weapon2notes: -10 to Defensive Skills
Weapon3: Long Bow
Weapon3dmg: D6
Weapon3notes: 
Armor: 1
currency: 150
ajats: 
merc: ".6"
provisions: 10
hregion: Akkar Strand
advantages: "**Extreme Concentration:** This allows you to perform extremely well under stress in any circumstance (combat, running from danger, etc.)."
disadvantages: "**Violent:** You simply think that violence is the answer to all questions."
flaws: Bad Tempered I
Head: Hunter (Foraging, Marksmanship)
Title69: 1x Healing Tincture
Title1: Rations
Pskills69: Marksmanship You may relinquish your turn to aim with a Ranged Weapon, doubling the damage of your next attack.
Pskills1: Foraging (Archetype Exclusive) This character consumes half as many supplies per day, thanks to their ability to find sources of food and water in the wild.
Title2: Torch x 10
Title3: Bandage x 5
Pskills2: "Inner Compass (1 EP): You may re-roll once any failed Orientation tests."
passive0: "**Marksmanship** You may relinquish your turn to aim with a Ranged Weapon, doubling the damage of your next attack."
passive1: "**Foraging (Archetype Exclusive)** This character consumes half as many supplies per day, thanks to their ability to find sources of food and water in the wild."
passive2: "**Inner Compass** You may re-roll once any failed Orientation tests."
archetype0: "**Hunter** Foraging, Marksmanship"
Title4: 10 Pale Ghar claws  (20 jats ea.)
Title5: One-Handed Sword
Title6: Wolf Pelt (100 jats)
Lightitem1: false
exampleProperty: false
title1: 1x Healing Tincture
title2: Rations
title3: Torch
title4: Bandage x 5
title5: Great Sword
title6: Great Sword
title7: Jats
checkbox1: true
checkbox2: true
checkbox3: true
checkbox4: true
checkbox5: false
checkbox7: true
equipped6: true
equipped7: false
mod0: "**Camping Gear** +20 Outdoor Survival when setting camp"
mod1: 
mod2: 
mod3: 
mod4: 
Spell1: 
Spell1cl: 
Spell1idio: 
Spell1des: 
Spell2cl: 
Spell2idio: 
Spell2des: 
Spell1mem: 
quest1: Witchreef Elder Fadar tells me that a sacred Temple that is used by the village Five Hexes Away and it has been over run by a Blessed One. He wants me to retake the temple and destroy the Blessed One.
quest2: 
title8: Jats
checkbox8: true
title9: Light Armor (+2)
checkbox9: false
title10: Light Armor (+2)
equipped10: true
title11: Tears of the Mother Remove all Conditions
equipped11: false
title12: Camping Gear +20 Outdoor Survival when setting camp
title13: Camping Gear
equipped12: false
equipped13: false
equipped5: true
equipped9: true
checkbox11: true
title14: Twilight Berry x 10
checkbox14: true
plant69: Twilight Berry
found69: Forests
effect69: Unknown
combined69: Unknown
produces69: Unknown
title15: Crawler Fangs x 6 (25 jats)
checkbox15: true
title16: Steel Deer Antlers (300 jats)
title17: Short Bow
title18: Long Bow
equipped18: true
title19: Longsword
equipped19: true
title20: Knife
---
>[!dice] %%FAKE TITLE HERE%%
>> [!dice] %%FAKE TITLE HERE%%
>> # `=this.file.name`
>> ![[Zaalu_P.webp|600]]
>> ###### Stats
>>|     |     |
>> |--- | --- |
>>|   **Level**   |  `=this.level`   |
>>|**HP** | **Current:** `43` **Max:** `=this.CONST*3`|
>> |**Corruption** | **Current:** `=this.CurrentCorruption` **Max:** `=this.Corruption`   |
>> |**Taint Threshold** | `=this.CurrentCorruption*10` |
>> |**Armor** | `=this.Armor` |
>> |**EP**| `2` |
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
>> ##### Character Traits
>>|     |     |
>> |--- | --- |
>>| **Home Region**   |  `=this.hregion`   |
>>|**Advantages** | `=this.advantages`|
>> |**Disadvantages** |`=this.disadvantages` |
>>| **Character Flaws**   |  `=this.flaws`   |
>>
>>&nbsp;
>>
>> ###### Supplies
>>  | 
>>---|---|
>>**Jats**|`=this.currency` |
>>**Sellsword Cut**| `VIEW[{ajats} * {merc}]`
>>**Provisions**|`12` |
>>**Torches**|`8` |
>>**Lamp Oil**|`0` |
>>**Sellsword jats**|  `INPUT[number:ajats]` `BUTTON[pjats]`|


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
>>| **Max Gear Slots**     | `=(this.STR)` | 
>>---
>>&nbsp;
>> ### Skill Checks
>>| <span style="color:rgb(129, 216, 208)">Skill Name</span>|<span style="color:rgb(129, 216, 208)"> Skill Level</span> |
>>| ------------ | ----------- |
>>| **Alchemy** | `31` |
>>| **Animal Handling** (CHA `=this.CHA`) | `12` |
>>| **Command Skills** (CHA `=this.CHA`) | `12` |
>>| **Crafting** (DEX `=this.DEX`) | `39` |
>>| **Disguise** (DEX `=this.DEX`) | `17` |
>>| **Dodge** (DEX `=this.DEX` x 2) | `44` |
>>|**First Aid** (20) | `50` |
>>| **Forbidden Lore** | `22` |
>>| **Herb Lore** | `37` |
>>| **Literacy** (INT `=this.INT`) | `45` |
>>| **One-Handed Melee** (STR `=this.STR` + DEX `=this.DEX`) | `53` |
>>| **Orientation** (20) | `41` |
>>|**Outdoor Survival** (INT `=this.INT` + DEX `=this.DEX`) | `46` |
>>| **Parry** (STR `=this.STR` + DEX `=this.DEX`) | `49` |
>>| **Perception** (20) | `31` |
>>| **Persuasion** (CHA `=this.CHA`) | `12` |
>>| **Pick Pockets** (DEX `=this.DEX`) | `17` |
>>| **Ranged Weapons** (DEX `=this.DEX` x 2) | `44` |
>>| **Sailing** (DEX `=this.DEX`) | `17` |
>>| **Sneaking** (DEX `=this.DEX` x 2) | `34` |
>>| **Throw** (STR `=this.STR` + DEX `=this.DEX`) | `35` |
>>| **Tracking** (INT `=this.INT` ) | `29` |
>>| **Traditional Lore** (20) | `20` |
>>| **Two-Handed Melee** (STR `=this.STR` x 2) | `46` |
>>| **Unarmed** (STR `=this.STR` + DEX `=this.DEX`) | `35` |
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
>>| Slot |  |Light Item | Equipped?|
>>| :-: | :---------------- |--------|--------|
>>|1|`INPUT[text:title1]`|`INPUT[toggle:checkbox1]`|`INPUT[toggle:equipped1]`
>>|2|`INPUT[text:title2]`|`INPUT[toggle:checkbox2]`|`INPUT[toggle:equipped2]`
>>|3|`INPUT[text:title3]`|`INPUT[toggle:checkbox3]`|`INPUT[toggle:equipped3]`
>>|4|`INPUT[text:title4]`|`INPUT[toggle:checkbox4]`|`INPUT[toggle:equipped4]`
>>|5|`INPUT[text:title5]`|`INPUT[toggle:checkbox5]`|`INPUT[toggle:equipped5]`
>>|6|`INPUT[text:title6]`|`INPUT[toggle:checkbox6]`|`INPUT[toggle:equipped6]`
>>|7|`INPUT[text:title7]`|`INPUT[toggle:checkbox7]`|`INPUT[toggle:equipped7]`
>>|8|`INPUT[text:title8]`|`INPUT[toggle:checkbox8]`|`INPUT[toggle:equipped8]`
>>|9|`INPUT[text:title9]`|`INPUT[toggle:checkbox9]`|`INPUT[toggle:equipped9]`
>>|10|`INPUT[text:title10]`|`INPUT[toggle:checkbox10]`|`INPUT[toggle:equipped10]`
>>|11|`INPUT[text:title11]`|`INPUT[toggle:checkbox11]`|`INPUT[toggle:equipped11]`
>>|12|`INPUT[text:title12]`|`INPUT[toggle:checkbox12]`|`INPUT[toggle:equipped12]`
>>|13|`INPUT[text:title13]`|`INPUT[toggle:checkbox13]`|`INPUT[toggle:equipped13]`
>>|14|`INPUT[text:title14]`|`INPUT[toggle:checkbox14]`|`INPUT[toggle:equipped14]`
>>|15|`INPUT[text:title15]`|`INPUT[toggle:checkbox15]`|`INPUT[toggle:equipped15]`
>>|16|`INPUT[text:title16]`|`INPUT[toggle:checkbox16]`|`INPUT[toggle:equipped16]`
>>|17|`INPUT[text:title17]`|`INPUT[toggle:checkbox17]`|`INPUT[toggle:equipped17]`
>>|18|`INPUT[text:title18]`|`INPUT[toggle:checkbox18]`|`INPUT[toggle:equipped18]`
>>|19|`INPUT[text:title19]`|`INPUT[toggle:checkbox19]`|`INPUT[toggle:equipped19]`
>>|20|`INPUT[text:title20]`|`INPUT[toggle:checkbox20]`|`INPUT[toggle:equipped20]`
>>|21|`INPUT[text:title21]`|`INPUT[toggle:checkbox21]`|`INPUT[toggle:equipped21]`
>>|22|`INPUT[text:title22]`|`INPUT[toggle:checkbox22]`|`INPUT[toggle:equipped22]`
>>|23|`INPUT[text:title23]`|`INPUT[toggle:checkbox23]`|`INPUT[toggle:equipped23]`
>>|24|`INPUT[text:title24]`|`INPUT[toggle:checkbox24]`|`INPUT[toggle:equipped24]`
>>|25|`INPUT[text:title25]`|`INPUT[toggle:checkbox25]`|`INPUT[toggle:equipped25]`
>>|26|`INPUT[text:title26]`|`INPUT[toggle:checkbox26]`|`INPUT[toggle:equipped26]`
>>|27|`INPUT[text:title27]`|`INPUT[toggle:checkbox27]`|`INPUT[toggle:equipped27]`
>>|28|`INPUT[text:title28]`|`INPUT[toggle:checkbox28]`|`INPUT[toggle:equipped28]`
>>|29|`INPUT[text:title29]`|`INPUT[toggle:checkbox29]`|`INPUT[toggle:equipped29]`
>>|30|`INPUT[text:title30]`|`INPUT[toggle:checkbox30]`|`INPUT[toggle:equipped30]`
>>|31|`INPUT[text:title31]`|`INPUT[toggle:checkbox31]`|`INPUT[toggle:equipped31]`
>>|32|`INPUT[text:title32]`|`INPUT[toggle:checkbox32]`|`INPUT[toggle:equipped32]`
>>|33|`INPUT[text:title33]`|`INPUT[toggle:checkbox33]`|`INPUT[toggle:equipped33]`
>>|34|`INPUT[text:title34]`|`INPUT[toggle:checkbox34]`|`INPUT[toggle:equipped34]`
>>|35|`INPUT[text:title35]`|`INPUT[toggle:checkbox35]`|`INPUT[toggle:equipped35]`
>>|36|`INPUT[text:title36]`|`INPUT[toggle:checkbox36]`|`INPUT[toggle:equipped36]`
>>|37|`INPUT[text:title37]`|`INPUT[toggle:checkbox37]`|`INPUT[toggle:equipped37]`
>>|38|`INPUT[text:title38]`|`INPUT[toggle:checkbox38]`|`INPUT[toggle:equipped38]`
>>|39|`INPUT[text:title39]`|`INPUT[toggle:checkbox39]`|`INPUT[toggle:equipped39]`
>>|40|`INPUT[text:title40]`|`INPUT[toggle:checkbox40]`|`INPUT[toggle:equipped40]`
>
>>[!table] %%FAKE TITLE HERE%%
>>### Magic
>>|     |     |
>> |--- | --- |
>>|**Name** | `=this.Spell1`|
>>|**CL** |  `=this.Spell1cl`|
>> | **Description**     | `=this.Spell1des` | 
>>|**Name** | `=this.Spell2`|
>>|**CL** |  `=this.Spell2cl`|
>> | **Description**     | `=this.Spell2des` | 

>[!important] %%FAKE TITLE HERE%%
>>[!important] %%FAKE TITLE HERE%%
>>##### Quests
>>Description  | Milestones |
>>---|---|
>>`=this.quest1`|`2/6` |
>>`=this.quest2`| |
>>
>>##### Notes
>>`INPUT[textArea:Other]`
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







