---
Role: The Controller
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
>>|**Role**|<font color="#3A86FF">The Protector</font>|
>>|**Damage Modifier**|`=this.dammod`|
|**Passive Trait**|`INPUT[inlineSelect(option(You have Advantage on Manipulation checks, Negotiator),option(You have Advantage on Lockpicking checks, Master Locksmith), option(You have Advantage on Stealth checks, Assassin),option(You have Advantage on Athletics checks, Strongman),option(Takes hits for the PC, Scout),option(Increase your Aether by 1, Aether Battery),option(You have Advantage on Gathering checks, Scavenger),option(You have Advantage on Insight checks, Mind Reader),option(You have Advantage on Literacy checks, Scholar),option(You have Advantage on Medicine checks, Healer)):rating]`|
>>| **Companion Level** | `0`   |
>>|**Quest Completed**|`b:0/5`|

>[!table] %%FAKE TITLE HERE%%
>>[!table] %%FAKE TITLE HERE%%
>>### Core Stats
>>| **Stats Name** | **Stats Level** | **Stats Name** | **Stats Level** |
>>| :-----: | :-: |:------: | :-: |
>>|**Agility** |`-10`| **Move**  | `0` |
>>| **Athletics** | `5` | **Parry** | `10`|
>>|**Combat Skill** | `5` | **Perception**  | `-10` |
>>| **Endurance**  | `10` | **Protection**  | `1` |
>>| **Evasion**  | `10` |**Tenacity**  | `-10` |
>>|**Health** |`5` |

---
>[!rng] %%FAKE TITLE HERE%%
>>[!rng] %%FAKE TITLE HERE%%
>>### Combat Strategy
>>Melee based **(range 0)**, so it will attempt to engage the chosen target (determined by their patron). Will always prioritize enemies that are targeting their patron. In case of doubt, determine randomly.
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





