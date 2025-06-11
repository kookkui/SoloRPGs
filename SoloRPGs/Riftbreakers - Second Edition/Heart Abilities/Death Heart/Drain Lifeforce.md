---
HeartAbCost: 5
HeartAbHeart: Death
HeartDef: Tenacity
HeartAbRange: 0-2
HeartDes: You deal D6 Necrotic damage to your target, and heal for half the damage done.
HeartFlav: "*A bolt of putrid green light erupts from your hands, striking your opponent and draining their lifeforce.*"
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


