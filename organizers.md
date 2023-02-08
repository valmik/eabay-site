---
layout: page
title: Organizers
nav_order: 5
description: A list of Bay Area EA organizers
---

## EA East Bay

<div class="area">
  {% assign eb_organizers = site.organizers | where: 'area', 'East Bay' %}
  {% for organizer in eb_organizers %}
  {{ organizer }}
  {% endfor %}
</div>

## EA South Bay

<div class="area">
  {% assign sb_organizers = site.organizers | where: 'area', 'South Bay' %}
  {% for organizer in sb_organizers %}
  {{ organizer }}
  {% endfor %}
</div>


## EA San Francisco

<div class="area">
  {% assign sf_organizers = site.organizers | where: 'area', 'San Fransisco' %}
  {% for organizer in sf_organizers %}
  {{ organizer }}
  {% endfor %}
</div>
