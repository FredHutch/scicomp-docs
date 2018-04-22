---
---

{% include toc.html html=content %}

# SciComp Docs
Welcome to our fledgling documentation site, now hosted by github!

## Posts

{% for p in site.posts %}
 * [{{ p.url}}]({{ p.title }})
{% endfor %}

## Pages

{% for p in site.pages %}
 * [{{ p.url}}]({{ p.title }})
{% endfor %}

## Topics

Collections will go here! Someday!
