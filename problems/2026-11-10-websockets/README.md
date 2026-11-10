# WebSockets: Tic Tac Toe

## Problem Description

Intro to WebSockets with a two-player tic tac toe game.

### Requirements

1. Implements standard tic tac toe rules and interaction (e.g. only current player can place a mark)
2. A server that handles `move` messages and broadcasts the new state
3. A web page that shows the board, allows player interaction, and sends moves

## Tests

Suggested tests:
- placing a mark on an empty square succeeds
- placing a mark on a taken square or outside the board is rejected
- a player cannot move out of turn
- three in a row (row, column or diagonal) wins
- a full board with no winner is a draw

## Resources

- [websockets (Python library)](https://websockets.readthedocs.io/)

## Solutions

Any solutions go in the `solutions/` subdirectory.
