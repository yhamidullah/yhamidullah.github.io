---
layout: about
title: about
permalink: /
subtitle: Sign language translation · multimodal NLP · <a href="https://www.uzh.ch/">University of Zurich</a> &amp; <a href="https://www.dfki.de/en/web/research/research-departments/multilinguality-and-language-technology">DFKI MLT</a>

profile:
  align: right
  image: prof_pic.jpg
  image_circular: true # crops the image to make it circular
  # TODO: add your institute/department and office at UZH
  more_info: >
    <p>University of Zurich, Switzerland</p>
    <p>DFKI, Saarland Informatics Campus</p>
    <p>Saarbrücken, Germany</p>

selected_papers: true # includes a list of papers marked as "selected={true}"
social: true # includes social icons at the bottom of the page

announcements:
  enabled: true # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: false
  scrollable: true # adds a vertical scroll bar if there are more than 3 new posts items
  limit: 3 # leave blank to include all the blog posts
---

I am a researcher at the [University of Zurich](https://www.uzh.ch/) and in the [Multilinguality and Language Technology](https://www.dfki.de/en/web/research/research-departments/multilinguality-and-language-technology) department at [DFKI](https://www.dfki.de/), on the Saarland Informatics Campus, where I work with Josef van Genabith and Cristina España-Bonet.

My research is on **sign language translation** — mapping continuous signing video into spoken-language text. Most systems in this area lean on _glosses_: manual annotations that are expensive to produce and exist for only a handful of languages. My work asks how far we can get without them. That means supervising translation with [sentence embeddings](https://aclanthology.org/2024.acl-short.40/) in place of glosses, extending that supervision to the [multilingual, language-agnostic setting](https://aclanthology.org/2025.wmt-1.18/), and learning [spatio-temporal representations](https://aclanthology.org/2022.wmt-1.94/) end to end.

More recently I have been asking whether these systems are actually _watching the video_. Fluent output is easy to mistake for correct output, so I study [visual signals that separate grounded translation from hallucination](https://openreview.net/forum?id=bLFW2T3UHq), what our [evaluation metrics really measure](https://arxiv.org/abs/2510.25434), and how well the [corpora the field has standardised on](/publications/) hold up under audit.

I work on multimodal NLP more broadly too — video-grounded fact verification, vision-language pipelines for data curation, and multilingual model behaviour.

Earlier, I contributed to [AVASAG](https://aclanthology.org/2021.mtsummit-at4ssl.5/), a German Sign Language translation system for public services built around a 3D signing avatar.
