---
layout: page
title: Schedule
nav_order: 5
description: COSMOS schedule.
---

# Schedule
Monday July 4th - Thursday July 7th, all times are CET (still subject to change)

[Sharable Google calendar link](https://calendar.google.com/calendar/u/4?cid=Y29zbW9zLmtvbnN0YW56QGdtYWlsLmNvbQ){:target="_blank"}


{% for schedule in site.schedules %}
{{ schedule }}
{% endfor %}
