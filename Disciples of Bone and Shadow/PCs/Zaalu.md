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
xp: 70
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
Lightitem1: false
exampleProperty: false
title1: 1x Healing Tincture
title2: Rations
title3: Torch x 10
title4: Bandage x 5
title5: 10 Pale Ghar claws  (20 jats ea.)
title6: One-Handed Sword
title7: Wolf Pelt (100 jats)
checkbox1: true
checkbox2: true
checkbox3: true
checkbox4: true
checkbox5: true
checkbox7: false
equipped6: true
equipped7: false
Spell1: 
Spell1cl: 
Spell1idio: 
Spell1des: 
Spell2cl: 
Spell2idio: 
Spell2des: 
Spell1mem: 
---
>[!dice] %%FAKE TITLE HERE%%
>> [!dice] %%FAKE TITLE HERE%%  
>> # `=this.file.name`
>> ![[Zaalu_Non_AI.webp]]
>> ###### Stats
>>|     |     |
>> |--- | --- |
>>|   **Level**   |  `=this.level`   |
>>|**HP** | **Current:** `41` **Max:** `=this.CONST*3`|
>> |**Corruption** | **Current:** `0` **Max:** `=this.Corruption`   |
>> |**Armor** | `=this.Armor` |
>> |**EP**| `0` |
>> |**XP** | `VIEW[{xp}][text]`|
>>|**ADD XP :**| `INPUT[number:axp]` `BUTTON[exp]`|
>>
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
>>| **One-Handed Melee** (STR `=this.STR` + DEX `=this.DEX`) | `51` |
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
>>|1|`INPUT[text:title1]`|`INPUT[toggle:checkbox1]`|`INPUT[toggle:equipped1]`
>>|2|`INPUT[text:title2]`|`INPUT[toggle:checkbox2]`|`INPUT[toggle:equipped2]`
>>|3|`INPUT[text:title3]`|`INPUT[toggle:checkbox3]`|`INPUT[toggle:equipped3]`
>>|4|`INPUT[text:title4]`|`INPUT[toggle:checkbox4]`|`INPUT[toggle:equipped4]`
>>|5|`INPUT[text:title5]`|`INPUT[toggle:checkbox5]`|`INPUT[toggle:equipped5]`
>>|6|`INPUT[text:title6]`|`INPUT[toggle:checkbox6]`|`INPUT[toggle:equipped6]`
>>|7|`INPUT[text:title7]`|`INPUT[toggle:checkbox7]`|`INPUT[toggle:equipped7]`
>>|8|`INPUT[text:title8]`|`INPUT[toggle:checkbox8]`|`INPUT[toggle:equipped8]`
>>|9|`INPUT[text:title9]`|`INPUT[toggle:checkbox9]`|`INPUT[toggle:equipped9]`
>>|10|`INPUT[text:title10]`|`INPUT[toggle:checkbox10]`|`INPUT[toggle:equipped10]`
>>|11|`INPUT[text:title11]`|`INPUT[toggle:checkbox11]`|`INPUT[toggle:equipped11]`
>>|12|`INPUT[text:title12]`|`INPUT[toggle:checkbox12]`|`INPUT[toggle:equipped12]`
>>|13|`INPUT[text:title13]`|`INPUT[toggle:checkbox13]`|`INPUT[toggle:equipped13]`
>>|14|`INPUT[text:title14]`|`INPUT[toggle:checkbox14]`|`INPUT[toggle:equipped14]`
>>|15|`INPUT[text:title15]`|`INPUT[toggle:checkbox15]`|`INPUT[toggle:equipped15]`
>>|16|`INPUT[text:title16]`|`INPUT[toggle:checkbox16]`|`INPUT[toggle:equipped16]`
>>|17|`INPUT[text:title17]`|`INPUT[toggle:checkbox17]`|`INPUT[toggle:equipped17]`
>>|18|`INPUT[text:title18]`|`INPUT[toggle:checkbox18]`|`INPUT[toggle:equipped18]`
>>|19|`INPUT[text:title19]`|`INPUT[toggle:checkbox19]`|`INPUT[toggle:equipped19]`
>>|20|`INPUT[text:title20]`|`INPUT[toggle:checkbox20]`|`INPUT[toggle:equipped20]`
>>|21|`INPUT[text:title21]`|`INPUT[toggle:checkbox21]`|`INPUT[toggle:equipped21]`
>>|22|`INPUT[text:title22]`|`INPUT[toggle:checkbox22]`|`INPUT[toggle:equipped22]`
>>|23|`INPUT[text:title23]`|`INPUT[toggle:checkbox23]`|`INPUT[toggle:equipped23]`
>>|24|`INPUT[text:title24]`|`INPUT[toggle:checkbox24]`|`INPUT[toggle:equipped24]`
>>|25|`INPUT[text:title25]`|`INPUT[toggle:checkbox25]`|`INPUT[toggle:equipped25]`
>>|26|`INPUT[text:title26]`|`INPUT[toggle:checkbox26]`|`INPUT[toggle:equipped26]`
>>|27|`INPUT[text:title27]`|`INPUT[toggle:checkbox27]`|`INPUT[toggle:equipped27]`
>>|28|`INPUT[text:title28]`|`INPUT[toggle:checkbox28]`|`INPUT[toggle:equipped28]`
>>|29|`INPUT[text:title29]`|`INPUT[toggle:checkbox29]`|`INPUT[toggle:equipped29]`
>>|30|`INPUT[text:title30]`|`INPUT[toggle:checkbox30]`|`INPUT[toggle:equipped30]`
>>|31|`INPUT[text:title31]`|`INPUT[toggle:checkbox31]`|`INPUT[toggle:equipped31]`
>>|32|`INPUT[text:title32]`|`INPUT[toggle:checkbox32]`|`INPUT[toggle:equipped32]`
>>|33|`INPUT[text:title33]`|`INPUT[toggle:checkbox33]`|`INPUT[toggle:equipped33]`
>>|34|`INPUT[text:title34]`|`INPUT[toggle:checkbox34]`|`INPUT[toggle:equipped34]`
>>|35|`INPUT[text:title35]`|`INPUT[toggle:checkbox35]`|`INPUT[toggle:equipped35]`
>>|36|`INPUT[text:title36]`|`INPUT[toggle:checkbox36]`|`INPUT[toggle:equipped36]`
>>|37|`INPUT[text:title37]`|`INPUT[toggle:checkbox37]`|`INPUT[toggle:equipped37]`
>>|38|`INPUT[text:title38]`|`INPUT[toggle:checkbox38]`|`INPUT[toggle:equipped38]`
>>|39|`INPUT[text:title39]`|`INPUT[toggle:checkbox39]`|`INPUT[toggle:equipped39]`
>>|40|`INPUT[text:title40]`|`INPUT[toggle:checkbox40]`|`INPUT[toggle:equipped40]`
>
>>[!danger] %%FAKE TITLE HERE%%
>>### Magic
>>|     |     |
>> |--- | --- |
>>|**Name** | `=this.Spell1`|
>>|**CL** |  `=this.Spell1cl`|
>> | **Description**     | `=this.Spell1des` | 
>>|**Name** | `=this.Spell2`|
>>|**CL** |  `=this.Spell2cl`|
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





