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

* Linux

{% include collection_doc_lister.html collection='linux' %}

* Access

{% include collection_doc_lister.html collection='access' %}

* HPC

{% include collection_doc_lister.html collection='hpc' %}

* Help

{% include collection_doc_lister.html collection='help' %}

* Software

{% include collection_doc_lister.html collection='software' %}

---
bmcgough 04.23.18
---
