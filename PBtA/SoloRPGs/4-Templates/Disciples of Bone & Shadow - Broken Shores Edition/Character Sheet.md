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
Weapon1dmg: d6
Weapon1notes: Its badass
Weapon2: Placeholder
Weapon2dmg: d8
Weapon2notes: Its badass
Weapon3: Placeholder
Weapon3dmg: d10
Weapon3notes: Its badass
Armor: Plate Mail
ArmorPR: D8+1
Armorintegrity: D12
Shield: Large
ShieldPR: 30
Shieldintegrity: D8
DmgTkn: 0
TempHP: 0
Currency: 0
Provisions: 0
shards: 10
csupplies: 10
rations: 10
Spell1: Enthrall
Spell2: Summon Minor Demon
CurrentFatigue: 15
CurrentHP: 20
---
>[!dice] %%FAKE TITLE HERE%%
>> [!dice] %%FAKE TITLE HERE%%  
>> # `=this.file.name`
>> `=this.Art`
>>```meta-bind
>>INPUT[progressBar(class(green-progress-bar), maxValue(20), title(HP)):CurrentHP]
>>```
>>```meta-bind
>>INPUT[progressBar(class(blue-progress-bar), maxValue(10), title(PP)):CurrentFatigue]
>>```
>> ##### Stats
>>|     |     |
>> |--- | --- |
>>|**Level** | **`=this.Level`**|
>>|**Max HP** | **`=this.CONST*2`**|
>>|**Max Power Points** | **`=this.WIL`**|
>>|**Corruption** |  **Current:** `0` **Max:** `10`|
>> |**Speed** |  **Walk:** `=this.DEX*2`' **Run:** `=this.DEX*4`' |
>> | **Max Gear Slots**     | `=(this.STR)+10` | 
>>
>>&nbsp;
>>
>> ##### Weapons
>>| **Weapons** | **Damage** | **Notes** |
>>| ---------------------- | --------------- | ------------- |
>>| `=this.Weapon1` | `=this.Weapon1dmg` | `=this.Weapon1notes` |
>>| `=this.Weapon2` | `=this.Weapon2dmg` | `=this.Weapon2notes` |
>>| `=this.Weapon3` | `=this.Weapon3dmg` | `=this.Weapon3notes` |
>>
>>&nbsp;
>>
>> ##### Armor
>>| **Name** | **Protection Rate** | **Integrity** | **Notes**|
>>| ---------------------- | --------------- | ------------- | ------------- |
>>| `=this.Armor` | `=this.ArmorPR` | `=this.Armorintegrity` | `=this.Armornote1`
>>| `=this.Shield` | `=this.ShieldPR` | `=this.Shieldintegrity` |`=this.Armornote2`
>>| `=this.Helmet` | `=this.HelmetPR` | `=this.Helmetintegrity` |`=this.Armornote3`
>>
>>&nbsp;
>>
>> ##### Supplies
>>  | 
>>---|---|
>>**Jats**|`=this.currency` |
>>**Sellsword Cut**| `VIEW[{ajats} * {merc}]`
**Shards**|`0` |
>>**Rations**|`0` |
>>**Crafting Supplies** |`0` |
>>**Torches**|`0` |
>>**Lamp Oil**|`16` |
>>**Lockpicks**| `INPUT[inlineSelect(option(D12), option(D10), option(D8), option(D6), option(D4), option(None)):Lockpicks1]`|
>>**Sellsword jats**|  `INPUT[number:ajats]` `BUTTON[pjats]`|
>>**Add jats**|  `INPUT[number:awjats]` `BUTTON[pwjats]`|
>>
>>&nbsp;
>>

