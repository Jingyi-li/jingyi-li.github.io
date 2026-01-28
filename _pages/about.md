---
permalink: /
title: "(Carol) Jingyi Li / 李静怡"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Jingyi (Carol) Li is a Postdoctoral Fellow in the Department of ECE at the Hong Kong University of Science and Technology. She received her Ph.D. from the University of Sydney, where her research focused on FPGA-based signal processing accelerators. Her current work explores high-performance implementations of cyclostationary signal analysis, reconfigurable computing, and machine learning on AMD Versal ACAP platforms.

## Selected and refereed publications
Peer-Reviewed Publications, including IEEE SPL, ACM TRETS, and FPL

[Full publication list]({{ site.baseurl }}/publications/)

{% assign selected_pubs = site.publications | where: "selected", true | sort: "date" | reverse %}

<ul style="list-style: none; padding-left: 0;">
{% for post in selected_pubs limit: 6 %}
  <li style="margin-bottom: 0.6em;">
    [{{ forloop.index }}]
    {{ post.citation }}
  </li>
{% endfor %}
</ul>

<!-- ## Research Interests -->


<!-- Peer-Reviewed Publications
====== -->

