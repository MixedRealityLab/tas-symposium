---
label: Posters
description: The posters track at CUI !!conference.year!! allows for the presentation, discussion and information exchange of early stage research in the field of conversational user interfaces.

splash_title: Posters<br>at CUI !!conference.year!!

cta:
  text: Submissions open soon
  title: Submissions for the posters track is currently closed
#  link: /2023/submit/pcs/
  
track:
  chairs: postersdemos
  dates: posters

menus:
  submit:
    title: Posters
    alt: Information about submitting to the posters track at CUI !!conference.year!!
    weight: 2
    is_track: true

lastmod: page
---

# Poster submission information

Posters are short papers that present early-stage research and late-breaking work in the field of Conversational User Interfaces. This track is suitable for shorter, original contributions that do not meet the length requirements or depth required for the [Papers]({{ "/submit/papers/" | relative_url }} "Papers track at CUI {{ site.conference.year }}") track. Submissions can include preliminary results, short prequels to or follow-ups of larger studies, early student research, and other research that is better suited to an interactive discussion format. 

For the submission and review process, you should write an extended abstract that summarises the content you wish to present in your poster. If accepted, we will invite you to present your work at CUI {{ site.conference.year }}, with your extended abstract published in the conference proceedings. 

## Key dates

{% for date in site.data.track_dates[page.track.dates] -%}
{{ date.label }}: {% if date.extended_date %}<strike>{{ date.date }}</strike> <strong>{{ date.extended_date }}</strong>{% else %}<strong>{{ date.date }}</strong>{% endif %}<br>
{%- endfor -%}

<em class="small">All deadlines are at 23:59 Anywhere on Earth</em>

## Examples of posters at CUI 
 
Some examples of previously successful submissions can be found below: 

