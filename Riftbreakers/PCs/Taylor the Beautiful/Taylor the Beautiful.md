---
Title: Protector of Kar Helos
STR: 10
DEX: 16
CON: 18
INT: 12
WIL: 11
CHA: 14
PER: 65
Proficiencies: |-
  Weapons: Longbow, Scimitar
  Armor: Soft Leather
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
exampleProperty: Apprentice
axp: 100
xp: 1575
a-N: "355"
a-a:
a-V:
a-M:
Ring1: |
  Name: Champion's Ring of the Snake
  Magic: Dexterity +1, Reduce your Stamina pool by 5 (26), but increase your Aether pool by 8 (23). You no longer need to eat or drink.
  Aspects: Air Life 2x Boon Bane 
  Quirk: It's always pristine
  Value: 300A
Ring2: |
  Name: Mage's Wonderful Ring 
  Magic: Stamina +4, Stamina +4, On command, this item works as a source of light. Illuminates in a 20 m. radius.
  Value: 300A
  Aspects: Fire 2xPower Light 
  Quirk: It's always covered in a layer of mucus
Gloves: |-
  Name: Victorious Gloves of the Whisper 
  Aspects: Air Earth 
  Magic: Constitution +1 Charisma +1
  Rarity: Uncommon
  Rank: Novice
  Object: Gloves
  Value: 200A 
  Quirk: Smells like rotten flesh
Other: |-
  Name: Knight's Glass Stone
  Magic: You can detect all living beings in a 20 m. radius. 
  Increase your luck by +5
  Rarity: Uncommon
  Rank: Novice
  Object: Other
  Identified
  Value: 200A
  Aspects: Chaos Life Boon Light
  Quirk: It appears to be completely made of glass. It doesn't make it more fragile than it should be though

