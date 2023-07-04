---
layout: page
permalink: /PapersandPresentations/
title: Papers & Presentations
description: Publications about some works that I have done or collaborated with. You can download the documents to read them in full.
sections:
  - bibquery: "@article|@inproceedings"
    text: "Peer-reviewed articles and proceedings"
  - bibquery: "@talk"
    text: "Presentations"
  - bibquery: "@misc|@phdthesis|@mastersthesis"
    text: "Theses"
years: [2023, 2022, 2021]
social: true
nav: true
nav_order: 4
---

<div class="publications">

{%- for section in page.sections %}
  <a id="{{section.text}}"></a>
  <p class="bibtitle">{{section.text}}</p>
  {%- for y in page.years %}
    {%- capture citecount -%}
    {%- bibliography_count -f {{site.scholar.bibliography}} -q {{section.bibquery}}[year={{y}}] -%}
    {%- endcapture -%}
    {%- comment -%} If exist bibliography in actual section and year, print {%- endcomment -%}
    {%- if citecount !="0" %}
      <!--<h2 class="year">{{y}}</h2>-->
      {% bibliography -f {{site.scholar.bibliography}} -q {{section.bibquery}}[year={{y}}] %}

    {%- endif -%}

  {%- endfor %}
{%- endfor %}

</div>