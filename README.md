# VATSAL SHAH 21BKT0131
# Turn-based Chess-like Game

## Objective
Develop a turn-based chess-like game with a server-client architecture, utilizing websockets for real-time communication and a web-based user interface.
# Game Rules
## Characters and Movement
There are three types of characters available:
 1. **Pawn:**
    Moves one block in any direction (Left, Right, Forward, or Backward).
    Move commands: L (Left), R (Right), F (Forward), B (Backward)
2. **Hero1:**
   Moves two blocks straight in any direction.
   Kills any opponent's character in its path.
   Move commands: L (Left), R (Right), F (Forward), B (Backward)
3. **Hero2:**
    Moves two blocks diagonally in any direction.
    Kills any opponent's character in its path.
    Move commands: FL (Forward-Left), FR (Forward-Right), BL (Backward-Left), BR (Backward-Right)
    All moves are relative to the player's perspective.    

## Screenshots of Testing
![image](https://github.com/user-attachments/assets/b0dcfc9b-d229-49d0-8604-b4a8718e82e9)
![image](https://github.com/user-attachments/assets/4287cd29-7c48-4239-bb27-0e4163304c53)
![image](https://github.com/user-attachments/assets/6f16b1cd-ab81-41ac-bcc6-5c13187e49f4)
![image](https://github.com/user-attachments/assets/54d32a88-2220-4864-9472-c478764ae018)

## Feature

- **Real-Time Multiplayer:** Players connect and play in real-time using WebSockets.
- **Character Types:** Three types of characters (Pawns, Hero1, Hero2) with unique movement and combat abilities.
- **Turn-Based Gameplay:** Players take turns to move their characters, with the goal of eliminating all opponent characters.
- **Game Over Conditions:** The game ends when one player eliminates all of the opponent's characters.

