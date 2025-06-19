```statblock
name: "Bog Snake (RB)"
layout: Riftbreakers_2E
description: "*These large serpents blend perfectly with their habitat, posing an ever-present threat to those who dare cross the glades and marshes of Kaethor.*"

actions: "1♟"
agility: "40"
athletics: "30"
cs: "70"
endurance: "60"
evasion: "10"
hp: "18♟"

move: "1"
number: "1"
parry: "0"
perception: "70"

protection: "D6"
tenacity: "30"
type: "Beast"


traits:
  - name: "Traits:"
    desc: "Melee, Vicious (*The creature deals an additional +D4 damage to targets below 50% Health.*)"

action:
  - name: '1-2'
    desc: '**Ambush Strike**: The Bog Snake lashes out from the water or underbrush with startling speed. It makes a Combat Skill check against its target, dealing 2D6 Piercing damage on a hit. If the target was unaware of the Bog Snake at the start of this turn, the attack has Advantage, and the target must pass a Tenacity check or be Dazed (1).'
  - name: '3-4'
    desc: '**Constricting Coil**: The Bog Snake attempts to wrap its massive body around its target. The target must succeed on an Athletics check or become Restrained. While Restrained, the target takes D6 Bludgeoning damage at the start of each of their turns.'
  - name: '5'
    desc: '**Venomous Fang**: The Bog Snake bites at a target, making a Combat Skill check. On a hit, it deals D8+2 Piercing damage and injects venom. The target must pass an Endurance check or become Poisoned (1).'
  - name: '6'
    desc: '**Camouflage**: The Bog Snake becomes Concealed.'

```