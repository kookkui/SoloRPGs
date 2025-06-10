---
Art: "![[MachineGods_Pure_Booty.webp]]"
STR: 8
INT: 8
WIL: 8
DEX: 8
CONST: 8
CHA: 8
xp: 0
xp: 0
axp: 
---
>[!dice] %%FAKE TITLE HERE%%
>> [!dice] %%FAKE TITLE HERE%%
>> # `=this.file.name`
>> `=this.Art`
>> 
>>|     |     |
>> |--- | --- |
>>|   **Level**   |  `=this.level`   |
>> |**Stamina** | **Current:** `0` **Max:** **10**   |
>> |**Trauma** |  **Current:** `0` **Max:** **10**   |
>> |**Rads** | `0` |
>> |**Luck**| `1` **Max:** **5**  |
>>|**Wounds** | **Current:** `0` **Max:** `0` |
>>|**Drake Coins** | `0` |
>> |**XP** | `VIEW[{xp}][text]`|
>>|**ADD XP**| `INPUT[number:axp]` `BUTTON[exp]`|
>>
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
>>|**Àrsaidh Tech**|`1`| **Close Combat** | `2` |
>>| **Perception** | `2` | **Manipulation** | `3`|
>>|**Pilot** | `2` | **Medical Aid** | `-1` |
>>| **Ranged Combat**  | `2` | **Resolve**  | `2` |
>>| **Science** | `0` |**Stealth** | `2` |
>>|**Survival** |`2` |**Technology** | `2`|
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
>


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
>>|1|`INPUT[text:bpackitem1]` |11|`INPUT[text:pocketitem11]`|
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
