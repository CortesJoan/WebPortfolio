---
project_id: "MusicGame"
layout: project
title: "Musical game"
categories: ["Video game Projects"]
description: "Music game made in less than 1 week with Unity"
thumbnail: assets/images/games/music-game/background.png
thumbnail: "assets/images/games/music-game/background.png"
tags:
  - C#
  - Solo project
 
###################### Team ######################
team:
  enable : true
  item:
  - name : "Joan Cortés"
    designation : "Solo Developer"
    image : "/assets/images/teams/logo300.png"
 
gallery:
  - url: /assets/images/games/music-game/badPlay.gif 
    image_path: /assets/images/games/music-game/badPlay.gif 
    alt: "Not playing very well" 
    title: "Not playing very well" 
  - url: /assets/images/games/music-game/goodPlay.mp4  
    image_path: /assets/images/games/music-game/goodPlay.mp4 
    lt: "Playing well" 
    title: "Playing well" 
download: true
download_link: "https://gitlab.com/EvilHack/GuitarHeroTest"
download_title: "GitLab Source"
---

<div class="col-lg-8 text-center" markdown=1>

## {{page.title}}

     {{page.description}}

</div>

<div class="row">
  <div class="col-lg-12 text-center">
   <p class="text-color font-weight-bold mb-2">Category</p>
   <p>{% for category in page.categories %} {{category}}{% unless forloop.last %} , {% endunless %} {% endfor %}</p>
  </div>
</div>
Explain
<div class="col-lg-8 text-center" markdown=1>

## Description

Music game made in less than 1 week

</div>

<div class="col-lg-8 text-center" markdown=1>

## Developers

{% include team.html %}

## Data sheet

* **Engine**: Unity3d
* **Release**: PC
* **Genre**: Rhythm
* **Mode(s)**: Singleplayer
* **Developer(s)**: Joan Cortés
* **Graphic Style**: 2D

</div>

<div class="col-lg-8 text-center" markdown=1>

## Mechanics

The main mechanics are:

* Play a song and earn score
* A combo system

</div>

## Gameplay

<div class="col-lg-12 text-center" markdown=1>
 <iframe width="640" height="360" src="https://drive.google.com/file/d/1pIRTbpWstjJ8MoKduW5ypt_UIMwg-sko/preview?usp=sharing" frameborder="0" allowfullscreen></iframe>
</div>

<div class="col-lg-8 text-center" markdown=1>

## My work

I did all the code and the game and the graphics are default Unity ones

## Images
  
   {% include carousel.html gallery=page.gallery %}
{% include modal.html modal_id='lightboxModal' img_id='lightbox-img' %}

 {% include modal.html %}
 
 
</div>

<div class="col-lg-12 text-center" markdown=1>

</div>
{% include related_posts.html property="project_id" value=page.project_id %}

 {% include share_this_on.html %}
