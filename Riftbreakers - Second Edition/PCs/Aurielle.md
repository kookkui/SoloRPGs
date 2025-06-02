---
Art: "![[Aurielle.webp|550]]"
Title: 
achievement_prog: "Riftbreaker: Successfully close 5 Rifts."
Protection: D4+3
Weapon1: Longsword
Weapon1dmg: D6
Weapon1type: Slashing
Weapon1notes: Bladed, Versatile, Parry(10)
Weapon2: 
Weapon2dmg: 
Weapon2type: 
Weapon2notes: 
Weapon3: 
Weapon3type: 
Weapon3dmg: 
Weapon3notes: 
achievement_path: Path of the Explorer
aetheryte: 14
aaaetheryte: 0
aaetheryte: 
gems: 
Armor1: Plain Tunic
Armor1rate: D3
Armor1notes: "Max Integrity: D6"
hand1: 
hand2: 
hand3: 
hand4: 
hand5: 
quest1: 
quest1t: false
quest2: 
quest2t: 
quest3: 
quest3t: 
quest4: 
quest4t: 
quest5: 
quest5t: 
quest6: 
quest6t: 
quest7: 
quest7t: 
quest8: 
quest9: 
quest10: 
headname: 
headmagic: 
headquirk: 
headnotes: 
chestname: 
chestmagic: 
chestquirk: 
chestnotes: 
beltname: 
beltmagic: 
beltquirk: 
beltnotes: 
pantsname: 
pantsmagic: 
pantsquirk: 
pantsnotes: 
bootname: 
bootmagic: 
bootquirk: 
bootnotes: 
ring1name: 
ring1magic: 
ring1quirk: 
ring1notes: 
ring2name: 
ring2magic: 
ring2quirk: 
ring2rank: 
ring2notes: 
pendantgearname: 
pendantgearmagic: 
pendantgearquirk: 
pendantgearrank: 
pendantgearnotes: 
title1: 
title2: 
title3: 
title4: 
title5: 
title6: 
title7: 
title8: ""
title9: ""
title10: ""
title11: ""
title12: ""
title13: ""
proficiency1: Longsword
proficiency2: Hard Leather
proficiency3: 
title21: ""
title15: ""
Hearts:
  - Restoration
  - Arrow
  - Ritual
  - Elemental
passive0: 
passive1: 
passive2: 
HeartAbLink1: "![[Cleave]]"
HeartAbLink2: "![[Bless]]"
HeartAbLink3: "![[Divine Shield]]"
HeartAbLink4: "![[Two-Handed Weapon Master]]"
HeartAbLink5: "![[Unbound Fury]]"
HeartAbLink6: "![[Holy Weapon]]"
gear1: Potion of Minor Healing X2
gear2: ""
Appearance1: |-
  Glowing Eyes: Your eyes glow faintly in the dark, with colors ranging from eerie white to deep crimson or electric blue.
  Translucent Skin: Your skin is semi-transparent, revealing faint outlines of your veins, muscles, or even bones beneath.
  Hair: Purple
