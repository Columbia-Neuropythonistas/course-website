---
layout: page
title: Course Calendar
nav_order: 2
description: Calendar displaying the weekly event schedule.
---

# Course Calendar

Topics and assignments subject to change.

## Modules

{% for module in site.modules %}
{{ module }}
{% endfor %}
