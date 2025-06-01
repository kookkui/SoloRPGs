---
HeartAbCost: 6
HeartAbHeart: Restoration
HeartDef: 
HeartDes: You summon a weapon of your choice for you to wield that deals D8 Radiant damage. Any instance of Weapon Strike in your Loadout uses this weapon. The weapon lasts until the end of combat.
HeartFlav: "*A burst of holy energy solidifies in your hand, creating a terrifying weapon of divine nature.*"
HeartAbRange: Self
prime: true
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

