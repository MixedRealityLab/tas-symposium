---
title: Submission information
description: Information on submitting to one of the TAS '24 tracks.

maintainer: general
lastmod: page

menu:
  main:
    title: Submit
    alt: Information about submitting to TAS '24
    weight: 2
    identifier: submit
---

<ul>
{% for item in site.menus.submit %}
    {% if item.is_track != true %}{% continue %}{% endif %}
    <li>
        <a class="" href="{{ item.url | absolute_url }}" title="{{ item.alt | escape | replace: "!!conference.year!!", site.conference.year | replace: "!!conference.location!!", site.conference.location | replace: "!!conference.dates!!", site.conference.dates }}">
            {{ item.title }}
        </a>
    </li>
{% endfor %}
</ul>