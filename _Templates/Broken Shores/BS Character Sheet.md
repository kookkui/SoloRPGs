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
Armor: Plate Mail
ArmorPR: D8+1
Armorintegrity: D12
Shield: Large
ShieldPR: +30
Shieldintegrity: D8
DmgTkn: 0
TempHP: 0
Currency: 0
Provisions: 0
shards: 10
csupplies: 10
rations: 10
water: 10
---
>[!dice] %%FAKE TITLE HERE%%
>> [!dice] %%FAKE TITLE HERE%%  
>> # `=this.file.name`
>> ![[Character Image Placeholder]]
>> ###### Stats
>>|     |     |
>> |--- | --- |
>>|**HP** | `=this.HP - this.DmgTkn + this.TempHP`|
>>|**Power Points** |  **Current:** `0` **Max:** `=this.WIL`|
>> |**Speed** |  **Walk:** `=this.DEX*2` **Run:** `=this.DEX*4` |
>> | **Max Gear Slots**     | `=(this.STR)+10` | 
 >> |**Armor** | `=this.Armor` |
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
>>| `=this.Armor` | `=this.ArmorPR` | `=this.Armorintegrity` | `INPUT[text:Armornote1]`
>>| `=this.Shield` | `=this.ShieldPR` | `=this.Shieldintegrity` |`INPUT[text:Armornote2]`
>>| `=this.Helmet` | `=this.HelmetPR` | `=this.Helmetintegrity` |`INPUT[text:Armornote3]`
>>| | | |
>>
>>##### Currency and Provisions
>>|     |     |
>> |--- | --- |
>>|**Coins (Ҁ)** |`=this.Currency` |
>>|**Shards** | `=this.advantages`|
>> |**Crafting Supplies** |`=this.csupplies` |
>>| **Rations**   |  `=this.rations`   |
>>| **Water**(Gal)   |  `=this.water`   |
>
>>[!infobox] %%FAKE TITLE HERE%%
>> ### Stats
>> |        |         |   | |
>>| ---- | ---- | ---- |---- |
>>| **Strength**   | `=this.STR`  | **Brawn** | `=(this.STR)*5`|
>> |    `0/10`   |         |   | |
>>| **Dexterity**    | `=this.DEX` |**Coordination** | `=(this.DEX)*5`|
>> |    `0/10`   |         |   | |
>>| **Constitution** | `=this.CONST` | **Vitality**|`=(this.CONST)*5`|
>> |    `0/10`   |         |   | |
>>| **Will**         |  `=this.WIL` | **Tenacity**|`=(this.WIL)*5`|
>> |    `0/10`   |         |   | |
>>| **Intelligence** |  `=this.INT` | **Intellect**|`=(this.INT)*5`|
>> |    `0/10`   |         |   | |
>>| **Charisma**     | `=this.CHA` | **Charm**|`=(this.CHA)*5`|
>> |    `0/10`   |         |   | |
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
>>
>> ### Passive Skills
>> |Slot| 
>>| :-: | :----------------------------------------------------------------------------------------------------------------------------------- |
>>| 1 | `INPUT[text:Pskills69]` |
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