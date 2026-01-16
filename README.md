# Fresha Cut

A hair cutting game built for Fresha.

## How to Play

Open the game in your browser:

```bash
open index.html
```

Or double-click `index.html` in Finder.

## Controls

- **SPACE** - Cut the hair
- **ENTER** - Submit score and restart

## Rules

1. Scissors move up and down automatically
2. Press SPACE when scissors are inside the blue target zone
3. Hit the zone = new client, score increases
4. Miss the zone = game over
5. Every 3 clients the difficulty increases (faster scissors, smaller target)

## Leaderboard

The game features a shared leaderboard. Enter your name after each game to save your score!

## Requirements

Any modern web browser (Chrome, Safari, Firefox, Edge).

No server, installation, or build step required - just open the HTML file directly.

## Deploy to GitHub Pages

1. Create a new repository on GitHub:
   ```bash
   git init
   git add .
   git commit -m "Initial commit: Fresha Cut game"
   ```

2. Create a repo on github.com, then push:
   ```bash
   git remote add origin https://github.com/YOUR_USERNAME/fresha-cut.git
   git branch -M main
   git push -u origin main
   ```

3. Enable GitHub Pages:
   - Go to your repo on GitHub
   - Click **Settings** > **Pages**
   - Under "Source", select **main** branch
   - Click **Save**

4. Your game will be live at:
   ```
   https://YOUR_USERNAME.github.io/fresha-cut/
   ```

It usually takes 1-2 minutes for the site to go live after enabling Pages.
