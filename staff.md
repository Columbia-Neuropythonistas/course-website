---
layout: page
title: Staff
nav_order: 4
description: A listing of all the course staff members.
---


## Instructors

{% assign instructors = site.staffers | where: 'role', 'Instructor' %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}

## Faculty Supervisor

{% assign supervisors = site.staffers | where: 'role', 'Faculty Supervisor' %}
{% for staffer in supervisors %}
{{ staffer }}
{% endfor %}
