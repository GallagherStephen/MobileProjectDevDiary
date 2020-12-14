# MobileProjectDevDiary


---

### Table of Contents

- [Description](#description)
- [Day to Day Developer Diary](#Diary)
- [References](#references)

---

## Description

Developer Diary for mobile app development 3 unity game Project




[Back To The Top](#MobileProjectDevDiary)

---
## Day to Day Developer Diary


## 1/11/2020 - 20/11/2020

Studied the Design Document and researched into the different areas needed to carry out the designed game.
With all of my reasearch into what was needed for my game I realised that the only area I would need to look further into was the multiplayer functionality.
As I have had no experience as of yet around multiplayer.This which will be a new learning experience.To date after all my research I have created a repository called 3dEndlessRunnerProject
where I initially created a game with a course my player would take.But I came into an issue with my game scene which had frozen and led me restarting my project with a new repository called "3dEndlessRunnerNew".

## 20/11/2020 

Project repository created and game started.I have created a plane that is being used as the main track of my 3dendless runner game.Then I went and created each tranglur structure using 
3d cylinders to achieve the effect that was given in the design document pictures.These which I put in Pink to match.I then went and created the main player using different 3d shapes to match the character given in the design document pictures also.
These steps which took some timne in doing.I then added The player controller functionality where they could move using the wasd or arrow keyboard keys. 
I then imported an asset from the asset store of a skybox that gave my game a nice futuristic space like feel which the design theme set out for.I went and then added music to my game that plays at the beinning of the game for a "Cyberpunk 80s theme" feel as requested in the design document.
![](Images/filename%20playerImage.png)
![](Images/filename%20mapLayout.png)

## 20/11/2020 

I went and added the functionality of the player being able to jump on request by the user when the spacebar is pressed.


## 02/12/2020 

I redone my Level 1 scene and this time I made the player and the camera move in the same direction in Sync (this done by two scripts.one for camera and one for player character).This which pushes the player forward in the correct way for an Infinite Runner Game.I also created another two levels identical to the first bar the enemies and pickups located on the players route.This which I have different in each level as I am distinguishing the difference in levels and what they should contain.for eg: (level 1 for now has 1 enemy ) (level 2 for now has 3 enemys and one pickup ) (level 3 for now has 5 enemys and two pick ups ).This just for myself to keep the level requirements visable and a self reminder.



## 03/12/2020 
Part (1)
- Added functionality to move between menus.

part (2)
- added better surrounding visuals to the gameplay scene. This where I got assests to have the following.Pyramids(which i modified to add blue edges like image in design brief),
- planet which is also in the design brief photo,stars and clouds in the distance to make some realism.(moving objects).Added an image to the plane(ground) which makes the ground look like a grid as in design document image.



## 08/12/2020 

- added pickups for the player to collect and destroy on collision.These "mail" pickups which when picked up will add up the score for the player .Making up the objective of the game to  get a high score.

- Added scripts to game to maske this possible (mailScript + pointScript )
- added a tile spawner that makes the game endless being a endless runner.
- fixed being able to die by enemies and pick up emails ,which was an issue the way i had it setup
- Added a Volume toggle to the game with a "MuteManager" script
- fixed toggle volume on main menu
- removed unwanted scenes
- fixed quit button to quit the application by adding quit method in "buttonManager" script
- added load game -level select menu - with EASY , MODERATE & HARD levels
- added the pause menu overlaps the gameScene when "ESC" button is pressed .


## 09/12/2020

- created the following enemies : firewalls and baston servers
- created a high score UI element for player to see .
- created a Time UI element for player to see when in game .(created a TimeScript for this which outputs time to two decimal spaces as passed in "f2" ..to four decimals would be "f4")
- added dialoge popup box on "trigger enter" at start of each level - DialogeTrigger Cube element ("DialogeTriggerScript")
- added a trigger to load to the next level using a script i called "LoadLevelTrigger"
- linked all levels together with the level trigger at end .This making a completed game feel.
- added music to end game scene
- changed the plane ground on each level to distinguish changed levels


## 10/12/2020

- created sounds to play on awake at the start of each game scene
- added the correct powerups  to each scene
- added a purple particle effect to instantiate when trigger the powerup object with player
- changed speed of the player for each level (to show change)
- added that each level enemy count is higher to make each level harder
- added 5 baston servers (enemy) to level 3

## 13/12/2020
- copied current "status" of scenes 1-3 including end game scene and renamed them to create a Local Multiplayer.
- linked all multiplayer scenes to transition between them by end of scene triggers and by button press's to load next scene.

## 14/12/2020
- added that you restart the "current" level you are on if you die in Multiplayer.for P1 & P2. (Like a checkpoint system)
- clamped the players movement between the values (-1.7f , 1.7f) on the x axis.




[Back To The Top](#MobileProjectDevDiary)

---

## References






[Back To The Top](#MobileProjectDevDiary)

---






[Back To The Top](#MobileProjectDevDiary)