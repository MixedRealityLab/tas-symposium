---
title: Submission instructions
label: Submission instructions
description: Information on submitting to TAS '23

splash_title: Submission instructions

lastmod: page

track:
  dates: submissions

menus:
  main:
    title: Submit
    identifier: submit
    weight: 2
  submit:
    title: Instructions
    alt: Instructions on submitting to TAS '23
    weight: 0
---

We invite full-paper submissions and posters (extended abstracts) that take a multidisciplinary approach to address the challenges of designing, building, and deploying Trustworthy Autonomous Systems (TAS). Contributions should consider social, legal, ethical, and technical issues and their impacts on individuals, society, and the economy.  

## Key dates

{% for date in site.data.track_dates[page.track.dates] -%}
{{ date.label }}: {% if date.extended_date %}<strike>{{ date.date }}</strike> <strong>{{ date.extended_date }}</strong>{% else %}<strong>{{ date.date }}</strong>{% endif %}<br>
{%- endfor -%}

<em class="small">All deadlines are at 23:59 Anywhere on Earth</em>

## Submission types 

**Posters.** The posters track invites extended abstracts (up to 3,000 words) that present early-stage research and/or novel ideas in the field of Trustworthy Autonomous Systems. The Posters track is suitable for shorter, original contributions that do not meet the length requirements or depth required for the Papers track. Submissions can include preliminary results, short prequels to or follow-ups of larger studies, provocative positions, early student research, and other research that is better suited to an interactive discussion format (a poster session). 

**Papers.** The papers track invites full papers (6,000-8,000 words) with a length proportional to its original contribution to knowledge in the field of Trustworthy Autonomous Systems; it cannot be published or be under concurrent review elsewhere. papers must include enough detail that the research can be reviewed for rigor and reproducibility or it may be rejected in the early phase.

### Responsible research and innovation (RRI)

