# Fire Training (Quest WebXR)

Standalone mixed-reality fire safety awareness demo for Meta Quest 3, built with three.js WebXR (immersive-ar). No build step, no keys, no backend - static files only.

**Awareness demo - not certified training. Follow site procedure.**

## Stages
1. **Classes** - flashcard-style 3D dioramas of fire classes A/B/C/D/E/K: materials, what fights each, and what to never use.
2. **PASS** - Pull, Aim, Squeeze, Sweep explained on the board, then animated on the real 3D extinguisher against a tray fire.
3. **Drill** - power-plant scenario: an 11kV control cabinet has a live electrical (Class E) fire. Pinch the RIGHT extinguisher from the rack (wrong types explain the danger), pull the pin, aim at the base, pinch-hold to squeeze, sweep side to side. Scored out of 100.

## Run
- Quest 3: open the deployed URL in the Quest browser, tap **ENTER AR**, allow hand tracking. Pinch to select; pinch-hold on the extinguisher body to squeeze; move your hand side to side to sweep.
- Desktop preview: open the URL, click = pinch, drag = look around.

## Credits
- Extinguisher model: NVIDIA SimReady (CC BY 4.0), Draco-decoded for fast Quest loads.
- PASS reference: OSHA portable extinguisher eTool.
- three.js r170 (MIT).
