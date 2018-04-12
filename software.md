---
layout: default
title: software information and documentation
---

{% for software in site.software %}


<a href="{{ software.url | prepend: site.baseurl }}">
        {{ software.title }}
</a>

<p class="post-excerpt">{{ software.description | truncate: 320 }}</p>

{% endfor %} 
