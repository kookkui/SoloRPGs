```statblock
name: "Crystal Construct"
layout: Riftbreakers_2E
description: "*A creature made entirely of crystal, that can shoot sharp crystal shards and use its tough, armor-like body to compensate for its slow movement.*"

actions: "1♟"
agility: "10"
athletics: "80"
cs: "50"
endurance: "80"
evasion: "0"
hp: "25♟"

move: "1"
number: "1"
parry: "0"
perception: "50"

protection: "D6+2"
tenacity: "40"
type: "Construct"


traits:
  - name: "Traits:"
    desc: "Ranged, Titanic. Resistant to Void damage, and Immune to Necrotic Damage and the Charmed, Poisoned, Bleeding, Frightened, and Asleep conditions."

action:
  - name: '1-2'
    desc: '**Crystal Shard:** The Crystal Construct shoots sharp crystal shards at a target, making a Combat Skill check that deals 2D6 Piercing damage on a hit.'
  - name: '3-4'
    desc: '**Crystal Spike:** The Crystal Construct makes a Combat Skill check summoning a sharp spike of crystal from the ground beneath a random target that deals D8 Piercing damage and knocks them Prone.'
  - name: '5'
    desc: '**Reflective Shield:** The Crystal Construct creates a reflective shield that lasts until the end of its next turn. Any ranged attacks made against the construct during this time are reflected back at the attacker.'
  - name: '6'
    desc: '**Crystalize:** The Crystal Construct channels energy into a single target,attempting to transform them into a crystal statue. The target must make an Endurance check or be *Paralyzed (2)*.'

```