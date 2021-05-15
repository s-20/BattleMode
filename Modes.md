# Modes

The Modes project is my attempt to marry Narrative style role playing with a fun tactical combat system. The game has two primary Modes (Battle and Narrative), hence the name.

In most games, being good at combat means you aren't good at something else. This happens in the interest of balancing a system, and it works well enough, but by separating the Narrative systems from the Combat systems, you can make characters that are good at both without unbalancing the other. That's the theory, anyway.

The other advantage is that the two systems, though interconnected, can operate independently of each other. If you're not interested in tactical combat, use Narrative Mode and resolve the odd fights using that system. If you prefer a different system to handle narrative aspects of the game (like [Gumshoe](https://en.wikipedia.org/wiki/Gumshoe_System) or something), then use that and switch over to Battle Mode for your fun tactical combat shenanigans. If all you want is to have a skirmish in either PVP or PVE mode, then use Battle Mode and ignore the rest, or write up backgrounds for the characters to give them a little depth and hang simplistic mechanics on those if it comes up. 

## Basic Framework

Modes uses five different dice - `d4`, `d6`, `d8`, `d10`, and `d12`, and uses traditional dice notation throughout the rules (i.e. `2d8` means roll two eight-sided dice and total the results). If for some reason you find yourself rolling more than five dice, you count the five highest values. This means there's a technical limit to how high your results can go (5x12= 60).

Modes works primarily by rolling and totalling dice. "Flat bonuses" (i.e. `+2`) exist, but are a secondary system.

### Battle Mode

During a fight or other action conflict, you roll the dice and add them up. If you're trying to do something, you compare it to an Opposed Roll, and if you meet or beat it, you succeed. If you don't you fail, but you may be able to apply some sort of "fail forward" benefit for your efforts. This can take the form of a minor penalty to the opponent, lesser damage, or providing a small benefit to an ally.

If you beat an opposed roll by 5 or more, it's a [Major Success](MajorSuccess.md), and if you miss it by 5 or more it's a [Major Failure](MajorFailure.md).

Because the PCs are generally the protagonists, ties go in their favor. If two PCs go up against each other and tie, the higher base dice pool wins. If which is higher isn't obvious, add up the highest values of the dice used - so if a roll of `1d4+1d6` and a roll of `1d12` tie, the `1d12` roll wins. . If there's *still* a tie, then decide what happens in that context; sometimes, efforts are identically matched, after all.

See [Battle Mode](Mode.Battle.md) for more information.

### Narrative Mode

Outside of combat, Modes avoids rolls unless they're needed. Often, there's one interesting possible outcome for an attempted task, and failure grinds the narrative to a hault. So we skip all that nonsense and call it a win, with the degree of success based on the highest dice value available to the character if degrees of success can have interesting narrative effect. 

If more than one interesting result is available, Narrative Mode uses the same set of dice, but they're assigned to descriptive skills, talents, and abilities of a character called [Traits](Narrative.Traits.md). You either roll the dice and compare the total (again using the five highest results) to a static Difficulty Value, or you determine the results based on how high the total is.

See [Narrative Mode](Mode.Narrative.md) for more information.

## Bonus/Penalty dice

Having an extra edge for whatever reason provides Bonus Dice, while adverse circumstances inflict Penalty Dice.

Bonus dice are extra dice you roll. A small bonus would provide `+1d4`, with larger bonuses providing higher value dice up to the lowest value die you already have for a roll. For example, if you're rolling `1d6+1d8` for a particular task, your bonus dice couldn't have a value above `1d6`.

Penalty Dice devalue the dice you're using instead. Each penalty reduces the value of your highest die by one step - from `d12` to `d10`, from `d10` to `d8`, and so on. 

A penalty die applied to a `d4` eliminates the die, but penalties can't reduce your roll below `1d4` total (so if you had 10 penalties applied to a `1d6+2d8` check, you'd roll `1d4`).

### The 1d4 Bounce

If you had more than one die for a particular task and penalties reduce you to `d4` for a given task, then the die can *bounce*. If you roll a `4`, roll the die again and add in the new result as well. The `1d4` bounces once - if you roll another `4`, then your total is 8 and you stop rolling.

This doesn't apply if you had a `1d4` to begin with.

## Narrative Mode

[Narrative Mode](Mode.Narrative.md)

## Battle Mode

[Battle Mode](Mode.Battle.md)

## Read Next

THe following articles are helpful reading after this one:

* [Battle Mode](Mode.Battle.md)
* [Character Creation](CharacterCreation.md)
* [Narrative Mode](Mode.Narrative.md)


## License

[![Creative Commons License](https://i.creativecommons.org/l/by/4.0/80x15.png)](http://creativecommons.org/licenses/by/4.0/)<br>
This work is licensed under a [Creative Commons Attribution 4.0 International License](http://creativecommons.org/licenses/by/4.0/).
