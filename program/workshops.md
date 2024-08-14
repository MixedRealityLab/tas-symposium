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

The day prior to the main program, 16th September 2024, we will be hosting a series of workshops related to the themes of the conference. You will be able to register for these when you register for the main conference, at no extra cost. All workshops will take place in the [Julius Glickman Conference Center]({{ "/attend/venue-information/" | relative_url }}).

{% for workshop in site.data.workshops %}
<div class="background-lightgray rounded border mb-3 p-3">
  <h3 class="m-0 p-0 text-primary d-flex flex-row align-items-start collapse-link-chevron small" data-bs-toggle="collapse" href="#workshop{{ forloop.index }}" role="button" aria-expanded="false" aria-controls="workshop{{ forloop.index }}">
    <span class="flex-grow-1">
    {{ workshop.title }}
    </span>
    <i class="flex-grow-0 float-right bi bi-chevron-right mt-1"></i>
  </h3>
  <div class="description collapse pt-3 mb-0" id="workshop{{ forloop.index }}">
    {{ workshop.description | markdownify }}
    {% if workshop.website %}
    <div class="d-block">
      <em><a href="{{ workshop.website }}" title="{{ workshop.title }} website">Workshop website &raquo;</a></em>
    </div>
    {% endif %}
  </div>
</div>
{% endfor %}

