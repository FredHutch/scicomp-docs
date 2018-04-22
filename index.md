---
title: index
description: SciComp Docs
author: bmcgough
date: 2018-04-22
---

Welcome to our fledgling documentation site, now hosted by github!

## Posts

{% for p in site.posts %}
  [{{ p.date | date: "%-d %B %Y" }}: {{ p.title }}]({{ site.baseurl }}{{ p.url }})
  - {{ p.description }} by _{{ p.author }}_
{% endfor %}

## Topics

{% include collection_doc_lister.html collection='about' %}

{% include collection_doc_lister.html collection='linux' %}

{% include collection_doc_lister.html collection='access' %}

{% include collection_doc_lister.html collection='hpc' %}

{% include collection_doc_lister.html collection='help' %}

{% include collection_doc_lister.html collection='software' %}

