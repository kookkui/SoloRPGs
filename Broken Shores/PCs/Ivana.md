---
Art: "![[Fem_Viking1.jpg|600]]"
Corruption: 0
HP: 0
STR: 15
DEX: 13
CONST: 13
WIL: 11
INT: 14
CHA: 11
Weapon1: Morningstar
Weapon1dmg: D10
Weapon1notes: Martial Melee, Bludgeoning
Weapon2: 
Weapon2dmg: 
Weapon2notes: 
Weapon3: 
Weapon3dmg: 
Weapon3notes: 
Armor: 
ArmorPR: 
Armorintegrity: 
Armornote1: 
Shield: 
ShieldPR: 
Shieldintegrity: 
trinketslot: 
Currency: 38
shards: 
csupplies: 
rations: 8
water: 0
talent0: "**Alchemist (Passive)**: You gain the special Crafting activity, Brew. When you Brew, you can expend 2x Crafting Supplies and 1x Ration to create a random potion (roll on the table on page 118). You automatically know what effect your potion will have."
talent1: "**Alchemist (Tier-1 Throw Potion)**: Standard Action. You can throw a potion up to 20 feet without needing to make a roll. A creature hit is affected as if they drank the potion."
Godshard: 
GodshardPassive: 
GodshardActive1: 
Spell1: Corrupt Weapon
Spell1pp: 2
Spell1range: Touch
Spell1time: WIL turns
Spell1idio: The sorcerer sweats blood each time this spell is cast, although they suffer no harm
Spell1des: "\rThe target weapon deals +D4 necrotic damage.\r *A coat of green, pus-like substance covers the weapon for a moment, only to be absorbed immediately after, leaving a faint, green glow behind.*"
Spell2pp: 
Spell2idio: 
Spell2des: 
Spell1mem: true
skill1: false
notes1: I stole a Ring of Healing (can cast the Stitch Wound spell 1/day) from the cult.
title1: Rope (40ft)
title21: ""
title2: Rations
title3: ""
title4: ""
skill21: false
lightsource: None
title5: ""
skill10: false
title6: ""
title7: ""
title8: ""
skill20: false
skill8: false
title9: ""
skill13: false
title10: ""
skill5: false
title11: ""
title12: ""
Pskills69: ""
title13: ""
Pskills1: ""
title14: ""
title15: ""
title16: ""
necklaceslot: 
ring1: Ring of Healing (can cast the Stitch Wound spell 1/day)
Pskills2: ""
title17: ""
title18: ""
Pskills3: ""
title19: ""
title20: ""
title22: ""
title23: ""
title24: ""
acoins: 
ruinscounter: None
---
>[!dice] %%FAKE TITLE HERE%%
>>[!dice] %%FAKE TITLE HERE%%  
>> # `=this.file.name`
>> 
>> `=this.Art`
>> 
>> ###### Stats
>>|     |     | 
>> |--- | --- | 
>>|**HP** | **Current:** `26` **Max:** `=this.CONST*2`|
>>|**Power Points** |  **Current:** `11`  **Max:** `=this.WIL`|
>> |**Speed** |  <font color="#00b0f0">Walk:</font> `=this.DEX*2`  <font color="#00b0f0">Run:</font> `=this.DEX*4` |
>>| **Max Gear Slots**     | `=(this.STR)+10` | 
>>
>>&nbsp;
>>
>> ###### Weapons
>>| **Weapons** | **Damage** | **Notes** |
>>| ---------------------- | --------------- | ------------- |
>>| `=this.Weapon1` | `=this.Weapon1dmg` | `=this.Weapon1notes` |
>>| `=this.Weapon2` | `=this.Weapon2dmg` | `=this.Weapon2notes` |
>>| `=this.Weapon3` | `=this.Weapon3dmg` | `=this.Weapon3notes` |
>>|`=this.Weapon4` |`=this.Weapon4dmg` | `=this.Weapon4notes` |
>>
>>&nbsp;
>>
>> ###### Armor
>>| **Name** | **Protection Rate** | **Integrity** | **Notes**|
>>| ---------------------- | --------------- | ------------- | ------------- |
>>| `=this.Armor` | `=this.ArmorPR` | `=this.Armorintegrity` | `=this.Armornote1`
>>| `=this.Shield` | `=this.ShieldPR` | `=this.Shieldintegrity` |`=this.Armornote2`
>>| `=this.Helmet` | `=this.HelmetPR` | `=this.Helmetintegrity` |`=this.Armornote3`
>>
>>&nbsp;
>>
>>###### Currency and Provisions
>>|     |     |
>> |:---: | :---: |
>>|**Coins (Ҁ)** |`=this.Currency` |
>>|**Shards** | `=this.shards`|
>> |**Crafting Supplies** |`0` |
>>| **Rations**   |  `8`   |
>>| **Water (Gal)** |  `=this.water`   |
>>|**Add Coins (Ҁ)**| `INPUT[number:acoins]` `BUTTON[ccoins]`|
>>
>>&nbsp;
>>
>>###### Exploration
>>|     |     |
>> |:---: | :---: |
>>|**Exploration Time**|`boxes: 0/10`|
>>| **Ruins/Derelict Size Timer** |`INPUT[inlineSelect(option(None), option(d4), option(d6), option(d8), option(d10), option(d12), option(d20)):ruinscounter]` |   |
>>| **Light Source Remaining** |`INPUT[inlineSelect(option(None), option(Ud4), option(Ud6), option(Ud8), option(Ud10), option(Ud12)):lightsource]` |   |

