---
layout: default
title: Comics
---
{% assign ordered_comics = site.comics | sort: "display-order" %}

<div class="posts">
  <h1>Comics</h1>
  {% for comic in ordered_comics %}
    <article class="post">

      <div class="entry">
        {{ comic.content }}
      </div>

      <a href="{{ site.baseurl }}{{ comic.url }}" class="read-more">#</a>

    </article>
  {% endfor %}
</div>
