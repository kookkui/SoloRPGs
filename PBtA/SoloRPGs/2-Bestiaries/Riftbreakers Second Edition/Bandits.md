```statblock
name: "Bandits"
layout: Riftbreakers 2E
description: "*Ruthless men and women who profit from assaulting the trade caravans and lone travelers in the area, They are skilled in both ranged and melee combat, and are not afraid to resort to dirty tactics to gain the upper hand.*"
actions: "1"
agility: "60"
athletics: "40"
cs: "50"
endurance: "40"
evasion: "15"
hp: "8"
move: "1"
number: "31"
parry: "15"
perception: "50"
protection: "D6"
tenacity: "60"
type: "Humanoid"

traits:
  - name: "Traits:"
    desc: "Melee, Swift, Stalker."

action:
  - name: '1-2'
    desc: '**Sneak Attack:** The Bandit attempts to catch their target off guard,making a Combat Skill check and dealing D8+2 Piercing damage if they succeed. Target must pass a Perception check or suffer an additional <br>+2 damage if hit.'
  - name: '3-4'
    desc: '**Ranged Assault:** The Bandit takes aim with their crossbow, making aCombat Skill check, and firing a bolt that deals D6+2 Piercing damage to a random target within 2 Combat Zones if successful. If the target is within the same Combat Zone, they also suffer a -20 penalty to theirnext attack.'
  - name: '5'
    desc: '**Empty Pockets:** The Bandit makes an Agility check, attempting to robtheir target. If they succeed, the target loses D20A. The target recovers half of the total amount they lost once the fight is over.'
  - name: '6'
    desc: "**Dirty Trick:** The Bandit throws sand or dirt in their target's face. The target is Blinded for 1 round."
 
```