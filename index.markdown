---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
title: Brittany Roman
permalink: /
---

{% for product in site.products %}
{% include product.html %}
{% endfor %}
