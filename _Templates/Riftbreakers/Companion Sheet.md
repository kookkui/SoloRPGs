---
Role: Mender
STR: 8
DEX: 13
CON: 12
INT: 15
WIL: 17
CHA: 12
Belt: ""
Pendant: Will always prioritize enemies that are targeting their patron. In case of doubt, determine randomly.
Notes: ""
CompanionHP: 24
hp: 32
comArmor: D4
comRange: Ranged (20 m.)
sattack: D6+2
comDodge: 50
comParry:
Fname: Opheron
Floyalty: 6
Freadiness: 31
Ftrait: "**Time Adept** The next Ability you use is a Free Action"
---
---
### Type: `INPUT[suggester(option(Bulwark), option(Controller), option(Executioner), option(Mender)):Role]`

```meta-bind
INPUT[progressBar(class(green-progress-bar), maxValue(24), title(HP)):CompanionHP]
```

>[!dice] %%FAKE TITLE HERE%%
>>[!dice] %%FAKE TITLE HERE%%
>>||  |
>>| :-: | :-: |
>>|**Standard Attack**|`=this.sattack`|
>>| **Companion Level** | `0`   |
>>|**Quest Completed**|`b:0/5`|





>[!table] %%FAKE TITLE HERE%%
>>[!table] %%FAKE TITLE HERE%%
>>### Companion Stats
>>|    |   |         |   |  |     |
>>| ---------------- |:---:| ---------------- |:---:|:--------------:|:-----:|
>>| **Strength**     | `=this.STR`  | **Brawn**        | `=this.STR*5`  | **Max Health** |   `=this.hp`   |
>>| **Dexterity**    | `=this.DEX`  | **Coordination** | `=this.DEX*5`  |   **Armor**    |  `=this.comArmor`   |
>>| **Constitution** | `=this.CON`  | **Vitality**     | `=this.CON*5`  |   **Dodge**    |  `=this.comDodge`   |
>>| **Will**         | `=this.WIL`  | **Tenacity**     | `=this.WIL*5`   |   **Range**    | `=this.comRange` |
>>| **Intelligence** | `=this.INT`  | **Intellect**    | `=this.INT*5`  |   **Parry**    |  `=this.comParry`  |
>>| **Charisma**     | `=this.CHA`  | **Charm**        | `=this.CHA*5` |                |       |

---

>[!dice] %%FAKE TITLE HERE%%
>>[!dice] %%FAKE TITLE HERE%%
>>### Follower Name: `=this.Fname`
>>---
>>
>>#### Follower Stats
>>| |    |
>>| :-: | :-: |
>>|Loyalty|`=this.Floyalty`|
>>| Readiness | `=this.Freadiness` |
>>| Follower Trait | `=this.Ftrait` |
>>| | |

---

>[!table] %%FAKE TITLE HERE%%
>>[!table] %%FAKE TITLE HERE%%
>>### Chest
>>`INPUT[textArea:Chest]`
>>### Legs
>>`INPUT[textArea:Belt]`
>>### Amulet 
>>`INPUT[textArea:Pant]`
>>### Ring 1
>>`INPUT[textArea:Ring1]`
>>### Ring 2
>>`INPUT[textArea:Ring2]`
>>### Notes
>>`INPUT[textArea:Notes]`
