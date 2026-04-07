# 🪨📄✂️ Modern Rock Paper Scissors

A sleek, full-stack Rock Paper Scissors web application built with **Python (Flask)** and **Vanilla JavaScript**. This isn't just a simple one-off game; it features a "Best of" match system, win streaks, real-time CPU "thinking" animations, and a bit of a spicy personality.


## ✨ Features

* **Match Modes:** Choose between **Best of 3** (2 wins to clinch) or **Best of 5** (3 wins to clinch).
* **Dynamic Scoreboard:** Tracks total wins, losses, ties, and your current vs. best ever win streak.
* **Visual Feedback:** * Smooth CSS animations and "shake" effects on losses.
    * Confetti celebrations using `canvas-confetti` for match victories.
    * CPU "Thinking" state to simulate real-time play.
* **Round History:** Keeps a rolling log of the last 5 rounds played.
* **The "Taunt" System:** A randomized set of messages from the CPU when you lose (e.g., "skill issue ngl" or "Too slow! 😈").
* **Responsive Design:** Dark-mode aesthetic with a "Glassmorphism" inspired UI, styled with custom grid backgrounds and the *Bebas Neue* typeface.

## 🛠️ Tech Stack

* **Backend:** Flask (Python)
* **Frontend:** HTML5, CSS3 (Flexbox/Grid), JavaScript (Fetch API)
* **Libraries:** [Canvas Confetti](https://www.npmjs.com/package/canvas-confetti) for animations.

## 🚀 Getting Started

### Prerequisites
* Python 3.x
* Flask

### Installation
1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/your-username/rock-paper-scissors.git](https://github.com/your-username/rock-paper-scissors.git)
    cd rock-paper-scissors
    ```

2.  **Install dependencies:**
    ```bash
    pip install flask
    ```

3.  **Run the application:**
    ```bash
    python app.py
    ```

4.  **Play!**
    Open your browser and navigate to `http://127.0.0.1:5000`.




## 🎮 How to Play

* **Select Match Mode**: Choose your preferred match length (Best of 3 or Best of 5) at the top of the interface.
* **Make Your Move**: Click on the **Rock**, **Paper**, or **Scissors** buttons to play a round.
* **Track Progress**: Watch the **Match Progress** dots fill up as you or the CPU win rounds toward the match total.
* **Win or Lose**: Win the match to trigger a **confetti celebration**, or lose to face randomized **CPU taunts**.


## 📂 Project Structure ##

```text
├── app.py              # Flask backend: handles game logic & state
├── static/
│   ├── styling.css     # Custom UI styling & animations
│   └── script.js       # Frontend logic, Fetch calls, and UI updates
└── templates/
    └── rps.html        # Main game interface
```
## ✍️ Author

* **Aadit Shah** — *Main Developer* — [GitHub Profile](https://github.com/your-username)
