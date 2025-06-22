```statblock
name: "Grove Guardian (RB)"
layout: Riftbreakers_2E
description: "*A fierce creature that resembles a mix between a bear and a tree, that defends its territory with brute force.*"

actions: "1♟"
agility: "30"
athletics: "80"
cs: "60"
endurance: "80"
evasion: "0"
hp: "22♟"

move: "1"
number: "1"
parry: "10"
perception: "60"

protection: "D8"
tenacity: "60"
type: "Beast, Plant"


traits:
  - name: "Traits:"
    desc: "Melee, Suppression Aura. Vulnerable to Fire damage, but Immune to the Frightened and Blinded conditions."

action:
  - name: '1-2'
    desc: '**Bear Swipe**: The Grove Guardian makes a Combat Skill check, attacking with its clawed paw and dealing D8+2 Slashing damage to its target on a hit.'
  - name: '3-4'
    desc: '**Entangling Roots**: The Grove Guardian targets up to three creatures within its Combat Zone, causing roots to grow from the ground. Targets must pass an Agility check or become Restrained. Restrained characters suffer 1 Piercing damage every round.'
  - name: '5'
    desc: '**Feral Roar**: The Grove Guardian lets out a feral roar that terrifies all creatures within its Combat Zone, forcing them to make a Tenacity check. Those who fail the check are Frightened (20).'
  - name: '6'
    desc: '**Earthquake**: The Grove Guardian slams its massive paw onto the ground, causing an earthquake in its Combat Zone. All creatures within the area must make an Athletics check or be knocked Prone and take D8 Bludgeoning damage. Creatures that succeed take half damage and are not knocked Prone.'

```