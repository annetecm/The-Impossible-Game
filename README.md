# The Impossible Game
A level progression game in which the player has to avoid enemies to pass the map level. The player character is controled with the keyboards a,d,w,s. 

# Project Features
* The game simulates an environment where a player-controlled red square navigates through levels filled with walls, enemies, and a winning cube.
* The player’s movement is controlled via keyboard inputs, allowing for adjustments in speed and direction using the Player class.
* The Player object interacts with walls, enemies, and a winning cube, with collision detection that determines outcomes such as player deaths or victory.
* Enemies move in either single or multiple steps using predefined paths, stablished by the Enemy class, and dynamically update their position.
* The game features multiple levels, each with different respawn points, wall configurations, enemy placements, and a winning cube.
* A death counter tracks the number of times the player has died, and is displayed on-screen during gameplay.
* Upon completing the game or reaching a stopping point, a high-score system updates and displays the top scores, based on player performance and deaths.
* The background, object positions, and other elements are rendered using pygame, and gameplay runs at a constant frame rate using the pygame clock.
