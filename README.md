# Mega Man 2 NESRecomp

A native PC port of **Mega Man 2** (NES) created with [NESRecomp](https://github.com/mstan/nesrecomp).

The original 6502 code is statically recompiled to C and compiled into a normal Windows executable. This is not an emulator. The cycle-accurate backend handles the game logic, MMC1 mapper, PPU, and APU. A modern launcher (adapted from the Legend of Zelda NESRecomp project) provides the frontend, ROM verification, controller support, and integer scaling.

## Status

- Playable with the cycle backend
- Mega Man 2 (USA) ROM verified on launch
- Full game is playable
- Launcher rebranded with Mega Man 2 title and box art
- 6× integer scaling supported

## Requirements

- Your own legally obtained **Mega Man 2 (USA)** NES ROM
- Windows 10/11
- CMake 3.20+
- Ninja or Visual Studio 2022/2026
- Python 3.11+
- Git (for submodules)

## Building

1. Clone the repository and initialize submodules:
   ```powershell
   git clone --recursive https://github.com/YOUR_USERNAME/MegaMan2NESRecomp.git
   cd MegaMan2NESRecomp

## License
PolyForm Noncommercial 1.0.0 — see LICENSE.  
Third-party components retain their own licenses.