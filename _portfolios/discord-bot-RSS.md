---
project_id: "RssDiscordBot" 
layout: project
title: "RssDiscordBot"
categories: ["Application Projects"]
description: "An open-source Discord bot that fetches tweets from RSS feeds and sends them to designated channels"
thumbnail: assets/images/applications/figurasbot_logo.png
team:
  enable : true
  item:
  - name : "Joan Cortés"
    designation : "Backend Developer"
    image : "/assets/images/teams/logo300.png"
tags:
  - Python
  - Discord
  - RSS
  - Twitter
  - Nitter
  - Firebase
  - Open Source
  - Hobby project
download: true
download_link: "https://github.com/CortesJoan/DiscordRSSBot"
download_title: "Github Source"
gallery:
  - url: /assets/images/applications/botWorking1.png
    image_path: /assets/images/applications/botWorking1.png
    alt: "The bot in action"
    title: "The bot in actionn"
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

RssDiscordBot is an open-source Discord bot designed to fetch tweets from a specified Twitter account's RSS feed  and send them to designated channels on a Discord server. This bot provides a reliable solution for keeping your Discord community updated with the latest tweets from a Twitter account, without the need for direct Twitter integration.

By making the code available to the public, you can now run your own instance of RssDiscordBot and target any Twitter account you wish, ensuring a seamless integration with your Discord server.

## Motivation

As a moderator of an Discord anme community, I wanted a free alternative to keep the community updated with the latest tweets.
</div>

<div class="col-lg-8 text-center" markdown=1>

## Developer

<div class="col-lg-8 text-center" markdown=1>
{% include team.html %}
</div>

## Key Features

- Fetches tweets from a specified Twitter account using RSS feeds from multiple Nitter instances (Twitter front-ends focused on privacy)
- Posts new tweets to configured Discord channels
- Allows dynamic management of target Discord channels using bot commands
- Stores sent tweet links in Firebase Realtime Database for data persistence
- Provides commands to start, pause, restart, or force sending tweets
- Retrieves specific or all recent tweets using bot commands
- Customizable interval for checking for new tweets

## Technical Highlights

- Utilizes the discord.py library for seamless integration with the Discord API
- Fetches tweet data from Twitter using RSS feeds, eliminating the need for the Twitter API
- Employs Firebase Realtime Database for persistent storage of bot configuration and sent tweet links
- Implements a modular architecture with separate classes for the bot, RSS feed handling, and Firebase service
- Supports dynamic addition and removal of target Discord channels using bot commands
- Hosted on Render for reliable and continuous operation

</div>

<div class="col-lg-8 text-center" markdown=1>

## Code Structure

The project is structured into multiple Python files for modularity and maintainability:

- `bot.py`: Contains the main `RssDiscordBot` class that handles the bot functionality and commands
- `rss_feed.py`: Implements the `RSSFeed` class responsible for fetching and parsing the Twitter RSS feed from Nitter instances
- `firebase_service.py`: Provides the `FirebaseService` class for interacting with the Firebase Realtime Database
- `main.py`: The entry point of the application that initializes the bot and starts the event loop
- `keep_alive.py`: A utility script to keep the bot running continuously on the hosting platform

## Hosting

FigurasBot is hosted on Render, a cloud platform for running web services and applications. Render provides a reliable and scalable environment for hosting the bot, ensuring its continuous operation and availability.

## The bot working

 {% include carousel.html gallery=page.gallery %}
 {% include modal.html  gallery=page.gallery modal_id='lightboxModal' img_id='lightbox-img' %}

## Future Enhancements

- Implement a user-friendly web interface for managing bot settings and target channels
- Add support for multiple Twitter accounts and RSS feeds
- Enhance error handling and logging for better monitoring and debugging
- Explore integration with other social media platforms beyond Twitter

## Limitations and Known Issues

- The bot relies on the availability and reliability of Nitter instances, which may vary.
- The bot does not handle rate limiting or other potential issues that may arise from frequent requests to Nitter instances (there are multiple instances by default to mitigate this issue) and there  are security measures to stop using rate limited instances.
- The bot does not support direct Twitter integration and relies solely on RSS feeds provided by Nitter instances.

</div>
{% include related_posts.html property="project_id" value=page.project_id %}
