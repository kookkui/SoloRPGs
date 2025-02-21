---
axp: 
xp: 31
immune1: false
---
>[!dice] %%FAKE TITLE HERE%%
>> [!dice] %%FAKE TITLE HERE%%  
>> # `=this.file.name`
>> ![[Character Image Placeholder]]
>> ###### Stats
>>|     |     |
>> |--- | --- |
>>|**Level**| `=this.level`|
>>|**Health** | **Current:** `0` **Max:** `=this.health`|
>>|**Toughness** |  **Current:** `0` **Max:** `=this.toughness`|
>> |**Aether** |  **Current:** `0` **Max:** `=this.aether` |
>> |**Santy** |  **Current:** `0` **Max:** `=this.santy` |
>> |**Exhaustion** | **Current:** `0` **Resistance:** `=this.Exhaustion` |
>> | **Magic Resistance**     | `=this.mresist` | 
>> | **Damage Modifier**     | `=this.dmod` | 
>> |**XP** | `VIEW[{xp}][text]`|
>>|**ADD XP**| `INPUT[number:axp]` `BUTTON[exp]`|
>>
>>---
>>
>> ###### Weapons
>>| **Weapons** | **Skill** | **Notes** |
>>| -------------- | --------------- | ------------- |
>>| `=this.Weapon1` | `=this.Weapon1skill` | `=this.Weapon1notes` |
>>| `=this.Weapon2` | `=this.Weapon2skill` | `=this.Weapon2notes` |
>>| `=this.Weapon3` | `=this.Weapon3skill` | `=this.Weapon3notes` |
>>|`=this.Weapon4` |`=this.Weapon4skill` | `=this.Weapon4notes` |
>>| | | |
>>
>>---
>>
>> ###### Armor
>>| **Name** | **Protection Rate** | **Integrity** | **Notes**|
>>| ---------------------- | --------------- | ------------- | ------------- |
>>| `=this.Armor` | `=this.ArmorPR` | `=this.Armorintegrity` | `=this.armornotes`
>>| `=this.Shield` | `=this.ShieldPR` | `=this.Shieldintegrity` | `=this.armor2notes`
>>| `=this.Helmet` | `=this.HelmetPR` | `=this.Helmetintegrity` | `=this.armor3notes`
>>| | | |
>>
>>##### Currency and Provisions
>>|     |     |
>> |--- | --- |
>>|**Coins (¢)** |`=this.Currency` |
>> |**Crafting Supplies** |`=this.csupplies` |
>> |**Cooking Supplies** |`=this.cooksupplies` |
>>| **Rations**   |  `=this.rations`   |
>>
>
>>[!error] %%FAKE TITLE HERE%%
>>|     |     |
>> |--- | --- |
>> |**Tension Die**| **Lair/Domain Exit Die**|
>>|***D10 > D8 > D6 > D4***|***D12 > D10 > D8 > D6 > D4***
>>|`0/4`| `0/5`
>
>>[!infobox] %%FAKE TITLE HERE%%
>>|     |     |
>> |--- | :---: |
>>|**Personal Goals** |`=this.pgoal1` |
>>||`=this.pgoal2` |
>>|**Lightsource** |`0/10` |
>>||`0/10` |
>>
>>&nbsp;
>>
>> ### Skill Checks
>>| **Skill Name** | **Skill Level** | **Skill Name** | **Skill Level** |
>>| :-: | :-: |:-: | :-: |
>>| **Acrobatics** (10) | `10` | **Scavenge** | `0`|
>>| **Athletics** (10) | `10` |**Shafted Weapons** | `0` |
>>| **Bladed Weapons**| `0` |**Stealth** | `0` |
>>| **Bludgeoning Weapons** | `0` | **Thievery** | `0` |
>>| **Dodge** (10) | `10` |**Unarmed Combat/Fist Weapons** | `0`|
>>| **Endurance**| `0` | **Medicine** |`0`|
>>| **Perception** (20) | `20` |**Resolve** (10) | `10` |
>>| **Reason**  | `0` | 
>
>
>>[!important] %%FAKE TITLE HERE%%
>>##### Masteries
>>|     |     |
>> |---- | ---------- |
>>|**Mastery** | `=this.mastery1`|
>>|**Passive** |  `=this.mastery1Passive`|
>> |**Tier 1**  |  `=this.mastery1tier1` |
>> |**Tier 2**   | `=this.mastery1tier2` | 
>> |**Tier 3** |`=this.mastery1tier3` |
>> |**Tier 4** | `=this.mastery1tier4`|
>> |**Tier 5** | `=this.mastery1tier5` |
>>
>>&nbsp;
>>
>>|     |     |
>> |---- | ---------- |
>>|**Mastery** | `=this.mastery2`|
>>|**Passive** |  `=this.mastery2Passive`|
>> |**Tier 1**  |  `=this.mastery2tier1` |
>> |**Tier 2**   | `=this.mastery2tier2` | 
>> |**Tier 3** |`=this.mastery2tier3` |
>> |**Tier 4** | `=this.mastery2tier4`|
>> |**Tier 5** | `=this.mastery2tier5` |
>>
>>&nbsp;
>>
>>|     |     |
>> |---- | ---------- |
>>|**Mastery** | `=this.mastery3`|
>>|**Passive** |  `=this.mastery3Passive`|
>> |**Tier 1**  |  `=this.mastery3tier1` |
>> |**Tier 2**   | `=this.mastery3tier2` | 
>> |**Tier 3** |`=this.mastery3tier3` |
>> |**Tier 4** | `=this.mastery3tier4`|
>> |**Tier 5** | `=this.mastery3tier5` |
>>##### Perks
>> |        |         |   
>>| :-: | :----- |
>>| 1 | `=this.perk0` |
>>| 2 | `=this.perk1` |
>>| 3 | `=this.perk2` |
>>| 4 | `=this.perk3` |
>>| 5 | `=this.perk` |
>>| 6 |`=this.perk5` |
>>| 7 | `=this.perk6` |
>>
>>### Equipped Gear
>>| | |
>>|:-:|:-:|
>>|**Main Hand** | `=this.mainhand`|
>>|**Off Hand** | `=this.offhand`|
>>|**Belt** | `=this.belt`|
>>| **Helmet** | `=this.helmet` |
>>| **Armor** | `=this.armor` |
>>|**Gloves** | `=this.gloves`|
>>| **Boots** | `=this.boots` |
>>| **Amulet** | `=this.amulet` |
>>| **Ring 1** | `=this.ring1` |
>>| **Ring 2** | `=this.ring2` |
>
>>[!table] %%FAKE TITLE HERE%%
>>### Gear
>>| Slot | Encumbering Items | Slot| Belt Quickslots
>>| :-: | :---------------- |:-: | :---------------- |
>>|1|`INPUT[text:gear1]` |1|`INPUT[text:qbelt1]` | 
>>|2|`INPUT[text:gear2]` | 2|`INPUT[text:qbelt2]` | 
>>|3|`INPUT[text:gear3]` |3|`INPUT[text:qbelt3]` | 
>>|4|`INPUT[text:gear4]` |4|`INPUT[text:qbelt4]` | 
>>|5|`INPUT[text:gear5]` |
>>|6|`INPUT[text:gear6]` |
>>|7|`INPUT[text:gear7]` |
>>|9|`INPUT[text:gear9]` |
>>|10|`INPUT[text:gear10]` |
>>
>>### Backpack
>>| Slot | Encumbering Items | Slot | Encumbering Items 
>>| :-: | :---------------- |--------|--------|
>>|1|`INPUT[text:title1]` |11|`INPUT[text:title11]`|
>>|2|`INPUT[text:title2]`|12|`INPUT[text:title12]`|
>>|3|`INPUT[text:title3]`|13|`INPUT[text:title13]`|
>>|4|`INPUT[text:title4]`|14|`INPUT[text:title14]`|
>>|5|`INPUT[text:title5]`|15|`INPUT[text:title15]`|
>>|6|`INPUT[text:title6]`|16|`INPUT[text:title16]`|
>>|7|`INPUT[text:title7]`|17|`INPUT[text:title17]`|
>>|8|`INPUT[text:title8]`|18|`INPUT[text:title18]`|
>>|9|`INPUT[text:title9]`|19|`INPUT[text:title19]`|
>>|10|`INPUT[text:title10]`|20|`INPUT[text:title20]`|
>>
>>### Pouches
>>| Slot | Pouch | Slot | Pouch
>>| :-: | :---------------- |--------|--------|
>>|1|`INPUT[text:pouch1]` |1|`INPUT[text:pouch11]`|
>>|2|`INPUT[text:pouch2]`|2|`INPUT[text:pouch12]`|
>>|3|`INPUT[text:pouch3]`|3|`INPUT[text:pouch13]`|
>>|4|`INPUT[text:pouch4]`|4|`INPUT[text:pouch14]`|
>>|5|`INPUT[text:pouch5]`|5|`INPUT[text:pouch15]`|
>>|1|`INPUT[text:pouch6]`|
>>|2|`INPUT[text:pouch7]`|
>>|3|`INPUT[text:pouch8]`|
>>|4|`INPUT[text:pouch9]`|
>>|5|`INPUT[text:pouch10]`|
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
>
>>[!error] %%FAKE TITLE HERE%%
>> ### Damage Vulnerabilities and Resistances
>>|Damage Type|Immune|Vulnerable|Resistant|Restored|Reduntion|
>>|---|---|---|---|---|---|
>>|Acid|`INPUT[toggle:immune1]`|`INPUT[toggle:vulnerable1]`|`INPUT[toggle:resistant1]`|`INPUT[toggle:restorted1]`||
>>|Air|`INPUT[toggle:immune2]`|`INPUT[toggle:vulnerable2]`|`INPUT[toggle:resistant2]`|`INPUT[toggle:restorted2]`||
>>|Arcane|`INPUT[toggle:immune3]`|`INPUT[toggle:vulnerable3]`|`INPUT[toggle:resistant3]`|`INPUT[toggle:restorted3]`||
>>|Bludgeoning|`INPUT[toggle:immune4]`|`INPUT[toggle:vulnerable4]`|`INPUT[toggle:resistant4]`|`INPUT[toggle:restorted4]`||
>>|Cold|`INPUT[toggle:immune5]`|`INPUT[toggle:vulnerable5]`|`INPUT[toggle:resistant5]`|`INPUT[toggle:restorted5]`||
>>|Earth|`INPUT[toggle:immune6]`|`INPUT[toggle:vulnerable6]`|`INPUT[toggle:resistant6]`|`INPUT[toggle:restorted6]`||
>>|Fire|`INPUT[toggle:immune7]`|`INPUT[toggle:vulnerable7]`|`INPUT[toggle:resistant7]`|`INPUT[toggle:restorted7]`||
>>|Holy|`INPUT[toggle:immune8]`|`INPUT[toggle:vulnerable8]`|`INPUT[toggle:resistant8]`|`INPUT[toggle:restorted8]`||
>>|Infernal|`INPUT[toggle:immune9]`|`INPUT[toggle:vulnerable9]`|`INPUT[toggle:resistant9]`|`INPUT[toggle:restorted9]`||
>>|Necrotic|`INPUT[toggle:immune10]`|`INPUT[toggle:vulnerable10]`|`INPUT[toggle:resistant10]`|`INPUT[toggle:restorted10]`||
>>|Piercing|`INPUT[toggle:immune11]`|`INPUT[toggle:vulnerable11]`|`INPUT[toggle:resistant11]`|`INPUT[toggle:restorted11]`||
>>|Poison|`INPUT[toggle:immune12]`|`INPUT[toggle:vulnerable12]`|`INPUT[toggle:resistant12]`|`INPUT[toggle:restorted12]`||
>>|Psychic|`INPUT[toggle:immune13]`|`INPUT[toggle:vulnerable13]`|`INPUT[toggle:resistant13]`|`INPUT[toggle:restorted13]`||
>>|Slashing|`INPUT[toggle:immune14]`|`INPUT[toggle:vulnerable14]`|`INPUT[toggle:resistant14]`|`INPUT[toggle:restorted14]`||
>>|Water(elemental)|`INPUT[toggle:immune15]`|`INPUT[toggle:vulnerable15]`|`INPUT[toggle:resistant15]`|`INPUT[toggle:restorted15]`||



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



