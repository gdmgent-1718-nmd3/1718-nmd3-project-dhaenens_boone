---
layout   : default
permalink: define/analyse/
published: true
# Custom Page Variables
# ─────────────────────
title: Analyse
---

Beweegredenen voor een museum bezoek
---

|   PRO   |   CONTRA   |
|   ---   |   ---   |
|   Uit **interesse** in een bepaald onderwerp en/of kunstenaar     |   Lange **wachttijden**   |
|   Ter **inspiratie**    |    Dure inkom **prijs**   |
|   Ter **ontspanning**    |   Het museum is niet uitgebreid genoeg   |
|   Om nieuwe kunstenaars en/of kunststijlen te **ontdekken**    |    Het museum is moeilijk bereikbaar   |
|   Mensen leren kennen met **gemeenschappelijke interesses**    |    De persoon is **niet mobiel**   |





{%- assign total = 0.0 %}
{%- for item in include.timesheet %}
{%- assign total = total | plus: item.time %}
{%- endfor %}
{:.table.table--primary}

