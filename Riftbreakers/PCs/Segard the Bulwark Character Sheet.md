---
Role: Bulwark
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
`2/5`

| Strength         | 14  | Brawn            | 70  | **Max Health** |  32   |
| ---------------- |:---:| ---------------- |:---:|:--------------:|:-----:|
| **Dexterity**    | 10  | **Coordination** | 50  |   **Armor**    |  D8   |
| **Constitution** | 16  | **Vitality**     | 80  |   **Dodge**    |  70   |
| **Will**         | 11  | **Tenacity**     | 55  |   **Range**    | Melee |
| **Intelligence** | 10  | **Intellect**    | 50  |   **Parry**    |  +10  |
| **Charisma**     | 12  | **Charm**        | 60  |                |       |

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
