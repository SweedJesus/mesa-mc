---
layout:default
---
Past integrals of the week:
{% for integral in site.data.integrals %}
- {{ integral }}
{% endfor %}
