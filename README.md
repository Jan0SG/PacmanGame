# Pacman Game
This project was done by a team of 3 members. Coded in C#.

## Number Assignment
0 = Blankspace
1 = Pellet
2 = Walls
3 = Door
5 = Pacman
6 = Portal Blue
7 = Portal Orange
8 = Ghost 1
9 = Ghost 2
10 = Ghost 3
11 = Ghost 4


# How does it work?
The game has the same goal as the original Pacman where all the pellets must be eaten before completing the level.
This project has 3 levels that change whenever all the pellets have been eaten.
### NOTE: The counter condition that changes the map is fixated whenever 150 pellets are eaten, this can be modified as well as the map layout.

## Map
The map was created by utiilizing a matrix for each level where each number represents the enemies, the player, the pellets, the blank spaces, the portals and the walls.

## Pacman
A player was added represented by Pacman. Before each movement, the number assigned to Pacman will check the direction it was requested to move to recognize what number is in the position it desires to move. Depending on the number, a collision, changing the value of the number, leaving the value and even causing a Game Over can happen.

## Enemies
Four ghost were added for the purpose of having a Game Over.
The game ends either by completing the 3 levels or by having a collision between the ghosts and Pacman; it can be either way the collision for it to happen.

## Portal
A portal was added in the X axis and can be accesed through both ends.

