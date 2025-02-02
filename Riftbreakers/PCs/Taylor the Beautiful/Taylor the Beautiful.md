---
Type: Player
Art: "![[Character Image Placholder]]"
Level: 0
AC: 0
Prof: 
HP: 0
HitDice: d0
Speed: 0
STR: 0
DEX: 0
CONST: 0
INT: 0
WIS: 0
CHA: 0
Race: RaceName
Alignment: NONE
Gender: GenderName
Age: "0"
Location: NONE
Class: ClassName
Subclass: SubClassName
AssociatedGroup: NONE
Likes: NONE
Dislikes: NONE
Pronouns: NONE
PersonalityTrait:
  - NONE
SocialTrait:
  - NONE
MentalTrait:
  - NONE
Proficiencies: |-
  Weapons: Longbow, Scimitar
  Armor: Soft Leather
Resistances:
  - NONE
Languages:
  - NONE
DmgTkn: 0
TempHP: 0
Copper: 0
Silver: 0
Electrum: 0
Gold: 0
Platinum: 0
exampleProperty: Apprentice
Title: Protector of Kar Helos
axp: 100
xp: 1575
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
Title69: Backpack
Title1: Quiver
Title2: Torch Ud10
Title3: Bandage Ud12
Title4: Arrows Ud12
Title5: Rations x 2
Title6: Rough Leather x 10
Title7: Extra-Dimensional bag x 0
Title8: Ascended Essence (Prime)
Title9: Lantern
Title10: Aetheryte
Title11: "Stoneskin Potion. For the next hour you have +1 Armor, but your Dodge and Acrobatics skills are reduced by -10. Aspects: Stone, Boon"
Title12: Aetheryte
a-N: "355"
---
>[!dice] %%FAKE TITLE HERE%%
>> [!dice] %%FAKE TITLE HERE%%  
>> # `=this.file.name`
>> ![[IMG-20250129190024669.webp]]
>> ###### Stats
>>  |
>> ---|---|
>> **Rank** |`INPUT[suggester(option(Novice), option(Apprentice), option(Veteran), option(Master)):exampleProperty]` |
>>  **Title** |`INPUT[text:Title]` |
>> **Reputation** | `3` |
>>  **HP** | `32` /32
>> **Aether** | `31` /31 |
>> **Stamina** | `29` /29 |
>> **Armor** | <span style="color:rgb(255, 128, 31)">D4+3</span>  |
>> **XP** | `VIEW[{xp}][text]`
>>**ADD XP :** `INPUT[number:axp]` `BUTTON[exp]`
>>
>> ###### Weapons
>>| **Weapons** | **Type** | **Damage** | **Notes** |
>>| ---------------------- | ---------------- | --------------- | ------------- |
>>| Holy Longbow of the Bear  | Piercing                |2D6+4           | Two-handed, Holy, Arrows UD12, Range 115 m              |
>>| Scimitar                 | Slashing                |      D8+4        | Parry, Finesse            |
>>|            |             |            |               |
>>|                        |                  |                 |                 |
>>|                        |                  |                 |                 |
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
>>|`INPUT[text:a-N]`|`INPUT[text:a-a]`|
>>| **⟑-V** | **⟑-M**   |
>>|`INPUT[text:a-v]`|`INPUT[text:a-m]`|
>
>
>>[!infobox] %%FAKE TITLE HERE%%
>> ### Stats
>> |        |         |            |            |
>>| ---- | ---- | ------ | ------ |
>>| **Strength**     | 10 | **Brawn**        | 50 |
>>| **Dexterity**    | 16 | **Coordination** | 80 |
>>| **Constitution** | 18 | **Vitality**     | 90 |
>>| **Will**         | 12 | **Tenacity**     |60|
>>| **Intelligence** | 11 | **Intellect**    | 55 |
>>| **Charisma**     | 14 | **Charm**        | 70 |
>>| **STR Damage**   |   | **DEX Damage**   |+4  |
>>| **Luck**        | 5 |  **WIL Damage**  | +1 |
>>|     **Speed**   | 15/30| **Persistence** | 65|
>> ### Skill Checks
>>| **Skill Name**                | **Skill Level** |
>>| ------------------------- | ----------- |
>>| **Alchemy** (INT)         | `34`           |
>>| **Acrobatics** (DEX)      | `15`           |
>>| **Animal Handling** (CHA) | `14`           |
>>| **Athletics** (STR)       | `33`           |
>>| **Blacksmithing** (DEX)   | `35`           |
>>| **Command** (CHA)         | `14`           |
>>| **Gathering** (DEX)       | `57`           |
>>|**Nature** (INT)          | `31`           |
>>| **Manipulation** (CHA)    | `14`           |
>>| **Medicine** (INT)        | `11`           |
>>| **Leatherworking** (DEX)  | `38`           |
>>| **Insight** (WIL)         | `15`           |
>>| **Dodge** (DEX)           | `75`           |
>>| **Perception** (WIL)      | `32`           |
>>| **Performance** (CHA)     | `14`           |
>>| **Sailing** (DEX)         | `15`           |
>>| **Sleight of Hand** (DEX) | `25`           |
>>| **Stealth** (DEX)         | `38`           |
>>| **Survival** (INT)        | `53`           |
>>##### Proficiencies
>>`INPUT[textArea:Proficiencies]`
>
>>[!table] %%FAKE TITLE HERE%%
>> ### Inventory
>>|  1  | `INPUT[text:Title69]`                                                                                                                             |
>>| :-: | :----------------------------------------------------------------------------------------------------------------------------------- |
>>|  2  | `INPUT[text:Title1]`                                                                                                                  |
>>|  3  | `INPUT[text:Title2]`                                                                                                                   |
>>|  4  | `INPUT[text:Title3]`                                                                                                                  |
>>|  5  | `INPUT[text:Title4]`                                                                                                                   |
>>|  6  |`INPUT[text:Title5]`                                                                                                                  |
>>|  7  | `INPUT[text:Title6]`                                                                                                                   |
>>|  8  | `INPUT[text:Title7]`                                                                                                           |
>>|  9  | `INPUT[text:Title8]`                                                                                                             |
>>| 10  | `INPUT[text:Title9]`                                                                                                                |
>>| 11  | `INPUT[text:Title10]`                                                                                                                 |
>>| 12  | `INPUT[text:Title11]`                                                                                                             |
>>| 13  | `INPUT[text:Title12]`                                                                        |
>>| 14  | `INPUT[text:Title13]`                                                                                                             |
>>| 15  |  `INPUT[text:Title14]`                                                                                                                |
>>| 16  |  `INPUT[text:Title1416]`                                                                                                                |
>>| 17  |  `INPUT[text:Title1417]`                                                                                                                   |
>>| 18  |   `INPUT[text:Title1418]`                                                                                                                   |
>>| 19  |    `INPUT[text:Title1419]`                                                                                                                 |
>>| 20  |    `INPUT[text:Title1420]`                                                                                                                 |
>>| 21  |    `INPUT[text:Title1421]`                                                                                                                |
>>| 22  |     `INPUT[text:Title1422]`                                                                                                                   |
>>| 23  |      `INPUT[text:Title143]`                                                                                                                               |
>>| 24  |    `INPUT[text:Title1424]`                                                                                                                                  |
>>| 25  |   `INPUT[text:Title1425]`                                                                                                                                  |
>>| 26  |   `INPUT[text:Title1426]`                                                                                                                                   |
>>| 27  |   `INPUT[text:Title1427]`                                                                                                                                   |
>>| 28  |    `INPUT[text:Title1428]`                                                                                                                                  |
>>| 29  |    `INPUT[text:Title1431]`                                                                                                                                  |
>>| 30  |    `INPUT[text:Title1430]`                                                                                                                                 |
>>| 31  |    `INPUT[text:Title1432]`                                                                                                                                  |
>>| 32  |   `INPUT[text:Title1433]`                                                                                                                                   |
>>| 33  |    `INPUT[text:Title1434]`                                                                                                                                  |
>>| 34  |    `INPUT[text:Title1435]`                                                                                                                                  |
>>| 35  |    `INPUT[text:Title1436]`                                                                                                                                  |
>>| 36  |    `INPUT[text:Title1437]`                                                                                                                                  |
>>| 37  |     `INPUT[text:Title1438]`                                                                                                                                 |
>>| 38  |     `INPUT[text:Title1439]`                                                                                                                                 |
>>| 39  |       `INPUT[text:Title1440]`                                                                                                                               |
>>| 40  |         `INPUT[text:Title1441]`                                                                                                                                                                       

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