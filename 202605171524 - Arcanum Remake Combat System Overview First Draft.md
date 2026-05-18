---
aliases:
created: 2026-05-17T15:24:00
tags:
  - arcanum/combat
---
Links: [[Arcanum of Steamworks and Magick Obscura (2001)|Arcanum: of Steamworks and Magick Obscura (2001)]]

___

==comments look like this==
### Combat
#### Overview

Combat is one of the areas where the original *Arcanum* most obviously struggles. Fights are short and unpredictable, victory mostly coming down to a simple stat check, magick and tech are indistinguishable mechanically your companions act on their own accord, mostly choosing to rush down enemies, often to disastrous results. As a whole, it bears a striking resemblance to *Ultima VII: The Black Gate* of all things, a game released almost a decade earlier, similarly criticized for a lack of interactivity and discernability in *its* rudimentary combat systems.

ARCANUM REMADE will aim to capture the *spirit* and *intent* of the original's combat, choosing to build it from scratch, aiming to make encounters both mechanically interesting and straightforwardly *fun*. With a focus on problem-solving and player agency, the new combat system will aim to more thoroughly integrate into the simulation of Arcanum's world, fostering emergent gameplay scenarios that reward player creativity and experimentation.

More concretely, combat will be carried out in a turn-based, tactical format, reminiscent of *XCOM 2*, *Vandal Hearts*, or the *Final Fantasy Tactics* series. Combat will take place directly on the world map in hand-crafted arenas that provide numerous ways to take on enemies depending on how you've built your character, turning combat into a more overt puzzle where players must carefully balance their numeric resources like health, magick, and turns with terrain, positional advantages, and specific tech-magick match-ups.

Combat encounters will, from the player's perspective, occur almost anywhere, be it in fetid swamps, dank caves, or bustling city streets. In reality though, combat will be scripted and sequestered to specific areas designated as "combat arenas", whose sole purpose is to provide an engaging space for players to interact with the game's combat mechanics. However, these arenas and whether combat actually ends up occurring in them will depend on player actions, creating a diverse experience and fostering replayability. 

To show more concretely what battles look like, let's take a closer look at the flow of standard battle:
#### How a standard combat encounter looks
##### The player's turn

The player is shown a wide view of the area naturally designated as the "battlefield", highlighting enemies and potential items of interest or secondary objectives. A traditional turn order display will denote the order that combatants will act in, changing to reflect temporary stat changes and status ailments.

During their turn, players can choose to take one of four actions:
1. **Move**
	Lets the player move a certain number of units, variable depending on skills, perks, status, or terrain
2. **Attack**
	Prompts the player to contextually use their main weapon, reactive depending on the exact nature of the weapon; e.g. firearms allow precise aiming or reloading, explosives highlight an area-of-effect and show an arc for throwing, staffs allow contextual selection of spells
3. **Item**
	Allows usage of items from the player's inventory. Usable items will be limited as little as possible to allow maximum player expression and engender immersive and emergent gameplay situations
4. **Fate**
	Use Fate Points to change the tides of battle, often to unpredictable and dynamic results

Depending on their scale and impact, actions take a different amount of resources, be it magick, health, or even turns. 
For example:
- Firearms can act quickly, attacking enemies from long distances without much preparation, but may miss small or mobile enemies and require occasional down-time to reload
- Magick tends to shorter ranges, with cast times varying on the "power" of the spell. Lower level magick attacks can be cast fast, and offer instant effects, while higher level spells might require multiple turns to prepare or have delayed effects that need to strategist around 
- Melee weapons are straightforward and effective, yielding immediate and tangible results at a fixed, short range, while also allowing potential interaction with the environment (cutting down chandeliers, bridges, trees)

Players choose their actions individually for their own character, *and* each of their companions, instead of them acting on their own. This lets players more actively play around their party's individual strengths and weaknesses, additionally informed by the terrain and enemy types.

Additionally, players can choose to undo any move made before choosing to advance to the enemies' turn, allowing a degree of planning and experimentation in-game before committing to a single plan of action and aiming to avoid player frustration over "just missing" a better action.

When the player is ready and has chosen an appropriate action for all of their party members, they may choose to confirm and execute their actions, watching them unfold in order. When all player actions are finished, the enemy party's turn begins.
##### The enemies' turn