Integrity1: D6
heart8: true
heart9: true
reputation_rank: Initiate
---
>[!dice] %%FAKE TITLE HERE%%
>>[!dice] %%FAKE TITLE HERE%% 
>> # `=this.file.name`
>> `=this.Art`
>> 
>> ##### Stats
>>  |
>> ---|---|
>>**Title** |`=this.Title` |
>> **Current Achievement Path** |`INPUT[suggester(option(Path of Slaughter), option(Path of Shadows), option(Path of the Arcane), option(Path of the Explorer), option(Path of the Diplomat)):achievement_path]` |
>>  **Achievement in Progress** |`=this.achievement_prog` |
>> **Ability Pool** | `20` |
>> **Reputation** | `0` `INPUT[suggester(option(Initiate), option(Journeyman), option(Vanguard), option(Champion), option(High Warden)):reputation_rank]` |
>> **HP** | **Current:**`26` **Max:** `26`
>> **Luck** | `0` |
>> **Parry** | `10` |
>> **Max Aether** | `10` |
>> **Protection** | `=this.Protection` |
>>
>> &nbsp;
>> 
>>  ##### Wealth
>>|  |   |
>>| :-: | :-: |
>>|**Aetheryte (⟑)** |`=this.aetheryte`|
>>| **Crystals** | `=this.gems`   |
>>| **Add Aetheryte** | `INPUT[number:aaetheryte]` `BUTTON[addaetheryte]`|
>>
>> &nbsp;
>> 
>> 
>> ##### Weapons
>>| **Weapons** | **Skill** | **Damage** | **Notes** |
>>| ------ | :-: | :-: | --------- |
>>| `=this.Weapon1` | `=this.Weapon1type` | `=this.Weapon1dmg` |`=this.Weapon1notes` |
>>| `=this.Weapon2` | `=this.Weapon2type` |`=this.Weapon2dmg` | `=this.Weapon2notes` |
>>| `=this.Weapon3` | `=this.Weapon3type`|`=this.Weapon3dmg` | `=this.Weapon3notes` |
>>
>> &nbsp;
>>
>> ##### Armor
>>| **Armor** | **Protection** | **Integrity** | **Notes** |
>>| ------ | :-: | :-: | --------- |
>>| `=this.Armor1` | `=this.Armor1rate` |  `INPUT[inlineSelect(option(D12), option(D10), option(D8), option(D6), option(D4), option(None)):Integrity1]`|`=this.Armor1notes` |
>>| `=this.Armor2` | `=this.Armor2rate` | `INPUT[inlineSelect(option(D12), option(D10), option(D8), option(D6), option(D4), option(None)):Integrity2]`|`=this.Armor2notes` |
>>
>> &nbsp;
>>
>> ##### Crafting Aspects
>>| **Crafting Component**   | **Common** | **Uncommon** | **Rare** | 
>>| :-: | :-: | :-: | :-: | 
>>|  <font color="#9B5DE5">Monster Part</font>  | `0`  | `0`  | `0`   | 
>>| <font color="#2DC653">Alchemical Ingredient</font> | `0` |`0` | `0` | 
>>|  <font color="#00CCFF">Ore</font>  | `0`  | `0`  | `0`   | 
>>
>> &nbsp;
>>
>> ##### Supplies
> |  | 
>>|---|---
>>|**Torches / Lamp Oil**| `INPUT[inlineSelect(option(D12), option(D10), option(D8), option(D6), option(D4), option(None)):torch1]` |
>>|**Bandages**|`INPUT[inlineSelect(option(D12), option(D10), option(D8), option(D6), option(None)):Bandage]` |
>>|**RiftLord Timer**|`INPUT[inlineSelect(option(D10), option(D8), option(D6), option(None)):RiftLord]` |
>>
>> &nbsp;
>>

---

>[!travel] %%FAKE TITLE HERE%%
>>[!travel] %%FAKE TITLE HERE%%
>>### Current Hand
>>| | |
>>| :-: | ---------------- |
>>|1|`INPUT[text:hand1]` | 
>>|2|`INPUT[text:hand2]` | 
>>|3|`INPUT[text:hand3]` |
>>|4|`INPUT[text:hand4]` |
>>|5|`INPUT[text:hand5]` |
>>
>> &nbsp;
>>
>>### Ability Loadout
>>| `dice:d12` | Ability Loadout  |
>>| ---------- | -------- |
>>| 1          | Weapon Strike (Two-Handed)     |
>>| 2          | Weapon Strike (Two-Handed)      |
>>| 3          | Weapon Strike (Two-Handed)   |
>>| 4          | Raise Skeleton     |
>>| 5          | Weave    |
>>| 6          | Sweeping Whirlwind |
>>| 7          | Double Strike     |
>>| 8          | Demonstrate Superiority |
>>| 9          | Warning   |
>>| 10         | Mark  |
>>| 11         | Mark    |
>>| 12         | Mark   |


