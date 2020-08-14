---
layout: default
title: Hacker Mode USMLE
permalink: /usmle/
---

# USMLE Notes

Goal of this page is to list high yeild principles or mechanisms popularly tested. 
<ul class="posts">
    {% for post in site.usmle %}

      <li>
        <span class="post-date">{{ post.date | date: "%b %-d, %Y" }}</span>
        <a class="post-link" href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a>
      </li>
    {% endfor %}
  </ul>
 

