---
layout: home
title: Home
nav_order: 0
description: >-
    Just the Class is a modern, highly customizable, responsive Jekyll theme
    for developing course websites.
---

# {{ site.description }}
{: .mb-2 }
{{ site.title }}
{: .fs-6 .fw-300 }

{% if site.announcements %}
{{ site.announcements.last }}
[Announcements]({{ site.baseurl }}{% link announcements.md %}){: .btn .btn-outline .fs-3 }
{% endif %}
