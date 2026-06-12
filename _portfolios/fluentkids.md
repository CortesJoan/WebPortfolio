---
project_id: "Fluentkids"
layout: project
title: "Fluentkids"
categories: ["Professional Projects"]
description: "An interactive, gamified English learning platform for children."
thumbnail: assets/images/portfolio/fluentkids_thumb.png
tags:
  - Unity 3d
  - C#
  - Fullstack Development
  - Tools Engineering
  - Professional Projects
team:
  enable : true
  item:
  - name : "Joan Cortés"
    designation : "Game & Tools Developer"
    image : "/assets/images/teams/logo300.png"
  - name : "Fluent Education SL"
    designation : "EdTech Studio"
    image : "/assets/images/portfolio/fluentkids_logo.svg"
download: true
download_link: "https://fluentkids.com/es"
download_title: "Visit Fluentkids Website"
gallery:
  - url: /assets/images/games/fluentkids/IMG_0659.jpeg
    image_path: /assets/images/games/fluentkids/IMG_0659.jpeg
    alt: "Interactive activity screenshot"
    title: "Vocabulary and letters activities"
  - url: /assets/images/games/fluentkids/IMG_0660.jpeg
    image_path: /assets/images/games/fluentkids/IMG_0660.jpeg
    alt: "Learning mini-games"
    title: "Interactive game-like lessons"
  - url: /assets/images/games/fluentkids/IMG_0661.jpeg
    image_path: /assets/images/games/fluentkids/IMG_0661.jpeg
    alt: "Educational challenges"
    title: "Teacher-approved activities"
  - url: /assets/images/games/fluentkids/IMG_0662.jpeg
    image_path: /assets/images/games/fluentkids/IMG_0662.jpeg
    alt: "Pronunciation and listening exercises"
    title: "Speaking and listening practice"
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

Fluentkids is a playful and interactive English learning platform designed for children aged 2 to 8. It leverages game-like activities, native-speaker lessons, and a safe, ad-free environment to make learning English natural and engaging.

* **Official Website (Spanish)**: [fluentkids.com/es](https://fluentkids.com/es)
* **Official Website (English)**: [fluentkids.com/en](https://fluentkids.com/en)

## My Work Here

My role at Fluentkids focuses on content development, maintenance, and building custom pipeline tools to improve efficiency:

### Content Development & Maintenance
* Developed new interactive educational content and activities in Unity / C#.
* Maintained and optimized existing gameplay mechanics and learning modules to ensure smooth performance across devices.

### Custom Tooling & Batch Generation
* Designed and built editor tools in Unity to streamline the development cycle for content creators.
* Created batch-processing scripts and automated generators to produce activities at scale, reducing manual overhead and speeding up content deployment.

## Developers

{% include team.html %}

## Screenshots

{% include carousel.html gallery=page.gallery %}
{% include modal.html modal_id='lightboxModal' img_id='lightbox-img' %}

</div>
