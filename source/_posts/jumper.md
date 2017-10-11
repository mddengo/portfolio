---
title: Jumper Game
tags:
cover_image: /images/jumper.png
---

# Background
Jumper is a game that was conceived in the first project for HCI class 05-833: Gadgets, Sensors, and Activity Recognition taught by Prof. Scott Hudson. It is an extremely simplified version of the popular phone app [Doodle Jump](https://itunes.apple.com/us/app/doodle-jump/id307727765?mt=8).

This game is displayed on an 8x8 LED matrix, where the user controls a pixel (the Jumper) on the screen with two switch buttons. The Jumper is in a constant bouncing motion, so the user only needs to move the Jumper left or right by pressing either the left or right switch. The goal of the game is to advance the pixel using ledges that will appear on the screen and to stay alive as long as possible. The game ends when the player misses a ledge, and the Jumper will "fall" all the way back to the first ledge, immediately starting a new game.

The final score is the total height the Jumper has achieved.

# Technologies
This game was developed using the [Arduino Nano](https://www.arduino.cc/en/Guide/ArduinoNano) on the Arduino Web IDE.

# Progress Pictures
{% asset_img "start.JPG" "spaced title" %}

# Final Product
{% video '<iframe height=498 width=510 src="play_game.MOV" frameborder=0 allowfullscreen></iframe>' %}

## Reflection
