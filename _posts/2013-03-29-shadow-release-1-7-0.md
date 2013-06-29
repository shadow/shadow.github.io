---
layout: post
title:  Shadow Release 1.7.0
author: robgjansen
tags: software release
---

I just tagged `Shadow v1.7.0`, and added a link on [the download page][dlpage].

This release includes:
 + Building with LLVM/Clang to automatically handle plug-in state
 + Fixes for multi-threaded simulations (use the `-w` flag to specify the number of worker threads)
 + Support for running multiple applications on each virtual node
 + The ability to communicate with Tor's control interface
 + A host of [other bugfixes and enhancements][m8issues]

Happy simulating!

[dlpage]: /download/
[m8issues]: https://github.com/shadow/shadow/issues?milestone=8&amp;page=1&amp;state=closed
