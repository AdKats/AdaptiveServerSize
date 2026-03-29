# CAdaptiveServerSize

A Procon plugin that dynamically adjusts Battlefield server size based on the current player count.

## Features

- **Adaptive Server Size** — Automatically scales server slots up and down as players join and leave, configurable per player count and per game mode.
- **Welcome/Join Messages** — Optional messages to encourage players to stay when the server is seeding.
- **Adaptive Idle Kick** — Disables idle kick when the server has few players to help retain seeders, re-enables it once the server populates.
- **Game Mode Limits** — Per-game-mode maximum server size caps.

## Supported Games

- Battlefield 3 (BF3)
- Battlefield 4 (BF4)
- Battlefield Hardline (BFHL)

## Installation

Download the latest release zip and extract `CAdaptiveServerSize.cs` into your Procon plugins directory for the appropriate game.

## Configuration

All settings are configured through the Procon plugin interface:

- **Enable adaptive server size** — Toggle the core feature on/off.
- **Maximum server size** — Upper bound for server slots.
- **Size with X players** — Define the desired server size for each player count.
- **Maximum [Game Mode] size** — Cap server size per game mode.
- **Welcome/join messages** — Customize messages shown to players when the server is seeding.
- **Adaptive idle kick** — Configure when idle kick is disabled and the desired timeout.

## License

GPLv3 — see [LICENSE](LICENSE) for details.

## Author

Originally created by falcontx.
