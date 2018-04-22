---
title: index
description: SciComp Docs
---

{% include toc.html html=content %}

# SciComp Docs
Welcome to our fledgling documentation site, now hosted by github!

## Posts

{% for p in site.posts %}
 * [{{ p.title }}]({{ site.baseurl }}{{ p.url }})
  * {{ p.description }} _{{ p.author }}_ last update {{ p.date }}
{% endfor %}

## Pages

{% for p in site.pages %}
 * [{{ p.title }}]({{site.baseurl}}{{ p.url }})
{% endfor %}

## Topics

{% include collection_doc_lister.html collection='linux' %}

{% include collection_doc_lister.html collection='access' %}

{% include collection_doc_lister.html collection='hpc' %}

{% include collection_doc_lister.html collection='help' %}

{% include collection_doc_lister.html collection='software' %}

---
bmcgough 04.23.18
---
