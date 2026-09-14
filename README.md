# CBK — Splashy Karp

A refreshed edition of Splashy Karp, the one-button underwater reef runner.

## Play

Open `index.html` in a modern web browser. The standalone download is named
`CBK.html` and works the same way. No installation, account, internet connection,
external fonts, image downloads, or build tools are required.

Choose **Start swimming** for the full run or **Boss practice** to meet CBK
straight away.

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
- Survive **19 seconds and six surges** to earn **+25 points**. The boss retreats,
  and the full run continues with a gradually tougher reef.
- The boss appears once per full run. Boss Practice can be replayed immediately
  and does not affect the personal-best record.
- Touching coral, a crimson projectile, the surface, or the seabed ends the run.
  Arrival and victory transitions give the fish a forgiving bounce at the edges.

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
  victory bonus, and a return to normal reef play.
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

The delivered HTML passed 15 local JavaScript/DOM gameplay checks. These cover
keyboard and pointer events, scoring, stored records, blocked storage, collisions,
restart cleanup, pause/resume, window-focus handling, the complete early boss
sequence, successful continuation at desktop and phone world sizes, practice
completion, and standalone release startup. Automated runs use the real physics
and collision logic with ordinary swim inputs.

The character, reef, and boss artwork were rendered directly and visually
inspected. A live browser layout and device play-test could not be completed
because the preview browser blocked local game files. Test-only controls are
removed from the delivered game.

Unofficial fan-made arcade game.
