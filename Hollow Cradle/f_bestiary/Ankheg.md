---
obsidianUIMode: preview
noteType: quartzMonster
aliases: ""
tags:
statblock: inline
name: "Ankheg"
cr: 2
---

```statblock
layout: Quartz Layout
columns: 2
forceColumns: true
image: 
name: Ankheg
size: Large
type: Monstrosity
alignment: Neutral
dv: 14
av: 10 "Natural"
hp: 68
hit_dice: 8d10 + 24
speed: "40 ft. Walking, 20 ft. Burrowing"
stats: [18, 10, 16, 3, 12, 5]
saves:
  - strength: 6
  - constitution: 5
skillsaves:
  - athletics: 6
damage_immunities: acid
senses: "Darkvision 60 ft., Tremorsense 30 ft."
languages: None
cr: 2
traits:
  - name: "Disoriented Resistance (2/day)."
    desc: "When the ankheg fails a saving throw, they can succeed instead, and they can't use bonus actions until the end of their next turn."
  - name: "Regenerative Carapace"
    desc: "When the Ankheg succeeds on a saving throw, or it tunnels at least 30 ft. it regains 1d4 [[Armor Value]]. It can only regain Armor Value this way once per turn."
  - name: "Earth Walk."
    desc: "Difficult terrain composed of sand, earth and stone doesn't cost the Ankheg extra movement."
  - name: "Soft Underbelly."
    desc: "When a prone creature within 5 feet of the Ankheg attacks the Ankheg, the attack ignores the Ankheg's [[Armor Value]]."
  - name: "Unstable Tunneler."
    desc: "While burrowing, the Ankheg leaves a 10-foot-diameter tunnel in their wake. Each section of tunnel collapses 1 minute after the Ahkheg leaves that space."
  - name: "Big Bad Bug"
    desc: "Each time a creature triggers the Soft Underbelly feature, the Ankheg gains the ability to perform one of these reactions: Big Bug!, Quick Burrow or Acid Bath."
actions:
  - name: Bite
    desc: "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 7 (1d6 + 4) slashing damage plus 2 (1d4) acid damage. If the target is Large or smaller, they are grappled (escape DC 14). Until this grapple ends, the target is restrained and the Ankheg can't make a Bite attack against another target."
  - name: Claw
    desc: "Melee Weapon Attack: +6 to hit, reach 5 ft., one target. Hit: 13 (2d8 + 4) slashing damage."
  - name: "Acid Spit (Recharge 6)"
    desc: "The ankheg spits acid in a 30-foot long, 5-foot-wide line. Each creature in that area must make a DC 13 Dexterity saving throw. On a failed save, a creature takes 7 (2d6) acid damage and is bathed in acid. On a successful save, a creature takes half as much damage and suffers no other effect. A creature who is bathed in acid takes 3 (1d6) acid damage at the start of each of their turns for 1 minute (save ends at end of turn). A creature can use their action to wipe the acid off themselves or another creature within their reach, ending the effect early."
bonus_actions:
  - name: Earth Eruption
    desc: "While burrowing within 10 feet of the surface, the ankheg erupts (without spending movement) into a 10-foot square on the ground directly above them. This area becomes difficult terrain, and each creature on the ground in this area must make a DC 14 Dexterity saving throw. On a failed save, a creature is pushed 5 feet to an unoccupied space of the ankheg's choice and is restrained by rubble. A creature can use their action to free themself or another creature within their reach. On a successful save, a creature is moved 5 feet to an unoccupied space of the creature's choice and is not restrained."
reactions:
  - name: Skitter
    desc: "When a creature attacks the ankheg, the ankheg can move up to half their speed without provoking opportunity attacks."
  - name: "Big Bug!"
    desc: "The ankheg stands on their hind legs in an impressive and terrifying display of dominance. Each enemy within 30 feet of the ankheg who can see them must make a DC 13 Wisdom saving throw or be frightened of the ankheg for 1 minute (save ends at end of turn)."
  - name: "Quick Burrow."
    desc: "If the ankheg is grappled, the condition ends for them, and they burrow up to twice their speed without provoking [[Opportunity Attack]]. If the ankheg is grappling a Large or smaller creature during this movement, the ankheg's speed is not halved."
  - name: "Acid Bath."
    desc: "Acid sprays from the ankheg's wounds onto each creature within 15 feet of them. Each target must make a DC 13 Dexterity saving throw, taking 7 (2d6) acid damage on a failed save, or half as much damage on a successful one."
```
# Description
