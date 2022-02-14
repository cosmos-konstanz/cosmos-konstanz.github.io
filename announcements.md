---
layout: page
title: Announcements
nav_order: 5
nav_exclude: true
description: A feed containing announcements.
---

# Announcements


{% assign announcements = site.announcements | reverse %}
{% for announcement in announcements %}
{{ announcement }}
{% endfor %}
