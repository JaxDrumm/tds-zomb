
## A small project by Jackson Drummond.

###### Changelog

###### Version 0.421 - October 24th, 2018
+ Fixed bug with tiles being invisible in the editor.

###### Version 0.42 - October 24th, 2018
+ Mostly finished building editor. Instructions below on how to use it.
- The web demo is either outdated or broken as of now.

###### Version 0.41 - October 19th, 2018
+ Rescaled Stats/Time HUD elements.
+ Rewrote how the command console interprets commands.
+ Added "play_ambient" command.
+ Game begins at 11:00 AM now.
+ Firepit now draws properly.
+ Added texture overlay shader effect to firepit.
+ Added new ambient noise (ambRadio2).
+ Sorted Ambient sounds into their own audio group.
+ Rewrote the audio group loading screen.
+ Clarified audio group loading screen.
+ Reanimated all player sprites for weapons to share a common resting position.
+ Stats drain slower.
+ Stats now round up (ceil) instead of rounding to the nearest integer (standard).
+ Time goes by slower.
+ Rewrote gamepad movement. Should now be fully functional.
+ Fixed a bug where the resource counter would have an incorrectly sized rectangle border.
+ Player now starts with 5 wooden planks.
+ Begun work on a building editor for procedurally placed buildings.

###### Version 0.407 - October 18th, 2018
+ Rewrote resource counter entirely.
+ Gave crates more health.
+ Linear interpolation speed of Crate health bar is now faster.
+ (Hidden)

###### Version 0.406 - October 17th, 2018
+ Added explosion object. Does not appear in standard gameplay as of yet.
+ Made debug outlines blink.
+ Added "window_size" command. (Only applicable on Windows).
+ Added Ben Walker mode. Credit to Gabe Bellew.
+ Added qualities to weapon pickups.
+ Temporary: Changed starting time of day.

###### Version 0.405 - October 15th, 2018
+ Updated ambRadio1.
+ Fixed shadows of doors.
+ Updated HTML5 favicon + loading bar.

###### Version 0.404 - October 15th, 2018
+ Sorted sprites.
+ Added new ambient noise (Radio1).
+ Increased time between ambient noises.
+ Rewrote how doors work.
+ Added door collision.
+ Added door opening/closing sound effects.
+ Reanimated Player: Unarmed Walking + Attack1, all Knife Animations.
+ Added 1 alternate attack for knife.
+ Version now shows compilation time.
+ Low health lowers volume of all sounds besides heartbeats.
- Pressing Space no longer speeds up time.
- Removed unused sound files and sound metadata.

###### Version 0.403 - October 15th, 2018
+ Made framerate + current frame always on GUI. (now referred to as custom overlay)
+ Custom overlay gives more details.
+ Separated inputs into own script.
+ Cleaned up pickup script. now branches to all interact-ables.
+ Added a slight sway to the camera.
+ Wooden planks from a broken crate now go in the general direction of the punch. (varies 45 degrees)
+ Crates now slightly flash when hit.
+ Pickups give off a slight sheen.
+ Added door functionality (temporarily removed collision.)
+ Added Double-Barrel + Knife to weapon pickups.
+ Updated cursor.
+ Improved outline of Firepit sprite.
+ Increased time between ambient noises.

###### Version 0.40 - October 14th, 2018
+ Added ambient noises. (Guitar as of now)
+ Corrected the way footsteps are counted.
+ Made the room bigger.
+ Set wind volume/distance cutoff to be more intense.
+ Sharpened concrete texture.
+ Slightly updated main shader.
+ Debug overlays should no longer start by default.
+ Debug overlays are now toggled differently.
+ Stats deplete slower.
+ Fixed "teleport" crashing on HTML5.
+ Added impact noises for punching Zombies (placeholders for now.)
- Properly removed Shift + CTRL for Crits.

###### Version 0.399 - October 13th, 2018
+ Corrected positioning in HTML5 port.
+ Added footsteps (concrete + grass so far.)

###### Version 0.397 - October 13th, 2018
+ Made far-looking look farther and calculate x/y separately
+ Rewrote how player attacking animations are stored.
+ Added alternate animations for Unarmed attacking (elbow, left punch).
+ Shake functions differently.
+ Separated 'help' into pages. No argument defaults to page 1.
+ Added "get_objects" command.


