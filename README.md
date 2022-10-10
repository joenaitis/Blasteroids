# Blasteroids

I designed a one-player game similar to Asteroids by Atari, Inc.  The program uses three classes for images, the spaceship, and the asteroids/missiles.  Primary functions include key handlers, a draw function, an asteroid spawner, and functions to test for collisions between missiles and asteroids and the ship and asteroids.  The program runs using three imported packages, simpleguitk, math, and random.

To begin the game and exit the splash screen, a player needs to click the mouse.  The player can move the spaceship forward using the forward arrow key and can turn the spaceship using the left or right arrow key.  The spacebar fires missiles.  Points are awarded when a missile hits an asteroid.  If an asteroid hits the spaceship, one life is lost.  A player starts with 3 lives.  Up to 10 asteroids are generated at a time, one per second, and all with varying forward velocity, spin velocity, and spin direction.  As the player destroys more asteroids and moves up in levels in the game, the asteroids increase in velocity.  

My next step on this program is to add the image of a explosion when a missile hits an asteroid or an asteroid hits a spaceship.  After the program was working in CodeSkulptor (an interactive, web-based Python programming environment that allows Python code to be run in a web browser), I ran into an issue in which the spaceship remained in thrust or turned left when the forward arrow key or left arrow key were pressed.  I need to debug this issue and suspect it is an issue with either an update to CodeSkulptor or Google Chrome since a similar issue appeared wtih another program and since this program was originally working for a couple months.

Additionally, I uncovered another bug when the program was implemented in the IDE PyCharm Community. Specifically the program is having trouble drawing asteroids (and missiles since they are in the same class).  For now, I have commented out where asteroids are drawn at line 339 under def process_sprite_group

See my code in this repository or click https://py2.codeskulptor.org/#user49_YedwzqGkFE_1.py to run this program in CodeSkulptor.
