---
layout: page
title: Today's
tagline: Strain Reviews
---
{% include JB/setup %}

<div class="col-xs-12 col-md-4">
  <div class="list-group">
    <h3>Sativa</h3>
    {% for post in site.categories.sativa %}
        <a href="{{ BASE_PATH }}{{ post.url }}" class="list-group-item">
          <h4 class="list-group-item-heading">{{ post.title }}</h4>
          <p class="list-group-item-text">
            {{ post.description }}
          </p>
        </a>
    {% endfor %}    
  </div>
</div>

<div class="col-xs-12 col-md-4">
  <div class="list-group">
    <h3>Hybrid</h3>
    {% for post in site.categories.hybrid %}
        <a href="{{ BASE_PATH }}{{ post.url }}" class="list-group-item">
          <h4 class="list-group-item-heading">{{ post.title }}</h4>
          <p class="list-group-item-text">
            {{ post.description }}
          </p>
        </a>
    {% endfor %}    
  </div>
</div>

<div class="col-xs-12 col-md-4">
  <div class="list-group">
    <h3>Indica</h3>
    {% for post in site.categories.indica %}
        <a href="{{ BASE_PATH }}{{ post.url }}" class="list-group-item">
          <h4 class="list-group-item-heading">{{ post.title }}</h4>
          <p class="list-group-item-text">
            {{ post.description }}
          </p>
        </a>
    {% endfor %}    
  </div>
</div>