>[!table] %%FAKE TITLE HERE%%
>>[!table] %%FAKE TITLE HERE%%
>> #### Stats
>> | | | | | |
>>| :--: |:--: | :--: | :--: | :---: |
>>| **Strength** | `=this.STR` | **Brawn** | `=(this.STR)*5`| `0/10` |
>>| **Dexterity** | `=this.DEX` |**Coordination** | `=(this.DEX)*5`|`0/10`|
>> | **Constitution** | `=this.CONST` | **Vitality**|`=(this.CONST)*5`| `1/10`|
>> | **Will** | `=this.WIL` | **Tenacity**|`=(this.WIL)*5`| `0/10`|
>>| **Intelligence** | `=this.INT` | **Intellect**|`=(this.INT)*5`|`0/10` |
>> | **Charisma** | `=this.CHA` | **Charm**|`=(this.CHA)*5`|`0/10`|
>>
>>&nbsp;
>>
>> #### Skill Checks
>>| **Skill Name** | **Skill Level** | **Level Up**
>>| --------------------- | ----------- | ----------- |
>>| **Acrobatics**(DEX `=this.DEX`) | `13` | `INPUT[toggle:skill1]`|
>>| **Athletics** (STR `=this.STR`) | `55` | `INPUT[toggle:skill2]`|
>>| **Animal Handling** (CHA `=this.CHA`) | `11` |`INPUT[toggle:skill3]`|
>>| **Command** (CHA `=this.CHA`) | `11` |`INPUT[toggle:skill4]`|
>>| **Crafting** (DEX `=this.DEX`) | `53` |`INPUT[toggle:skill5]`|
>>| **Dodge** (DEX `=this.DEX` ) | `53` |`INPUT[toggle:skill6]`|
>>| **Insight** (WIL `=this.WIL`) | `11` |`INPUT[toggle:skill7]`|
>>| **Literacy** (INT `=this.INT`) | `74` |`INPUT[toggle:skill8]`|
>>|**Manipulation** (CHA `=this.CHA`) | `11` | `INPUT[toggle:skill9]`|
>>| **Martial Weapons** (STR `=this.STR`) | `55` |`INPUT[toggle:skill10]`
>>| **Medicine** (INT `=this.INT`) | `34` |`INPUT[toggle:skill11]`
>>|**Nature** (INT `=this.INT`) | `34` |`INPUT[toggle:skill12]`
>>| **Perception** (WIL `=this.WIL`) | `41` |`INPUT[toggle:skill13]`
>>| **Performance** (CHA `=this.CHA`) | `11` |`INPUT[toggle:skill14]`
>>| **Ranged Weapons** (DEX `=this.DEX` ) | `33` |`INPUT[toggle:skill15]`
>>| **Sailing** (DEX `=this.DEX`) | `33` |`INPUT[toggle:skill16]`
>>| **Siege Weapons** (DEX `=this.DEX`) | `13` |`INPUT[toggle:skill17]`
>>| **Simple Melee Weapons** (STR `=this.STR`) | `15` |`INPUT[toggle:skill18]`
>>| **Sleight of Hand** (DEX `=this.DEX` ) | `15` |`INPUT[toggle:skill19]`
>>| **Stealth** (DEX `=this.DEX`) | `33` |`INPUT[toggle:skill20]`
>>| **Survival** (INT `=this.INT` ) | `34` |`INPUT[toggle:skill21]`
>>| **Unarmed** (STR `=this.STR`) | `15` |`INPUT[toggle:skill22]`
>>
>>&nbsp;
>>
>>#### Notes
>>`INPUT[textArea:notes1]`

