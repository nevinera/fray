## Gameplay

Fray is played on a 1-inch gridded battlemat, with minis or tokens to represent the characters.
Each hero has a deck of cards to play with (their "play deck"), and the Overlord has a deck of
20 cards called the "overlord deck". Combat takes place on this grid, in a location drawn in
wet-erase marker for each encounter - there is no exploring, role-playing, or investigation,
only endless waves of interesting monsters to kill and objectives to accomplish.

### Play Deck

A hero's play deck is composed of 12 cards, selected from the 20 cards available to each
character. After each scenario, every player may swap out *one* of their chosen cards to a
card not currently in their play deck. Every card in a play deck has a `type` and a `cost` - the
types are "aid", "action", "attack", and "cast", and the costs are "swift", "move", "standard",
and "full".

Each character also has three action resources that refill each turn: a swift action, a move
action, and a standard action. At the end of your turn, you refill those resources (unless
some status or card tells you not to); you can lose them before your turn if you're unlucky.

When your play deck runs out, you shuffle your discard pile and it becomes your play deck. Note
that cards do not go into your discard pile from the current turn until *after* you refill your
hand - this ensures that you cannot use the same ability card two turns in a row.

### Anatomy of a Round

A round of play can be broken down like this:

* Overlord Phase
  - each monster's turn (in any order)
    * Use resources to perform attacks and actions, and move around
    * Refill resources
  - play an event card from the overlord deck
* Hero Phase
  - each hero's turn (in any order)
    * Use resources to perform attacks and actions, and move around
    * Discard down to one ability card.
    * Refill resources and ability cards
    * Place used and expired cards into the discard pile

### At a Larger Scale

The heroes and overlord are playing through a `campaign`, which is a series of 3 scenarios,
each including 2-4 encounters. Every encounter is described using a map; the details of the
encounters are *not* secret, and can be studied by anyone at the table. The heroes will retry
each encounter until they defeat it; at the end of the campaign, the overlord's score is how
many times he killed the entire party (and that should be his goal - he is no GM).

After each scenario is completed, the heroes gain a level - they each gain 2 hp, some passive
benefits as described on their character, and every one of the skills in their play deck becomes
more powerful or flexible in some way. The monsters they encounter in the next dungeon will be
harder and tougher as well of course. In addition, each hero may swap out one skill that they
didn't find as useful as expected.

There are also a rare few pieces of equipment - these are cards that grant passive benefits to
the hero holding them, or consumeable items that are discarded when they grant their effect.
Equipment is kept permanently, except that each hero may only carry one artifact and one
consumable at a time - a hero may pass an item to an adjacent hero as a swift action, or drop
it (destroying it permanently) for free.

### Using Abilities

Each hero and monster has some abilities inscribed on their character card - these abilities
are always available. The four ability cards in your hand should generally be more powerful and
more specific - these represent attacks and actions you might take. In order to use an ability,
whether it is on your character or in your hand, you have to pay its *cost* - a "swift attack"
for example costs one swift action, and a "full action" costs a move and a standard action.
You can spend any action as a smaller action if you choose to, and if something allows you to
use a "standard attack", you could use a "swift attack" or "move attack" instead. Using an ability
from your hand *always* spends that ability card as well as its resource cost - it should never
be possible to use the same ability card two turns in a row.

Some abilities have an additional mana cost - mana is a separate resource that is regained over
time (depending on the class) - typically it can be spent in large quantities to allow for
powerful effects, but cannot be gained rapidly enough to be used that way every turn. Classes
gain mana in different ways - Wizards gain MP at the start of their turn for example, while a
Magus gains MP by landing physical attacks against enemies, and a Cleric spends actions to gain
MP by praying to a divinity. Mystical abilities are of type 'cast' or 'aid', while physical
abilities have the types 'action' or 'attack'.

### Tactics

Combat takes place on a grid - the environment is drawn on with wet-erase marker, and in-room
obstacles that are lower than head-height are drawn in a different color, while difficult
terrain is drawn in a third.

When an attack or cast is rolled, the owner of the ability rolls the fudge dice and adds their
bonus. If the result is higher than the defense/resist of the target, then the attack/cast is
successful; if it is lower, the attack/cast has missed. If the two numbers are equal, then the
attack/cast is 'blocked' - by default, blocked abilities do no damage, just like misses.

Movement (and distance) is measured in 'spaces' - the distance from A to B is the number of
spaces through which a character would have to pass to move from A to B. Every second diagonal
move costs an extra space. Line of Sight is required for nearly all ranged abilities - two
characters have line-of-sight if you can draw a straight line from *any* point in one character's
space to *any* point in the other's space. Moving from a rough-terrain space costs one extra
space of movement.

A character A has 'cover' from character B if any of the lines from any corner of B's space
to any corner of A's space *cross* a wall, raised obstacle, or another character. Cover provides
an additional +1 defense/resistance bonus against ranged attacks and casts.

A character is 'flanked' if there are two enemy units positioned on exactly opposite sides of him.
Flanked characters get -1 to defense against everybody, not just the flankers.

The "threatened region" of character A includes all of the spaces within distance 1 of them.
An "Attack of Opportunity" is provoked whenever a unit in the threatened region of an opponent
attempts to move, stand up (from being prone), or use a 'cast' or 'aid' ability. When an AoO is
provoked from a given character, that character has an opportunity to immediately spend a move
action to perform a *standard* attack against the provoking unit.

#### Conditions - unspecified durations

* flanked: -1 to defense
* dazed: lose and do not recharge 'move' actions.
* confused: -1 to resist, lose and do not recharge 'swift' actions.

#### Statuses - self-limiting durations
* poisoned: At the start of your turn, roll. Discard a card and an action at random if negative,
  discard this status if positive. (Monsters gain 'confused' while poisoned, instead of discarding
  cards).
* aflame/bleeding: At the start of your turn, roll. 1 damage if net-negative, discard this status
  if net-positive.
* stunned: Skip your next turn, then discard this status. You have 0 defense and resist until then,
  and you count as flanked.
* blinded: All ofy our attacks and casts get -2. At the end of your turn, roll;
  discard this status unless net-negative
* prone: remain prone until you can spend a move action to stand up. You count as flanked, and
  cannot attack. Standing up provokes an AoO (while still prone) from anyone threatening you.
* regen: At the start of your turn, regain 1 hp and then roll. Discard this status unless positive
