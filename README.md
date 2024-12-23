# Snake
Snake game that was written in C as part of a team along with Raymond Torres as a project for CS-355 Systems Programming.

## The snake pit:


- [x] The snake pit is the area where the snake can move.


- [x] The snake pit must utilize all available space of the current terminal window.


- [x] There must be a visible border delineating the snake pit.


## The snake:


- [x] The initial length of the snake is five characters.


- [x] Initial direction of the snake's movement is chosen randomly.


- [x] The user can press one of the four arrow keys to change the direction of the snake's movement.


- [x] The snake's speed is proportional to its length.


## The trophies:


- [x] Trophies are represented by a digit randomly chosen from 1 to 9.


- [x] There's always exactly one trophy in the snake pit at any given moment.


- [x] When the snake eats the trophy, its length is increased by the corresponding number of characters.


- [x] A trophy expires after a random interval from 1 to 15 seconds.


- [x] A new trophy is shown at a random location on the screen after the previous one has either expired or is eaten by the snake.


## The gameplay:


The snake dies and the game ends if:


- [x] It runs into the border; or


- [x] It runs into itself; or


- [x] The user attempts to reverse the snake's direction.

- [x] The user wins the game if the snake's length grows to the length equal to half the perimeter of the border.
