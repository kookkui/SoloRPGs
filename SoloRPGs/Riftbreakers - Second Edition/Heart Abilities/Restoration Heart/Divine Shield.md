---
HeartAbCost: 5
HeartAbHeart: Restoration
HeartDef: Agility
HeartDes: Grants a target +3 Protection until your next turn.
HeartFlav: "*You envelop your target in a shining halo of holy energy that deflects incoming attacks.*"
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