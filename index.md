---
layout: default
---
{% for talk in site.talks %}
  <h2>
    <a href="{{ talk.url | prepend:site.baseurl }}">{{ talk.title }}</a>
  </h2>
{% endfor %}
