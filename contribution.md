---
layout: page
title: Contribution Guidelines
description: Instructions on how to contribute to the Slayte help documentation
permalink: /contribution/
collection: contribution
weight: 5
---

## {{ page.description }}

{% assign items = site.contribution | sort: 'weight' %}
{% for item in items %}
  <a href="{{ site.baseurl }}{{ item.url }}">{{ item.title }}</a>
{% endfor %}