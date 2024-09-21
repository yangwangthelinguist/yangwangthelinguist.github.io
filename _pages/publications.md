---
layout: page
permalink: /PapersandPresentations/
title: Papers & Presentations
description: This page includes a list of works that I have done or collaborated on. You can download the documents to read them in full. Feel free to email me if a link breaks or if you want a copy of any materials.
sections:
  - bibquery: "article"
    text: "Peer-reviewed articles and proceedings"
  - bibquery: "talk"
    text: "Presentations"
  - bibquery: "thesis"
    text: "Theses"
years: [2024, 2023, 2022, 2021]
social: true
nav: true
nav_order: 2
---

<div class="publications">

{%- for section in page.sections %}
  <a id="{{section.text}}"></a>
  <br>
  <br>
  <p class="bibtitle">{{section.text}}</p>
  {%- for y in page.years %}
    {%- capture citecount -%}
    {%- bibliography_count -f {{site.scholar.bibliography}} -q @*[category = {{section.bibquery}} && year={{y}}] -%}
    {%- endcapture -%}
    {%- if citecount != "0" %}
      {% bibliography -f {{site.scholar.bibliography}} -q @*[category = {{section.bibquery}}&& year={{y}}] %}
      
    {%- endif -%}
  {%- endfor %}
  <hr>
{%- endfor %}

</div>