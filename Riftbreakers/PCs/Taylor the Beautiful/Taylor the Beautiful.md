---
Title: Protector of Kar Helos
STR: 10
DEX: 16
CON: 18
INT: 12
WIL: 11
CHA: 14
PER: 65
Armor: D4+3
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
rank: Apprentice
axp: 25
xp: 1675
a-N: "355"
a-a: 
a-V: 
a-M: 
quest1: "**Rift Closure:** Travel 14 days and close the marked rift. (Sky Islets)."
quest1t: false
quest2: "**Escort:** a caravan distance is 22 travel days."
quest2t: 
quest3: "**Patrol:** Patrol the perimeter and wilds for 17 days. Mark any rifts found with a beacon. Roll a d10 each day, on a 1 or 2, there is a rift."
quest3t: 
quest4: "**Collect:** deliver 22 Chitinous Plate."
quest4t: 
quest5: "**Rift Closure:** Travel 14 days and close the marked rift. (Timeworn Ruins)."
quest5t: 
quest6: "**Patrol:**the perimeter and wilds for 11 days. Mark any rifts found with a beacon. Roll a d10 each day, on a 1 or 2, there is a rift."
quest6t: 
quest7: "**Collect:** deliver 13 Fiery Ember."
quest7t: 
quest8: "**Escort:** a caravan distance is 21 travel days."
quest9: "**Monster Hunt:** Travel 7 days and search for the monster. The type of monster is determined by the region."
quest10: 
headname: 
headmagic: 
headquirk: 
headnotes: 
chestname: Soft Leather Armor
chestmagic: 
chestquirk: 
chestnotes: 
beltname: 
beltmagic: 
beltquirk: 
beltnotes: 
pantsname: 
pantsmagic: 
pantsquirk: 
pantsnotes: 
glovesname: 
glovesmagic: 
glovesquirk: 
glovesrank: 
glovesnotes: 
bootname: Victorious Gloves of the Whisper
bootmagic: Constitution +1 Charisma +1
bootquirk: Smells like rotten flesh
bootrank: Novice
bootnotes: 200A, Air Earth
ring1name: Champion's Ring of the Snake
ring1magic: Dexterity +1, Reduce your Stamina pool by 5 (26), but increase your Aether pool by 8 (23). You no longer need to eat or drink.
ring1quirk: It's always pristine
ring1rank: Novice
ring1notes: 300A Air Life 2x Boon Bane
ring2name: Mage's Wonderful Ring
ring2magic: Stamina +8, On command, this item works as a source of light. Illuminates in a 20 m. radius.
ring2quirk: It's always covered in a layer of mucus
ring2rank: Novice
ring2notes: 300A Fire 2xPower Light
pendantgearname: Knight's Glass Stone
pendantgearmagic: You can detect all living beings in a 20 m. radius. Increase your luck by +5
pendantgearquirk: It appears to be completely made of glass. It doesn't make it more fragile than it should be though
pendantgearrank: Novice
pendantgearnotes: Chaos Life Boon Light 200A  Rarity:Uncommon
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
proficiency1: Longbow
proficiency2: Scimitar
proficiency3: Soft Leather
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
title14: "Potion of Rest. Reduce your Fatigue by 1. Aspects: Stone, Life"
---
>[!note] %%FAKE TITLE HERE%%
>>[!gear] %%FAKE TITLE HERE%% 
>> # `=this.file.name`
>> ![[IMG-20250129190024669.webp]]
>> ###### Stats
>>  |
>> ---|---|
>> **Rank** |`INPUT[suggester(option(Novice), option(Apprentice), option(Veteran), option(Master)):rank]` |
>>  **Title** |`=this.Title` |
>> **Reputation** | `3` |
>>  **HP** | **Current:**`36` **Max:** `=this.CON*3`
>> **Aether** | `27` /`VIEW[{WIL} + {INT} + 8]` |
>> **Stamina** | `36` /`VIEW[{STR} + {CON}+ 8]` |
>> **Armor Rating** | `=this.Armor` |
>> **XP** | `VIEW[{xp}][text]`
>>
>>---
>> **ADD XP:** `INPUT[number:axp]` `BUTTON[exp]`
>>
>>
>> &nbsp;
>>
>> ###### Weapons
>>| **Weapons** | **Type** | **Damage** | **Notes** |
>>| ------ | :-: | :-: | --------- |
>>| `=this.Weapon1` | `=this.Weapon1type` | `=this.Weapon1dmg` |`=this.Weapon1notes` |
>>| `=this.Weapon2` | `=this.Weapon2type` |`=this.Weapon2dmg` | `=this.Weapon2notes` |
>>| `=this.Weapon3` | `=this.Weapon3type`|`=this.Weapon3dmg` | `=this.Weapon3notes` |
>>| | | |
>>| | | |
>> &nbsp;
>>
>> ###### Crafting Aspects
>>| **Air**   | **Bane** | **Boon** | **Chaos** | **Dark**  | **Death** |
>>| :-: | :-: | :-: | :-: | :-: | :-: |
>>| `0`   | `0`  | `1`  | `10`   | `21`   | `1`   |
>>| **Earth** | **Fire** | **Life** | **Light** | **Power** | **Water** |
>| `1`   | `11`  | `0`  | `10`   | `11`   | `10`   |
>> &nbsp;
>>
>>###### Minerals
>>
>>| **Coal** | **Iron** | **Silver** | **Aglite** |
>>| :-: | :-: | :-: | :-: |
>>| `21`  | `3`  | `1`    | `4`    |
>> &nbsp;
>>
>>  ###### Currency
>>| **⟑-N** | **⟑-A**   |
>>| :-: | :-: |
>>|`=this.a-N`|`=this.a-a`|
>>| **⟑-V** | **⟑-M**   |
>>|`=this.a-V`|`=this.a-M`|

