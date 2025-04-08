[![Open in Codespaces](https://classroom.github.com/assets/launch-codespace-2972f46106e565e64193e422d61a12cf1da4916b45550586e14ef0a7c637dd04.svg)](https://classroom.github.com/open-in-codespaces?assignment_repo_id=19078898)
# cpp_tictactoe_tree
## Part 1: Questions

**What is the purpose of the minimax function?**  
The minimax function is used to simulate all possible future moves and outcomes in a Tic-Tac-Toe game to determine the best move for the AI. It assumes both players play optimally and recursively calculates the score of each possible game state.

**How does the GameState class represent the tree?**  
The GameState class represents the nodes of the decision tree. Each time `makeMove` is called, it creates a new GameState object representing a child node (i.e., the game state after a move). The tree is formed by recursively generating new GameState objects for all available moves.

**When does the recursion stop in the minimax algorithm?**  
Recursion stops when a terminal state is reached — either one player has won (`checkWinner` returns `X` or `O`) or the board is full (draw).
## Part 3: Reflection

This project taught me how recursion is used to simulate future decisions in games through decision trees. I saw how the minimax algorithm navigates these trees to find optimal moves. The AI was smart and rarely made mistakes, but with a depth limit, it sometimes missed perfect plays. With more time, I would implement alpha-beta pruning to optimize performance and maybe build a GUI for a better user experience.
