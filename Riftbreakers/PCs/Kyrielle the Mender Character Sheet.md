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
type: |-
  Loyalty 6 Readiness 45

  Opener: Increase your next attack's damage by D4
CompanionHP: 32
Clevel: 3
hp: 32
modifier: 0
---
---
### Type: `INPUT[suggester(option(Bulwark), option(Controller), option(Executioner), option(Mender)):Role]`

```meta-bind
INPUT[progressBar(class(green-progress-bar), maxValue(32), title(HP)):CompanionHP]
```
### Standard Attack: D8+2
### Companion Level: 1
#### Quest Completed
`0/5`

|    |   |         |   |  |     |
| ---------------- |:---:| ---------------- |:---:|:--------------:|:-----:|
| **Strength**     | `=this.STR`  | **Brawn**        | `=this.STR*5`  | **Max Health** |  32   |
| **Dexterity**    | `=this.DEX`  | **Coordination** | `=this.DEX*5`  |   **Armor**    |  D8   |
| **Constitution** | `=this.CON`  | **Vitality**     | `=this.CON*5`  |   **Dodge**    |  70   |
| **Will**         | `=this.WIL`  | **Tenacity**     | `=this.WIL*5`   |   **Range**    | Melee |
| **Intelligence** | `=this.INT`  | **Intellect**    | `=this.INT*5`  |   **Parry**    |  +10  |
| **Charisma**     | `=this.CHA`  | **Charm**        | `=this.CHA*5` |                |       |

---
### Follower Name: Thalyss
#### Follower Type:

^1252e7

`INPUT[textArea:type]`

---
## Chest
`INPUT[textArea:Chest]`
## Legs
`INPUT[textArea:Belt]`
## Amulet 
`INPUT[textArea:Pant]`
## Ring 1
`INPUT[textArea:Ring1]`
## Ring 2
`INPUT[textArea:Ring2]`
## Combat Strategy
`INPUT[textArea:Pendant]`
## Notes
`INPUT[textArea:Notes]`