---

>[!dice] %%FAKE TITLE HERE%%
>>[!dice] %%FAKE TITLE HERE%%
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
>>[!dice] %%FAKE TITLE HERE%%
>> ### Skill Checks
>>| **Skill Name** | **Skill Level** | **Skill Name** | **Skill Level** |
>>| :-: | :-: |:-: | :-: |
>>| **Alchemy** (INT) | `34` | **Leatherworking** (DEX) | `38`|
>>| **Acrobatics** (DEX) | `15` |**Literacy** (INT) | `57` |
>>| **Animal Handling** (CHA) | `14` |**Insight** (WIL) | `15` |
>>| **Athletics** (STR) | `33` | **Dodge** (DEX) | `75` |
>>| **Blacksmithing** (DEX) | `35` |**Perception** (WIL) | `32`|
>>| **Command** (CHA) | `14` | **Performance** (CHA)|`14`|
>>| **Gathering** (DEX) | `57` |**Sailing** (DEX) | `15` |
>>| **Nature** (INT) | `31` |  **Sailing** (DEX) | `15` |
>>| **Manipulation** (CHA) | `14` | **Stealth** (DEX) | `38` |
>>| **Medicine** (INT) | `11` |**Survival** (INT) | `54` |
>
>>[!dice] %%FAKE TITLE HERE%%
>>##### Proficiencies
>> | | |
>>|:-:| :---: |
>>| `=this.proficiency1` | `=this.proficiency2` |
>>| `=this.proficiency3` | `=this.proficiency4` |
>>| `=this.proficiency5` | `=this.proficiency6` |
>>| `=this.proficiency7` | `=this.proficiency8` |


---

