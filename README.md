# unity2d-starter

A bare bones sample project for a 2D Unity game.

## Scenes

The project includes 3 scenes:
- TitleScene.unity is a landing screen for startup. Pressing space from the title screen starts the game and loads... 
- MainMenu.unity is an empty scene that is meant to hold the main game menu. It is referenced from the title scene.
- Credits.unity loads when the game finishes. Pressing any key exits the application.

## Scripts

The game includes three rudimentary C# scripts:
- StartGame.cs loads the MainMenu scene when the spacebar is pressed. It is connected to the Main Camera in TitleScene.
- CameraController.cs defines a public Transform that should be set to the player object. The camera will follow the player at a given X and Y offset.
- Quit.cs detects a keypress and quits the application. It is attached to the Credits scene Main camera.

## Building and Playing

The project includes two placeholder logos that will appear when the game is built and played (See Player Settings). The TitleScene should be loaded first (See Build Settings.) Be sure all three scenes have been added to the build.