>[!gather] %%FAKE TITLE HERE%%
>>[!gather] %%FAKE TITLE HERE%%
>>
>> ### Skill Checks
>>| **Skill Name** | **Skill Level** | **Skill Up**
>>| ------------------------- | ----------- | ----------- |
>>| **Agility** (10) | `20` | `INPUT[toggle:skill1]`|
>>| **Alchemy** | `30` | `INPUT[toggle:skill2]`|
>>| **Animal Handling** | `0` |`INPUT[toggle:skill3]`|
>>| **Armorsmithing** | `10` |`INPUT[toggle:skill4]`|
>>| **Athletics** (10) | `20` |`INPUT[toggle:skill5]`|
>>| **Bladed Weapons** | `60` |`INPUT[toggle:skill6]`|
>>| **Bludgeoning Weapons**  | `0` |`INPUT[toggle:skill7]`|
>>| **Cooking**  | `15` |`INPUT[toggle:skill8]`|
>>|**Command** | `0` | `INPUT[toggle:skill9]`|
>>| **Endurance (10)**  | `25` |`INPUT[toggle:skill10]`
>>| **Gathering**  | `30` |`INPUT[toggle:skill11]`
>>| **Insight**  | `0` |`INPUT[toggle:skill12]`
>>| **Jewelcrafting** | `0` |`INPUT[toggle:skill13]`
>>| **Literacy**| `40` |`INPUT[toggle:skill14]`
>>| **Lockpicking** | `0` |`INPUT[toggle:skill15]`
>>| **Manipulation** | `0` |`INPUT[toggle:skill16]`
>>| **Medicine**  | `15` |`INPUT[toggle:skill17]`
>>| **Nature**  | `0` |`INPUT[toggle:skill18]`
>>| **Perception (20)** | `30` |`INPUT[toggle:skill19]`
>>| **Performance** | `0` |`INPUT[toggle:skill20]`
>>| **Ranged Weapons** | `40` |`INPUT[toggle:skill21]`
>>| **Reason (10)** | `10` |`INPUT[toggle:skill22]`
>>| **Sailing** | `0` |`INPUT[toggle:skill23]`
>>| **Shafted Weapons** | `0` |`INPUT[toggle:skill24]`
>>| **Sleight of Hand** | `0` |`INPUT[toggle:skill25]`
>>| **Stealth** | `15` |`INPUT[toggle:skill26]`
>>| **Survival** | `40` |`INPUT[toggle:skill27]`
>>| **Tenacity (10)** | `40` |`INPUT[toggle:skill28]`
>>| **Unarmed Combat (10)** | `10` |`INPUT[toggle:skill29]`
>>| **Weaponsmithing** | `0` |`INPUT[toggle:skill30]`
>
>>[!gather] %%FAKE TITLE HERE%%
>>##### Proficiencies
>> | | |
>>|:-:| :---: |
>>| `=this.proficiency1` | `=this.proficiency2` |
>>| `=this.proficiency3` | `=this.proficiency4` |
>>| `=this.proficiency5` | `=this.proficiency6` |
>>| `=this.proficiency7` | `=this.proficiency8` |


---

>[!travel] %%FAKE TITLE HERE%%
>>[!travel] %%FAKE TITLE HERE%%
>>### Quests
>>|**Quest Description** |**Completed** | **Timer/Counter**|
>> |:---: | --- | :---------: |
>>| `=this.quest1` | `INPUT[toggle:quest1t]` | `7/14`
>> |`=this.quest2` |`INPUT[toggle:quest2t]` | `0/22`
>>| `=this.quest3` | `INPUT[toggle:quest3t]` | `0/17`
>> |`=this.quest4` |`INPUT[toggle:quest4t]` | `0/22`
>>| `=this.quest5` | `INPUT[toggle:quest5t]` | `0/14`
>> |`=this.quest6` |`INPUT[toggle:quest6t]` | `0/11`
>>| `=this.quest7` | `INPUT[toggle:ques71t]` | `0/13`
>> |`=this.quest8` |`INPUT[toggle:quest8t]` | `0/21`
>>| `=this.quest9` | `INPUT[toggle:ques91t]` | `0/7`
>> |`=this.quest10` |`INPUT[toggle:quest10t]` |

---

