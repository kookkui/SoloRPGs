---
HeartAbCost: 3
HeartAbHeart: Weapon Strike
HeartDef: Parry
HeartDes: Make an Unarmed Combat skill check. If successful, you deal D4 Bludgeoning damage.
HeartFlav: "*You strike at your target with your fists and feet.*"
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