---
layout: page
title: Instructors
nav_order: 3
description: A listing of all the course staff members.
---

## Organizers

{% assign organizers = site.instructors | where: 'role', 'Organizer1' %}
{% for staffer in organizers %}
{{ staffer }}
{% endfor %}

{% assign organizers = site.instructors | where: 'role', 'Organizer2' %}
{% for staffer in organizers %}
{{ staffer }}
{% endfor %}

## Keynote

{% assign keynote = site.instructors | where: 'role', 'Keynote' %}
{% for staffer in keynote %}
{{ staffer }}
{% endfor %}

## Instructors

{% assign instructors = site.instructors | where: 'role', 'Instructor' %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}

{% assign teaching_assistants = site.instructors | where: 'role', 'Teaching Assistant' %}
{% assign num_teaching_assistants = teaching_assistants | size %}
{% if num_teaching_assistants != 0 %}

## Teaching Assistants

{% for staffer in teaching_assistants %}
{{ staffer }}
{% endfor %}
{% endif %}
