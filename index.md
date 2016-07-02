---
layout: home
title: Choose My Weed ..
tagline: Find Weed in Skagit Valley
---


<div class="col-xs-12 col-md-4">
  <div class="list-group sativa">
    <h2>Sativa</h2>
    {% for post in site.categories.sativa limit:5 %}
      {% if post.thumbnail %}
        <a class="list-group-item container-relative" href="{{ BASE_PATH }}{{ post.url }}">
          <img class="thumb-edge" src="{{ post.thumbnail }}"/>
          <span class="content-center-text-absolute text-capitalize">
          <div>
            <h4>{{ post.title }}</h4>
            <h5>{{ post.farm }}</h5>
            </div>
          </span>
        </a>
      {% else %}  
        <a class="list-group-item" href="{{ BASE_PATH }}{{ post.url }}">
          <span class="text-capitalize">
            <h4>{{ post.title }}</h4>
            <h5>{{ post.farm }}</h5>
          </span>
        </a>
      {% endif %}
    {% endfor %}      
  </div>
</div>

<div class="col-xs-12 col-md-4">
  <div class="list-group hybrid">
    <h2>Hybrid</h2>
    {% for post in site.categories.hybrid limit:5 %}
      {% if post.thumbnail %}
        <a class="list-group-item container-relative" href="{{ BASE_PATH }}{{ post.url }}">
          <img class="thumb-edge" src="{{ post.thumbnail }}"/>
          <span class="content-center-text-absolute text-capitalize">
          <div>
            <h4>{{ post.title }}</h4>
            <h5>{{ post.farm }}</h5>
            </div>
          </span>
        </a>
      {% else %}  
        <a class="list-group-item" href="{{ BASE_PATH }}{{ post.url }}">
          <span class="text-capitalize">
            <h4>{{ post.title }}</h4>
            <h5>{{ post.farm }}</h5>
          </span>
        </a>
      {% endif %}
    {% endfor %}     
  </div>
</div>

<div class="col-xs-12 col-md-4">
  <div class="list-group indica">
    <h2>Indica</h2>
    {% for post in site.categories.indica limit:5 %}
      {% if post.thumbnail %}
        <a class="list-group-item container-relative" href="{{ BASE_PATH }}{{ post.url }}">
          <img class="thumb-edge" src="{{ post.thumbnail }}"/>
          <span class="content-center-text-absolute text-capitalize">
          <div>
            <h4>{{ post.title }}</h4>
            <h5>{{ post.farm }}</h5>
            </div>
          </span>
        </a>
      {% else %}  
        <a class="list-group-item" href="{{ BASE_PATH }}{{ post.url }}">
          <span class="text-capitalize">
            <h4>{{ post.title }}</h4>
            <h5>{{ post.farm }}</h5>
          </span>
        </a>
      {% endif %}
    {% endfor %}    
  </div>
</div>


