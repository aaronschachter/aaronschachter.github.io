---
layout: default
title: Haiku
---
{% assign ordered_haiku = site.haiku | sort: "display-order" %}

<div class="posts">
  <h1>Haiku</h1>
  {% for haiku in ordered_haiku %}
    <article class="post">

      <div class="entry">
        {{ haiku.content }}
      </div>

      <a href="{{ site.baseurl }}{{ haiku.url }}" class="read-more">#</a>

    </article>
  {% endfor %}
</div>