* [Do we know and do we care? Algorithms and Attitude towards Conversational User Interfaces: Comparing Chatbots and Voice Assistants](https://dl.acm.org/doi/abs/10.1145/3543829.3544517 "Read 'Do we know and do we care? Algorithms and Attitude towards Conversational User Interfaces: Comparing Chatbots and Voice Assistants' in the ACM Digital Library") 
* [A Pilot Study for Understanding Users’ Attitudes Towards a Conversational Agent for News Recommendation](https://dl.acm.org/doi/abs/10.1145/3543829.3544530 "Read 'A Pilot Study for Understanding Users’ Attitudes Towards a Conversational Agent for News Recommendation' in the ACM Digital Library")
* [Understanding Differences between Heavy Users and Light Users in Difficulties with Voice User Interfaces](https://dl.acm.org/doi/abs/10.1145/3405755.3406170 "Read 'Understanding Differences between Heavy Users and Light Users in Difficulties with Voice User Interfaces' in the ACM Digital Library")


## The process

All posters will proceed through the following process. Please contact the <a href="{{ site.data.oc['tracks']['roles'][page.track.chairs]['email'] }}" title="Contact the CUI {{ site.conference.year }} {{ site.data.oc['tracks']['roles'][page.track.chairs]['label'] }} if you have any questions">{{ site.data.oc['tracks']['roles'][page.track.chairs]['label'] }}</a> if you have any questions.

### 1. Prepare your manuscript

Submissions of extended abstract must be in English, in PDF format, anonymised using the [CHI anonymization policy](https://chi2022.acm.org/for-authors/presenting/papers/chi-anonymization-policy/ "CHI 2022 Anonymization Policy"), and approximately 3,000 words (including figures, tables, proofs, appendixes, and any other content excluding references and acknowledgments).

You must use the [ACM LaTeX or Word templates](https://www.acm.org/publications/proceedings-template "ACM templates for Microsoft Word and LaTeX") to prepare your submission.  LaTeX users may start their work by using the official ACM template available on [Overleaf](https://www.overleaf.com/latex/templates/acm-conference-proceedings-primary-article-template/wbvnghjbzwpc "ACM Primary Article Template templates on Overleaf"), which we strongly encourage. LaTeX users should have the following document class: <code>\documentclass[sigconf, screen, review, anonymous]{acmart}</code> for submission.

Word users should use [the double-column "Interim Template"](https://www.acm.org/publications/proceedings-template#h-interim-template "ACM Interim Template for submissions") during submission and review and should be prepared to submit to TAPS _approximately one week earlier_ than the stated camera-ready deadline. Word users may be required to reimplement their paper, if accepted, into the correct document format for the publishing process.

ACM's CCS concepts and keywords are not required for submission and peer review but are required if your paper is accepted and published by the ACM.

### 2. Submit your manuscript

You should submit your extended abstract to the [conference submission system]({{ "/submit/pcs/" | relative_url }} "CUI {{ site.conference.year }} submission system"). You must include your title, abstract, author details, and extended abstract as a PDF. Your extended abstract must be anonymised, or it may be desk rejected.

We ask you to make sure that your submission is accessible for all users. To accomplish this, please follow the [SIGCHI Guide to an Accessible Submission](https://sigchi.org/conferences/author-resources/accessibility-guide/ "SIGCHI's guide to an Accessible Submission").

### 3. Await reviews

Each submission will be peer reviewed by three expert reviewers under a refereed process under a double-anonymous process (i.e., authors will not be revealed to reviewers, and all reviewers will be hidden from each other and authors). Extended abstracts for which there is a very high agreement among reviewers regarding recommendation for inclusion in the proceedings will receive early acceptance decisions and will be conditionally accepted, pending the integration of any changes requested through the review process. 

### 4. Prepare your manuscript for publication

If your extended abstract is accepted, you should de-anonymise it. You must include [CCS concepts](https://dl.acm.org/ccs "ACM Computing Classification System") and keywords for publication.

At least one author of each accepted poster must register for the conference, otherwise we cannot guarantee publication of your paper. Accepted poster extended abstracts will be archived in the <a href="http://dl.acm.org/" title="The ACM Digital Library">ACM Digital Library</a>.

You will receive an email from ACM to assign the rights for your paper, following which you will receive an email from "The ACM Publishing System" (TAPS), which will handle the generation of the final version of your paper. Accepted extended abstracts will be produced from LaTeX or Word source files into a single column HTML document and a two-column PDF for publication. We recommend all authors read ACM's guidance for [TAPS Best Practice](https://www.acm.org/publications/taps/taps-best-practices "The ACM Publishing System (TAPS) Best Practices").

All ACM publications follow the [Green Open Access route by default](https://www.acm.org/publications/openaccess#green "Details on ACM's Green Open Access policies"), although authors have the opportunity to independently pay a fee for [Gold Open Access](https://www.acm.org/publications/openaccess#oapricing "Details on Gold Open Access pricing for ACM publications"). The total fee payable depends on the author(s) ACM membership status.

You should, at this stage, produce the final design for your poster.

### 5. Present your work

You will be invited to present your poster at CUI {{ site.conference.year }}. The specific details of this presentation will be provided closer to the conference.


## Questions?

<p>
{%- for group in site.data.oc -%}
{%- for role in group[1]['roles'] -%}
{%- if role[0] == page.track.chairs -%}
  If you have any questions, please contact the <a href="{{ role[1].email }}" title="Send an email to the CUI {{ site.conference.year }} {{ role[1].label }}">{{ role[1].label }}</a>, 
  {% assign use_and = role[1]['people'] | size | plus: -1 -%}
  {%- for person in role[1]['people'] -%}
      {{- person.name -}}
      {%- if forloop.index == use_and %} and {% else -%}{%- unless forloop.last %}, {% endunless -%}{%- endif -%}
  {%- endfor %} for support.
  {%- break -%}
{%- endif -%}
{%- endfor -%}
{%- endfor -%}
</p>