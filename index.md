---
layout: home
title: Home
nav_order: 0
description: >-
    Aggregator Site for Bay Area Effective Altruism
---
<!-- <div class="parallax-window" data-parallax="scroll" data-image-src="/assets/background.png" data-speed="0.1">/div> -->
# Bay Area Efffective Altruism
{: .mb-2 }

<hr>

{% if site.announcements %}
{{ site.announcements.last }}
<a href="{{ site.baseurl }}/announcements" class="btn btn-outline fs-3">
  All Announcements
</a>
{% endif %}

# Course Calendar

{% for module in site.modules %}
{{ module }}
{% endfor %}
