# Post-tac-toe
Post-tac-toe is a generalized tic-tac-toe game written in the stack based language [PostScript](https://en.wikipedia.org/wiki/PostScript).

The game is generalized in that it is an m,n,k,l-game (similar to the [m,n,k-game](https://en.wikipedia.org/wiki/M,n,k-game)) where
- m stands for the number of rows of the field
- n stands for the number of columns of the field
- k stands for the number of marks in a row, column or diagonal a player needs to win the game
- l stands for the number of players

This implementation also supports the [random turn](https://en.wikipedia.org/wiki/Tic-tac-toe_variants#Random_turn_tic-tac-toe) feature.

## Dependencies

You need to have **ghostscript** installed.

### Linux

On most Linux distributions the package ist called `ghostscript`.

### Windows

On Windows install the binary from https://www.ghostscript.com/download/gsdnld.html.

## Start the game

### Linux

Just run `gsx post-tac-toe.ps` in a terminal with an X window environment.

### Windows

Start a `cmd.exe` command line and run `<path-to-ghostscript-install-dir>\bin\gswin64.exe post-tac-toe.ps`.

## References
- https://en.wikipedia.org/wiki/PostScript
- https://en.wikipedia.org/wiki/Tic-tac-toe
- https://en.wikipedia.org/wiki/Tic-tac-toe_variants
- https://en.wikipedia.org/wiki/M,n,k-game
