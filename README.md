# ✊✋✌️ Rock Paper Scissors — Web‑Based Game

## 📌 Project Overview
This is a classic **Rock Paper Scissors** game built with **HTML**, **CSS**, and **JavaScript**, designed for quick, interactive play between a human and the computer. Players click on their choice, and the computer randomly selects its move. The game then determines the winner, updates the score, and displays a message with the result.

---

## ✨ Features
- 🧑‍🤝‍🧑 **Player vs Computer** — You play against a randomly generated computer move  
- 🧠 **Smart Logic** — Determines win/loss/draw based on standard RPS rules  
- 📊 **Live Scoreboard** — Tracks and displays user and computer scores  
- 💬 **Dynamic Messages** — Shows result of each round with color-coded feedback  
- 🖱️ **Clickable Icons** — Intuitive UI with hover effects and image-based choices  
- 📱 **Responsive Design** — Works well on desktop and mobile screens  

---

## 🗂 Project Structure

```
ROCK-PAPER-SCISSORS/
├── index.html      # Game layout and structure
├── style.css       # Styling and responsive design
├── script logic and score.js       # Game tracking
├── rock.png        # Rock       # Paper icon icon
├── paper.png
└── scissors.png    # Scissors icon
```

---

## 🖼 UI Layout
- **Header** → Displays game title  
- **Choice Buttons** → Rock, Paper, and Scissorsboard** → Shows current icons  
- **Score scores for player and computer  
- **Message Container** → Displays result of each round  

---

## ⚙️ How It Works

### Game Flow
1. Player clicks on Rock, Paper, or Scissors  
2. Computer randomly selects its move  
3. Game compares choices and determines is updated and result outcome  
4. Score message is shown  

### Outcome Logic
- Rock beats Scissors  
- Scissors beats Paper  
- Paper beats Rock  
- Same choice results in a draw  

---

## 📜 JavaScript Highlights

### State Variables = 0;
let compScore = 0;
```

### Core
```js
let userScore Functions
- `genCompChoice()` → Randomly selects computer's move  
- `drawGame()` → Handles draw scenario  
- `showWinner(userWin, userChoice, compChoice)` → Updates score and message  
- `playGame(userChoice)` → Main game logic triggered on user click  

### Event Handling
```js
choices.forEach((choice) => {
  choice.addEvent () => {
    constListener("click", userChoice = choice.getAttribute("id");
    playGame(userChoice);
  });
});
```

---

## 🎨 CSS Highlights
- **Flexbox Layout** — Centers choices and scoreboard  
- **Hover Effects** — Highlights selected choice  
- **Responsive Sizing** — Uses `rem` and percentages for scaling  
- **Color Feedback** — Green for win, red for loss, blue for draw  

---

## 🚀 How to Run
git clone https Locally

```bash:https://github.com/SamiUrRehman065/StonePaperScissorsGame
cd ROCK-PAPER-SCISSORS
```

Then open `index.html` in your browser.

---

## 💡 Possible Improvements
- Add sound effects for win/loss/draw  
- Include animations for selected choices  
- Track win streaks or total rounds played  
- Add reset button to clear scores  
- Implement multiplayer or AI difficulty levels  

---

## 🧑‍💻 Author

**Name:** Sami Ur Rehman  
**Location:** KarachiHub:** [SamiUrRehman065](https, Pakistan  
**Git://github.com/SamiUrRehman065)

---

## 🪞 Developer Reflection

This project helped me reinforce core JavaScript concepts, event handling like DOM manipulation, and conditional logic. I focused on creating a clean, responsive UI and logic was intuitive ensuring the game and bug-free.

### What I Learned
- How to use `querySelector` and `addEventListener` effectively  
- Managing game state and updating the DOM dynamically  
- Structuring code for readability and reusability  

### Challenges I Faced
- Ensuring the score updates correctly without glitches  
- Designing a layout that works well across screen sizes  

### How I Solved Them
I modularized the logic into small functions and used consistent styling with Flexbox. Testing each interaction helped me catch edge cases and polish### Why It Matters for My Portfolio the experience.


This project shows my ability to build apps with clean interactive web logic and user-friendly design. It’s a great example of combining front-end skills with game mechanics.

---
```

Let me know if you’d like to add preview images, badges, or a live demo link. I can also help you write a `reflection.md GitHub repo presentation` or polish your!
