---
title: "Huang Lab - Publications"
layout: gridlay
excerpt: "Huang Lab -- Publications."
sitemap: false
permalink: /publications/
---

## Preprints
{% for publi in site.data.preprintlist %}

  {{ publi.title }} <br />
  <em>{{ publi.authors }} </em><br /><a href="{{ publi.link.url }}">{{ publi.link.display }}</a>

{% endfor %}

## Publications
{% for publi in site.data.publist %}

  {{ publi.title }} <br />
  <em>{{ publi.authors }} </em><br /><a href="{{ publi.link.url }}">{{ publi.link.display }}</a>

{% endfor %}

*: co-first author

&#9993;: corresponding author

<u>Underscore</u>: lab member/alumnus
