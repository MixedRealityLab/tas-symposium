---
title: Workshops
description: >
  Details about workshops at the TAS '24 symposium at The University of Texas at Austin.

splash_title: Workshops at TAS '24

menus:
  programme:
    title: Workshops
    alt: Details about the TAS '24 workshops
    weight: 4
---

The day prior to the main program, 15th September 2024, we will be hosting a series of workshops related to the themes of the conference. You will be able to register for these when you register for the main conference, at no extra cost. These will take place in the Julius Glickman Conference Center.

There are {{ site.data.workshops | size }} workshops at TAS '24:

{% for workshop in site.data.workshops %}
<div class="background-lightgray rounded border mb-3 p-3">
  <h3 class="mt-0 pt-0 text-primary">{{ workshop.title }}</h3>
  {{ workshop.description | markdownify }}
  {% if workshop.website %}<div class="d-block"><em><a href="{{ workshop.website }}" title="{{ workshop.title }} website">Workshop website &raquo;</a></em></div>{% endif %}
</div>
{% endfor %}