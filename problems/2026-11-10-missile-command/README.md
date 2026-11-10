# Build Your Own Version of Missile Command

## Timings
- 18:00 -- start
- 18:15 - 18:30 -- introduce the problem and timings, split into teams
- 18:30 - 19:30 -- 1 hour to develop your solutions!
- **19:30 DEADLINE keyboards down!**
- 19:30 - 20:30 -- each team demos their solution & shares it via the repo
- 20:10 -- everyone votes
- Note the winning team in the repository

## Problem / Challenge
Build a 2D browser version of the retro game **Missile Command**! Incoming missiles are incoming toward your cities. Click on the screen to send intecepting missiles to destroy them before they hit.

What the real game looks like:
https://www.youtube.com/watch?v=tz4YCQaOxOI

One hour is enough for a tense, playable defence, not a full arcade port. 

Aim for readable threats and a real "I can't save them all" feeling.

### Must have, minimum to count as a solution:
- Three cities along the bottom of the screen
- Incoming missiles: straight lines from the top toward a city
- Click to fire: a burst appears at the click (or flies there, then explodes)
- Explosion has a radius; any missile inside is destroyed
- A city is destroyed if a missile reaches it
- **Lose** when all cities are gone
- **survive** at least one wave (or a 20–30s barrage)
- Restart

### Out of scope
- Missile splits
- Aircraft launching missiles
- Satellites
- Terrain
- Sound
- Particle engines
- Online multi-player
- High scores

### Stretch (only after the must-haves)
- Interceptor travel time (burst flies, then detonates)
- limited ammo 
- missiles that split
- faster waves
- score (missiles killed / cities left)
- screen shake / effects on impact
  
### Suggested stack
- One HTML / JS / canvas page, potentially pulling in other JS files to split the work and make the code easier to understand. No game engine required.
- Keep the sim simple:
  - missiles are segments or points with constant velocity
  - explosions are circles that grow for a few frames then vanish
  - Spawn from random `x` at the top, aimed at a random living city. 
  - Tune so the first waves of missiles are beatable and the next one is increasingly less comfortable.

## Judging
(Criterion -- What to look for)
- Teamwork -- How you split up the task and collaborated 
- Clarity -- You can see missiles, bursts, and which cities still stand
- Interactivity --  Click to intercept, with obvious hit/miss feedback
- Challenge -- Balanced difficulty, making it hard to save every city, but not too hard, aiming and timing matter

- Code structure -- AI will tend to pile everything into one .html file, extra points for giving it a more maintainable structure.

Juice (trails, shake, boom) is a tie-break, not the goal.

## Ground rules
- AI coding allowed
- Teams of 3-4

## Guidance
- Agree in the first 5-10 minutes who does what
- Well suited to live / collaborative coding if it works