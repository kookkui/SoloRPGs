---
HeartAbCost: 8
HeartAbHeart: Companion
HeartDef: 
HeartDes: Your Companion enters the fray.
HeartFlav: "*You call forth your Companion, who promptly obeys you, ready for combat.*"
HeartAbRange: 0
prime: false
---

>[!crafting]  %%FAKE TITLE HERE%%
>>[!crafting]  %%FAKE TITLE HERE%%
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