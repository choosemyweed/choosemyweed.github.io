---
layout: home
title: Choose My Weed ..
tagline: Find Weed in Skagit Valley
keywords: [weed, skagit, find weed, sativa, indica, hybrid]
---


<div class="col-xs-12 col-md-4">
  <div class="list-group sativa">
    <h2>Sativa</h2>
    {% assign strain_home_list = site.categories.sativa %}
    {% include JB/strain_home %}
    <li class="list-group-item list-text-right"><a href="{{ BASE_PATH }}types/sativa">sativa strain list</a></li>
  </div>
</div>

<div class="col-xs-12 col-md-4">
  <div class="list-group hybrid">
    <h2>Hybrid</h2>
    {% assign strain_home_list = site.categories.hybrid %}
    {% include JB/strain_home %}       
    <li class="list-group-item list-text-right"><a href="{{ BASE_PATH }}types/hybrid">hybrid strain list</a></li>
  </div>
</div>

<div class="col-xs-12 col-md-4">
  <div class="list-group indica">
    <h2>Indica</h2>
    {% assign strain_home_list = site.categories.indica %}
    {% include JB/strain_home %} 
    <li class="list-group-item list-text-right"><a href="{{ BASE_PATH }}types/indica">indica strain list</a></li>
  </div>
</div>


