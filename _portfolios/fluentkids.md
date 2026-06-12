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
  - Professional Projects
team:
  enable : true
  item:
  - name : "Fluentkids Team"
    designation : "EdTech Company"
    image : "/assets/images/teams/logo300.png"
download: true
download_link: "https://fluentkids.com/es"
download_title: "Visit Fluentkids Website"
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

Fluentkids is a fun, playful, and interactive English learning platform designed specifically for children. It levels up children's language skills through a combination of native-speaker lessons, game-like activities, and engaging interactive challenges.

* **Official Website (Spanish)**: [fluentkids.com/es](https://fluentkids.com/es)
* **Official Website (English)**: [fluentkids.com/en](https://fluentkids.com/en)

## My Work Here

As a professional developer on the team, my work focuses on building and expanding the platform:

### Interactive Gameplay & Learning Systems
* Designed and implemented gamified interactive activities and mini-games to help children learn vocabulary and grammar in a natural, playful way.
* Engineered clean, modular gameplay components in Unity to support fast iteration on new educational content.

### Fullstack & Integration
* Contributed to the backend systems, APIs, and client-server integration to ensure smooth progress tracking and user authentication.
* Applied clean code practices and design patterns to keep the codebase scalable and maintainable.

## Developers

{% include team.html %}

</div>
