---
Art:
CompanionHP: 24
dammod:
CompanionLOAbility:
---

>[!thing] %%FAKE TITLE HERE%%
>>[!thing] %%FAKE TITLE HERE%%
>> # `=this.file.name`
>> `=this.Art`
>>```meta-bind
>>INPUT[progressBar(class(green-progress-bar), maxValue(24), title(HP)):CompanionHP]
>>```
>>
>>&nbsp;
>>
>>||  |
>>| :-: | :-: |
>>|**Role**|<font color="#7FFF00">The Mender</font>|
>>|**Damage Modifier**|`=this.dammod`|
|**Passive Trait**|`INPUT[inlineSelect(option(You have Advantage on Manipulation checks, Negotiator),option(You have Advantage on Lockpicking checks, Master Locksmith), option(You have Advantage on Stealth checks, Assassin),option(You have Advantage on Athletics checks, Strongman),option(Takes hits for the PC, Scout),option(Increase your Aether by 1, Aether Battery),option(You have Advantage on Gathering checks, Scavenger),option(You have Advantage on Insight checks, Mind Reader),option(You have Advantage on Literacy checks, Scholar),option(You have Advantage on Medicine checks, Healer)):rating]`|
>>| **Companion Level** | `0`   |
>>|**Quest Completed**|`b:0/5`|

>[!table] %%FAKE TITLE HERE%%
>>[!table] %%FAKE TITLE HERE%%
>>### Core Stats
>>| **Stats Name** | **Stats Level** | **Stats Name** | **Stats Level** |
>>| :-----: | :-: |:------: | :-: |
>>|**Agility** |`0`| **Move**  | `0` |
>>| **Athletics** | `0` | **Parry** | `0`|
>>|**Combat Skill** | `0` | **Perception**  | `0` |
>>| **Endurance**  | `5` | **Protection**  | `0` |
>>| **Evasion**  | `5` |**Tenacity**  | `5` |
>>|**Health** |`0` |

---
>[!rng] %%FAKE TITLE HERE%%
>>[!rng] %%FAKE TITLE HERE%%
>>### Combat Strategy
>>Ranged based **(range 2)**. Will always attempt to maximize the utility of their spells, keeping their distance and attacking from range when necessary but trying to support their patron first, and other allies second.
>>

---

>[!table_time] %%FAKE TITLE HERE%%
>>[!table_time] %%FAKE TITLE HERE%%
>>### Companion Loadout Ability
>> 
>>`=this.CompanionLOAbility`
>>
>>
>>&nbsp;
>> 
>>
>>---



