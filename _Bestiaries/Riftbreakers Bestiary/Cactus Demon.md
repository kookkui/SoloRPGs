```statblock

name: Cactus Demon

layout: Riftbreakers

description: 'A monstrous creature that resembles a giant cactus, with deadly  spines and tendrils that ensnare its prey.'

Number: 1

Type: 'Plant, Demon'

Speed: 10

Size: Large

Combat Skill: 10

Coordination: 30

Intellect: 20

Tenacity: 70

Vitality: 50

Health: 25

Perception: 40

traits:
  - name: 'Special:'
    desc: 'Vulnerable to Fire and Holy damage, Immune to Poison  damage.'
  - name: 'Apprentice Rank'
    desc: '50 Health, +3 damage,Combat Skill: +10'
  - name: 'Veteran Rank'
    desc: '75 Health, +4 damage, Combat Skill: +20'
  - name: 'Master Rank'
    desc: '100 Health, +5 damage, Combat Skill: +30'
actions:
  - name: '1-2'
    desc: 'Needle Volley: The cactus demon launches a volley of needle-like spines at a target within 20 m, dealing 2D6 Piercing damage. Any creature within 5 m of the target must make a Coordination check or take D6 Piercing damage as well.'
  - name: '3-4'
    desc: "Ensnaring Tendrils: The monster extends its tendrils towards a target within 10 m attempting to Ensnare them. The target must make a Brawn check or be restrained until the start of the cactus demon's next turn, taking D6 Piercing damage each round they remain restrained."
  - name: '5'
    desc: 'Poisonous Thorns: The cactus demon launches a barrage of thorns at a target within 20 m, dealing 2D6 Piercing damage and potentially poisoning the target. The target must make a Vitality check or take D6 Poison damage each round for the next 3 rounds.'
  - name: '6'
    desc: 'Root Bind:The demon tendrils extend into the ground, wrapping around the legs of all creatures within a 10 m radius. Targets must make a Brawn check or become Entangled.'
loot:
  - name: '1-30'
    desc: '20**⟑**'
  - name: '31-40'
    desc: '10 units of a Random Alchemical ingredient'
  - name: '41-50'
    desc: '1x Potion'
  - name: '51-55'
    desc: 'Alchemical formula. Roll on the Potions & Unguents table'
  - name: '56-72'
    desc: 'Skill Book'
  - name: '73-80'
    desc: 'Enhanced Sickle'
  - name: '81-87'
    desc: 'Essence. Roll on the Random Essence table'
  - name: '88-95'
    desc: 'Heart. Roll on the Random Heart table '
  - name: '96-100'
    desc: 'Random Magic Item'
```