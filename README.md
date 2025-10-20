<h1 align="center"><img src="https://github.com/0six0nine/Bloxstrap-Preset-Switcher/blob/main/BPS_icon.png" alt="Bloxstrap Preset Manager Logo"></p>

<h1 align="center">🔁 BLOXSTRAP PRESET SWITCHER 🔁</h1>

<p align="center">A command-line Python script that allows you to change Bloxstrap FFlags in the form of presets conveniently!</p>

<hr>

## Overview
An easy solution for people who change ROBLOX FFlags regularly; this is mainly for developers who want to experiment with the engine's beta features, or for people on lower-end devices who want a performance boost. This script streamlines the otherwise grueling process of opening Bloxstrap and clearing & pasting in JSON entries into just a few button presses.

---

## ⬇️ Prerequisites/Installation ⬇️

### Bloxstrap
Install Bloxstrap by clicking [**here**](https://github.com/bloxstraplabs/bloxstrap/)

### Python
Install the latest version of Python by clicking [**here**](https://www.python.org/downloads/)

## Features
- Before the script closes, you'll be able to decide whether you want a shortcut of the program on your desktop or not (if there isn't already) for your own convenience.
- The script will notify you if there are any `.json` files with invalid JSON.
- `.json` files inside the preset folder will automatically be copied into a directory in `%USERPROFILE%\AppData\Local` with the name `BloxstrapPresetSwitcher`. New files put into the `Presets` folder will automatically be copied to the directory the next time the program is run
- This script saves a maximum of 3 backups in the same location as `ClientAppSettings.json` in the following format: `ClientAppSettings_YEARMONTHDAY-HOURMINUTESECOND.json.old`
> [!NOTE]
  This script will delete the oldest backup when 3 are already made, so be careful!

## Usage
After installing, extract the ZIP file and run `BloxstrapPresetSwitcher.exe`.
When running the script, you should be able to see something similar to the image below: 

<img width="762" height="142" alt="hi" src="https://github.com/user-attachments/assets/720ded79-c9d4-47f8-a1d3-35cb71db7780" />

You can then enter any number up to the amount of detected JSON files, and launch ROBLOX with those settings applied.
You can add as many presets as you want; just place any `.json` file inside the `Presets` folder.

## Bugs
I'm not the most experienced Python coder, so if you spot any errors or things I could improve on, please make an issue request! This benefits both me and you in terms of my coding skills and keeping this script running optimally.
