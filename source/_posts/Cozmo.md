---
title: Voice-controlled Tic Tac Toe with Anki Cozmo
cover_image: /images/cozmo_ttt.png
---
# Introduction

This project was the culminating final project of [15-494: Cognitive Robotics](https://www.cs.cmu.edu/afs/cs/academic/class/15494-s17/) taught by Dave Touretzky at Carnegie Mellon University. This class explored the future of robot toys by analyzing and programming the [Anki Cozmo](https://www.anki.com/en-us/cozmo), a robot with built-in artificial intelligence algorithms. Its capabilities include face and object recognition, map building, path planning, and object pushign and stacking. We used Cozmo's open source Python SDK to learn about robot software architecture, human-robot interaction, perception, and planning algorithms for navigation and manipulation.

For this project, my partner and I made a voice-controlled two-player Tic Tac Toe game, where each player would use speech to choose their Cozmo's moves, and Cozmo would push a chip to the chosen square of the Tic Tac Toe board. Cozmo has knowledge of and understands the game board, pieces, and game logic. 

To help Cozmo "see" and know the spacial configuration of the board, we used two different Aruco markers and pasted them onto 3D-printed "stop signs," which were posted on two opposite corners of the physical game board. We distinguished each part of the board with animal names in the range A–I (Ant to Iguana), since the speech recognition was a bit finicky and couldn't easily recognize letter-character combinations such as "A1" or "C3".

# Game Play

<center><img src="cozmo_action.png" width="69%" alt="Cozmo in action" title="Cozmo in Action">
_Cozmo pushing a chip to a named square._</center>

Game play would follow this kind of sequence:
P1: "Cozmo Alpha go to frog."
P1's Cozmo pushes a chip to the "frog square", then returns to its original position.
P2: "Cozmo Bravo go to bear."
P2's Cozmo pushes a chip to the "bear square", then returns to its original position.
...
If P1 or P2 makes a winning move, their Cozmo will recognize that they have just won and it will say, "We did it! We won!"

# Conclusion
Many improvements could still be made to this game. For two players to play this game, two computers need to run the game script, so the Cozmos don't have shared knowledge of the board. Future work could include a global board that can be shared by multiple Cozmos. In addition, improve speech recognition would definitely help improve the quality and smoothness of the game.