---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

# {%- assign latest_post = site.posts[0] -%}

layout: default
---

{% for post in site.posts  %}
<a href="{{ post.url }}">{{ post.title }}</a>
{% endfor %}
