---
layout: page
title: Practicas
permalink: /practicas-iaw/
---
<ul class="post-list">
    {% for post in site.categories.practicas %}
      <li>
        <span class="post-meta">{{ post.date | date: "%b %-d, %Y" }}</span>

        <h2>
          <a class="post-link" href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
        </h2>
      </li>
    {% endfor %}
  </ul>

practicas