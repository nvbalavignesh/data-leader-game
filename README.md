# Who's the Best CDO?

This repo contains a simple prototype web game where you take on the role of a Chief Data Officer (CDO). The game logic and UI are contained in a single `index.html` file. The interface uses a clean Roboto font and displays a timeline of your choices so you can easily review your progress.

## Running the Game

1. Clone or download the repository.
2. Open `index.html` directly in a modern web browser (Chrome, Firefox, Edge). No build step is required.

Alternatively, you can serve the file locally to avoid any browser security restrictions:

```bash
# from the repository root
python3 -m http.server
```

Then open `http://localhost:8000` in your browser and click `index.html`.

That's it! The game will present you with email scenarios. Choose responses to see how they affect your budget, profit, data quality and reputation.
It now shows each scenario on a timeline so you can track decisions over time.

## Features

- Professional layout with Google Roboto font
- Timeline records each email decision
- Metrics update instantly as you play
