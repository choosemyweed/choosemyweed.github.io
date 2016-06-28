---
layout: home
title: Home
tagline: Find Weed in Northwest Washington
---
{% include JB/setup %}

<div class="col-xs-12 col-md-4">
  <div class="list-group sativa">
    <h3>Sativa</h3>
    {% for post in site.categories.sativa %}
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
    <h3>Hybrid</h3>
    {% for post in site.categories.hybrid %}
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
    <h3>Indica</h3>
    {% for post in site.categories.indica %}
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


