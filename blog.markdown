---
title: Blog
---
<section>
  <ul class="post-list">
    {% for post in site.posts %}
      <li class="post-list-element">
        {% include post-card.html post=post %}
      </li>
    {% endfor %}
  </ul>
</section>