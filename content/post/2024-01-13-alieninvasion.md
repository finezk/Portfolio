---
layout:     post
title:      "Alien-Invasion"
subtitle:   "A game about shooting aliens"
date:    2024-01-13
author:     "Zachary Hsu"
image: "/img/alieninvasion.png"
tags:
    - Python
URL: "/2024/01/13/2024-01-13-alieninvasion"
---
# Alien-invasion Game

## Introduction
![banner.png (1918×1080) (raw.githubusercontent.com)](https://raw.githubusercontent.com/finezk/alien-invasion/main/banner.png)

"Space Invaders" is a classic arcade game released in 1978 by Taito. It was one of the earliest shooting games and remains a significant and influential title in the video game industry. In the game, players control a ship that moves horizontally at the bottom of the screen, and they must shoot down waves of approaching alien invaders before they reach the bottom. The game's simple yet addictive gameplay and iconic pixelated alien sprites have made it a classic in the gaming world.

### Play Online Game
[Alien-invasion - Replit](https://replit.com/@ZacharyHsu/Alien-invasion)

### Download Desktop App
[Releases · finezk/alien-invasion (github.com)](https://github.com/finezk/alien-invasion/releases)

## Usage

1. Run this script from command line without arguments to use the default keywords:
```
python alien_invasion.py
```

2. Visual Studio Code
Download VSCode https://code.visualstudio.com/

Download python https://www.python.org/

After installing VScode and Python, download the extension in VSCode as follow:
* python
* python for vscode
* code runner

Done it and Run code


## HOW TO PLAY:
1. Download the game by clicking on the "Alien" file.
2. After the download is completed, open the file.
3. Click the green button that said "Play" on it.
4. Control the aircraft in order to shoot the aliens on the top of the screen.
5. The aliens will slowly lower there height every second until it reaches the aircraft.
6. Each level completed will increase the alien's speed. (The level is indicated in the top right)
7. The top left corner displays your current life amount. (Indicated by the amount of ship)
8. Shoot the aliens to earn points, the objective is to get as many points as you can before you used up all 3 lives.

## CONTROLS:

Movement: Left-arrow key/Right-arrow key
Shoot: Spacebar
Quit: Press Q

##  Build exe
Using terminal and pyinstaller to build exe
```
$ pyinstaller -F alien_invasion.py -c --icon=icon.ico
```