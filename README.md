<h1 align="center"><img src="https://github.com/0six0nine/Bloxstrap-Preset-Switcher/blob/main/BPS_icon.png" alt="Bloxstrap Preset Manager Logo"></p>

<h1 align="center">🔁 BLOXSTRAP PRESET SWITCHER 🔁</h1>

<p align="center">A command-line Python script that allows you to change Bloxstrap FFlags in the form of presets conveniently!</p>

<hr>

> [!TIP]
> - Run `Bloxstrap Preset Switcher.py` first ***BEFORE*** running from the shortcut; the script will fix its otherwise wrong target location.

## Overview
An easy solution for people who change ROBLOX FFlags regularly, whether it be for testing purposes, or simply for a slight advantage in some games. This script streamlines the otherwise grueling process of opening Bloxstrap, clearing/editing/pasting in FFlags (in my case, it was copying from text files) into just a few button presses.

---

## ⬇️ Prerequisites/Installation ⬇️

### Bloxstrap
Install Bloxstrap by clicking [**here**](https://github.com/bloxstraplabs/bloxstrap/)

### Python
Install the latest version of python by clicking [**here**](https://www.python.org/downloads/)

### Modules
Run the batch file named `requirements.bat` inside the `Other` folder; this should install all the modules required by the script

## Features
This script saves a maximum of 3 backups in the same location as `ClientAppSettings.json` in the following format:
`ClientAppSettings_YEARMONTHDAY-HOURMINUTESECOND.json.old`
> [!NOTE]
Do note that this deletes the oldest backup when there are already 3 existing ones, so be mindful of that!

## Usage
After installing, extract the ZIP file and run `Bloxstrap Preset Switcher.py`.
When running the script, you should be able to see something similar to the image below: 
<img width="768" height="140" alt="image" src="https://github.com/user-attachments/assets/1ca7464a-4153-4d46-82af-bf2d730b68bf"/>

You can then enter any number up to the amount of detected JSON files, and launch ROBLOX with those settings applied.
You can add as many presets as you want, inside the `Presets` folder.

## Bugs
I'm not the most experienced Python coder, so if you spot any errors or things I could improve on, please make an issue request! This benefits both me and you in terms of my coding skills and keeping this script running optimally.
