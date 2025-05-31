---
Art: "![[Riftbreaker_Female.webp|600]]"
Title: Protector of Kar Helos
STR: 18
DEX: 14
CON: 13
INT: 12
WIL: 15
CHA: 11
Luck: 0
Armor: D4
Weapon1: Battleaxe
Weapon1dmg: 3D6+3
Weapon1type: Slashing
Weapon1notes: Two-Handed
Weapon2: Traveler's Shortbow
Weapon2dmg: D6+1
Weapon2type: Piercing
Weapon2notes: Ud12 Arrows
Weapon3: 
Weapon3type: 
Weapon3dmg: 
Weapon3notes: 
rank: Apprentice
axp: 
xp: 250
a-N: 65
a-a: 
a-V: 
a-M: 
quest1: "**Patrol** the perimeter and wilds for 16 days. Mark any rifts found with a beacon. Roll a d10 each day, on a 1 or 2, there is a rift."
quest1t: 
quest2: 
quest2t: 
quest3: "**Rift Closure**  Travel 10 days and close the marked rift. (Underground Cave System)."
quest3t: 
quest4: "**Rift Closure** Travel 14 days and close the marked rift. (Thousand Islands)."
quest4t: 
quest5: "**Delivery** Collect and deliver - 10 Moonstone Shard."
quest5t: 
quest6: "**Monster Hunt** Travel 7 days and search for the monster. The type of monster is determined by the region."
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
chestname: Mage's Soft Leather
chestAR: D4
chestint: D8
chestrank: Novice
chestmagic: You can speak with other party members up to a distance of 1 km. Increase your daily healing rate to 10 Health. Increase integrity die
chestquirk: It's always covered in a layer of mucus
chestnotes: "300⟑, Aspects: Air Earth Power Life Dark"
beltname: 
beltmagic: 
beltquirk: 
beltnotes: 
pantsname: 
pantsmagic: 
pantsquirk: 
pantsnotes: 
glovesname: 
glovesmagic: 
glovesquirk: 
glovesrank: 
glovesnotes: 
bootname: 
bootmagic: 
bootquirk: 
bootrank: 
bootnotes: 
ring1name: 
ring1magic: 
ring1quirk: 
ring1rank: 
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
title1: Backpack
title2: Ration
title3: Simple Healing Potion
title4: Bandage Ud8
title5: Torch Ud8
title6: Heart - Restoration
title7: "Holy Aetheric Glaive "
title8: Glorious Gloves of the Dog
title9: "Potion of Stoneskin. For the next hour you have +1 Armor, but your Dodge and Acrobatics skills are reduced by -10. Aspects: Stone, Boon"
title10: ""
title11: ""
title12: ""
title13: ""
proficiency1: Battleaxe
proficiency2: Soft Leather
proficiency3: Long Bow
title21: ""
title15: ""
Hearts:
  - Restoration
  - Arrow
  - Ritual
  - Elemental