## Stats
>[!thing] %%FAKE TITLE HERE%%
>>[!travel] %%FAKE TITLE HERE%%
>> ### Stats
>> |        |         |   | |
>>| ---- | ---- | ---- |---- |
>>| **Strength**   | `=this.STR`  | **Brawn** | `=(this.STR)*5`|
>>| **Dexterity**    | `=this.DEX` |**Coordination** | `=(this.DEX)*5`|
>>| **Constitution** | `=this.CONST` | **Vitality**|`=(this.CONST)*5`|
>>| **Will**         |  `=this.WIL` | **Tenacity**|`=(this.WIL)*5`|
>>| **Intelligence** |  `=this.INT` | **Intellect**|`=(this.INT)*5`|
>>| **Charisma**     | `=this.CHA` | **Charm**|`=(this.CHA)*5`|
>>
>> &nbsp;
>>
>> ### Skill Up Points
> | **Skill Up Points** | 
>>|:---:|
>>|`boxes,green,30: 0/12`| |
>>
>>
>> &nbsp;
>>
>> ### Skill Checks
>>| **Skill Name** | **Skill Level** | Level Up
>>| ------------------------- | ----------- | ----------- |
>>| **Acrobatics**(DEX `=this.DEX`) | `10` | `INPUT[toggle:skill1]`|
>>| **Alchemy** (INT `=this.INT`)| `10` | `INPUT[toggle:skill23]`|
>>| **Athletics** (STR `=this.STR`) | `10` | `INPUT[toggle:skill2]`|
>>| **Animal Handling** (CHA `=this.CHA`) | `10` |`INPUT[toggle:skill3]`|
>>| **Command** (CHA `=this.CHA`) | `10` |`INPUT[toggle:skill4]`|
>>| **Crafting** (DEX `=this.DEX`) | `10` |`INPUT[toggle:skill5]`|
>>| **Dodge** (DEX `=this.DEX` ) | `10` |`INPUT[toggle:skill6]`|
>>| **Forbidden Lore** | `0` |`INPUT[toggle:skill24]`|
>>| **Insight** (WIL `=this.WIL`) | `10` |`INPUT[toggle:skill7]`|
>>| **Literacy** (INT `=this.INT`) | `10` |`INPUT[toggle:skill8]`|
>>| **Manipulation** (CHA `=this.CHA`) | `10` | `INPUT[toggle:skill9]`|
>>| **Melee Weapons** (STR `=this.STR`) | `10` |`INPUT[toggle:skill10]`
>>| **Medicine** (INT `=this.INT`) | `10` |`INPUT[toggle:skill11]`
>>| **Nature** (INT `=this.INT`) | `10` |`INPUT[toggle:skill12]`
>>| **Perception** (WIL `=this.WIL`) | `10` |`INPUT[toggle:skill13]`
>>| **Performance** (CHA `=this.CHA`) | `10` |`INPUT[toggle:skill14]`
>>| **Ranged Weapons** (DEX `=this.DEX` ) | `10` |`INPUT[toggle:skill15]`
>>| **Sailing** (DEX `=this.DEX`) | `10` |`INPUT[toggle:skill16]`
>>| **Siege Weapons** (DEX `=this.DEX`) | `10` |`INPUT[toggle:skill17]`
>>| **Sleight of Hand** (DEX `=this.DEX` ) | `10` |`INPUT[toggle:skill19]`
>>| **Stealth** (DEX `=this.DEX`) | `10` |`INPUT[toggle:skill20]`
>>| **Survival** (INT `=this.INT` ) | `10` |`INPUT[toggle:skill21]`
>>|**Traditional Lore** (20) | `20` |`INPUT[toggle:skill25]`
>>| **Unarmed** (STR `=this.STR`) | `10` |`INPUT[toggle:skill22]`
>>

## Talents
>[!rng] %%FAKE TITLE HERE%%
>>[!rng] %%FAKE TITLE HERE%%
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

## Inventory
>[!table_time] %%FAKE TITLE HERE%%
>>[!table_time] %%FAKE TITLE HERE%%
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
>> ### Non-Incumbering Items
>> |Slot| Item |Slot| Item 
>>| :-: | :---------------------------- |:-: | :---------------------------- |
>>| 1 | `INPUT[text:Pskills69]` | 9 | `INPUT[text:Pskills8]` |
>>| 2 | `INPUT[text:Pskills1]` | 10 | `INPUT[text:Pskills9]` |
>>| 3 | `INPUT[text:Pskills2]` |11 | `INPUT[text:Pskills10]` |
>>| 4 | `INPUT[text:Pskills3]` | 12 | `INPUT[text:Pskills11]` |
>>| 5 | `INPUT[text:Pskills4]` |13 | `INPUT[text:Pskills12]` |
>>| 6 |`INPUT[text:Pskills5]` |14 | `INPUT[text:Pskills13]` |
>>| 7 | `INPUT[text:Pskills6]` | 15 | `INPUT[text:Pskills14]` |
>>| 8 | `INPUT[text:Pskills7]` |16 | `INPUT[text:Pskills15]` |

### Sorcery
 
`=this.Spell1`


---

`=this.Spell2`


---


`=this.Spell3`


---


`=this.Spell4`


---


`=this.Spell5`


------


`=this.Spell6`


---


`=this.Spell7`


---


`=this.Spell8`


---


`=this.Spell9`


---


`=this.Spell10`


---



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

```meta-bind-button
label: Merc Jats
icon: ""
style: primary
class: ""
cssStyle: ""
backgroundImage: ""
tooltip: ""
id: pjats
hidden: True
actions:
- type: updateMetadata
  bindTarget: currency
  evaluate: True
  value: getMetadata('ajats') * '0.6' + getMetadata('currency')

```

```meta-bind-button
label: Add Jats
icon: ""
style: primary
class: ""
cssStyle: ""
backgroundImage: ""
tooltip: ""
id: pwjats
hidden: True
actions:
- type: updateMetadata
  bindTarget: currency
  evaluate: True
  value: getMetadata('currency') + getMetadata('awjats')

```

