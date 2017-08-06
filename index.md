---
layout: newtheme
---

{% comment %}
 <div class="posts">
  {% for post in site.posts %}
    <article class="post">

      <figure class="figure">
        <img src="images/pastries.jpg" alt=""/>
        <ul>
          <li><a href="#"><img src="images/pastry1.jpg" alt=""/></a></li>
          <li><a href="#"><img src="images/pastry2.jpg" alt=""/></a></li>
          <li><a href="#"><img src="images/pastry3.jpg" alt=""/></a></li>
        </ul>
        <a href="#">click to enlarge images</a>
      </figure>

      <div>

        <h3><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></h3>

        <div class="entry">
          {{ post.excerpt }}
        </div>

        <a href="{{ site.baseurl }}{{ post.url }}" class="read-more">Read More</a>
      </div>
    </article>
  {% endfor %}
</div>

{% include pagination.html %}

{% endcomment %}

{% comment %} {% include hero.html %} {% endcomment %}

{% comment %} {% include featured-pages.html %} {% endcomment %}

## Coming soon!

Please check back, this site is a work in progress.