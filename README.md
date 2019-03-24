# Ace Fighter
Developed between 2006-2010
!['Title Screen'](https://github.com/cbraunsch-dev/AceFighter/blob/master/AF_Game_Final_Debug/Images/Screens/StartScreen.png)

This is a simple shooting game I developed back when I was just starting out. The game is entirely written in java along with all of the development tools (Level and cutscene editor). No engine was used. The game uses its own very rudimentary engine.

## Running the project
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