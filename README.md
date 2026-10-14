# A Table For Four

**A grid-tactics game about a kitchen robot with a shopping list, in a world
that ended a long time ago. Only the robot hasn't noticed.**

<p align="center">
  <img src="media/gameplay/hero.gif" width="720" alt="Vex fighting through the roaches at the supermarket's front door">
</p>

Vex wakes up under the cereal in aisle seven with a handwritten grocery list
and one job: get everything on it, and cook dinner for the family. The
supermarket is overgrown and the wildlife has mutated. Vex treats all of it
as an unusually difficult shopping trip. The robots who join along the way
know exactly what happened to the world, and they've decided not to say.

On every turn you draw a **path** for each robot across the board. The tiles
are the action: red tiles attack, green ones gather, purple ones defend. The
longer the path, the bigger the result. Then the enemies take their turn.

> This repository is the public window onto a game in active development.
> The game's source is private. What's here is the work as it happens:
> gameplay, art, and a log of every build.

---

## Latest builds

Filled in automatically on every push to the game. The full history is in the
**[build log](BUILDLOG.md)**.

<!-- buildlog:latest:start -->
- 2026-10-14 `build 356` · **Art**: decoration *park* (fountain, oak), new unit *baked potato*, new unit *bucket*, new unit *ember hive*, new unit *potato bed*, new unit *snapper*, +6 more · **Levels**: chapter 2, level index, sandbox · **Engine** · **Rules** · **Testing** · **Art pipeline** · **Design notes**: abilities & UI mockups — 10 commits
- 2026-10-13 `build 352` · **Art**: decoration *park* (fountain), new unit *baked potato*, new unit *bucket*, new unit *ember hive*, new unit *potato bed*, new unit *snapper*, +6 more · **Art pipeline** · **Design notes** — 3 commits
- 2026-10-13 `build 349` · **Art**: decoration *park* (compost, hedge, railings, raisedbed), effects, interface art, new unit *ember beetle* · **Engine** · **Rules** · **Story** · **Testing** · **Art pipeline** · **Design notes**: abilities & UI mockups · **Site** — 20 commits
- 2026-10-12 `build 329` · **Engine** · **Rules** · **Art pipeline** · **Design notes** — 4 commits
- 2026-10-11 `build 325` · **Art**: effects, new unit *fire*, story stills, terrain tiles · **Levels**: chapter 2, level index · **Engine** · **Rules** · **Story** · **Testing** · **Art pipeline** · **Design notes** — 19 commits
<!-- buildlog:latest:end -->

## Devlog

| | |
|---|---|
| 2026-10-13 | **[Seven weeks in](devlog/2026-10-13-seven-weeks-in.md)**: from a grid of coloured squares to a rendered campaign |

---

## Seven weeks, one board

The same 8×8 test board, captured from the game as it stood at the end of
each day of work.

<p align="center">
  <img src="media/timeline/timelapse.gif" width="800" alt="The test board at the end of each day of development, from flat squares to rendered 3D">
</p>

| 24 Aug | 27 Aug | 1 Oct | 13 Oct |
|---|---|---|---|
| ![](media/timeline/2026-08-24.jpg) | ![](media/timeline/2026-08-27.jpg) | ![](media/timeline/2026-10-01.jpg) | ![](media/timeline/2026-10-13.jpg) |

## The cast

Every unit is a 3D model rendered from 8 directions, with idle, walk, attack and
death animations. Each one here plays its idle, walks a full turn, then
attacks.

| Vex | Kade | Bram |
|:---:|:---:|:---:|
| ![Vex](media/units/vex.gif) | ![Kade](media/units/kade.gif) | ![Bram](media/units/bram.gif) |
| Kitchen robot. Proper, precise, and always pays. | Garden robot. Keeps living things alive. | The supermarket's front door. *"After you."* |

| Cockroach | Tick | Ember beetle | Tuber |
|:---:|:---:|:---:|:---:|
| ![Cockroach](media/units/cockroach.gif) | ![Tick](media/units/tick.gif) | ![Ember beetle](media/units/ember_beetle.gif) | ![Tuber](media/units/tuber.gif) |
| *"Not on the list. High protein, though."* | Arrives in chapter 1, along with poison. | Chapter 2. The park is burning. | Chapter 2. Potatoes, and they run. |

## Gameplay

Six levels, each played for three rounds by a script rather than a person, so
the moves are random. The clips show the systems, not good play. Click one to
watch the full round.

| | |
|:---:|:---:|
| [![Baking Aisle](media/gameplay/t2.gif)](media/gameplay/t2.mp4) | [![Checkout](media/gameplay/t3.gif)](media/gameplay/t3.mp4) |
| **1·2 Baking Aisle**: planks from broken shelving, and a clock | **1·3 Checkout**: nails, and a bill Vex insists on paying |
| [![Mind the Gap](media/gameplay/t4.gif)](media/gameplay/t4.mp4) | [![Customer Service](media/gameplay/t5.gif)](media/gameplay/t5.mp4) |
| **1·4 Mind the Gap**: salt, a floor full of holes, and poison | **1·5 Customer Service**: *"Eight of them, and they are not queuing."* |
| [![The Front Door](media/gameplay/t6.gif)](media/gameplay/t6.mp4) | [![The Old Oak](media/gameplay/p6.gif)](media/gameplay/p6.mp4) |
| **1·6 The Front Door**: the rescue. Bram has been holding up the ceiling | **2·6 The Old Oak** *(first draft)*: a hive in the oak keeps starting fires |

## Story stills

Each level opens and closes on a still. These are chapter 1, *the supermarket*.

![Chapter 1 stills](media/stills/chapter1_sheet.jpg)

---

## Status

A playable design probe. Chapter 1 (the supermarket, six levels) is built and
illustrated. Chapter 2 (the park, seven levels) is in its first draft. Ability
trees are being designed now.

## Rights

© 2026 Marco Battiato. All rights reserved. The images, video and text in this
repository are shown for viewing only. They aren't licensed for reuse.
