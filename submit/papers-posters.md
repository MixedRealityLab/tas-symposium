---
title: Submission instructions
label: Submission instructions
description: Information on submitting to TAS '24

splash_title: Papers and posters<br>submission instructions

lastmod: page

track:
  dates: papers_posters

menus:
  submit:
    title: Papers and Posters Instructions
    alt: Instructions on submitting papers and posters to TAS '24
    weight: 0
    is_track: true
---

We invite full-paper submissions and posters (extended abstracts) that take a multidisciplinary approach to address the challenges of designing, building, and deploying Trustworthy Autonomous Systems (TAS). Contributions should consider social, legal, ethical, and technical issues and their impacts on individuals, society, and the economy. 

**Submit your papers on [EasyChair](https://easychair.org/conferences/?conf=tas24 "EasyChair submission site for TAS '24").**

## Key dates

{% for date in site.data.track_dates[page.track.dates] -%}
{{ date.label }}: {% if date.extended_date %}<strike>{{ date.date }}</strike> <strong>{{ date.extended_date }}</strong>{% else %}<strong>{{ date.date }}</strong>{% endif %}<br>
{%- endfor -%}

<em class="small">All deadlines are at 23:59 Anywhere on Earth</em>

## Submission types 

**Posters**. The posters track invites extended abstracts (up to 3,000 words, excluding references and acknowledgements) that present early-stage research and/or novel ideas in the field of Trustworthy Autonomous Systems. The posters track is suitable for shorter, original contributions that do not meet the length requirements or depth required for the Papers track. Submissions can include preliminary results, short prequels to or follow-ups of larger studies, provocative positions, early student research, and other research that is better suited to an interactive discussion format (a poster session).

**Papers**. The papers track invites full papers (6,000-8,000 words excluding references and acknowledgement) with a length proportional to their original contribution to knowledge in the field of Trustworthy Autonomous Systems. The paper cannot be published or be under concurrent review elsewhere. Papers must include enough detail to allow the research to be reviewed for rigor and reproducibility; otherwise,  the work may be rejected in the early phase.

We strongly encourage authors to include in their submissions a consideration of the dilemmas and the controversies inherent to the advance of autonomous systems. This might include, for instance, the ethical concerns that were identified and/or addressed in the work conducted, reflections on how authors’ background and experiences inform or shape the work, and the broader impact and societal consequences of both the research output and the research process by which it was produced.

## Submission process

All submissions will proceed through the following process. Please contact the Posters or Papers chairs if you have any questions.

### 1. Preparing your submission
Submissions of both full papers and extended abstracts for posters must be in English and in PDF format; anonymised using the [CHI anonymization policy](https://chi2024.acm.org/submission-guides/chi-anonymization-policy/ "CHI 2024 anonymisation policy"); and include figures, tables, proofs, appendixes, and any other content. Extended abstracts for the posters track should be no longer than 3,000 words, and full papers should be approximately 6,000-8,000 words excluding references and acknowledgements.

For more information about the paper templates, including downloading the [LaTeX](
https://authors.acm.org/proceedings/production-information/preparing-your-article-with-latex) or [Word](https://authors.acm.org/proceedings/production-information/preparing-your-article-with-microsoft-word) templates, please refer to [the ACM TAPS workflow](https://authors.acm.org/proceedings/production-information/taps-production-workflow "The ACM Publishing System workflow") guidance.

### 2. Submitting your paper or extended abstract
Submit your paper or extended abstract to [the conference submission system](https://easychair.org/conferences/?conf=tas24 "EasyChair submission site for TAS '24"). Include your title, abstract, author details, and the paper or extended abstract as a PDF. Your submission must be anonymised; otherwise, it may be desk rejected.

We ask you to ensure your submission is accessible for all users. To accomplish this, please follow the [SIGCHI Guide to an Accessible Submission](https://sigchi.org/conferences/author-resources/accessibility-guide/ "ACM SIGCHI guide to making publications accessible").

### 3. Peer review

An associate chair (AC) of the programme committee will lead the reviewing process and write a meta review. Following a double-blind process (i.e., authors will not be revealed to reviewers, and all reviewers will be hidden from each other and authors), each submission will be peer reviewed by expert reviewers.  All “accept” decisions are conditional and will be checked by the AC before final acceptance.

A small number of submissions that may require further revisions (minor revisions & resubmit) will be shepherded, with 2 weeks allocated for authors to coordinate the revisions with the associate chair coordinating each paper. This process may include making revisions targeted to specific parts of the original submission, addressing the most significant points raised by the reviewers, or alternative forms of revision deemed appropriate by the associate chair.

Submissions for which there is a very high agreement among reviewers regarding recommendation for inclusion in the proceedings will receive early acceptance.  Such submissions will be conditionally accepted, pending the integration of any changes requested through the review process.

Reviewers and ACs may request an ethics review of a submission, in which case the submission will be sent to the ethics review committee, whose comments then will be considered by the AC. Note that papers cannot be rejected directly by the ethics review committee, but they may be rejected by the program chairs due to concerns such as ethics considerations, inadequate scientific quality, and lack of contribution.

### 4. Preparing your submission for publication

If your paper or extended abstract (poster) is accepted, you should de-anonymise it. You also must include [CCS concepts](https://dl.acm.org/ccs "ACM CCS concepts on the Digital Library" ) and keywords for publication.

At least one author of each accepted submission must register for the conference to guarantee publication of your work. 

Accepted papers and extended abstracts will be archived in the [ACM Digital Library](http://dl.acm.org/ "The ACM Digital Library").

You will receive an email from ACM to assign the rights for your paper. Next, you will receive an email from “The ACM Publishing System” (TAPS), which will handle the generation of the final version of your paper. Accepted papers and extended abstracts will be produced from [LaTeX](https://authors.acm.org/proceedings/production-information/preparing-your-article-with-latex) or [Word](https://authors.acm.org/proceedings/production-information/preparing-your-article-with-microsoft-word) source files into a single column HTML document and a two-column PDF for publication. We recommend all authors read ACM’s guidance for [TAPS Best Practice](https://www.acm.org/publications/taps/taps-best-practices "TAPS best practice from ACM").

Please ensure that you and your co-authors obtain an [ORCID ID](https://orcid.org/register "OCIRD registration"), which will enable you to complete the publishing process for your accepted paper. ACM has been involved in ORCID from the start, and has recently [made it a requirement that ORCID IDs are provided by all of our published authors](https://authors.acm.org/author-resources/orcid-faqs "ACM policy on ORCID"). We are committed to improving author discoverability, ensuring proper attribution, and contributing to ongoing community efforts around name normalization; your ORCID ID will help in these efforts.

You should, at this stage, produce the final design for your poster based on your extended abstract.

#### Important note to authors about the new ACM open access publishing model

ACM has introduced a new open access publishing model for the International Conference Proceedings Series (ICPS). Authors based at institutions that are not yet part of the [ACM Open program](https://libraries.acm.org/acmopen/open-participants) and do not qualify for a waiver will be required to pay an article processing charge (APC) to publish their ICPS article in the ACM Digital Library. To determine whether or not an APC will be applicable to your article, please follow the detailed guidance here: https://www.acm.org/publications/icps/author-guidance.

Further information may be found on the ACM website, as follows:

* [Full details of the new ICPS publishing model](https://www.acm.org/publications/icps/faq)<br>
* [Full details of the ACM Open program](https://www.acm.org/publications/openaccess)

Please direct all questions about the new model to [icps-info@acm.org](mailto:icps-info@acm.org).

### 5. Presenting your work

**Papers**. Authors of accepted papers will be invited to present their paper as a talk in a paper session at the TAS 2024 symposium. The specific details of the presentation will be provided closer to the conference.

**Posters**. Accepted posters will be on display during the symposium, and presenters will have the opportunity to discuss their work with attendees during designated poster sessions. Authors are welcome to design their own posters; alternatively, [an optional poster template](https://symposium.tas.ac.uk/2023/assets/pptx/UKRI-TAS-Hub-Research-Poster-Template.pptx "Poster template for TAS '24") is available.

## Ensuring Accessibility of Papers and Presentations

We strongly encourage authors to consider the accessibility of their papers and presentations, such as by including figure descriptions. For more information about accessibility requirements for papers and posters, please see the [TAS guidance on making your paper accessible](/2024/submit/accessibility/). If you have any questions about creating accessible submissions, please contact us.


## LLM Statement
We are following the ACM guidelines on the use of Large Language Models (LLMs) in authoring papers. This means that any text generation from an LLM such as ChatGPT must be clearly marked where such tools are used for purposes beyond editing the author’s own text. While we will not use tools to detect text generated by LLMs, we will investigate submissions brought to our attention and will desk reject papers where LLM use is not clearly marked. We recommend that authors read the [ACM Policy on Authorship](https://www.acm.org/publications/policies/new-acm-policy-on-authorship) and related [SIGCHI blog post](https://medium.com/sigchi/acm-publications-policy-guidance-for-sigchi-venues-87332173aad1).


## Questions?
If you have any questions, please contact the Posters Chair (Gisela Reyes Cruz) or the Papers Chair (Katie Parnell) [here](mailto:contact@tas.ac.uk).




