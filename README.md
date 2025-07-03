# 🤝 Repeated Prisoner's Dilemma Game – CS50x Final Project

This is an interactive web app built as the final project for [CS50x](https://cs50.harvard.edu/x/), inspired by Robert Axelrod's tournament on the Iterated Prisoner's Dilemma. It lets users play repeated rounds against different AI strategy bots.

---

## 💡 Features

- Play repeated Prisoner's Dilemma against 5+ bots (e.g. Tit-for-Tat, Grim Trigger, Random)
- Live score tracking and history via SQL
- Custom game logic written in Python
- Built using Flask for backend + HTML/CSS frontend

---

## 🧠 Strategy Bots

Each bot follows a different strategy:
-  `Tit-for-Tat`: Cooperates, then mimics your last move
-  `Always Defect`: Always chooses to betray
-  `Grim Trigger`: Cooperates until you defect once, then punishes forever
-  `Random`: 50/50 chance each round
-   Plus 15 more!
-   You can find the code for strategy bots within Game_logic.py

---

## 🚀 Tech Stack

- **Python** — game logic & strategy bots
- **Flask** — server-side framework
- **HTML/CSS** — front-end rendering
- **SQLite** — persistent storage of user scores

---

## 📦 How to Run It

```bash
# Clone the repo
git clone https://github.com/darrenkim05/gametheory.git
cd gametheory

# Create virtual environment (optional)
python3 -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate

# Install Flask
pip install flask

# Run the app
flask run
