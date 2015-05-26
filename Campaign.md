## Campaigns

This document describes the structure and implementation of a campaign. A campaign should
include 3 scenarios, each of which implements 2-5 encounters. The characters gain a level
between scenarios, and it is expected that the last encounter in a scenario should be
somewhat tougher than the rest.  Two campaigns are included: "Assault on the Black Citadel"
and "Escape from Ewain's Tomb"

"Assault" is a campaign for three Heroes, on their quest to find and rescue Princess
Tessa from her prison-tower during the Citadel Siege, and has many human enemies, including
lots of foes inspired by the Hero classes. It starts with some sneaky back-passage fighting,
with a lot of 'keep them from getting away' style objectives, and culminates in an assault
on the team of elite dark knights and cultists guarding the tower itself. The scenarios included
are named: "Sight Unseen", "To the Tower", and "From Darkness".

"Escape" is a campaign for two heroes, following their flight from the clutches of the
goblins infesting those dark ruins, and tracking their ascent through the massing army above.
It features a lot of "survive until" and "escape past" objectives, and includes many goblinoid,
undead, and monstrous enemies in poorly lit situations. The scenarios are named: "Out of the
Frying Pan", "Bones", and "Against All Odds".

### What is in an Encounter

1. A described objective. This might be "defeat all the monsters", "destroy
   the profane statue", "rescue the princess", "get the key and get back to
   the door", "survive 15 rounds", etc. What is important is that it is clear
   to the Heroes what they must do.
2. A map of the encounter zone - this probably includes 1-4 rooms, may include
   a choke point or so, some rough terrain and obstacles, and the placement points
   of any existing or pending enemies and objectives.
3. A card/sheet for each type of enemy, describing their HP/MP, defense/resistance,
   abilities, and passives.
4. A schedule - various events happen in response to certain triggers, like "on turn 4",
   "after there are less than three monsters left", or "when the boss dies". Typically
   these trigger the spawn of more monsters to fight or flee from, but sometimes they
   have some other effect, like a door becoming unlocked, or a magical effect reducing
   all units' attack bonus by 1.

### Between Encounters

After each encounter, all lingering statuses and conditions are cleared, HP and MP are filled,
play decks are reshuffled, and everything starts fresh. If the heroes have lost a given encounter
at least three times in a row, all heroes may swap out 4 cards from their play decks to try
to address whatever keeps killing them.

### Beyond Level Four

While the initial game contains rules only up to level four, which leaves room for only three
scenarios per campaign, there are two ways to build a longer campaign. You might have them play
through multiple scenarios before gaining each level to build a longer campaign that still fits
in levels 1-4.

Alternately, you can buy the soon-to-be-released expansion, Epic Fray - this adds
replacement cards for all abilities to allow their power to continue expanding through
level 8 and Overlord cards with increased power, and comes with campaigns for levels 5-8.
It also introduces 2 new classes, the Paladin and the Magus.

(FIXME: Write expansion)