>[!table] %%FAKE TITLE HERE%%
>>[!table] %%FAKE TITLE HERE%%
>>### Inventory
>>| Slot | Encumbering Items | Slot| Belt Quickslots
>>| :-: | ---------------- |:-: | ---------------- |
>>|1|`INPUT[text:gear1]` |1|`INPUT[text:qbelt1]` | 
>>|2|`INPUT[text:gear2]` | 2|`INPUT[text:qbelt2]` | 
>>|3|`INPUT[text:gear3]` |3|`INPUT[text:qbelt3]` | 
>>|4|`INPUT[text:gear4]` |4|`INPUT[text:qbelt4]` | 
>>|5|`INPUT[text:gear5]` |
>>|6|`INPUT[text:gear6]` |
>>|7|`INPUT[text:gear7]` |
>>|9|`INPUT[text:gear9]` |
>>|10|`INPUT[text:gear10]` |
>>
>>
>>##### Backpack
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
>
>>[!dice] %%FAKE TITLE HERE%%
>> ### Non-Encumbering Items
>> |Slot| Item |Slot| Item 
>>| :-: | ----------------- |:-: | -------------------------- |
>>| 1 | `INPUT[text:Pskills69]` | 9 | `INPUT[text:Pskills8]` |
>>| 2 | `INPUT[text:Pskills1]` | 10 | `INPUT[text:Pskills9]` |
>>| 3 | `INPUT[text:Pskills2]` |11 | `INPUT[text:Pskills10]` |
>>| 4 | `INPUT[text:Pskills3]` | 12 | `INPUT[text:Pskills11]` |
>>| 5 | `INPUT[text:Pskills4]` |13 | `INPUT[text:Pskills12]` |
>>| 6 |`INPUT[text:Pskills5]` |14 | `INPUT[text:Pskills13]` |
>>| 7 | `INPUT[text:Pskills6]` | 15 | `INPUT[text:Pskills14]` |
>>| 8 | `INPUT[text:Pskills7]` |16 | `INPUT[text:Pskills15]` |
>>

---

>[!travel] %%FAKE TITLE HERE%%
>>[!travel] %%FAKE TITLE HERE%%
>>## Gear
>> &nbsp;
>>
>>### Head
>>| | |
>>|--- | --- |
>>|**Name** | `=this.headname`|
>>|**Magic** | `=this.headmagic`|
>>|**Quirk** | `=this.headquirk`|
>>| **Rank** | `=this.headrank` |
>>| **Notes** | `=this.headnotes` |
>>
>>&nbsp;
>>### Chest
>>| | |
>>|--- | --- |
>>|**Name** | `=this.chestname`|
>>|**Magic** | `=this.chestmagic`|
>>|**Quirk** | `=this.chestquirk`|
>>| **Rank** | `=this.chestrank` |
>>| **Notes** | `=this.chestnotes` |
>> &nbsp;
>>
>>### Belt
>>| | |
>>|--- | --- |
>>|**Name** | `=this.beltname`|
>>|**Magic** | `=this.beltmagic`|
>>|**Quirk** | `=this.beltquirk`|
>>| **Rank** | `=this.beltrank` |
>>| **Notes** | `=this.beltnotes` |
>> &nbsp;
>>
>>### Pants
>>| | |
>>|--- | --- |
>>|**Name** | `=this.pantsname`|
>>|**Magic** | `=this.pantsmagic`|
>>|**Quirk** | `=this.pantsquirk`|
>>| **Rank** | `=this.pantsrank` |
>>| **Notes** | `=this.pantsnotes` |
>> &nbsp;
>>
>>### Gloves
>>| | |
>>|--- | --- |
>>|**Name** | `=this.glovesname`|
>>|**Magic** | `=this.glovesmagic`|
>>|**Quirk** | `=this.glovesquirk`|
>>| **Rank** | `=this.glovesrank` |
>>| **Notes** | `=this.glovesnotes` |
>> &nbsp;
>>
>>### Boots
>>| | |
>>|--- | --- |
>>|**Name** | `=this.bootname`|
>>|**Magic** | `=this.bootmagic`|
>>|**Quirk** | `=this.bootquirk`|
>>| **Rank** | `=this.bootrank` |
>>| **Notes** | `=this.bootnotes` |
>> &nbsp;
>>
>>### Ring 1
>>| | |
>>|--- | --- |
>>|**Name** | `=this.ring1name`|
>>|**Magic** | `=this.ring1magic`|
>>|**Quirk** | `=this.ring1quirk`|
>>| **Rank** | `=this.ring1rank` |
>>| **Notes** | `=this.ring1notes` |
>> &nbsp;
>>
>>### Ring 2
>>| | |
>>|--- | --- |
>>|**Name** | `=this.ring2name`|
>>|**Magic** | `=this.ring2magic`|
>>|**Quirk** | `=this.ring2quirk`|
>>| **Rank** | `=this.ring2rank` |
>>| **Notes** | `=this.ring2notes` |
>> &nbsp;
>>
>>### Pendant
>>| | |
>>|--- | --- |
>>|**Name** | `=this.pendantgearname`|
>>|**Magic** | `=this.pendantgearmagic`|
>>|**Quirk** | `=this.pendantgearquirk`|
>>| **Rank** | `=this.pendantgearrank` |
>>| **Notes** | `=this.pendantgearnotes` |

