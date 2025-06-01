---
Exterminator: 5
money: 200
moneyAdd: 
cheevo1: false
ExterminatorAdd: 1
monster1: false
monster2: false
monster3: false
monster4: true
monster5: false
monster6: true
monster7: false
cheevo7: false
explore1: false
explore3: true
explore4: false
heals: 0
healsAdd: 
riftbreaker: false
cheevo15: false
---
#### Adventurer
>[!travel] %%FAKE TITLE HERE%%
>>[!travel]  #### Adventurer `INPUT[toggle:cheevo1]`
>>
>>`1/50`
>>
>>&nbsp;
>>*Complete 50 Quests.* 
>>*Reward: Title -"Adventurer" Increase all quest rewards by 50%.*

#### Alchemist
>[!table] %%FAKE TITLE HERE%%
>>[!table] #### Alchemist `INPUT[toggle:cheevo2]`
>>
>>`0/50`
>>
>>&nbsp;
>>*Craft 50 Potions* 
>>*Reward: 100 XP, 100A* 
>>

#### Master Alchemist
>[!done] %%FAKE TITLE HERE%%
>>[!done] #### Master Alchemist `INPUT[toggle:cheevo3]`
>>
>>`0/100`
>>
>>&nbsp;
>>*Craft 100 Potions* 
>>*Reward: 300 XP, 300A* 
>>

#### Master Crafter
>[!example] %%FAKE TITLE HERE%%
>>[!example] #### Master Crafter `INPUT[toggle:cheevo4]`
>>`0/100`
>>
>>&nbsp;
>>*Craft 100 Items.* 
>>*Reward: 100 XP, 100A And one magic item.*
>>

#### Pest Control
>[!bug] %%FAKE TITLE HERE%%
>>[!bug] #### Pest Control `INPUT[toggle:cheevo5]`
>>`5/100`
>>
>>&nbsp;
>>*Defeat 100 Monsters.* 
>>*Reward: 100 XP, 100A And one magic item.*
>>

#### Exterminator
>[!crafting] %%FAKE TITLE HERE%%
>>[!crafting] #### Exterminator `INPUT[toggle:cheevo6]`
>>```meta-bind
>>INPUT[progressBar(maxValue(500)):Exterminator]
>>```
>>
>>&nbsp;
>>`INPUT[number:ExterminatorAdd]` `BUTTON[ext]`
>>
>>&nbsp;
>>*Defeat 500 Monsters.* 
>>*Reward: Title -"Exterminator", Deal +5 damage.* 
>>

#### Master Hunter
>[!gear] %%FAKE TITLE HERE%%
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
>>*Reward: 100 XP, 100A*

#### Climbing the Ladder
>[!table] %%FAKE TITLE HERE%%
>>[!table] #### Climbing the Ladder `INPUT[toggle:cheevo8]`
>>`INPUT[toggle:apprentice]` Reach Apprentice Rank.
>>
>>&nbsp
>>*Reward: Title - "Apprentice", Increase your Stamina and Aether pools by +2.*
>>

#### Merchant Prince
>[!done] %%FAKE TITLE HERE%%
>>[!done] #### Merchant Prince `INPUT[toggle:cheevo9]`
>> ## `VIEW[{money}][text]`/10000 
>>
>>&nbsp
>>`INPUT[number:moneyAdd]` `BUTTON[bling]`
>>
>>&nbsp
>>*Obtain a total of 10,000 Aetheryte regardless of its Rank.*
>>*Reward: Sell items for 60% of their value, instead of 50%.*
>>

#### Crafter
>[!crafting] %%FAKE TITLE HERE%%
>>[!crafting] #### Crafter `INPUT[toggle:cheevo10]`
>>`0/50`
>>
>>&nbsp
>>*Craft 50 Items.* 
>>*Reward: 100 XP, 100A*

#### Miner
>[!gather] %%FAKE TITLE HERE%%
>>[!gather] #### Miner `INPUT[toggle:cheevo10]`
>>`1/50`
>>
>>&nbsp
>>*Mine 50 Ore Veins. Reward: Title -"Miner". Repeat a failed roll when attempting to find an ore vein.*

#### Explorer
>[!note] %%FAKE TITLE HERE%%
>>[!note] #### Explorer `INPUT[toggle:cheevo11]`
>>`INPUT[toggle:explore1]` Arenmist Forest
>>`INPUT[toggle:explore2]` Bonespire Peaks
>>`INPUT[toggle:explore3]` Crystal Plains
>>`INPUT[toggle:explore4]` The Violet Sands
>>
>>&nbsp
>>*Visit each region of Kaethor,  Reward: 100 XP*

