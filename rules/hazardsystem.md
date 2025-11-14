# Hazard System (v0.3)

The six-sided hazard die deploys threats, manages resources such as light, and keeps time. It is the engine that drives gameplay forward, ensuring that choices have consequences while minimizing bookkeeping. To take a turn, have a player roll the hazard die and have the referee interpret the results relative to the current turn type. During a turn, each player may take one full action. The general form of the hazard die is:

|1|2|3|4|5|6|
|:-:|:-:|:-:|:-:|:-:|:-:|
|Setback|Fatigue|Expiration|Locality|Percept|Advantage|

## Hazard Die Interpretations

### Haven Turn Interpretation

|D6|RESULT|INTERPRETATION|
|:--|:--|:--|
|1|Setback|Encounter (use regional table) or disaster (see below)|
|2|Fatigue|Shortage (1 medicine, 2-3 drought, 4-5 famine, 6 trust)|
|3|Expiration|Clear one or more haven conditions|
|4|Locality|Advance season (or other local change)|
|5|Percept|Foreshadow looming disaster|
|6|Advantage|Full recovery|

### Wilderness Turn Interpretation

|D6|RESULT|INTERPRETATION|
|:--|:--|:--|
|1|Setback|Encounter (use regional table) or road/bridge out|
|2|Fatigue|Rest and consume rations (1/person) or suffer minor harm (1 HP)|
|3|Expiration|Expire transient wilderness condition|
|4|Locality|Shift weather (or other local change)|
|5|Percept|Spoor or clue regarding next encounter|
|6|Advantage|Free wilderness turn|

### Dungeon Turn Interpretation

|D6|RESULT|INTERPRETATION|
|:--|:--|:--|
|1|Setback|Encounter (use zone table)|
|2|Fatigue|Rest and consume rations (1/party) or suffer minor harm (1 HP)|
|3|Expiration|Expire transient dungeon conditions (light, spell, etc)|
|4|Locality|Shift dungeon state (or other local change)|
|5|Percept|Spoor or clue regarding next encounter|
|6|Advantage|Free dungeon turn|

### Combat Turn Interpretation

|D6|RESULT|INTERPRETATION|
|:--|:--|:--|
|1|Setback|Opponents act first or additional encounter (use zone table)|
|2|Fatigue|Suffer minor harm (1 HP) if engaged in melee|
|3|Expiration|Expire transient combat conditions (light, burning, etc)|
|4|Locality|Shift battlefield (or other local change)|
|5|Percept|Spoor or clue regarding next encounter|
|6|Advantage|Free combat turn|

- _Some disasters (1d6)_:  
    1 invasion, 2 insurrection, 3 fire, 4 earthquake, 5 flood, 6 falling star
- _Some dungeon localities (1d6)_:  
    1 obstruction, 2-3 seal/open door, 4-5 divert water, 6 expose secret
- _Use common sense_: ignore results that do not make fictional sense, but only the first time
- _Keep time abstract_: quantifying the details precisely is rarely worth the hassle

## Moves and Conditions

_Moves_ represent actions relevant to the current fictional context, such as exploring a trackless stretch of swamp. _Conditions_ represent persistence of a transient state, such as adventurer exhaustion. Conditions can apply to areas, parties, or individuals. Strictness tracking conditions is a matter of style. Tokens can help. The lists of moves and conditions below below are suggestive rather than complete. Improvise others as appropriate, according to referee ruling.

**Haven turns** represent several days or weeks of rest and recovery.

- _Free haven moves_: advance/level up, prepare spells, recover, recruit, resupply
- _Full haven moves_: craft gear, scribe scroll, conduct research
- _Haven conditions_: curse, famine, pestilence, shortage, siege, winter

**Wilderness turns** represent travel and making camp, approximately one day and night. Making a wilderness move requires consuming a ration or taking the exhausted condition in addition to rolling the hazard die. If already exhausted, at the start of a wilderness turn suffer minor harm (1 HP). Determine randomly whether setbacks occur during day or night.

- _Free wilderness moves_: access known landmark in current area, survey adjacent areas
- _Full wilderness moves_: travel to adjacent area, search, explore, hunt, track
- _Wilderness conditions_: exhausted, lost

_Lost_: Travel is no longer an option. Use search to locate a landmark, removing the lost condition on success.

**Dungeon turns** represent exploration at architectural scale, approximately tens of minutes or a few hours, assuming careful advance into hostile places.

- _Free dungeon moves_: look under a rug, open unstuck door, pull lever
- _Full dungeon moves_: climb, force a door, move to adjacent area, pick a lock, search
- _Dungeon conditions_: candlelight, torchlight, overburdened

**Combat turns** represent tactical actions occuring over seconds or minutes.

- _Free combat moves_: shout command, drop held item,
- _Full combat moves_: shoot, spell, strike, throw, withdraw
- _Combat conditions_: burning, defended, grappled, prone

## Notes and Further Reading

- Consider using a simple slot-based encumbrance system, such as one item per point of strength.
- Locality results work best if you design areas with countdowns or aspects that can shift between states.
- I replace traditional initiative with the combat hazard die.