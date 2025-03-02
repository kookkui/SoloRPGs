---
Art: "![[Character Image Placholder]]"
Corruption: 0
HP: 0
STR: 16
DEX: 15
CONST: 16
WIL: 14
INT: 13
CHA: 12
Weapon1: Longsword
Weapon1dmg: D8+1 Slashing
Weapon1notes: Parry, Versatile (d10)
Weapon2: Scimitar +1
Weapon2dmg: " D8+2 Slashing"
Weapon2notes: Parry
Weapon3: Bow +1
Weapon3dmg: D6+2 Piercing
Weapon3notes: Range 320', Two-Handed
Armor: Half Plate
ArmorPR: D8+1
Armorintegrity: D12
Armornote1: -20 Stealth
Shield: 
ShieldPR: 
Shieldintegrity: 
trinketslot: 
Currency: 215
shards: 110
csupplies: 12
rations: 9
water: 0
talent0: "**Sorcerer:** Start the game knowing an extra spell of your choice. Only new characters may pick this Talent."
talent1: "**Gifted - Dexterity:** You may re-roll any failed skill up rolls for skills associated with DEX."
Godshard: 
GodshardPassive: 
GodshardActive1: 
Spell1: Stitch Wound
Spell1pp: 4
Spell1idio: The spell’s effects are doubled, if applicable.
Spell1des: "Range: Touch / Resisted: No / Duration: Permanent \rThe target heals D6+5 HP.\r *Blood emerges from the sorcerer’s fingertips in the shape of a red thread, stitching up the target’s wounds.*"
Spell2pp: 
Spell2idio: 
Spell2des: 
Spell1mem: true
skill1: false
notes1: |-
  Captured by Nirena's Emissaries because "Our cause requires blood". After a year, I saw an opportunity and I took it to escape.

  I saw an opportunity and I took it (+5 Perception)
title1: Sturdy backpack
title21: ""
title2: Coins
title3: Rations
title4: Fishing Rod
skill21: false
lightsource: Ud12
title5: Thieves’ tools
skill10: true
title6: Shards
title7: Lantern
title8: Arrows Ud12
skill20: false
skill8: false
title9: Quiver
skill13: false
title10: Oil Ud12
skill5: false
title11: Lockpicks Ud12
title12: Tent
Pskills69: ""
title13: Potion of Frenzy 500Ҁ For the next D6 rounds you deal +5 damage, but you’re unable to defend in any way.
Pskills1: ""
title14: Rope 50'
title15: Crafting Supplies
title16: Crafting Supplies
necklaceslot: Earing that grants +10 Perception
ring1: Ring of Insulation that grants immunity to fire
Pskills2: ""
title17: Shards
title18: ""
Pskills3: ""
title19: ""
title20: ""
title22: ""
title23: ""
title24: ""
---
>[!dice] %%FAKE TITLE HERE%%
>>[!dice] %%FAKE TITLE HERE%%  
>> # `=this.file.name`
>> 
>>
>>![[SoloRPGs/_ Assets/SoloRPGs/Broken Shores/PCs/Krystyna/KrystynaN.jpg]]
>> 
>> ###### Stats
>>|     |     | 
>> |--- | --- | 
>>|**HP** | **Current:** `32` **Max:** `=this.CONST*2`|
>>|**Power Points** |  **Current:** `14`  **Max:** `=this.WIL`|
>> |**Speed** |  **Walk:** `=this.DEX*2`  **Run:** `=this.DEX*4` |
>>
>> ###### Weapons
>>| **Weapons** | **Damage** | **Notes** |
>>| ---------------------- | --------------- | ------------- |
>>| `=this.Weapon1` | `=this.Weapon1dmg` | `=this.Weapon1notes` |
>>| `=this.Weapon2` | `=this.Weapon2dmg` | `=this.Weapon2notes` |
>>| `=this.Weapon3` | `=this.Weapon3dmg` | `=this.Weapon3notes` |
>>|`=this.Weapon4` |`=this.Weapon4dmg` | `=this.Weapon4notes` |
>>| | | |
>> ###### Armor
>>| **Name** | **Protection Rate** | **Integrity** | **Notes**|
>>| ---------------------- | --------------- | ------------- | ------------- |
>>| `=this.Armor` | `=this.ArmorPR` | `=this.Armorintegrity` | `=this.Armornote1`
>>| `=this.Shield` | `=this.ShieldPR` | `=this.Shieldintegrity` |`=this.Armornote2`
>>| `=this.Helmet` | `=this.HelmetPR` | `=this.Helmetintegrity` |`=this.Armornote3`
>>| | | |
>>
>>##### Currency and Provisions
>>|     |     |
>> |:---: | :---: |
>>|**Coins (Ҁ)** |`=this.Currency` |
>>|**Shards** | `=this.shards`|
>> |**Crafting Supplies** |`18` |
>>| **Rations**   |  `10`   |
>>| **Water (Gal)** |  `=this.water`   |
>>| **Light Source Remaining** |`INPUT[suggester(option(None), option(Ud4), option(Ud6), option(Ud8), option(Ud10), option(Ud12)):lightsource]` |   |
>>| **Max Gear Slots**     | `=(this.STR)+10` | 
 >>|**Exploration Time**|`0/10`|

