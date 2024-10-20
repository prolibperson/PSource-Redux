## PSource-Redux

Compile this in Release x64

## Credits:
Jetman, for the quest fixes, the gamemodes and the original source.
Lotus, for your guidance, support and fixes.
Gunblade, SecretsOfThePast, Nayr438, for work on the original source.

# (Fixes)
Quest AI Fixes And Improvements, 
Ammo Bar Fix (wasnt relative to Resolution, and Jetman also used the wrong values), 
Medkit Fix (logic error by jetman made them unable to get picked up after respawn), 
Sword Reload Fix (added an additional isReloadable check in the function for reload anim), 
Damage Counter Fix (counts both HP and AP damage), 
Duel Tournament Fix (fixed an iterator memory leak)

# (Features)
Cleanup Of A Ton Of Stuff (UI, Unfinished Achievement and Mailing System, Etc), 
C++17 Support, 
O2 Compiler Optimizations, 
Support for unpacked MRSes (Toggle in GlobalConstants.h), 
Got rid of the broken "Render_Update" and "Render_Frame" FPS Limiter seperation

shoutout to ini because without her there wouldnt be any ini files in this world
