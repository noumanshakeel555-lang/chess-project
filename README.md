♟️ Chess Game with AI (Flask Web App)

A fully functional web-based Chess Game built using Python and Flask, featuring both Player vs Player and Player vs AI modes.

This project combines backend game logic with a clean frontend interface, allowing users to play chess directly in the browser.

🚀 Features

♟️ Player vs Player (Local 2-Player Mode)

🤖 Player vs AI Mode

Legal move validation for all pieces

Turn-based game logic

Interactive chessboard UI

Real-time move updates

Game state management

Responsive frontend design

🧠 AI Functionality

The AI opponent:

Evaluates board positions

Selects moves based on game-state evaluation

Automatically responds to player moves

Simulates strategic gameplay

This demonstrates:

Basic game-tree evaluation

Decision-making logic

Automated opponent behavior

🛠 Tech Stack

Backend: Python, Flask

Frontend: HTML, CSS, JavaScript

Architecture: Flask templates + static file structure

📂 Project Structure
chess-game/
│
├── app.py
├── requirements.txt
├── README.md
│
├── templates/
│   └── index.html
│
├── static/
│   ├── css/
│   │   └── style.css
│   └── js/
│       └── script.js
⚙️ Installation & Setup
1️⃣ Clone the Repository
git clone https://github.com/your-username/chess-game.git
cd chess-game
2️⃣ Create Virtual Environment (Optional but Recommended)
python -m venv venv

Activate it:

Windows

venv\Scripts\activate

Mac/Linux

source venv/bin/activate
3️⃣ Install Dependencies
pip install -r requirements.txt

If requirements.txt is empty, make sure it includes:

flask
4️⃣ Run the Application
python app.py

Then open your browser and visit:

http://127.0.0.1:5000
🎯 What This Project Demonstrates

Game logic implementation

Turn-based system design

AI integration into a web app

Flask routing and template rendering

Frontend–backend communication

Clean project structure

🔮 Future Improvements

Improved AI using Minimax with Alpha-Beta pruning

Difficulty levels

Online multiplayer support

Move history tracking

Game save/load functionality

📌 Author

Developed as a learning project to strengthen understanding of:

Python backend development

AI fundamentals

Web application architecture

Interactive UI design
