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

The day prior to the main program, 16th September 2024, we will be hosting a series of workshops related to the themes of the conference. You will be able to register for these when you register for the main conference, at no extra cost. These will take place in the Julius Glickman Conference Center.

Details for workshops are below.

{% for workshop in site.data.workshops %}
<div class="background-lightgray rounded border mb-3 p-3">
  <h3 class="mt-0 pt-0 text-primary">{{ workshop.title }}</h3>
  {{ workshop.description | markdownify }}
  {% if workshop.website %}<div class="d-block"><em><a href="{{ workshop.website }}" title="{{ workshop.title }} website">Workshop website &raquo;</a></em></div>{% endif %}
{</div>
{% endfor %}

More workshops are planned, and details will be avaialble soon:

* Coming Together: Addressing Ethical AI with Diverse Teams and Perspectives
* A Hands-on Workshop for Responsible Research and Innovation
* Human-AI Alignment: Developing a Research Agenda by Bridging Interdisciplinary Approaches
* The regulation of workplaces in the age of collaborative robotics towards trustworthy embodied autonomous systems.

Further details and sign up information will be up on this page soon.
