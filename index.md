---
title: index
description: SciComp Docs
---

{% include toc.html html=content %}

# SciComp Docs
Welcome to our fledgling documentation site, now hosted by github!

## Posts

{% for p in site.posts %}
 * [{{ p.title }}]({{ p.url }})
{% endfor %}

## Pages

{% for p in site.pages %}
 * [{{ p.title }}]({{ p.url }})
{% endfor %}

## Topics

* Linux

{% include collection_doc_lister.html collection='github-pages' %}

* Access

{% include collection_doc_lister.html collection='github-pages' %}

* HPC

{% include collection_doc_lister.html collection='github-pages' %}

* Help

{% include collection_doc_lister.html collection='github-pages' %}

* Software

{% include collection_doc_lister.html collection='github-pages' %}

---
bmcgough 04.23.18
---
