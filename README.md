Seega: Ancient Egyptian Abstract Strategy Game

Seega is an authentic, web-based adaptation of the ancient Egyptian abstract strategy game, a historical two-player board game played since at least the 19th century. This project faithfully recreates the classic 5x5 Khamsáwee ruleset, providing an engaging digital experience for players and developers interested in cultural games and game AI.

Overview
This implementation is built using pure HTML, CSS, and JavaScript, making it a highly accessible and lightweight browser application. It meticulously follows the original game mechanics, divided into two distinct phases:

The Placement Phase: Players strategically place their 12 pieces onto the 5x5 board, excluding the central, 'safe' square. This initial phase sets the foundation for the tactical battle to come.

The Movement & Capture Phase: Pieces move orthogonally to an adjacent empty square. Captures are executed via custodial capture, where an opponent’s piece is removed when flanked by two of the player's pieces. The central square grants immunity from capture.

Key Features
Purity: Developed without external libraries or frameworks, ensuring maximum performance and ease of maintenance.

Game AI: Includes a robust, tiered Artificial Intelligence (AI) system. The CPU opponent employs the Minimax algorithm with Alpha-Beta Pruning to simulate increasingly challenging strategic depth.

Modern Design: Features a responsive, mobile-friendly interface designed with contemporary CSS practices.

Game Modes: Supports both Human vs. Human (local multiplayer) and Human vs. CPU modes with adjustable difficulty settings.

Technology Stack
Frontend: HTML, CSS, JavaScript

Algorithm: Minimax with Alpha-Beta Pruning (for the CPU Player)

This repository serves as both a playable digital artifact and a resource for studying classical board game logic and algorithm implementation. Contributions and feedback are welcome!
