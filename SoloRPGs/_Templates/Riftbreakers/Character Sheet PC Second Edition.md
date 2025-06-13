---
Art: "![[Riftbreaker_Female.webp|600]]"
Title: Protector of Kar Helos
achievement_prog: Achievement in Progress Example
Protection: D4+3
Weapon1: Holy Longbow of the Bear
Weapon1dmg: 2D6+4
Weapon1type: Piercing
Weapon1notes: Two-handed, Holy, Arrows UD12, Range 115 m
Weapon2: Scimitar
Weapon2dmg: D8+4
Weapon2type: Slashing
Weapon2notes: Parry, Finesse
Weapon3: 
Weapon3type: 
Weapon3dmg: 
Weapon3notes: 
achievement_path: Path of the Explorer
aetheryte: 14
aaaetheryte: 0
aaetheryte: 
gems: 
quest1: "**Rift Closure:** Travel 14 days and close the marked rift. (Sky Islets)."
quest1t: false
quest2: "**Escort:** a caravan distance is 22 travel days."
quest2t: 
quest3: "**Patrol:** Patrol the perimeter and wilds for 17 days. Mark any rifts found with a beacon. Roll a d10 each day, on a 1 or 2, there is a rift."
quest3t: 
quest4: "**Collect:** deliver 22 Chitinous Plate."
quest4t: 
quest5: "**Rift Closure:** Travel 14 days and close the marked rift. (Timeworn Ruins)."
quest5t: 
quest6: "**Patrol:**the perimeter and wilds for 11 days. Mark any rifts found with a beacon. Roll a d10 each day, on a 1 or 2, there is a rift."
quest6t: 
quest7: "**Collect:** deliver 13 Fiery Ember."
quest7t: 
quest8: "**Escort:** a caravan distance is 21 travel days."
quest9: "**Monster Hunt:** Travel 7 days and search for the monster. The type of monster is determined by the region."
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
bootname: Victorious Gloves of the Whisper
bootmagic: Constitution +1 Charisma +1
bootquirk: Smells like rotten flesh
bootrank: Novice
bootnotes: 200A, Air Earth
ring1name: Champion's Ring of the Snake
ring1magic: Dexterity +1, Reduce your Stamina pool by 5 (26), but increase your Aether pool by 8 (23). You no longer need to eat or drink.
ring1quirk: It's always pristine
ring1rank: Novice
ring1notes: 300A Air Life 2x Boon Bane
ring2name: Mage's Wonderful Ring
ring2magic: Stamina +8, On command, this item works as a source of light. Illuminates in a 20 m. radius.
ring2quirk: It's always covered in a layer of mucus
ring2rank: Novice
ring2notes: 300A Fire 2xPower Light
pendantgearname: Knight's Glass Stone
pendantgearmagic: You can detect all living beings in a 20 m. radius. Increase your luck by +5
pendantgearquirk: It appears to be completely made of glass. It doesn't make it more fragile than it should be though
pendantgearrank: Novice
pendantgearnotes: Chaos Life Boon Light 200A  Rarity:Uncommon
title1: Backpack
title2: Extra-Dimensional bag x 0
title3: Quiver
title4: Bandage Ud12
title5: Arrows ud12
title6: Rations x 2
title7: Torch Ud10
title8: ""
title9: ""
title10: ""
title11: ""
title12: ""
title13: ""
proficiency1: Longbow
proficiency2: Scimitar
proficiency3: Soft Leather
title21: ""
title15: ""
Hearts:
  - Restoration
  - Arrow
  - Ritual
  - Elemental
passive0: "**Restoration Heart**: *Dampening Aura* Reduce all incoming damage by -1 to all allies in a 10 m radius."
passive1: "**Arrow Heart**: *Marksman* You suffer no penalty from firing a ranged weapon at melee range. Increase the range of your equipped ranged weapons by +50 m."
passive2: "**Ritual Heart**: *Arcane Storage* You can summon a chest that has 10 item slots. This power gains +10 item slots per rank."
Heart1: []
Heart2: Elemental
Heart3: Restoration
Heart4: Ritual
HeartAbLink1: "![[Cleave]]"
HearAb1: Novice
HeartAbRank1: Novice
Heartexp1: 
gear1: ""
gear2: ""
Appearance1: |-
  Glowing Eyes: Your eyes glow faintly in the dark, with colors ranging from eerie white to deep crimson or electric blue.
  Translucent Skin: Your skin is semi-transparent, revealing faint outlines of your veins, muscles, or even bones beneath.
  Hair: Purple
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
>> **Reputation** | `0` |
>> **HP** | **Current:**`32` **Max:** `32`
>> **Luck** | `0` |
>> **Parry** | `0` |
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
>>|**Rations**|`9` |
>>|**Torches / Lamp Oil**| `INPUT[inlineSelect(option(D12), option(D10), option(D8), option(D6), option(D4), option(None)):torch1]` |
>>|**Bandages**|`INPUT[inlineSelect(option(D12), option(D10), option(D8), option(D6), option(None)):Bandage]` |
>>|**RiftLord Timer**|`INPUT[inlineSelect(option(D10), option(D8), option(D6), option(None)):RiftLord]` |
>>
>> &nbsp;
>>

---