>[!todo] %%FAKE TITLE HERE%%
>>[!todo] %%FAKE TITLE HERE%%
>> #### Stats
>> | | | | |
>>| --- | --- | :--: | :---: |
>>| **Strength** | `=this.STR` | **Brawn** | `=(this.STR)*5`|
>> | `5/10` | | | |
>>| **Dexterity** | `=this.DEX` |**Coordination** | `=(this.DEX)*5`|
>> | `1/10` | | | |
>>| **Constitution** | `=this.CONST` | **Vitality**|`=(this.CONST)*5`|
>> | `1/10` | | | |
>>| **Will** | `=this.WIL` | **Tenacity**|`=(this.WIL)*5`|
>> | `1/10` | | | |
>>| **Intelligence** | `=this.INT` | **Intellect**|`=(this.INT)*5`|
>> | `0/10` | | | |
>>| **Charisma** | `=this.CHA` | **Charm**|`=(this.CHA)*5`|
>> | `0/10` | | | |
>>
>>&nbsp;
>>
>> #### Skill Checks
>>| **Skill Name** | **Skill Level** | **Level Up**
>>| --------------------- | ----------- | ----------- |
>>| **Acrobatics**(DEX `=this.DEX`) | `15` | `INPUT[toggle:skill1]`|
>>| **Athletics** (STR `=this.STR`) | `56` | `INPUT[toggle:skill2]`|
>>| **Animal Handling** (CHA `=this.CHA`) | `12` |`INPUT[toggle:skill3]`|
>>| **Command** (CHA `=this.CHA`) | `12` |`INPUT[toggle:skill4]`|
>>| **Crafting** (DEX `=this.DEX`) | `57` |`INPUT[toggle:skill5]`|
>>| **Dodge** (DEX `=this.DEX` ) | `55` |`INPUT[toggle:skill6]`|
>>| **Insight** (WIL `=this.WIL`) | `15` |`INPUT[toggle:skill7]`|
>>| **Literacy** (INT `=this.INT`) | `74` |`INPUT[toggle:skill8]`|
>>|**Manipulation** (CHA `=this.CHA`) | `14` | `INPUT[toggle:skill9]`|
>>| **Martial Weapons** (STR `=this.STR`) | `62` |`INPUT[toggle:skill10]`
>>| **Medicine** (INT `=this.INT`) | `23` |`INPUT[toggle:skill11]`
>>|**Nature** (INT `=this.INT`) | `23` |`INPUT[toggle:skill12]`
>>| **Perception** (WIL `=this.WIL`) (<font color="#FF00CC">+10</font>) | `46` |`INPUT[toggle:skill13]`
>>| **Performance** (CHA `=this.CHA`) | `12` |`INPUT[toggle:skill14]`
>>| **Ranged Weapons** (DEX `=this.DEX` ) | `35` |`INPUT[toggle:skill15]`
>>| **Sailing** (DEX `=this.DEX`) | `35` |`INPUT[toggle:skill16]`
>>| **Siege Weapons** (DEX `=this.DEX`) | `15` |`INPUT[toggle:skill17]`
>>| **Simple Melee Weapons** (STR `=this.STR`) | `16` |`INPUT[toggle:skill18]`
>>| **Sleight of Hand** (DEX `=this.DEX` ) | `15` |`INPUT[toggle:skill19]`
>>| **Stealth** (DEX `=this.DEX`) | `36` |`INPUT[toggle:skill20]`
>>| **Survival** (INT `=this.INT` ) | `34` |`INPUT[toggle:skill21]`
>>| **Unarmed** (STR `=this.STR`) | `16` |`INPUT[toggle:skill22]`
>>
>>&nbsp;
>>
>>#### Notes
>>`INPUT[textArea:notes1]`

