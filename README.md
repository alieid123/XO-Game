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

## 🎯 How the Minimax Algorithm Works

The **Minimax** algorithm is used in turn-based games like Tic Tac Toe.  
Its goal is to **choose the best possible move for the player** while **minimizing the opponent’s chances of winning**.

### 📌 Steps:
1. **Start from the current board state** → Generate all possible moves.
2. **Simulate each move** → Temporarily make the move and see how the game could progress.
3. On the **opponent’s turn**, choose the move that *minimizes* the player’s score.
4. **Repeat** alternately between player and opponent until the game ends (win, draw, or loss).
5. **Assign a final score**:
   - **+10** → Win  
   - **0** → Draw  
   - **-10** → Loss

---

### 💡 Hard Mode
In **Hard mode**, the AI evaluates all possible future scenarios and always picks the move with the **best guaranteed outcome**.  
It uses **Alpha-Beta Pruning** to skip unnecessary calculations and improve performance.


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

