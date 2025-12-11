# 1 Game, 1 Engine

This project is a ground-up 2D game engine built in C, powered by SDL2 and a persistent desire to understand what actually happens under the hood—because sometimes you just want fewer black boxes and more raw control.

The engine walks through the essentials: opening windows, drawing quads, pushing pixels through shaders, handling input, running physics, resolving collisions, juggling entities, animating sprites, layering systems, and eventually spawning enemies that absolutely didn’t read the design doc.

Every subsystem is intentionally small, transparent, and hackable. No frameworks, no magic—just well-aimed C and a focus on learning how a real engine thinks.

### What You’ll Find Inside

* A dead-simple rendering pipeline that doesn’t fight you
* Collision detection that behaves (unless you do something creatively illegal)
* A growing entity system that scales surprisingly well for something this handmade
* Audio, animation, levels, and enough modularity to build the game *you* want
* Plenty of opportunities to say “okay, **now** I get how engines actually work”

### Why This Exists

Because building engines from scratch is equal parts pain and enlightenment. Writing your own lets you understand the rules well enough to break them later.

Dive in, break things, fix them, break them differently, and come out the other side with a deeper understanding of game engine guts.
