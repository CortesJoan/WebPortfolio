---
project_id: "Meowfy"
layout: project
title: "Meowfy"
categories: ["Application Projects"]
description: "Meowfy is a music player application that leverages the Spotify API to provide users with a seamless music streaming experience. "
showOnlySameCategoryInRelatedProjects: false
thumbnail: assets/images/applications/meowfyLogo.png
download: true
download_link: "https://github.com/CortesJoan/Meowfy"
download_title: "Github Source"
tags:  
 - Java  
 - Android  
 - Pair project 
 - Spotify API 
 - Backend Development
 - Music Streaming
###################### Team ######################
team:  
 enable : true  
 item:  
 - name : "Joan Cortés"    
   designation : "Backend Developer"    
   image : "/assets/images/teams/logo300.png"      
 - name : "Sergi Granell "    
   designation : "Frontend Developer"    
   image : "/assets/images/teams/sergi2b.jpg"
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

## Developers

{% include team.html %}
</div>

<div class="col-lg-12 text-center" markdown=1>

##  Data sheet

* **Made with**: Android Studio
* **Release**: Android
* **Developer(s)**: Sergi Granell, Joan Cortés

</div>

## Features

<div class="col-lg-12 text-center" markdown=1>

* A simple but functional player with shuffle, loop, etc.
* Add your favorite songs to a favorite list
* Save playlists to your library or create your own
* Search that works with songs, artists, and playlists
* Login using Spotify account
* You get the recommendations of new songs based on your listening habits

</div>

## Technical Highlights

<div class="col-lg-12 text-center" markdown=1>

* **API Integration:** Successfully integrated the Spotify Web API to access user data, playlists, and enable music streaming functionalities.
* **Data Management:** Implemented efficient data management strategies using Firebase Realtime Database for storing and retrieving user preferences and playlists.
* **JSON Parsing:** Utilized JSON parsing libraries (e.g., Gson) to process data received from the Spotify API and ensure smooth integration with the application.
* **Backend Logic:** Developed the core backend logic for user authentication, music library access, playlist management, and player features.
* **Collaboration:** Collaborated effectively with the frontend developer to ensure seamless communication and synchronization between the user interface and the backend logic.
* **Backend Logic:** Fragments based frontend

</div>

<div class="col-lg-12 text-center" markdown=1>

## My Work

My primary focus was on building the backend infrastructure of Meowfy. I utilized the Spotify Web API to handle user authentication, access user data and playlists, and enable music playback. This involved extensive JSON parsing and data manipulation to seamlessly integrate Spotify's functionalities within the application. Additionally, I implemented data management strategies to ensure efficient storage and retrieval of user preferences and playlists.

Furthermore, I collaborated with the frontend developer to implement core player features such as shuffle and loop, ensuring smooth communication and synchronization between the user interface and the backend logic.

</div>

## Images

<div class="col-lg-12 text-center" markdown=1>

{% include carousel.html gallery=page.gallery invert_icons=true %}
{% include modal.html  gallery=page.gallery modal_id='lightboxModal' img_id='lightbox-img' invert_icons=true %}

</div>

## Demo video

<div class="col-lg-12 text-center" markdown=1>
<iframe width="1024" height="1024" src="https://drive.google.com/file/d/1CcLzuNwkFhcgXEirxSiKj_etGGEm17rS/preview?usp=sharing" frameborder="0" allowfullscreen></iframe>

</div>

## Future Enhancements

<div class="col-lg-12 text-center" markdown=1>

* **Offline Playback:** Explore options for enabling offline music playback to enhance user experience.
* **Social Features:** Integrate social features allowing users to share playlists  outside the application and discover music with friends.
* **Lyrics Integration:**  Explore options for displaying song lyrics within the application.
* **Port the application to iOS systems**  Integrate the application in Apple ecosystem.

</div>

{% include related_posts.html property="project_id" value=page.project_id %}
