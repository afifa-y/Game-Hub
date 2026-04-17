# Game-Hub
A Game Hub is an app where all your games live in one place. Instead of installing each game separately, you just open the hub, pick a game, and play instantly. It's fast, clean, and simple, like a mini arcade in your pocket, always ready to go.
GAME 1 :
Boom Equation is a timed math puzzle game. The player is shown a target number and must type a valid arithmetic equation that evaluates to that target before the timer expires. The game progresses through multiple levels of increasing difficulty. Scores are stored in a Binary Search Tree (BST)-based leaderboard.
•	Features: Multi-level gameplay, real-time timer, equation validation, BST leaderboard
•	Input: Player name, arithmetic characters (digits and operators)
•	Output: Correct/Wrong feedback, score, leaderboard ranking
•	Real-world use: Online quiz platforms, coding challenge systems

GAME 2: 
A classic snake game where the player controls a snake that grows when it eats food. The snake body is maintained using a queue. The head is added to the front, and the tail is removed from the back unless food is eaten.
•	Features: Real-time movement, food generation, wall and self-collision detection, high score tracking
•	Input: Direction keys (arrow keys or WASD)
•	Output: Updated game grid, score, game over screen
•	Real-world use: Demonstrates queue-based buffer management as used in streaming applications

GAME 3:
Brain Duel is a puzzle battle game where the player faces an AI opponent. Both the player and AI have health points. The player answers puzzles pulled from a priority queue to deal damage to the AI. Time taken to answer affects damage dealt. Puzzles are replenished using a secondary priority queue sorted by difficulty.
•	Features: Turn-based battle system, time-based damage, AI health system, difficulty scaling
•	Input: Puzzle answers, player choices
•	Output: Round results, damage dealt, current HP of both player and AI
•	Real-world use: Adaptive quiz/learning systems, competitive game AI

GAME 4: 
The Escape Game is a maze navigation game where the player navigates through a 2D grid maze using WASD keys. A stack records every move the player makes. If the player wants to undo a move, the stack pops the last position and reverts the player to it. The goal is to reach the exit marked 'E'.
•	Features: Grid-based maze, WASD movement, undo functionality using stack, boundary and wall checking
•	Input: W/A/S/D for movement, U to undo
•	Output: Updated maze with player position, escape confirmation
•	Real-world use: GPS navigation with backtracking, undo systems in editors

GAME 5: 
A classic 9x9 Sudoku game with procedurally generated puzzles based on player level. The player places numbers in cells and the system validates entries. Mistakes reduce the score. Winning the game grants points based on level and mistake count.
•	Features: Level-based puzzle generation, mistake tracking, win/loss detection, scoring system
•	Input: Row, column, and number to place
•	Output: Updated Sudoku board, win/loss notification, score
•	Real-world use: Puzzle game apps, constraint-solving systems


