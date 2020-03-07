---
permalink: /help/
title: "DM's Guide to Construct"
toc: true
author_profile: false
---

Let Construct help you run awesome sessions effortlessly. 

# Workflow
In order to figure out how Construct fits into your workflow, we'll explain the workflow that was kept in mind during development.

We'll describe the way Construct can be used for planned encounters as well as random encounters.

## Planned encounters
While preparing a session, you can use Construct to plan your encounters and make sure everything is ready to go when they happen.

1. [Add](#adding-a-creature) your player character's to the compendium
2. Create a party that contains the player characters
3. Add important NPCs to the compendium 
4. [Build your encounters](#building-an-encounter)

When a random encounter happens during the session, follow these steps:

1. Open the encounter
2. Start running the encounter
3. Add the party to the encounter
4. Let Construct roll monster [initiative](#initiative) & enter PC initiative

## Random encounters
When a random encounter happens, you'll want to get the PCs and the monsters they're facing together into an encounter in Construct as quickly as possible. Use the **Scratch pad** encounter for this. It's a default encounter meant to be used over and over again.

Add the monsters and PCs to the encounter and press "run". Once you're done, you can use the special "Reset" button and remove only the monsters from the encounter. The PCs remain, ready for the next random encounter. For more info, see [building an encounter](#building-an-encounter).

# Adventure
In Construct's "Adventure" tab, you can create encounters and organize them in groups. Groups can be used to arrange encounters that belong to a single session, adventure or campaign.

> Tip: Long press on a group or encounter for more options such as rename and move.

## Building an encounter
Begin by tapping the "New encounter" button in the "Adventure" tab. After entering a name, add one or more combatants to the encounter. A combatant is either a monster or character from the compendium or one you create on the fly specifically for this encounter.

You can add combatants by tapping the plus icon on the monster, character or party list views. Monsters can be added multiple times from their detail view.

While adding or removing combatants, the difficulty bar will update automatically. It automatically uses the PCs in the encounter to calculate the difficulty, falling back to simple party compositions (e.g. "three level two characters") if there are none. The difficulty is calculated according to the DMG.

## Running an encounter
When you run an encounter, Construct makes a copy of the encounter just for that run. Any changes you make to the encounter (e.g. adding PCs, other monsters or changes to health and tags) while running are made in that copy. If you end the run, you'll find the original encounter untouched. It's ready to be run again the way you initially set it up. Instead of running it from the start, you can also choose to resume any previous runs.

You can remove old runs from the encounter's setting screen.

### Initiative
As you start to run an encounter, tap the "Roll initiative" button in the bottom bar. By default, Construct assumes you want to roll initiative for all DM controlled combatants and it'll group similar creatures into the same initiative. Then tap the initiative label to the right of each player controlled combatant to enter what your players rolled. You can do this at any time you want to (re-)roll initiative for a specific combatant.

You can re-roll initiative in batch by tapping the ellipsis button in the bottom bar and choosing "Re-roll initiative...".

### Turns
Once initiative has been rolled, tap "Start" to start round 1 with the combatant that rolled highest for initiative. The active combatant is displayed in the left side of the bottom bar and its initiative is marked with a green circle. Combatants on the same initiative order as the active combatant are marked with a dim green circle.

Only combatants with initiative have turns.

### Combatants
Each combatant row on the encounter screen has multiple functions:
- Tap on the hp (left) to hit or heal
- Tap on the name to open its detail screen.
- Tap on the initiative (right) to (re-)roll initiative 

On a combatant detail screen, you can look at its stats, manage tags and limited resources. Combatants that were created for this encounter can be edited here. If the combatant was added from the Compendium, it needs to be edited there.

> Tip: Tap the Edit button in the top right corner of the encounter screen to select multiple encounters and perform batch operations such as hp changes and adding or removing tags.

#### Tags

Tags can be used to indicate combatant conditions, tactical status, spell effects and more.

> Tip: When adding a new tag, tap on its name to add an additional note, e.g. the DC of a hidden creature.

#### Limited resources
Track spell slots, recharching abilities and X per day features. Construct is able to auto-create trackers for common resources, but you can also add custom ones.

# Compendium
## Import
If you use [Improved Initiative](https://www.improved-initiative.com) and have created files with compendium content for it, you can import those into Construct.

## Adding a creature
Construct is not a full-fledged character or monster builder. It focusses on the information that is most relevant during combat.

A creature can be created with nothing more than its name. It can be increasingly useful when augmented with hp, AC, abilities and more.

## Creating NPC's
Construct allows you to create NPCs from monster stats. Go to the monster in the Compendium tab, press the ellipsis in the top right corner and select "Save as NPC". Construct will copy the monster to the Character section. There you can edit the NPCs name and some of its stats.

If you want to quickly create a NPC that is not based on a monster, go to the Characters section in the Compendium tab and tap the "Add character" button at the bottom of the screen. Enter a name, all other stats are optional.
