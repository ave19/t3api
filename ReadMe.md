Golang powered rest api for interacting with persistent strategies.

Each strategy will implement things like:

- /move/x
- /move/o
	given a board, choose a square for x or o
- /win
- /lose
- /draw
	record the results of a game.
