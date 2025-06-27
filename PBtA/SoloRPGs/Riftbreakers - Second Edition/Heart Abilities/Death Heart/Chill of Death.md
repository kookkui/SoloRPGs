---
HeartAbCost: 5
HeartAbHeart: Death
HeartDef: Endurance
HeartDes: Target suffers D6 Necrotic damage and is Freezing.
HeartFlav: "*The chill of the tomb awaits those who oppose you.*"
HeartAbRange: 0-2
prime: true
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
>>
>>`=this.HeartFlav`
>>