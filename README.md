Project01_Bomberman_Standalone
==============================

About
===================

This project is inspired by Bomberman and was made for the intention of learning C++ and DirectX11. This project is not for sale.

By reading this that means I have finally finished this project without adding another feature or two! This is huge as i would have been done months ago, but would have much less to show for it.

When I Started this project back in December 2013, I had just finished learning C++ from a couple of text books over the months before. I had the drive to make a game in C++ so i looked into Cryengine. 
After about a week i realized that i had no idea how to start programming using that engine. There were no tutorials or any guides to get me started, but that's when i stumbled upon a DirectX11 tutorial. 
So within a month had a prototype engine that could generate 2D, 3D, GUI and sound!

With this new engine i decided to try to make a "small" project to help me learn how to code in C++ and also make a game at the same time. During the design period i learn countless new ways to program!
I learned about callbacks, A* pathfinding, Shaders, how to draw objects on a screen and much much more!
I loved this project and am sad its over, but am really looking forward to what ever is next.

Thank you for checking this out, it really means the world to me.

Jordan Soch

How To
===================
This project is inspired by Bomberman and was made for the intention of learning C++ and DirectX11. This project is not for sale.

NOTE: this program was designed for Windows platforms. As such will not work on Linux or Mac OS. Sorry for the inconvenience. 

First run the Setup EXE to configure the game to your computer settings.

How to play!
Launch the game by running the Bomberman EXE in the DX2DE folder.

to play the game launch either campaign, level select or bundle select. This will bring you into the game itself.

Ingame controls
W OR Up - Move Up
A OR Left - Move Left
S OR Down - Move Down
D OR RIGHT - Move RIGHT
Drop bombs - Space Bar

The goal of the game is to kill all the enemies in a level and find the exit. 

Game Grid:
Red Tiles 		- 	Can NOT be Destroyed
Yellow tiles 	- 	Can be Destroyed 
Green tiles 	- 	Can place bombs and walk through


Editor:
To create a new level hit the New level button. 
In the next screen enter a name into the large box and the width and height into the respected boxes. 
The level name, width and height all must be greater then 4!
Hit 

There are two states the editor can be in Level and Navigation
In level you can manipulate the tiles of a level. Place the tiles located on the right hands side on the grid to place in the level.
Each level must have an Spawn and an Exit or the level will not work.
Place enemies the same way you would place other tiles.

When in navigation mode you are now placing the waypoints that the enemies will follow around your level.
First you need to click the "Select" button, this will allow you to pick the enemy you want to edit.
By Selecting and enemy you are now ready to place waypoints. Click the add button and then place them on the grid. They are 
numbered in the order that the enemy will travel to them. If you place a waypoint and want to remove it, just click the remove button then 
click on the grid to remove it from the enemy. It will automatically update the order in which the waypoints will be followed.

Once you are happy with your waypoints click the Submit button. This will finalize your enemy and he will be ready to run through your level.

Finally once you are done with your level hit the Save button. As i mentioned you need to have a spawn and an exit for the save to work. But,
you also need to make sure the player can reach each enemy. If an enemies tile runs red, that means the enemy can not reach the player.
Modify the level until it returns to its original color before attempting to save. 

Save Successful. Congratulations! you made your first level. To play the level back out to the main menu and add pick select level.

Level Bundles
level bundles are bundles of levels that are connected back to back. This means you can start playing one level and once its completed move onto the next level of the bundle.
THis is great for creating your own campaigns! To create a bundle, you first need levels. hit the + symbol by the drop down to add a level. You can add as many levels are you want!

If you have any questions or run into any problems you can reach me at:
jlsoch@shaw.ca


