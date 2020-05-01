---
layout: archive
classes: wide
title: "Archive"
permalink: /archive.html
author_profile: false
sidebar:
  nav: "archive"
---

<div class="container">
<div class="notice--warning item">Long Posts</div>
<div class="notice--danger item">Meta Posts</div>
<div class="notice--success item">English Posts</div>
</div>

<div class="container">
{% for post in site.posts  %}

{% include tags.html %}

{% endfor %}
</div>
