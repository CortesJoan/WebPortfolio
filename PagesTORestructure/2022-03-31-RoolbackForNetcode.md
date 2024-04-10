---
title: "Rollback for NetcodeForGameObjects"
comments: true
excerpt: "Unity tool that add support for rollback netcode to a Unity project"
lang: en
ref: gamejam1Post
header:
  image: assets/images/foodBattles1.png
  caption: "A cubes used in the test scene"
categories:
  - Unity3d
  - Library
  - Uncategorized
tags:
  - C#
  - Online
  - GameJam
  - Netcode
  - Solo project

gallery:
  - url: /assets/images/games/food-battles/previewMcBurger.png
    image_path: /assets/images/games/food-battles/previewMcBurger.png
    alt: "placeholder image 1"
    title: "The McBurger Count strikes again!"
  - url: /assets/images/games/food-battles/previewpinchitos.png
    image_path: /assets/images/games/food-battles/previewpinchitos.png
    alt: "placeholder image 2"
    title: "Skewers fight!"
  - url: /assets/images/games/food-battles/previewArmy.png
    image_path: /assets/images/games/food-battles/previewArmy.png
    alt: "placeholder image 2"
    title: "Warrior Nuggets and War HotDogs are ready for the battle!"
  - url: /assets/images/games/food-battles/attack1.gif
    image_path: /assets/images/games/food-battles/attack1.gif
    alt: "placeholder image 2"
    title: "Attack!"
---
## Description
This is a package for Unity 2021 and **NetcodeForGameObjects** 1.0 that adds rollback netcode for a project.
The reason I did this library is  because NetcodeForGameObjects and similar network frameworks doesn't have a rollback netcode support and I wanted to make some simple library to avoid having to use external C++ libraries like GGPO
Currently still in **alpha** version so expect bugs
 
 
## Data sheet
* **Engine**: Unity3d
* **Release**: PC
* **Requeriments**: TMP, NetcodeForGameObjects>1.0prev3
* **Developer(s)**: Joan Cortés 

## Features
The main features are:
* Deterministic rollback netcode* Use class or struct type to store the important data
* Easy to understand code
* Works with Package manager remotely
* Examples scene
* Works with Unity Physics in the same platform
* Deterministic Math included (Thanks to XXXXX)

## Demo 
<iframe width="640" height="360" src="https://drive.google.com/file/d/1pIRTbpWstjJ8MoKduW5ypt_UIMwg-sko/preview?usp=sharing" frameborder="0" allowfullscreen></iframe>

## My work

## Images:
{% include gallery caption="Some demo examples" %}

## Download
[GitLab Source with instructions to add it to the package manager](https://gitlab.com/EvilHack/NetworkRollbackTestGit){: .btn .btn--primary} 
  
