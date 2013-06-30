---
layout: page
title: The Shadow Simulator
class: home
---

Shadow is a unique, open source 
[discrete-event network simulator][wikidiscrete]{: target="_blank"} 
that runs real-life applications like 
[Tor][torweb]{: target="_blank"}. 
Shadow combines the accuracy of 
[emulation][wikiemulation]{: target="_blank"} 
with the efficiency and control of 
[simulation][wikisimulation]{: target="_blank"}, 
achieving the best of both approaches. 
[Download Shadow now!](/download)

Latest News <span class="morenews">[<a href="/atom.xml">subscribe</a>][<a href="/news">browse archives</a>]</span>
===========

{% for post in site.posts limit: 3 %}
  &raquo; **{{ post.title }}** _on {{ post.date | date_to_string }}_
  {{ post.content }}
{% endfor %}

[wikidiscrete]: http://wikipedia.org/wiki/Discrete_event_simulation
[torweb]: https://www.torproject.org/
[wikiemulation]: http://wikipedia.org/wiki/Emulator
[wikisimulation]: http://wikipedia.org/wiki/Computer_simulation
[shadoworg]: https://github.com/shadow
