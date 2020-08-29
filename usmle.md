---
layout: default
title: Hacker Mode USMLE
permalink: /usmle/
---

# USMLE Notes

Goal of this page is to list high yeild principles or mechanisms popularly tested. 

----


_Random:_

{% assign random = site.time | date: "%s%N" | modulo: site.usmle.size %}
{% assign randomnote = site.usmle[random].content %}
>      {{randomnote}}


----

{% assign notesByYear = site.usmle | group_by_exp:"note", "note.date | date: '%m/%d/%Y'" %}
{% for year in notesByYear %}
<h2 id="{{ year.name }}">{{ year.name }}</h2>
<ul aria-label="posts from {{ year.name }}">
  {% for note in year.items %}
  <li>
    <a href="{{ note.url }}">{{ note.title }}</a>
  </li>
  {% endfor %}
</ul>
{% endfor %}

--------------------

Mohammed Raheel Sayeed, MD; current home: [bch](https://chip.org) [hms](https://hms.harvard.edu);
[vi](https://vim.org) for informatics;
<a href="https://twitter.com/rsayeed">@rsayeed</a>

