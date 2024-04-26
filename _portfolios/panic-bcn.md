---
project_id: "PanicBCN" 
layout: project
title: "PanicBCN Remake"
categories: ["Collaboration project"]
description: A remake of an old arcade 2D platformer game.
thumbnail: assets/images/games/panic-bcn/panic_bcn_old_logo_resized.jpg
team:
  enable : true
  item:
  - name : "Joan Cortés"
    designation : "Backend Developer"
    image : "/assets/images/teams/logo300.png"
tags:
  - Unity 3d
  - Videogame projects
  - Collaboration project
download: false
gallery:
  - url: /assets/images/games/panic-bcn/bcn_image_1.jpg
    image_path: /assets/images/games/panic-bcn/bcn_image_1.jpg
    alt: "The game in action"
    title: "The game in action"
  - url: /assets/images/games/panic-bcn/bcn_image_2.jpg
    image_path: /assets/images/games/panic-bcn/bcn_image_2.jpg
    alt: "The game in action"
    title: "The game in action"
  - url: /assets/images/games/panic-bcn/bcn_image_4.jpg
    image_path: /assets/images/games/panic-bcn/bcn_image_4.jpg
    alt: "One of the bosses"
    title: "One of the bosses"
---

<div class="col-lg-8 text-center" markdown=1>

## {{page.title}}

    {{page.description}}

</div>

  <div class="col-lg-12 text-center">
   <p class="text-color font-weight-bold mb-2">Category</p>
   <p>{% for category in page.categories %} {{category}}{% unless forloop.last %} , {% endunless %} {% endfor %}</p>
  </div>

<div class="col-lg-8 text-center" markdown=1>

## Description

An unreleased remake of an old arcade 2D platformer game. I am only allowed to tell in more detail the features that were already present in the original game more than the things that would be added new to this remake

## Features

- Quick and smart action.
- Superb Arcade Mode for 1 or 2 simultaneous players.
- Wonderful History Mode that lets you save your progress.
- More than 100 levels filled with pure fun.
- With 3 different enemies in 3 perilous varieties each.
- 3 defying final bosses in 9 explosive encounters!
- Great and Sticky music - you won't stop whistling it!
- Unique difficulty levels meant for all kind of players.

## Images

For reference these are some images of the original game (I can not share about the remake but the looks are the same) all are extracted from the original webpage linked at the end of the page


{% include carousel.html gallery=page.gallery invert_icons=true %}
{% include modal.html  gallery=page.gallery modal_id='lightboxModal' img_id='lightbox-img' invert_icons=true %}

## My work here

In this project I had more room to make a flexible code that in the other collaborations. That means that I had a large abstraction layer and I could setup the foundations in the code structure of the project. .

### Enemy Behaviors and AI

I implemented and refined various enemy behaviors, including movement, patrolling, attacking, and responding to player actions. I also made the 3 original variations that each basic enemy had in the original game.

### Player Mechanics and Abilities

I worked on core player mechanics such as movement, jumping, basic attacks, and the ultimate attack. This included scripting features like combo handling, invulnerability during blinking, and health management.

### Fruit system

I designed and implemented the fruit system, including both large and small fruits with different point values and behaviors. I also made the script for splitting big fruits into small ones.

### Projectile System

I developed the projectile system, including scripting the movement and behavior of projectiles.

### Health and Damage System

I implemented the health and damage system for both players and enemies. The logic is easily reusable by any player or any enemy.

### Scoring System

I developed the scoring system, independent for each player, to make them able to save their own scores. The display and logic are correctly decoupled.

### Basic level prototyping

I made some basic level prototyping to test the mechanics and the gameplay. I also made some basic level design and adjusted some tools to make it easier to make levels for the level designers.

### Improved project structure as a whole

As I said, I had plenty of freedom to refactor and optimize the already existing codebase, improving code structure, readability, and performance as well as fixing some bugs. 

### Other Contributions

I can not talk too much about these other contributions, but I also worked on some aspects of the game that are exclusively new for this remake.

My work at PanicBCN remake was a great opportunity to showcase my skills and contribute to a fun and challenging game. I am proud of the work I did and am excited to see the final product released to the public.

## Game webpage

The original version has a webpage:

 <https://www.spiritvg.com/PanicBCN>

</div>