###### Version 0.396 - October 11th, 2018
+ Added "shake" command.
+ Added far-looking. (Shift)
- Removed debug information from on-HUD time.

###### Version 0.395 - October 9th, 2018
+ Implemented motion blur.
+ Made screen shake when punching crate more intense.
+ Added "set_global" command.
+ Screen shakes slightly when picking up Wooden Planks.
+ Player gives off a slight glow. Helps spotting the player in the dark.

###### Version 0.391 - October 9th, 2018
+ Fixed minor bug in last version.

###### Version 0.39 - October 9th, 2018
+ Updated loading text.
+ Updated organization of Stats initialization.
+ Added "set_stat" command.
+ Added listener velocity for player. should make moving fast sound a little better.
+ Updated gamepad inputs.
+ Cleaned up input script.
- Pressing Shift no longer forces crits. (Debugging tool)

###### Version 0.388 - October 8th, 2018
+ Minor fixes.

###### Version 0.387 - October 8th, 2018.
+ Tweaked health bars to damagable-objects.
+ Added readme.
+ Testing Discord/GitHub webhook.

###### Version 0.385 - October 8th, 2018.
+ Added health bars to damagable-objects.
+ Testing Discord/GitHub webhook.

###### Version 0.38 - October 7th, 2018.
+ Pushed source code onto repository.
+ Updated crosshair.
+ Player now slows down based on low Health, not Hunger/Thirst.
+ Having low Health now lowers attack damage and speed of Melee weapons.
+ Added "set_time" command.

###### Version 0.37 - October 7th, 2018.
+ Finished reanimating unarmed player sprites.
+ Various fixes

###### Version 0.36 - October 6th, 2018.
+ Added command console.
+ Added icon/counter for wooden planks.

###### Version 0.35 - October 3rd, 2018.
+ Added Disclaimer.
+ Web autoscaling is faster and doesn't affect app surface.
+ Added leaf particles.
+ Made positional sound much stronger.

##### [Pickup After Several Month Hiatus]

# How to use the [Building Editor](https://jaxdrumm.github.io/tds-zomb/html5game/editor/index.html)
Use Left Mouse Button to place objects. Hold Shift to place them quickly.
Hold Right Mouse Button to delete objects. You can hold Q while doing this to delete tiles.
Use the scroll-wheel to change the current object or tile.
'O' and 'P' will change the grid size.
CTRL + S will save your level. On the HTML5 export (web demo) this will send your room code to the debug console.
CTRL + L to load a level.

## Sounds Used:

Campfire Crackle 1, rbirdwise
https://freesound.org/people/rbirdwise/sounds/157185/
(crossfaded by me)

Cicada 1.aif, le_abbaye_Noirlac
https://freesound.org/people/le_abbaye_Noirlac/sounds/129475/

Impact-Misc_Tools-0004.wav, D W
https://freesound.org/people/D%20W/sounds/144265/

Kicking/Forcing/Breaking Wooden Door, qubodup
https://freesound.org/people/qubodup/sounds/160213/

heartbeat single, .name
https://freesound.org/people/.name/sounds/418788/
(modified by me)

Footsteps, Concrete, A.wav , InspectorJ
https://freesound.org/people/InspectorJ/sounds/336598/
(sliced by me)

grass footsteps.mp3, DSOADigital
https://freesound.org/people/DSOADigital/sounds/362250/
(sliced by me)

Door Squeak, Normal, B.wav, InspectorJ
https://freesound.org/people/InspectorJ/sounds/342554/
(sliced by me)

## Art Used:

"64 crosshairs pack", para
https://opengameart.org/content/64-crosshairs-pack

"Animated Top Down Survivor Player", rileygombart
https://opengameart.org/content/animated-top-down-survivor-player
(reanimated by me)

"Zombie UI pack", Osmic
https://opengameart.org/content/zombie-ui-pack
(unused so far)

"700+ RPG Icons", Lorc
https://opengameart.org/content/700-rpg-icons
(unused so far)

