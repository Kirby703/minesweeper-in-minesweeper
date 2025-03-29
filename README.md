# minesweeper-in-minesweeper
Building Minesweeper in Minesweeper, for SIGBOVIK 2025

To play the board yourself:
1. Go to https://davidnhill.github.io/JSMinesweeper
2. Disable the automatic solver, or your browser _will_ grind to a halt. To do this, set the "Overlay" dropdown to "None", the "Show hints" checkbox to off, and "Auto play" to off.
3. (technically optional) Turn "Fast mode" on. This will take some game actions for you, but just the boring ones that require only a single safe cell's information.
4. Download minesweeper_in_minesweeper.mine and drag it onto the board.
5. If it breaks in Chrome, try Firefox. This is a case of "I only tested it in my browser" from a Firefox user. Chrome appears to immediately run out of memory upon trying to render the 693x693 board onto one canvas, but Firefox only renders the part of the canvas that's visible at a given moment. It will need time to render the board anytime you scroll, unfortunately.

How did I do this? The answers are in the pdf! I also wrote a few tiny scripts to copy/paste and rotate regions of the board, and a solver to determine where the hidden mines are.
