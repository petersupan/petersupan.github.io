# Peter Supan
## Personal projects
### Vincent in the ice caves
A rather simplistic 3D Shooter on the Gameboy advance with a completely self-written raycasting engine somewhere between Wolfenstein 3D and Doom.  
I made it out of curiosity if I could pull off a raycasting engine on the 16Mhz ARM3 Chip, without cache, without much graphics hardware support and without Operating System.

It can be downloaded from gamebrew.org:
https://www.gamebrew.org/wiki/Vincent_In_The_Ice_Caves_GBA

A youtuber made a video of it:
https://www.youtube.com/watch?v=niy8JLmbHFs

See [https://github.com/petersupan/svedishbox](https://github.com/petersupan/Raycaster/tree/main/VincentGBA)


### InstantFeedback Running
I was frustrated by the fact that there exist so many gadgets for running, which measure parameters related to running technique, but none of them gives immediate, actionable feedback. They all give averaged analytical data to look at after the run, which makes it hard to iterate.
So I decided to explore the possibilites to do this myself.
Goal was to provide feedback on one step in running fast enough so that adaptions could be made in the next step, either visually or acoustic.

### Swedish Box
A box which talks swedish words when pressing buttons. Very simple, I made it that my kids hear the swedish language before we moved to sweden. However, they learned a lot more with "Peppa Pig" (or Greta Gris, how it is called in swedish).
See https://github.com/petersupan/svedishbox

### VoxelGPU
I was always a big fan of the Comanche series games and later Ken Silvermans Voxel engines for terrain rendering (https://advsys.net/ken/voxlap.htm). I wanted to prove the claim wrong that these kinds of algorithms (2D-raycasting) are not suitable for GPUs.

I tested ways to parallelize these heightmap rendering engines  to make them run efficiently in compute shaders.

