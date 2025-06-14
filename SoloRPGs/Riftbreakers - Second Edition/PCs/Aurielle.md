---
Art: "![[GoblinGirl_Token.webp|center]]"
Title: 
achievement_prog: "Riftbreaker: Successfully close 5 Rifts."
Protection: D4+1
Weapon1: Longsword
Weapon1dmg: D6+2
Weapon1type: Slashing
Weapon1notes: Versatile(2D6), Parry(10)
Weapon2: 
Weapon2dmg: 
Weapon2type: 
Weapon2notes: 
Weapon3: 
Weapon3type: 
Weapon3dmg: 
Weapon3notes: 
achievement_path: Path of the Explorer
aetheryte: 75
aaaetheryte: 0
aaetheryte: 
gems: 
Armor1: Hard Leather
Armor1rate: D4+1
Armor1notes: "Max Integrity: D8"
hand1: ""
hand2: ""
hand3: ""
hand4: ""
hand5: ""
quest1: "**Monster Hunt**: The quest is to hunt a Luminous Lizard that as been terrorizing near by villages at night. Distance: 8 Hexes. Rewards: 200⟑"
quest1t: false
quest2: "**Rift Closure:** Distance: 19 Hexes Rift Dominion: Sky Islets Rewards: 1x Random Magic Item"
quest2t: false
quest3: "**Rift Closure:** A Rift appeared one night and is spewing out monstrosities! Distance: 6 Hexes. Rift Dominion:  Primordial Forest Rewards: 1x Random Magic Item"
quest3t: 
quest4: "**Patrol:** A patrol duty to check the far reaches for new Rifts. Need the new lay abouts to take on some responsibility around here. Distance: 19 Hexes. 3x Skill Books"
quest4t: 
quest5: "**Rift Closure:** A Rift appeared down by the ol' mill! Jessup damn near got eaten! Distance: 16 Hexes. Rift Dominion: Lava FieldsRewards: 1x Random Formula or Blueprint"
quest5t: 
quest6: "Delivery: Mineral Ingredients x11 Reward: 3x Skill Books"
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
ring2notes: 
pendantgearname: Amulet of Eagle Eyes
pendantgearmagic: +10 Perception and +5 to Luck
pendantgearquirk: Covered in intricate runes.
pendantgearnotes: 
title1: Tent
title2: Torches U12
title3: (Rare) Greatsword
title4: (Epic) Item
title5: (Uncommon) Amulet
title6: (Uncommon) Ring
title7: (Epic) Magic Item
title8: (Uncommon) Ring
title9: ""
title10: ""
title11: ""
title12: ""
title13: ""
proficiency1: Longsword
proficiency2: Hard Leather
proficiency3: Mail
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
gear1: Bandages UD12
gear2: "Potion of Liquid Shadows: You are immediately Concealed. "
Appearance1: ""
Integrity1: D8
heart8: true
heart9: true
reputation_rank: Initiate
gear3: Rope
CurrentAether: 10
skill6: false
hp: 26
modifier: 0
gear4: Sickle
skill5: false
gear5: Crowbar
Bandage: D12
torch1: D12
qbelt1: Potion of Minor Healing
qbelt2: Potion of Minor Healing
gear6: "Hunting Knife "
gear7: Pickaxe
gear9: ""
gear10: ""
Pskills69: Backpack
skill1: false
RiftLord: D6
ac: "4"
skill19: false
heart5: true
heart1: true
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
>>  **Achievement in Progress** |`=this.achievement_prog` `boxes: 0/5` |
>> **Ability Pool** | Used: `6` **Max:** `21` |
>> **Reputation** | `1` `INPUT[suggester(option(Initiate), option(Journeyman), option(Vanguard), option(Champion), option(High Warden)):reputation_rank]` |
>> **HP** | **Current:**`22` **Max:** `26`
>> **Luck** | `5` |
>> **Parry** | `10` |
>> **Max Aether** | `10` |
>> **Protection** | `=this.Protection` |
>>
>> &nbsp;
>> 
>>  ##### Wealth
>>|  |   |
>>| :-: | :-: |
>>|**Aetheryte** |`=this.aetheryte`**⟑**|
>>| **Crystals** | `=this.gems`   |
>>| **Add Aetheryte** | `INPUT[number:aaetheryte]` `BUTTON[addaetheryte]`|
>>
>> &nbsp;
>> 
>> 
>> ##### Weapons
>>| **Weapons** | **Skill** | **Damage** | **Notes** |
>>| :-: | :-: | :-: | :-: |
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
>>|  <font color="#00CCFF">Ore</font>  | `0`  | `0`  | `1`   | 
>>
>> &nbsp;
>>
>> ##### Supplies
> |  | 
>>|---|---
>>|**Torches / Lamp Oil**| `INPUT[inlineSelect(option(D12), option(D10), option(D8), option(D6), option(D4), option(None)):torch1]` |
>>|**Bandages**|`INPUT[inlineSelect(option(D12), option(D10), option(D8), option(D6), option(D4), option(None)):Bandage]` |
>>|**RiftLord Timer**|`INPUT[inlineSelect(option(D8), option(D6), option(D4), option(None)):RiftLord]` |
>>
>> &nbsp;
>>

---