passive0: "**Combat Mastery** You can disengage from combat at will, without requiring a Coordination check. Opponents cannot disengage from combat when facing you, unless you let them."
passive1: "**Lord of the Dead** All your checks against Undead gain +20 bonus and all Undead’s checks against you gain -20 penalty."
passive2: 
Heart1: Might
Heart2: Death
Heart3: None
Heart4: None
title14: 
HeartAbLink1: "![[Cleave]]"
HearAb1: Novice
HeartAbRank1: Novice
Heartexp1: 
HeartAbLink2: "![[Two-Handed Weapon Master]]"
HeartAbRank2: Novice
HeartAbLink3: "![[Drain Lifeforce]]"
HeartAbLink4: "![[Death Bolt]]"
HeartAbRank4: Novice
torch1: D8
Bandage: D8
HeartAbRank3: Novice
integrity1: D8
ac: "4"
hp: 32
level: 1
modifier: 0
RiftLord: D10
---
>[!dice] %%FAKE TITLE HERE%%
>>[!dice] %%FAKE TITLE HERE%% 
>> # `=this.file.name`
>> `=this.Art`
>> 
>>  |
>> ---|---|
>> **Rank** |`INPUT[suggester(option(Novice), option(Apprentice), option(Veteran), option(Master)):rank]` |
>>  **Title** |`=this.Title` |
>> **Reputation** | `0` |
>>  **HP** | **Current:**`39` **Max:** `=this.CON*3`
>> **Aether** | `35` **Max:** `VIEW[{WIL} + {INT} + 8]` |
>> **Stamina** | `29` **Max:** `VIEW[{STR} + {CON}+ 8]` |
>> **Max Gear Slots** | `=this.STR+10` |
>> **XP** | `VIEW[{xp}][text]`
>>
>>---
>> **ADD XP:** `INPUT[number:axp]` `BUTTON[exp]`
>>
>>
>> &nbsp;
>>
>> ##### Weapons
>>| **Weapons** | **Type** | **Damage** | **Notes** |
>>| ------ | :-: | :-: | --------- |
>>| `=this.Weapon1` | `=this.Weapon1type` | `=this.Weapon1dmg` |`=this.Weapon1notes` |
>>| `=this.Weapon2` | `=this.Weapon2type` |`=this.Weapon2dmg` | `=this.Weapon2notes` |
>>| `=this.Weapon3` | `=this.Weapon3type`|`=this.Weapon3dmg` | `=this.Weapon3notes` |
>>
>> &nbsp;
>>
>> ##### Armor
>>| **Armor** | **Armor Rating** | **Integrity**|
>>| ---------------------- | :----------: |:------: |
>>| `=this.chestname` | `=this.chestAR` | `INPUT[inlineSelect(option(D12), option(D10), option(D8), option(D6), option(D4), option(None)):integrity1]` |
>>| `=this.Armor2` | `=this.Armor2DL` |`INPUT[inlineSelect(option(D12), option(D10), option(D8), option(D6), option(D4), option(None)):integrity2]`|
>>
>> &nbsp;
>>
>> ##### Crafting Aspects
>>| **Air**   | **Bane** | **Boon** | **Chaos** | **Dark**  | **Death** |
>>| :-: | :-: | :-: | :-: | :-: | :-: |
>>| `2`   | `0`  | `0`  | `0`   | `1`   |`0`  |
>>| **Earth** | **Fire** | **Life** | **Light** | **Power** | **Water** |
>| `0`  | `0` | `0`  | `0`   | `0`  | `0`  |
>> &nbsp;
>>
>>##### Minerals
>>
>>| **Coal** | **Iron** | **Silver** | **Aglite** |
>>| :-: | :-: | :-: | :-: |
>>| `0`  | `0`  | `0`   | `0`   |
>> &nbsp;
>>
>>  ##### Currency
>>| **⟑-N** | **⟑-A**   |
>>| :-: | :-: |
>>|`=this.a-N`|`=this.a-a`|
>>| **⟑-V** | **⟑-M**   |
>>|`=this.a-V`|`=this.a-M`|
>>|**Rations**|`9` |
>>|**Torches / Lamp Oil**| `INPUT[inlineSelect(option(D12), option(D10), option(D8), option(D6), option(D4), option(None)):torch1]` |
>>|**Bandages**|`INPUT[inlineSelect(option(D12), option(D10), option(D8), option(D6), option(None)):Bandage]` |
>>|**RiftLord Timer**|`INPUT[inlineSelect(option(D10), option(D8), option(D6), option(None)):RiftLord]` |