>[!gather] %%FAKE TITLE HERE%%
>>[!gather] %%FAKE TITLE HERE%%
>>
>> ### Skill Checks
>>| **Skill Name** | **Skill Level**| **Gear Mod** | **Skill Up**
>>| ------------------------- | ----------- | -----------| ----------- |
>>| **Agility** (10) | `25` |  `0` | `INPUT[toggle:skill1]`|
>>| **Alchemy** | `30` |`0` | `INPUT[toggle:skill2]`|
>>| **Animal Handling** | `0` | `0` |`INPUT[toggle:skill3]`|
>>| **Armorsmithing** | `10` |`0` | `INPUT[toggle:skill4]`|
>>| **Athletics** (10) | `24` |`0` |`INPUT[toggle:skill5]`|
>>| **Bladed Weapons** | `64` |`0` |`INPUT[toggle:skill6]`|
>>| **Bludgeoning Weapons**  | `0` |`0` |`INPUT[toggle:skill7]`|
>>| **Cooking**  | `15` |`0` |`INPUT[toggle:skill8]`|
>>|**Command** | `0` | `0` |`INPUT[toggle:skill9]`|
>>| **Endurance (10)**  | `25` |`0` |`INPUT[toggle:skill10]`
>>| **Gathering**  | `30` |`0` |`INPUT[toggle:skill11]`
>>| **Insight**  | `0` |`0` |`INPUT[toggle:skill12]`
>>| **Jewelcrafting** | `0` |`0` |`INPUT[toggle:skill13]`
>>| **Literacy**| `40` |`0` |`INPUT[toggle:skill14]`
>>| **Lockpicking** | `0` |`0` |`INPUT[toggle:skill15]`
>>| **Manipulation** | `0` |`0` |`INPUT[toggle:skill16]`
>>| **Medicine**  | `15` |`0` |`INPUT[toggle:skill17]`
>>| **Nature**  | `0` |`0` |`INPUT[toggle:skill18]`
>>| **Perception (20)** | `30` |`0` |`INPUT[toggle:skill19]`
>>| **Performance** | `0` |`0` |`INPUT[toggle:skill20]`
>>| **Ranged Weapons** | `40` |`0` |`INPUT[toggle:skill21]`
>>| **Reason (10)** | `10` |`0` |`INPUT[toggle:skill22]`
>>| **Sailing** | `0` |`0` |`INPUT[toggle:skill23]`
>>| **Shafted Weapons** | `0` |`0` |`INPUT[toggle:skill24]`
>>| **Sleight of Hand** | `0` |`0` |`INPUT[toggle:skill25]`
>>| **Stealth** | `10` |`0` |`INPUT[toggle:skill26]`
>>| **Survival** | `40` |`0` |`INPUT[toggle:skill27]`
>>| **Tenacity (10)** | `40` |`0` |`INPUT[toggle:skill28]`
>>| **Unarmed Combat (10)** |`0` | `10` |`INPUT[toggle:skill29]`
>>| **Weaponsmithing** | `0` |`0` |`INPUT[toggle:skill30]`
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

---

>[!table_time] %%FAKE TITLE HERE%%
>>[!table_time] %%FAKE TITLE HERE%%
>>```meta-bind
>>INPUT[progressBar(class(blue-progress-bar), maxValue(10), title(Aether)):CurrentAether]
>>```
>>
>> &nbsp;
>>
>>### Ability Loadout
>>| Slot | Ability Loadout  |
>>| ---------- | -------- |
>>| 1          | [[Weapon Strike (Two-Handed)]]     |
>>| 2          | [[Weapon Strike (Two-Handed)]]      |
>>| 3          | [[Weapon Strike (Two-Handed)]]    |
>>| 4          | [[Summon Companion]]     |
>>| 5          | [[Unbound Fury]]   |
>>| 6          | [[Unbound Fury]] |
>>| 7          | [[Divine Shield]]     |
>>| 8          | [[Two-Handed Weapon Master]]  |
>>| 9          | [[Two-Handed Weapon Master]]   |
>>| 10         | [[Two-Handed Weapon Master]]  |
>>| 11         |   [[Holy Weapon]]  |
>>| 12         | [[Holy Weapon]]  |




>[!table] %%FAKE TITLE HERE%%
>>[!table] %%FAKE TITLE HERE%%
>>## Hearts
>>| | | ||
>>| ---------- | -------- |---------- | -------- |
>>| `INPUT[toggle:heart1]` | <font color="#00CAFF">Arcane</font> | `INPUT[toggle:heart7]` | <font color="#FB5607">Elemental</font> | 
>>| `INPUT[toggle:heart2]` | <font color="#1A7431">Arrow</font> |`INPUT[toggle:heart8]` | <font color="#FF073A">Might</font> |
>>| `INPUT[toggle:heart3]` | <font color="#00FFCC">Bastion</font> |`INPUT[toggle:heart9]` | <font color="#11FF00">Restoration</font> |
>>| `INPUT[toggle:heart4]` | <font color="#FF006E">Blade</font> | `INPUT[toggle:heart10]` | <font color="#2A9D8F">Ritual</font> |
>>| `INPUT[toggle:heart5]` | <font color="#8624FF">Death Heart</font> |  `INPUT[toggle:heart11]` | <font color="#2D00F7">Shadow</font> |
>>| `INPUT[toggle:heart6]` | <font color="#D100D1">Devastation</font> | `INPUT[toggle:heart12]` | <font color="#FFFF00">Time</font> |
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
>>[!cite] %%FAKE TITLE HERE%%
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




