---
title: Best, First, Favorite
---
<section>
<h2>What the heck is this website about?</h2>
The concept <p><strong>Best, First, Favorite (BFF)</strong> was first introduced by <a href="https://mastodon.social/@hotdogsladies">Merlin Mann</a> and <a href="https://mastodon.social/@siracusa">John Siracusa</a> during <a href="https://www.relay.fm/rd/220">episode 220</a> of their program <a href="https://www.relay.fm/rd">Reconcilable Differences</a>.</p>
</section>

<section>
<div class="grid">
  <section>
      <h2>John</h2>
      <ul class="post-list">
        {% for item in site.data.john.items %}
          <li class="post-list-element">
            {% include entry-card.html item=item %}
          </li>
        {% endfor %}
      </ul>
    </section>
    <section>
      <h2>Merlin</h2>
      <ul class="post-list">
        {% for item in site.data.merlin.items %}
          <li class="post-list-element">
            {% include entry-card.html item=item %}
          </li>
        {% endfor %}
      </ul>
    </section>
</div>
</section>