>[!gather] %%FAKE TITLE HERE%%
>>[!gather] %%FAKE TITLE HERE%%
>> ### Stats
>> | | | | |
>>| ---- | ---- | ------ | ------ |
>>| **Strength** | `=this.STR` | **Brawn** | `=this.STR*5` |
>>| **Dexterity** | `=this.DEX`| **Coordination** | `=this.DEX*5` |
>>| **Constitution** |`=this.CON` | **Vitality** |`=this.CON*5` |
>>| **Will** | `=this.WIL` | **Tenacity** |`=this.WIL*5` |
>>| **Intelligence** | `=this.INT` | **Intellect** | `=this.INT*5` |
>>| **Charisma** | `=this.CHA` | **Charm** | `=this.CHA*5` |
>>| **STR Damage** |+`=floor((this.STR - 10)/2.5)` | **DEX Damage** |+`=floor((this.DEX - 10)/2.5)` |
>>| **Luck** | `=this.Luck` | **WIL Damage** | +`=floor((this.WIL - 10)/2.5)` |
>>| **Speed** | **Walk**: `=this.DEX` **Run**: `=this.DEX*2`| **Persistence** | `=floor((this.WIL+this.CHA)/2*5)` |
>
>>[!gather] %%FAKE TITLE HERE%%
>> ### Skill Checks
>>| **Skill Name** | **Skill Level** | **Skill Name** | **Skill Level** |
>>| --- | :-: |--- | :-: |
>>| **Alchemy** (INT `=this.INT`) | `32` | **Leatherworking** (DEX `=this.DEX`) | `14`|
>>| **Acrobatics** (DEX `=this.DEX`) |`34` |**Literacy** (INT `=this.INT`) | `52` |
>>| **Animal Handling** (CHA `=this.CHA`) | `11` |**Insight** (WIL `=this.WIL`) | `15` |
>>| **Athletics** (STR `=this.STR`) | `38` | **Dodge** (DEX `=this.DEX`) | `76` |
>>| **Blacksmithing** (DEX `=this.DEX`) | `24` |**Perception** (WIL `=this.WIL`) | `45`|
>>| **Command** (CHA `=this.CHA`) | `11` | **Performance** (CHA `=this.CHA`)|`11`|
>>| **Gathering** (DEX `=this.DEX`) | `35` |**Sailing** (DEX `=this.DEX`) | `14` |
>>| **Nature** (INT `=this.INT`) | `32` |  **Sleight of Hand** (DEX `=this.DEX`) | `14` |
>>| **Manipulation** (CHA `=this.CHA`) | `11` | **Stealth** (DEX `=this.DEX`) | `14` |
>>| **Medicine** (INT `=this.INT`) | `22` |**Survival** (INT `=this.INT`) | `52` |
>
>>[!gather] %%FAKE TITLE HERE%%
>>### Proficiencies
>> | | |
>>|:-:| :---: |
>>| `=this.proficiency1` | `=this.proficiency2` |
>>| `=this.proficiency3` | `=this.proficiency4` |
>>| `=this.proficiency5` | `=this.proficiency6` |
>>| `=this.proficiency7` | `=this.proficiency8` |

>[!travel] %%FAKE TITLE HERE%%
>>[!gear] %%FAKE TITLE HERE%%
>>### Quests
>>|**Quest Description** |**Completed** | **Timer/Counter**|
>> |--- | :---: | :---------: |
>>| `=this.quest1` | `INPUT[toggle:quest1t]` | `0/16`
>> |`=this.quest2` |`INPUT[toggle:quest2t]` | `0/4`
>>| `=this.quest3` | `INPUT[toggle:quest3t]` | `10/10`
>> |`=this.quest4` |`INPUT[toggle:quest4t]` | `0/14`
>>| `=this.quest5` | `INPUT[toggle:quest5t]` | `0/10`
>> |`=this.quest6` |`INPUT[toggle:quest6t]` | `0/7`
>>| `=this.quest7` | `INPUT[toggle:ques71t]` | 
>> |`=this.quest8` |`INPUT[toggle:quest8t]` | 
>>| `=this.quest9` | `INPUT[toggle:ques91t]` | 
>> |`=this.quest10` |`INPUT[toggle:quest10t]` |

