---
layout: portfolio
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
body: >
  ## Description
  This game is an online multiplayer RTS(max 4 players)  made with the Unity engine and the Mirror and FizzySteamworks addons to make the game work with Steam servers.
  In the game you have to command your food faction to become the best food in the table destroying all the other factions.
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

Mainly, I have been dedicated to the implementation of the multiplayer and the development of tools for the game designer. Although I have also programmed basic mechanics and some units and buildings

## Images

 {% include gallery caption="Food Battle Sample Images" %}
Explain
  
<!-- Carousel Begins Here -->
<div id="carouselExampleIndicators" class="carousel slide" data-ride="carousel">
  carrousel a
  <ol class="carousel-indicators">
    {% for image in page.gallery %}
      <li data-target="#carouselExampleIndicators" data-slide-to="{{ forloop.index }}" class="{% if forloop.first %}active{% endif %}"></li>
    {% endfor %}
  </ol>
    <a class="carousel-control-prev" href="#carouselExampleIndicators" role="button" data-slide="prev">
    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
    <span class="sr-only">Previous</span>
  </a>
  <a class="carousel-control-next" href="#carouselExampleIndicators" role="button" data-slide="next">
    <span class="carousel-control-next-icon" aria-hidden="true"></span>
    <span class="sr-only">Next</span>
  </a>
  <div class="carousel-inner">
    {% for image in page.gallery %}
      <div class="carousel-item {% if forloop.first %} active {% endif %}">
        <img class="d-block w-100" src="{{site.baseurl}}{{ image.image_path }}"
             alt="{{ image.alt }}"
             data-toggle="modal"
             data-target="#lightboxModal">
      </div>
    {% endfor %}
  </div>
  </div>

<!-- Modal Begins Here -->
<div class="modal fade" id="lightboxModal" tabindex="-1" role="dialog" aria-labelledby="exampleModalLabel" aria-hidden="true">
  <div class="modal-dialog modal-dialog-centered modal-lg" role="document">
    <div class="modal-content">
      <div class="modal-body">
        <img src="" class="img-fluid" id="lightbox-img">
      </div>
      <div class="modal-footer">
        <button type="button" class="btn btn-secondary" data-dismiss="modal">Close</button>
      </div>
    </div>
  </div>
</div>

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

{% include share_this_on.html %}
<div class="col-lg-8 text-center" >
 <h2>Related Posts</h2>
</div>

<ul>

{% for post in site.posts %}
  {% if post.categories contains "Unity3d" or post.categories contains "Unity projects" %}
    <li><a href="{{ post.url}}">{{ post.title   post.header.image}}</a></li>
  {% endif %}
{% endfor %}

</ul>

<h2>Related Posts</h2>
<ul>
{% for post in site.posts %}
  {% if post.categories contains "Unity3d" or post.categories contains "Unity projects" %}
    <li><a href="{{ post.url}}">{{ post.title   post.header.image}}</a>
 </li>

  {% endif %}
{% endfor %}
</ul>
 {% include share_this_on.html %}
