# Super Mario Bros
ARM64 ASM version of the original Super Mario Bros (World 1-1), developed for NU CE205 Final Project.

A recreation of the original first level of Super Mario Bros.

![Screenshot of Mario level 1](https://user-images.githubusercontent.com/59988812/230674343-82f52c1f-7e97-4d72-ac60-8a0cc6b1b7b4.png)

## Features
- Collision detection
- Player input response
- Scrolling Background
- Platforms
- Gravity
- Complex scoring system with multiple increments to player's score

## How to play
Mario can be controlled using the push buttons:
- Button 0: Move to the right
- Button 1: Move to the left
- Button 2: Jump
- Button 3: Pause the game

The goal is to reach the flag with the most amount of points:
- +200 for breaking the item block
- +100 for killing an enemy by jumping on them
- +50 for breaking a platform block

If the player does not reach the flag by the end of the countdown, the game is over.

If the player collides with the enemy, the game is over.

## Demo
To demo the game, visit [CPUlator](https://cpulator.01xz.net/), choose `ARMv7` as the architecture and `ARMv7 DE1-SoC` for system. Import the mario.s file, press compile and load, then Continue. 
The game should pop up in the VGA Pixel Buffer window on the righthand side, and you can control Mario using the push buttons interaction window. 
