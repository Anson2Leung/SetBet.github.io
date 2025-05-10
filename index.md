# Team Jace: Set Bet

![](doc/FireSheep-FCTWhite.png)


#### Team Members:
* Joseph Carmelo Averion
* Anson Leung
* Ciara Kang
* Eric Zhou

## Table of Contents
* [Overview](#overview)
* [Introduction](#game-introduction)
* [Next Steps](#next-steps)

## Overview


## Game Introduction
Set Bet is a deck-builder roguelike that takes inspiration from games like Balatro and Dicey Dungeon. The player must defeat their enemies by placing down bets that can trigger a variety of effects, like copying adjacent bets, drawing cards, and so on (aside from dealing damage). These effects are triggered if the appropriate conditions are met, the most basic one is having a stronger poker hand than the opponent. Currently, the game features an endless set of enemies with randomized bets that scale in health with each win, so see how far you can get.

## Gameplay


### Battle Sequence
The turn starts with the player and opponent drawing cards out of their deck; the enemy and the player have their own 52-card deck to draw from. They will also have a hand of bets capped at a limit of 4. The enemy will play their bets before the player does, so they can have a plan accordingly. Afterwards, the enemy will play their poker hand faced down. The player will then build their poker hand to play, where they can not swap out cards in their hand like in Poker, but unused cards will remain in their hand. The poker hands are then evaluated with the bets of the opponent and the player being evaluated, and having their effects executed. If the player or opponent is not defeated, the cycle repeats, and if the 52-card deck runs out, discarded cards are reshuffled.

## Next Steps
1. Improved enemy AI that decides on what bets to play and what poker hand to make according to what bets are on the table.
2. Remove hand size restrictions on enemies.
3. Add cutscenes and transitions between battles.
4. A way mechanic change to player's bets (e.g., a shop, end battle reward, etc.)
5. More types of bets (like copying the enemy's bet, adding block, etc.)
6. Preset enemies with set bets and artwork associated with them.