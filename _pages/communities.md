---
layout: base
title: Comunidades
heading: Comunidades
permalink: /Comunidades/
description: Encuentra la comunidad de tu ciudad.
---

<header class="subpage-header">
  <h1>{{ page.heading }}</h1>
</header>

<div class="content subpage-content">
  <section class="section-pad">
    <div style="text-align:center" class="row column">
      <p class="lead">
       Encuentra la comunidad de tu ciudad.
      </p>
      <div  class="row ">

      <div class="column medium-4">
      <ul style="text-align: left;">
            {% for communnity in site.communities %}
             <li> <a href="/comunidades/{{ communnity.slug }}"> {{ communnity.name }} </a> </li>
            {% endfor %}
      </ul>  
      </div>


      </div>
    </div>
  </section>
</div><!-- end .content -->