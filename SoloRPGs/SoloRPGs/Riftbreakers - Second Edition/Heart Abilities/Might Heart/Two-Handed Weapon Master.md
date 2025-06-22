---
HeartAbCost: 5
HeartAbHeart: Might
HeartDef: 
HeartDes: For the remainder of combat, if you are wielding a two-handed weapon you deal an additional D4 damage.
HeartFlav: "*You shift your stance slightly, focusing on a two-handed, specialized combat style.*"
HeartAbRange: Self
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