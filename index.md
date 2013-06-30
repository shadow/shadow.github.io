---
layout: page
title: The Shadow Simulator
class: home
---

Shadow is a unique, open source [discrete-event network simulator][wikidiscrete] that runs real-life applications like [Tor][torweb]. Shadow combines the accuracy of [emulation][wikiemulation] with the efficiency and control of [simulation][wikisimulation], achieving the best of both approaches. [Shadow is on GitHub!][shadoworg]

Latest News <span class="morenews">[subscribe][<a href="/news">browse archives</a>]</span>
===========

{% for post in site.posts limit: 5 %}
  &raquo; **{{ post.title }}** _on {{ post.date | date_to_string }}_
  {{ post.excerpt }} \[[more]({{ post.url }})\]
{% endfor %}

[wikidiscrete]: http://wikipedia.org/wiki/Discrete_event_simulation
[torweb]: https://www.torproject.org/
[wikiemulation]: http://wikipedia.org/wiki/Emulator
[wikisimulation]: http://wikipedia.org/wiki/Computer_simulation
[shadoworg]: https://github.com/shadow
