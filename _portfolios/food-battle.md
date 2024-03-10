---
layout: portfolio
title: "Food battle"
categories: ["VideoGame Projects","Unity3D"]
thumbnail: "/assets/images/portfolio/p-2.jpg"
description: "Online multiplayer RTS(max 4 players)  made with Unity"
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
---

 <!--Title and desription. -->
<div class="col-lg-8 text-center">
	<h3 class="mb-5 mt-2">{{page.title}}</h3>
	<p>{{page.description}}</p>
 <hr class="my-5">
	
  
    <!--Categories portfolio page list -->
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


<!--
<div class="row justify-content-center align-items-center text-center mb-5">
<div class="col-12">
	<div class="btn-group btn-group-toggle " data-toggle="buttons">
	<label class="btn border-0 active">
		<input type="radio" name="shuffle-filter" value="all" checked="checked" />All Projects
	</label>
	{% assign posts = site.posts| map: 'categories' | join: ',' | split: ',' | uniq %}
	{% for post in posts %}
	<label class="btn border-0">
		<input type="radio" name="shuffle-filter" value="{{ post | downcase | slugify }}" />{{ post }}
	</label>
	{% endfor %}
	</div>
	<div class="row shuffle-wrapper portfolio-gallery">
{% include portfolio_loop_posts.html %}
</div>
</div>
</div>   -->

 
 
{% include team.html %}	 

	
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