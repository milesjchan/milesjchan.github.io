---
layout: page
title: Projects
permalink: /projects/
---

<div class="card-deck">
  {% for projects in site.projects %}
    <!-- <a href="{{ projects.url | prepend: site.baseurl }}"> -->
      <!-- <div class="col-xs-12 col-sm-6 col-md-4"> -->
        <div class="card">
          <img class="card-img-top" src="{{site.url}}/assets/projects/{{ projects.thumbnail }}" alt="Card image">
          <div class="card-header">
              {{ projects.title }}
          </div>
        </div>
      <!-- </div> -->
    <!-- </a> -->
  {% endfor %}
</div>
