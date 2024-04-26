---
project_id: "FoodBattle"
layout: project
title: "Food battle"
categories: ["Personal Video game Projects"]
showOnlySameCategoryInRelatedProjects: true
thumbnail: "/assets/images/games/food-battles/nuggetWarriorIcon.png"
description: "Online multiplayer RTS  made with Unity and Mirror"
post_image:  "/assets/images/games/food-battles/nuggetWarriorIcon.png"

tags:
  - C#
  - Cartoon
  - Online
  - GameJam
  - Netcode
  - Group project
download: true
download_link: "https://gitlab.com/EvilHack/RTSeadosProject"
download_title: "GitLab Source Code"
###################### Team ######################
team:
  enable : true
  item:
  - name : "Joan Cortés"
    designation : "Main Programmer"
    image : "/assets/images/teams/logo300.png"
    
  - name : "Eric Bujaldon Marco"
    designation : "3D Artist"
    image : "/assets/images/teams/eric.png"
    
  - name : "Sergi Granell "
    designation : "Programmer, Main Game Designer"
    image : "/assets/images/teams/sergi2b.jpg"
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

 <!--Title and desription. -->
<div class="col-lg-8 text-center" markdown=1>

## {{page.title}}

     {{page.description}}

</div>
 <!-- <div class="row">-->

  <div class="col-lg-12 text-center">
   <p class="text-color font-weight-bold mb-2">Category</p>
   <p>{% for category in page.categories %} {{category}}{% unless forloop.last %} , {% endunless %} {% endfor %}</p>
  </div>
  <!--<div class="col-lg-12 text-center">
  # <p class="text-color font-weight-bold mb-2">Si se quieren poner mas tags en rojo</p>
  # <p>aqui habia algo?</p> -->
   <!--</div>-->

<div class="col-lg-8 text-center" markdown=1>

## Description

 This game is an online multiplayer RTS(max 4 players)  made with the Unity engine and the Mirror and FizzySteamworks addons to make the game work with Steam servers.
 In the game you have to command your food faction to become the best food in the table destroying all the other factions.
</div>

<div class="col-lg-8 text-center" markdown=1>

## Developers

{% include team.html %}

## Data sheet

* **Engine**: Unity3d
* **Release**: PC
* **Genre**: Real Time Strategy(RTS)
* **Mode(s)**: Multiplayer PvP (2-4 players)
* **Graphic Style**: 3D Low Poly (Magicavoxel), Cartoon

</div>

<div class="col-lg-8 text-center" markdown=1>

## Mechanics

 &ensp; &ensp;  The main mechanics are:

* Construction.
* Resource collection.
* Combat.
* Expiration.
* Morale buffs and debuffs.

</div>



<div class="col-lg-12 text-center" markdown=1>

## Gameplay

 <iframe width="640" height="360" src="https://drive.google.com/file/d/1pIRTbpWstjJ8MoKduW5ypt_UIMwg-sko/preview?usp=sharing" frameborder="0" allowfullscreen></iframe>
</div>

<div class="col-lg-12 text-center" markdown=1>

## My work

Mainly, I have been dedicated to the implementation of the multiplayer and the development of tools for the game designer. Although I have also programmed basic mechanics including some units and buildings

## Images

{% include carousel.html gallery=page.gallery %}
{% include modal.html  gallery=page.gallery modal_id='lightboxModal' img_id='lightbox-img' %}

</div>

{% include related_posts.html property="project_id" value=page.project_id %}