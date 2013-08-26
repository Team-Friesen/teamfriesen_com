---
title: armature solution
date: 2013-08-26 16:49:00 UTC
tags: rigging, animation
---

Another weekend has passed. We didn't work much on the game. Yay! Chris got a new game (Hammerwatch) which he and Jake played nearly non-stop all weekend. This was quite refreshing for me, as I got to watch and get some happy knitting time in. Now, we did get some game stuff done, though...

So, I ended my week being very frustrated with rigging exporting/importing. Nothing seemed to work. Well, I found a solution... although we still haven't successfully imported the animations and had a character fully animated in the engine. Poo for that part... but my rig is fine, I do believe.

The solution. Rigify's features are so exciting and easy to use, and yet, adds too much complication for exporting to a game. So, I decided to use the original simple rigify human-rig. Using this, I duplicate it in object mode. I now have 2 completely seperate rigs. I renamed them 'def_rig' and 'ani_rig' respectively. Now, I can add IK constraints and specialty parts to the ani_rig while keeping the important bones named the same as the def_rig. This means that I can bake any actions I create, and then just apply them to the def_rig. That means no more 'too many bones' errors when exporting since there is only the 61 bones of the basic rig.

I plan on adding to my ani_rig so that it's even easier to animate... but for now, I can get some basic walk cycles and such finished so that Chris can play in the engine.

![armature setup/ani-left def-right](/files/armature_solution.png)

ani_rig - left / def_rig - right
