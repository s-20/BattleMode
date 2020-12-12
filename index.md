# BattleMode

The BattleMode project is my attempt to marry Narrative style role playing with a fun tactical combat system. This is accomplished by having the characters divided into two parts - the Narrative Mode character, and the Battle Mode Character. These two modes are governed by some shared mechanics and _inform_ each other without being bound together.

In most games, being good at combat means you aren't good at something else. This is done in the interest of balancing a system, and it works well enough, but it's also limiting. By separating the Narrative systems from the Combat systems, you can make characters that are good at both without unbalancing the other. That's the theory, anyway.

## Dice Conventions

BattleMode uses four different dice - `d6`, `d8`, `d10`, and `d12`, and will use traditional dice notation throughout the rules (i.e. `2d8` means roll two eight-sided dice and total the results).

The core rule is simple enough - you roll the dice and add them up. If you're trying to accomplish something, you compare it to an Opposed Roll, and if you meet or beat it, you succeed. If you don't you fail. If you beat it by 6 or more, it's a [Major Success](MajorSuccess.md), and if you miss it by more than 6 it's a [Major Failure](MajorFailure.md). Simple. Damage rolls are just roll and add together the dice.

Because the PCs are generally the protagonists, ties go in their favor. If two PCs go up against each other and tie, the higher base dice pool wins - so if a roll of `2d6` and a roll of `2d12` tie, the `2d12` roll wins.

BattleMode uses a simple dice-based bonus and penalty system with Bonus Dice and Penalty Dice.

### Bonus dice

Bonus Dice are how bonuses are handled universally in the system. If you're especially good at something or there are favorable circumstances (or there's any other reason why you should get better than normal results), you add Bonus Dice to the roll.

Bonus dice are extra dice you roll, but you only add up the highest results equal to the base number of dice rolled. Bonus dice are indicated by a lowercase `b` followed by the number of bonus dice appended to the dice notation. So `2d6b2` would mean `roll four six sided dice, and total the two highest results`. If a bonus is to be added to a check, it's noted as `b#` to indicate the number of bonus dice added to the roll.

Bonus Dice and Penalty Dice cancel each other out at a one-for-one rate. See [Bonus Dice](BonusDice.md).

### Penalty dice

Penalty Dice are how penalties are handled universally in the system. If you're especially bad at something, or there are unfavorable circumstances (or there's any other reason why you might get worse than normal results), you add Penalty Dice to the roll.

Penalty dice are extra dice you roll, but you only add up the lowest results equal to the base number of dice rolled. Penalty dice are indicated by a lowercase `p` followed by the number of penalty dice appended to the dice notation. So `4d12p2` would mean `roll six twelve sided dice, and total the four lowest results`. If a penalty is to be added to a check, it's noted as `p#` to indicate the number of penalty dice added to the roll.

Penalty Dice and Bonus Dice cancel each other out at a one-for-one rate. See [Penalty Dice](PenaltyDice.md).

## Narrative Mode

Narrative Mode is used for anything outside of combat or other ordered tactical situation. It can be used to resolve a quick scuffle (two people going for the same gun, for instance), but is generally for out-of-combat situations. During Narrative Mode, you use your [Narrative Sheet](NarrativeSheet.md) to resolve your actions, rolling only when you have to.

The Narrative Sheet is largely descriptive with a few simple mechanics attached to it. You have things you know about, things know how to do, people and organizations you are connected to, and things you suck at outlined on the sheet, broken down by dice values indicating your relative ability or the strength of the connection.

When in Narrative Mode, you usually roll one die (although you may have added Bonus or Penalty dice).

### Perks

Perks are a narrative tool that allows you to re-roll failed checks, negate penalties, and add to the narrative. See [Perks](Perks.md) for more details.

## Battle Mode

Battle Mode is used for tactical situations like Combat, extended chase, and so on. During Battle Mode, you use your [Battle Sheet](BattleSheet.md).

The Battle Sheet outlines your specific combative techniques, dividing them into four groups - Attacks, Defenses, Assists, and Utilities - that all have some overlap. Battle Sheets are built based on _outcomes_, not descriptions, which are still the province of roleplay and interpretation.

For example, if two characters both have an Attack ability that cuts up the enemy for 1d12 damage in melee, but one character uses a knife while the other uses a broadsword, the ability's _mechanics_ are described the same way. The point of the ability is that you cut someone badly, not what sort of implement you used to do it.

Specific techniques or circumstances can have added [Special Effects](SpecialEffects.md) based on what was used to do the deed. For example, if you bash someone with a mace they might be concussed, and if you bash someone with a torch they might be set on fire.

### Prowess

Prowess is the Battle Mode equivalent to Perks - it is a pool that allows you to add bonus dice to a check, negate penalties, improve damage, or add to the effects of a [Technique](Techniques.md). See [Prowess](Prowess.md) for more details.

## Getting Started

To get going, check out [Building Character](BuildingCharacter.md) for how to put together and use your Narrative Sheet, and [Suit Up!](SuitUp.md) for how to put together and use your Battle Sheet. If you're the Game Master, check out [Game Mastering](GMing.md) for how to make and run NPCs and environmental hazards.

## License

[![Creative Commons License](https://i.creativecommons.org/l/by/4.0/80x15.png)](http://creativecommons.org/licenses/by/4.0/)<br>
This work is licensed under a [Creative Commons Attribution 4.0 International License](http://creativecommons.org/licenses/by/4.0/).
