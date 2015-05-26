The goals of this game:

* Simple to implement - grid for tactics, cards for game
* Emergent tactical complexity - playing should not be difficult
* Handicap system - experienced players should still have a hard game
* character progression - options and power should both increase over time
* low preparation - No involved deck construction; should be able to set up in 5 minutes.


### Overall gameplay

The game is played as a series of scenarios, each composed of multiple encounters.
An encounter is a single tactical game - the heroes start on the board with some enemies,
and others enter through certain locations after given turn counts. Tactical play is
similar to pathfinder - we are playing on a square grid map, drawn in wet-erase on a mat.
movement and los are ripped from PF, but actual combat is much less random - we use fudge
dice to provide randomness, and damage is rarely random at all.

Characters are represented by minis on the board, but their abilities are determined by
the cards in their hand, and by the characters' skills (always-available abilities).
Units do have 'HP', but the numbers are low - heroes mostly have `4 + x/2` (x is always
level) hit points, and early enemies mostly have one or two.

The scenarios and encounters are going to be designed for a particular number of characters,
but the handicap system can be used to compensate by plus or minus 1 player. (Our initial
module will be three scenarios designed for 2 players and a GM). Objectives are not always
to kill all the enemies (though that is probably the most common one) - they might include
getting all players to some exit, destroying a dangerous artifact, reaching an defeating
a boss, surviving N rounds, or escorting an NPC to safety. Or anything else the level
designer can come up with - the only rule is that the heroes need to know the winning condition
before the level starts! Secrets kill replayability.

### Deck Management

Each character comes with 20 cards from which to construct their play deck - they choose
12 of those cards to play with. After each encounter, they may switch out one card if
they like (but no more). Randomly choosing cards should result in a workable game - there
should be very few cards that cannot be used for an attack of some kind.

The cards all have some basic ability, and all list additional effects that come into
play at different levels - a level 1 moonfire just attacks for one damage against a
target, but a level 3 moonfire also keeps it from moving next turn, and a level 5
moonfire can be cast with a move action as well as a standard action. A level 1 fireball
has a chance to damage each adjacent unit, a level 2 fireball has a reduced chance to
damage heroes, a level 4 fireball lights all damaged units on fire, and a level 6
fireball does 3 damage to the main target instead of 1.

Using an action usually requires a resource to be spent - each round you get one standard,
one movement, and one swift action card to spend; each resource can be spent as any lower
resource. (A "Full" resource takes both a move and a standard action). During a given turn
you have 4 cards in your hand - at the end of the turn, you will discard all but one card
and draw up to four. Cards shuffle through whenever the deck is depleted, but it is
possible for there not to be enough cards in the deck AND discard pile. Regardless, you
never get to draw cards that were used this turn (unless some effect specifies it). Cards
used during a turn either (a) stay on the board until their effect is complete or (b) go
to the discard pile for the current turn.

After each scenario, players gain one level - this generally means they get some passive
advantage, and some of their abilities gain additional effects.

### Board tactics

Moving out of the threatened squares of any given unit gives them a chance for an 'attack
of opportunity' (AoO) - they may spend their move action from *next* turn to perform any
'attack' ability they have available (including the always-available one all players share).
The "threatened squares" or "adjacent squares" are those which are within one kings-move
of the unit - having abilities that allow for more reach does not expand the threat region.
The opportunity is described as being 'provoked' - if somebody moves out of your threatened
region and you have no move actions remaining to spend, they have still 'provoked' an AoO
from you, you were just unable to use it.

When an attack is attempted against a unit, there are two quantities of relevance: the attack
bonus of the attack, and the defense of the target. The attack is usually stated like "attack +2",
which implies that the attack has a bonus of +2 - if your character has a built-in bonus, then
that also gets added on. A first level Warrior with 'Slash', for example gets a net bonus of
+2 - his character has an attack bonus of +1 with all attack cards, and the card itself has
an attack bonus of +1 at level 1. The attacker rolls the fudge dice, adds the net to his bonus,
and compares that value with the defense of his target - if the defense is lower, he hits; if
the defense is higher, he misses. If the defense is equal to the attack, then it is 'blocked' -
by default that means that no damage is dealt just like with a miss, but there are a lot of
cards and abilities that affect what happens when blocked or can be used when blocking.

A unit is 'flanked' if there are two enemies on exactly opposite sides of it, as in PF. Unlike
PF, 'flanked' is a status on the unit, and is true for any attack against it, not just for the
flanking characters.

### From the Overlord's perspective

The 'Overlord' is the player who controls the dungeon and tries to kill the heroes. He controls
all of the monsters each turn, and he gets to play one 'overlord' card per turn from his hand
of 4 cards (he draws to replace it at the end of his turn). The monsters all get to go first
each turn, and they can go in whatever order the overlord chooses. (The heroes can go in
whatever order they prefer as well).

The overlord is supposed to *try to win*. He is not a GM, he is an opponent. He is generally
expected to win about a third of the time - heroes must replay a given encounter until they win.

There should seldom be more than 6 monsters on the board at once - we don't want the overlord's
turn to take forever.

### Notation

In general, if you see two numbers separated by a slash, they represent an attack and defense bonus.
Two numbers separated by an '@' (at symbol) represent attack bonus and damage.
A "Full" action or attack costs a move AND a standard.
The types are: Action, Reaction, Attack, Cast

#### Status Conditions

* flanked: -1 to defense
* dazed: You lose and do not recharge 'move' actions while dazed.
* confused: -1 to resist, lose and do not recharge 'swift' actions.
* poisoned: At the start of your turn, roll. discard a card and an action at random if negative,
  discard this status if positive.
* aflame: At the start of your turn, roll. 1 damage if net-negative, discard if net-positive.
* stunned: Skip your next turn, then discard this status.
* blinded: All of your attacks and casts get -2. At the end of your turn, roll;
  discard this status unless net is negative.

