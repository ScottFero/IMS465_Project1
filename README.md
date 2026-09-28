# IMS465_Project1

**Mechanic:**
A recreation of the Blade Barrage "Super" mechanic from _Destiny 2_, which involves the player "jumping" in the air and spawning several blade objects that fly away from the player.

**Architectural Showcase:**
An interface wasn't strictly necessary for my mechanic, nor was the use of delta time as the main movement portion of my mechanic was done through Unreal Engine's default physics system.

**Scope Adjustments:**
I originally wanted to have larger walking mechanics as part of my project, but I ended up just having the jumping and spawning of blades as they were the core pieces of the mechanic. I also added a check for what "Class" the player had equipped to make the system more modular in case I needed to expand it later. Given the lack of movement mechanics, I just had the player face one direction and only took input for the Super casting.
