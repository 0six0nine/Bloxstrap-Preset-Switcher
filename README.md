<h1 align="center"><img src="https://github.com/0six0nine/Bloxstrap-Preset-Switcher/blob/main/BPS_icon.png" alt="Bloxstrap Preset Manager Logo"></p>

<h1 align="center">🔁 BLOXSTRAP PRESET SWITCHER 🔁</h1>

<p align="center">A command-line Python script that allows you to change Bloxstrap FFlags in the form of presets conveniently!</p>

<hr>

> [!TIP]
> - Run `main.py` first ***BEFORE*** running from the shortcut; the script will fix the otherwise wrong target location.

## Overview

An easy solution for people who change ROBLOX FFlags regularly, whether it be for testing purposes, or simply for a slight advantage in some games. This script streamlines the otherwise grueling process of opening Bloxstrap, clearing/editing/pasting in FFlags (in my case, it was copying from text files) into just a few button presses.
---
## Prerequisites/Installation
## Bloxstrap
Install Bloxstrap by clicking [**here**](https://github.com/bloxstraplabs/bloxstrap/)

### Python
Install the latest version of python by clicking [**here**](https://www.python.org/downloads/)

### Modules
Run the batch file named `requirements.bat`; this should install everything needed for the script

## Features
This script saves a maximum of 3 backups in the same location as `ClientAppSettings.json` in the following format:
> - `ClientAppSettings_YEARMONTHDAY-HOURMINUTESECOND.json.old`

Do note that this deletes the oldest backup when there are already 3 existing ones!

## Usage
When running the script, you should be able to see something similar to the image below: 
<img width="960" height="480" alt="image" src="https://github.com/user-attachments/assets/dba47017-1120-4f4a-a8ee-1513cdb49900" />

You can then enter a number up to the amount of detected JSON files, and launch ROBLOX with those settings applied.
You can add as many presets as you want, inside the `Presets` folder.
