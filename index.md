---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: default
# {% for post in site.posts  %}
# <a href="{{ post.url }}">{{ post.title }}</a>
# {% endfor %}

---

# Header: Index.html 
--------------------
## Posts

{% assign postsByYear = site.posts | group_by_exp:"post", "post.date | date: '%Y'" %}
<nav class="menu browse by-year text-center" aria-label="year">
  <strong aria-hidden="true">Jump to:</strong>
  {% for year in postsByYear %}
  <a href="#{{ year.name }}"><span class="visually-hidden">jump to posts from</span>{{ year.name }}</a>
  {% endfor %}
</nav>
{% for year in postsByYear %}
<h2 id="{{ year.name }}">{{ year.name }}</h2>
<ul aria-label="posts from {{ year.name }}">
  {% for post in year.items %}
  <li>
    <a href="{{ post.url }}">{{ post.title }}</a>
  </li>
  {% endfor %}
</ul>
{% endfor %}

## Apps

- LabGear ([iOS][ios-labgear]) & ([Android][android-labgear]): Pocket Lab Tests Reference for Physicians

## Code

- [SMART Markers](https://github.com/smartmarkers): Framework for Patient Generated Health Data
- [Synthetic PRO Generator](https://github.com/raheelsayeed/synthetic-pros): For PROMIS FHIR questionnaires


[ios-labgear]: https://apps.apple.com/us/app/labgear-medical-lab-tests/id350942163
[android-labgear]: https://play.google.com/store/apps/details?id=com.smartddx.labgearessentials&hl=en_US


--------------------

<a href="https://twitter.com/rsayeed">@rsayeed</a>

