---
HeartAbCost: 4
HeartAbHeart: Might
HeartDef: "Agility"
HeartDes: You perform a free Weapon Strike with a melee weapon that deals its damage to 2 targets within range.
HeartFlav: "*You swing your weapon in a wide arc, striking your foes.*"
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