>[!travel] %%FAKE TITLE HERE%%
>>[!travel] %%FAKE TITLE HERE%%
>>### Quests
>>|**Quest Description** |**Completed** | **Timer/Counter**|
>> |:---: | --- | :---------: |
>>| `=this.quest1` | `INPUT[toggle:quest1t]` | `8/14`
>> |`=this.quest2` |`INPUT[toggle:quest2t]` | `0/22`
>>| `=this.quest3` | `INPUT[toggle:quest3t]` | `0/17`
>> |`=this.quest4` |`INPUT[toggle:quest4t]` | `0/22`
>>| `=this.quest5` | `INPUT[toggle:quest5t]` | `0/14`
>> |`=this.quest6` |`INPUT[toggle:quest6t]` | `0/11`
>>| `=this.quest7` | `INPUT[toggle:ques71t]` | `0/13`
>> |`=this.quest8` |`INPUT[toggle:quest8t]` | `0/21`
>>| `=this.quest9` | `INPUT[toggle:ques91t]` | `0/7`
>> |`=this.quest10` |`INPUT[toggle:quest10t]` |

---

>[!table] %%FAKE TITLE HERE%%
>>[!table] %%FAKE TITLE HERE%%
>>### Inventory
>>| <span style="color:rgb(129, 216, 208)">Slot</span> | <span style="color:rgb(129, 216, 208)">Encumbering Items</span> | <span style="color:rgb(129, 216, 208)">Slot</span> | <span style="color:rgb(129, 216, 208)">Encumbering Items</span> 
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

---

>[!travel] %%FAKE TITLE HERE%%
>>[!travel] %%FAKE TITLE HERE%%
>>## Gear
>> &nbsp;
>>
>>### Head
>>| | |
>>|--- | --- |
>>|**Name** | `=this.headname`|
>>|**Magic** | `=this.headmagic`|
>>|**Quirk** | `=this.headquirk`|
>>| **Rank** | `=this.headrank` |
>>| **Notes** | `=this.headnotes` |
>>
>>&nbsp;
>>### Chest
>>| | |
>>|:-:|:-:|
>>|**Name** | `=this.chestname`|
>>|**Magic** | `=this.chestmagic`|
>>|**Quirk** | `=this.chestquirk`|
>>| **Rank** | `=this.chestrank` |
>>| **Notes** | `=this.chestnotes` |
>> &nbsp;
>>
>>### Belt
>>| | |
>>|:-:|:-:|
>>|**Name** | `=this.beltname`|
>>|**Magic** | `=this.beltmagic`|
>>|**Quirk** | `=this.beltquirk`|
>>| **Rank** | `=this.beltrank` |
>>| **Notes** | `=this.beltnotes` |
>> &nbsp;
>>
>>### Pants
>>| | |
>>|:-:|:-:|
>>|**Name** | `=this.pantsname`|
>>|**Magic** | `=this.pantsmagic`|
>>|**Quirk** | `=this.pantsquirk`|
>>| **Rank** | `=this.pantsrank` |
>>| **Notes** | `=this.pantsnotes` |
>> &nbsp;
>>
>>### Gloves
>>| | |
>>|:-:|:-:|
>>|**Name** | `=this.glovesname`|
>>|**Magic** | `=this.glovesmagic`|
>>|**Quirk** | `=this.glovesquirk`|
>>|**Rank** | `=this.glovesrank` |
>>|**Notes** | `=this.glovesnotes` |
>> &nbsp;
>>
>>### Boots
>>| | |
>>|:-:|:-:|
>>|**Name** | `=this.bootname`|
>>|**Magic** | `=this.bootmagic`|
>>|**Quirk** | `=this.bootquirk`|
>>| **Rank** | `=this.bootrank` |
>>| **Notes** | `=this.bootnotes` |
>> &nbsp;
>>
>>### Ring 1
>>| | |
>>|:-:|:-:|
>>|**Name** | `=this.ring1name`|
>>|**Magic** | `=this.ring1magic`|
>>|**Quirk** | `=this.ring1quirk`|
>>| **Rank** | `=this.ring1rank` |
>>| **Notes** | `=this.ring1notes` |
>> &nbsp;
>>
>>### Ring 2
>>| | |
>>|:-:|:-:|
>>|**Name** | `=this.ring2name`|
>>|**Magic** | `=this.ring2magic`|
>>|**Quirk** | `=this.ring2quirk`|
>>| **Rank** | `=this.ring2rank` |
>>| **Notes** | `=this.ring2notes` |
>> &nbsp;
>>
>>### Pendant
>>| | |
>>|:-:|:-:|
>>|**Name** | `=this.pendantgearname`|
>>|**Magic** | `=this.pendantgearmagic`|
>>|**Quirk** | `=this.pendantgearquirk`|
>>| **Rank** | `=this.pendantgearrank` |
>>| **Notes** | `=this.pendantgearnotes` |

