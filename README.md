# Skate Mod (Fabric, Minecraft 26.1.2)

## Setup
1. Fill in the `CHANGE_ME` values in `gradle.properties` with the Loader, Fabric API, Mod Menu and Loom versions for 26.1.2 (see https://fabricmc.net/develop).
2. Skins and models are already generated. To regenerate: `python3 tools/generate_skins.py`
3. Build: `./gradlew build`, then take the jar from `build/libs/`.
4. Install the jar alongside Fabric API and Mod Menu.

## Items
- Skateboard: right-click a block to place a board, then right-click the board to ride.
- Small Wooden Ramp / Big Wooden Ramp: the slope rises in the direction you were facing when you placed it.

## Controls
| Key | Action |
|-----|--------|
| G | Open skin selector (34 skins) |
| W / S | Push / brake (S while moving forward) |
| A / D | Steer on the ground, spin in the air |
| Space | Ollie on the ground; ride up a ramp to launch off the top |
| Z | Kickflip while airborne |
| X | Heelflip while airborne |

Landing a trick shows its score in the action bar. Spins are named by total rotation (180, 360, 540, 720, 900). Settings are under Mod Menu → Skate Mod and are saved to `config/skatemod.json`.
