# CBK — Splashy Karp · Teacher’s Pet

The Teacher’s Pet update adds a bubble shield, a temporary sea-dragon evolution,
and a second ocean zone to the one-button underwater reef runner.

## Play

Open `index.html` in a modern web browser. The standalone download is named
`CBK.html` and works the same way. No installation, account, internet connection,
external fonts, image downloads, or build tools are required.

Choose **Start swimming** for the full run or **Boss practice** to meet CBK
straight away. Practice starts with one shield and includes the 15-second
Teacher’s Pet preview in the Lantern Grove after you survive the boss.

## Controls

| Action | Control |
| --- | --- |
| Swim upward | Tap the game, click, Space, or Arrow Up |
| Sink | Wait between taps |
| Pause or resume | P, Escape, or the on-screen buttons |
| Toggle optional sound | M or the speaker button |

The game pauses when its browser window loses focus or its tab is hidden.
Hold-to-repeat is intentionally disabled: each swim uses a new tap or key press.

## Score and progression

- Coral gate: **+1 point**.
- Glowing bubble: **+3 points**.
- After **four gates**, the reef clears for an early boss encounter.
- **CBK — The Crimson Current** is a red sea-serpent homage to red Gyarados.
- A 2.8-second arrival warning introduces the encounter. Stay outside the marked
  red currents; arrow cues also show a safe direction.
- Survive **19 seconds and six surges** to earn **+25 points** and unlock
  **Teacher’s Pet**. The boss appears once per full run.
- The full run continues into **Zone 02: The Lantern Grove**, a luminous cavern
  with drifting jellyfish, submerged pillars, and a new colour palette.
- Boss Practice does not affect the personal-best record. It finishes after
  the evolution preview and offers the full game.

## Bubble shield

A blue bubble containing a shield symbol appears ahead of the first coral gate.
Collect it to protect against one collision with coral, a boss projectile,
a jellyfish, the surface, or the seabed. A blue shell surrounds Karp and the HUD
shows **Shield ready**. Shields are separate from the smaller point bubbles.

The shield pops on impact and grants 1.4 seconds of recovery so the same
obstacle or volley cannot immediately end the run. Coral impacts nudge you
into the open gap; boundary impacts bounce you back into the water. Only one
shield can be held at a time. More are offered periodically in the Lantern
Grove when you do not already have one.

## Teacher’s Pet

Surviving CBK transforms Karp into a larger teal-and-gold sea dragon with a
star crest, flowing fins, and a luminous trail. The evolution announcement
holds the timer until you enter the Lantern Grove, where you receive a full
**15 seconds of power**.

- The same tap/click/Space controls apply, with a gentler swimming arc.
- Coral breaks on contact and awards **+1 point**, exactly once per gate.
- Lantern jellyfish disperse on contact and award **+2 points**.
- The surface and seabed bounce you back into the water.
- An existing shield is kept for use after the evolution ends.
- The HUD displays the remaining power, with a warning in the final 3 seconds.
- Pausing also pauses the evolution and all moving hazards.

When the power expires, you return to Karp with 1.6 seconds of recovery.
The full run continues in the Lantern Grove: dodge the jellyfish and coral,
collect bubbles and find another shield. The zone does not disappear when
the evolution expires.

Without evolution, a shield, or recovery protection, colliding with a hazard
or the water boundaries ends the run. Boss-arrival and evolution-announcement
transitions also give the fish a forgiving boundary bounce.

Your full-run personal best uses the original `splashy-karp-best` browser-storage
key. An existing record carries over when the replacement is played on the same
website origin and browser. Local downloads and other websites have separate
storage. If browser storage is unavailable, the game still works and keeps the
record for the current page session.

## What changed

- Rebuilt title screen, typography, controls, score display, and results screens.
- A larger, expressive Karp model with animated fins, tail, eyes, and whiskers.
- Layered underwater light, distant fish, stone arches, kelp, and detailed coral.
- An animated crimson boss with coiling body segments, fins, horns, and barbels.
- A complete boss sequence with warnings, aimed projectiles, a survival meter,
  victory bonus, and a Teacher’s Pet evolution reward.
- A collectible bubble shield with one-hit protection and a recovery window.
- The Teacher’s Pet model, a timed power meter, obstacle smashing, and a safe
  transition back to Karp.
- The Lantern Grove, with a distinct cavern backdrop, bioluminescent plants,
  new coral colours, drifting jellyfish hazards, and a zone-entry chime.
- Responsive desktop and phone layouts, keyboard controls, optional synthesized
  sound, pause/resume, and protected score saving.
- Reduced decorative motion when the operating system requests reduced motion.

## Update your existing GitHub game

This ZIP contains `index.html` at its root. Replace the existing game's
`index.html` with this file and commit it to the branch your existing Pages
deployment uses. The complete game lives in that one file; keep the filename
`index.html` for the website entry point.

This handoff supplies the replacement files. It does not change or deploy a
GitHub repository.

## Validation

The game passed 26 local JavaScript/DOM gameplay checks. These cover
keyboard and pointer events, scoring, stored records, blocked storage, collisions,
restart cleanup, pause/resume, window-focus handling, the complete early boss
sequence, shield pickup and consumption, recovery windows, coral and jellyfish
smashing, evolution timing, timer freezing, power expiry inside an obstacle,
successful continuation through the second zone at desktop and phone world
sizes, practice completion, and standalone release startup. Automated runs
use the real physics and collision logic with ordinary swim inputs.

The character, shield, boss, Teacher’s Pet, and ocean artwork were rendered
directly and visually inspected. A live browser layout and device play-test could not be completed
because the preview browser blocked local game files. Test-only controls are
removed from the delivered game.

Unofficial fan-made arcade game.
