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
|   Week 02   |   
|   Week 03   |   Afwerken elevator pitch
|   Week 04   |   Voorstelling elevator pitch      

{%- assign total = 0.0 %}
| Taak            |                                                                                              Tijd |
|-----------------|--------------------------------------------------------------------------------------------------:|
{%- for item in include.timesheet %}
    {%- assign total = total | plus: item.time %}
| {{ item.task }} | {{ item.time | floor }}.{{ item.time | times: 100 | modulo: 100 | plus: 100 | round | split: 1 }} |
{%- endfor %}
|=================|===================================================================================================|
| **Totaal**      | **{{ total | floor }}.{{ total | times: 100 | modulo: 100 | plus: 100 | round | split: 1 }}**     |
{:.table.table--primary}