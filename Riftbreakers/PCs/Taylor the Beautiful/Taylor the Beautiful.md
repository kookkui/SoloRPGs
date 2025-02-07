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
gear1name: 
gear1magic:
gear1magic2:
gear1quirk:
gear1notes:
gear2name: 
gear2magic:
gear2magic2:
gear2quirk:
gear2notes:
gear3name: 
gear3magic:
gear3magic3:
gear3quirk:
gear3notes:
gear4name: 
gear4magic:
gear4magic4:
gear4quirk:
gear4notes:
gear6name: Victorious Gloves of the Whisper
gear6magic: Constitution +1 Charisma +1
gear6magic6:
gear6quirk: Smells like rotten flesh
gear6rank: Novice
gear6notes: 200A, Air Earth
gear7name: Champion's Ring of the Snake
gear7magic: Dexterity +1, Reduce your Stamina pool by 5 (26), but increase your Aether pool by 8 (23). 
gear7magic7: You no longer need to eat or drink.
gear7quirk: It's always pristine
gear7rank: Novice
gear7notes: 300A Air Life 2x Boon Bane
gear8name: Mage's Wonderful Ring
gear8magic: Stamina +8, On command, this item works as a source of light.
gear8magic8: Illuminates in a 20 m. radius.
gear8quirk: It's always covered in a layer of mucus
gear8rank: Novice
gear8notes: 300A Fire 2xPower Light
gear9name: Knight's Glass Stone
gear9magic: You can detect all living beings in a 20 m. radius.
gear9magic9: Increase your luck by +5
gear9quirk: It appears to be completely made of glass. It doesn't make it more fragile than it should be though
gear9rank: Novice
gear9notes: Chaos Life Boon Light 200A  Rarity:Uncommon
title1: Backpack
title2: Extra-Dimensional bag x 0
title3: Quiver
title4: Bandage Ud12
title5: Arrows ud12
title6: Rations x 2
title7: Torch Ud10
title8: Ascended Essence (prime)
title9: Lantern
title10: Aetheryte
title11: "Stoneskin Potion. for the next hour you have +1 armor, but your dodge and acrobatics skills are reduced by -10. aspects: stone, boon"
title12: Aetheryte
title13: Rough Eather x 10
proficiency1: "**Weapon:** Longbow"
proficiency2: "**Weapon:** Scimitar"
proficiency3: "**Armor:** Soft Leather"
title21: ""
title15: ""
Hearts:
  - Restoration
  - Arrow
  - Ritual
  - Elemental
passive0: "**Restoration Heart**: *Dampening Aura* Reduce all incoming damage by -1 to all allies in a 10 m radius."
passive1: "**Arrow Heart**: *Marksman* You suffer no penalty from firing a ranged weapon at melee range. Increase the range of your equipped ranged weapons by +50 m."
passive2: "**Ritual Heart**: *Arcane Storage* You can summon a chest that has 10 item slots. This power gains +10 item slots per rank."
Heart1: Arrow
Heart2: Elemental
Heart3: Restoration
Heart4: Ritual
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
>> **Aether** | `31` /`VIEW[{WIL} + {INT} + 8]` |
>> **Stamina** | `36` /`VIEW[{STR} + {CON}+ 8]` |
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

>[!important] %%FAKE TITLE HERE%%
>>[!travel] %%FAKE TITLE HERE%%
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
>
>>[!travel] %%FAKE TITLE HERE%%
>> ### Skill Checks
>>| **Skill Name** | **Skill Level** |
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
>
>>[!travel] %%FAKE TITLE HERE%%
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
>>

>[!table] %%FAKE TITLE HERE%%
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
>>|9|`INPUT[text:title9]`|29|`INPUT[text:title29]`|
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

