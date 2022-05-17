# **Sword Fighter AR Game**
## Team Members:
1. Akshay Singh
2. Shreya Attri
3. Sanchit Sikri

## **Concept:**
This game involves sword fighting with integrated AR experience. Augmented Reality (AR) can be defined as a system that incorporates three basic features: a combination of real and virtual worlds, real-time interaction, and accurate 3D registration of virtual and real objects.

## **Gameplay:**
The game involves a player having a sword and he has to simply kill the zombies that are coming towards to kill him. The zombies will come towards the player and he has to save him from his sword. There will be a city where all over only zombies are there and our player has to cross that city by killing all the zombies. There will be a total of 7 zombies roaming around in the whole city and the player has to kill all of them in order to complete the level. A timer will also be running and only in that specified time the player has to complete the whole game. 

## **Game Construction:**
- We are using C# for the coding part of the game. With this we are controlling the movements, zombies, efficiency, force of the sword, collision, point board, game start, game over, and few others. 
- We placed an image target using Vuforia engine on to the gamescene. Then we imported a map of the game on placed on the image target.
- Similarly, we place player and zombies on the map and add scripts for their movement. 

## **Gamescene:**
We have incorporated a 3d-model of a game scene from a site “sketchfab.com” to our AR project. We have also added rigid body component to all the components of the 3d-model.

![image](https://user-images.githubusercontent.com/79785530/119209240-2c53a380-bac3-11eb-889b-fc8e3794e4fe.png)


## **Scripts:**
> There are several scripts of visual studios used to control the player movement, zombie movement and the AR system.
- Player movement script:
  Through this script we have added player movement using the keys A,D,W,S. Further these keys have been attached to the joystick for the movement of the player using it.


![image](https://user-images.githubusercontent.com/79785530/119209164-ce26c080-bac2-11eb-95a0-848b4ab1e68b.png)


- Attack script:
  This script has been attached to the zombie and allows him to follow the player and attack him when he is at the specified distance. This script bascially uses navigation     component to be completed and also NavMeshagent have been used. 

- Health script:
  This script has been attached to both player and the zombie and helps us to attach a health bar to them which depicts their health and also reduces it upon taking damage.
- Damage script:
  This script has been attached to zombie's hands and player's sword. It specifies the amount of damage that the player or zombie will take on getting hit by the enemy
  weapon.
## **Joystick and Attack button:**
We have added a joystick and attacking button on the screen of the mobile phone to control the player movements and attacks.


Google Drive link of the project:
https://drive.google.com/drive/folders/1ayOjpfDaT-eF00N3wmzPQlcfz70zjHfB?usp=sharing

## **Referrences**