>[!table] %%FAKE TITLE HERE%%
>>[!gather] %%FAKE TITLE HERE%%
>>
>> ### Skill Checks
>>| **Skill Name** | **Skill Level**| **Gear Mod** | **Skill Up**
>>| ------------------------- | ----------- | -----------| ----------- |
>>| **Agility** (10) | `31` |  `0` | `INPUT[toggle:skill1]`|
>>| **Alchemy** | `30` |`0` | `INPUT[toggle:skill2]`|
>>| **Animal Handling** | `0` | `0` |`INPUT[toggle:skill3]`|
>>| **Armorsmithing** | `10` |`0` | `INPUT[toggle:skill4]`|
>>| **Athletics** (10) | `28` |`0` |`INPUT[toggle:skill5]`|
>>| **Bladed Weapons** | `66` |`0` |`INPUT[toggle:skill6]`|
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
>>| **Perception (20)** | `34` |`10` |`INPUT[toggle:skill19]`
>>| **Performance** | `0` |`0` |`INPUT[toggle:skill20]`
>>| **Ranged Weapons** | `40` |`0` |`INPUT[toggle:skill21]`
>>| **Reason (10)** | `10` |`0` |`INPUT[toggle:skill22]`
>>| **Sailing** | `0` |`0` |`INPUT[toggle:skill23]`
>>| **Shafted Weapons** | `0` |`0` |`INPUT[toggle:skill24]`
>>| **Sleight of Hand** | `0` |`0` |`INPUT[toggle:skill25]`
>>| **Stealth** | `10` |`0` |`INPUT[toggle:skill26]`
>>| **Survival** | `40` |`0` |`INPUT[toggle:skill27]`
>>| **Tenacity (10)** | `40` |`0` |`INPUT[toggle:skill28]`
>>| **Unarmed Combat (10)** |`10` | `0` |`INPUT[toggle:skill29]`
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
>>| `=this.quest1` | `INPUT[toggle:quest1t]` | `boxes: 0/16`
>> |`=this.quest2` |`INPUT[toggle:quest2t]` |  `boxes: 0/19`
>>| `=this.quest3` | `INPUT[toggle:quest3t]` | `boxes: 6/6`
>> |`=this.quest4` |`INPUT[toggle:quest4t]` | `boxes: 0/19`
>>| `=this.quest5` | `INPUT[toggle:quest5t]` | `boxes: 0/16`
>> |`=this.quest6` |`INPUT[toggle:quest6t]` | `0`
>>| `=this.quest7` | `INPUT[toggle:ques71t]` | `0`
>> |`=this.quest8` |`INPUT[toggle:quest8t]` | `0`
>>| `=this.quest9` | `INPUT[toggle:ques91t]` | `0`
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
>>|10|`INPUT[text:gear10]` || [[Aurielle's Large Spatial Bag]]|
>>
>>
>>### Backpack 
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

---

>[!thing] %%FAKE TITLE HERE%%
>>[!travel] %%FAKE TITLE HERE%%
>>## Gear
>>
>> &nbsp;
>>
>>### Head
>>| | |
>>|--- | --- |
>>|**Name** | `=this.headname`|
>>|**Magic** | `=this.headmagic`|
>>|**Quirk** | `=this.headquirk`|
>>| **Notes** | `=this.headnotes` |
>>
>>&nbsp;
>>### Chest
>>| | |
>>|--- | --- |
>>|**Name** | `=this.chestname`|
>>|**Magic** | `=this.chestmagic`|
>>|**Quirk** | `=this.chestquirk`|
>>| **Notes** | `=this.chestnotes` |
>> &nbsp;
>>
>>### Belt
>>| | |
>>|--- | --- |
>>|**Name** | `=this.beltname`|
>>|**Magic** | `=this.beltmagic`|
>>|**Quirk** | `=this.beltquirk`|
>>| **Notes** | `=this.beltnotes` |
>> &nbsp;
>>
>>### Pants
>>| | |
>>|--- | --- |
>>|**Name** | `=this.pantsname`|
>>|**Magic** | `=this.pantsmagic`|
>>|**Quirk** | `=this.pantsquirk`|
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
>>| **Notes** | `=this.bootnotes` |
>> &nbsp;
>>
>>### Ring 1
>>| | |
>>|--- | --- |
>>|**Name** | `=this.ring1name`|
>>|**Magic** | `=this.ring1magic`|
>>|**Quirk** | `=this.ring1quirk`|
>>| **Notes** | `=this.ring1notes` |
>> &nbsp;
>>
>>### Ring 2
>>| | |
>>|--- | --- |
>>|**Name** | `=this.ring2name`|
>>|**Magic** | `=this.ring2magic`|
>>|**Quirk** | `=this.ring2quirk`|
>>| **Notes** | `=this.ring2notes` |
>> &nbsp;
>>
>>### Pendant
>>| | |
>>|--- | --- |
>>|**Name** | `=this.pendantgearname`|
>>|**Magic** | `=this.pendantgearmagic`|
>>|**Quirk** | `=this.pendantgearquirk`|
>>| **Notes** | `=this.pendantgearnotes` |
>>
>> &nbsp;
>>

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
>>| 11         |  [[Cleave]]  |
>>| 12         | [[Holy Weapon]]  |


>[!rng] %%FAKE TITLE HERE%%
>>[!rng] %%FAKE TITLE HERE%%
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




