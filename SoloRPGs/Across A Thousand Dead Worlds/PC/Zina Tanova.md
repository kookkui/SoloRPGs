---
Art: "![[MinerYellow166.png|600]]"
level: 1
STR: 10
INT: 11
WIL: 11
DEX: 10
CONST: 10
CHA: 8
xp: 0
axp: 0
background: "**Algae Farmer** You spent most of your life working one of the giant algae farms that feeds most of the world, probably after inheriting the job from your parents. ***+1 Resolve***"
talent1: "**Charge**"
talent1desc: You can barge into melee, gaining +5 Skill and +5 damage during your first turn. Cannot be used in conjunction with any form of stealth.
Lhand: “Requiem” B99 Carbine
Lhanddmg: "+5"
Lhandrange: "8"
Lhandtraits: Two-handed // Burst // Powerful
Rhand: '" "'
Rhanddmg: '" "'
Rhandrange: '" "'
Rhandtraits: '" "'
headslot: 
torsoslot: KSA Personal Body Armor (2)
backslot: KSA Personal Body Armor (2)
waistslot: KSA Personal Body Armor (2)
legsslot: 
feetslot: 
bodysuitslot: 
bpackitem1: LKPK x1
---
>[!dice] %%FAKE TITLE HERE%%
>> [!dice] %%FAKE TITLE HERE%%
>> # `=this.file.name`
>> `=this.Art`
>> 
>>|     |     |
>> |--- | --- |
>>|   **Level**   |  `=this.level`   |
>> |**Stamina** | **Current:** `10` **Max:** **10**   |
>> |**Trauma** |  **Current:** `0` **Max:** **10**   |
>> |**Rads** | `0` |
>> |**Luck**| `3` **Max:** **5**  |
>>|**Wounds** | **Current:** `0` **Max:** `3` |
>>|**Drake Coins (DC)** | `800` |
>> |**XP** | `VIEW[{xp}][text]`|
>>|**ADD XP**| `INPUT[number:axp]` `BUTTON[exp]`|
>>|**Time Units** |`boxes: 0/6` |
>>&nbsp;
>

>[!thing] %%FAKE TITLE HERE%%
>>[!thing] %%FAKE TITLE HERE%%
>> ### Stats
>>|        |         |   
>>| ---- | ---- |
>>| **Strength**   | `=this.STR`  |
>>| **Dexterity**    | `=this.DEX` | 
>>| **Constitution** | `=this.CONST` |
>>| **Will**         |  `=this.WIL` | 
>>| **Intelligence** |  `=this.INT` | 
>>| **Charisma**     | `=this.CHA` | 
>>
>>&nbsp;
>>
>> ### Skills
>>| **Skill Name** | **Skill Level** | **Skill Name** | **Skill Level** |
>>| :-----: | :-: |:------: | :-: |
>>|**Àrsaidh Tech**|`-5`| **Close Combat** | `8` |
>>| **Perception** | `6` | **Manipulation** | `3`|
>>|**Pilot** | `4` | **Medical Aid** | `6` |
>>| **Ranged Combat**  | `8` | **Resolve**  | `8` |
>>| **Science** | `8` |**Stealth** | `6` |
>>|**Survival** |`6` |**Technology** | `8`|
>>
>>---
>
>>[!travel] %%FAKE TITLE HERE%%
>>##### Talents
>> |**Name**| **Description**|
>>|:-:| :----: |
>>| `=this.talent1` | `=this.talent1desc` |
>>| `=this.talent2` | `=this.talent2desc` |
>>| `=this.talent3` | `=this.talent3desc` |
>>| `=this.talent4` | `=this.talent4desc` |
>>| `=this.talent5` | `=this.talent5desc` |
>>---
>>
>>&nbsp;
>>
>>| | |
>>|---| -- |
>>| **Background** |  `=this.background`   |


>[!gather] %%FAKE TITLE HERE%%
>>[!gather] %%FAKE TITLE HERE%%
>>
>> #### Left Hand
>>| **Weapon** | **Damage** | **Range** | **Traits** |
>>| ---------------------- | --------------- | ------------- | ------------- |
>>| `=this.Lhand` | `=this.Lhanddmg` | `=this.Lhandrange` | `=this.Lhandtraits` |
>> #### Right Hand
>>| **Weapon** | **Damage** | **Range** | **Traits** |
>>| ---------------------- | --------------- | ------------- | ------------- |
>>| `=this.Rhand` | `=this.Rhanddmg` | `=this.Rhandrange` | `=this.Rhandtraits` |
>>
>>&nbsp;
>>
>> #### Gear
>> |        |         |   
>>| :-: | :-----: |
>>| **Head** | `=this.headslot` |
>>| **Torso** | `=this.torsoslot` |
>>| **Back** | `=this.backslot` |
>>| **Waist** | `=this.waistslot` |
>>| **Legs**| `=this.legsslot` |
>>| **Feet**|`=this.feetslot` |
>>| **Full Body Suit**|`=this.bodysuitslot` |
>>
>>&nbsp;
>>

>[!dice] %%FAKE TITLE HERE%%
>>[!dice] %%FAKE TITLE HERE%%
>> ### Backpack
>>| Slot | Item |  Slot | Item |
>>| :-: | :---------------- |--------|--------|
>>|1|`INPUT[text:bpackitem1]` |11|`INPUT[text:bpackitem11]`|
>>|2|`INPUT[text:bpackitem2]`|12|`INPUT[text:bpackitem12]`|
>>|3|`INPUT[text:bpackitem3]`|13|`INPUT[text:bpackitem13]`|
>>|4|`INPUT[text:bpackitem4]`|14|`INPUT[text:bpackitem14]`|
>>|5|`INPUT[text:bpackitem5]`|15|`INPUT[text:bpackitem15]`|
>>
>>&nbsp;
>>
>> ### Pockets
>>| Slot | Item |  Slot | Item |
>>| :-: | :---------------- |--------|--------|
>>|1|`INPUT[text:pocketitem1]` |11|`INPUT[text:pocketitem11]`|
>>|2|`INPUT[text:pocketitem2]`|12|`INPUT[text:pocketitem12]`|
>>|3|`INPUT[text:pocketitem3]`|13|`INPUT[text:pocketitem13]`|
>>|4|`INPUT[text:pocketitem4]`|14|`INPUT[text:pocketitem14]`|
>>|5|`INPUT[text:pocketitem5]`|15|`INPUT[text:pocketitem15]`|



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
