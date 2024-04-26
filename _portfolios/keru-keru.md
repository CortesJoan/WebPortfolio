---
project_id: "KeruKeru" 
layout: project
title: "Unreleased Octopus game"
categories: ["Collaboration project"]
description: An Unreleased 3d platformer-puzzle about octopus.
thumbnail: assets/images/games/keru-keru/keru_keru_old_logov2.png
tags:
  - Unity 3d
  - Videogame projects
  - Collaboration project
download: false
team:
  enable : true
  item:
  - name : "Team garden"
    designation : "Video game Studio"
    image : "/assets/images/teams/team_garden.jpg"
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

An unreleased platformer-puzzle game about an octopus. I can not give too many more details about the game itself or provide captures at the moment. I will update this page when I get the permission to do so.

## Developer

{% include team.html %}

## My work here

I worked in different areas of this project, but my main focus was on the gameplay elements and the editor tools. I also contributed to the boss fight.

### Gameplay Elements

#### Objects behaviour

I developed the behavior of several objects in the game, ones for the ice themed level, a cloud themed one, and some ones that are part of the core gameplay like one that alters the limits of the principal mechanics of the main character.
Each object needed a specific behaviour, and I had to make sure that they were consistent with the game's overall design and mechanics, as well as the project structure on the organization side.

#### Refactoring to some code

I was also responsible to remake some of the code that was already done, to make it more efficient and easier to maintain. This included some extractions for a more modular approach, like having a script for forward movement that could be combined inherited by other scripts to make the creation of new projectiles easier and more consistent.

#### Generic scripts

I made some generic scripts that were used in different parts of the game, like a script that simply spawns objects following a set of parameters.
These reusable components enhanced the efficiency and modularity of the development process.

### Editor tools

Some of these gameplay elements needed some editor scripts to make the creation of new levels easier, so I made some tools that would help the level designers to create some of this objects faster and with fewer errors.

### Boss fight

I contributed to make the first version of the final boss fight. I was involved in designing and implementing its core mechanics, including its different phases, attack patterns, and state changes. I also created the win conditions. I coded more than 9 different attacks. These attacks contributed to the challenging and dynamic nature of the boss fight. I also created some placeholder cinematics for the Anomaly boss fight, including scenes for phase transitions and material state discards. Additionally, I implemented some of the visual effects of the Anomaly and its projectiles made by other parts of the team, enhancing the overall presentation of the boss encounter.

</div>