title1: Quiver
title2: Torch Ud10
title3: Bandage Ud12
title4: arrows ud12
title5: rations x 2
title6: rough leather x 10
title7: extra-dimensional bag x 0
title8: ascended essence (prime)
title9: lantern
title10: aetheryte
title11: "stoneskin potion. for the next hour you have +1 armor, but your dodge and acrobatics skills are reduced by -10. aspects: stone, boon"
title12: aetheryte
title13: backpack
proficiency1: "**Weapon:** Longbow"
proficiency2: "**Weapon:** Scimitar"
proficiency3: "**Armor:** Soft Leather"
---
>[!dice] %%FAKE TITLE HERE%%
>> [!dice] %%FAKE TITLE HERE%%  
>> # `=this.file.name`
>> ![[IMG-20250129190024669.webp]]
>> ###### Stats
>>  |
>> ---|---|
>> **Rank** |`INPUT[suggester(option(Novice), option(Apprentice), option(Veteran), option(Master)):exampleProperty]` |
>>  **Title** |`=this.Title` |
>> **Reputation** | `3` |
>>  **HP** | **Current:**`32` **Max:** `=this.CON*3`
>> **Aether** | `24` /`VIEW[{WIL} + {INT}]` |
>> **Stamina** | `28` /`VIEW[{STR} + {CON}]` |
>> **Armor** | <span style="color:rgb(255, 128, 31)">D4+3</span>  |
>> **XP** | `VIEW[{xp}][text]`
>>**ADD XP :** `INPUT[number:axp]` `BUTTON[exp]`
>>
>> ###### Weapons
>>| **Weapons** | **Type** | **Damage** | **Notes** |
>>| --------------- | ------------ | --------------- | --------------------- |
>>| `=this.Weapon1` | `=this.Weapon1type` |  `=this.Weapon1dmg` |`=this.Weapon1notes` |
>>| `=this.Weapon2` | `=this.Weapon2type` |`=this.Weapon2dmg` | `=this.Weapon2notes` |
>>| `=this.Weapon3` | `=this.Weapon3type`|`=this.Weapon3dmg` | `=this.Weapon3notes` |
>>| | | |
>>| | | |
>> ###### Crafting Aspects
>>| Air   | Bane | Boon | Chaos | Dark  | Death |
>>| ----- | ---- | ---- | ----- | ----- | ----- |
>>| `0`   | `0`  | `1`  | `10`   | `21`   | `1`   |
>>| Earth | Fire | Life | Light | Power | Water |
>| `1`   | `11`  | `0`  | `10`   | `11`   | `10`   |
>>###### Minerals
>>
>>| Coal | Iron | Silver | Aglite |
>>| ---- | ---- | ------ | ------ |
>>| `21`  | `3`  | `1`    | `4`    |
>>  ###### Currency
>>| **⟑-N** | **⟑-A**   |
>>| ------- | --------- |
>>|`=this.a-N`|`=this.a-a`|
>>| **⟑-V** | **⟑-M**   |
>>|`=this.a-V`|`=this.a-M`|
>
>
>>[!infobox] %%FAKE TITLE HERE%%
>> ### Stats
>> | | | | |
>>| ---- | ---- | ------ | ------ |
>>| **Strength** | `=this.STR` | **Brawn** | `=this.STR*5` |
>>| **Dexterity** | `=this.DEX`| **Coordination** | `=this.DEX*5` |
>>| **Constitution** |`=this.CON` | **Vitality** |`=this.CON*5` |
>>| **Will** | `=this.WIL` | **Tenacity** |`=this.WIL*5` |
>>| **Intelligence** | `=this.INT` | **Intellect** | `=this.INT*5` |
>>| **Charisma** | `=this.CHA` | **Charm** | `=this.CHA*5` |
>>| **STR Damage** | | **DEX Damage** |+4 |
>>| **Luck** | 5 | **WIL Damage** | +1 |
>>| **Speed** | `=this.DEX`/`=this.DEX*2`| **Persistence** |`=this.PER`|
>> ### Skill Checks
>>| **Skill Name**                | **Skill Level** |
>>| ------------------------- | ----------- |
>>| **Alchemy** (INT) | `34` |
>>| **Acrobatics** (DEX) | `15` |
>>| **Animal Handling** (CHA) | `14` |
>>| **Athletics** (STR) | `33` |
>>| **Blacksmithing** (DEX) | `35` |
>>| **Command** (CHA) | `14` |
>>| **Gathering** (DEX) | `57` |
>>|**Nature** (INT) | `31` |
>>| **Manipulation** (CHA) | `14` |
>>| **Medicine** (INT) | `11` |
>>| **Leatherworking** (DEX) | `38` |
>>| **Insight** (WIL) | `15` |
>>| **Dodge** (DEX) | `75` |
>>| **Perception** (WIL) | `32` |
>>| **Performance** (CHA) | `14` |
>>| **Sailing** (DEX) | `15` |
>>| **Sleight of Hand** (DEX) | `25` |
>>| **Stealth** (DEX) | `38` |
>>| **Survival** (INT) | `53` |
>>##### Proficiencies
>> |        |         |   
>>| :-: | :----- |
>>| 1 | `=this.proficiency1` |
>>| 2 | `=this.proficiency2` |
>>| 3 | `=this.proficiency3` |
>>| 4 | `=this.proficiency4` |
>>| 5 | `=this.proficiency5` |
>>| 6 |`=this.proficiency6` |
>>| 7 | `=this.proficiency7` |
>
>>[!table] %%FAKE TITLE HERE%%
>>### Inventory
>>| Slot | Encumbering Items | Slot | Encumbering Items 
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

>[!seealso] %%FAKE TITLE HERE%%
>>[!important] %%FAKE TITLE HERE%%
>> ### Gear
>>##### Head
>>`INPUT[textArea:Head]`
>>##### Chest
>>`INPUT[textArea:Chest]`
>>##### Belt
>>`INPUT[textArea:Belt]`
>>##### Pants
>>`INPUT[textArea:Pant]`
>>##### Boots
>>`INPUT[textArea:Boots]`
>>##### Gloves
>>`INPUT[textArea:Gloves]`
>>##### Ring 1
>>`INPUT[textArea:Ring1]`
>>##### Ring 2
>>`INPUT[textArea:Ring2]`
>>##### Pendant
>>`INPUT[textArea:Pendant]`
>>##### Other
>>`INPUT[textArea:Other]`








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





