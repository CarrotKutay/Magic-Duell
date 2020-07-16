# Magic-Duell
Another experimental game development project, looking into the possibility of cerating a magical spell duell battle game

Inspiration goes to this awsome strategic real time battle rpg called [Super-Spell-Heroes](https://www.superspellheroes.com/).
The idea behind this game is to match element blocks as 'building blocks' together with a mathing elemental spell. 
Depending on how many building blocks a player adds together the spell cast will be stronger.

![Picture of in-game gameplay](/documentation/Super-Spell-Heroes-1.jpg)

### Gameplay Super Spell Heroes
The game itself is only available for mobile plattforms. It revolves around a simple progression system from one region to the next and by unlocking new regions new heroes can be unlocked as well. Different heroes have preset elements and spells that are available to their disposal:
- 2 elements per Hero
- each element contains a variety of different spells
- different heroes can have the same elements with the same spells as other hereos

Progression between different regions are done by duelling against different players. One battle is always only against one opponent and for each the player chosses different kind of spells to iniclude for it:
- 3 common spells
- 3 uncommen spells
- 2 rare spells
- 1 ultimate spell

These spells become more efficient depending on what kind of grade they are (e.g. a shield-spell of rare quality will have stronger base values as a common shield-spell). Therefore, a higher tier spell with less elements added to its buildpath can potentially still be stronger then for lower tier spell.
Higher spell tiers are unlocked after casting a certain amount up-to-now available tier spells.

#### User Inteface / User Controls
The Game super spell heroes is strictly 2D, which might be a expression of the plattform it was/is developed for (mobile). Controls are stricly tap-oriented.

# Game idea for Magic-Duell 

#### Competitive real time battle 
A battle between minimum 2 players, with the potential of wielding different spells. Spells can build by players on the fly and dieffernt build path result in the spells taking effect differently (maybe with different effects or/and with stronger and lesser efficiency depending on said build path)

Battle arena should be rather stoic itself, focus soley on the spell building for each player. Spell building path should be difficult and challenging, but the bar into spell building should not be to difficult, to make it easier for new players to adapt.

First arena draft could look like the follwong:
![arena draft](/first_arena_draft.png)

Suggestion to use a 3D-Plattfrom inside the game for the battle. This is however not needed, as the players themselves will not move as much, main focus should be thrown into spell casting + building. Movement of the player themselves could be an option, but not needed for casting the spells, avoiding spells casted by other players through movement could be a feature, but would not make much sense in a mobile rpg when looking at user controls as it might overload the the ones available and make for a bad user experience.
