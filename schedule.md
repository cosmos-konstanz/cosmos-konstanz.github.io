---
layout: page
title: Schedule
nav_order: 5
description: COSMOS 2023 schedule.
---

# COSMOS 2023 Schedule
Tuesday July 4th - Friday July 7th, all times are CET
*Preliminary schedule, subject to change*


- Tuesday: poster session/reception takes place in the [A06 Foyer near the main entrance of the University of Konstanz](https://www.uni-konstanz.de/en/university/about-the-university-of-konstanz/travel-and-campus-map/){:target="_blank"})
- Wednesday and Thursday: all sessions are held in [Bodensee Forum, Reichenaustraße 21, 78467 Konstanz](https://goo.gl/maps/g6SKWBJgQB63P3C97){:target="_blank"}. 
- Friday: all sessions will be in [Senatssaal – V 1001, University of Konstanz, Building B, Universitätsstraße 10, 78464 Konstanz](https://goo.gl/maps/SBiC3WTC9KpPb3cg7){:target="_blank"}. 

<!-- [Add the schedule via this Google calendar link](https://calendar.google.com/calendar/u/4?cid=Y29zbW9zLmtvbnN0YW56QGdtYWlsLmNvbQ){:target="_blank"}

 -->
{% for schedule in site.schedules %}
{{ schedule }}
{% endfor %}
