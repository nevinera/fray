## Developer Notes

### Ability Balance

Some ability cards are intended to be situationally powerful, but powerful cards should
always be situational - if a player is using a given attack every chance he gets, that
probably means it is unbalanced. Likewise, if a card rarely gets played at all, it may
be *too* situational, or not powerful enough.

We can compensate for overly situational abilities by giving them broader applicability,
but not by making them more effective non-situationally; the latter leaves them either in
the same boat as before, or overpowered.

### Character Balance

There are definitely distinct tactical roles present in this game, and some classes do not
function well without those roles being filled - a two player group of a Wizard and a Rogue
would flounder in situations with many melee enemies, while a Warrior/Cleric group would be
unable to fight their way through some encounters *fast* enough.

These are not a balance concern - it is expected that the players pick heroes that can form a
viable party. However, if a class is being under-used because other classes can fill the same
roles, but more flexibly or more effectively, then we need to fix it. It's also important to
track how dependent a class *is* on party makeup - if the wizard can only really be useful in
a four-person group, then we need to fix it with more teleporting and crowd-control. If the
Cleric can't function without a tank to stand behind, then they need to be able to fill the
tank role themselves to some degree.

Card-choice allows us to offer varied builds for a class - we should note what the different
intended directions for a class to be taken are, so that we can tell if any of those directions
turns out to be never viable.

### Combat Bonuses

There are essentially two types of attacks, physical and spell. It is intended that physical
characters handle physical attacks better and caster characters handle spell attacks better,
but we don't want the to be terribly unbalanced - on average, a physical character should have
1 higher defense than resist, and vice versa for casters.

We want attacks to succeed more often than they fail, so the net bonus on attacks should generally
be around one higher than the defense bonus of the character making the attack (likewise for
casters and resist). The 'always available' attack/cast on the other hand should generally clock
in at the same as the defense/resist of the character using it, so that blocks and misses are a
bit more likely then hits.

### Statuses and Conditions

We do NOT want tracking statuses and conditions to be a lot of effort. There are cards that
represent those conditions, that are placed on top of the unit under the status effect. Boss-
like monsters, which are intended to be functionally powerful relative to a whole group, should
always have some way to reduce the impact of statuses and conditions - forcing rerolls, using
actions to discard statuses, etc. Otherwise a team with lots of stuns and dazes can stun-kite a
boss around without taking any damage. Many monsters are immune to various specific statuses
(undead cannot be dazed or confused for example); make sure to give bosses a lot of immunities!

### Buying Time

We have to be careful with how longer-term resources (hp and mana) recharge. If players can
regain health or mana, they are incentivized to buy time for that to happen by playing chase
games - that's no fun. Limit regen capabilities by requiring characters to spend a move or full
action, or remain in one spot, or engage in melee; don't make the players (or monsters!) play
hide and seek.