Enemies act governed by the same rules as the player, their actions dependant on their specific abilities and builds, but generally being similar to the player's. Most importantly, enemies are **not** given any affordances or advantages that are not likewise given to the player. To put it simply, enemies play fair, according to the rules and systems of combat, as the player does.

==fine section, needs to be somewhere, but that place might not be *here*==
Challenge in combat instead stems from a variety of interoperating factors:
- Enemy abilities and builds
	Most directly, the difference between magick and tech, the precise methods that the enemy can utilize to act in combat. In this way, enemies are also differentiated based on their relative strength or weakness; e.g. a large number of weak grunts or a single skilled and well-armed technician
- Rock-paper-scissors relationships
	Certain weapon types or classes act as natural foils to others, requiring an additional level of consideration; e.g. powerful sorcerers that take multiple turns to execute spells may be disrupted by nimble gunslingers, summoners or mechanists might be devastated by area-of-effect attacks, sorcerers focusing on traps may find themselves outmaneuvered by thieves. Players must take these relationships into account and arrange their party in a way that minimizes their weaknesses while striking at the cracks in the enemies' own formation
- Positioning
	Enemies may find themselves in a more advantageous position at the start of combat, requiring careful positioning and strategy to prevail
- Attrition
	Having to hold out against superior numbers or enemy reinforcements, starting battles one after another, or during a low-point in the story

As is customary in turn-based tactical games, players cannot act during enemy turns (barring exceedingly rare exceptions), merely observing their actions and preparing for their next turn. That is to say, enemy actions must be preempted and played around strategically, like a game of *Chess* or *Go*.

In this section, we placed a great deal of importance on the asymmetry of combat encounters through build variety and uniqueness. This is an area that is perhaps overstated in the original Arcanum, the lines between different factions and weapon types blurred into a homogeneous paste of real-time combat. With this being the original's implementation, it begs the question, in ARCANUM REMADE...
#### What is the practical difference between tech and magick?

A core pillar of Arcanum's world, the divide between *tech* and *magick*, *technicians* and *sorcerers*, *new* and *old*, is the driving force behind the fantasy that the it seeks to portray. A clear, mechanical, *tangible* and *measurable* divide is necessary to maintain ludonarrative harmony. The first, and most obvious of these differences is of course...

- **Aesthetic**
==very subjective, more argumentative than professional==
While some designers choose to interpret aesthetic as an entirely separate pillar, unrelated and opposed to the goals and tenets of systemic and mechanical design, I personally do not make such a distinction. Aesthetics support mechanics, which in turn support the setting and the overall player fantasy. How a mechanic *feels* is often just as, if not *more* important than what it means in a systemic context. Let us never forget *Metal Gear Rising: Revengeance*, a simple hack-and-slash video game that turns mashing a single button into a monumental and deeply satisfying event of city-razing proportions.

*Satisfying* is the keyword here; ARCANUM REMADE will strive to make each attack *feel* good for players. Sharp hit sounds, screen shake, blood spatter, smoke rising from barrels, charred remains left behind in the wake of a terrible fireball... It might sound crude, but in a game in which player interactivity is mainly achieved through combat mechanics— i.e. *violence*—unless the game is trying to make a specific statement, players should wholeheartedly enjoy the act of cold-blooded murder.

That being said, aesthetics still *is* only one part of the equation; in a successful combat system, magick and tech should also have...

-  **Measurable mechanical difference**
That is to say, magick and tech should be different in the way that they interact with the the core gameplay systems, offering visibly distinct playstyles and providing unique strengths and weaknesses in combat. We touched on some examples in the previous section, but as one of the main pillars of combat design, this aspect warrants further, detailed discussion.

Technology has its preparation time front-loaded and compressed. Loading a gun, building bombs, creating machines, all of these generally take place *before* battle (barring exceptions); as such, technicians enjoy the privilege of nigh instant actions in combat. 

Gun-slinging technicians can take on the role of flankers or the vanguard of the party, supporting and protecting their allies with covering fire; Wind-Up Mechanists can send hordes of constructs to disrupt enemies; Cannoneers turn people into people-shaped flesh chunks. 

As a consequence of this, however, technicians have to manage their supplies carefully and are practically defenseless during their "reloading" phase, leaving them vulnerable to well-timed or delayed attacks.

Meanwhile, mages can take much longer to affect the battlefield, preparing spells and potions on the fly, or casting delayed trap spells that influence combat over a period of multiple turns.