---

>[!gather] %%FAKE TITLE HERE%%
>>[!gather] %%FAKE TITLE HERE%%
>>## Hearts
>> |        |     |   
>>| :-: | :----- |
>>| 1 | `INPUT[inlineSelect(option(Arcane), option(Arrow), option(Bastion), option(Blade), option(Elemental), option(Might), option(Restoration), option(Ritual), option(Shadow)):Heart1]` |
>>| 2 |  `INPUT[inlineSelect(option(Arcane), option(Arrow), option(Bastion), option(Blade), option(Elemental), option(Might), option(Restoration), option(Ritual), option(Shadow)):Heart2]` |
>>| 3 |  `INPUT[inlineSelect(option(Arcane), option(Arrow), option(Bastion), option(Blade), option(Elemental), option(Might), option(Restoration), option(Ritual), option(Shadow)):Heart3]` |
>>| 4 |  `INPUT[inlineSelect(option(Arcane), option(Arrow), option(Bastion), option(Blade), option(Elemental), option(Might), option(Restoration), option(Ritual), option(Shadow)):Heart4]` |
>>
>>&nbsp;
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

---

>[!warning] %%FAKE TITLE HERE%%
>>[!npc]  %%FAKE TITLE HERE%%
>>### Heart Abilities
>>
>>| **Ability Name** | Life Bolt | **Type** | Holy, Attack, Support |
>>|:-:|:----------:|:-----:|:---------------------:|
>>| **Rank** | Novice | **XP** | |
>>| **Cost** | 2 MP | **Heart** | Talent, Restoration |
>>| **Actions** | 1 Required | **Range** | 30 m        |  
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
>>| **Ability Name** | Twin Shots | **Type** | Martial, Attack |
>>| :-: | :-: | :-: | :-: |
>>| **Rank** | Novice | **XP** | |
>>| **Cost** | 4 ST | **Heart** | Talent, Arrow |
>>| **Actions** | 1 Required | **Range** | Weapon's Range |
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
>>| **Ability Name** |Identify Magic Item | **Type** | Arcane, Utility |
>>| :----------: | :-------------: | :---: | :-------------: |
>>| **Rank** | Novice | **XP** | |
>>| **Cost** | 2 MP | **Heart** | Talent, Ritual |
>>| **Actions** | 1 Required | **Range** | Touch |
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
>>| **Ability Name** | Portal | **Type** | Arcane, Utility |
>>| :----------: | :-----: | :---: | :-------------: |
>>| **Rank** | Novice | **XP** | |
>>| **Cost** | 10 MP | **Heart** | Prime, Ritual |
>>| **Actions** | 2 Required | **Range** | 5 Travel Days |
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
>>| **Ability Name** | Bless| **Type** | Holy, Support |
>>| :----------: | :-------: | :---: | :------------: |
>>| **Rank** | Novice | **XP** | |
>>| **Cost** | 4 MP | **Heart** | Power, Restore |
>>| **Actions** | 1 Required | **Range** | 30 m. |
>>
>>&nbsp
>>Increase a target’s Brawn by +20 and Dodge by +10 for D4+2 rounds.
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





