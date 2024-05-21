**Controls:**
- 0-8         = input number onto board
- right-click = input flag onto board
- x           = delete / reset tile
- t           = opens prompt to change board size to given input (input should be formatted as "10x10")
- i           = opens prompt to import .MINE file
- space       = run ATL.solve() on board 

**Solver Notes:**
- running ATL.solve() multiple times in a row may return new safe cells as it utilizes previously found information to look further
- the solver will usually assume that the given board is valid, which means it will return wrong conclusions if given an invalid board.
- although the solver only works with 1-tiles, it will attempt to use other number tiles as well if adjacent flags are found
