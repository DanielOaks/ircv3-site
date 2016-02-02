---
layout: page
title: IRCv3 Specifications
excerpt: Links to the IRCv3 specifications.
index: true
---

{% for spec in site.irc %}
{% if spec.index != true %}

## {{spec.title}}

{{spec.content}}

{% endif %}
{% endfor %}
