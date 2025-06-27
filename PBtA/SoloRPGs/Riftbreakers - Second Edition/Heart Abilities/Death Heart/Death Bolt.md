---
HeartAbCost: 4
HeartAbHeart: Death
HeartDef: Endurance
HeartAbRange: 0-3
HeartDes: Target suffers D6 Necrotic damage.
HeartFlav: "*You concentrate the power of death into a bolt, launching it at your target.*"
---

>[!dice]  %%FAKE TITLE HERE%%
>>[!dice]  %%FAKE TITLE HERE%%
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