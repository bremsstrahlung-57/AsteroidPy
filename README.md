# Asteroids Game

A classic Asteroids arcade game implementation using Python and Pygame.

## Description

This is a recreation of the classic Asteroids arcade game where players control a triangular spaceship and shoot incoming asteroids while avoiding collisions. The game features:

- Player-controlled spaceship with rotation and thrust
- Shooting mechanism with cooldown
- Asteroids that split into smaller pieces when shot
- Progressive difficulty with continuous asteroid spawning

## Requirements

- Python 3.x
- Pygame 2.6.1

## Installation

1. Clone this repository
2. Create a virtual environment (optional but recommended):
```
python -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate
```
3. Install the required packages:
```
pip install -r requirements.txt
```

## How to Play

Run the game:
```
python main.py
```

### Controls

- `W` - Move forward
- `A` - Rotate left
- `D` - Rotate right
- `SPACE` - Shoot

### Game Rules

- Control your spaceship and shoot the incoming asteroids
- Large asteroids split into smaller ones when hit
- Avoid colliding with asteroids
- Game ends if your ship collides with an asteroid

## Project Structure

- [main.py](vscode-file://vscode-app/c:/Users/DELL/AppData/Local/Programs/Microsoft%20VS%20Code/resources/app/out/vs/code/electron-sandbox/workbench/workbench.html) - Game entry point and main loop
- [player.py](vscode-file://vscode-app/c:/Users/DELL/AppData/Local/Programs/Microsoft%20VS%20Code/resources/app/out/vs/code/electron-sandbox/workbench/workbench.html) - Player spaceship implementation
- [asteroid.py](vscode-file://vscode-app/c:/Users/DELL/AppData/Local/Programs/Microsoft%20VS%20Code/resources/app/out/vs/code/electron-sandbox/workbench/workbench.html) - Asteroid object implementation
- [asteroidfield.py](vscode-file://vscode-app/c:/Users/DELL/AppData/Local/Programs/Microsoft%20VS%20Code/resources/app/out/vs/code/electron-sandbox/workbench/workbench.html) - Asteroid spawning system
- [shot.py](vscode-file://vscode-app/c:/Users/DELL/AppData/Local/Programs/Microsoft%20VS%20Code/resources/app/out/vs/code/electron-sandbox/workbench/workbench.html) - Projectile implementation
- [circleshape.py](vscode-file://vscode-app/c:/Users/DELL/AppData/Local/Programs/Microsoft%20VS%20Code/resources/app/out/vs/code/electron-sandbox/workbench/workbench.html) - Base class for circular objects
- [constants.py](vscode-file://vscode-app/c:/Users/DELL/AppData/Local/Programs/Microsoft%20VS%20Code/resources/app/out/vs/code/electron-sandbox/workbench/workbench.html) - Game constants and configuration

## License

This project is available under the MIT License.

```
MIT License

Copyright (c) 2025 Sagar Sharma

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```