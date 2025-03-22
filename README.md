# 🐷 Pig Game

This is a simple 2-player **Pig Dice Game** built using **HTML**, **CSS**, and **JavaScript**.

## 🎯 Objective

The goal is to be the first player to reach **20 points**. On your turn, roll the dice as many times as you like to build up your score — but if you roll a **1**, you lose all points from that turn!

---

## 🛠️ Features

- Two-player turn-based gameplay
- Rolling the dice and accumulating current score
- Holding the score to add it to the global score
- Switching turns when a 1 is rolled or "Hold" is clicked
- Visual feedback for active player and winner
- "New Game" button to restart the game

---

## 📂 Project Structure
```

.
├── index.html # Game layout
├── style.css # Styling and animations
└── script.js # Game logic and interactivity

```

---

## 🎮 How to Play

1. Open the `index.html` file in your browser.
2. Player 1 starts by clicking **"🎲 Roll Dice"**.
3. The dice shows a number between 1 and 6:
   - If it's not 1, the number is added to the current turn's score.
   - If it's 1, the player loses their turn and score resets for the round.
4. Click **"📥 Hold"** to save your current score and pass the turn.
5. First player to reach **20 points** wins.
6. Click **"🔄 New Game"** to play again.

---

## images

![image_2025-03-22_23-22-25](https://github.com/user-attachments/assets/57574780-6b43-4d52-98be-950a898d3cac)

---

## 🧠 What I Learned

- Event-driven programming with JavaScript
- Managing state in a multi-player game
- Updating the DOM dynamically based on game logic
- Creating reusable functions like `init()` and `switchPlayer()`
- Applying CSS transitions and effects for better UI

---

## 📚 Acknowledgements

This project is part of the **[JavaScript course by Jonas Schmedtmann](https://www.udemy.com/course/the-complete-javascript-course/)**. A great hands-on way to learn the language through practical mini-games.

---

## 🙋‍♂️ About Me

Hi! I’m [zdvman](https://github.com/zdvman), currently learning full-stack web development.

- 🔗 [GitHub](https://github.com/zdvman)
- 💼 [LinkedIn](https://www.linkedin.com/in/zdvman/)

---

Thanks for playing the Pig Game! 🐽🎲
