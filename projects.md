---
layout: page
title: Projects
permalink: /projects/
---

<div class="card-columns">
  {% for projects in site.projects %}
      <!-- <div class="col-xs-12 col-sm-6 col-md-4"> -->
      <a href="{{ projects.url | prepend: site.baseurl }}">
        <div class="card">
          <img class="card-img-top" src="{{site.url}}/assets/projects/{{ projects.thumbnail }}" alt="Card image">
          <div class="card-header">
              {{ projects.title }}
          </div>
        </div>
      </a>
      <!-- </div> -->
  {% endfor %}
</div>
