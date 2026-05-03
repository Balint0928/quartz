---
obsidianUIMode: preview
noteType: quartzMonster
aliases:
  - Medusa
tags:
statblock: inline
name: Medusa
cr: "6"
---

```statblock
layout: Quartz Layout
columns: 2
forceColumns: true
image: 
name: Medusa
size: Medium
type: Monstrosity
subtype: 
alignment: Lawful Evil
dv: 16
av: 1 "Natural"
hp: 130
hit_dice: 17d8
speed: "30 ft."
stats: [16, 20, 18, 12, 13, 14]
saves:
  - strength: 6
  - dexterity: 8
  - constitution: 7
skillsaves:
  - deception: 5
  - insight: 4
  - perception: 4
  - stealth: 5
damage_vulnerabilities: 
damage_resistances: 
damage_immunities: Poison
condition_immunities: [[Poisoned]]
senses: "Darkvision 60 ft."
languages: common
cr: 6
traits:
  - name: "[[Weapon Mastery]] with Scimitar."
    desc: "Access to the [[Versatile blade]] and [[Biting Blade]]"
  - name: "Nimble Escape."
    desc: "As a bonus action can take the [[Disengage Action]] or Hide Action"
  - name: "Stone Vein"
    desc: "When the Medusa hits a creature with its bite attack that is under the Poisoned condition, the target is immediately subjected to the effects of Stone Gaze"
  - name: "Multiattack"
    desc: "Stone Gaze and one Snake Bite or Two Scimitar or Longbow attacks"
actions:
  - name: Snake Bite
    desc: "Melee Weapon Attack: +8 to hit, reach 5 ft., one creature. Hit: 10 (3d6) poison damage, and the target must succeed on a DC 15 Constitution saving throw or be poisoned until the end of the medusa's next turn."
  - name: Scimitar
    desc: "Melee Weapon Attack: +8 to hit, reach 5 ft., one creature. Hit: 1d6 + 3 Slashing damage"
  - name: Longbow
    desc: "Ranged Weapon Attack: +8 to hit, reach 5 ft., one creature. Hit: 1d8 + 5"
  - name: "Venom Shower"
    desc: "Free action, once per turn. Black venom rains down in a 10-foot-radius, 40-foot-high cylinder centered on a point the medusa can see within 90 feet of them. Each creature in that area must succeed on a DC 15 Constitution saving throw or be Poisoned until the end of its next turn."
bonus_actions:
  - name: [[Disengage Action]]
  - name: Hide Action
reactions:
  - name: "Shadowstep"
    desc: "After a creature misses her with a melee attack, as a reaction, teleport to an area of dim light or darkness within 30 feet."
```