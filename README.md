# La Va Land
> four person fast-five

CIS568 Project 2 Work Plan

Santiago Buenahora, Edward Cai, Alexander Chan, Davin Hazard, Anosha Minai

## Technical Requirements Time Estimate:

1. Arrow Shooting:
  * Hold bow: Change the starter gun to a bow ~ 2 hours
  * Shoot arrow (with button): change projectile to bow object ~ 2 hours
  * Shoot arrow (with motion): detect when the arrow is pulled back on the Vive controller and then shoot when it is let go ~ 10 hours
  * Make VR ready: test with Vive headset to make sure it “feels right” for VR ~4 hours
2. Teleportation:
  * Change arrows: add option to change arrows that teleport instead of damaging the opponent ~ 4 hours
  * Teleportation arrow: implement something similar to the class demo with option of confirmation ~ 2 hours.
  * Condition Testing: Set conditions for valid teleportation areas ~ 3 hours.
  * Make VR ready: add camera effects to make sure it doesn’t cause motion sickness ~ 3 hours
3. Game Mechanics:
  * Random power-ups: Create power-ups (possibly large arrow, explosives, slow) ~ 12 hours
  * Additional arrow types: bundled with above task
  * Radar and scatter arrow (like Hanzo’s) ~ 4 hours
  * Arrow disabling “special” arrows ~ 4 hours
  * Implementing win conditions: keep track of health and lives. End game when conditions are met ~ 4 hours
  * Time-based (most kills wins)
4. VR UX:
  * Haptic feedback: vibrate controller when shoot arrow, vibrate controller when hit ~ 2 - 4 hours (no idea how to do this)
  * Visual feedback when hit ~ 2 - 4 hours
  * Arrow color switch: Change colors of arrows ~ 2 hours.
  * Scoreboard
  * Multiplayer:
5. TOTAL: ~40 hours

## Teamwork Breakdown:

1. Santiago Buenahora: game environment, teleportation
2. Edward Cai: bow, shoot arrows, game environment
3. Alexander Chan: game mechanics, level design, bow/arrows, UI/UX
4. Anosha Minai: game mechanics, level design

## Mechanics & Visual Style:

1. Win conditions: 3 lives, 100 health or time-based
2. Location based damage (headshots are OHKO, etc)
3. World appearance: cartoonish, with buildings (like Team Fortress: https://usercontent2.hubstatic.com/12810491_f520.jpg)

## Timeline:

1. Alpha Mechanic Demo (2/16/17 @ 1:30PM):
 * ~~Basic arrow shooting with controller~~
 * ~~Teleportation~~ with VR ready camera effects
 * Some additional arrow types
 * ~~Arrow switching~~
 * Basic “shooting gallery” level
 * Visual/haptic feedback
2. Beta Mechanic Demo (2/21/17 @ 1:30PM):
 * Polished arrow shooting
 * Polished teleportation
 * Win conditions
 * Basic multiplayer
 * Preliminary full level
 * UI
3. Final Demo 2/28/17 @ 1:30PM: Everything should work!

## Questions

### Name and Project Name
La Va Land

### A link to a demo of your game on YouTube (you will be expected to make a good video - this is important for both resume purposes and in general for visual applications)
[Video!](https://youtu.be/4Ezl-UG5XNw)
[Multiplayer Demo](https://youtu.be/ih8ww9oYQ2o)

### Techniques used, and why those techniques.
- Steamsworks
- Lava (death upon player step + animated material)
- Respawn to random location
- Lobby with spheres

### How to play (using a controller or HMD)
- The player starts in a Game Lobby, where they can either host a game by shooting the "Host Games" sphere or look for an existing one by shooting the "Find Servers" sphere. If they opt to find an existing session, the lobby populates with smaller "Session" spheres which can be shot to join a session. In order for both players to join the same game via different computers they need to write ""
- Once in the Lava Level, the player needs to shoot a team sphere to join either the red or blue teams.

### When in VR mode, did you feel any motion sickness? Why and why not?
Not really, only when falling off the tower

### What was the hardest part of the assignment?
Among the difficulties
- Configuring multiplayer (both lobby and replication)
- Modeling the towers in a navigable way

### What do you wish you’d done differently?
- Music
- More lava
- Death animation
- More visuals on scene

### What do you wish we had done differently?
- A bit more time?