Responsible research and innovation (RRI) provides a unique space to explore dilemmas and the controversies inherited within the advance of autonomous systems. To ensure the development of trustworthy autonomous systems goes hand in hand with RRI principles, we strongly encourage you to engage with these issues in your submission. At least there should be a concise RRI statement within the main body of your submission, including how any ethical concerns were / are being addressed. However, you do not have to include a separate section if your submission clearly addresses the topic of RRI. A successful RRI statement focuses on the broader impact and societal consequences of both the research output and the research process by which it was produced. Authors may find it helpful to adopt a framework for Responsible Research and Innovation (RRI) such as the [AREA](https://www.ukri.org/about-us/epsrc/our-policies-and-standards/framework-for-responsible-innovation/ "UKRI guidance to Anticipate, reflect, engage, act") and [RRI Tools](https://rri-tools.eu/ "RRI Toolkit from the European Union"). More information about RRI can be found at [this link](https://tas.ac.uk/responsible-research-and-innovation/ "Guidance on RRI from the Trustworthy Autonomous Systems Hub"). 

## Submission process
All submissions will proceed through the following process. Please contact the Posters or Papers chairs if you have any questions.

### 1. Prepare your submission

Submissions of full papers and extended abstract must be in English, in PDF format, anonymised using the [CHI anonymization policy](https://chi2022.acm.org/for-authors/presenting/papers/chi-anonymization-policy/ "ACM CHI 2022 Anonymization Policy"), and (including figures, tables, proofs, appendixes, and any other content excluding references and acknowledgments). Extended abstracts for the posters track should be no longer than 3,000 words, full papers should be approximately (6,000-8,000 words). 

For more information about the paper templates, please refer to [the ACM TAPS workflow](https://authors.acm.org/proceedings/production-information/taps-production-workflow).

<!--You must use the [ACM LaTeX or Word templates](https://www.acm.org/publications/proceedings-template "ACM templates for Microsoft Word and LaTeX") to prepare your submission.  LaTeX users may start their work by using the official ACM template available on [Overleaf](https://www.overleaf.com/latex/templates/acm-conference-proceedings-primary-article-template/wbvnghjbzwpc "ACM Primary Article Template templates on Overleaf"), which we strongly encourage. LaTeX users should have the following document class: <code>\documentclass[sigconf, screen, review, anonymous]{acmart}</code> for submission.

Word users should use [the double-column "Interim Template"](https://www.acm.org/publications/proceedings-template#h-interim-template "ACM Interim Template for submissions") during submission and review and should be prepared to submit to TAPS _approximately one week earlier_ than the stated camera-ready deadline. Word users may be required to reimplement their paper, if accepted, into the correct document format for the publishing process. ACM's CCS concepts and keywords are not required for submission and peer review but are required if your paper is accepted and published by the ACM.

For more information about the paper templates, please refer to [ACM Primary Article Template](https://www.acm.org/publications/proceedings-template "Information on ACM Primary Article Template") page.-->


### 2. Submit your paper / extended abstract

You should submit your paper / extended abstract to [the conference submission system](https://easychair.org/my/conference?conf=tas23 "TAS '23 EasyChair"). You must include your title, abstract, author details, and paper / extended abstract as a PDF. Your paper / extended abstract must be anonymised, or it may be desk rejected.

We ask you to make sure that your submission is accessible for all users. To accomplish this, please follow the [SIGCHI Guide to an Accessible Submission](https://sigchi.org/conferences/author-resources/accessibility-guide/ "Read the ACM SIGCHI Guide to an Accessible Submission").

### 3. Peer review

An associate chair (AC) of the programme committee will lead the reviewing process and write a meta review. Each submission will be peer reviewed by expert reviewers following a double-blind process (i.e., authors will not be revealed to reviewers, and all reviewers will be hidden from each other and authors). All accept decisions are conditional and will be checked by the AC before final acceptance.

A small number of submissions that may require further revisions will be shepherded (minor revisions & resubmit), with 2 weeks allocated for authors to coordinate the revisions with the associate chair coordinating each paper. This may include targeted revisions to specific parts of the original submission addressing the most significant points raised by the reviewers, or alternative forms as deemed appropriate by the associate chair. 

Submissions for which there is a very high agreement among reviewers regarding recommendation for inclusion in the proceedings will receive early acceptance decisions and will be conditionally accepted, pending the integration of any changes requested through the review process.

Reviewers and ACs may request ethics review. These submissions will be sent to the ethics review committee to get their comments and these comments will be considered by the AC. Papers cannot be rejected directly by the ethics review committee, but they may be rejected by the program chairs because of issues such as ethics considerations, inadequate scientific quality, and contribution.

### 4. Prepare your submission for publication

If your paper / extended abstract is accepted, you should de-anonymise it. You must include [CCS concepts](https://dl.acm.org/ccs "ACM Computing Classification System concepts") and keywords for publication.

At least one author of each accepted submission must register for the conference, otherwise we cannot guarantee publication of your paper. Accepted papers and extended abstracts will be archived in the [ACM Digital Library](http://dl.acm.org/ "ACM Digital Library").

You will receive an email from ACM to assign the rights for your paper, following which you will receive an email from “The ACM Publishing System” (TAPS), which will handle the generation of the final version of your paper. Accepted papers / extended abstracts will be produced from LaTeX or Word source files into a single column HTML document and a two-column PDF for publication. We recommend all authors read ACM’s guidance for [TAPS Best Practice](https://www.acm.org/publications/taps/taps-best-practices "ACM guide on best practices with The ACM Publishing System").

Please ensure that you and your co-authors [obtain an ORCID ID](https://orcid.org/register "Register for an ORCID ID"), so you can complete the publishing process for your accepted paper. ACM has been involved in ORCID from the start and we have recently [made a commitment to collect ORCID IDs from all of our published authors](https://authors.acm.org/author-resources/orcid-faqs "ACM committment to collect ORCID IDs from all authors"). The collection process has started and will roll out as a requirement throughout 2022. We are committed to improve author discoverability, ensure proper attribution and contribute to ongoing community efforts around name normalization; your ORCID ID will help in these efforts.

All ACM publications follow the [Green Open Access route by default](https://www.acm.org/publications/openaccess#green "Details on ACM's Green Open Access policies"), although authors have the opportunity to independently pay a fee for [Gold Open Access](https://www.acm.org/publications/openaccess#oapricing "Details on Gold Open Access pricing for ACM publications"). The total fee payable depends on the author(s) ACM membership status.

You should, at this stage, produce the final design for your poster.

### 5. Present your work
You will be invited to present your work at TAS 2023. 

**Papers.** Accepted papers will be invited to present their paper as a talk in a paper session at the conference. 

**Posters.** Accepted posters will be on display during the symposium, and presenters will have the opportunity to discuss their work with attendees during designated poster sessions. 

The specific details of the presentation will be provided closer to the conference.

#### Accessibility of Papers and Presentations 

We strongly encourage authors to work on improving the accessibility of their papers and presentations including adding figure descriptions. For more information about accessibility requirements for papers and posters, please refer to the sources given below:

 * [Creating accessible PDFs](https://sigchi.org/conferences/author-resources/accessibility-guide/)
 * [Accessible presentation guide](http://www.sigaccess.org/welcome-to-sigaccess/resources/accessible-presentation-guide/)
* [Check the accessibility of a PDF document](https://checkers.eiii.eu/en/pdfcheck/)

If you have any questions or concerns about creating accessible submissions, please contact us.


## Questions?

If you have any questions, please contact the Poster chairs (Jeremie Clos,  Xinwei Fang) at [tas2023posters@gmail.com](mailto:tas2023posters@gmail.com "Send an email to the TAS '23 Posters chairs") or the Papers chairs (Benedicte Legastelois, Daria Onitiu, Burak Yuksek, Katie Parnell) at [tas2023papers@gmail.com](mailto:tas2023papers@gmail.com  "Send an email to the TAS '23 Papers chairs").  




