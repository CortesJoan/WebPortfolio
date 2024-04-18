---
project_id: "Meowfy"
layout: project
title: "Meowfy"
categories: ["Application Projects"]
description: "A simple music player made with Java and Android Studio"
showOnlySameCategoryInRelatedProjects: false
thumbnail: assets/images/applications/meowfyLogo.png
download: true
download_link: "(https://github.com/CortesJoan/Meowfy"
download_title: "Github Source"
tags:
  - Java
  - Android
  - Pair project
 
###################### Team ######################
team:
  enable : true
  item:
  - name : "Joan Cortés"
    designation : "Backend Developer"
    image : "/assets/images/teams/logo300.png"
    
  - name : "Sergi Granell "
    designation : "Frontend Developer"
    image : "/assets/images/teams/sergi.png"

gallery:
  - url: /assets/images/applications/launchScreen.png
    image_path: /assets/images/applications/launchScreen.png
    alt: "Launch screen"
    title: "The launch screen"
  - url: /assets/images/applications/homeScreen.png
    image_path: /assets/images/applications/homeScreen.png
    alt: "The home screen"
    title: "The home screen"
  - url: /assets/images/applications/library.png
    image_path: /assets/images/applications/library.png
    alt: "The library"
    title: "The music library"
  - url: /assets/images/applications/playlist.png
    image_path: /assets/images/applications/playlist.png
    alt: "A playlist example"
    title: "A playlist example"
  - url: /assets/images/applications/searchScreen.png
    image_path: /assets/images/applications/searchScreen.png
    alt: "The search screen"
    title: "The search screen"
  - url: /assets/images/applications/player.png
    image_path: /assets/images/applications/player.png
    alt: "The player"
    title: "The player"          
---

<div class="col-lg-8 text-center" markdown=1>

## {{page.title}}

     {{page.description}}

</div>

  <div class="col-lg-12 text-center">
   <p class="text-color font-weight-bold mb-2">Category</p>
   <p>{% for category in page.categories %} {{category}}{% unless forloop.last %} , {% endunless %} {% endfor %}</p>
  </div>
 <div class="col-lg-12 text-center" markdown=1>

## Description

A simple music player using the Spotify API made by 2 people
</div>

<div class="col-lg-12 text-center" markdown=1>

## Developers

<div class="col-lg-12 text-center" markdown=1>
{% include team.html %}
</div>
## Data sheet

* **Made with**: Android Studio
* **Release**: Android
* **Developer(s)**: Sergi Granell, Joan Cortés

## Features

* Add your favorite songs to a favorite list
* Recommendations
* A simple player with shuffle, loop, etc.
* Save playlists to your library or create your own
* Search that works with songs, artists, and playlists
* Login using Spotify account

</div>
## My work

Mainly, I did the backend work of the app (the API connection, data management, JSON parsing) and the player features.


## Images

 {% include carousel.html gallery=page.gallery %}
 {% include modal.html  gallery=page.gallery modal_id='lightboxModal' img_id='lightbox-img' %}

## Demo video

<div class="col-lg-12 text-center" markdown=1>
 <iframe width="640" height="360" src="https://drive.google.com/file/d/1CcLzuNwkFhcgXEirxSiKj_etGGEm17rS/preview?usp=sharing" frameborder="0" allowfullscreen></iframe>
</div>

<div class="col-lg-12 text-center" markdown=1>


</div>

{% include related_posts.html property="project_id" value=page.project_id %}
