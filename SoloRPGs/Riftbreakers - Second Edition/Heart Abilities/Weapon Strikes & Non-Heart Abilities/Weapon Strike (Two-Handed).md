---
HeartAbCost: 3
HeartAbHeart: Weapon Strike
HeartDef: Evasion
HeartDes: Make a weapon skill check with your weapon. If successful, you deal D6+2 damage.
HeartFlav: "*You wield your weapon with purpose, striking at your target.*"
HeartAbRange: "0"
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