>[!important] %%FAKE TITLE HERE%%
>>[!important] %%FAKE TITLE HERE%%
>>##### Godshard
>>|     |     |
>> |---- | ---------- |
>>|**Godshard** | `=this.Godshard`|
>>|**Passive Ability** |  `=this.GodshardPassive`|
>> |**Active Ability**  |  `=this.GodshardActive1` |
>> | **Active Ability**     | `=this.GodshardActive2` | 
>> |**Active Ability** | `=this.GodshardActive3` |
>> |**Active Ability** | `=this.GodshardActive4` |
>> |**Earth Essence** (+1 Armor) | `0/4` |
>> |**Fire Essence** (+1 Damage) | `0/4` |
>> |**Water Essence** (+2 HP) | `0/4` |
>> |**Air Essence** (+2 PP) | `0/4` |
>>
>>&nbsp;
>>
>>##### Misc. Gear
>> |        |         |   
>>| :-: | :-----: |
>>| **Trinket** | `=this.trinketslot` |
>>| **Boots** | `=this.bootsslot` |
>>| **Earing** | `=this.earingslot` |
>>| **Necklace/Pendant** | `=this.necklaceslot` |
>>| **Ring 1**| `=this.ring1` |
>>| **Ring 2**|`=this.ring2` |
>>
>>&nbsp;
>>
>>##### Talents
>> |        |         |   
>>| :-: | :----- |
>>| 1 | `=this.talent0` |
>>| 2 | `=this.talent1` |
>>| 3 | `=this.talent2` |
>>| 4 | `=this.talent3` |
>>| 5 | `=this.talent4` |
>>| 6 |`=this.talent5` |
>>| 7 | `=this.talent6` |
>>

>[!table] %%FAKE TITLE HERE%%
>>[!table] %%FAKE TITLE HERE%%
>>### Inventory
>>| **Slot** | **Encumbering Items** | **Slot** | **Encumbering Items** 
>>| :-: | :---------------- |--------|--------|
>>|1|`INPUT[text:title1]` |21|`INPUT[text:title21]`|
>>|2|`INPUT[text:title2]`|22|`INPUT[text:title22]`|
>>|3|`INPUT[text:title3]`|23|`INPUT[text:title23]`|
>>|4|`INPUT[text:title4]`|24|`INPUT[text:title24]`|
>>|5|`INPUT[text:title5]`|25|`INPUT[text:title25]`|
>>|6|`INPUT[text:title6]`|26|`INPUT[text:title26]`|
>>|7|`INPUT[text:title7]`|27|`INPUT[text:title27]`|
>>|8|`INPUT[text:title8]`|28|`INPUT[text:title28]`|
>>|9|`INPUT[text:title9]`|29|`INPUT[text:title29]`
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
>>
>> ### Non-Incumbering Items
>> |**Slot**| **Item** |**Slot**| **Item** 
>>| :-: | :---------------------------- |:-: | :---------------------------- |
>>| 1 | `INPUT[text:Pskills69]` | 9 | `INPUT[text:Pskills8]` |
>>| 2 | `INPUT[text:Pskills1]` | 10 | `INPUT[text:Pskills9]` |
>>| 3 | `INPUT[text:Pskills2]` |11 | `INPUT[text:Pskills10]` |
>>| 4 | `INPUT[text:Pskills3]` | 12 | `INPUT[text:Pskills11]` |
>>| 5 | `INPUT[text:Pskills4]` |13 | `INPUT[text:Pskills12]` |
>>| 6 |`INPUT[text:Pskills5]` |14 | `INPUT[text:Pskills13]` |
>>| 7 | `INPUT[text:Pskills6]` | 15 | `INPUT[text:Pskills14]` |
>>| 8 | `INPUT[text:Pskills7]` |16 | `INPUT[text:Pskills15]` |
>
>>[!danger] %%FAKE TITLE HERE%%
>>### Sorcery
>>|     |     |
>> |--- | --- |
>>|**Name** | `=this.Spell1`|
>>|**PP Cost** |  `=this.Spell1pp`|
>>|**Memorized**  |  `INPUT[toggle:Spell1mem]` |
>> |**Idiosyncrasy**  |  `=this.Spell1idio` |
>> | **Description**     | `=this.Spell1des` | 
>>|**Name** | `=this.Spell2`|
>>|**PP Cost** |  `=this.Spell2pp`|
>> |**Idiosyncrasy**  |  `INPUT[toggle:Spell2mem]` |
>> | **Description**     | `=this.Spell2des` | 


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



