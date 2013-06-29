---
layout: post
title: Shadow Release 1.6.1
author: robgjansen
tags: software release
---

I just tagged `Shadow v1.6.1`, and added a link on [the download page][dlpage]. This is really more like a `pre-1.7.0` release, but I wanted to get out some exciting new support for running multi-threaded simulations earlier!

This release includes:
 + Support for running multi-threaded simulations! (use the `-w` flag to specify the number of worker threads)
 + A few bugfixes

In preliminary testing, the biggest improvements have been seen when using between 4 and 8 worker threads. Happy simulating! 

[dlpage]: /download
