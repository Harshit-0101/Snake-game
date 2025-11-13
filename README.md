# Snake Game

A simple classic Snake game built with **HTML**, **CSS** and **JavaScript**.  
Open `index.html` in your browser to play.  
Live demo: https://snake-game-blond-zeta.vercel.app/ . :contentReference[oaicite:1]{index=1}

---

## Features
- Classic snake gameplay: eat food to grow, avoid collisions with walls/self
- Lightweight — vanilla HTML/CSS/JS, no build step
- Works locally by opening `index.html` or by deploying to GitHub Pages / Vercel

---

## Files
- `index.html` — game markup and container.
- `style.css` — styling for the board & UI.
- `script.js` — game logic (movement, food, scoring, collision detection).
(These files are included in the repository.) :contentReference[oaicite:2]{index=2}

---

## How to run (locally)
1. Clone the repo:
   ```bash
   git clone https://github.com/Harshit-0101/Snake-game.git
   cd Snake-game
Open the game:

Double-click index.html or

Serve it locally (recommended if your browser blocks local scripts):

bash
Copy code
# using a simple static server (Node.js)
npx http-server .
# or (Python 3)
python -m http.server 8000
Visit http://localhost:8080 (or http://localhost:8000) in your browser.

Controls
Use arrow keys (← ↑ → ↓) to move the snake.

(If implemented) W A S D may work as alternatives — check script.js for exact key bindings.

Gameplay / Rules
Eat the food to grow and increase your score.

Hitting the walls (or your snake body) ends the game.

Try to beat your high score!

Screenshots
(Add a screenshot of the game here — create a screenshots/ folder and include screenshot.png for best presentation.)

markdown
Copy code
![Gameplay screenshot](screenshots/screenshot.png)
Deploying
GitHub Pages: Push the repo to GitHub and enable Pages from main branch → / (root).

Vercel / Netlify: Connect the repo — they auto-deploy static sites containing index.html.

The repo already links to a Vercel demo. 
GitHub

Contributing
Contributions are welcome! Suggestions:

Add pause/resume and restart buttons

Add mobile/touch controls

Add difficulty levels and speed increase with score

Save high scores using localStorage

If you want to contribute:

Fork the repo

Create a branch: git checkout -b feature/your-feature

Commit: git commit -m "Add feature"

Push & open a Pull Request

License
No license file detected in the repo. If you want others to freely use and contribute, add a license such as MIT.
Example LICENSE (MIT):

sql
Copy code
MIT License

Copyright (c) <YEAR> <OWNER>

Permission is hereby granted, free of charge, to any person obtaining a copy...
Author
Harshit-0101 — original repository. 
