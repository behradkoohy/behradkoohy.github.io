---
layout: post
title: Publications
description: My Publications
image: assets/images/pic04.jpeg
nav-menu: true
---

{% for publi in site.data.publist %}

**{{ publi.title }}**  
{{ publi.authors }} - {{ publi.link }}

{% endfor %}