#### One in a Thousand
>[!npc] %%FAKE TITLE HERE%%
>>[!npc] #### One in a Thousand `INPUT[toggle:cheevo12]`
>>`INPUT[toggle:vet]` Reach Veteran Rank.
>>
>>&nbsp
>>*Reward: Title - "Veteran",  Increase your Luck by +10.* 
>>

#### Healer
>[!dice] %%FAKE TITLE HERE%%
>>[!dice] #### Healer `INPUT[toggle:cheevo13]`
>> ## `VIEW[{heals}][text]`/10000 
>> 
>>
>>&nbsp
>>`INPUT[number:healsAdd]` `BUTTON[life]`
>>
>>&nbsp
>>*Heal other characters for a total of 1,000 Health.*
>>*Reward: Title -"Healer". Increase your healing effects by +1.* 
>>

#### Herbalist
>[!check] %%FAKE TITLE HERE%%
>>[!check] #### Herbalist `INPUT[toggle:cheevo14]`
>>`1/50`
>>
>>&nbsp
>>*Obtain 50 ingredients via gathering.* 
>>*Reward: Title -"Herbalist". Repeat a failed roll when attempting to find ingredients.*

#### Riftbreaker
>[!note] %%FAKE TITLE HERE%%
>>[!note] #### Riftbreaker `INPUT[toggle:cheevo15]`
>>`INPUT[toggle:riftbreaker]` Successfully close a Rift.
>>
>>&nbsp
>>*Reward: 100XP and one random magic item.*
>>

#### Hero
>[!bug] %%FAKE TITLE HERE%%
>>[!bug] #### Hero `INPUT[toggle:cheevo16]`
>>`0/100`
>>
>>&nbsp
>>*Complete 100 Quests.* 
>>*Reward: Title -"Hero". Increase all quest rewards by 100%.*
>>

#### Riftbane
>[!crafting] %%FAKE TITLE HERE%%
>>[!crafting] #### Riftbane `INPUT[toggle:cheevo17]`
>> `0/20` 
>>
>>&nbsp
>>*Successfully close 20 Rifts.*
>>*Reward: Title -"Riftbane". While in a Rift. +20 attack skills, +2 damage dealt.* 
>>

#### I Have the Power
>[!table] %%FAKE TITLE HERE%%
>>[!table] #### I Have the Power `INPUT[toggle:cheevo18]`
>>`5/20`
>>
>>&nbsp
>>*Unlock all 20 Abilities.*
>>*Reward: Title - "Powerful". Re-roll any failed check once each 24 hours.*

#### Skilled
>[!dice] %%FAKE TITLE HERE%%
>>[!dice] #### Skilled `INPUT[toggle:cheevo19]`
>>`INPUT[toggle:skilled]` Reach 100 with one skill. 
>>
>>&nbsp
>>*Reward: 400 XP* 

#### Legendary
>[!npc] %%FAKE TITLE HERE%%
>>[!npc] #### Legendary `INPUT[toggle:cheevo20]`
>>`INPUT[toggle:legendary]` Obtain a Legendary Item.
>>
>>&nbsp
>>*Reward: 300A*

#### Top of the Mountain
>[!gear] %%FAKE TITLE HERE%%
>>[!gear] #### Top of the Mountain 
>>`INPUT[toggle:mounter]` Reach Master Rank.
>>
>>&nbsp
>>*Reward: Title -"Master" Increase your Health by +10.* 
 

```meta-bind-button
label: Add
icon: ""
style: primary
class: ""
cssStyle: ""
backgroundImage: ""
tooltip: ""
id: ext
hidden: True
actions:
- type: updateMetadata
  bindTarget: Exterminator
  evaluate: True
  value: getMetadata('Exterminator') + getMetadata('ExterminatorAdd')

```



```meta-bind-button
label: Add
icon: ""
style: primary
class: ""
cssStyle: ""
backgroundImage: ""
tooltip: ""
id: bling
hidden: True
actions:
- type: updateMetadata
  bindTarget: money
  evaluate: True
  value: getMetadata('money') + getMetadata('moneyAdd')

```

```meta-bind-button
label: Add
icon: ""
style: primary
class: ""
cssStyle: ""
backgroundImage: ""
tooltip: ""
id: life
hidden: True
actions:
- type: updateMetadata
  bindTarget: heals
  evaluate: True
  value: getMetadata('heals') + getMetadata('healsAdd')

```