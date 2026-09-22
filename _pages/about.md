---
permalink: /
title: "Home"
layout: home
---

I'm a B.Tech + M.S. by Research student in Computer Science and Computational Linguistics at [IIIT Hyderabad](https://www.iiit.ac.in/), working on NLP, vision-language models, and AI alignment with [Precog](https://precog.iiit.ac.in/) and LTRC. In 2025 I was a visiting researcher at [Maastricht University](https://www.maastrichtuniversity.nl/), applying ML to sustainable agriculture under the EU Horizon project AMBROSIA.

{% include tag-row.html tags="NLP,Vision-Language Models,AI Alignment,Code-Mixing,Multimodal Learning,Responsible AI" %}

## Selected work

<div class="card-grid">
  {% assign highlights = site.data.publications.entries | where: "highlight", true %}
  {% for pub in highlights %}
    {% include publication-entry.html pub=pub %}
  {% endfor %}
</div>

<p class="prose__more"><a href="{{ base_path }}/publications/">See all publications</a> &nbsp;&middot;&nbsp; <a href="{{ base_path }}/research/">See all projects</a></p>

## Updates

{% include updates-timeline.html heading=false %}

<p class="prose__more"><a href="{{ base_path }}/about/">More about me</a></p>
