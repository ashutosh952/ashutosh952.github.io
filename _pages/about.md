---
permalink: /
title: "👋 About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

My name is Ashutosh Soni.

<h2>📢 News</h2> {% for post in site.news reversed %} {% include
archive-single.html %} {% endfor %}
