---
layout: page
title: Projects
permalink: /projects/
---

<div class="row">

  {% for projects in site.projects %}

    <a href="{{ projects.url | prepend: site.baseurl }}">
      <div class="col-xs-12 col-sm-6 col-md-4">
        <div class="panel panel-primary">
          <div class="panel-heading">
              {{ projects.title }}
          </div>
          <div class="panel-body">
            {{ projects.excerpt }}
          </div>
        </div>
      </div>
    </a>

  {% endfor %}

</div>
