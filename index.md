---
title: "Astro"
---

Astro is a player-maintained Netrunner format which allows only a single copy of any card, including cards from the entire span of FFG's card pool through current NSG sets, with a small [banlist](/astro-netrunner/banlist).

Primarily maintained by Saff (saff_inity) with the help of many others.

### Deck Construction
*  No more than a single copy of any card, by name. [Multi-card IDs](https://netrunnerdb.com/en/card/36036) are still considered to be "one card".
*  "Consumer-Grade"/"Limit 6 per deck" cards are also limited to one copy each.
*  Influence maximums and deck size minimums are as defined by identity cards with no changes.

*  **[Ban List](/astro-netrunner/banlist)**

* * *

{% for post in site.posts %}
  <h2><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></h2>  
  <p>{{post.date | date_to_string}}</p> 
  <p>{{post.description}}</P>
{% endfor %}
