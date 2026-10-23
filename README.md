# Skyshard Companion

A desktop companion for the Steam game Skyshard. It reads your island from the log and from your game window and tells you which units and shops fit your board.

The app watches `%APPDATA%\Project SkyShard\logs\godot.log`. If your log is somewhere else, use **Choose log file…**.

## What it shows

- **My island**: the board as the companion currently understands it. When the log is updated it pulls the data from there, but in between log updates it relies on image recognition from your Skyshard game window. You can click on a unit to show its details.
- **Units to look for**: shop units ranked by their value to your island.
- **Shop picks**: the shops on offer, ranked by the average value of the units each can offer (default), or by the chance each offers one of your top 15 suggestions.
- **Latest shop**: reads the shop you open in the game from the screen, marks the best pick for your board, and adds the unit you take to "Bought this round".
- **Bought this round**: units you've bought this round. Shop buys are entirely reliant on image recognition, so the app may get things wrong. You can add and modify purchases here.
- **Unlocked in shops**: conditional units your board has made available.
- Every pane can be minimized to its title with the button at its top right.

## Overlay

With shop reading on, the app can draw its scores over the game. Each unit's value under it in an open shop, and each shop's average value under its icon, with a gold star on the best pick. Resting the mouse on a shop's icon lists the three units it can offer that are worth most. Turn it on or off with the Overlay button or Ctrl+Shift+O, or parts of it on or off with **Settings** (top right). It hides whenever the game window isn't in focus.
