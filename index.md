---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: default
# {% for post in site.posts  %}
# <a href="{{ post.url }}">{{ post.title }}</a>
# {% endfor %}
# {% assign postsByYear = site.posts | group_by_exp:"post", "post.date | date: '%Y'" %}
# {% for year in postsByYear %}
# <h2 id="{{ year.name }}">{{ year.name }}</h2>
# <ul aria-label="posts from {{ year.name }}">
#   {% for post in year.items %}
#   <li>
#     <a href="{{ post.url }}">{{ post.title }}</a>
#   </li>
#   {% endfor %}
# </ul>
# {% endfor %}
---

# Posts

{% for post in site.posts  %}
<li><a href="{{ post.url }}">{{ post.title }}</a></li>
{% endfor %}

----------------------

## Talks


- _sep 22, 2020_: [DPHARM](https://theconferenceforum.org/conferences/disruptive-innovations-us/2020-speaking-faculty/raheel-sayeed) [slides](https://docs.google.com/presentation/d/1tI-p5yNvynPx5xqF8NKXJOPPoUrye54bUnAqnw-4V3Q/edit?usp=sharing)
- _nov 16, 2020_: [AMIA 2020](https://www.amia.org/amia2020/systems-demonstrations)
- _nov 2018_: [AMIA 2018](https://knowledge.amia.org/67852-amia-1.4259402/t008-1.4262115/t008-1.4262116/2976057-1.4262126/2975528-1.4262123?qr=1)

-------------

## Papers

- _[JAMIA](https://academic.oup.com/jamia/advance-article/doi/10.1093/jamia/ocaa227/6031254)_ A proposal for shoring up Federal Trade Commission protections for electronic health record–connected consumer apps under 21st Century Cures
- _[Nature Digital Medicine](https://www.nature.com/articles/s41746-020-00358-4)_ Push Button Population Health: The SMART/HL7 FHIR Bulk Data Access Application Programming Interface
- _[Nature Digital Medicine](https://www.nature.com/articles/s41746-020-0218-6)_ SMART Markers: collecting patient-generated health data as a standardized property of health information technology
- _[Neurips Conf](https://arxiv.org/abs/1811.11400)_ FADL:Federated-Autonomous Deep Learning for Distributed Electronic Health Record

----------------------------------------------------------------------
## Apps

- LabGear ([iOS][ios-labgear]) & ([Android][android-labgear]): Pocket Lab Tests Reference for Physicians

-------------


## Code

- [SMART Markers](https://github.com/smartmarkers): Framework for Patient Generated Health Data
- [Synthetic PRO Generator](https://github.com/raheelsayeed/synthetic-pros): For PROMIS FHIR questionnaires


[ios-labgear]: https://apps.apple.com/us/app/labgear-medical-lab-tests/id350942163
[android-labgear]: https://play.google.com/store/apps/details?id=com.smartddx.labgearessentials&hl=en_US

--------------------

## [USMLE Notes](https://vimatics.com/usmle/)


--------------------

Mohammed Raheel Sayeed, MD; current home:  [DBMI-HMS](https://dbmi.hms.harvard.edu); [CHIP-BCH](https:/chip.org); [vi](https://vim.org) for informatics;
<a href="https://twitter.com/rsayeed">@rsayeed</a>