---

>[!table] %%FAKE TITLE HERE%%
>>[!table] %%FAKE TITLE HERE%%
>>## Hearts
>>| | | ||
>>| ---------- | -------- |---------- | -------- |
>>| `INPUT[toggle:heart1]` | Arcane | `INPUT[toggle:heart7]` | Elemental | 
>>| `INPUT[toggle:heart2]` | Arrow |`INPUT[toggle:heart8]` | Might |
>>| `INPUT[toggle:heart3]` | Bastion |`INPUT[toggle:heart9]` | Restoration |
>>| `INPUT[toggle:heart4]` | Blade | `INPUT[toggle:heart10]` | Ritual |
>>| `INPUT[toggle:heart5]` | Death |  `INPUT[toggle:heart11]` | Shadow |
>>| `INPUT[toggle:heart6]` | Devastation | `INPUT[toggle:heart12]` | Time |
>>
>>&nbsp;
>>
>> #### Passive Skills
>> |        |         |   
>>| :-: | :------------- |
>>| 1 | `=this.passive0` |
>>| 2 | `=this.passive1` |
>>| 3 | `=this.passive2` |
>>| 4 | `=this.passive3` |

---

>[!crafting] %%FAKE TITLE HERE%%
>>[!crafting] %%FAKE TITLE HERE%%
>>### Heart Abilities
>> 
>>`=this.HeartAbLink1`
>>
>>
>>&nbsp;
>> 
>>
>>---
>>
>>&nbsp;
>>
>> 
>>`=this.HeartAbLink2`
>>
>>
>>&nbsp;
>> 
>>
>>---
>>
>>&nbsp;
>>
>> 
>>`=this.HeartAbLink3`
>>
>>
>>&nbsp;
>> 
>>
>>---
>>
>>&nbsp;
>>
>> 
>>`=this.HeartAbLink4`
>>
>>
>>&nbsp;
>> 
>>
>>---
>>
>>&nbsp;
>>
>> 
>>`=this.HeartAbLink5`
>>
>>
>>&nbsp;
>> 
>>
>>---
>>
>>&nbsp;
>>
>>`=this.HeartAbLink6`
>>
>>
>>&nbsp;
>> 
>>
>>---
>>
>>&nbsp;
>>
>>`=this.HeartAbLink7`
>>
>>
>>&nbsp;
>> 
>>
>>---
>>
>>&nbsp;
>>
>>`=this.HeartAbLink8`
>>
>>&nbsp;
>> 
>>
>>---
>>
>>&nbsp
>>
>>`=this.HeartAbLink9`
>>
>>
>>&nbsp;
>> 
>>
>>---
>>
>>&nbsp;
>>
>>`=this.HeartAbLink10`
>>
>>
>>&nbsp;
>> 
>>
>>---
>>
>>&nbsp;
>>
>>#### Character Appearance
>>`INPUT[textArea:Appearance1]`





```meta-bind-button
label: Add
icon: ""
style: primary
class: ""
cssStyle: ""
backgroundImage: ""
tooltip: ""
id: addaetheryte
hidden: True
actions:
- type: updateMetadata
  bindTarget: aetheryte
  evaluate: True
  value: getMetadata('aetheryte') + getMetadata('aaetheryte')

```




