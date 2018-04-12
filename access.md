---
layout: default
title: access information
---

{% for access in site.access %}


<a href="{{ linux.url | prepend: site.baseurl }}">
        {{ access.title }}
</a>

<p class="post-excerpt">{{ access.description | truncate: 320 }}</p>

{% endfor %} 
