# # Spicerunner
Spicerunner is a 2d action game.
In this game you take a hold of our protagonist Roger’s spaceship, Vulcan,
and fight through waves of enemies to achieve a high score to move on to the end mission boss.
The game is still in alpha phase, and will be worked on incrementally as I have time to do so.
The end goal is to turn this game into a rogue-like that rewards the player based on how far they 
progressed in the game, and punishes by making them restart from the beginning. A full upgrade system and
inventory system are planned for future implementations.

## Table of contents
* [General info](#general-info)
* [Game Controls](#game-controls)
* [Power Drops](#power-drops)
* [Enemies](#enemies)
* [Screenshots](#screenshots)
* [Technologies](#technologies)
* [Setup](#setup)
* [Features](#features)
* [Status](#status)
* [Inspiration](#inspiration)
* [Contact](#contact)

## General info
As of today there are a total of 3 missions with a boss battle at the end of each. Every mission is incrementally harder
and makes you gain more points per mission to get to that next boss fight. The game comes included with a custom sound track
that I made with bosca ceoil to give to coincide with it's a vibrant 16-bit feel.

## Game Controls
The Game is played using WASD keys to move the player around the map.
The J key is used to flip the direction Vulcan is facing.
The SPACE key is used to fire the ships main weapon.

![Controls](https://github.com/josherz94/spicerunner/blob/master/Screenshots/Controls.PNG?raw=true)

## Power Drops 
There are five different items that may drop at random from enemies.

* The Shield Generator - provides invincibility for a set amount of time:

![Shield](https://github.com/josherz94/spicerunner/blob/master/Screenshots/shield.PNG?raw=true)
* The Phaser - Auto locks onto enemies for a short duration:

![Phaser](https://github.com/josherz94/spicerunner/blob/master/Screenshots/phaser.PNG?raw=true)
* The Laser - fires in random directions, sure to hit a target at random:

![Laser](https://github.com/josherz94/spicerunner/blob/master/Screenshots/laser.PNG?raw=true)
* Ammo - Ammunition for Vulcan's default weapon:

![Ammo](https://github.com/josherz94/spicerunner/blob/master/Screenshots/ammo.PNG?raw=true)
* The Nuke: Decimate all enemies within the vicinity:

![Nuke](https://github.com/josherz94/spicerunner/blob/master/Screenshots/nuke.PNG?raw=true)

## Enemies
There are five different enemy types implemented so far excluding bosses.

* The Tank - Don't let too many spawn because it will result in total chaos for you!

![Tank](https://github.com/josherz94/spicerunner/blob/master/Screenshots/tank.PNG?raw=true)

* The Soul Collector - Will try to locate you and sieze your ship!

![Soul-Collector](https://github.com/josherz94/spicerunner/blob/master/Screenshots/soul_collector.PNG?raw=true)

* The Mushroom - will tend to mob up and then attack Vulcan.

![Mushroom](https://github.com/josherz94/spicerunner/blob/master/Screenshots/mushroom.png?raw=true)

* The Mini Saucer - will home in on Vulcan rapidly

![Mini-Saucer](https://github.com/josherz94/spicerunner/blob/master/Screenshots/mini_saucer.PNG?raw=true)

* The Spider - Will rotate, firing rapidly in many directions! 

![Spider](https://github.com/josherz94/spicerunner/blob/master/Screenshots/spider.PNG?raw=true)

## Screenshots

![SS1](https://github.com/josherz94/spicerunner/blob/master/Screenshots/SS1.png?raw=true)
![SS2](https://github.com/josherz94/spicerunner/blob/master/Screenshots/SS2.png?raw=true)
![SS_Boss1](https://github.com/josherz94/spicerunner/blob/master/Screenshots/SS_boss1.png?raw=true)
![SS_Boss2](https://github.com/josherz94/spicerunner/blob/master/Screenshots/SS_boss2.png?raw=true)
![SS_Boss3](https://github.com/josherz94/spicerunner/blob/master/Screenshots/SS_boss3.png?raw=true)
![SS_Boss4](https://github.com/josherz94/spicerunner/blob/master/Screenshots/SS_boss4.png?raw=true)

## Technologies
* Unity Engine - version 2019.3.10f1 
* C#
* 2D Flat Explosion - Osama Deep
* Space Shooter Art Pack 02 - Playniax
* bosca ceoil - music maker

## Setup
This game is still in alpha, but will make its way to the steam store eventually.


## Features
List of features ready and TODOs for future development
* Procedurally generated maps for each boss fight.
* Fully animated enemies, players and weapon systems.
* AI for each enemy ship. No enemy reacts the same way to the player.
* Intense combat that will keep you moving to avoid enemies and get to the goal score.
* Custom soundtrack made by myself.
* Custom made maps for each mission

To-do list:
* tweak drop rates for enemies
* turn the game into a rogue-like where dying will make you start from the beginning
* add in an upgrade system to the ship that will carry over through deaths
* make the game harder in general.
* add more music
* fine tune player controller

## Status
Project is: _in alpha stage_

## Inspiration
Inspired by games such as Galactica and Space Invaders

## Contact
Created by [@josherz94] - feel free to contact me!
