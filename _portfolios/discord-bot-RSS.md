---
project_id: "FigurasBot" 
layout: project
title: "FigurasBot"
categories: ["Application Projects"]
description: "A Discord bot that fetches and sends tweets from an RSS feed to designated channels"
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
  - Firebase
  - Solo project
  - Hobby project
download: false
download_link: "no for the moment is a private repo"
download_title: "Github Source"
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

FigurasBot is a Discord bot developed to solve a specific need - fetching tweets from an anime figures Twitter account and sending them to designated channels on a Discord server. This was motivated by recent issues with Twitter bots on Discord. As a moderator of an anime Discord community, I wanted a free alternative to keep the community updated with the latest tweets.

The bot is built using Python and leverages the discord.py library to interact with the Discord API. It fetches tweet data from Twitter using RSS feeds, allowing it to bypass the need for the Twitter API. The bot is designed to be easily configurable, with the ability to specify the RSS feed URL, target Discord channels, and the interval at which to check for new tweets.

</div>

<div class="col-lg-8 text-center" markdown=1>

## Developer

<div class="col-lg-8 text-center" markdown=1>
{% include team.html %}
</div>

## Technical Highlights

- Utilizes the discord.py library for seamless integration with the Discord API
- Fetches tweet data from Twitter using RSS feeds, eliminating the need for the Twitter API
- Employs Firebase Realtime Database for persistent storage of bot configuration and sent tweet links
- Implements a modular architecture with separate classes for the bot, RSS feed handling, and Firebase service
- Supports dynamic addition and removal of target Discord channels using bot commands
- Hosted on Render for reliable and continuous operation

## Features

- Fetches tweets from a specified Twitter RSS feed at regular intervals
- Sends the fetched tweets to designated channels on a Discord server
- Allows dynamic management of target Discord channels using bot commands
- Stores bot configuration and sent tweet links in Firebase for data persistence
- Provides commands to start, pause, and retrieve RSS feed entries
- Hosted on Render for 24/7 availability

</div>

<div class="col-lg-8 text-center" markdown=1>

## Code Structure

The project is structured into multiple Python files for modularity and maintainability:

- `bot.py`: Contains the main `FigurasBot` class that handles the bot functionality and commands
- `rss_feed.py`: Implements the `RSSFeed` class responsible for fetching and parsing the Twitter RSS feed
- `firebase_service.py`: Provides the `FirebaseService` class for interacting with the Firebase Realtime Database
- `main.py`: The entry point of the application that initializes the bot and starts the event loop
- `keep_alive.py`: A utility script to keep the bot running continuously on the hosting platform

## Hosting

FigurasBot is hosted on Render, a cloud platform for running web services and applications. Render provides a reliable and scalable environment for hosting the bot, ensuring its continuous operation and availability.

## Future Enhancements

- Implement a user-friendly web interface for managing bot settings and target channels
- Add support for multiple Twitter accounts and RSS feeds
- Enhance error handling and logging for better monitoring and debugging
- Explore integration with other social media platforms beyond Twitter

</div>
 