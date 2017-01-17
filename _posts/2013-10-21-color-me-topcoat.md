---
title: Color Me Topcoat
author: garthdb
date: 2013-10-21
layout: post
comments: true
isPost: true
excerpt: Topcoat 0.8.0 is out!  This build focused on improving customization and theming workflows, specifically on optimizing colors in the theme.
---

Deep in the pits of the Topcoat Theme lived way too many colors.  It made it tricky to customize a new theme quickly.  So we leveraged the color functions from Stylus to whittle the colors down to just a few base colors:

* Text color
* Control base color
* Page base color
* Notification color
* Highlight color
* Shadow color

This colors then effect the rest of the theme.  Each of the previous colors can still be declared manually if you need that control.

Here's a screencast that steps through the theme and how to tweak it.

{% include video.html type="vimeo" id="77716726" %}
