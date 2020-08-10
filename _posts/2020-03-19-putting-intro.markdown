---
layout: post
title:  "Put intro!"
date:   2020-03-19 15:10:27 +0530
excerpt: Of course.
---

Test Post
<a href="{{ '/assets/css/main.css' | absolute_url }}">Absolute Link</a>
<a href="{{ '/assets/css/main.css' | relative_url }}">Relative Link</a>

$asset_url: '{{ '/assets' | absolute_url }}';
url(#{$asset_url}/images/divider.svg)

<a href="{{ '/assets' | absolute_url }}/images/divider.svg">Absolute Link to Image</a>
<a href="{{ '/assets' | relative_url }}/images/divider.svg">Relative Link to Image</a>
