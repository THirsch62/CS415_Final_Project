# Fire Boy and Water Girl 3-D

## April 17th, 2024
Tyler looked into the linking issue between the two buttons. After debugging, the issue was identified within the "Get Current Level Name" function. This was resolved by creating a new level, specifically for menu operations. The menu can only be opened on level, which will help prevent trying to open an already open level.  

After this, the linking issue was resolved. Tyler also added:
* Functionality for level restart upon player death
* Fixed door functionality (Couldn't recognize when both players were standing at their respective doors)
* Added level complete/end screen
* Bringing up main menu upon level completion
* Combining endgates into one spawnable object

## April 16th, 2024
Max added Level 1. A few problems he noticed:
* Linking issue between two buttons and the same platform on Level 1
* Push block leaves red outlines and is buggy
* Push block is not affected by gravity
* Need to add level end screen

## April 10th, 2024
Tyler created a linking feature to map lever/button platforms to the various moving platforms.

## April 8th, 2024
Anwesa added the water, fire and acid pools. Functionality is as follows:
* Water pools
  * Fire boy dies
  * Water girl lives
* Fire pools
  * Fire boy lives
  * Water girl dies
* Acid pools
  * Fire boy dies
  * Water girl dies

Wentao added the level end door. It will load the next level upon completion. He also added movable blocks.

## April 7th, 2024
Eric added the fire and water gems, with functionality, so that fire gems can only be picked up by fire boy and water gems can only be picked up by water girl.

## April 5th, 2024
Tyler created the following:
* Spawnable Objects
  * Basic Platform
  * Moving Platform Z
  * Moving Platform XY
  * Lever Platform
  * Button Platform
* In game GUI with working time and gems collected

Tyler added these features to the demo level for display and also started work on the menus and menu controllers.

## April 4th 2024
Max made a demo level and created the two base characters, fireboy and water girl.

## April 3rd, 2024
Met on discord at 5pm to discuss project details, and divide out work. Here is link to <a href="https://docs.google.com/spreadsheets/d/1pCrzvWXF4yZpCi_FmnKuRyMFsfaez11LSaAhWlaeaDY/edit?usp=sharing">document</a> detailing how we will divide out work.

![Screenshot](/readme_images/initial_work_divide.png)

We decided that we will import the Unreal Starter Kit for character movement and other basic functions that will make it easier to get a good start on our game. We will create a new directory for all content directly pertaining to our game and create subdirectories for:
* Spawnable Objects
* GUI
* Character
* Textures
* (Others TBD)

We set a goal of having all Spawnable objects completed by April 8th, so we can start dragging and dropping into levels for level design.
