---
layout: page
title: Schedule
description: Listing of workshop program
nav_order: 1
---

{% include splash.html %}


<!---
# Bird's Eye View of the Program (Tentative)

All times in GST (GMT+4).
-->

# Workshop Schedule (Tentative)

All times in GST (GMT+4).

{% for module in site.modules %}
{{ module }}
{% endfor %}
