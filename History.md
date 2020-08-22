# Console version

Basic logic adopted from **@JBKahn** [code](https://github.com/JBKahn/Battleship).

Features I liked:

- board size is a variable
- amount of players defined at runtime
- user ships can be placed on the board randomly
- simple console output

Important things added:

- ships can not intersect
- unlimited amount of players (strange feature of course)
- split the monolith code onto small classes (one class - one file)
- game logic in separate python modules

# Graphical version

From **@tmac-balla** I've taken [the engine](https://github.com/tmac-balla/battleship-game) that uses PyGame library and 

* extended logic classes with sprites and fonts
* linked game classes to the engine