>[!table] %%FAKE TITLE HERE%%
>>[!table] %%FAKE TITLE HERE%%
>>### Inventory
>>| <span style="color:rgb(129, 216, 208)">Slot</span> | <span style="color:rgb(129, 216, 208)">Encumbering Items</span> | <span style="color:rgb(129, 216, 208)">Slot</span> | <span style="color:rgb(129, 216, 208)">Encumbering Items</span> 
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
>>|:-:|:-:|
>>|**Name** | `=this.chestname`|
>>|**Magic** | `=this.chestmagic`|
>>|**Quirk** | `=this.chestquirk`|
>>| **Rank** | `=this.chestrank` |
>>| **Notes** | `=this.chestnotes` |
>> &nbsp;
>>
>>### Belt
>>| | |
>>|:-:|:-:|
>>|**Name** | `=this.beltname`|
>>|**Magic** | `=this.beltmagic`|
>>|**Quirk** | `=this.beltquirk`|
>>| **Rank** | `=this.beltrank` |
>>| **Notes** | `=this.beltnotes` |
>> &nbsp;
>>
>>### Pants
>>| | |
>>|:-:|:-:|
>>|**Name** | `=this.pantsname`|
>>|**Magic** | `=this.pantsmagic`|
>>|**Quirk** | `=this.pantsquirk`|
>>| **Rank** | `=this.pantsrank` |
>>| **Notes** | `=this.pantsnotes` |
>> &nbsp;
>>
>>### Gloves
>>| | |
>>|:-:|:-:|
>>|**Name** | `=this.glovesname`|
>>|**Magic** | `=this.glovesmagic`|
>>|**Quirk** | `=this.glovesquirk`|
>>|**Rank** | `=this.glovesrank` |
>>|**Notes** | `=this.glovesnotes` |
>> &nbsp;
>>
>>### Boots
>>| | |
>>|:-:|:-:|
>>|**Name** | `=this.bootname`|
>>|**Magic** | `=this.bootmagic`|
>>|**Quirk** | `=this.bootquirk`|
>>| **Rank** | `=this.bootrank` |
>>| **Notes** | `=this.bootnotes` |
>> &nbsp;
>>
>>### Ring 1
>>| | |
>>|:-:|:-:|
>>|**Name** | `=this.ring1name`|
>>|**Magic** | `=this.ring1magic`|
>>|**Quirk** | `=this.ring1quirk`|
>>| **Rank** | `=this.ring1rank` |
>>| **Notes** | `=this.ring1notes` |
>> &nbsp;
>>
>>### Ring 2
>>| | |
>>|:-:|:-:|
>>|**Name** | `=this.ring2name`|
>>|**Magic** | `=this.ring2magic`|
>>|**Quirk** | `=this.ring2quirk`|
>>| **Rank** | `=this.ring2rank` |
>>| **Notes** | `=this.ring2notes` |
>> &nbsp;
>>
>>### Pendant
>>| | |
>>|:-:|:-:|
>>|**Name** | `=this.pendantgearname`|
>>|**Magic** | `=this.pendantgearmagic`|
>>|**Quirk** | `=this.pendantgearquirk`|
>>| **Rank** | `=this.pendantgearrank` |
>>| **Notes** | `=this.pendantgearnotes` |

