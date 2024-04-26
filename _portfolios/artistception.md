---
project_id: "Artistception"
layout: project
title: "Artistception"
categories: ["Personal Video game Projects"]
showOnlySameCategoryInRelatedProjects: true
description: "2D platformer created with Unity where the art takes an important part"
thumbnail: assets/images/games/artistception/menu1024.png
tags:
  - C#
  - Artistic
  - Group project

 ###################### Team ######################
team:
  enable : true
  item:
  - name : "Joan Cortés"
    designation : "Gameplay Programmer"
    image : "/assets/images/teams/logo300.png"
    
  - name : "Joan Lecha Guix"
    designation : "Artist,Game Designer"
    image : "/assets/images/teams/lecha.png"
    
  - name : "Roger Lario"
    designation : "Level Designer, Programmer"
    image : "/assets/images/teams/roger.png"

gallery:
  - url: /assets/images/games/artistception/menu2.png
    image_path: /assets/images/games/artistception/menu2.png
    alt: "Menu 1"
    title: "First version of the menu"
  - url: /assets/images/games/artistception/pickUpTorch.png
    image_path: /assets/images/games/artistception/pickUpTorch.png
    alt: "placeholder image 2"
    title: "And then there was light."
  - url: /assets/images/games/artistception/mamoothA.png
    image_path: /assets/images/games/artistception/mamoothA.png
    alt: "The first boss cinematic"
    title: "The first boss cinematic"
  - url: /assets/images/games/artistception/fish1.png
    image_path: /assets/images/games/artistception/fish1.png
    alt: "The fish in the second level"
    title: "The fish in the second level"
  - url: /assets/images/games/artistception/fish2.png
    image_path: /assets/images/games/artistception/fish2.png
    alt: "placeholder image 2"
    title: "Fish searching for the moon"
  - url: /assets/images/games/artistception/fishBoss.png
    image_path: /assets/images/games/artistception/fishBoss.png
    alt: "The final boss"
    title: "The final boss of the game"
    
download: true
download_link: "https://gitlab.com/EvilHack/artistception/"
download_title: "GitLab Source"
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

This game is a 2D platformer created with Unity by a team of 3 people where the player enters to a different painting each level.
Currently there are 2 fully functional levels

</div>

<div class="col-lg-8 text-center" markdown=1>

## Developers

{% include team.html %}

## Data sheet

* **Engine**: Unity3d
* **Release**: PC
* **Genre**: Adventure
* **Mode(s)**: SinglePlayer
* **Developer(s)**: Joan Lecha, Roger Lario, Joan Cortés
* **Graphic Style**: 2D

</div>

<div class="col-lg-8 text-center" markdown=1>

## Mechanics

The main mechanics are:

* 2 different graphic styles
* Educational dialogues
* 1 painting → 1 level
* Cinematics
* 2 bosses
* 2 levels
* Sounds
* Weapons
* Main menu with variations
* Game in Spanish and English

</div>

<div class="col-lg-12 text-center" markdown=1>

## My work

I was the main programmer, I made the menus, the bosses code, the weapons system, the cinematics system, and helped to implement some character mechanics.

## Images

{% include carousel.html gallery=page.gallery %}
{% include modal.html  gallery=page.gallery modal_id='lightboxModal' img_id='lightbox-img' %}

</div>

{% include related_posts.html property="project_id" value=page.project_id %}
