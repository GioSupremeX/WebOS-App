Cloud Retro Gaming Hub - ROM folder
====================================

Put your legally obtained ROM files in this folder, then list them in games.json.

Supported cores (EmulatorJS): nes, snes, gb, gbc, gba, genesis, n64, psx, atari2600, ...

Each entry in games.json:
  {
    "id": "unique-id",
    "title": "Game Title",
    "platform": "NES",
    "core": "nes",
    "rom": "./games/your-rom.nes"
  }

NOTE: Only use ROMs you own or that are freely distributable (homebrew/public domain).
Do NOT commit copyrighted ROMs to a public GitHub repository.
