---
project_id: "FoodBattle"
layout: project
title: "Food battle"
categories: ["VideoGame Projects","Unity3D"]
thumbnail: "/assets/images/portfolio/p-2.jpg"
description: "Online multiplayer RTS  made with Unity and Mirror"
thumbnail: assets/images/foodBattles1.png
tags:
  - C#
  - Cartoon
  - Online
  - GameJam
  - Netcode
  - Group project
 
###################### Team ######################
team:
  enable : true
  item:
  - name : "Joan Cortés"
    designation : "Lead Programmer"
    image : "/assets/images/teams/logo300.png"
    
  - name : "Eric Bujaldon Marco"
    designation : "3D Artist"
    image : "/assets/images/teams/eric.png"
    
  - name : "Sergi Granell "
    designation : "Programmer and Lead Game Designer"
    image : "/assets/images/teams/sergi.png"
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

<div class="row">
  <div class="col-lg-12 text-center">
   <p class="text-color font-weight-bold mb-2">Category</p>
   <p>{% for category in page.categories %} {{category}}{% unless forloop.last %} , {% endunless %} {% endfor %}</p>
  </div>
  <div class="col-lg-12 text-center">
   <p class="text-color font-weight-bold mb-2">Si se quieren poner mas tags en rojo</p>
   <p>aqui habia algo?</p>
  </div>
</div>

<div class="col-lg-8 text-center" markdown=1>

## Description
{% for portfolio in site.portfolios %}
  {{ portfolio.title }} - {{ portfolio.project_id }}<br>
{% endfor %}  
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

The main mechanics are:

* Construction.
* Resource collection.
* Combat.
* Expiration.
* Morale buffs and debuffs.

  </div>

## Gameplay

<div class="col-lg-12 text-center" markdown=1>
 <iframe width="640" height="360" src="https://drive.google.com/file/d/1pIRTbpWstjJ8MoKduW5ypt_UIMwg-sko/preview?usp=sharing" frameborder="0" allowfullscreen></iframe>
</div>

<div class="col-lg-12 text-center" markdown=1>

## My work

Mainly, I have been dedicated to the implementation of the multiplayer and the development of tools for the game designer. Although I have also programmed basic mechanics including some units and buildings

## Images
  
   {% include carousel.html gallery=page.gallery %}
{% include modal.html modal_id='lightboxModal' img_id='lightbox-img' %}


 {% include modal.html %}

<!-- Script for Modal Begins Here -->
<script>
$(document).ready(function() {
    $('.carousel img').click(function(event) {
        event.preventDefault(); // Prevent the default action

        var imgSrc = this.src;
        $('#lightbox-img').attr('src', imgSrc);

        console.log('Modal should be open now without jumping the page.'); // Debug message
    });

    // Check if the modal is being shown and log it
    $('#lightboxModal').on('show.bs.modal', function () {
        console.log('Modal is being shown.');
    });

    // Check if the modal has finished being hidden and log it
    $('#lightboxModal').on('hidden.bs.modal', function () {
        console.log('Modal has been hidden.');
    });
});
</script>

## Download

 [GitLab Source](https://gitlab.com/EvilHack/RTSeadosProject){: .btn .btn--primary}

</div>

<div class="col-lg-12 text-center" markdown=1>

 
</div>
{% include related_posts.html property="project_id" value=page.project_id %}


 {% include share_this_on.html %}