>[!crafting] %%FAKE TITLE HERE%%
>>[!crafting] %%FAKE TITLE HERE%%
>>## Hearts
>> |        |     |   
>>| :-: | :----- |
>>| 1 | `INPUT[inlineSelect(option(None), option(Arcane), option(Arrow), option(Bastion), option(Blade), option(Death), option(Elemental), option(Might), option(Restoration), option(Ritual), option(Shadow)):Heart1]` |
>>| 2 |  `INPUT[inlineSelect(option(None), option(Arcane), option(Arrow), option(Bastion), option(Blade), option(Death), option(Elemental), option(Might), option(Restoration),  option(Ritual), option(Shadow)):Heart2]` |
>>| 3 |  `INPUT[inlineSelect(option(None), option(Arcane), option(Arrow), option(Bastion), option(Blade), option(Death), option(Elemental), option(Might), option(Restoration),  option(Ritual), option(Shadow)):Heart3]` |
>>| 4 |  `INPUT[inlineSelect(option(None), option(Arcane), option(Arrow), option(Bastion), option(Blade), option(Death), option(Elemental), option(Might), option(Restoration),  option(Ritual), option(Shadow)):Heart4]` |
>>
>>&nbsp;
>> #### Passive Skills
>> |        |         |   
>>| :-: | :------------- |
>>| 1 | `=this.passive0` |
>>| 2 | `=this.passive1` |
>>| 3 | `=this.passive2` |
>>| 4 | `=this.passive3` |
>>
>
>>[!crafting]  %%FAKE TITLE HERE%%
>>### Heart Abilities
>> 
>>`=this.HeartAbLink1`
>>
>>| | | |
>>|:-:|:----------:|:-----:|:---------------------:|
>>| **Rank** |  `INPUT[inlineSelect(option(Novice), option(Apprentice), option(Veteran), option(Master)):HeartAbRank1]` | **XP** |`INPUT[number:Heartexp1]`|
>>
>>&nbsp;
>> 
>>
>>---
>>
>>&nbsp
>>
>> 
>>`=this.HeartAbLink2`
>>
>>| | | |
>>|:-:|:----------:|:-----:|:---------------------:|
>>| **Rank** |  `INPUT[inlineSelect(option(Novice), option(Apprentice), option(Veteran), option(Master)):HeartAbRank2]` | **XP** |`INPUT[number:Heartexp2]`|
>>
>>&nbsp;
>> 
>>
>>---
>>
>>&nbsp
>>
>> 
>>`=this.HeartAbLink3`
>>
>>| | | |
>>|:-:|:----------:|:-----:|:---------------------:|
>>| **Rank** |  `INPUT[inlineSelect(option(Novice), option(Apprentice), option(Veteran), option(Master)):HeartAbRank3]` | **XP** |`INPUT[number:Heartexp3]`|
>>
>>&nbsp;
>> 
>>
>>---
>>
>>&nbsp
>>
>> 
>>`=this.HeartAbLink4`
>>
>>| | | |
>>|:-:|:----------:|:-----:|:---------------------:|
>>| **Rank** |  `INPUT[inlineSelect(option(Novice), option(Apprentice), option(Veteran), option(Master)):HeartAbRank4]` | **XP** |`INPUT[number:Heartexp4]`|
>>
>>&nbsp;
>> 
>>
>>---
>>
>>&nbsp
>>
>> 
>>`=this.HeartAbLink5`
>>
>>| | | |
>>|:-:|:----------:|:-----:|:---------------------:|
>>| **Rank** |  `INPUT[inlineSelect(option(Novice), option(Apprentice), option(Veteran), option(Master)):HeartAbRank5]` | **XP** |`INPUT[number:Heartexp5]`|
>>
>>&nbsp;
>> 
>>
>>---
>>
>>&nbsp
>>
>>
>>
>>
>>| | | |
>>|:-:|:----------:|:-----:|:---------------------:|
>>| **Rank** |  `INPUT[inlineSelect(option(Novice), option(Apprentice), option(Veteran), option(Master)):HeartAbRank6]` | **XP** |`INPUT[number:Heartexp6]`|
>>
>>&nbsp;
>> 
>>
>>---
>>
>>&nbsp
>>
>>
>>
>>
>>| | | |
>>|:-:|:----------:|:-----:|:---------------------:|
>>| **Rank** |  `INPUT[inlineSelect(option(Novice), option(Apprentice), option(Veteran), option(Master)):HeartAbRank7]` | **XP** |`INPUT[number:Heartexp7]`|
>>
>>&nbsp;
>> 
>>
>>---
>>
>>&nbsp
>>
>>
>>
>>
>>| | | |
>>|:-:|:----------:|:-----:|:---------------------:|
>>| **Rank** |  `INPUT[inlineSelect(option(Novice), option(Apprentice), option(Veteran), option(Master)):HeartAbRank8]` | **XP** |`INPUT[number:Heartexp8]`|
>>
>>&nbsp;
>> 
>>
>>---
>>
>>&nbsp
>>
>>
>>
>>
>>| | | |
>>|:-:|:----------:|:-----:|:---------------------:|
>>| **Rank** |  `INPUT[inlineSelect(option(Novice), option(Apprentice), option(Veteran), option(Master)):HeartAbRank9]` | **XP** |`INPUT[number:Heartexp9]`|
>>
>>&nbsp;
>> 
>>
>>---
>>
>>&nbsp
>>
>>
>>
>>
>>| | | |
>>|:-:|:----------:|:-----:|:---------------------:|
>>| **Rank** |  `INPUT[inlineSelect(option(Novice), option(Apprentice), option(Veteran), option(Master)):HeartAbRank10]` | **XP** |`INPUT[number:Heartexp10]`|
>>
>>&nbsp;
>> 
>>
>>---
>>


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


