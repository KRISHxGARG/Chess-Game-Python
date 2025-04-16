# ♟️ Python Chess Game – Text-Based Console Application

---

## 📌 Overview

This project is a **text-based Chess game** developed in **Python** as part of a mini project to demonstrate the practical application of **Object-Oriented Programming (OOP)** concepts. Designed for two human players, the game runs in a terminal environment and simulates real chess gameplay, including move validation, turn-based flow, and detection of check and checkmate conditions.

The Chess game is built with a modular and scalable structure, making it a great foundation for future enhancements like a graphical user interface or AI opponents.

---

## 🎯 Objectives

- ✅ Build a fully functional console-based Chess game for two players
- ✅ Use OOP principles (inheritance, abstraction, encapsulation, and polymorphism)
- ✅ Implement movement logic for each piece (Pawn, Rook, Knight, Bishop, Queen, King)
- ✅ Handle turn-based logic and validate legal moves
- ✅ Detect game-ending states like **check** and **checkmate**
- ✅ Provide user interaction through simple text-based commands

---

## 🔍 Key Insights & Analysis

### 🧱 Code Design
- **Object-Oriented Architecture**: Each piece is represented as a class inheriting from a base `Piece` class. Movement validation is defined through method overriding.
- **Game Control**: A central `Game` controller handles the alternation of turns, move validation, and endgame conditions.
- **Board Management**: The `Board` class creates and updates an 8x8 grid representing piece positions, allowing for visual board refreshes after each move.

### 💡 Functional Highlights
- Movement logic strictly adheres to chess rules
- Displays real-time board updates
- Captures invalid moves and provides error messages
- Detects **check**, **checkmate**, and **stalemate**

### 🧪 Development Experience
- Developed in **Jupyter Notebook** for interactive testing
- Future-proofed with consideration for GUI and AI integration
- Focused on both functionality and user experience

---

## ✅ Recommendations

Based on the current implementation and challenges faced, the following steps are recommended to take this project further:

1. **Graphical User Interface (GUI)**  
   Use libraries like **Pygame** or **Tkinter** to provide drag-and-drop interactions, visual feedback, and a more intuitive playing experience.

2. **AI Opponent**  
   Introduce single-player mode using algorithms like **Minimax** with alpha-beta pruning to allow users to play against the computer.

3. **Online Multiplayer Mode**  
   Enable networked gameplay using Python sockets or REST APIs to support remote two-player matches.

4. **Save/Load Game State**  
   Implement functionality to store and resume games using serialization (e.g., pickle or JSON format).

5. **Code Optimization & Testing**  
   Introduce unit testing for movement logic and edge cases to improve robustness and ensure long-term maintainability.

---

## 📬 Contact

For any querries reach out to:
<br>
**-Name-** Krish Garg
<br>
**-Email-** krishgarg665@gmail.com
