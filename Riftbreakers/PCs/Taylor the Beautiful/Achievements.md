---
Exterminator: 65
money: "600"
cheevo1: false
ExterminatorAdd: 
monster1: true
monster2: true
monster3: true
monster4: true
monster5: true
monster6: true
monster7: true
cheevo7: true
---
>[!thing] %%FAKE TITLE HERE%%
>>[!travel]  #### Adventurer `INPUT[toggle:cheevo1]`
>>
>>`2/50`
>>
>>&nbsp;
>>*Complete 50 Quests.* 
>>*Reward: Title -"Adventurer". Increase all quest rewards by 50%.*
>>
>>---
>>[!table] #### Alchemist `INPUT[toggle:cheevo2]`
>>
>>`0/50`
>>
>>&nbsp;
>>*Craft 50 Potions. Reward: 100 XP. 100 A* 
>>
---
>>[!done] #### Master Alchemist `INPUT[toggle:cheevo3]`
>>
>>`0/100`
>>
>>&nbsp;
>>*Craft 100 Potions. Reward: 300 XP. 300 A* 
>>
---
>>[!example] #### Master Crafter `INPUT[toggle:cheevo4]`
>>`0/100`
>>
>>&nbsp;
>>*Craft 100 Items. Reward:100 XP. 100 A And one magic item.*
>>
---
>>[!bug] #### Pest Control `INPUT[toggle:cheevo5]`
>>`62/100`
>>
>>&nbsp;
>>*Defeat 100 Monsters. Reward: 100 XP, 100A And one magic item.*
>>
---
>>[!crafting] #### Exterminator `INPUT[toggle:cheevo6]`
>>```meta-bind
>>INPUT[progressBar(maxValue(500)):Exterminator]
>>```
>>
>>&nbsp;
>>`INPUT[number:ExterminatorAdd]` `BUTTON[exp]`
>>
>>&nbsp;
>>*Defeat 500 Monsters.* 
>>*Reward: Title -"Exterminator". Deal +5 damage.* 
>>
---
>>[!gear] #### Master Hunter `INPUT[toggle:cheevo7]`
>>Defeat one monster of each type.
>>`INPUT[toggle:monster1]` Astral
>>`INPUT[toggle:monster2]` Plant
>>`INPUT[toggle:monster3]`Demon
>>`INPUT[toggle:monster4]` Elemental
>>`INPUT[toggle:monster5]` Undead
>>`INPUT[toggle:monster6]` Humanoid
>>`INPUT[toggle:monster7]`Construct
>>
>>&nbsp
>>*Reward: 100 XP 100A*

---
>>[!table] #### Climbing the Ladder `INPUT[toggle:cheevo8]`
>>`INPUT[toggle:apprentice]` Reach Apprentice Rank.
>>
>>&nbsp
>>*Reward: Title - "Apprentice". Increase your Stamina and Aether pools by +2.*
>>
---
#### Merchant Prince
`INPUT[text:money]`/10000 
Obtain a total of 10,000 Aetheryte. regardless of its Rank. *Reward: Sell items for 60% of their value, instead of 50%.*

---
#### Crafter 
`0/50`
*Craft 50 Items. Reward: 100 XP. 100 A*

---
#### Miner
`4/50`
Mine 50 Ore Veins. *Reward: Title -"Miner". Repeat a failed roll when attempting to find an ore vein.*

---
#### Explorer
- [x] Arenmist Forest
- [ ] Bonespire Peaks
- [x] Crystal Plains
- [x] The Violet Sands
Visit each region of Kaethor.  *Reward:100 XP* 

---
#### One in a Thousand
- [ ] Reach Veteran Rank.
*Reward: Title - "Veteran".  Increase your Luck by +10.* 

---
#### Healer 
 `INPUT[text:Heals]`/1000
Heal other characters for a total of 1,000 Health. *Reward: Title -"Healer". Increase your healing effects by +1.* 

---

#### Herbalist
`12/50`
Obtain 50 ingredients via gathering. *Reward: Title -"Herbalist". Repeat a failed roll when attempting to find ingredients.*

---
#### Riftbreaker 
- [x] Successfully close a Rift.
Reward: 100XP and one random magic item. 

---
#### Hero
`3/100`
Complete 100 Quests. *Reward: Title -"Hero". Increase all quest rewards by 100%.*

---

#### Riftbane
`3/20` 
Successfully close 20 Rifts. *Reward: Title -"Riftbane". While in a Rift. +20 attack skills, +2 damage dealt.* 

---
#### I Have the Power
`7/20` 
Unlock all 20 Abilities. 
*Reward: Title - "Powerful". Re-roll any failed check once each 24 hours.*

---
#### Skilled
- [ ] Reach 100 with one skill. 
*Reward: 400 XP* 

---
#### Legendary 
- [ ] Obtain a Legendary Item. 
*Reward: 300A*

---
#### Top of the Mountain 
- [ ] Reach Master Rank. 
*Reward: Title -"Master" Increase your Health by +10.* 
 

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
  bindTarget: Exterminator
  evaluate: True
  value: getMetadata('Exterminator') + getMetadata('ExterminatorAdd')

```



```meta-bind
INPUT[progressBar:exampleProperty]
```