>[!travel] %%FAKE TITLE HERE%%
>>[!travel] %%FAKE TITLE HERE%%
>>## Gear
>> &nbsp;
>>
>>### Head
>>|     |     |
>>|--- | --- |
>>|**Name** | `=this.gear1name`|
>>|**Magic** |  `=this.gear1magic`|
>>|   | `=this.gear1magic2` | 
>>|**Quirk** |  `=this.gear1quirk`|
>>| **Rank**     | `=this.gear1rank` | 
>>| **Notes**     | `=this.gear1notes` | 
>> 
>> &nbsp;
>>### Chest
>>|     |     |
>>|--- | --- |
>>|**Name** | `=this.gear2name`|
>>|**Magic** |  `=this.gear2magic`|
>>|   | `=this.gear2magic2` | 
>>|**Quirk** |  `=this.gear2quirk`|
>>| **Rank**     | `=this.gear2rank` | 
>>| **Notes**     | `=this.gear2notes` | 
>> &nbsp;
>> 
>>### Belt
>>|     |     |
>>|--- | --- |
>>|**Name** | `=this.gear3name`|
>>|**Magic** |  `=this.gear3magic`|
>>|   | `=this.gear3magic3` | 
>>|**Quirk** |  `=this.gear3quirk`|
>>| **Rank**     | `=this.gear3rank` | 
>>| **Notes**     | `=this.gear3notes` | 
>> &nbsp;
>> 
>>### Pants
>>|     |     |
>>|--- | --- |
>>|**Name** | `=this.gear4name`|
>>|**Magic** |  `=this.gear4magic`|
>>|   | `=this.gear4magic4` | 
>>|**Quirk** |  `=this.gear4quirk`|
>>| **Rank**     | `=this.gear4rank` | 
>>| **Notes**     | `=this.gear4notes` | 
>> &nbsp;
>>
>>### Gloves
>>|     |     |
>>|--- | --- |
>>|**Name** | `=this.gear6name`|
>>|**Magic** |  `=this.gear6magic`|
>>|   | `=this.gear6magic6` | 
>>|**Quirk** |  `=this.gear6quirk`|
>>| **Rank**     | `=this.gear6rank` | 
>>| **Notes**     | `=this.gear6notes` | 
>> &nbsp;
>> 
>>### Boots
>>|     |     |
>>|--- | --- |
>>|**Name** | `=this.gear5name`|
>>|**Magic** |  `=this.gear5magic`|
>>|   | `=this.gear5magic5` | 
>>|**Quirk** |  `=this.gear5quirk`|
>>| **Rank**     | `=this.gear5rank` | 
>>| **Notes**     | `=this.gear5notes` | 
>> &nbsp;
>> 
>>### Ring 1
>>|     |     |
>>|--- | --- |
>>|**Name** | `=this.gear7name`|
>>|**Magic** | `=this.gear7magic`|
>>| | `=this.gear7magic7` |
>>|**Quirk** | `=this.gear7quirk`|
>>| **Rank** | `=this.gear7rank` |
>>| **Notes** | `=this.gear7notes` |
>> &nbsp;
>> 
>>### Ring 2
>>|     |     |
>>|--- | --- |
>>|**Name** | `=this.gear8name`|
>>|**Magic** | `=this.gear8magic`|
>>| | `=this.gear8magic8` |
>>|**Quirk** | `=this.gear8quirk`|
>>| **Rank** | `=this.gear8rank` |
>>| **Notes** | `=this.gear8notes` |
>> &nbsp;
>>
>>### Other
>>|     |     |
>>|--- | --- |
>>|**Name** | `=this.gear9name`|
>>|**Magic** | `=this.gear9magic`|
>>| | `=this.gear9magic9` |
>>|**Quirk** | `=this.gear9quirk`|
>>| **Rank** | `=this.gear9rank` |
>>| **Notes** | `=this.gear9notes` |

