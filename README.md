[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/pI6im86_)
[![Open in Codespaces](https://classroom.github.com/assets/launch-codespace-2972f46106e565e64193e422d61a12cf1da4916b45550586e14ef0a7c637dd04.svg)](https://classroom.github.com/open-in-codespaces?assignment_repo_id=22164283)
# NeXtCS Final Project
### Name 0: Crystal
### Name 1: Joshua
### Name 2: Jimmy
---

### Project Description
We will be recreating candy crush(<img width="1024" height="768" alt="image" src="https://github.com/user-attachments/assets/11655dc0-a2a3-4f82-ac62-ffeac4743aee" />) instead of candy we'll be immplementing geometric shapes such as squares, circles, triangles, elipses, rectangles. The goal of the game is to gain maximum points within a time or move limit. Getting more in a row gives you power ups and more points. 


### Skill Usage
-2D arrays: grid of tiles for the board

-1D arrays: geometric shapes

-arrayList: 

-Classes

-functions for game functionality

-Globals for booleans, score

### Controls
How will your program be controlled? List all keyboard commands and mouse interactions.


Keyboard Commands:
- R: to restart the game

- 1: to set it to timer mode

- 2: to set it to move mode

Mouse Control:
- Mouse pressed: Selects the piece to be moved. If a piece is already selected, check if it is a neighbor(not diagonal). If it is attempt to switch the tiles, and if not then override the selection to the new piece.


### Classes
What classes will you be creating for this project? Include the instance variables and methods that you believe you will need. You will be required to create at least 2 different classes. If you are going to use classes similar to those we've made for previous assignments, you will have to add new features to them.
# Tile(individual pieces)
vars:

int shape

int size

display(shows the shape and the tile)

# Board(grid of tiles)
int rows

int cols

checkMatch

display
