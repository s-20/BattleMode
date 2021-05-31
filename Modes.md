# Modes

The Modes project is my attempt to marry Narrative style role playing with a fun tactical combat system. The game has two primary Modes (Battle and Narrative), hence the name.

In most games, being good at combat means you aren't good at something else. This happens in the interest of balancing a system, and it works well enough, but by separating the Narrative systems from the Combat systems, you can make characters that are good at both without unbalancing the other. That's the theory, anyway.

The other advantage is that the two systems, though interconnected, can operate independently of each other. If you're not interested in tactical combat, use Narrative Mode and resolve the odd fights using that system. If you prefer a different system to handle narrative aspects of the game (like [Gumshoe](https://en.wikipedia.org/wiki/Gumshoe_System) or something), then use that and switch over to Battle Mode for your fun tactical combat shenanigans. If all you want is to have a skirmish in either PVP or PVE mode, then use Battle Mode and ignore the rest, or write up backgrounds for the characters to give them a little depth and hang simplistic mechanics on those if it comes up. 

## Basic Framework

Modes uses three types of dice - `d4`, `d6`, and `d8`, with `d6` being the most common. When you make a `Check`, you roll three or more dice, totaling either the highest or the lowest three dice (see [Systems: Bonus and Penalty](Systems.BonusPenalty.md)). You compare the total to a target number (the [Difficulty](Systems.Difficulty.md) or `DIF`), or the result of an opposed roll.

If your dice roll within five below the target number but not equal to the number itself, then you succeed - but barely, and there's a twist to your victory. If you roll lower than that, you've failed marginally - you still make progress or achieve some effect, but you don't quite get there. If your roll exceeds the value, you succeed at the task.

There are two other possible results - [Major Failure and Major Success](Systems.MajorSF.md). If all the dice you count are a 1, then you have a Major Failure, and if you exceed the amount you needed by 5 more more, you have a Major Success.

*Major Failure* means not only to you fail at what you were trying to do, but something may happen to make your life more difficult - failure with a twist. *Major Success* means that you not only accomplish your goal, you gain some additional benefit as well - either immediately, or carried forward to a later `Check` or event.

> **Further Reading:**
> * [Systems: Checks and Challenges](Systems.Checks.md)
> * [Systems: Difficulty](Systems.Difficulty.md)
> * [Systems: Major Success and Failure](Systems.MajorSF.md)

### Rounding

You are sometimes asked to reduce a value by half. In these cases, you always round *up* if you end up with a fraction; if you were to take half of a `5`, you'd end up with a `3`.

One exception to this is if the initial value is `1`. If you need to half a value, and that value starts at `1`, reduce it to `0` instead.

### Battle Mode

During a fight or other action conflict, you roll the dice and add them up. If you're trying to do something, you compare it to an Opposed Roll, and if you meet or beat it, you succeed. If you don't you fail, but you may be able to apply some sort of "fail forward" benefit for your efforts. This can take the form of a minor penalty to the opponent, lesser damage, or providing a small benefit to an ally.

If you beat an opposed roll or [Difficulty](Systems.Difficulty.md) by 5 or more, it's a [Major Success](Systems.MSF.md), and if you miss it by 5 or more it's a [Major Failure](Systems.MSF.md). Anything more than 5 either way can mean a more dramatic success/failure, but doesn't always.

Because the PCs are generally the protagonists, ties go in their favor. If two PCs go up against each other and tie, the higher base dice pool wins; add up the highest values of the dice used to determine the highest pool, so if a roll of `1d4+1d6` and a roll of `1d12` tie, the `1d12` roll wins. . If there's *still* a tie, then decide what happens in that context; sometimes, efforts are identically matched, after all.

See [Battle Mode](Mode.Battle.md) for more information.

### Narrative Mode

Outside of combat, Modes avoids rolls unless they're needed. Often, there's one interesting possible outcome for an attempted task, and failure grinds the narrative to a hault. So we skip all that nonsense and call it a win, with the degree of success based on the highest dice value available to the character if degrees of success can have interesting narrative effect. 

If more than one interesting result is available, Narrative Mode uses the same set of dice, but they're assigned to descriptive skills, talents, and abilities of a character called [Traits](Narrative.Traits.md). You either roll the dice and compare the total (again using the five highest results) to a static [Difficulty](Systems.Difficulty.md) or, if going up against another PC, sn opposed roll.

See [Modes: Narrative](Mode.Narrative.md) for more information.

## Bonus/Penalty Shifts

Having an extra edge for whatever reason provides a Bonus Shift (or a *Shift Up*), while adverse circumstances inflict Penalty Shifts (or a *Shift Down*).

Shifts change the dice type. A Bonus Shift increases the lowest value die by one, while a Penalty Shift decreases your highest dice value. Shifting a die below `d4` eliminates it from the roll, while shifting above `d12` adds a `d4` to the roll.

Up and Down shifts cancel each other out - `Bonus 2` and `Penalty 3` on the same check results in a `Penalty 1`, or 1 shift down. Shifts cap at 5 - you cannot have a Bonus or Penalty higher than 5 on any single check.

For more information, see [Systems: Bonuses and Penalties](Systems.BonusPenalty.md).

### The 1d4 Bounce

If you had more than one die for a particular task and penalties reduce you to `d4` for a given task, then the die can *bounce*. If you roll a `4`, roll the die again and add in the new result as well. The `1d4` bounces once - if you roll another `4`, then your total is 8 and you stop rolling.

This doesn't apply if you had a `1d4` to begin with.

## Damage Rolls

In combat, if you deal damage you roll the indicated dice for the attack you're using. You also add any excess you had on the to-hit roll. So if you needed a `10` and your total roll was `13`, you would deal `Attack Damage +3` to the [Hit Points](Systems.HitPoints.md) of your target.

If you roll a Major Success, you also inflict [Trauma](Systems.Trauma.md) - a severe, potentially scarring or crippling injury. Trauma can lead to death or being permanently taken out of action in some other way, so be careful.

Players also roll to defend against incoming attacks. A successful Defense reduces the incoming damage by half, or to 0 for a Major Success. On a Major Failure, you may take Trauma at the GM's discretion.

## Read Next

THe following articles are helpful reading after this one:

* [Battle Mode](Mode.Battle.md)
* [Character Creation](Systems.CharacterCreation.md)
* [Narrative Mode](Mode.Narrative.md)
* 

## License

[![Creative Commons License](https://i.creativecommons.org/l/by/4.0/80x15.png)](http://creativecommons.org/licenses/by/4.0/)<br>
This work is licensed under a [Creative Commons Attribution 4.0 International License](http://creativecommons.org/licenses/by/4.0/).