>[!dice] %%FAKE TITLE HERE%%
>>[!dice] %%FAKE TITLE HERE%%
>>## Hearts
>> |        |     |   
>>| :-: | :----- |
>>| 1 | `INPUT[inlineSelect(option(Arcane), option(Arrow), option(Bastion), option(Blade), option(Elemental), option(Might), option(Restoration), option(Ritual), option(Shadow)):Heart1]` |
>>| 2 |  `INPUT[inlineSelect(option(Arcane), option(Arrow), option(Bastion), option(Blade), option(Elemental), option(Might), option(Restoration), option(Ritual), option(Shadow)):Heart2]` |
>>| 3 |  `INPUT[inlineSelect(option(Arcane), option(Arrow), option(Bastion), option(Blade), option(Elemental), option(Might), option(Restoration), option(Ritual), option(Shadow)):Heart3]` |
>>| 4 |  `INPUT[inlineSelect(option(Arcane), option(Arrow), option(Bastion), option(Blade), option(Elemental), option(Might), option(Restoration), option(Ritual), option(Shadow)):Heart4]` |
>>
>> #### Passive Skills
>> |        |         |   
>>| :-: | :------------- |
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
>>

>[!thing] %%FAKE TITLE HERE%%
>>[!gear]  %%FAKE TITLE HERE%%
>>### Heart Abilities
>>
>>| **Ability Name** | Life Bolt  | **Type**  | Holy, Attack, Support |
>>|:------------:|:----------:|:-----:|:---------------------:|
>>|     **Rank**     |   Novice   |  **XP**   |                       |
>>|     **Cost**     |    2 MP    | **Heart** |  Talent, Restoration  |
>>|   **Actions**    | 1 Required | **Range** |         30 m          |  
>>&nbsp;
>> 
>>
>>Target is healed for D6+DM Health. If the target is undead, it deals damage instead.
>>
>>&nbsp;
>>**Apprentice Rank:** Amount increased to 2D6+DM 
>>**Veteran Rank:** Amount increased to 3D6+DM 
>>**Master Rank:** Amount increased to 4D6+DM
>>&nbsp;
>>*You gather divine energy in your hand, shooting off a beam of bright light.*
>>
>>&nbsp
>>
>>---
>>
>>&nbsp
>>
>>| **Ability Name** | Twin Shots | **Type**  | Martial, Attack |
>>| ---------------- | ---------- | --------- | --------------- |
>>| **Rank**         | Novice     | **XP**    |                 |
>>| **Cost**         | 4 ST       | **Heart** | Talent, Arrow   |
>>| **Actions**      | 1 Required | **Range** | Weapon's Range  |
>>
>>&nbsp
>>You can perform two ranged attacks with a single Standard Action against the same target, each one suffering -10 to the attack check.
>>
>>&nbsp
>>**Apprentice Rank:** Attacks suffer no penalty
>>**Veteran Rank:** Attacks deal +2 damage
>>**Master Rank:** Attacks receive +10 to their check
>>
>>&nbsp
>>
>>*You let loose two shots in quick succession, trusting your skill over any careful aiming.*
>>
>>&nbsp
>>
>>---
>>
>>&nbsp
>>
>>| **Ability Name** | Cleanse Body | **Type**  |    Holy, Support    |
>>|:--------------: | :----------: | :-------: | :-----------------: |
>>|     **Rank**     |    Novice    |  **XP**   |                     |
>>|     **Cost**     |     1 MP     | **Heart** | Talent, Restoration |
>>|   **Actions**    |  1 Required  | **Range** |        30 m         |
>>
>>&nbsp
>>Removes 1 instance of Poison, Disease, Blind, Dazed, Freezing, Paralyzed, Slowed, Sleep or Stunned from a single target.
>>
>>&nbsp
>>
>>**Veteran Rank:** Removes all physical conditions from the target
>>
>>&nbsp
>>
>>*With your divine power you pull the poison out from the target, turning it into ash once outside their body.*
>>
>>&nbsp
>>
>>---
>>
>>&nbsp
>>
>>| **Ability Name** |  Backflip  | **Type**  | Martial, Utility |
>>|:----------------:|:----------:|:---------:|:----------------:|
>>|     **Rank**     | Apprentice |  **XP**   |      1,000       |
>>|  **Cost**     |    2 ST    | **Heart** |  Talent, Arrow   |
>>|   **Actions**    |    Free    | **Range** |       Self       |
>>
>>&nbsp
>> You automatically disengage from combat and gain +10 Dodge until your next turn.
>>
>>&nbsp
>>
>> **Apprentice Rank:** Opponent suffers D4 damage 
>> **Veteran Rank:**  Dodge increased to +20
>> **Master Rank:** Your next action receives +20
>>
>>&nbsp
>>
>> *You swiftly move around your opponent, suddenly jumping backwards against them and landing on a perfect defensive guard.*
>>
>>&nbsp
>>
>>---
>>
>>&nbsp
>>
>>| Ability Name |Identify Magic Item | Type | Arcane, Utility |
>>| :----------: | :-------------: | :---: | :-------------: |
>>| Rank | Novice | XP | |
>>| Cost | 2 MP | Heart | Talent, Ritual |
>>| Actions | 1 Required | Range | Touch |
>>
>>&nbsp
>> You learn the powers of an item, allowing you to use it. You close your eyes, concentrating on the item’s aura and learning all its secrets.
>>
>>&nbsp
>>
>>*After a long incantation, you touch the item, which collapses in a rainbow shower of solid aetheryte.*
>>
>>&nbsp
>>
>>---
>>
>>&nbsp
>>
>>| Ability Name | Portal | Type | Arcane, Utility |
>>| :----------: | :-----: | :---: | :-------------: |
>>| Rank | Novice | XP | |
>>| Cost | 10 MP | Heart | Prime, Ritual |
>>| Actions | 2 Required | Range | 5 Travel Days |
>>
>>&nbsp
>>Creates linked teleportation portals that remain open for 1 min. The destination portal can be set to appear on a place the caster is familiar with, or within their line of sight.
>>
>>&nbsp
>>
>>**Apprentice Rank:** Range increased to 10 Travel Days. 
>>**Veteran Rank:** Range increased to 20 Travel Days. 
>>**Master Rank:** Range increased to 40 Travel Days. 
>>
>>&nbsp
>>
>>*After a long incantation, you touch the item, which collapses in a rainbow shower of solid aetheryte.*
>>
>>&nbsp
>>
>>---
>>
>>&nbsp
>>
>>| Ability Name | Bless| Type | Holy, Support |
>>| :----------: | :-------: | :---: | :------------: |
>>| Rank | Novice | XP | |
>>| Cost | 4 MP | Heart | Power, Restore |
>>| Actions | 1 Required | Range | 30 m. |
>>
>>&nbsp
>>Description: Increase a target’s Brawn by +20 and Dodge by +10 for D4+2 rounds.
>>
>>&nbsp
>>
>>**Apprentice Rank:** Actions Required: Free
>>**Veteran Rank:** Duration increased to D6+2 rounds
>>**Master Rank:** Effect lasts until the end of combat
>>
>>&nbsp
>>
>>*A blinding glow appears from within the target’s chest, only to
disappear seconds later.*
>>
>>&nbsp
>>
>>---
>>
>>&nbsp
>>
>>
>>| Ability Name |     | Type  |     |
>>| ------------ | --- | ----- | --- |
>>| Rank         |     | XP    |     |
>>| Cost         |     | Heart |     |
>>| Actions      |     | Range |     |
>>Description:
>>
>>
>>---
>>
>>| Ability Name |     | Type  |     |
>>| ------------ | --- | ----- | --- |
>>| Rank         |     | XP    |     |
>>| Cost         |     | Heart |     |
>>| Actions      |     | Range |     |
>>Description:
>>
>>
>>---
>>| Ability Name |     | Type  |     |
>>| ------------ | --- | ----- | --- |
>>| Rank         |     | XP    |     |
>>| Cost         |     | Heart |     |
>>| Actions      |     | Range |     |
>>Description:
>>
>>
>>---
>>


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





