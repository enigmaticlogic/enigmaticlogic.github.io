---
layout: page
title: Projects
categories: Projects
permalink: /Projects/
---

My projects

### Project Info

{% for post in site.categories[Projects] %}
    <article class="post">

      <h1><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></h1>

      <div class="entry">
        {{ post.excerpt }}
      </div>

    </article>
{% endfor %}

### Contact me

[email@domain.com](mailto:email@domain.com)
