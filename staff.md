---
layout: page
title: Instructors
description: A listing of all the course instructors.
nav_exclude: true
---

# Instructors

{% assign instructors = site.staffers | where: 'role', 'Instructor' %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}

