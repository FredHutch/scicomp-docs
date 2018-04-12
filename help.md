---
layout: default
title: how to get help
---

{% for help in site.help %}


<a href="{{ help.url | prepend: site.baseurl }}">
        {{ help.title }}
</a>

<p class="post-excerpt">{{ help.description | truncate: 320 }}</p>

{% endfor %} 
