---
layout   : default
permalink: define/planning/
published: true
# Custom Page Variables
# ─────────────────────
title: Planning
---

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
{%- endfor %}
{:.table.table--primary}