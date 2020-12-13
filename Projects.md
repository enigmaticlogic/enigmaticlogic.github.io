---
layout: page
title: Projects
permalink: /Projects/
---

My projects

### Project Info

<div class="posts">
  {% for post in site.categories.Project %}
    <article class="post">

      <h1><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></h1>

      <div class="entry">
        {{ post.excerpt }}
      </div>

    </article>
  {% endfor %}
</div>

### Contact me

[email@domain.com](mailto:email@domain.com)
