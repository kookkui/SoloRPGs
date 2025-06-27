---
HeartAbCost: 5
HeartAbHeart: Might
HeartDef: Endurance
HeartDes: All targets within the area of effect become Stunned for D4 rounds.
HeartFlav: "*You let out a blood-curdling roar, confusing and freezing in place all your enemies.*"
HeartAbRange: "0"
prime: true
---

>[!rng]  %%FAKE TITLE HERE%%
>>[!rng]  %%FAKE TITLE HERE%%
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