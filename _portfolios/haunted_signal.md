---
layout: portfolio
title: "Haunted Signal"
categories: ["VideoGame Projects","Unity3D"]
thumbnail: "/assets/images/portfolio/p-2.jpg"
description: "An horror/mistery game where you have to go out of a haunted house"
###################### Team ######################
team:
  enable : true
  item:
  - name : "Joan Cortés"
    designation : "Manager"
    image : "/assets/images/team/team-1.jpg"
    
  - name : "Marc López Macías"
    designation : "3D Artist"
    image : "/assets/images/teams/marc.png"
    
  - name : "Gerard Bystron Santanach"
    designation : "Programmer and Game Designer"
    image : "/assets/images/teams/gerard.png"
---
<div class="col-lg-8 text-center">
	<h3 class="mb-5 mt-2">{{page.title}}</h3>
	<p>{{page.description}}</p>

<hr class="my-5">
	
<div class="row">
		<div class="col-lg-12 text-center">
			<p class="text-color font-weight-bold mb-2">Category</p>
			<p>{% for category in page.categories %} {{category}}{% unless forloop.last %} , {% endunless %} {% endfor %}</p>
		</div>
		<div class="col-lg-12 text-center">
			<p class="text-color font-weight-bold mb-2"></p>
			<p></p>
		</div>
	</div> 
	
	
<h2>Related Posts</h2>
<ul>
{% for post in site.posts %}
  {% if post.categories contains "Unity3d" or post.categories contains "Unity projects" %}
    <li><a href="{{ post.url}}">{{ post.title   post.header.image}}</a>
	</li>
	
  {% endif %}
{% endfor %}
</ul>


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
</div> 
 {% include share_this_on.html %}

 
</section>
<div class="col-lg-8 text-center mt-5">
	<p>Dolor sit amet consectetur elit sed do eiusmod tempor incididunt labore et dolore magna aliqua enim minim veniam quis nostrud exercitation ullamco laboris nisi aliquip commodo consequat.duis aute irure sint occae cat cupidatat non proident sunt in culpa qui officia deserunt mollit anim id est laborum. Sed perspiciatis unde omnis iste natus error sit voluptatem.
	</p>
</div>	
{% include team.html %}	 
