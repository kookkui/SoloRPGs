---
Art: "![[Character Image Placholder]]"
Level: 1
Corruption: 10
HP: 41
GeSl: 0
STR: 18
DEX: 17
CONST: 16
WIL: 15
INT: 14
CHA: 12
xp: 50
Weapon1: One-Handed Sword
Weapon1dmg: d6
Weapon1notes: +10 Parry
Weapon2: 
Weapon2dmg: 
Weapon2notes: 
Weapon3: 
Weapon3dmg: 
Weapon3notes: 
Armor: 0
DmgTkn: 0
TempHP: 0
currency: 125
provisions: 10
hregion: Akkar Strand
advantages: "Extreme Concentration: No matter what the circumstances are, you're capable of focusing on the task at hand, completely ignoring all distractions. This allows you to perform extremely well under stress in any circumstance (combat, running from danger, etc.)."
disadvantages: "Violent: Maybe you were beaten up as a child, or belong to a tribe that strongly believed in “might is right”; whatever the case, you always tend to solve all problems with violence, unless it is completely evident that you will not fare well. To be clear, you are not suicidal, you simply think that violence is the answer to all questions."
flaws: Bad Tempered I
Head: Hunter (Foraging, Marksmanship)
Title69: 1x Healing Tincture
Title1: Rations
Pskills69: "Marksmanship: You may relinquish your turn to aim with a Ranged Weapon, doubling the damage of your next attack."
Pskills1: "Foraging (Archetype Exclusive): This character consumes half as many supplies per day, thanks to their ability to find sources of food and water in the wild."
Title2: Torch x 10
Title3: Bandage x 5
Pskills2: "Inner Compass (1 EP): You may re-roll once any failed Orientation tests."
passive0: "**Marksmanship**: You may relinquish your turn to aim with a Ranged Weapon, doubling the damage of your next attack."
passive1: "**Foraging (Archetype Exclusive)**: This character consumes half as many supplies per day, thanks to their ability to find sources of food and water in the wild."
passive2: "**Inner Compass**: You may re-roll once any failed Orientation tests."
archetype0: "**Hunter**: Foraging, Marksmanship"
axp: 10
Title4: 10 Pale Ghar claws  (20 jats ea.)
Title5: One-Handed Sword
Title6: Wolf Pelt (100 jats)
---
>[!dice] %%FAKE TITLE HERE%%
>> [!dice] %%FAKE TITLE HERE%%  
>> # `=this.file.name`
>> ![[Zaalu_Non_AI.webp]]
>> ###### Stats
>>|     |     |
>> |--- | --- |
>>|   **Level**   |  `=this.level`   |
>>|**HP** | `=this.HP - this.DmgTkn + this.TempHP`|
>> |**Corruption** | **Current:** `0` **Max:** `=this.Corruption`   |
>> |**Armor** | `=this.Armor` |
>> |**XP** | `VIEW[{xp}][text]`|
>>|**ADD XP :**| `INPUT[number:axp]` `BUTTON[exp]`|
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
>>**Currency**|`=this.currency` |
>> ###### Provisions
>>  | 
>>---|---|
>>**Provisions**|`=this.provisions` |
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
>>| **Max Gear Slots**     | `=(this.STR)` | 
>> ### Skill Checks
>>| **Skill Name** | **Skill Level** |
>>| ------------------------- | ----------- |
>>| **Alchemy** | `30` |
>>| **Animal Handling** (CHA `=this.CHA`) | `12` |
>>| **Command Skills** (CHA `=this.CHA`) | `12` |
>>| **Crafting** (DEX `=this.DEX`) | `38` |
>>| **Disguise** (DEX `=this.DEX`) | `17` |
>>| **Dodge** (DEX `=this.DEX` x 2) | `44` |
>>|**First Aid** (20) | `40` |
>>| **Forbidden Lore** | `20` |
>>| **Herb Lore** | `35` |
>>| **Literacy** (INT `=this.INT`) | `35` |
>>| **One-Handed Melee** (STR `=this.STR` + DEX `=this.DEX`) | `50` |
>>| **Orientation** (20) | `41` |
>>|**Outdoor Survival** (INT `=this.INT` + DEX `=this.DEX`) | `46` |
>>| **Parry** (STR `=this.STR` + DEX `=this.DEX`) | `48` |
>>| **Perception** (20) | `30` |
>>| **Persuasion** (CHA `=this.CHA`) | `12` |
>>| **Pick Pockets** (DEX `=this.DEX`) | `17` |
>>| **Ranged Weapons** (DEX `=this.DEX` x 2) | `44` |
>>| **Sailing** (DEX `=this.DEX`) | `17` |
>>| **Sneaking** (DEX `=this.DEX` x 2) | `34` |
>>| **Throw** (STR `=this.STR` + DEX `=this.DEX`) | `35` |
>>| **Tracking** (INT `=this.INT` ) | `29` |
>>| **Traditional Lore** (20) | `20` |
>>| **Two-Handed Melee** (STR `=this.STR` x 2) | `46` |
>>| **Unarmed** (STR `=this.STR` + DEX `=this.DEX`) | `35` |
>>
>>
>> ### Passive Skills
>> |        |         |   
>>| :-: | :----------------------------------------------------------------------------------------------------------------------------------- |
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
>>[!important] %%FAKE TITLE HERE%%
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



