---
layout: default
tagline: engineer in spe
---

<!-- {% include JB/setup %} -->

<!-- 
<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul> -->

<ul id="posts">
  {% for post in site.posts %}
  <li>
    <article class="post">
      <header>
        <h2 class="post-title"><a class="post-title-url" href="{{ post.url }}">{{ post.title }}</a></h2>
      </header>
      <time class="post-date">{{ post.date | date_to_string }}</time>
    </article>
  </li>
  {% endfor %}
</ul>