---
layout: page
title: Schedule
nav_order: 5
description: COSMOS 2022 schedule.
---

# COSMOS 2022 Schedule
Tuesday July 4th - Friday July 7th, all times are CET
*Preliminary schedule, subject to change*

<!-- [Add the schedule via this Google calendar link](https://calendar.google.com/calendar/u/4?cid=Y29zbW9zLmtvbnN0YW56QGdtYWlsLmNvbQ){:target="_blank"}

- Tuesday: poster session/reception takes place in the [A06 Foyer near the main entrance of the University of Konstanz](https://www.uni-konstanz.de/en/university/about-the-university-of-konstanz/travel-and-campus-map/){:target="_blank"})
- Wednesday: all sessions are held in [Wolkenstein-Saal im Kulturzentrum, Katzgasse 3](https://goo.gl/maps/42DWNSyE3x5GeDDv5){:target="_blank"}. The Biergarten is held at [Hafenhalle, Hafenstraße 10](https://goo.gl/maps/9W6iyGTb3TGZeJHu9){:target="_blank"}
- Thursday and Friday: all sessions will be in [Zebra Kino, Joseph-Belli-Weg 5](https://goo.gl/maps/jkhWJDiJRsXZAMrY7){:target="_blank"}. 
 -->
{% for schedule in site.schedules %}
{{ schedule }}
{% endfor %}
