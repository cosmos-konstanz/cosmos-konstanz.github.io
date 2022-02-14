---
layout: page
title: Schedule
nav_order: 5
description: COSMOS schedule.
---

# Schedule

Monday July 4th - Thursday July 7th,

All times are CET

{% for schedule in site.schedules %}
{{ schedule }}
{% endfor %}
