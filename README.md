# Space Invaders

### Software Design Documentation

Project Name: Space Invaders<br/>
Development Language: Python<br/><br/>
Developed By: Jones Jenkins<br/><br/><br/><br/>

1. Introduction<br/>
   1. Purpose<br/>
      a. This project documentation contains the Concept, How-To-Steps, and References for the game, Space Invaders, designed in Python. This document is intended for developers and end users.<br/>
   2. Scope<br/>
      a. This game is based on the classic game, Space Invaders. The user moves a spaceship left and right to shoot and destroy incoming aliens. The game ends when the aliens reach the spaceship and destroy it.<br/>
   3. Overview<br/>
      a. This document contains:<br/>
         * Concept<br/>
         * How-To-Steps<br/>
   4. Resources<br/>
      a. The following resources were used in the production of this software application:<br/>
         * https://www.pygame.org/docs/: Pygame reference index including basic information, installation steps, and tutorials<br/>


2. Concept<br/>
   * This application is an iteration of the classic game Space Invaders. It consists of one screen where the user controls a ship to shoot and destroy incoming aliens. The player’s spaceship is located at the bottom of the screen and fires missiles vertically at the aliens. There are five aliens that move left and right across the screen. Once the aliens reach either side of the window, they move a step down the screen and proceed to the other side of the screen horizontally. The game ends when the aliens move down the entire window and reach the player’s spaceship.<br/>
   * The sprites in the game were all custom made using Gimp:<br/>
     * Alien:<br/>
     * Spaceship:<br/>


3. How-To-Steps<br/>
   1. Open the project in a Python interpreter and run “SpaceInvaders.py”.<br/>
   2. Use the right and left arrow keys to move the spaceship left and right.<br/>
      * Right:<br/>
      * Left:<br/>
   3. Press the spacebar to fire missiles.<br/>
   4. The player’s score increases by 10 for every alien destroyed.<br/>
      * (Nine aliens were destroyed):<br/>
   5. Left click on the close icon in the upper right corner of the window to quit the game when finished.<br/>
