---
project_id: "Fast&Fractured"
layout: project
title: "Fast & Fractured"
categories: ["Personal Video game Projects"]
showOnlySameCategoryInRelatedProjects: true
thumbnail: "/assets/images/games/fast-and-fractured/josefino-portrait.png"
description: "Frenetic physics-based driving shooter for up to 12 contenders"
post_image: "/assets/images/games/fast-and-fractured/splashScreen.png"


tags:
  - C#
  - Cartoon
  - Online
  - Netcode
  - Group project
download: true
download_link: "https://cevr-icales.itch.io/fast-fractured"
download_title: "Download the demo on itch.io"
###################### Team ######################
team:
  enable : true
  item:
  - name : "CEVR-ICALES"
    designation : "Development Team (<a href='https://cevr-icales.itch.io/fast-fractured' target='_blank'>see full team on itch.io</a>)"
    image : "/assets/images/teams/cevricales-logo-300.png"
gallery:
  - url: /assets/images/games/fast-and-fractured/gold.png
    image_path: /assets/images/games/fast-and-fractured/gold.png
    alt: "Look at gold josefino statue"
    title: "Look at gold josefino statue"
  - url: /assets/images/games/fast-and-fractured/pushshoot.gif
    image_path: /assets/images/games/fast-and-fractured/pushshoot.gif
    alt: "Push shoot"
    title: "Push shoot!"
  - url: /assets/images/games/fast-and-fractured/ultimate-carme.gif
    image_path: /assets/images/games/fast-and-fractured/ultimate-carme.gif
    alt: "Ultimate carme ability"
    title: "Ultimate carme ability"
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

Step into the dusty streets of a dynamic, **sun-baked Spanish village** and prepare for Fast and Fractured experience, a **frenetic physics-based driving shooter** for up to 12 contenders—all AI-controlled in a **single-player free-for-all**. Choose from 4 colorful characters, **each sporting 2 unlockable skins**, and battle it out across a map **inspired by** a stereotypical, **old-school Spanish town** while having fun with cheeky elder-villager humor.

**Four Distinct Drivers:** Pick one of four quirky locals—each with two unique skins—and master their handling quirks.

**Frenetic Physics Combat:** Ram, dash, and blast opponents into the dust, leveraging realistic weight, grip, and push-shot mechanics.

**Single-Player Showdown:** No multiplayer headaches—jump straight into AI mayhem for quick, chaotic rounds.

**Beloved Locales:** Battle across iconic spots like the golf club, an Alien Forest out on the outskirts, the typical Spanish plaza, and more.

**Vibrant, Stereotypical Charm:** Overflowing with Spanish jokes, elder-villager antics, and brightly colored, cartoon-inspired art.

**Quick Matches, Big Laughs:** Perfect for streamers and content creators seeking dynamic, shareable moments.
</div>

<div class="col-lg-8 text-center" markdown=1>

## Developers

{% include team.html %}

## Data sheet

* **Engine**: Unity3d
* **Release**: PC
* **Genre**: Shooter, Hero Shooter, Battle Royale
* **Mode(s)**: Singleplay/Multiplayer PvP in progress (2-12 players)
* **Graphic Style**: 3D Cartoony
</div>

<div class="col-lg-8 text-center" markdown=1>

## Mechanics

 &ensp; &ensp;  

At its heart, Fast & Fractured is all about dynamic, physics-driven vehicular combat where your main goal is to send your rivals flying! Here's how you'll dominate the village:

*   **Vehicular Mayhem:** Master intuitive car-based movement, including **acceleration, sharp reversing, and tight turns**. Each of the four distinct vehicles boasts unique **handling characteristics** influenced by its **weight, speed, acceleration, traction, and more**, making every choice impactful.
*   **Push your opponents away** The core of combat revolves around pushing your opponents out of the arena.
    *   **Standard Shooting:** A continuous firing action to chip away at rivals, making them more susceptible to being pushed.
    *   **Push Shot:** A tactical ability with a short cooldown (3 seconds) designed to forcefully shove enemies, perfect for sending them over the edge. This can be aimed precisely, even on the move.
*   **Dash to Dominate:** Unleash a spontaneous burst of speed in your current direction, **ignoring typical physics** for a moment to deliver powerful shoves or make daring escapes. This ability has a cooldown to keep things balanced.
*   **Unique Character Abilities:** Each of the four quirky drivers comes equipped with a **special, cooldown-based ability** that adds a unique strategic layer to their playstyle (like Carme's deployable "McChicken" or Maria Antonia's "Croquette" fueled power-up).
*   **Advanced Driving Techniques:**
    *   **Handbrake Stop:** Quickly halt your momentum for precise positioning.
    *   **Drifting:** Maintain speed while cornering by skillfully using the handbrake and acceleration.
    *   **Aerial Control:** Use the handbrake mid-air to slightly adjust your car's rotation and aim for that perfect landing.
*   **Interactive Environment:** The battlefield itself is part of the chaos! Push various props scattered around the map:
    *   **Light Props:** Easily sent flying, these can even knock other players around.
    *   **Medium Props:** Will slow you down as you push them, but can be used strategically.
    *   **Heavy Props:** Immovable obstacles that will bring your car to a dead stop.
*   **The Encroaching Sandstorm:** To ensure matches reach a climactic finish, a deadly sandstorm periodically shrinks the playable area from one of four random directions, forcing intense final confrontations.

</div>



<div class="col-lg-12 text-center" markdown=1>

## Gameplay

<iframe src="https://drive.google.com/file/d/1Ix929TsCArMUuBlSz4XNdIzfBCxACh4H/preview" width="640" height="360" allow="autoplay"></iframe>
</div>

<div class="col-lg-12 text-center" markdown=1>

## My work
* **AI Implementation:** Design from scratch the AI of the game used for the bots.
* **Tools for artists:** I made tools to integrate artists art in the project following the project TDD. For example there is a tool that can import 80 fbx models with the corresponding folders at once making them share a material if needed.
* **Tools for game designers:** I made tools to speed up the map development. An example of this is a set of tools to create AI navigable obstacles.
* **Multiplayer (WIP):** Currently developing the multiplayer mode of the game while having and abstraction layer to avoid redoing all the game code.
* **Prop behaviours:** For instance the code to have designer friendly traffic lights between other things.
* **General system mechanics:** Helped with other mechanics related to the car

## Images

{% include carousel.html gallery=page.gallery %}
{% include modal.html  gallery=page.gallery modal_id='lightboxModal' img_id='lightbox-img' %}

</div>

{% include related_posts.html property="project_id" value=page.project_id %}