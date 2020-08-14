---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: default
---

## Apps

- LabGear ([iOS][ios-labgear]) & ([Android][android-labgear]): Pocket Lab Tests Reference for Physicians

## Code

- [SMART Markers](https://github.com/smartmarkers): Framework for Patient Generated Health Data
- [Synthetic PRO Generator](https://github.com/raheelsayeed/synthetic-pros): For PROMIS FHIR questionnaires

## Posts

{% for post in site.posts  %}
<a href="{{ post.url }}">{{ post.title }}</a>
{% endfor %}

[ios-labgear]: https://apps.apple.com/us/app/labgear-medical-lab-tests/id350942163
[android-labgear]: https://play.google.com/store/apps/details?id=com.smartddx.labgearessentials&hl=en_US
