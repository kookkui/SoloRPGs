---
HeartAbCost: 4
HeartAbHeart: Restoration
HeartDef: 
HeartDes: Increase a target’s Endurance by +20 and Agility by +10 for D4+2 rounds.
HeartFlav: "*A blinding glow appears from within the target’s chest, only to disappear seconds later.*"
HeartAbRange: 0-2
prime: false
---

>[!table_time]  %%FAKE TITLE HERE%%
>>[!table_time]  %%FAKE TITLE HERE%%
>>### `=this.file.name`
>>|  | |  |  |
>>|:--------:|:-------:|:-----:|:--------------:|
>>| **Ability Name** | `=this.file.name` | **Defense** | `=this.HeartDef` |
>>| **Cost** | `=this.HeartAbCost` | **Heart** | `=this.HeartAbHeart` |
>>| **Prime** | `INPUT[toggle:prime]` | **Range** | `=this.HeartAbRange` |
>>&nbsp;
>> 
>> ##### Description
>>`=this.HeartDes`
>>
>>&nbsp;
>>`=this.HeartFlav`
>>