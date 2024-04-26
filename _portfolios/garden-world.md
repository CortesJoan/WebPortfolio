---
project_id: "GardenWorld" 
layout: project
title: "GardenWorld"
categories: ["Collaboration project"]
description: An unreleased AA 3D platformer .
thumbnail: assets/images/games/garden-world/TitleGW_Outlined2048.png
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
  - AA
download: false
gallery:
  - url: /assets/images/games/garden-world/gw_0.png
    image_path: /assets/images/games/garden-world/gw_0.png
    alt: "Game promotional image"
    title: "Game promotional image"
  - url: /assets/images/games/garden-world/gw_1.png
    image_path: /assets/images/games/garden-world/gw_1.png
    alt: "Gameplay Image"
    title: "Gameplay Image"
  - url: /assets/images/games/garden-world/gw_2.png
    image_path: /assets/images/games/garden-world/gw_2.png
    alt: "One of the levels were I worked. I did the programming of the noire and some other attractions of the Amusement planet"
    title: "One of the levels were I worked. I did the programming of the noire and some other attractions of the Amusement planet"
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

Welcome to GardenWorld! Make tons of friends and save nature in this 3D platformer that will take you through all the Universe! Play as Tane, the last Seed of Life, and join the resistance against an army of corrupted creatures in search of your lost parents.

## Features

- Open world adventure
- Unique gameplay with unique powers
- Set on tiny, exhuberant planets
- Help Tane to reunite with their parents!
- Help, befriend and ride tiny animals
- Fly from planet to planet on a giant golden ladybug
- Uncover the great mystery of the GardenWorld Universe!
- Suitable for all audiences

## My work here

While I can't disclose specifics due to the project's ongoing development, I can share some highlights of my contributions to this captivating game:

### Internal Tool Development
- Helped to develop an internal tool to streamline the creation of BezierLines, which are used to create paths for objects to follow. This tool allowed level designers to easily create and modify paths without needing to write code, saving time and effort.

### Dynamic Object Traversal
- Spearheaded the implementation and refinement of systems allowing objects like vehicles and transportation mechanisms to seamlessly navigate along complex paths adapting to a variable gravity, enhancing the player's interactive experience within the game's diverse environments.

### Electrical Systems Improvements
- Played a key role in building the framework for interactive electrical systems, crafting components like generators, switches, and lights, and meticulously ensuring their functionality through rigorous testing and bug fixing.
- Programmed the behavior of the Ferris wheel (visible in the second image in the gallery), along with multiple other electric objects in that level.

### Illumination and Darkness Mechanics
- Contributed to the development of gameplay mechanics related to darkness and illumination, influencing the game's atmosphere and player interaction with the environment using a specific shader.

### Diverse Gameplay Mechanics
- Expertise extended to a range of other gameplay elements, including:
  - Physics-based interactions
  - Puzzle mechanics like Simon Says
  - Harder physics puzzles like a polar crane
  - Trampolines and slingshots

### Code Revision and Improvements
- Responsible for revising and improving old code to ensure it was up-to-date with new features and mechanics being added to the game.

### New Plant Logic
- Created the logic for a new plant in the game.

### Mission Scripting
- Scripted gameplay missions for objects programmed by me.

### Bug Fixes and Optimizations
- Dedicated significant effort to identifying and resolving bugs across various systems and scripts.
- Implemented optimizations to ensure smooth performance and stability.

This was also my first professional experience on a  professional game development team, where I learned a great deal about the development process, working collaboratively, and the importance of communication and collaboration.

## Images

{% include carousel.html gallery=page.gallery %}
{% include modal.html  gallery=page.gallery modal_id='lightboxModal' img_id='lightbox-img' %}

## Game webpage

You can check more about the game in the official webpage: <br>

<https://www.gardenworldgame.com>

</div>
