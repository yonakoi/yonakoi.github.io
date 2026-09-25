---
name: Rat Runner
tools: [C#, Unity, Procreate]
image: ../images/rat-runner-itch-cover.png
description: Play as rat trying to escape a mad scientist's maze while avoiding corrupt rat comrades. Find the key, and don't get caught. Team project using 3D assets and 2D menus in Unity. Click to learn more.
---
# Rat Runner

<p class="text-center">ᓚᘏᕐᐷ
{% include elements/button.html link="https://chessmix.itch.io/rat-runner" text="Play the Game!" %}ᓚᘏᕐᐷ
</p>

## Overview

Rat Runner is a 3D game created in Unity. You play as a rat who's trying to escape a maze created by the mad scientist who trapped him there. There are other rats who succumbed to the scientist's experiments running around the maze, chasing the player whenever they get too close. The player must find the key to escape the maze, and can also find items to give themself upgrades throughout the game. The player has 3 days to escape.

## Gameplay

Use WASD to move, C to change cameras. The player can touch items with the rat to collect them, and can use E to interact with the workbench to upgrade. Avoid the enemy rats, if the player's health goes down to 0, the day will progress. 

![preview](../images/rat-runner-menu.png)

## My Role

I was the UX/UI and Audio Manager. 

For the UX/UI, I hand drew the menus on Procreate, and then handled the systems in game. I used C# to create slight animations in the game such as movement, the transition between one day to the next, and the vignettes that appear when an enemy is nearby and when the player is on their last life. I handled the switch between each game state, such as game over, menu, game, and pause state. 

For the audio, I implemented all the sounds my teammate created. I also created two of the audios, the atmosphere that plays throughout the game, and the audio that plays when an enemy is chasing the player. I used an AudioManager to keep track of all the audios, instead of having them scattered throughout the objects.


![search](../images/rat-runner-workbench.png)

<p class="text-center">⪩. .⪨</p>
