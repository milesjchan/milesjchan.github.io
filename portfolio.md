---
layout: page
title: Portfolio
permalink: /portfolio/
---

<div class="row">

  {% for portfolio in site.portfolio %}

    <a href="{{ portfolio.url | prepend: site.baseurl }}">
      <div class="col-xs-12 col-sm-6 col-md-4">
        <div class="panel panel-primary">
          <div class="panel-heading">
              {{ portfolio.title }}
          </div>
          <div class="panel-body">
            {{ portfolio.excerpt }}
          </div>
        </div>
      </div>
    </a>

  {% endfor %}

</div>

ME2110 project

Hack-A-Thing

Broach press  