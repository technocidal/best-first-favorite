---
title: Best, First, Favorite
---
<section>
<h2>What the heck is this website about?</h2>
<p>The concept <strong>Best, First, Favorite (BFF)</strong> was first introduced by <a href="https://mastodon.social/@hotdogsladies">Merlin Mann</a> and <a href="https://mastodon.social/@siracusa">John Siracusa</a> during <a href="https://www.relay.fm/rd/220">episode 220</a> of their program <a href="https://www.relay.fm/rd">Reconcilable Differences</a>.</p>

<p>BFF is meant to quickly convey one's feelings about a thing, especially TV shows and podcasts.</p>

<p><strong>Best</strong> is the particular instance of a thing where there are <a href="https://overcast.fm/+E5IOgLjKU/49:41">"like no bad parts"</a>, and it usually comes up in a conversation between two people who already love the thing.</p>

<p><strong>First</strong> is used to label an episode or entry that truly encapsulates the appeal of the thing, helping people experiencing it for the first time decide if it's for them.</p>

<p><strong>Favorite</strong> is the one that <a href="https://overcast.fm/+E5IOgLjKU/51:51">"gives you the most warm fuzzies"</a>.</p>

<p>For now, for the sake of my own sanity, this website will only include entries for things that are mentioned while John or Merlin are discussing BFF and have made mention of the overall concept.</p>
</section>

<section>
<div class="grid">
  <section>
      <h2>Johns BFF</h2>
      <ul class="post-list">
        {% for item in site.data.john.items %}
          <li class="post-list-element">
            {% include entry-card.html item=item %}
          </li>
        {% endfor %}
      </ul>
    </section>
    <section>
      <h2>Merlins BFF</h2>
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