---
Art: "![[Hema.webp|600]]"
Level: 2
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
xp: 10
axp: 
Weapon1: Bone Battleaxe
Weapon1dmg: 3D6
Weapon1notes: Parry, Two-handed
Weapon2: Long Bow
Weapon2dmg: D6
Weapon2notes: Two-handed
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
archetype1: 
Title4: 10 Pale Ghar claws  (20 jats ea.)
Title5: One-Handed Sword
Title6: Wolf Pelt (100 jats)
Lightitem1: false
exampleProperty: false
title1: Bone Battleaxe
title2: Bone Battleaxe
title3: Light Armor
title4: Healing Tincture
title5: Lantern
title6: Long Bow
title7: Camping gear
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
title8: Camping gear
checkbox8: false
title9: Portable Alchemy
checkbox9: false
title10: Portable Alchemy
equipped10: true
title11: Portable Alchemy
equipped11: false
title12: Ornate Helmet (800 jats)
title13: A Piece of Mail Armor (800 jats)
equipped12: false
equipped13: false
equipped5: true
equipped9: true
checkbox11: false
title14: A Iron Maul (D10+4). (800 jats)
checkbox14: false
plant69: Crypt Tears
found69: Ruins
effect69: Counters the effects of a poison
combined69: Nimble Thorn
produces69: Antidote.
plant1: Nimble Thorn
found1: Ruins
effect1: Counters the effects of a poison
combined1: Crypt Tears
produces1: Antidote.
plant2: Sanguine Dew
found2: Caves
effect2: NA
combined2: NA
produces2: NA
plant3: Nivyl
found3: Caves
effect3: NA
combined3: NA
produces3: NA
title15: A Iron Maul (D10+4). (800 jats)
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
checkbox16: false
lightitem1: Way Clover x6
lightitem2: Nimble Thorn x5
lightitem3: Crypt Tears x4
lightitem4: Bandage x10
lightitem5: Lamp Oil x9
checkbox6: true
checkbox22: true
lightitem6: Rations
lightitem7: Lockpicks x10
lightitem8: Sanguine Dew x7
lightitem9: Large Gemstone (200 jats)
lightitem10: Nivyl x4
lightitem11: Scroll of Cleanse Poison (500 jats)
lightitem12: Potion of Antidote x1
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
>>---
>
>>[!travel] %%FAKE TITLE HERE%%
>>
>>&nbsp;
>>
>>### Combo Abilities
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
>
>>[!travel] %%FAKE TITLE HERE%%
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
>>| **Gear Slot** | Item |Equipped? |
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
>
>>[!dice] %%FAKE TITLE HERE%%
>> ### Light Item Slots
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







