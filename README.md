# 🏓 Pickleball Arena

A 1v1 browser pickleball game featuring the crew.

## Players
Mark · Ian · Earl · Arnel · Martin

## How to Play
1. Open `index.html` in a browser (use a local server — see below)
2. Pick your player
3. Face a random opponent
4. **Move your mouse** to control your paddle
5. **Click** to serve the ball
6. First to **11 points** wins

## Adding / Updating Player Photos
Drop images into the `players/` folder with these exact filenames:
```
players/ian.jpg
players/arnel.jpg
players/mark.jpg
players/martin.jpg
players/earl.jpg
```
JPEG format recommended. Any resolution works — the game crops to the face automatically.

## Running Locally
Because the game loads images via canvas, you need a simple HTTP server:

```bash
# Python 3
python3 -m http.server 8080
# then open http://localhost:8080
```
Or use VS Code's **Live Server** extension — right-click `index.html` → *Open with Live Server*.
