# DX Ball

A brick-breaker game written in C using raylib.

## Requirements
- gcc (or clang) and make
- raylib

Install raylib:
- macOS: `brew install raylib`
- Linux: install raylib and its dev packages (OpenGL, X11)
- Windows: install raylib with MinGW

## Compile
make

## Run
- macOS/Linux: `./dxball`
- Windows: `dxball.exe`

## Setup notes
- Keep the `resources` folder and `highscores.txt` in the same folder as the program.
- Run the game from the project folder so it can find the sounds and images.
- `make clean` deletes the executable and also resets `highscores.txt`.

## Controls
- Left / Right arrow keys: move the paddle
- Space: launch the ball
