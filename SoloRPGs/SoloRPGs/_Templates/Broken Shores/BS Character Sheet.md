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
water: 10
Godshard: Axor, God of the Earth
GodshardPassive: "**Inspiring Might.** Both you and any ally in a 10 ft radius receives +1 Armor. This ability is always active."
GodshardActive1: "**Earthbound.** Cost: 4  Range: 20 ft  Resisted: No  Duration: Special You gain an amount of temporary HP equal to your STR. Choose a target: each time they receive damage, it is transferred to you instead, until you run out of temporary HP."
Spell1: Enthrall
Spell1pp: 5
Spell1idio: This spell can only be cast at touch range
Spell1des: "Range: 30 ft / Resisted: Yes / Duration: WIL turns \rThe target becomes Charmed. An ethereal rope shoots from the sorcerer’s head to the target’s heart, becoming invisible to all but the sorcerer."
Spell2: Summon Minor Demon
Spell2pp: "10"
Spell2idio: The spell cleanses a negative condition from the sorcerer
Spell2des: "Range: 30 ft / Resisted: No / Duration: WIL turns In order to cast this spell, the sorcerer needs to sacrifice 3 HP. It takes 3 rounds to complete this spell, resulting in the summoning of a minor demon, as described on page 126. The demon is bound to the sorcerer until the spell duration is over, and will obey their commands."
Spell1mem: false
---
>[!dice] %%FAKE TITLE HERE%%
>> [!dice] %%FAKE TITLE HERE%%  
>> # `=this.file.name`
>> ![[Character Image Placeholder]]
>> ###### Stats
>>|     |     |
>> |--- | --- |
>>|**HP** | **Current:** `0` **Max:** `=this.CONST*2`|
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
>>
>>
>> ### Skill Checks
>>| **Skill Name** | **Skill Level** | Level Up
>>| ------------------------- | ----------- | ----------- |
>>| **Acrobatics**(DEX `=this.DEX`) | `10` | `INPUT[toggle:skill1]`|
>>| **Athletics** (STR `=this.STR`) | `10` | `INPUT[toggle:skill2]`|
>>| **Animal Handling** (CHA `=this.CHA`) | `10` |`INPUT[toggle:skill3]`|
>>| **Command** (CHA `=this.CHA`) | `10` |`INPUT[toggle:skill4]`|
>>| **Crafting** (DEX `=this.DEX`) | `10` |`INPUT[toggle:skill5]`|
>>| **Dodge** (DEX `=this.DEX` ) | `10` |`INPUT[toggle:skill6]`|
>>| **Insight** (WIL `=this.WIL`) | `10` |`INPUT[toggle:skill7]`|
>>| **Literacy** (INT `=this.INT`) | `10` |`INPUT[toggle:skill8]`|
>>|**Manipulation** (CHA `=this.CHA`) | `10` | `INPUT[toggle:skill9]`|
>>| **Martial Weapons** (STR `=this.STR`) | `10` |`INPUT[toggle:skill10]`
>>| **Medicine** (INT `=this.INT`) | `10` |`INPUT[toggle:skill11]`
>>|**Nature** (INT `=this.INT`) | `10` |`INPUT[toggle:skill12]`
>>| **Perception** (WIL `=this.WIL`) | `10` |`INPUT[toggle:skill13]`
>>| **Performance** (CHA `=this.CHA`) | `10` |`INPUT[toggle:skill14]`
>>| **Ranged Weapons** (DEX `=this.DEX` ) | `10` |`INPUT[toggle:skill15]`
>>| **Sailing** (DEX `=this.DEX`) | `10` |`INPUT[toggle:skill16]`
>>| **Siege Weapons** (DEX `=this.DEX`) | `10` |`INPUT[toggle:skill17]`
>>| **Simple Melee Weapons** (STR `=this.STR`) | `10` |`INPUT[toggle:skill18]`
>>| **Sleight of Hand** (DEX `=this.DEX` ) | `10` |`INPUT[toggle:skill19]`
>>| **Stealth** (DEX `=this.DEX`) | `10` |`INPUT[toggle:skill20]`
>>| **Survival** (INT `=this.INT` ) | `10` |`INPUT[toggle:skill21]`
>>| **Unarmed** (STR `=this.STR`) | `10` |`INPUT[toggle:skill22]`
>
>
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
>> |**Earth Essence** (+1 Armor) | `2/4` |
>> |**Fire Essence** (+1 Damage) | `0/4` |
>> |**Water Essence** (+2 HP) | `0/4` |
>> |**Air Essence** (+2 PP) | `0/4` |
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



