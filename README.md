# Ragdoll Range

A private physics playground with first-person shooting, active ragdolls, interactive props, and explosive barrels. An early prototype for testing with friends.

This repository contains the player guide only. Download finished game builds from **[Releases](https://github.com/Blueapple77/ragdoll-range/releases)**. The source project is not included.

## Download and play

- **Windows x64:** download and run `RagdollRange.exe`. No installation or Godot runtime required.
- **macOS:** download `RagdollRange-macOS.zip`, extract it, and open `Ragdoll Range.app`. Supports Intel (macOS 11+) and Apple Silicon (macOS 13+). This build is ad-hoc signed, not notarized by Apple, and has not yet been tested on a Mac. macOS may require permission in Privacy & Security settings.

To access this private repository, sign in with an invited GitHub account and accept the invitation.

## Controls

| Action | Control |
| --- | --- |
| Move / sprint | WASD / Shift |
| Jump | Space |
| Aim / fire | Mouse / left click |
| Pistol / shotgun / minigun | 1 / 2 / 3 |
| Spawn NPC at crosshair | Right click |
| NPC and prop spawn menu | Middle click |
| Gameplay settings | F2 |
| Reset arena | R |
| Toggle pixel filter | P |
| Release cursor / close menu | Esc |
| Quit | Close the window |

## Things to try

- NPCs react to the body part you hit, try to regain their balance, and can get up after surviving a fall.
- Adjust weapon damage, impulse, and fire rate with F2. Powerful shots launch bodies through the air.
- Crates, ordinary barrels, and balls are indestructible but physically interact with shots, NPCs, and explosions.
- Red TNT barrels have health and can trigger chain reactions. Adjust their health, explosion radius, damage, impulse, and upward lift with F2.
- Explosions launch and spin props. They also damage the player; losing all health returns you to the starting position.
- R restores NPCs and props, including exploded barrels. F2 settings last for the current session; health changes marked new / reset apply to newly spawned objects or after a reset.

Report problems in Issues with reproduction steps, your settings, and your operating system.
