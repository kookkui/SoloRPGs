---
axp: 
xp: 150
Title: The Title
exampleProperty: Novice
---
## Title  `INPUT[text:Title]`

## Rank `INPUT[suggester(option(Novice), option(Apprentice), option(Veteran), option(Master)):exampleProperty]`
```meta-bind-button
label: Add
icon: ""
style: primary
class: ""
cssStyle: ""
backgroundImage: ""
tooltip: ""
id: exp
hidden: True
actions:
- type: updateMetadata
  bindTarget: xp
  evaluate: True
  value: getMetadata('axp') + getMetadata('axp')

```
## Total XP : `VIEW[{xp}][text]`

ADD XP : `INPUT[number:axp]` `BUTTON[exp]`
## HP
`0`
## Aether

`0`
## Stamina
`0`
## Reputation
`0`

| Strength         |                     | Brawn            |     | **Luck**       |     |
| ---------------- | ------------------- | ---------------- | --- | -------------- | :-: |
| **Dexterity**    |                     | **Coordination** |     | **Armor**      |     |
| **Constitution** |                     | **Vitality**     |     | **Speed**      |     |
| **Will**         |                     | **Tenacity**     |     |                |     |
| **Intelligence** |                     | **Intellect**    |     |                |     |
| **Charisma**     |                     | **Charm**        |     |                |     |
| **STR Damage**   |                     | **DEX Damage**   |     | **WIL Damage** |     |
## Skills 
**Acrobatics** (DEX):  `1`

**Animal Handling** (CHA): `1`

**Athletics** (STR): `1`

**Blacksmithing** (DEX): `1`

**Command** (CHA): `1`

**Alchemy** (INT):  `1`

**Gathering** (DEX): `1`

**Medicine** (INT): `1`

**Nature** (INT): `1`

**Literacy** (INT):  `1`

**Manipulation** (CHA): `1`

**Leatherworking** (DEX): `1`

**Insight** (WIL): `1`

**Dodge** (DEX): `1`

**Perception** (WIL): `1`

**Performance** (CHA): `1`

**Sailing** (DEX):  `1`

**Sleight of Hand** (DEX): `1`

**Stealth** (DEX): `1`

**Survival** (INT): `1`

|       **Weapons**        | **Type** | **Damage** |                 **Notes**                  |
| :----------------------: | :------: | :--------: | :----------------------------------------: |
|                          |          |            |                                            |
|                          |          |            |                                            |
|                          |          |            |                                            |

## Head
`INPUT[textArea:Head]`
## Chest
`INPUT[textArea:Chest]`
## Belt
`INPUT[textArea:Belt]`
## Pants 
`INPUT[textArea:Pant]`
## Boots
`INPUT[textArea:Boots]`
## Gloves
`INPUT[textArea:Gloves]`
## Ring 1
`INPUT[textArea:Ring1]`
## Ring 2
`INPUT[textArea:Ring2]`
## Pendant
`INPUT[textArea:Pendant]`
