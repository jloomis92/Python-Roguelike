# Tombs of the Ancient Kings
In typical roguelike fashion, each dungeon level as well as items/monsters are procedurally generated fresh with each new game or level of the dungeon you explore. If you die, you start all over again. If the game quits without you dying, there is a save file called `savegame.sav` that stores the game engine's state. When you start playing again, you can choose to either wipe that and start a new game, or continue your previous save.

Feel free to provide feedback/raise any issues you may run into when you play the game. See the [Planned Features](https://github.com/jloomis92/Python-Roguelike?tab=readme-ov-file#planned-features) section below to see what I currently have planned for implementation at some point.

This is a project developed from a tutorial by [TStand90](https://github.com/TStand90) (original tutorial found [here](https://rogueliketutorials.com/)).

## Instructions
The [Releases](Roguelike/Releases) folder contains the application in executable format. Otherwise, ensure you have python installed and then run `python main.py` or `python3 main.py` (depending on what your environment looks like) from inside the Roguelike directory to run the game.

## Controls
Until I have the in-game help menu set up, this is the best I can do:

### Movement
You can use several differnt keys to move your rogue around the dungeon. The currently supported movement keys are:

- Arrow Keys (Up, Down, Left, Right)
- Numpad Keys:
  -  **8:** Move Up
  -  **2:** Move Down
  -  **4:** Move Left
  -  **6:** Move Right
  -  **7:** Move Up, Left
  -  **9:** Move Up, Right
  -  **1:** Move Down, Left
  -  **3:** Move Down, Right

### Interaction

**C** -  Open character menu

**G** -  Pick up items

**I** -  View inventory

**D** -  Drop item

**V** -  View message log history

**/** -  Enable look mode (allows you to use your mouse/movement keys to move the curor around the dungeon to get the labels of things

**>** -  Use stairs (You will have to actually type the '>' symbol by using Shift + .

> [!NOTE]
> Note: Use the letters that coorespond to the menu item to interact with it inside of the menu (consuming a potion, equipping/unequipping an item, dropping an item, etc.)

## Planned Features
- [ ] Adjust monster difficulty
- [ ] Add in-game Help menu to display things like controls, or any other relevant information.
- [ ] Add in some new items/spells
- [ ] Expand ability to have more than one savegame file
- [ ] Add way to save game without having to exit
  
## Changelog
Version 1.0 - This is the state of the game right after finishing the tutorial linked above (with a few minor tweaks to things like the name of the window, welcome text, etc.). Current, stable build.
