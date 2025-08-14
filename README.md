# 🎮 Tic Tac Toe with AI

A modern **Tic Tac Toe** game built with C# and Windows Forms, supporting both **Player vs Player** and **Player vs Computer** modes.  
The AI uses the **Minimax Algorithm** with optional **Alpha-Beta Pruning** to make optimal moves, and includes multiple difficulty levels for more fun and challenge.

---

## 🚀 Features
- **Player vs Player** mode (local multiplayer).
- **Player vs Computer** mode with:
  - Easy difficulty (random moves).
  - Medium difficulty (simple heuristics).
  - Hard difficulty (Minimax Algorithm with Alpha-Beta Pruning).
- Dynamic board status and real-time move validation.
- Visual highlights for winning moves.
- Clean and responsive Windows Forms UI.

---

## 🛠️ Technologies Used
- **C# (.NET Framework)**
- **Windows Forms**
- **Object-Oriented Programming (OOP)**
- **Minimax Algorithm** with Alpha-Beta Pruning (for AI logic)

---

## 🎥 Demo Video
You can watch the gameplay demo video here:  
[🎬 Click to play demo](videos/demo.mp4)

*(The video file is included in the repository under `videos/`)*

---

## 📂 Project Structure

## 🧠 How Minimax Algorithm Works
The **Minimax Algorithm** is a decision-making algorithm for turn-based games like Tic Tac Toe.  
It tries to **maximize** the player's score and **minimize** the opponent's score.


        Current Board
              ↓
      ┌────────────────┐
      │ Generate all    │
      │ possible moves  │
      └────────────────┘
              ↓
      ┌────────────────┐
      │ Simulate each   │
      │ move recursively│
      └────────────────┘
              ↓
 ┌────────────┴────────────┐
 │ Opponent's turn: choose │
 │ move that minimizes     │
 │ player's score          │
 └────────────┬────────────┘
              ↓
   Repeat until game over
              ↓
      Assign score:
      +10 → Win
       0  → Draw
      -10 → Loss


In **Hard** mode, the AI will always choose the move with the best possible outcome  
by evaluating all future moves using Minimax (with Alpha-Beta Pruning to optimize performance).

---

## 🎯 How to Play
1. Choose game mode (Player vs Player / Player vs Computer).
2. If playing against the computer, select difficulty.
3. Take turns placing your symbol (X or O) on the board.
4. First to align 3 in a row, column, or diagonal wins.

---

## 📌 Future Improvements
- Online multiplayer support.
- Animated transitions and sound effects.
- Score tracking system.

