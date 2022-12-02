---
layout: page
title: Speakers
description: A listing of confirmed speakers that will present at the workshop.
nav_order: 2
---

{% include splash.html %}

# Confirmed Speakers

Clicking a speaker's photo will jump to their talk information below.

{% include speakers.html %}

# Talk Details

{% assign speakers = site.speakers %}
{% for speaker in speakers %}

### [{{ speaker.name }}]({{ speaker.website }})

{{ speaker.affiliation }}

#### Title: {{ speaker.talk }}

#### Abstract
{{ speaker.abstract}}

{% endfor %}

