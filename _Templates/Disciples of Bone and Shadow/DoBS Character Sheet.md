---
Art: "![[Character Image Placholder]]"
Level: 1
Corruption: 0
HP: 0
GeSl: 0
STR: 10
DEX: 10
CONST: 10
WIL: 10
INT: 10
CHA: 10
Weapon1: Placeholder
Weapon1dmg: 69
Weapon1notes: Its badass
Weapon2: Placeholder
Weapon2dmg: 69
Weapon2notes: Its badass
Weapon3: Placeholder
Weapon3dmg: 69
Weapon3notes: Its badass
Armor: 0
DmgTkn: 0
TempHP: 0
Currency: 0
Provisions: 0
hregion: Place
advantages: Good thing
disadvantages: Bad thing
flaws: Asshole
---
>[!dice] %%FAKE TITLE HERE%%
>> [!dice] %%FAKE TITLE HERE%%  
>> # `=this.file.name`
>> ![[Character Image Placeholder]]
>> ###### Stats
>>|     |     |
>> |--- | --- |
>>|   **Level**   |  `=this.level`   |
>>|**HP** | `=this.HP - this.DmgTkn + this.TempHP`|
>> |**Corruption** | **Current:** `0` **Max:** `=this.Corruption`   |
>> |**Armor** | `=this.Armor` |
>> |**XP** | `VIEW[{xp}][text]`|
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
>>##### Character Traits
>>|     |     |
>> |--- | --- |
>>| **Home Region**   |  `=this.hregion`   |
>>|**Advantages** | `=this.advantages`|
>> |**Disadvantages** |`=this.disadvantages` |
>>| **Character Flaws**   |  `=this.flaws`   |
>>
>>  ###### Currency
>>  | 
>>---|---|
>>**Currency**|`=this.Currency` |
>> ###### Provisions
>>  | 
>>---|---|
>>**Provisions**|`=this.Provisions` |
>
>>[!infobox] %%FAKE TITLE HERE%%
>> ### Stats
>> |        |         |   
>>| ---- | ---- |
>>| **Strength**   | `=this.STR`  |
>>| **Dexterity**    | `=this.DEX` | 
>>| **Constitution** | `=this.CONST` |
>>| **Will**         |  `=this.WIL` | 
>>| **Intelligence** |  `=this.INT` | 
>>| **Charisma**     | `=this.CHA` | 
>>| **Max Gear Slots**     | `=this.GeSl` | 
>> ### Stats
>> |        |         |   
>>| ---- | ---- |
>>| **Strength**   | `=this.STR`  |
>>| **Dexterity**    | `=this.DEX` | 
>>| **Constitution** | `=this.CONST` |
>>| **Will**         |  `=this.WIL` | 
>>| **Intelligence** |  `=this.INT` | 
>>| **Charisma**     | `=this.CHA` | 
>>| **Max Gear Slots**     | `=(this.STR)` | 
>> ### Skill Checks
>>| **Skill Name** | **Skill Level** |
>>| ------------------------- | ----------- |
>>| **Alchemy** | `0` |
>>| **Animal Handling** (CHA `=this.CHA`) | `0` |
>>| **Command Skills** (CHA `=this.CHA`) | `0` |
>>| **Crafting** (DEX `=this.DEX`) | `0` |
>>| **Disguise** (DEX `=this.DEX`) | `0` |
>>| **Dodge** (DEX `=this.DEX` x 2) | `0` |
>>|**First Aid** (20) | `0` |
>>| **Forbidden Lore** | `0` |
>>| **Herb Lore** | `0` |
>>| **Literacy** (INT `=this.INT`) | `0` |
>>| **One-Handed Melee** (STR `=this.STR` + DEX `=this.DEX`) | `0` |
>>| **Orientation** (20) | `0` |
>>|**Outdoor Survival** (INT `=this.INT` + DEX `=this.DEX`) | `0` |
>>| **Parry** (STR `=this.STR` + DEX `=this.DEX`) | `0` |
>>| **Perception** (20) | `0` |
>>| **Persuasion** (CHA `=this.CHA`) | `0` |
>>| **Pick Pockets** (DEX `=this.DEX`) | `0` |
>>| **Ranged Weapons** (DEX `=this.DEX` x 2) | `0` |
>>| **Sailing** (DEX `=this.DEX`) | `0` |
>>| **Sneaking** (DEX `=this.DEX` x 2) | `0` |
>>| **Throw** (STR `=this.STR` + DEX `=this.DEX`) | `0` |
>>| **Tracking** (INT `=this.INT` ) | `0` |
>>| **Traditional Lore** (20) | `0` |
>>| **Two-Handed Melee** (STR `=this.STR` x 2) | `0` |
>>| **Unarmed** (STR `=this.STR` + DEX `=this.DEX`) | `0` |
>>
>>
>> ### Passive Skills
>>| 1 | `INPUT[text:Pskills69]` |
>>| :-: | :----------------------------------------------------------------------------------------------------------------------------------- |
>>| 2 | `INPUT[text:Pskills1]` |
>>| 3 | `INPUT[text:Pskills2]` |
>>| 4 | `INPUT[text:Pskills3]` |
>>| 5 | `INPUT[text:Pskills4]` |
>>| 6 |`INPUT[text:Pskills5]` |
>>| 7 | `INPUT[text:Pskills6]` |
>>| 8 | `INPUT[text:Pskills7]` |
>>| 9 | `INPUT[text:Pskills8]` |
>>| 10 | `INPUT[text:Pskills9]` |
>>| 11 | `INPUT[text:Pskills10]` |
>>| 12 | `INPUT[text:Pskills11]` |
>>| 13 | `INPUT[text:Pskills12]` |
>>| 14 | `INPUT[text:Pskills13]` |
>>| 15 | `INPUT[text:Pskills14]` |
>>| 16 | `INPUT[text:Pskills1416]` |
>>| 17 | `INPUT[text:Pskills1417]` |
>>| 18 | `INPUT[text:Pskills1418]`
>
>>[!important] %%FAKE TITLE HERE%%
>>##### Archetypes
>>`INPUT[textArea:Head]`
>>##### Notes
>>`INPUT[textArea:Other]`
>
>>[!table] %%FAKE TITLE HERE%%
>> ### Inventory
>>| Slot |  |Light Item | Equipped?|
>>| :-: | :---------------- |--------|--------|
>>| 1 | `INPUT[text:Title69]` | <input type="checkbox" unchecked>  |  <input type="checkbox" unchecked>   | 
>>| 2 | `INPUT[text:Title1]` |<input type="checkbox" unchecked>   |<input type="checkbox" unchecked>   | 
>>| 3 | `INPUT[text:Title2]` |<input type="checkbox" unchecked>   |<input type="checkbox" unchecked>   | 
>>| 4 | `INPUT[text:Title3]` |<input type="checkbox" unchecked>   |<input type="checkbox" unchecked>   | 
>>| 5 | `INPUT[text:Title4]` |<input type="checkbox" unchecked>   |<input type="checkbox" unchecked>   | 
>>| 6 |`INPUT[text:Title5]` |<input type="checkbox" unchecked>   |<input type="checkbox" unchecked>   | 
>>| 7 | `INPUT[text:Title6]` |<input type="checkbox" unchecked>   |<input type="checkbox" unchecked>   | 
>>| 8 | `INPUT[text:Title7]` |<input type="checkbox" unchecked>   |<input type="checkbox" unchecked>   | 
>>| 9 | `INPUT[text:Title8]` |<input type="checkbox" unchecked>   |<input type="checkbox" unchecked>   | 
>>| 10 | `INPUT[text:Title9]` |<input type="checkbox" unchecked>   |<input type="checkbox" unchecked>   | 
>>| 11 | `INPUT[text:Title10]` |<input type="checkbox" unchecked>   |<input type="checkbox" unchecked>   | 
>>| 12 | `INPUT[text:Title11]` |<input type="checkbox" unchecked>   |<input type="checkbox" unchecked>   | 
>>| 13 | `INPUT[text:Title12]` |<input type="checkbox" unchecked>   |<input type="checkbox" unchecked>   | 
>>| 14 | `INPUT[text:Title13]` |<input type="checkbox" unchecked>   |<input type="checkbox" unchecked>   | 
>>| 15 | `INPUT[text:Title14]` |<input type="checkbox" unchecked>   |<input type="checkbox" unchecked>   | 
>>| 16 | `INPUT[text:Title1416]` |<input type="checkbox" unchecked>   |<input type="checkbox" unchecked>   | 
>>| 17 | `INPUT[text:Title1417]` |<input type="checkbox" unchecked>   |<input type="checkbox" unchecked>   | 
>>| 18 | `INPUT[text:Title1418]` |<input type="checkbox" unchecked>   |<input type="checkbox" unchecked>   | 
>>| 19 | `INPUT[text:Title1419]` |<input type="checkbox" unchecked>   |<input type="checkbox" unchecked>   | 
>>| 20 | `INPUT[text:Title1420]` |<input type="checkbox" unchecked>   |<input type="checkbox" unchecked>   | 
>>| 21 | `INPUT[text:Title1421]` |<input type="checkbox" unchecked>   |<input type="checkbox" unchecked>   | 
>>| 22 | `INPUT[text:Title1422]` |<input type="checkbox" unchecked>   |<input type="checkbox" unchecked>   | 
>>| 23 | `INPUT[text:Title143]` |<input type="checkbox" unchecked>   |<input type="checkbox" unchecked>   | 
>>| 24 | `INPUT[text:Title1424]` |<input type="checkbox" unchecked>   |<input type="checkbox" unchecked>   | 
>>| 25 | `INPUT[text:Title1425]` |<input type="checkbox" unchecked>   |<input type="checkbox" unchecked>   | 
>>| 26 | `INPUT[text:Title1426]` |<input type="checkbox" unchecked>   |<input type="checkbox" unchecked>   | 
>>| 27 | `INPUT[text:Title1427]` |<input type="checkbox" unchecked>   |<input type="checkbox" unchecked>   | 
>>| 28 | `INPUT[text:Title1428]` |<input type="checkbox" unchecked>   |<input type="checkbox" unchecked>   | 
>>| 29 | `INPUT[text:Title1431]` |<input type="checkbox" unchecked>   |<input type="checkbox" unchecked>   | 
>>| 30 | `INPUT[text:Title1430]` |<input type="checkbox" unchecked>   |<input type="checkbox" unchecked>   | 
>>| 31 | `INPUT[text:Title1432]` |<input type="checkbox" unchecked>   |<input type="checkbox" unchecked>   | 
>>| 32 | `INPUT[text:Title1433]` |<input type="checkbox" unchecked>   |<input type="checkbox" unchecked>   | 
>>| 33 | `INPUT[text:Title1434]` |<input type="checkbox" unchecked>   |<input type="checkbox" unchecked>   | 
>>| 34 | `INPUT[text:Title1435]` |<input type="checkbox" unchecked>   |<input type="checkbox" unchecked>   | 
>>| 35 | `INPUT[text:Title1436]` |<input type="checkbox" unchecked>   |<input type="checkbox" unchecked>   | 
>>| 36 | `INPUT[text:Title1437]` |<input type="checkbox" unchecked>   |<input type="checkbox" unchecked>   | 
>>| 37 | `INPUT[text:Title1438]` |<input type="checkbox" unchecked>   |<input type="checkbox" unchecked>   | 
>>| 38 | `INPUT[text:Title1439]` |<input type="checkbox" unchecked>   |<input type="checkbox" unchecked>   | 
>>| 39 | `INPUT[text:Title1440]` |<input type="checkbox" unchecked>   |<input type="checkbox" unchecked>   | 
>>| 40 | `INPUT[text:Title1441]` |<input type="checkbox" unchecked>   |  <input type="checkbox" unchecked>   |                                                                                             

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