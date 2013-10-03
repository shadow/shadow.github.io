---
layout: post
title:  Shadow Release 1.8.0
author: robgjansen
tags: software release
---

I just tagged `Shadow v1.8.0`, and added a link on [the download page][dlpage].

This release includes:

 + epoll enhancements - epoll an epoll descriptor, edge-triggered events (EPOLLET), one-shot support (EPOLLONESHOT)
 + tracking virtual host statistics (ram, bandwidth, and per-socket stats)
 + lots and lots of [bugfixes][m9issues]

Happy simulating!

[dlpage]: /download/
[m9issues]: https://github.com/shadow/shadow/issues?milestone=9&amp;page=1&amp;state=closed
