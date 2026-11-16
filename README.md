# Northwood Patrol

Mobile-first, top-down **police patrol and detective pixel-art game**.

## Play on iPhone

**[Play Northwood Patrol](https://liamg52.github.io/Northwood-Patrol/?v=0.5)**

Rotate your phone to **landscape (horizontal)**. If the screen will not rotate, disable iOS Portrait Orientation Lock in Control Center.

## Version 0.5 — Living Town

- 14 ambient pedestrians on sidewalk loops, with short conversations via **ACT**
- 8 moving civilian vehicles on road routes, with basic yielding near the cruiser
- Repeatable dispatch calls after finishing the first case: store alarm, welfare check, park disturbance, motorist assistance
- Follow the new gold call marker, exit your vehicle, and use **ACT** to complete a follow-up call
- Patrol completion count and next call details appear in the Casebook
- Existing 45° isometric camera, landscape layout, larger joystick, solid building collisions, and custody flow remain intact

## Version 0.4

- New **45-degree isometric-style** camera with angled buildings and roads
- **Landscape-first** layout with a rotate-device prompt
- Solid collisions: the officer and cruiser cannot pass through building footprints
- Detention, escort, rear-seat transport, unloading, and booking at the station jail
- Suspect follows the officer's route around obstacles
- Existing joystick, ACT button, driving, evidence, witness, and casebook flow retained

## Case NW-001 — Electronics Break-In

1. Visit Northwood Electronics and collect all three evidence items
2. Interview the witness, then question and arrest the suspect
3. **Walk back to your patrol cruiser with the suspect following you**
4. Tap **ENTER CAR** near the cruiser to secure the suspect in the back
5. Drive to the **Police Station**, then tap **EXIT CAR** to unload the suspect
6. Escort the suspect to the **JAIL / BOOKING** entrance and press **ACT**

## Continue patrolling

After booking the suspect from Case NW-001, a new dispatch call arrives automatically. Follow the gold marker, stop nearby, exit the cruiser, and press **ACT** to clear the call. A different call will follow. This is a first-pass repeating call system, not a full investigation for every call.

## Controls

- Left on-screen joystick: walk or drive; direction follows the angled screen
- **ACT**: interact with evidence, witnesses, suspect, jail booking, civilians and active dispatch markers
- **ENTER CAR / EXIT CAR**: enter and exit the cruiser
- **Casebook**: view evidence and custody status

The game is plain HTML, CSS, Canvas, and JavaScript; no build step is required. GitHub Pages serves the `index.html` on the repository's `main` branch.

Note: Safari websites cannot reliably force iPhone screen rotation. Turn the phone sideways to play in landscape.
