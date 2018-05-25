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
|   12/02  |   Briefing opdracht  |
|   23/02   |   Museumbezoek
|   06/03  |   Afwerken elevator pitch/ Feedback
|   08/03   |   Voorstelling elevator pitch 
|   15/03   |   Ideaboard aanleggen
|   15/03  |   Werken aan wireframes
|   03/04  |   Wireframes afwerken 
|   12/04  |   Werken aan screen designs
|   18/04  |   Screen designs afwerken  
|   20/04  |  Productiedossier afwerken  
|   05/05   |   Productiedossier afwerken
|   17/05   |   Afwerken
|   24/05   |   Feedback
|   30/05   |   Feedback
|   04/06   |   Indienen en voorstelling opdracht. 

{%- assign total = 0.0 %}
{%- for item in include.timesheet %}
{%- assign total = total | plus: item.time %}
{%- endfor %}
{:.table.table--primary}