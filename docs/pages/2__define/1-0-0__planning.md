---
layout   : default
permalink: define/planning/
published: true
# Custom Page Variables
# ─────────────────────
title: Planning
---

Titel


|Datum|Opdracht|       
|-----|--------|
|   Week 01   |   Briefing opdracht  |
|   Week 02   |   Museumbezoek
|   Week 03   |   Afwerken elevator pitch/ Feedback
|   Week 04   |   Voorstelling elevator pitch  
|   Week 05   |   Wireframes/flow afwerken  
|   Week 06   |   Screen designs afwerken   

{%- assign total = 0.0 %}
{%- for item in include.timesheet %}
    {%- assign total = total | plus: item.time %}
| {{ item.task }} | {{ item.time | floor }}.{{ item.time | times: 100 | modulo: 100 | plus: 100 | round | split: 1 }} |
{%- endfor %}
{:.table.table--primary}