>[!travel] %%FAKE TITLE HERE%%
>>[!travel] %%FAKE TITLE HERE%%
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
>>| **Pendant** | `=this.necklaceslot` |
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

>[!dice] %%FAKE TITLE HERE%%
>>[!dice] %%FAKE TITLE HERE%%
>>### Inventory
>>| **Slot** | **Encumbering Items** | **Slot** | **Encumbering Items** 
>>| :-: | :---------------: |--------|--------|
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
>>&nbsp
>>
>> ### Non-Incumbering Items
>> |**Slot**| **Item** |**Slot**| **Item** 
>>| :-: | :-----------------------: |:-: | :-------------: |
>>| 1 | `INPUT[text:Pskills69]` | 9 | `INPUT[text:Pskills8]` |
>>| 2 | `INPUT[text:Pskills1]` | 10 | `INPUT[text:Pskills9]` |
>>| 3 | `INPUT[text:Pskills2]` |11 | `INPUT[text:Pskills10]` |
>>| 4 | `INPUT[text:Pskills3]` | 12 | `INPUT[text:Pskills11]` |
>>| 5 | `INPUT[text:Pskills4]` |13 | `INPUT[text:Pskills12]` |
>>| 6 |`INPUT[text:Pskills5]` |14 | `INPUT[text:Pskills13]` |
>>| 7 | `INPUT[text:Pskills6]` | 15 | `INPUT[text:Pskills14]` |
>>| 8 | `INPUT[text:Pskills7]` |16 | `INPUT[text:Pskills15]` |
>
>>[!table] %%FAKE TITLE HERE%%
>>### Sorcery
>>
>>&nbsp
>>
>>|     |     |      |     |
>> |:---: | :---: | :---: | :---: |
>>| <font color="#00B0F0">Name</font> | `=this.Spell1`|<font color="#00B0F0">PP Cost</font> |  `=this.Spell1pp`|
>>|<font color="#00b0f0">Range</font> | `=this.Spell1range`|<font color="#00b0f0">Duration</font> |  `=this.Spell1time`|
>>
>>
>>|     |     |
>> |:---: | --- |
>>|<font color="#00b0f0">Memorized</font>  |  `INPUT[toggle:Spell1mem]`|
>>|<font color="#00b0f0">Idiosyncrasy</font> | `=this.Spell1idio` |
>> 
>>
>>&nbsp;
>>
>> `=this.Spell1des`
>>
>>&nbsp;
>>
>>---
>>
>>&nbsp
>>
>>|     |     |      |     |
>> |:---: | :---: | :---: | :---: |
>>| <font color="#00B0F0">Name</font> | `=this.Spell2`|<font color="#00B0F0">PP Cost</font> |  `=this.Spell2pp`|
>>|<font color="#00b0f0">Range</font> | `=this.Spell2range`|<font color="#00b0f0">Duration</font> |  `=this.Spell2time`|
>>
>>
>>|     |     |
>> |:---: | --- |
>>|<font color="#00b0f0">Memorized</font>  |  `INPUT[toggle:Spell2mem]`|
>>|<font color="#00b0f0">Idiosyncrasy</font> | `=this.Spell2idio` |
>> 
>>
>>&nbsp;
>>
>> `=this.Spell2des`
>>
>>&nbsp;
>>
>>---
>>
>>&nbsp
>>


```meta-bind-button
label: Add coins
icon: ""
style: primary
class: ""
cssStyle: ""
backgroundImage: ""
tooltip: ""
id: ccoins
hidden: True
actions:
- type: updateMetadata
  bindTarget: Currency
  evaluate: True
  value: getMetadata('acoins') + getMetadata('Currency')

```



