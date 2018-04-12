---
layout: default
title: docs for gizmo/beagle/slurm/HPC
---

{% for hpc in site.hpc %}


<a href="{{ hpc.url | prepend: site.baseurl }}">
        {{ hpc.title }}
</a>

<p class="post-excerpt">{{ hpc.description | truncate: 320 }}</p>

{% endfor %} 
