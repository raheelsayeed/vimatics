---
layout: default
title: Hacker Mode USMLE
permalink: /usmle/
---

# USMLE Notes

Goal of this page is to list high yeild principles or mechanisms popularly tested. 


{% assign postsByYear = site.usmle | group_by_exp:"note", "note.date | date: '%m'" %}
{% for year in postsByYear %}
<h2 id="{{ year.name }}">{{ year.name }}</h2>
<ul aria-label="posts from {{ year.name }}">
  {% for note in year.items %}
  <li>
    <a href="{{ note.url }}">{{ note.title }}</a>
  </li>
  {% endfor %}
</ul>
{% endfor %}
</ul>


<ul class="posts">
    {% for post in site.usmle %}

      <li>
        <span class="post-date">{{ post.date | date: "%b %-d, %Y" }}</span>
        <a class="post-link" href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
      </li>
    {% endfor %}
  </ul>
 

