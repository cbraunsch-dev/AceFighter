# Ace Fighter
Developed between 2006-2010
!['Title Screen'](https://github.com/cbraunsch-dev/AceFighter/blob/master/AF_Game_Final_Debug/Images/Screens/StartScreen.png)

## The Game

This is a simple shooting game I developed back when I was just starting out. The game is entirely written in java along with all of the development tools (Level and cutscene editor). No engine was used. The game uses its own very rudimentary engine.

!['img'](https://github.com/cbraunsch-dev/AceFighter/blob/master/Screenshots/af_1.png)

!['img'](https://github.com/cbraunsch-dev/AceFighter/blob/master/Screenshots/af_3.png)

!['img'](https://github.com/cbraunsch-dev/AceFighter/blob/master/Screenshots/af_4.png)

!['img'](https://github.com/cbraunsch-dev/AceFighter/blob/master/Screenshots/af_5.png)

!['img'](https://github.com/cbraunsch-dev/AceFighter/blob/master/Screenshots/af_gif_1.gif)

!['img'](https://github.com/cbraunsch-dev/AceFighter/blob/master/Screenshots/af_gif_2.gif)

!['img'](https://github.com/cbraunsch-dev/AceFighter/blob/master/Screenshots/af_gif_3.gif)

!['img'](https://github.com/cbraunsch-dev/AceFighter/blob/master/Screenshots/af_gif_4.gif)

!['img'](https://github.com/cbraunsch-dev/AceFighter/blob/master/Screenshots/af_gif_5.gif)

!['img'](https://github.com/cbraunsch-dev/AceFighter/blob/master/Screenshots/af_gif_6.gif)

!['img'](https://github.com/cbraunsch-dev/AceFighter/blob/master/Screenshots/af_gif_7.gif)

!['img'](https://github.com/cbraunsch-dev/AceFighter/blob/master/Screenshots/af_gif_8.gif)

!['img'](https://github.com/cbraunsch-dev/AceFighter/blob/master/Screenshots/af_gif_9.gif)

!['img'](https://github.com/cbraunsch-dev/AceFighter/blob/master/Screenshots/af_gif_10.gif)

## The Level Editor

This is a rudimentary level editor I developed to help me build the levels. The editor allowed me to specify whether the level would be a side-scrolling level or whether it would be static. It also allowed me to add all the different types of game objects.

!['img'](https://github.com/cbraunsch-dev/AceFighter/blob/master/Screenshots/level_editor1.png)

!['img'](https://github.com/cbraunsch-dev/AceFighter/blob/master/Screenshots/level_editor2.png)

!['img'](https://github.com/cbraunsch-dev/AceFighter/blob/master/Screenshots/level_editor3.png)

!['img'](https://github.com/cbraunsch-dev/AceFighter/blob/master/Screenshots/level_editor4.png)

## The Cutscene editor

This tool allowed me to write dialog for cutscenes and allowed me to script simple actions for different NPCs. I could specify that an NPC should move left and start speaking when the user pressed a certain button, for instance.

!['img'](https://github.com/cbraunsch-dev/AceFighter/blob/master/Screenshots/cutscene_editor1.png)

!['img'](https://github.com/cbraunsch-dev/AceFighter/blob/master/Screenshots/cutscene_editor2.png)

!['img'](https://github.com/cbraunsch-dev/AceFighter/blob/master/Screenshots/cutscene_editor3.png)

## Running the projects
### Running the game in Eclipse
* Clone the project
* Copy the 'Load' and 'Images' folders into the 'bin' directory
* Start Eclipse
* Import the project's root folder
* Under Run Configurations choose 'Java Applet'
* Under 'Project' Select 'AF_Game_Final_Debug'
* Under 'Applet' select 'GameEngine'
* Apply and run the project

### Running the level editor in Eclipse
* Clone the project
* Start Eclipse
* Import the project's root folder
* Under Run Configurations choose 'Java Application'
* Under 'Project' Select 'Level_Editor_Before_SVN'
* Under 'Main class' Select 'Main'
* Apply and run the project

### Running the cutscene editor in Eclipse
* Clone the project
* Start Eclipse
* Import the project's root folder
* Under Run Configurations choose 'Java Application'
* Under 'Project' Select 'CutsceneEditor'
* Under 'Main class' Select 'MainGUI - GUI'
* Apply and run the project
* If an error dialog appears informing you that a custscene file could not be loaded, ignore it and click 'Ok'. This message appears because the application tries to load the cutscene file located in the location specified in the preferences.
