# PuellaMagiMod

**PuellaMagiMod** is a Minecraft mod designed to enhance gameplay with various commands related to combat, movement, visuals, and utility. This mod allows users to easily modify in-game mechanics such as teleportation, visual effects, and aimbot settings, while providing a variety of keybindings for ease of use.

## Features
- **Combat Enhancements:** Modify aimbot range with ease.
- **Movement Utilities:** Adjust vertical and horizontal clipping (VClip/HClip), teleport to coordinates, fly, and more.
- **Visual Commands:** Customize health text color, enable/disable message suffixes, and apply gradient effects.
- **Utility Commands:** Command spamming tools for advanced users.
- **Keybindings:** Quick access to various actions such as VClip, HClip, teleportation, aimbot.....

## Installation
1. Download the latest release from the [releases page](https://github.com/Sallie-May/PuellaMagi-Mod/releases).
2. Place the mod `.jar` file into your Minecraft `mods` folder.
3. Launch Minecraft with Forge installed.

## Available Commands

### Combat Commands
- `?aimbot <number>`: Change the aimbot range to the specified number.

### Movement Commands
- `?vclip <number>`: Set the vertical clip height. Default: `2.0`.
- `?hclip <number>`: Set the horizontal clip height. Default: `2.0`.
- `?goto <Coordinate>`: Teleport to the specified coordinate.
- `?goto stop`: Stop teleporting.
- `?autoteleport <on/off>`: Enable or disable automatic teleportation.
- `?spin <1/2>: 1 is packet based, 2 is head based`: Change type of spinning.
- `?fly <number>`: Change fly speed.
### Visual Commands
- `?color <hexCode>`: Set the health text color using a hex code (e.g., `?color FF5733`).
- `?suffix <text>`: Change the message suffix (e.g., `?suffix uwu`).
- `?suffixdisable`: Disable the message suffix.
- `?suffixenable`: Enable the message suffix if disabled.
- `?gradient <index>`: Apply a gradient effect to the module (e.g., rainbow effect).
- `?gradientlist`: List all available gradient colors.
- `?noweather`: Will disable or enable noweather

### Utility Commands
- `?cmdspammer delay <ticks>`: Set the delay (in ticks) between spamming commands.
- `?cmdspammer command <command>`: Define the command to be spammed.
- `?discord`: To get the discord URL
  
### Key Commands
- **Press** `[Teleport Key]` to VClip (use `?vclip` to modify).
- **Press** `[Fly Key]` to fly (use `?fly <speed>` to modify).
- **Press** `[HClip Key]` to HClip (use `?hclip` to modify).
- **Press** `[Teleport Toggle Key]` to random teleport.
- **Press** `[Particles Key]` to enable Laser ESP.
- **Press** `[Aimbot Key]` to toggle Aimbot.
- **Press** `[Killaura Key]` to toggle Killaura (15 blocks).
- **Press** `[CMD Spammer Key]` to enable the CMD Spammer.
- **Press** `[Spin]` to enable the Spin.
- **Press** `[Fake Creative]` to enable the Fake Creative.
- **Press** `[Velocity]` to enable Velocity
- **Press** `[NoBadEffect]` to disable/enable NoBadEffect
- **Press** `[NoHurtCam]` to disable/enable NoHurtCam

## Bonus Features
- **Auto Teleport:** Automatically teleport if health drops below 500 HP.
- **Health Display:** Your current health is shown in the top-left corner of the screen.

## Contributing
If you'd like to contribute to the development of FurRiotMod, feel free to fork the repository and submit a pull request. We welcome improvements and new features!
